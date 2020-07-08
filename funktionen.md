---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Funktionen
description: In diesem Abschnitt finden Sie eine vollständige Übersicht der Funktionen, die das CVS bietet. Die Gliederung der Dokumentation richtet sich dabei nach der Menü-Struktur der Software. Navigieren Sie mit den Buttons durch die verschiedenen Bereiche der Dokumentation:

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Inhalt
        url: '/inhalt'
    next:
        content: Dashboard
        url: '/dashboard'
---

# Grundlegende Funktionen
## Automatisches Speichern
Im gesamten CVS gibt es keinen Button um Änderungen zu speichern. Alle Änderungen, die vorgenommen werden, werden automatisch und in Echtzeit auf dem Server gespeichert. Falls Sie eine ungültige Eingabe vornehmen, die nicht gespeichert werden kann bzw. soll, erhalten Sie immer eine entsprechende Fehlermeldung. Die einzige Ausnahme von dieser Regel stellt die sogenannte Inline-Bearbeitung dar (z.B. beim Bearbeiten von Schlagworten oder Klassen- und Lerngruppenbezeichnungen). Weitere Details dazu finden sich in den entsprechenden Abschnitten der Dokumentation.

## Paralleles Arbeiten
Alle Bereiche des CVS können von beliebig vielen NutzerInnen gleichzeitig betrachtet und bearbeitet werden. Dies ermöglicht das gleichzeitige Bearbeiten von beispielsweise Zeugnissen oder Förderdokumentationen, ohne dass eine gegenseitige Absprache nötig ist, oder ein Datensatz für die Bearbeitung gesperrt werden muss. Konflikte durch das gleichzeitige Bearbeiten des selben Textes werden dadurch verhindert, dass die Software ein Feld automatisch für alle BenutzerInnen sperrt, sobald eine Eingabe erkannt wird. Zusätzlich wird ein Hinweis eingeblendet, welche Person den Text gerade bearbeitet. Wird der Tippvorgang beendet, wird das Feld wieder für alle AnwenderInnen freigegeben.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/parallel_working.mp4"></video>
    </p>
</div>

Alle getätigten Änderungen werden in Echtzeit an alle anderen eingeloggten BenutzerInnen übertragen, so dass produktiv an einer gemeinsamen Datenbasis gearbeitet werden kann.

## Benutzer-Berechtigungen
Nicht alle Funktionen des CVS stehen allen BenutzerInnen in gleichem Maße zur Verfügung. Bestimmte Bereiche oder Funktionen stehen nur NutzerInnen mit Administrator-Berechtigung zur Verfügung. Dies dient besonders dazu, jedem Anwender und jeder Anwenderin nur den Funktionsumfang zur Verfügung zu stellen, der in der täglichen Arbeit benötigt wird. So kann die Benutzeroberfläche übersichtlich gehalten werden ohne durch ungenutzte Funktionalität überladen zu werden. Die vorliegende Dokumentation behandelt alle existierenden Funktionen des CVS, es wird jedoch jeweils kenntlich gemacht, falls eine Funktion ausschließlich mit Administrator-Berechtigung zur Verfügung steht.

## Login
Um im CVS arbeiten zu können, müssen Sie sich zunächst im System authentifizieren. Geben Sie dazu auf der <a href="https://cvs.christophor.ch" target="blank">Login-Seite</a> Ihre eMail Adresse (vorname.nachname@christophor.ch) und Ihr durch die Administration zugewiesenes Passwort ein. Bestätigen Sie die Eingabe mit Klick auf den "Einloggen" Button oder durch Drücken der Enter-Taste.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/login_flow.mp4"></video>
    </p>
</div>



Achten Sie bei der Eingabe darauf, das Passwort genau wie zugewiesen anzugeben. <strong>Groß- und Kleinschreibung</strong> müssen beachtet sowie <strong>Leerzeichen</strong> innerhalb oder am Anfang oder Ende des Passworts <strong>vermieden</strong> werden.


