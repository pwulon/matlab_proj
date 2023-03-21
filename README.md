# Opis projektu

Celem projektu było utworzenie programu symulacji rozchodzenia się fali w dwóch wymiarach. Program pozwala użytkownikowi na dostosowanie właściwości symulowanej fali.

## Założenia wstępne przyjęte w realizacji projektu

Program jest aplikacją programu Matlab, użytkownik wybiera właściwości fali takie jak częstotliwość czy amplituda, następnie wybiera czas wykonywania symulacji. Ostatnim krokiem jest rozpoczęcie animacji.

## Równanie symulowanej fali
$$ \frac{\partial^2\delta}{\partial t^2} = c^2\frac{\partial^2\delta}{\partial x^2} + c^2\frac{\partial^2\delta}{\partial y^2} - \beta \frac{\partial \delta}{\partial t} $$

## Funkcjonalność

Po lewej stronie znajdują się suwaki do ustawiania parametrów:
- Propagation (prędkość rozchodzenia się fali)
- Amplitude (amplituda)
- Frequency (częstotliwość)
- Phaze (faza)

oraz checkbox pozwalający dodać drugie źródło fali.

Pod oknem animacji znjdują się opcje wyświetlania oraz narzędzia do dostosywania przypadków rozchodzonej fali:
- Source (droplist do wybrania przypadków gdzie znajdują się źródła fali oraz trybów double/single slit)
- Border (checkbox, jeżli zaznaczony warónki brzegowe ustawione, żeby fala odbiła się od ścian)
- Pulse (checkbox, jeśli zaznaczony wykonany zostanie tylko jeden okres źródła)
- Run (rozpoczęcie animacji)
