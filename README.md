<div align="center">

<img src="assets/hero.svg" alt="Zubair Ahmed - terminal intro" width="100%"/>

</div>

<br/>

### `$ pmap $(pidof zubair)`

> Most profiles are a list. Mine is a process. This is my memory layout right now.

```text
HIGH ADDRESS
┌────────────────────────────────────────────────────────┐
│ STACK   what I'm running right now                     │
│   push  personal projects in C++ and Python            │
│   push  becoming a full-stack developer                │
├────────────────────────────────────────────────────────┤
│  .  .  .  .  .  unallocated  .  .  .  .  .  .          │
├────────────────────────────────────────────────────────┤
│ HEAP    allocated, still being learned                 │
│   malloc(advanced_git)                                 │
│   malloc(node + typescript + express)                  │
│   malloc(wsl_and_linux)                                │
├────────────────────────────────────────────────────────┤
│ .data   what I carry with me                           │
│   C++  Python  C  JavaScript  HTML/CSS                 │
│   Git  GitHub  Linux  Docker  SQL  MongoDB             │
├────────────────────────────────────────────────────────┤
│ .text   read-only, always executing                    │
│   Final-year CS @ FAST. Curious by default.            │
│   Solving problems. Shipping programs.                 │
└────────────────────────────────────────────────────────┘
LOW ADDRESS
```

<br/>

### `$ nm --defined-only projects.o`

| symbol | lang | what it does |
|:--|:--:|:--|
| [`pymapshelper`](https://github.com/Zubair1s/pymapshelper) | Python | A library that wraps OpenStreetMap APIs: geocoding, places, routing |
| [`flaskchatapp`](https://github.com/Zubair1s/flaskchatapp) | Python | Real-time chat web app on Flask + Socket.IO |
| [`Wallet-Woes`](https://github.com/Zubair1s/Wallet-Woes) | Python | Expense tracker with a customtkinter UI and SQLite storage |
| [`ClickNShop`](https://github.com/Zubair1s/ClickNShop-Programming-Fundamental-Project-in-C) | C | A shopping program built from pure C fundamentals |

<br/>

### `$ ./reach_me`

```c
int main(void) {
    connect("linkedin");     // https://www.linkedin.com/in/zubair-ahmed-a4488b30a/
    send_mail("inbox");      // zasoomro111@gmail.com
    solve("leetcode");       // https://leetcode.com/u/soomro1/
    compete("codeforces");   // https://codeforces.com/profile/Soomro
    return 0;
}
```

[LinkedIn](https://www.linkedin.com/in/zubair-ahmed-a4488b30a/) &nbsp;·&nbsp; [LeetCode](https://leetcode.com/u/soomro1/) &nbsp;·&nbsp; [Codeforces](https://codeforces.com/profile/Soomro) &nbsp;·&nbsp; [Email](mailto:zasoomro111@gmail.com)

<br/>

```text
$ make profile
[100%] Built target zubair
0 errors, 0 warnings, 1 very curious developer.
```
