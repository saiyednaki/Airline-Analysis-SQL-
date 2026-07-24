# Airline-Analysis-SQL-

# Deutsch

**Analyse der Auslastung und Erlöse im Flugbetrieb**

**Projektüberblick**

Die Luftfahrtbranche sieht sich zunehmendem Druck durch Umweltauflagen, steigende Treibstoffpreise, höhere Steuern und gestiegene Personalkosten ausgesetzt. Diese Faktoren haben die Rentabilität erheblich beeinträchtigt.
Im Rahmen dieses Projekts werden Betriebs- und Erlösdaten analysiert, um Möglichkeiten zur Steigerung der Flugzeugauslastung zu identifizieren. Ziel ist es, den durchschnittlichen Gewinn pro Sitzplatz zu erhöhen, ohne dabei das Kundenerlebnis oder die Sicherheit zu beeinträchtigen.

Der Schwerpunkt der Analyse liegt auf der Untersuchung von Ticketbuchungen, Tarifstrukturen, Flugzeugkapazitäten, Erlösentwicklungen sowie der Auslastung bei verschiedenen Flugzeugtypen.

**Geschäftliche Herausforderung**

- Das Unternehmen betreibt eine gemischte Flugzeugflotte mit unterschiedlichen Sitzplatzkapazitäten und Tarifbedingungen. Trotz stabiler Nachfrage steht die Rentabilität unter Druck, bedingt durch:
- Strengere Umweltauflagen
- Höhere Flugsteuern
- Steigende Treibstoff- und Personalkosten
- Sich wandelnde Kundenpräferenzen
- Um diesen Herausforderungen zu begegnen, strebt das Unternehmen an, die Auslastung bei Flügen mit geringer Performance zu steigern und die Preisstrategien zu optimieren, um den Gesamtumsatz zu erhöhen. 

**Zielsetzungen**

- Steigerung der Auslastung zur Erhöhung des Gewinns pro Sitzplatz
- Analyse von Ticketbuchungen und Umsatztrends im Zeitverlauf
- Vergleich der Preisgestaltung über verschiedene Flugzeugtypen und Tarifklassen hinweg
- Identifizierung leistungsschwacher Flugzeuge und Verbesserungspotenziale
- Abschätzung der Umsatzauswirkungen bei einer Auslastungssteigerung um 10 %

**Tools & Kompetenzen**
- SQL / Datenanalyse
- Aggregationen & KPIs
- Umsatz- und Auslastungsanalyse

**Methodik**
1. Grundlegende Datenanalyse
  - Identifizierung von Flugzeugen mit mehr als 100 Sitzplätzen
  - Analyse der Sitzplatzkapazität nach Flugzeugtyp
  - Berechnung der gebuchten Tickets und Umsatztrends

2. Umsatz- und Preisanalyse
  - Vergleich der durchschnittlichen Ticketpreise nach Tarifklassen
  - Analyse der Umsatzverteilung nach Flugzeugtyp
  - Identifizierung von Preismustern, die die Nachfrage beeinflussen

3. Analyse der Auslastungsquote
  - Berechnung der Auslastungsquote:
  - Auslastungsquote = Gebuchte Sitzplätze / Gesamtzahl der Sitzplätze
  - Vergleich der Auslastung verschiedener Flugzeuge
  - Identifizierung von Flugzeugen mit geringer Auslastung

4. Szenarioanalyse
  - Simulation einer Auslastungssteigerung um 10 %
  - Abschätzung des potenziellen Umsatzwachstums
  - Bewertung der Machbarkeit preisbasierter Verbesserungen

**Wichtige Erkenntnisse**
- Flugzeuge mit niedrigeren Preisen erzielen tendenziell höhere Ticketverkäufe
- Die Preise der Business Class liegen bei allen Flugzeugtypen durchgehend über denen der Economy Class
- Einige Flugzeuge generieren hohe Umsätze aufgrund höherer Nachfrage, nicht aufgrund höherer Preise
- Flugzeuge mit eingeschränkten Tarifoptionen und geringerer Servicequalität erzielen niedrigere Umsätze
- Eine Auslastungssteigerung um 10 % führt zu einem spürbaren und beständigen Umsatzanstieg

