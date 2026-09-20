# tbh dont even use this it's just that bad
Hi\
Depending on which C++ version you have it'll differ.\
Mostly you'll use this one\
<br>
<br>
<br>

#include <bits/stdc++.h>\
using namespace std;\
<br>
int main() {\
    ios::sync_with_stdio(false);\
    cin.tie(nullptr);\
}
<br>
If it doesn't let you have that specific include then you'll just have to make your own.\
1.Make a file called something like (my_headers.h)\
2.Then paste this\
#ifndef MY_HEADERS_H\
#define MY_HEADERS_H\
<br>
#include <iostream>\
#include <vector>\
#include <string>\
#include <algorithm>\
#include <map>\
#include <set>\
#include <queue>\
#include <stack>\
#include <cmath>\
#include <utility>\
<br>
#endif\
Got no clue why the actual things after #include dont work.\
# Will fix the formatting later\
<br>

