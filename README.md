**English README:**
# Object_oriented_programming_Project
# PyWizards of the Coast Coding School Project

## Description

This project is an implementation of object-oriented programming concepts. It focuses on creating classes with various properties and functions. The goal is to simulate a coding school named "PyWizards of the Coast," where individuals can participate as students or instructors. The project is divided into three parts, each involving different aspects of the simulation.

### Part 1: Person, Student, and Instructor

You are establishing your own coding school called PyWizards of the Coast. Every individual, whether a student or an instructor, is considered a "Person":

- Each person has a name.
- Every person can introduce themselves (e.g., "Hello, my name is Pascal").

Each person is categorized as either a student or an instructor:

- Students have a reason for attending (e.g., "I want to learn coding").
- Instructors have a biography (e.g., "I code with R and Python and have a passion for teaching").
- Instructors possess skills (e.g., "Python," "R," "SAS").
- Instructors can learn new skills using the `add_skill` function (e.g., `add_skill("C++")` adds the skill "C++" to the instructor's list of skills).

### Part 2: Workshop

PyWizards of the Coast offers workshops with the following attributes:

- Start and end dates.
- A topic.
- One or more instructors.
- Multiple students.
- An `add_participants` function that allows adding individuals as participants. If the individual is an instructor, they are added to the list of instructors. If the individual is a student, they are added to the list of students.

### Part 3: External Functions

- Implement a function called `print_members` that displays the information of all students in a DataFrame and all instructors in a second DataFrame.
- Implement a function called `print_workshops` that displays all information about a workshop.
- Implement a function called `print_details` that combines the functionality of the previous two functions.

## Usage

To use and test this project, follow these steps:

1. Clone the repository.
2. Navigate to the project directory.
3. Run the main script or import the classes and functions into your own Python environment.
4. Create instances of `Person`, `Student`, `Instructor`, and `Workshop` classes as needed.
5. Use the provided functions to interact with and display information about the objects.

-----

**German README:**

# PyWizards of the Coast Coding School Projekt

## Beschreibung

Dieses Projekt implementiert Konzepte der objektorientierten Programmierung. Es konzentriert sich auf das Erstellen von Klassen mit verschiedenen Eigenschaften und Funktionen. Das Ziel ist es, eine Codierschule mit dem Namen "PyWizards of the Coast" zu simulieren, in der Individuen als Studenten oder Lehrkräfte teilnehmen können. Das Projekt ist in drei Teile unterteilt, die jeweils verschiedene Aspekte der Simulation behandeln.

### Teil 1: Person, Student und Dozent

Du gründest deine eigene Codierschule namens PyWizards of the Coast. Jede Person, egal ob Student oder Dozent, wird als "Person" betrachtet:

- Jede Person hat einen Namen.
- Jede Person kann sich vorstellen (z. B. "Hallo, mein Name ist Pascal").

Jede Person wird entweder als Student oder Dozent kategorisiert:

- Studenten haben einen Grund für ihre Teilnahme (z. B. "Ich möchte das Codieren lernen").
- Dozenten haben eine Biografie (z. B. "Ich programmiere mit R und Python und habe eine Leidenschaft fürs Unterrichten").
- Dozenten besitzen Fertigkeiten (z. B. "Python", "R", "SAS").
- Dozenten können neue Fertigkeiten mit der `add_skill`-Funktion erlernen (z. B. `add_skill("C++")` fügt die Fertigkeit "C++" zur Liste der Fertigkeiten des Dozenten hinzu).

### Teil 2: Workshop

PyWizards of the Coast bietet Workshops mit folgenden Attributen an:

- Start- und Enddaten.
- Ein Thema.
- Eine oder mehrere Lehrkräfte.
- Mehrere Studenten.
- Eine `add_participants`-Funktion, die das Hinzufügen von Personen als Teilnehmer ermöglicht. Wenn die Person ein Dozent ist, wird sie der Liste der Dozenten hinzugefügt. Wenn die Person ein Student ist, wird sie der Liste der Studenten hinzugefügt.

### Teil 3: Externe Funktionen

- Implementiere eine Funktion namens `print_members`, die die Informationen aller Studenten in einem DataFrame und aller Dozenten in einem zweiten DataFrame anzeigt.
- Implementiere eine Funktion namens `print_workshops`, die alle Informationen zu einem Workshop anzeigt.
- Implementiere eine Funktion namens `print_details`, die die Funktionalität der beiden vorherigen Funktionen kombiniert.

## Verwendung

Um dieses Projekt zu verwenden und zu testen, befolge diese Schritte:

1. Klone das Repository.
2. Navigiere zum Projektverzeichnis.
3. Führe das Hauptskript aus oder importiere die Klassen und Funktionen in deine eigene Python-Umgebung.
4. Erstelle Instanzen der Klassen `Person`, `Student`, `Dozent` und `Workshop` nach Bedarf.
5. Verwende die bereitgestellten Funktionen, um mit den Objekten zu interagieren und Informationen anzuzeigen.
