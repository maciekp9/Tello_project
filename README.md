# Tello_projects
This repo contains source code for our college project.
PL
-----------------------------------------------------------------------------------------------



1. Opis:

  Głównym założeniem naszego projektu z przedmiotu "Identyfikacja i sterowanie robotami latającymi" jest zeskanowanie obiektu za pomocą drona i stworzenie modelu 3D badanego przedmiotu. Plan został zrealizowany za pomocą robota latającego DJI Tello, oraz oprogramowania Meshroom od firmy Alice Vision, a także programu Meshlab. 
Kod źródłowy jest modyfikacją gotowej biblioteki Tello-Python opublikowanej przez użytkownika hanker-lu na GitHub.

Opis misji:<br/><br/>
<img src="https://github.com/maciekp9/Tello_project/blob/main/readme_images/Opis misji1.PNG" width="600" height="400"> <br/><br/>


Rysunek powyżej przedstawia poszczególne etapy wykonywane podczas misji naszego drona. Istotą zadania jest lot po wielokącie w sposób zbliżony do lotu po okręgu i wykonanie kilkunastu fotografii obiektowi znajdującemu się w centralnym punkcie okręgu (zaznaczony czerwoną kropką). <br/>
Wykonywane kroki: <br/>
a) Dron startuje z punktu początkowego. Ustawiamy dron tak, aby na wprost niego znajdował się fotografowany przedmiot. Dron wznosi się, robi pierwsze zdjęcie. <br/>
b) Następnie dron obraca się o wyliczony kąt, pokonuje dystans oznaczony żółtą linią po czym ponownie dokonuje obrotu w celu sfotografowania obiektu w centralnej części kadru. <br/>
c) Punkt 'B' powtarzany jest do osiągnięcia zadanej liczby kroków - osiągnięcia położenia początkowego. <br/>
d) Dron ląduje. <br/>


2. Cele projektu:
- Start misji drona
- Rozpoczęcie lotu wokół obiektu na zadanej wysokości
- Sfotografowanie obiektu z różnych pozycji oraz przesłanie zdjęć do komputera
- Koniec misji 
- Stworzenie modelu 3D w oprogramowaniu Meshroom

4. Filmy pokazujące poprawne działanie projektu:
- https://www.youtube.com/watch?v=_nwLo5d7gSs #Widok z perspektywy drona
- https://www.youtube.com/watch?v=Pq0rOZ08Mts #Widok drona z trzeciej osoby
-    #Zeskanowany model
6. Uruchomienie projektu:
- uruchomienie skryptu 'main.py' - trzeba ustawić dwa parametry ( stepNumber <- odpowiedzialny za ilość kroków oraz zdjęć, bok <- odpowiada za długość boku wielokąta foremnego, po którym dron ma swoją trajektorię lotu)
- naciśnięcie przycisku 'Start mission' ( misja wykonuje się automatycznie)







EN
-----------------------------------------------------------------------------------------------



1. Description:

The main idea of our project in the subject "Identification and Control of Flying Robots" is to scan an object with a drone and create a 3D model of the object under study. The plan was implemented using DJI Tello flying robot, and Meshroom software from Alice Vision, and Meshlab software. The source code is a modification of the ready-made Tello-Python library published by user hanker-lu on GitHub. <br/><br/>

Description of the mission:<br/><br/>
<img src="https://github.com/maciekp9/Tello_project/blob/main/readme_images/Opis misji1.PNG" width="600" height="400"> <br/><br/>
<br/><br/>

The figure above shows the different steps performed during the mission of our drone. The essence of the mission is to fly around a polygon in a manner similar to flying around a circle, and to take several photographs of an object located at the central point of the circle (marked with a red dot). 
The steps performed: <br/>
(a) The drone takes off from the starting point. Drone must be in position which allows to take the first photo of object. The drone rises, takes the first photo.  <br/>
b) Then the drone rotates by the calculated angle, covers the distance marked with a yellow line and rotates again in order to photograph the object in the central part of the frame.  <br/>
c) Point 'B' is repeated until the set number of steps - the initial position - is reached. 
d) The drone lands. <br/>


2. Goals of our project:
- Launch the drone mission
- Starting the flight around the object (at one or two heights)
- Photograph the object from different positions and upload the images to the computer
- End of the mission 
- Create 3D model in Meshroom Software



4. Videos showing the correct operation of the project:
- https://www.youtube.com/watch?v=_nwLo5d7gSs #Drone view
- https://www.youtube.com/watch?v=Pq0rOZ08Mts #Drone view from third person
- #Scanned model

7. How to run project:
- run the 'main.py' script - you need to set two parameters ( stepNumber <- responsible for the number of steps and photos, side <- responsible for the length of the side of the regular polygon along which the drone has its flight trajectory)
- pressing the 'Start mission' button (the mission will be executed automatically)

