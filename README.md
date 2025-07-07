## Einrichtungsschritte für ThingsBoard & ChirpStack

1. **User anlegen**
2. **ThingsBoard Rule Chains importieren**
3. **Rulechain-Verknüpfungen anpassen**
4. **ChirpStack API Token generieren** (in ChirpStack)
    - In der ThingsBoard Downlink Rulechain folgenden Header anpassen:
      - **Header:** `authorization`
      - **Value:** `Bearer "YOUR_API_TOKEN"`
5. **Dashboards importieren**
6. **Device Profile anlegen**
7. **Device erstellen**
8. **Server Attributes anlegen**
    - siehe Ordner `tb-devices`
9. **Access Token kopieren**
    - In ChirpStack für das Device eine Variable `ThingsBoardAccessToken` anlegen und als **Value** den ThingsBoard Access Token eintragen
