## Tryby:
- OUTPUT - tryb ustawiający dany pin jako wyjście, ma wpływ na sposób zasialania logiki rejestru wyjściowego
- INPUT - tryb wejściowy za pomocą, którego dany pin przygotowany będzie do odczyty stanu. W tym trybie na niepodłączonych pinach mogą występować stany nieustalone.
- INPUT_PULLUP - tryb wejściowy z podciągnięciem do napięcia zasilającego, uruchamia wew. zasilanie i ustawia domyślnie stan wysoki na pinie


Do ustawiania trybu służy funkcja: [pinMode(nr, tryb)](https://www.arduino.cc/reference/en/language/functions/digital-io/pinmode/)