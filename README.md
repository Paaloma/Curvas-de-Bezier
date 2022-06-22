# Curvas-de-Bezier


Para qualquer n inteiro não-negativo e $P_0,  P_1, ..., P_n$ pontos distintos, a curva de Bézier de ordem n é dada pela equação:

$ B_n(t, P_0, ...,P_n) = \sum_{k=0}^{n}\binom{n}{k}(1-t)^{n-k}t^k \cdot P_k $,

onde $0\leq t \leq 1$. [1]

Por exemplo, quando n = 5:

$B_n(t, P_0, ...,P_5) =  (1 - t)^5P_0 + 5t(1 - t)^4P_1 + 10t^2(1 - t)^3 P_2 + 10t^3 (1-t)^2 P_3 + 5t^4(1-t)P_4 + t^5 P_5 $, 

$0\leq t \leq 1$.



1. Urs Oswald. Bézier Curves.  Disponível em: <http://www.ursoswald.ch/metapost/tutorial/BezierDoc/BezierDoc.pdf>. September 11, 2002.
