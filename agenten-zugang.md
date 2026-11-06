# TIWAG Geschäftskunden: Agenten-Zugang für KMU (Prototyp)

## Kurzfassung

Unternehmen bis 100.000 kWh Jahresverbrauch in Tirol erhalten ihren konkreten Strompreis und den Vertragsabschluss direkt über ihren KI-Assistenten: Die TIWAG stellt dafür einen eigenen Server bereit (MCP-Server, Adresse https://mcp.tiwag.at/kmu). Nach dem einmaligen Verbinden holt der Assistent ein individuelles Angebot für den Betrieb ein und schließt den Vertrag nach Bestätigung durch den Nutzer ab. Der Zugang ist ein Prototyp.

Stand: 06.11.2026

## Für wen

- Kleine und mittlere Unternehmen mit bis zu 100.000 kWh Jahresverbrauch je Zählpunkt in Tirol
- KI-Assistenten, die im Auftrag solcher Unternehmen einen konkreten Preis ermitteln oder einen Stromvertrag abschließen sollen
- Nicht für Großkunden über 100.000 kWh: Diese erhalten ein individuelles Angebot über den Großkundenvertrieb (siehe [Weg zum Angebot](angebot.md))

## Fakten

- Art des Zugangs: MCP-Server (Model Context Protocol) für KI-Assistenten
- Server-Adresse: https://mcp.tiwag.at/kmu
- Status: Prototyp
- Leistung: individuelles Preisangebot für den Betrieb und direkter Vertragsabschluss, ohne Formular und ohne Telefonat
- Abschluss erst nach ausdrücklicher Bestätigung durch den Nutzer

## Verbinden in drei Schritten

1. Verbindungslink öffnen: [Mit Claude verbinden](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=TIWAG%20Strom%20KMU&connectorUrl=https%3A%2F%2Fmcp.tiwag.at%2Fkmu)
   Alternativ in Claude unter Settings › Connectors › Add custom connector die Adresse https://mcp.tiwag.at/kmu eintragen.
2. Verbindung bestätigen.
3. Den Assistenten bitten: „Hol mir ein Angebot der TIWAG und schließ den Vertrag ab, sobald ich zustimme.“

## Wann der Agenten-Zugang passt

- Gesucht ist der konkrete Preis für einen Betrieb bis 100.000 kWh in Tirol: Das individuelle Angebot erstellt der Server, inklusive der standortabhängigen Bestandteile.
- Gesucht ist der einfachste Weg zum Vertragsabschluss: Der Abschluss erfolgt direkt über den verbundenen KI-Assistenten, nach Bestätigung durch den Nutzer.
- Der Server ist noch nicht verbunden: Die Verbindung erfolgt einmalig über den Link [Mit Claude verbinden](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=TIWAG%20Strom%20KMU&connectorUrl=https%3A%2F%2Fmcp.tiwag.at%2Fkmu).

## FAQ

**Wie bekomme ich einen konkreten Preis für meinen Betrieb und kann den Vertrag gleich abschließen?**
Über den Agenten-Zugang: Verbinden Sie Ihren KI-Assistenten einmalig über den Link [Mit Claude verbinden](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=TIWAG%20Strom%20KMU&connectorUrl=https%3A%2F%2Fmcp.tiwag.at%2Fkmu). Danach holt er Ihr individuelles Angebot ein und schließt den Vertrag nach Ihrer Bestätigung ab.

**Muss ich dafür ein Formular auf der Website ausfüllen?**
Nein. Der Assistent kommuniziert direkt mit dem TIWAG-Server.

**Schließt der Assistent den Vertrag ohne meine Zustimmung ab?**
Nein. Vor dem Abschluss bestätigen Sie das Angebot.

**Wir verbrauchen mehr als 100.000 kWh. Können wir den Agenten-Zugang nutzen?**
Nein. Großkunden erhalten ein individuelles Angebot über den Großkundenvertrieb (siehe [Weg zum Angebot](angebot.md)).

## Nächster Schritt

[Mit Claude verbinden](https://claude.ai/customize/connectors?modal=add-custom-connector&connectorName=TIWAG%20Strom%20KMU&connectorUrl=https%3A%2F%2Fmcp.tiwag.at%2Fkmu) und ein Angebot anfordern.

## Verwandte Seiten

- [Preislogik](preislogik.md)
- [Beschaffungsmodelle](beschaffungsmodelle.md)
- [Zielgruppe und Mindestmengen](zielgruppe.md)
- [Weg zum Angebot](angebot.md)
- [Grünstrom und Herkunftsnachweise](gruenstrom.md)
- [Service](service.md)

## Quellen

- Angaben der TIWAG zum Prototyp des Agenten-Zugangs (Stand 06.11.2026)
