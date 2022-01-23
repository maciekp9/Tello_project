# Tello_projects
This repo contains source code for our college project.
PL
-----------------------------------------------------------------------------------------------



1. Opis:

  Głównym założeniem naszego projektu z przedmiotu "Identyfikacja i sterowanie robotami latającymi" jest zeskanowanie obiektu za pomocą drona i stworzenie modelu 3D badanego przedmiotu. Plan został zrealizowany za pomocą robota latającego DJI Tello, oraz oprogramowania Recap od firmy Autodesk. 
Kod źródłowy jest modyfikacją gotowej biblioteki Tello-Python opublikowanej przez użytkownika hanker-lu na GitHub.

Opis misji:<br/><br/>
<img src="https://github.com/maciekp9/Tello_project/blob/main/readme_images/opis_misji.png" width="400" height="400"> <br/><br/>


Rysunek powyżej przedstawia cztery fazy wykonywane podczas misji naszego drona. Istotą zadania jest lot po okręgu i zrobienie paru fotografii obiektowi znajdującemu się wewnątrz okręgu (zaznaczony czerwoną kropką). <br/>
Wykonywane kroki: <br/>
a) Dron startuje z punktu początkowego o współrzędnych (0,0). Ustawiamy dron tak, aby na wprost niego znajdował się fotografowany przedmiot. Dron wznosi się, robi pierwsze zdjęcie. <br/>
b) Następuje lot po okręgu do punktu "I", po czym wykonywany jest obrót do pozycji umożliwiającej zrobienie odpowiedniego zdjęcia. Pod koniec tego kroku wykonywana jest fotografia. <br/>
c) Punkt 'B' powtarzany jest dla pozycji "II", "III" oraz "IV'. <br/>
d) Dron ląduje. <br/>


2. Cele projektu:
- Start misji drona
- Rozpoczęcie lotu wokół obiektu ( na jednej, bądź dwóch wysokościach)
- Sfotografowanie obiektu z różnych pozycji oraz przesłanie zdjęć do komputera
- Koniec misji 
- Stworzenie modelu 3D w oprogramowaniu Recap

4. Problemy?
- Niepoprawnie wykonywana misja? Prawdopodobnie trzeba odpytać drona o aktualny stan
- Jak zrealizować lot po okręgu?
6. Screenshots:
7. Uruchomienie projektu:
- instalacja biblioteki Tello-Python, wraz z niezbędnymi bibliotekami
- uruchomienie skryptu 'main.py'
- Naciśnięcie przycisku Start Mission






EN
-----------------------------------------------------------------------------------------------



1. Description:
The main goal of our project for  

2. Goals of our project:
- Launch the drone mission
- Starting the flight around the object (at one or two heights)
- Photograph the object from different positions and upload the images to the computer
- End of the mission 
- Creation of a 3D model in Recap software


3. Problems:


4.Screenshots:
