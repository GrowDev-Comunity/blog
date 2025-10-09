---
title: The Static CMS
author: Zan
date: 2025-10-09T09:46:53
description: Tes posting menggunakan Static CMS
image: /images/fuji.jpg
tags:
  - grown test
  - dev
---
# Hello World

Postingan ini di buat menggunakan static CMS

## Heading 2

Lorem ipsum 

```cpp
#include <iostream>
#include <sstream>
#include <string>
#include <cstdlib>
#include <cmath>

using namespace std;

// Headers
string toString (double);
int toInt (string);
double toDouble (string);

int main() {
    int a;
    int b[10];
    a = 50000;

    cout << "Nilai variabel a: " << a << endl;
    cout << "Alamat memori variabel a: " << &a << endl;
    cout << endl;
    cout << "Nilai variabel b: " << b << endl;
    cout << "Alamat memori variabel b: " << &b << endl;

    return 0;
}

// The following implements type conversion functions.
string toString (double value) { //int also
    stringstream temp;
    temp << value;
    return temp.str();
}

int toInt (string text) {
    return atoi(text.c_str());
}

double toDouble (string text) {
    return atof(text.c_str());
}


```




