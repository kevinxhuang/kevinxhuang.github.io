---
layout: post
title: 'Qt编程技巧  QLCDNumber与QSpinBox链接'
date: 2009-10-26
categories: [Programming, C++]
tags: [Qt]
keywords: "Qt"
description: 
comments: true
---

```cpp 
connect(spinBox, SIGNAL(valueChanged(QString)), lcdNumber, SLOT(display(QString)));
```

