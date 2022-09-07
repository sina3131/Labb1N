# Laboration 1 
Deadline: 2022/11/9 13:00
Betyg: U, G

## Innan du gör uppgiften
Du bör du ha gjort klart git-övningen och labb-förberedelsen på studentportalen. Det hjälper också om du gjort extrauppgifterna.

## Inlämning
Uppgiften inlämnas genom att du har pushat ut koden med git push. Den sista uppladdade commiten som gjorts innan deadline är den som betygsätts.

## Beskrivning:
Du ska bygga ett enkelt system för att hantera studenter via terminalen.
Filen student_system.py innehåller startdata för alla studenter, du ska bygga på funktionalitet. 

Försök att använda funktioner där det verkar logiskt (och flera filer om du vill, det är dock valfritt). Kom ihåg att denna uppgift kräver att du använder en hel del loopar. All kod och output ska vara på engelska! 

När användaren skriver in val som ej passar så kan du försöka visa felmeddelanden och visa alternativen igen. 

1. Programmet ska hälsa användaren välkommen och ge den en meny med olika följande val numrerat. 
   [q] Stäng ner programmet
   [0] Lista alla studenter med namn och student-id.
   [1] Lägg till en student med studentID och namn
   [2] Ta bort en student

Exempel:
```python
Welcome to the greatest student system in the world. 
What would you like to do?
[q] - Exit
[0] - List all students from the registry
[1] - Add a student from the registry
[2] - Remove a student from the registry
```

2. Om användaren valt 0 för att lista studenter så ska användaren sedan kunna välja en student i ordningen från 0 och uppåt (dvs. användaren ska kunna skriva in "0" för att se den första studenten i listan). När användaren valt student så visar du ytterligare 3 val:
   [q] Gå tillbaka till menyn
   [0] Lista användarens betyg i samtliga kurser
   [1] Lista personlig information om studenten

Exempel:
```python
Choose a student
[q] Go back
[0] ID: 11230 - Tobias Fors
[1] ID: 11231 - Karin Börjell
....
```
0
```python
What would you like to do?
[q] Go back
[0] Show summary of grades
[1] List personal information
```
0
```python
Pythonprogrammering 1: 1
Pythonprogrammering 2: 4
------------------------
```

**OBS!** Tänk på att visa menyalternativen för användaren när det känns logiskt!
Innan du lämnar in uppgiften bör du testa programmet.
Fastna inte i detaljer, **exakt** hur du gör eller hur det ser ut spelar ingen roll.

BONUS (Ej obligatoriskt): Användaren ska kunna lägga till betyg och kurser för enskilda studenter också (se 1.2)

