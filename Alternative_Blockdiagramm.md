```mermaid
block-beta
  columns 4

  block **Umschulung** "Umschulung Fachinformatiker Anwendungsentwicklung (IHK)" {
    A["Software &<br/>Programmierung"]
    B["Datenbanken &<br/>Datenmanagement"]
    C["Systeme &<br/>Netzwerke"]
    D["Wirtschaft &<br/>Management"]
    E["Prüfungen &<br/>Zertifikate"]
  }

  block "Details: Software" {
    columns 2
    A1>"Grundlagen<br/>mit Python"
    A2>"OOP"
    A3>"UML-Design"
    A4>"GUI"
  }
  
  block "Details: Datenbanken" {
    B1>"DB-Design"
    B2>"SQL"
  }

  block "Details: Systeme" {
    C1>"Netzwerktechnik"
    C2>"Linux-Dienste"
    C3>"IT-Sicherheit"
    C4>"Hardware"
  }

  block "Details: Wirtschaft" {
    D1>"BWL"
    D2>"Projektplanung"
    D3>"Kundenbeziehung"
  }
  
  block "Details: Abschlüsse" {
    E1>"IHK Prüfung 1+2"
    E2>"Abschlussprojekt"
    E3>"AWS Zertifikat"
  }

  A -- "beinhaltet" --> A1
  A -- "beinhaltet" --> A2
  A -- "beinhaltet" --> A3
  A -- "beinhaltet" --> A4
  B -- "beinhaltet" --> B1
  B -- "beinhaltet" --> B2
  C -- "beinhaltet" --> C1
  C -- "beinhaltet" --> C2
  C -- "beinhaltet" --> C3
  C -- "beinhaltet" --> C4
  D -- "beinhaltet" --> D1
  D -- "beinhaltet" --> D2
  D -- "beinhaltet" --> D3
  E -- "beinhaltet" --> E1
  E -- "beinhaltet" --> E2
  E -- "beinhaltet" --> E3