**Empfehlungen**
- Optimierung der Preisgestaltung basierend auf Flugzeugzustand, Ausstattung und Nachfrage
- Vermeidung extrem niedriger oder hoher Preise, da beides das Kundeninteresse mindert
- Fokus von Marketing- und Preisstrategien auf Flüge mit geringer Auslastung
- Verbesserung des Kundenerlebnisses zur nachhaltigen Förderung einer höheren Auslastung
- Einsatz datengestützter Preisstrategien anstelle pauschaler Preisanpassungen

**Fazit**

Die Verbesserung der Auslastungsquote ist ein wirksamer Hebel zur Steigerung der Rentabilität einer Fluggesellschaft. Diese Analyse zeigt, dass eine strategische Preisoptimierung und gezielte Verbesserungen den Umsatz erheblich steigern können, ohne die Betriebskosten zu erhöhen.
Ein ausgewogener, datengestützter Ansatz ermöglicht es Fluggesellschaften, wettbewerbsfähig zu bleiben und gleichzeitig die Kundenzufriedenheit sowie Sicherheitsstandards zu wahren.

# English

**Airline Occupancy Rate & Revenue Analysis**

**Project Overview**

The airline industry is facing increasing pressure due to environmental regulations, rising fuel prices, higher taxes, and increased labor costs. These factors have significantly impacted profitability.
This project analyzes airline operational and revenue data to identify opportunities to increase aircraft occupancy rates, thereby improving average profit per seat without compromising customer experience or safety.

The analysis focuses on understanding ticket bookings, fare structures, aircraft capacity, revenue trends, and occupancy performance across different aircraft types.

**Business Problem**

  - The company operates a mixed fleet of aircraft with varying seat capacities and fare conditions. Despite steady demand, profitability is under pressure due to:
  - Stricter environmental regulations
  - Higher flight taxes
  - Rising fuel and labor costs
  - Changing customer preferences
  - To address these challenges, the company aims to increase occupancy rates on low-performing flights and optimize pricing strategies to improve overall revenue.

**Objectives**

  - Increase aircraft occupancy rate to boost profit per seat
  - Analyze ticket bookings and revenue trends over time
  - Compare fare pricing across aircraft and fare classes
  - Identify low-performing aircraft and improvement opportunities
  - Estimate revenue impact of a 10% increase in occupancy

**Tools & Skills**
  - SQL / Data Analysis
  - Aggregations & KPIs
  - Revenue & occupancy analysis

**Methodology**
1. Basic Data Analysis
  - Identified aircraft with more than 100 seats
  - Analyzed seat capacity by aircraft type
  - Calculated total tickets booked and revenue trends

2. Revenue & Pricing Analysis
  - Compared average fare prices across fare classes
  - Analyzed revenue distribution by aircraft
  - Identified pricing patterns influencing demand

3. Occupancy Rate Analysis
  - Calculated occupancy rate as:
  - Occupancy Rate = Booked Seats / Total Seats
  - Compared occupancy performance across aircraft
  - Identified underutilized aircraft

4. Scenario Analysis
  - Simulated a 10% increase in occupancy rate
  - Estimated potential revenue growth
  - Assessed feasibility of pricing-based improvements

**Key Insights**
  - Aircraft with lower fares tend to achieve higher ticket sales
  - Business class fares are consistently higher than economy across all aircraft
  - Some aircraft generate high revenue due to higher demand, not higher prices
  - Aircraft with limited fare options and lower service quality show lower revenue
  - A 10% increase in occupancy results in a noticeable and consistent revenue increase

**Recommendations**
  - Optimize pricing based on aircraft condition, facilities, and demand
  - Avoid extremely low or high pricing, as both reduce customer interest
  - Focus marketing and pricing efforts on low-occupancy flights
  - Improve customer experience to support higher occupancy sustainably
  - Use data-driven pricing strategies rather than uniform fare adjustments

**Conclusion**

Improving occupancy rates is a powerful lever for increasing airline profitability. This analysis demonstrates that strategic pricing optimization and targeted improvements can significantly boost revenue without increasing operational costs.
A balanced, data-driven approach enables airlines to remain competitive while maintaining customer satisfaction and safety standards.
