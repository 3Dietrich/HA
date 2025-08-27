```mermaid
graph LR
    subgraph "Umschulung: Fachinformatiker Anwendungsentwicklung (IHK)"
        A["Softwareentwicklung & Programmierung"]
        B["Datenbanken & Datenmanagement"]
        C["Systeme, Netzwerke & IT-Sicherheit"]
        D["Wirtschaftliche & Betriebliche Prozesse"]
        E["Projektmanagement & Methoden"]
        F["Zertifikate & Prüfungen"]
    end

    subgraph "Kompetenzbereich A: Softwareentwicklung"
        A --> A1("Programmiergrundlagen mit Python")
        A --> A2("Moderne Software mit modularen, wiederverwendbaren Bausteinen entwickeln (OOP)")
        A --> A3("Visuelle Planung und Dokumentation von Softwaresystemen (UML)")
        A3 --> A3a("Baupläne für Software entwerfen (Klassendiagramme)")
        A3 --> A3b("Benutzeranforderungen & Systemabläufe grafisch darstellen (Anwendungsfall-, Aktivitätsdiagramme)")
        A --> A4("Benutzerschnittstellen gestalten und entwickeln (GUI)")
        A --> A5("Funktionalität in Anwendungen realisieren")
    end

    subgraph "Kompetenzbereich B: Datenbanken"
        B --> B1("Konzepte zur strukturierten Datenspeicherung (Relationale DBs)")
        B --> B2("Daten systemübergreifend bereitstellen und abfragen (SQL)")
        B --> B3("Software zur Verwaltung von Daten anpassen")
    end

    subgraph "Kompetenzbereich C: Systeme & Sicherheit"
        C --> C1("Grundlagen der Netzwerktechnik (LAN, WAN, OSI-Modell)")
        C --> C2("Clients in Netzwerke einbinden")
        C --> C3("Netzwerke und Dienste unter Linux bereitstellen")
        C --> C4("Grundlagen PC-Hardware, Betriebssysteme und Virtualisierung")
        C --> C5("Themen der IT-Sicherheit & angewandter Datenschutz")
        C --> C6("Schutzbedarfsanalysen durchführen")
        C --> C7("Grundlagen der Digitaltechnik und logischer Schaltungen")
        C --> C8("Systeme entwickeln, die Informatik mit mechanischen/elektronischen Prozessen verbinden (Cyberphysische Systeme)")
    end

    subgraph "Kompetenzbereich D: Wirtschaft & Betrieb"
        D --> D1("Das Unternehmen und die eigene Rolle im Betrieb beschreiben")
        D --> D2("Betriebswirtschaftliche Organisation")
        D --> D3("Kunden- und Serviceanfragen bearbeiten")
        D --> D4("Marktbeobachtung, Marketing und Rechnungswesen")
        D --> D5("Wirtschafts- und Sozialkunde (WISO)")
    end

    subgraph "Kompetenzbereich E: Projektmanagement"
        E --> E1("Projektpläne erstellen und Methoden zur zeitlichen Planung anwenden (Netzplantechnik)")
        E --> E2("Qualitätsmanagement")
        E --> E3("Handlungskompetenzen eines IT-Berufes")
        E --> E4("Englisch (Leseverstehen & technisches Englisch)")
    end

    subgraph "Kompetenzbereich F: Abschlüsse"
        F --> F1("Gestreckte Abschlussprüfung Teil 1 & 2 (IHK)")
        F --> F2("Betriebliches Abschlussprojekt (Planung, Doku, Präsentation)")
        F --> F3("Herstellerzertifikat: AWS Cloud (fakultativ)")
        F --> F4("Sprachzertifikat: LanguageCert Test of English (fakultativ)")
    end

    style A fill:#f9f,stroke:#333,stroke-width:2px,color:#000
    style B fill:#ccf,stroke:#333,stroke-width:2px,color:#000
    style C fill:#9cf,stroke:#333,stroke-width:2px,color:#000
    style D fill:#f99,stroke:#333,stroke-width:2px,color:#000
    style E fill:#9c9,stroke:#333,stroke-width:2px,color:#000
    style F fill:#fc9,stroke:#333,stroke-width:2px,color:#000
