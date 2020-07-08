---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: BenutzerInnen
description: AdministratorInnen können unter diesem Menüpunkt neue BenutzerInnen anlegen und diesen somit Zugriff auf das CVS gewähren. Es können außerdem Passwörter bestehender NutzerInnen geändert und Verknüpfungen zu Personen-Datensätzen hergestellt werden.

# Micro navigation
micro_nav: true

# Page navigation
page_nav:
    prev:
        content: Briefe
        url: '/briefe'
    next:
        content: Kontakt
        url: '/kontakt'
---

<div class="callout callout--warning">
<p><strong>Administrator-Berechtigungen erforderlich</strong>
Bitte beachten Sie, dass das Aufrufen des Menüpunkts "BenutzerInnen" Administrator-Berechtigungen erfordert.
</p>
</div>

# Liste

In der Liste werden alle im System erfassten NutzerInnen angezeigt. Standardmäßig werden zehn Datensätze pro Seite angezeigt und die Liste ist absteigend alphabetisch nach Nachnamen der verknüpften Person sortiert.

Unter der Tabelle wird die Gesamtzahl der NutzerInnen angezeigt, die den aktuellen Filterkriterien entsprechen, wurden keine Filter angewendet, repräsentiert dies also die Gesamtzahl der im System vorhandenen Datensätze. Rechts daneben kann entweder durch die Seiten navigiert oder die Anzahl der pro Seite angezeigten BenutzerInnen auf <strong>10</strong>, <strong>25</strong> oder <strong>50</strong> angepasst werden.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/user_list.mp4"></video>
    </p>
</div>

## BenutzerIn anlegen

Um einen neuen BenutzerInnen-Datensatz anzulegen, klicken Sie auf den Button "BenutzerIn hinzufügen", der sich mittig über der Tabelle befindet. Wählen Sie aus, welche Berechtigungen der neu angelegten Nutzerin oder dem Nutzer zugewiesen werden sollen. Sie haben die Wahl zwischen "Lehrer/in" und "Administrator/in". Geben Sie eine eMail Adresse ein, diese fungiert als Benutzername und wird während des Logins benötigt. Abschließen müssen Sie ein Passwort festlegen und dies zur Sicherheit wiederholen. Beachten Sie, dass die Software keine Passwörter unter <strong>16 Zeichen</strong> akzeptiert. Klicken Sie abschließend auf "Anlegen". Der neue Datensatz erscheint nun gemäß der eingestellten Sortierung in der Tabelle. So kann es vorkommen, dass er nicht direkt auf der ersten Seite erscheint. Um weitere Daten eingeben zu können, suchen Sie die gerade angelegte Benutzerin oder den Benutzer in der Tabelle und navigieren Sie durch einen Doppelklick auf die Zeile zur Detailansicht des Datensatzes.

<strong>Beachten Sie</strong>, dass neu angelegte BenutzerInnen unter Umständen nicht in der Tabelle erscheinen, falls sie nicht den von Ihnen vorgegebenen Filterkriterien entsprechen.

## Bearbeiten und Einsehen

Möchten Sie einen bestimmten Datensatz betrachten bzw. bearbeiten, gelangen Sie mit einem Doppelklick auf die entsprechende Zeile der Tabelle in die Detailansicht. Hier kann ein neues Passwort festgelegt oder eine Verknüpfung mit einem Personen-Datensatz erstellt oder verändert werden. Zusätzlich besteht die Möglichkeit Administrator-Berechtigungen zu gewähren oder zu entziehen.

Die Benutzerberechtigungen lassen sich ganz einfach durch einen Klick auf die gewünschte Berechtigungsoption festlegen.

Um ein neues Passwort zu vergeben, klicken Sie auf den Button "Passwort ändern". Geben Sie im sich öffnenden Fenster zwei mal das neue Passwort ein und klicken Sie anschließend auf "Absenden". Das neue Passwort ist dann sofort gültig und dann für den Login benutzt werden.

<div class="callout callout--info">
    <p><strong class="video-collapse" style="cursor:pointer;">+ Video ansehen</strong>
    <video style="display:none;max-width:580px;" controls="controls" lazyvideo="/videos/user_detail.mp4"></video>
    </p>
</div>

Es besteht außerdem die Möglichkeit einen BenutzerInnen-Account mit einem Personendatensatz zu verknüpfen. Dies ist sinnvoll, da ein Benutzerkonto lediglich aus eMail-Adresse und Passwort besteht, für bestimmte Funktionen wie etwa den Versand von Briefen benötigt das CVS aber Informationen über den Namen der Person. Um einen BenutzerInnen-Datensatz mit einer Person zu verknüpfen wählen Sie einfach die gewünschte Person im Drop-Down Menü "verknüpfte Person" aus. In diesem Drop-Down werden alle Personen zur Auswahl angezeigt, die im System als "MitarbeiterInnen" hinterlegt sind.

<div class="callout callout--warning">
<p><strong>Verknüpfung für Briefversand erforderlich</strong>
Grundsätzlich funktioniert ein BenutzerInnen-Konto auch ohne Personen-Verknüpfung. Die Funktion "Briefe versenden" steht diesen AnwenderInnen dann allerdings nicht zur Verfügung.
</p>
</div>

## Sortieren

Die Tabelle lässt sich nach unterschiedlichen Kriterien sortieren. Sie erkennen die Tabellen-Spalten nach denen sortiert werden kann an den beiden Pfeilen hinter der Spalten-Überschrift. Klicken Sie auf die gewünschte Spalten-Überschrift um eine aufsteigende Sortierung zu erreichen. Ein erneutes Klicken führt zu einer absteigenden Sortierung. Der dritte Klick deaktiviert die Sortierung und ein erneutes Klicken führt wiederum zu einer aufsteigenden Ordnung.
