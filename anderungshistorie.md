# Änderungshistorie

Die folgenden Änderungen sind in die bestehende Version eingearbeitet, mit den neuesten Änderungen am Anfang der Liste.

**Januar 2026 - IN ARBEIT!**

Im Laufe des Jahres 2025, vor allem im Herbst / Winter, wurden einige Änderungen an der Datenbank durchgeführt. Diese Änderungen **werden aktuell in das Handbuch eingepflegt** und betreffen vor allem die folgenden Bereiche:

* Bewerbe anlegen (Bearbeiten, Dokumente, Nennungen)
* Bewerbe auswerten Boulder (Wechselmodus, Team Wertungen)
* Verfügbare Bewerbsmodi (Wechselmodus, Boulder und Lead)
* Ranking/Gesamtwertung

**10.01.2025**

Boulder Punktemodus wurde eingefügt (neu lt. IFSC Rules 2025). In diesem Zusammenhang gab es einige Änderungen bei den Einstellungen für Boulderbewerbe (Durchführungsmodus vs. Auswertungsmodus).

Dadurch entsteht zusätzliche Felxibilität: Anzahl der Zonen (1 / 2), Punkte für Zone und Top, Abzug pro Versuch sind frei wählbar.

<figure><img src=".gitbook/assets/Bildschirmfoto 2025-01-10 um 09.40.33.png" alt=""><figcaption></figcaption></figure>

**23.12.2024**

* E-Mails aus dem System (Admin Bewerbsoberfläche): Hier wurde die Möglichkeit hinzugefügt, dass man für die ausgesendeten E-Mails eine Return-Adresse eingibt. Hier ist standardmäßig die Mail-Adresse eingetragen, die auch in den Bewerbs-Details hinterlegt ist. Wenn Teilnehmer:innen auf die Nachricht antworten, die ihr aussendet, geht diese Anwort an die hier hinterlegte Mail Adresse.

<figure><img src=".gitbook/assets/Bildschirmfoto 2024-12-24 um 10.26.58.png" alt=""><figcaption></figcaption></figure>

**12.12.2024**

* **Wechselmodus-Listen flexibler:** Im Finale eines Boulder-Bewerbs können bei den Startlisten eine spezielle Startliste und Judges-Liste für den Wechselmodus kreiert werden. Nun funktionieren diese Listen auch dann, wenn nicht 8 Athlet:innen im Finale sind. Die Listen werden an die tatsächliche Anzahl an Finalist:innen angepasst. An der Eingabe für den Auswerter im Backend ändert sich aber nichts. Achtung: Reihenfolge der Finalist:innen im Backend stimmt nicht mit Startreihenfolge im Wechselmodus überein!
* **Auswerter:innen können alle Personen in ihrem Bewerb bearbeiten** (Name, Geburtsdatum, Verein). Änderungen in den Stammdaten werden zur Überprüfung automatisch an den KVÖ gesendet.\
  In den linken Spalten wird der/die Athlet:in nur für den aktuellen Bewerb bearbeitet, in der rechtesten Spalte kann man das Datenblatt aufrufen und die Daten dauerhaft ändern. Achtung: Änderungen werden nicht automatisch auch für anderen Bewerbe übernommen, bei denen der/die Athlet:in genannt ist. (Screenshot aus Auswertungsoberfläche - Nennungen)

<figure><img src=".gitbook/assets/Bildschirmfoto 2024-12-19 um 11.33.58.png" alt=""><figcaption></figcaption></figure>

#### 24.10.2024

* Standardmäßig benötigt ein Bewerb keine medizinischen Zertifikate. Kann aber aktiviert werden unter Bewerb - Bearbeiten:

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

* Im Kalender gibt es eine neue Ansicht, die das gesamte Jahr mit allen Bewerben (je nach Auswahl oben) übersichtlich anzeigt.

<figure><img src=".gitbook/assets/image (2).png" alt="" width="375"><figcaption></figcaption></figure>

#### 11.10.2024

* Alle Wettkampflisten können jetzt auch mit EInstellungen versehen werden (Querformat / Hochformat, Verein ja/nein, ...)
*   Alle Wettkampflisten können nicht nur ein bestimmte, sondern mehrere Bewerbsklassen anzeigen\\

    <figure><img src=".gitbook/assets/image (3).png" alt="" width="375"><figcaption></figcaption></figure>

#### 10.10.2024

* Alle Datagrids im Scoringbereich können jetzt nach StNr durchsurcht werden, nicht nur Athletennamen
* Ergebnisse können jetzt nachträglich ganz gelöscht werden
*   Ergebnisse können jetzt auch nach Problemen durchsucht werden (z.B. doppelte Bibs)\\

    <figure><img src=".gitbook/assets/image (4).png" alt="" width="375"><figcaption></figcaption></figure>

#### 1.10.2024

* Ein User kann jetzt mehrere Vereine oder Bundesländer gleichzeitig administrieren

#### 11.9.2024

*   User sehen jetzt welche anderen User einer verknüpften Person zugeordnet sind\\

    <figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>
*   User können keine Personen mehr verknüpfen, welche bereits alleinig verknüpft sind

    <figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>
*   Dafür können User andere User zu ihrem bereits verknüpften Personen hinzufügen\\

    <figure><img src=".gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

#### 26.4.2024

* Automatisch generierte Ergebnis PDFs können ausgeblendet werden

