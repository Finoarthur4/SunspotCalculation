\documentclass{article}
\usepackage{amsmath}
\begin{document}

\section*{Beweis der Mittelpunktformel}

Gegeben zwei Punkte \( A(a_1, a_2, a_3) \) und \( B(b_1, b_2, b_3) \) im dreidimensionalen Raum, wird der Mittelpunkt \( M \) der Strecke, die diese beiden Punkte verbindet, berechnet als:

\[ M = \left( \frac{a_1 + b_1}{2}, \frac{a_2 + b_2}{2}, \frac{a_3 + b_3}{2} \right) \]

Um dies zu beweisen, müssen wir zeigen, dass \( M \) von beiden Punkten \( A \) und \( B \) gleich weit entfernt ist.

\subsection*{Berechnung der Entfernung von \( A \) zu \( M \):}

\[
\text{Entfernung} = \sqrt{\left( \frac{a_1 + b_1}{2} - a_1 \right)^2 + \left( \frac{a_2 + b_2}{2} - a_2 \right)^2 + \left( \frac{a_3 + b_3}{2} - a_3 \right)^2 }
\]

Vereinfachen jedes Termes innerhalb der Wurzel:

\[
\left( \frac{a_1 + b_1}{2} - a_1 \right) = \frac{b_1 - a_1}{2}
\]
\[
\left( \frac{a_2 + b_2}{2} - a_2 \right) = \frac{b_2 - a_2}{2}
\]
\[
\left( \frac{a_3 + b_3}{2} - a_3 \right) = \frac{b_3 - a_3}{2}
\]

Die Entfernung wird also:

\[
\text{Entfernung} = \sqrt{\left( \frac{b_1 - a_1}{2} \right)^2 + \left( \frac{b_2 - a_2}{2} \right)^2 + \left( \frac{b_3 - a_3}{2} \right)^2 }
\]

\[
= \frac{1}{2} \sqrt{(b_1 - a_1)^2 + (b_2 - a_2)^2 + (b_3 - a_3)^2}
\]

\subsection*{Berechnung der Entfernung von \( B \) zu \( M \):}

\[
\text{Entfernung} = \sqrt{\left( \frac{a_1 + b_1}{2} - b_1 \right)^2 + \left( \frac{a_2 + b_2}{2} - b_2 \right)^2 + \left( \frac{a_3 + b_3}{2} - b_3 \right)^2 }
\]

Vereinfachen des Termes innerhalb der Wurzel:

\[
\left( \frac{a_1 + b_1}{2} - b_1 \right) = \frac{a_1 - b_1}{2}
\]
\[
\left( \frac{a_2 + b_2}{2} - b_2 \right) = \frac{a_2 - b_2}{2}
\]
\[
\left( \frac{a_3 + b_3}{2} - b_3 \right) = \frac{a_3 - b_3}{2}
\]

Die Entfernung wird also:

\[
\text{Entfernung} = \sqrt{\left( \frac{a_1 - b_1}{2} \right)^2 + \left( \frac{a_2 - b_2}{2} \right)^2 + \left( \frac{a_3 - b_3}{2} \right)^2 }
\]

\[
= \frac{1}{2} \sqrt{(a_1 - b_1)^2 + (a_2 - b_2)^2 + (a_3 - b_3)^2}
\]

Da die Entfernungen von \( A \) zu \( M \) und von \( B \) zu \( M \) gleich sind, ist \( M \) tatsächlich der Mittelpunkt der Strecke \( \overrightarrow{AB} \).

\subsection*{Zusammenfassung}

Damit ist bewiesen, dass die Gleichung

\[
\vec{OM} = \vec{OA} + \frac{1}{2} \Rightarrow M\left(\frac{a_1 + b_1}{2}, \frac{a_2 + b_2}{2}, \frac{a_3 + b_3}{2}\right)
\]

immer gilt.

\end{document}
