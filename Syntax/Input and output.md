# HOW TO INPUT AND OUTPUT IN C++
Alright I put this syntax topic first because it's pretty much the first thing you need to do during problems.\
<br>
There are two different ways to both take values and print them out. (I don't really know how to do the second method so I'm not really qualified to teach that)
<br>
### The way I do it is using
cin << (variable)
This means that whatever is typed in, the value of the variable becomes that.
<br>
Say I typed this code up,\
cin >> n;
and typed in 100, then n would equal 100.\
<br>
So then if I did\
cout << n << "\n";\
^ &emsp; &emsp;&emsp; &emsp;&emsp;  ^\
how to  &emsp; &emsp;&emsp;     most efficient\
print    &emsp; &emsp;&emsp;     way to break the line because without breaking the line it would all be printed on the same line\

it would print out 100\
Some notes for the people who really are just completely starting off and using my guide (for whatever reason) as a guide to C++ syntax, "\n" is used as a line break as C++ doesn't automatically print on a new line.\
<br>
Additionally, use this to make the input and output process the most efficient as it possibly can get.\
ios::sync_with_stdio(false);\
cin.tie(nullptr);\
<br>
#### That's pretty much all for the input and output. Honestly, not that hard and if you struggle there are plenty of guides online (and AI).