<div class="callout callout--success">
<p><strong>Tipp</strong>
Durch einen Klick auf das Augen-Symbol im Passwort-Eingabefeld, lässt sich das eingegebene Passwort ein- und ausblenden. Diese Funktion soll helfen Tippfehler und mehrmaliges Eingeben zu vermeiden.
</p>
</div>

## Logout
Wenn Sie im System angemeldet sind, können Sie sich jederzeit ausloggen. Klicken Sie dazu am oberen rechten Bildrand auf das Benutzer-Symbol und dann auf den Menüpunkt "Ausloggen".

[![Ausloggen Menü](/img/logout.jpg)](/img/logout.jpg)

In Klammern ist Ihre eMail-Adresse angegeben. Falls Sie über mehrere Accounts verfügen, können Sie so feststellen mit welchem Benutzer Sie gerade eingeloggt sind. Unter bestimmten umständen kommt es aus Sicherheitsgründen zu einem automatischen Ausloggen. Mehr dazu erfahren Sie unter dem Punkt [Allgemeines -> Sitzungen](/allgemeines/#sitzungen).

## Menü
Am linken Bildschirmrand befindet sich das Menü. Der aktive Menüpunkt ist zur besseren Kenntlichmachung jeweils grün hinterlegt. Umfangreichere Punkte wie etwa "Personen" können durch Klicken aus- und eingeklappt werden, um weitere Unterpunkte sichtbar zu machen bzw. auszublenden.

Für eine bessere Darstellung auf kleinen Bildschirmen und mobilen Endgeräten lässt sich das Menü durch Klicken auf das Menü-Icon (drei horizontale Balken) am linken oberen Bildschirmrand wahlweise ein- oder ausfahren. Sobald dem Browser-Fenster weniger als <strong>1200 Pixel</strong> Breite zur Verfügung stehen, wird das Menü automatisch eingefahren. Wird das Fenster wieder über diese Größe hinaus vergrößert, wird das Menü wiederum automatisch ausgefahren. Durch Klicken auf das Menü-Icon kann jedoch jederzeit unabhängig von der Breite des Fensters ein Aus- oder Einfahren erreicht werden.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/menu.mp4"></video>
    </p>
</div>

## Tabs und Navigation
Um das Arbeiten in unterschiedlichen Bereichen des CVS zu erleichtern, gibt es am oberen Bildschirmrand eine Tab-Leiste. Darin werden alle geöffneten Unterseiten angezeigt. Wird eine neue Seite geöffnet, erscheint automatisch ein neues Tab in der Leiste. Durch Klicken auf eines der Tabs kann somit ein schneller Wechsel zwischen beispielsweise zwei geöffneten Datensätzen erreicht werden. Durch Klicken auf das "x" am rechten Rand eines Tabs wird das jeweilige Tab geschlossen. Wird in einem geöffneten Tab beispielsweise eine Liste gefiltert oder eine Auswahl an Datensätzen getroffen, werden diese Einstellungen solange beibehalten, bis das Tab geschlossen wird.

Unter der Tab-Leiste befindet sich die Navigations-Übersicht. Sie beinhaltet den Titel der aktuellen Seite, sowie eine Übersicht der Navigationsstruktur. Dadurch wird einerseits die Gliederung der Navigation deutlich, andererseits kann durch Klicken auf einen der Punkte der Navigationsstruktur schnell zu einem übergeordneten Punkt der aktuellen Seite navigiert werden.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/tabs.mp4"></video>
    </p>
</div>

## Vollbild
Möchten Sie das CVS im Vollbild nutzen, können Sie dies durch Klicken auf die vier auseinander zeigenden Pfeile links neben dem Benutzer-Symbol am oberen rechten Rand des Browserfensters erreichen. Der Vollbild-Modus kann entweder durch erneutes Klicken auf das Icon oder das Betätigen der Escape-Taste auf der Tastatur verlassen werden.

# Eingabe-Typen
Innerhalb des CVS gibt es unterschiedliche Typen von Eingabemöglichkeiten, die sich danach richten welche Art von Daten gespeichert werden soll. Folgende Typen werden unterschieden:

## Freitext
Am häufigsten werden Freitextfelder für die Dateneingabe genutzt. In diesen Feldern kann beliebiger Text erfasst werden, ähnlich wie in einem Text-Editor. Auch Absätze können durch betätigen der Enter-Taste eingefügt und gespeichert werden. Dies kann beispielsweise bei der Eingabe längerer Text bei Förderdokumentationen oder Zeugnissen sinnvoll sein.

Es gilt zu beachten, dass je nach Eingabefeld unterschiedliche Vorgaben für die erlaubten Zeichen bestehen. So existieren bei der Eingabe von Zeugnis-Texten etwa keine Restriktionen wohingegen in eMail-Adressen-Feldern keine Absätze oder Sonderzeichen erlaubt sind, die in eMail Adressen nicht vorgesehen sind. Falls Sie eine Eingabe Tätigen, wird die Software Ihnen in der entsprechenden Fehlermeldung mitteilen, aus welchem Grund die Eingabe ungültig ist und deshalb nicht gespeichert wurde.

Alle Freitextfelder verfügen über die Funktion, dass sie automatisch für andere NutzerInnen gesperrt werden, falls Sie gerade eine Eingabe vornehmen. Dadurch können konkurrierende Eingaben in das selbe Textfeld und das gegenseitige Überschreiben von Daten verhindert werden. Mehr zu diesem Thema erfahren Sie unter dem Punkt [Grundlegende Funktionen -> Paralleles Arbeiten](/funktionen/#paralleles-arbeiten)
## Datum
In Datumsfeldern können Sie entweder direkt ein Datum im Format TT.MM.JJJJ eingeben oder durch Klicken in das Datumsfeld einen Kalender öffnen um den gewünschten Tag auszuwählen.

Zum Löschen eines Datums klicken Sie auf das "x" am rechten Rand des Feldes (erscheint nur, falls bereits ein Datum eingegeben wurde).
## Radio-Buttons
Bei sogenannten Radio-Buttons handelt es sich um Kreise die durch Klicken eine Anwahl der gewünschten Option erlauben. Radio-Buttons gestatten grundsätzlich nur die Auswahl genau einer Option, es handelt sich also um eine "Entweder-oder-Auswahl". Die Auswahl eines Radio-Buttons lässt sich nicht löschen, es ist lediglich möglich eine andere Option zu wählen.

Beispiel:
[![Radio-Buttons](/img/radio.jpg)](/img/radio.jpg)
## Selektion
Bei einem Selektionsfeld handelt es sich um ein Dropdown-Menü, das eine Auswahl an unterschiedlichen Optionen bietet aus denen eine ausgewählt werden kann. Da es vorkommen kann, dass eine erhebliche Anzahl an Optionen zur Auswahl steht, kann durch eine Texteingabe im Feld ein Eingrenzen der möglichen Optionen vorgenommen werden. Möchten Sie beispielsweise aus einem Dropdown mit allen Schülern eine bestimmte Person auswählen, klicken Sie in das Feld und geben Sie wahlweise den Vor- oder Nachnamen der gesuchten Person ein. Die Auswahl im Dropdown-Menü passt sich Ihrer Eingabe an und präsentiert nur Personen, die dem eingegeben Text entsprechen.

Zum Löschen einer Selektion, klicken Sie auf das "x" am rechten Rand des Feldes.
## Mehrfach-Selektion
Die Mehrfach-Selektion funktioniert grundsätzlich analog zur einfachen Selektion. Es können aber beliebig viele Optionen aus dem Dropdown durch Klicken ausgewählt werden. Die ist beispielsweise bei der Eingabe einer Person sinnvoll, die über mehrerer Staatsbürgerschaften verfügt. Die ausgewählten Optionen erscheinen als kleine Labels im Eingabefeld.

Durch einen Klick auf das "x" können Optionen einzeln deselektiert werden.