<figure><img src=".gitbook/assets/image (26).png" alt="" width="375"><figcaption></figcaption></figure>

*   Bei performancebasiertem Scoring ist die Einstellung, ob Versuche gezählt werden sollen, nicht mehr unter Optional eingeordnet

    <figure><img src=".gitbook/assets/image (27).png" alt="" width="375"><figcaption></figcaption></figure>
* KVÖ bekommt Email wenn sich ein Offizieller verfübar meldet für einen Wettkampf
*   Athleten bekommen in der Bestätigungsemail zu einem Bewerb auch den Status ihres medizinischen Zertifikats mitgeteilt

    <figure><img src=".gitbook/assets/image (28).png" alt="" width="256"><figcaption></figcaption></figure>
* Nennungen und Einladungen im Adminbereich zeigen die Kaderzugehörigkeit an
*   Kaderlisten können jetzt exportiert werden\\

    <figure><img src=".gitbook/assets/image (29).png" alt="" width="221"><figcaption></figcaption></figure>
*   Kader können jetzt zu einem Event gesammelt eingeladen oder genannt werden\
    \\

    <figure><img src=".gitbook/assets/image (30).png" alt="" width="375"><figcaption></figcaption></figure>

#### 16.4.2024

* Link zur Online-Doku eingebaut in Sidebar
* Nennungen können exportiert und importiert werden

#### 2.4.2024

* Nennlisten und Ergebnisse im Frontend können nach Sektion gefiltert werden
* Kopfzeile bei Auswertungsgerätezuordnung "sticky"
* Anzahl Zonnen konnte bei Boulder Jam Scoring Modus nicht eingegegeben werden
* Laufzettel hat jetzt größere Kästchen bei wenigen Boulder und ist jetzt 1/3 Din A4 hoch
* Möglichkeit zur Nennung wurde nicht angezeigt im Frontend wenn ein Bewerb mehreren Kategorien zugeordnet war

#### 19.3.2024

* Vereine können jetzt als "gelöscht" markiert werden und scheinen dann in den Auswahlen nicht mehr auf

#### 18.3.2024

* Lead Live Scoring geänderte Reihenfolge: Klasse -> Runde -> Route

#### 6.3.2024

*   Bei Modus "Performance Based" kann man auswöhlen ob Versuche gewertet werden sollen oder nicht (und einen Tie brechen)\\

    <figure><img src=".gitbook/assets/image (8).png" alt="" width="375"><figcaption></figcaption></figure>
* Startnmummern für den Laufzettel Ausdruck können jetzt markiert werden in der Liste

#### 5.3.2024

*   Eine Zuordnung zwischen Judge/Tablet und Boulder (Linien) in unterschiedlichen Klassen kann erstellt werden:\\

    <figure><img src=".gitbook/assets/image (22).png" alt="" width="375"><figcaption></figcaption></figure>
*   Scoring für dieses Gerät und den zugehörigen Klassen/Bouldern (Linien) kann hier aufgerufen werden: \\

    <figure><img src=".gitbook/assets/image (23).png" alt="" width="375"><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (24).png" alt="" width="375"><figcaption></figcaption></figure>

#### Ältere Einträge

*   Anzahl der Zonen kann jetzt auch im Weltcupmodus auf 2 gesetzt werden (anstatt B\&L Modus zu verwenden)\\

    <figure><img src=".gitbook/assets/image (21).png" alt="" width="563"><figcaption></figcaption></figure>
*   Startzeitenliste und Judges-Form für Wechselmodus\\

    <figure><img src=".gitbook/assets/image (16).png" alt="" width="375"><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

    <figure><img src=".gitbook/assets/image (20).png" alt=""><figcaption></figcaption></figure>
*   Auslosungsgruppe, Startgruppe, Startposition und Bib könne jetzt aus Excel importiert werden\\

    <figure><img src=".gitbook/assets/image (9).png" alt="" width="375"><figcaption></figcaption></figure>
* LiveScoring für Boulder Jams optimiert zur Ergebnis-Eingabe.
* In B\&L Bewerben kann nur noch B\&L als Scoringmodus gewählt werden.
* Wenn der Scoringmodus einer Runde geändert wird, dann aktualiseren sich jetzt auch die zugehörigen anderen Eigenschaften.
* Auswerter haben jetzt Zugriff auf Logos.
*   die Kopfzeilen von Bewerbe können jetzt Skripte enthalten und standardmäßig das Datum und den Ort anzeigen auf den PDF Listen.\
    `{{ date.to_string event.begin "%d. %B %Y" }}, {{ event.location }}`\\

    <figure><img src=".gitbook/assets/image (15).png" alt="" width="375"><figcaption></figcaption></figure>
*   Für Testzwecke können jetzt Dummy-Athleten für einen Bewerb registriert werden.\\

    <figure><img src=".gitbook/assets/image (14).png" alt="" width="375"><figcaption></figcaption></figure>
* Auswerter können sich jetzt analog zu Routensetzern oder Judges für Bewerbe verfügbar melden.
*   Die Einteilung von Offiziellen zu Bewerben kann jetzt als abgeschlossen markiert werden.\\

    <div><figure><img src=".gitbook/assets/image (10).png" alt="" width="375"><figcaption></figcaption></figure> <figure><img src=".gitbook/assets/image (11).png" alt="" width="375"><figcaption></figcaption></figure></div>
