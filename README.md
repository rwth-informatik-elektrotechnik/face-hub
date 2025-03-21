# face-hub
Face Recognition/Detection

Projekt: Gesichtserkennungssystem mit C++
Technologien: C++, OpenCV, Dlib
Teamgröße: 3 Personen
Dauer: 3 Monate
Ziel: Ein System entwickeln, das Gesichter erkennen, speichern und unterscheiden kann (Detection + Recognition).

Person A	Gesichtserkennung (Face Detection) – OpenCV + Dlib
Person B	Gesichtswiedererkennung (Face Recognition) – Dlib Deep Learning
Person C	Datenverwaltung & Benutzeroberfläche (UI + Speicherung)

📅 Monat 1: Grundlagen & Einzeln arbeiten (Theorie + Setup)

Ziel: Alle bereiten ihre eigene Arbeitsumgebung vor und lernen ihre Tools kennen.
  
  Woche 1:
   
    Person A:
    
      Was ist Face Detection? Verschiedene Algorithmen (Haar, HOG, CNN) recherchieren	
    
    Person B:
    
      Was ist Face Recognition? LBPH, Dlib, Deep Learning vergleichen	
    
    Person C:
    
      Wie speichert man Bilddaten und Metadaten? JSON, XML, kleine DB-Optionen


  Woche 2:
  
    Person A:
  
      OpenCV Installation & erstes Bild laden
 
    Person B:
  
      Dlib Installation & Beispielcode zum Laden von Bildern	
  
    Person C:
  
      C++ GUI-Optionen recherchieren (z. B. Qt, OpenCV UI)

  Woche 3:

    Person A:
  
      Haarcascade Detection in C++ implementieren	
  
    Person B:
  
      LBPH und Dlib face recognition Beispielcode testen	
  
    Person C:
  
      Erstes Interface-Layout skizzieren, Konsoleninterface programmieren

  Woche 4:

    Person A:
  
      Kamera einbinden, Echtzeit-Face Detection testen	
  
    Person B:
  
      Erste Gesichter erkennen lassen (auch mit Testbildern)
  
    Person C:
  
      Datenspeicherung vorbereiten (z. B. Bilder + Namen speichern)


📅 Monat 2: Modulentwicklung (eigenständig)
Ziel: Jeder entwickelt ein vollständiges Modul unabhängig vom anderen.
  Woche 5:
    Person A:
      Haarcascade vs. Dlib HOG vergleichen, eigenes Detection-Modul bauen		
    Person B:
      Gesichtsembeddings erzeugen (128-D Feature Vektor mit Dlib)		
    Person C:
      Erste Version: Gesichtsinfos lokal speichern & laden
Woche 6:
  Person A:
    Gesichter tracken (z. B. mit Rechteck verfolgen)	
  Person B:
    Eigene Bilddatenbank anlegen und Trainieren (Eigenes Dataset)	
  Person C:
    Eingabemaske für neue Nutzer (Gesicht + Name) erstellen
Woche 7:
  Person A:
    Fehlerbehandlung & stabile Gesichtserkennung implementieren	
  Person B:
    Vergleich zweier Gesichter (Ähnlichkeitsvergleich)
  Person C:
    Datensatz-Verwaltung + Nutzerverwaltung
Woche 8:
  Person A:
    Modul mit sauberen Schnittstellen abschließen	
  Person B:
    Modul fertigstellen, JSON-Export von Gesichtsdaten	
  Person C:
    UI mit Datenmodul verbinden, Bild anzeigen können

📅 Monat 3-4: Integration, Optimierung, Abschluss
Ziel: Module zusammenfügen, testen, präsentieren.

Woche 9	  Schnittstellen festlegen: Wie übergibt Detection Modul Daten an Recognition Modul?
Woche 10	Alle Module zusammenführen (Detection → Recognition → UI)
Woche 11	Testen mit realen Bildern / Kamera. Genauigkeit und Geschwindigkeit messen.
Woche 12	Optimierungen, README schreiben, GitHub Repository fertigstellen, optional Video-Demo oder Präsentation vorbereiten.


✅ Endziel nach 3 Monaten
Ein C++-basiertes Gesichtserkennungssystem mit:
Echtzeitkameraunterstützung
Gesichtserkennung und -unterscheidung
Benutzeroberfläche zur Verwaltung von Gesichtern
Dokumentierter, verständlicher Code auf GitHub
Lauffähige Demo mit Testdaten
