Steps:
1)Use prolog and create file and save 
2) paste the code
3) open consult open saved file
Paste first line of code
4) done 👍


CSP_mapcolor

Code:
coloring(WA,SA,NT,QU,NSW,VI) :-

different(WA,SA),

different(WA,NT),

different(NT,SA),

different(NT,QU),

different(SA,QU),

different(SA,NSW),

different(SA,VI),

different(QU,E),

different(NSW,VI).


different(red,blue).

different(blue,red).

different(blue,green).

different(red, green).

different(green, blue,).

different(green,red).
