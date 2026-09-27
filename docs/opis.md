# Opisy przycisków
## Przycisk środkowy
- android:id="@+id/button5" - tworzy i ustawia nowe ID dla przycisku o nazwie button5
- android:layout_width="wrap_content" - ustawia szerokość przycisku na taką aby odpowiadała jej zawartości
- android:layout_height="wrap_content" - to samo co wyżej tylko dla wysokości
- android:text="Button" - ustawia na sztywno tekst w przycisku na "Button"
- app:layout_constraintBottom_toBottomOf="parent" - łączy dół przycisku z dołem ekranu
- app:layout_constraintEnd_toEndOf="parent" - łączy lewo przycisku z lewem ekranu
- app:layout_constraintStart_toStartOf="parent" - łączy prawo przycisku z prawem ekranu
- app:layout_constraintTop_toTopOf="parent" - łączy górę przycisku z górą ekranu
<br>**Ponieważ element ma założone constrainty ze wszystkich 4 stron i nie posiada atrybutów layout_constraintHorizontal_bias oraz layout_constraintVertical_bias (co defaultowo ustawia je na 0.5) to element sie środkuje**

## Przycisk 1/4 wysokości i 3/4 szerokości
Pojawiają się tu te same atrybuty co w środkowym przycisku oraz pojawiają się dwa nowe:
- app:layout_constraintHorizontal_bias="0.75" - ustawia bias poziomy na 0.75 czyli ustawia przycisk na 75% od lewej krawędzi ekrannu
- app:layout_constraintVertical_bias="0.25" - to samo tylko pionowo i na 25% od góry ekranu