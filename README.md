# ti-84-pong
simple slow pong game i made in ti-84 basic

(note: `ℕ` and `I%` are finance variables)

may be a little broken

```
GridLine
AxesOn
1→ℕ
1→I%
1→J
4→Q
randInt(2,11→R
1→V
-1→W
0→Y
0→Z
ZQuadrant1
StartTmr→I
0→U
While 1
If checkTmr(I)
Then
Text(1,1,"          "
Text(1,1,U
0→U
startTmr→I
End
Vertical 6,5,BLACK,1
4(1+iPart(log(Y+not(Y
Text(1,(127-Ans)-6,Y
4(1+iPart(log(Z+not(Z
Text(1,127+Ans+7,Z
Line(.5,ℕ,.5,ℕ+2,0
getKey
N-.4(Ans=34)+.4(Ans=25→ℕ
Line(.5,ℕ,.5,ℕ+2,1,BLACK
If V=1
Then
.25→J
R+W((12-Q)/V→S
If .2>abs(S-(I%+(1-2(J<0
0→J
S<I%+(1-2(J<0
J(-Ans+not(Ans→J
Line(12.7,I%,12.7,I%+2,0
I%+J
Ans+((11-Ans)(Ans>11
Ans-Ans(Ans<0→I%
Line(12.7,I%,12.7,I%+2,1,BLACK
End
R>ℕ and R<ℕ+2→E
R>I% and R<I%+2→F
If FQ>12.3
Then
-1→V
1-2(W<0
Ans+.5(R-I%-1→W
End
If Q<1 and E
Then
1→V
1-2(W<0
Ans+.5(R-ℕ-1→W
End
If Q<.3 or Q>12.6 and not(E+F
Then
Pt-Off(Q,R
Z+(Q<1→Z
Y+(Q>12→Y
7→Q
-V→V
End
If R<.5 or R>12.5
-W→W
Pt-Off(Q,R
Q+.3V→Q
R+.3W→R
Pt-On(Q,R
U+1→U
End
```
