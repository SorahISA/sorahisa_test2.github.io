---
title: 演算法概論－期中考
date: 2021-11-20 12:43:11
category: 比賽
tags: NYCU
---

好久沒發文了，電腦好像還有些東西沒設定好，沒辦法本機 deploy ;w;

---

## 準備階段

本來表定是 9:00 ~ 13:00 的，但是大家進教室之後就已經 9:00 了，還要測試環境，所以就延到 9:35 才開始。

先測一下 gcc 11.2 有支援什麼，發現不能直接 `#include <bits/extc++.h>`，會少東西，也不能宣告 `int _N`，他會說底線開頭的是預留字，但是可以宣告 `int _test` OwO。

在開始前約 10 分鐘，助教說今年的系統會跟以往的 Formosa OJ 不一樣，結果竟然是用 CMS！？而且還有計分板可以看，當下感覺好爽 >////<

---

## 考試開始

可以直接用測機時打的模板耶！

本來的策略是先看過所有題目跟 Subtask 再去想要用什麼順序去寫，結果...

### B - Spaghetti Tower Again (Spaghetti)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$30$</span>$\\,/\\,$<span style="color:#4e9a05">$70$</span>$\\,)$ (02:38)

> 給你 $N$ 個正整數 $A_i$，接著詢問 $Q$ 次有多少數字在 $[l_i, r_i]$ 內。
> 
> 限制：$\\mathcal{O}(Q \\lg N)$。
> Subtask 1 $[30]$：$\\mathcal{O}(NQ)$。
> Subtask 2 $[70]$：$\\mathcal{O}(Q \\lg N)$。

顯然就是 `upper_bound(ALL(A), r) - lower_bound(ALL(A), l)`，然後他就 AC 了。

### F - Preventing Conflicts (Conflicts)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$10$</span>$\\,/\\,$<span style="color:#4e9a05">$90$</span>$\\,)$ (06:50)



### D - Get Together (Together)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$25$</span>$\\,/\\,$<span style="color:#4e9a05">$75$</span>$\\,)$ (12:17)



### A - Yet Another Good Sequence (Sequence)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$60$</span>$\\,/\\,$<span style="color:#4e9a05">$40$</span>$\\,)$ (19:01)



### E - Awkwardness Continued (Awkwardness)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$60$</span>$\\,/\\,$<span style="color:#4e9a05">$40$</span>$\\,)$ (26:45)



### C - AMD Stocks (Stocks)

<span style="color:#4e9a05">分數：$100$</span>$\\,(\\,$<span style="color:#4e9a05">$20$</span>$\\,/\\,$<span style="color:#4e9a05">$80$</span>$\\,)$ (41:36)


