
# Telco Customer Churn Prediction


## Beschreibung

Dieses Projekt analysiert den **Telco Customer Churn**-Datensatz, um vorherzusagen, ob ein Kunde seinen Vertrag kündigen wird. Die Vorhersage der Kundenabwanderung ist für Telekommunikationsunternehmen entscheidend, um die Kundenzufriedenheit zu verbessern und Verluste zu vermeiden.

### Datensatzübersicht

- Der Datensatz enthält Informationen über **7.043 Kunden** eines fiktiven Telekommunikationsunternehmens in Kalifornien.
- Jede Zeile repräsentiert einen Kunden sowie dessen Services, demografische Daten, Vertragsinformationen und ob der Kunde abgewandert ist.

**Wichtige Merkmale:**
- Demografie: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- Services: `PhoneService`, `InternetService`, `OnlineSecurity`, `TechSupport` usw.
- Vertragsinformationen: `tenure`, `Contract`, `MonthlyCharges`, `TotalCharges`
- Zielvariable: `Churn`

### Hauptschritte

1. **Datenbereinigung:** Umgang mit fehlenden oder fehlerhaften Werten, Typkonvertierungen und Dublettenprüfung.
2. **Explorative Datenanalyse (EDA):** Visualisierung der Churn-Verteilung, Korrelationen und Kundenverhalten.
3. **Vorverarbeitung:** Kodierung kategorialer Merkmale, Skalierung numerischer Daten.
4. **Modellierung:** Einsatz von ML-Modellen wie logistischer Regression oder Random Forest zur Vorhersage.
5. **Evaluation:** Genauigkeit, Präzision, Recall, Konfusionsmatrix und ROC-Kurve zur Leistungsbewertung.

### Verwendete Tools & Technologien

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn