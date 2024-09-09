2.1 Kondensator o pojemności 60μF naładowano napięciem 10V i połączono z cewką o indukcyjności 10mH.
Wyznacz: częstotliwość drgań układu, maksymalny ładunek kondensatora, maksymalne natężenie prądu,
energię zgromadzoną w układzie. Jak zmieniają się chwilowe wartości energii kondensatora i cewki?

Mamy do czynienia z klasycznym **układem drgającym LC**, w którym kondensator o pojemności \(C = 60 \, \mu\text{F}\) (mikrofaradów) i cewka o indukcyjności \(L = 10 \, \text{mH}\) (milihenrów) tworzą obwód LC.

### Dane:
- Pojemność kondensatora: \(C = 60 \, \mu\text{F} = 60 \times 10^{-6} \, \text{F}\),
- Indukcyjność cewki: \(L = 10 \, \text{mH} = 10 \times 10^{-3} \, \text{H}\),
- Napięcie początkowe na kondensatorze: \(U_0 = 10 \, \text{V}\).

### 1. Częstotliwość drgań układu

Częstotliwość drgań własnych w obwodzie LC wynika ze wzoru na **częstotliwość drgań** układu LC:

\[
f = \frac{1}{2\pi} \sqrt{\frac{1}{LC}}
\]

Podstawiamy dane:

\[
f = \frac{1}{2\pi} \sqrt{\frac{1}{(10 \times 10^{-3}) \times (60 \times 10^{-6})}}
\]

\[
f = \frac{1}{2\pi} \sqrt{\frac{1}{6 \times 10^{-4}}}
\]

\[
f = \frac{1}{2\pi} \times \frac{1}{0.02449} \approx \frac{1}{0.15398} \approx 6.49 \, \text{kHz}
\]

Częstotliwość drgań wynosi zatem **około 6,49 kHz**.

### 2. Maksymalny ładunek kondensatora

Maksymalny ładunek zgromadzony na kondensatorze wynika z prawa Q = CU, gdzie \(C\) to pojemność kondensatora, a \(U_0\) to początkowe napięcie.

\[
Q_{\text{max}} = C U_0
\]

Podstawiamy dane:

\[
Q_{\text{max}} = (60 \times 10^{-6}) \times 10 = 600 \times 10^{-6} \, \text{C} = 0.0006 \, \text{C}
\]

Maksymalny ładunek na kondensatorze wynosi **0,0006 C**.

### 3. Maksymalne natężenie prądu

Maksymalne natężenie prądu w obwodzie LC występuje, gdy cała energia zgromadzona początkowo w kondensatorze zostaje przekazana do cewki. Energia elektryczna zgromadzona w kondensatorze jest wtedy równa energii zgromadzonej w cewce, co opisuje zależność:

\[
\frac{1}{2} L I_{\text{max}}^2 = \frac{1}{2} C U_0^2
\]

Stąd maksymalne natężenie prądu:

\[
I_{\text{max}} = U_0 \sqrt{\frac{C}{L}}
\]

Podstawiamy dane:

\[
I_{\text{max}} = 10 \times \sqrt{\frac{60 \times 10^{-6}}{10 \times 10^{-3}}}
\]

\[
I_{\text{max}} = 10 \times \sqrt{\frac{60 \times 10^{-6}}{10^{-2}}} = 10 \times \sqrt{6 \times 10^{-3}} = 10 \times 0.07746 = 0.7746 \, \text{A}
\]

Maksymalne natężenie prądu wynosi **0,7746 A**.

### 4. Energia zgromadzona w układzie

Energia zgromadzona w układzie LC (zarówno w kondensatorze, jak i cewce) jest stała i wynosi tyle, ile początkowo zgromadzono w kondensatorze:

\[
E = \frac{1}{2} C U_0^2
\]

Podstawiamy dane:

\[
E = \frac{1}{2} \times (60 \times 10^{-6}) \times (10)^2 = \frac{1}{2} \times 60 \times 10^{-6} \times 100 = 3 \times 10^{-3} \, \text{J} = 0.003 \, \text{J}
\]

Energia zgromadzona w układzie wynosi **0,003 J**.

### 5. Jak zmieniają się chwilowe wartości energii kondensatora i cewki?

W układzie LC energia drga między kondensatorem a cewką:
- **Energia kondensatora** (\(E_C\)) jest maksymalna, gdy kondensator jest całkowicie naładowany (prąd w obwodzie jest wtedy równy zero).
- **Energia cewki** (\(E_L\)) jest maksymalna, gdy prąd w obwodzie jest maksymalny, a kondensator jest rozładowany.

Energie zmieniają się sinusoidalnie i są opisywane wzorami:

- **Energia zgromadzona w kondensatorze**:

\[
E_C(t) = \frac{1}{2} C U(t)^2
\]

- **Energia zgromadzona w cewce**:

\[
E_L(t) = \frac{1}{2} L I(t)^2
\]

Gdzie \(U(t)\) i \(I(t)\) to odpowiednio chwilowe napięcie na kondensatorze i chwilowe natężenie prądu. Wartości te zmieniają się z czasem zgodnie z funkcjami sinusoidalnymi.

- Kiedy kondensator jest całkowicie naładowany, energia \(E_C\) jest maksymalna, a energia w cewce \(E_L\) wynosi zero.
- Kiedy kondensator jest rozładowany, energia \(E_L\) osiąga maksimum, a \(E_C\) wynosi zero.

W sumie energia zgromadzona w układzie jest zachowana, a jej całkowita wartość wynosi \(E = 0.003 \, \text{J}\).

### Podsumowanie:
- **Częstotliwość drgań układu**: około **6,49 kHz**,
- **Maksymalny ładunek kondensatora**: **0,0006 C**,
- **Maksymalne natężenie prądu**: **0,7746 A**,
- **Energia zgromadzona w układzie**: **0,003 J**,
- **Chwilowe wartości energii kondensatora i cewki** zmieniają się sinusoidalnie: energia przepływa między kondensatorem a cewką w trakcie drgań.