# GitUebung

[branche](branches.md)
[link](links.md)

Wer hat Git erfunden?

Git wurde von Linus Torvalds, dem Erfinder des Linux-Betriebssystems, entwickelt. Es wurde erstmals im Jahr 2005 veröffentlicht. Git ist ein verteiltes Versionskontrollsystem, das in erster Linie für die effiziente und zuverlässige Verwaltung von Quellcode in Softwareprojekten verwendet wird.

Was ist git?


Git ist ein verteiltes Versionskontrollsystem, das von Linus Torvalds entwickelt wurde. Es ist weit verbreitet in der Softwareentwicklung, um den Quellcode von Projekten zu verwalten. 

Hier sind einige grundlegende Konzepte und Funktionen von Git.

Versionskontrolle:

Git ermöglicht die Verfolgung von Änderungen im Quellcode über die Zeit. Jede Änderung wird als "Commit" bezeichnet und enthält Informationen darüber, welche Dateien geändert wurden und was genau geändert wurde.

Verteiltes System:

Im Gegensatz zu zentralisierten Versionskontrollsystemen wie SVN (Subversion) speichert Git nicht nur die neueste Version des Codes, sondern das gesamte Repository mit der gesamten Versionshistorie wird auf jedem Entwicklerrechner gespiegelt. Das ermöglicht eine zentrale Zusammenarbeit.

Branches (Zweige):

Entwickler können unabhängige Zweige erstellen, um an neuen Funktionen zu arbeiten oder Fehler zu beheben, ohne den Hauptcode zu beeinträchtigen. Diese Zweige können dann bei Bedarf in den Hauptzweig integriert werden.

Merge (Zusammenführung) und Rebase (Neubasis):

Git bietet verschiedene Methoden, um Änderungen aus einem Zweig in einen anderen zu integrieren. Das Zusammenführen (Merge) kombiniert die Änderungen zweier Zweige, während das Neubasis (Rebase) den Verlauf des Zweigs ändert, um eine saubere und lineare Historie zu erhalten.

Commits:

Ein Commit repräsentiert eine einzelne Änderung am Code. Commits werden mit einer Nachricht versehen, die eine Zusammenfassung der vorgenommenen Änderungen enthält.

Remote Repositories:

Git ermöglicht die Zusammenarbeit mit anderen Entwicklern über Remote Repositories. Diese Repositories können auf Plattformen wie GitHub, GitLab oder Bitbucket gehostet werden.

Staging Area:

Git verwendet eine Zwischenstufe, genannt "Staging Area" oder "Index", um festzulegen, welche Änderungen in den nächsten Commit aufgenommen werden sollen. Dies ermöglicht eine präzise Kontrolle über den Inhalt jedes Commits.

Verzweigungs- und Verschmelzungshistorie:

Git behält eine detaillierte Historie von Branches, Commits und Merges bei, was es einfach macht, Änderungen zu verstehen und zu verwalten.
Git ist nicht auf die Verwaltung von Code beschränkt. Es kann auch für das Versionieren von Dateien jeglicher Art verwendet werden, was es zu einem vielseitigen Werkzeug für die Versionskontrolle macht.

Was kann man mit git machen?

Git ist nicht auf die Verwaltung von Code beschränkt. Es wird auch in anderen Kontexten verwendet, um Änderungen an Dateien jeglicher Art zu verfolgen, wie z.B. Konfigurationsdateien oder Dokumente. Es ist ein mächtiges Werkzeug, um kollaborative Softwareentwicklung zu unterstützen und die Versionshistorie von Projekten zu verwalten.

Aufgabe B

Die wichtigsten Befehle für Git:

git init
git clone 
git add
git commit
git pull
git push
git branch und git checkout oder git switch
