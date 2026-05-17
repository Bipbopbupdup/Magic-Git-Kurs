# Plan zur Sitzung: GitHub Crash-Kurs​

## Ziele der Sitzung 

- Git installieren, konfigurieren und einrichten. 
- Wichtige **Grundbefehle** von Git kennenlernen und anwenden. 
- Ein grundlegendes Verständnis für Versionskontrolle mit Git entwickeln. 
- Berührungsängste abbauen: Git bald selbstbewusst im Studium nutzen können. 
- Offene Fragen der Teilnehmenden klären. 

---

## Git konfigurieren 

die configuration von git findet vor dem Kurs statt.

Teilnehmer werden mit Hilfe einer Anleitung (git repo)
auf schon existierende tutorials weiter geleitet.
Auf der installations Anleitung steht wie man teste kann ob die configuration erfolgreich war.
Es wird drauf hingewiesen das man bei fragen den tutor kontaktieren kann sowie das auch ein help-desk der for dem Kurs beginn angeboten wird

---

## 1. Begrüßung und Einstieg 

**Ziele:** 

- Überblick über den Kurs geben. 
- Erwartungen, Fragen und mögliche Probleme der Teilnehmenden sammeln. 
- Klar machen, dass Rückfragen und Zwischenfragen jederzeit erwünscht sind. 

**Ablauf:** 

- Kurze Vorstellungsrunde (wer ist da, welche Vorerfahrungen mit Git?). 
- Mit Tafel oder Oncoo Fragen, Erwartungen und Vorerfahrungen sammeln. 
- Ablauf der Sitzung und Lernziele vorstellen. 
- Kurz nachfragen, wie es den Teilnehmenden geht und welche Themen ihnen besonders wichtig sind. 

**Materialien:** Präsentation, Tafel oder Oncoo. 

---

## 2. Thematische Einleitung: Was ist Versionskontrolle? 

**Ziele:** 

- Verstehen, was Versionskontrolle ist und wozu sie dient. 
- Unterschied zwischen Git (Tool) und GitHub (Plattform) klären. 
- Neugier und Motivation für Git wecken. 

**Ablauf:** 

- Einstiegsfrage ins Plenum: „Ihr seid in einer 5er-Gruppe bei einem Game Jam – wie arbeitet ihr gemeinsam an eurem Code?“ 
- Begriffe sammeln und von dort zur Idee von Versionskontrolle überleiten.     
- Gemeinsam klären: „Was könnte Versionskontrolle sein?“ und „Was ist der Unterschied zwischen Git und GitHub?“
- Kollaboratives Notizen-Schreiben mit Git als roten Faden für die Sitzung ankündigen mit einem focus auf Mathe. (verbal ein bringen)

**Materialien:** Präsentation. 

---

## 3. Zentrale Git-Konzepte 

**Ziele:** 

- Ein erstes Git-Repository erstellen. 
- Den Aufbau von Git verstehen (Working Directory, Staging Area, Repository, Remote). 
- Verstehen, was ein Commit ist. 

**Ablauf:** 

- Kontext setzen: „Wir erstellen gemeinsam ein kleines Markdown-Notizprojekt fuer mathe.“ 
- Live zeigen, wie man auf GitHub ein neues Repository erstellt (ohne README). 
- Aufbau von Git erklären: Working Directory, Staging Area, lokales Repository, Remote. 


**Materialien:** Präsentation, GitHub im Browser. 

---

## 4. Die ersten Git-Basics 

**Ziele:** 

- Vier zentrale Git-Befehle kennenlernen: `status`, `add`, `commit`, `push`.     
- Eine leere Markdown-Datei mit dem Namen „Aussagenlogik.md“ erstellen. 

**Ablauf:** 

- Die vier Befehle zunächst nur vom Namen her vorstellen. 
- Dann mit der Methode **Predict → Try → Explain** arbeiten:
    - Frage an die Gruppe: „Was denkt ihr, macht der Befehl `git status`?“
    - Befehl gemeinsam ausprobieren.
    - Ergebnis und Bedeutung gemeinsam besprechen. 
- In dieser Reihenfolge weitergehen: `status` → `commit` (Fehlermeldung ohne `add`) → `add` → `commit` → `push`. 
- Die Aufgaben live gemeinsam mit den Teilnehmenden am Beamer mitmachen. 
- Zum Abschluss das Zusammenspiel der Befehle noch einmal visuell darstellen (Pfeildiagramm) und die befehle nochmal mit Erklärung zeigen

**Materialien:** Präsentation, Terminal/VS Code. 

---

## 5. Gruppenarbeit 1: Konflikte verstehen 

**Ziele:** 

- In 2er-Gruppen arbeiten und kollaboratives Arbeiten erleben. 
- `git pull` kennenlernen und anwenden. 
- Einen Merge-Konflikt bewusst herbeiführen und im Editor lösen. 

**Ablauf:** 

- 2er-Gruppen bilden, Rollen erklären: eine Person ist „Driver“ (tippt), die andere „Navigator“ (denkt mit). 
- Das Repository der Navigator-Person wird vom Driver geklont. 
- Beide erstellen nun im Repository eine `README.md` mit einer kurzen Beschreibung des Projekts „Mathe-Notizen“. 
- Dabei Markdown-Formatierung kurz zeigen und dabei alle bisher kennengelernten Git-Befehle plus `git pull` wiederholt zeigen. 
- Beide führen mehrere Commits oder einen Commit durch und pushen diese, anschließend wird vom jeweils Navigator gepullt. 
- jetzt arbeite jeder wieder am eigen Gerät.
- Nun schreibt jede Person in die Datei „Aussagenlogik.md“ eine Definition von „Aussage“ in Zeile 10.     
- Beide pushen ihre Änderungen – ein Konflikt entsteht. 
- Der Merge-Konflikt wird im Editor (VS Code, nvim, vim oder nano) gemeinsam gelöst. 
- Bei Bedarf Aufgaben vorne am Beamer vormachen und in den Gruppen unterstützen. 

