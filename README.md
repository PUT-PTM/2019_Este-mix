2019_Este-mix

Projekt jest elektroniczną wersją tehereminu. Poruszając rękoma nad czujnikami można modulować generowany dźwięk.

Projekt składa się z płytki STM32F407, głośnika oraz trzech czujników ultradźwiękowych HC-SR04. Do generowania sunusoidy wykorzystywany jest CS43L22, który wykorzystuje moduły I2C oraz DAC. Próbkę z wygenerowanej sinusoidy wyprowadza się na DAC. Z czujników HC-SR04 pobierane są wartości, które następnie wykorzystywane są do modulowania sinusoidą. Funkcja overdrive przycina sinusoidę.

Aby uruchomić urządzenie potrzebny jest program STM32CubeMX oraz Eclipse, które pozwolą nam skompilować kod źródłowy.

W projekcie można poprawić sposób odczytywanie wartości z czujników, ponieważ czasami zdarza się, że wychwytywane są losowe wartości.

Kod do wygenerowania sinusoidy był bazowany na kodzie podanym w filmie:
https://www.youtube.com/watch?v=QIPQOnVablY&feature=youtu.be&fbclid=IwAR1Zl6XtSaZ0rACBRkMNhYdTjurQVUtrHhU8ySXA0XNeOIXiJhNZKQUdSnE

Licencja do projektu znajduje się w pliku License.pdf. Jest to licencja MIT.

Autorzy: ALeksandra Laskowska, Wojciech Lulek

The project was conducted during the Microprocessor Lab course held by the Institute of Control and Information Engineering, Poznan University of Technology.
Supervisor: Marek Kraft/Michał Fularz/Tomasz Mańkowski/Adam Bondyra
