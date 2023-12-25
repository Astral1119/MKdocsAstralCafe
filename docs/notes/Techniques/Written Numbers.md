---
title: Calculation Limits
blurb: Calculation Limits
tags:
  - technique
dg-publish: true
---

### Introduction

Generating the written form of numerals is a challenging problem. However, one commonly used trick resolves this problem for small numbers.

### Syntax

```
SUBSTITUTE(GOOGLETRANSLATE(BAHTTEXT([number])), " baht", )
```

### Notes

* The efficacy of this technique is dependent on the accuracy of Google Translate.