**Materialien:** Präsentation, VS Code oder anderer Editor. 

---

## 6. Gruppenarbeit 2: Arbeiten mit Branches 

**Ziele:** 

- Verstehen, was Branches sind und warum sie hilfreich sind. 
- Einen Branch erstellen, darauf arbeiten und ihn pushen.     
- Einen Pull Request anlegen und mergen. 
- Parallelisiertes Arbeiten im Team verstehen. 

**Ablauf:** 

- Einstieg: „Konflikte lassen sich nie ganz vermeiden, aber wir können sie mit Branches reduzieren.“ 
- Visuelle Erklärung: Was ist ein Branch, was „verzweigt“ man, warum sind Branches leichtgewichtig? 
- Wichtige Befehle zeigen: `git branch`, `git checkout` bzw. moderner `git switch`, und zeigen wie man ein branch in GitHub erstellt.
- Im Team erstellt jede Person einen Branch, z.B. einen „informatik“-Branch und einen „mathe“-Branch. 
- In jedem Branch wird ein reales Beispiel passend zum thema des branches zur Aussagenlogik ergänzt und committet. 
- Wenn alle fertig sind, werden die Branches gepusht. 
- Danach soll man zum Branch des Partners wechseln und dann wird zurück zur main gewechselt.
- Anschließend demonstrieren, was ein Pull Request ist, und einen PR über GitHub anlegen. 
- Das Team führt den Merge selbstständig durch, bei Bedarf mit Unterstützung. 

**Materialien:** GitHub im Browser, Editor, Terminal. 

---

## 7. „How to undo“ – Änderungen rückgängig machen 

**Ziele:** 

- Möglichkeiten kennenlernen, Fehler mit Git rückgängig zu machen. 
- Selbstständig im Team Lösungen recherchieren und ausprobieren. 

**Ablauf:** 

- Szenario stellen und umsetzten: „Du hast aus Versehen den falschen Text committed. Wie kannst du das rückgängig machen?“ 
- Teams suchen selbstständig nach Lösungen (Google ausdrücklich erlaubt). 
- `git log` zeigen, um die Commit-Historie sichtbar zu machen. 
- Durch den Raum gehen, bei der Auswahl einer passenden Strategie unterstützen. 
- Im Plenum die unterschiedlichen Lösungen sammeln und kurz vorstellen lassen. 
- Wenn nötig zum Abschluss ein eigenes kleines Beispiel gemeinsam am Beamer demonstrieren. 

**Materialien:** Präsentation, Oncoo oder Tafel für Ergebnissammlung. 

---

## 9. Weitere wichtige Konzepte: Gute Commits 

**Ziele:** 

- Commit verständlich machen, z.B. als „Sedimentschicht“ der Projektgeschichte, mit eindeutiger ID, eindeutig und unveränderlich. 
- Verstehen, wie man gute Commit-Messages schreibt. 
- Bedeutung von „atomaren“ Commits kennenlernen. 
- Teamkommunikation als wichtigen Teil von Versionskontrolle erkennen. 

**Ablauf:** 

- Einstieg ins Gespräch: „Wie können Commit-Messages euch als Team helfen?“ 
- Im Plenum Ideen sammeln, was eine gute Commit-Message ausmacht. 
- In 2er-Teams eine gute Commit-Message zu einer Beispieländerung (z.B. geänderte Notizen) formulieren und dann ein paar hervorheben.
- Hervorheben, dass es verschiedene „Git-Philosophien“ gibt und dass Teams ihre Regeln (Commit-Stil, Branch-Strategie, Review-Prozess) klar vereinbaren sollten. 

**Materialien:** Oncoo oder Tafel/Whiteboard. 

---

## 10. Ergebnissicherung 

**Ziele:** 

- Inhalte des Tages sichern und sichtbar machen. 
- Reflexion über den eigenen Lernstand anregen. 

**Ablauf:** 

- Die heutige Präsentation und die Oncoo-Boards in ein gemeinsames GitHub-Repository hochladen. 
- Reflexionsfrage ins Plenum: „Wann würdet ihr Git im Studium oder in euren Projekten konkret nutzen?“ 

**Materialien:** GitHub-Repository, Präsentation, Oncoo-Boards. 

---

## 11. Feedback und Abschluss 

**Ziele:** 

- Rückmeldung zur Sitzung einholen. 
- Ressourcen zum Weiterlernen bereitstellen. 

**Ablauf:** 

- Einen kurzen Fragebogen zum Kurs austeilen oder online ausfüllen lassen. 
- Im Plenum Rückmeldungen einsammeln (Was war hilfreich? Was war schwierig? Was wünscht ihr euch fürs nächste Mal?). 
- Auf weiterführende Links, Tutorials und Dokumentationen in der Repository-Readme hinweisen. 

**Materialien:** Fragebogen (Papier oder online), GitHub-Repository mit Linkliste. 

---

## Benötigte Materialien und Orga:
- Raum mit Beamer/Display und Internetzugang  
- Rechner der Teilnehmenden mit installiertem Git und Editor (z.B. VS Code)  
- Zugang zu GitHub (Accounts angelegt)  
- Oncoo-Board oder alternatives Online-Tool für Sammlung und Reflexion  
- Ausdrucke oder Online-Formular für Feedback