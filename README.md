Installation der Entwickungsumgebung und Projektübertragung
-----------------------------------------------------------

Installation auf Windows
------------------------
1. Android Stuio installieren.
2. GitHub Zugang anlegen.
3. Git auf dem Rechner installieren. ( Es kann vorab im Terminal geprüft werden, ob eine git Version bereits installiert ist. Befehl: git --version. Wenn eine Version angezeigt wird ist Git bereits installiert.)
4. Unter GitHub das Repository DemenzKalenderApp suchen und clonen.
5. Überprüfen, ob GitHub mit Android Studio verknüpft ist. (Android Studio Einstellungen -> Version Control -> Git -> Prüfen, ob der Pfad für Git vorhaden ist)
6. GitHub Projekt zu Android Studio hinzufügen über 'Get from VCS' -> Projekt URL (geklontes Repository) eingeben  

Installation auf MacOS
----------------------
1. Bevor Android Studio installliert werden kann müssen die Developer Tools in den Systemeinstellungen installiert werden, um die 'Xcode command line tools' nutzen zu können.
   Einstellungen -> Allgemein -> Softwareupdate oder im Terminal xcode-select --install
2. GitHub Zugang anlegen.
3. Git auf dem Rechner installieren. ( Es kann vorab im Terminal geprüft werden, ob eine git Version bereits installiert ist. Befehl: git --version. Wenn eine Version angezeigt wird ist Git bereits installiert.)
4. Unter GitHub das Repository DemenzKalenderApp suchen und clonen.
5. Überprüfen, ob GitHub mit Android Studio verknüpft ist. (Android Studio Einstellungen -> Version Control -> Git -> Prüfen, ob der Pfad für Git vorhaden ist)
6. GitHub Projekt zu Android Studio hinzufügen über 'Get from VCS' -> Projekt URL (geklontes Repository) eingeben   

Hilfe bei häufigen Fehlermeldungen in Android Studio
---------------------------------------------------
1. Bei Problemen mit der Gradle Version im Ordner gradle/wrapper/gradle-wrapper.proberties die Version von 8.6 auf 8.7 ändern.
   -> distributionUrl=https\://services.gradle.org/distributions/gradle-8.7-bin.zip
   
2. SDK fehlt ( richtiger SDK Pfad ist aber angegeben)
   -> Einstellungen -> SDK Manager -> Edit -> Next -> Next -> Finish
   -> SDK Pfad wird wieder gefunden
