# My-Security-Learning-Resources
A collections of good security articles I have come across.
Note that this repository does **NOT** have any actual contents than a list of urls.
Also not all articles are in English, but with the Google Translate browser extension there should be no issue understanding the most of contents. I will be noting the source language though.

Most articles may not be beginner friendly, just saying. The layout is also pretty messed up, will clean things up in the future (I hope).

# Web

## Deserialization 
### Java Deserialization

#### Theory
- https://medium.com/swlh/hacking-java-deserialization-7625c8450334 (EN)
- https://www.anquanke.com/post/id/233410 (ZH)
- https://www.freebuf.com/articles/web/267623.html (ZH)
- https://cloud.tencent.com/developer/article/1590955 (ZH)
- Shameless self promotion 2(https://y4y.space/2021/06/25/taking-a-peek-at-ysosreial-commoncollection1-gadget/) (EN)


#### Development
- https://lgtm.com/rules/1823453799/ (EN)
- https://wiki.sei.cmu.edu/confluence/display/java/SER12-J.+Prevent+deserialization+of+untrusted+data (EN)

#### CodeQL
- https://securitylab.github.com/research/insecure-deserialization (EN)


#### Exploitation
- https://afinepl.medium.com/testing-and-exploiting-java-deserialization-in-2021-e762f3e43ca2 (EN)
- https://github.com/frohoff/ysoserial (EN)
- https://xz.aliyun.com/t/9344 (ZH)
- https://www.anquanke.com/post/id/230788 (ZH)

### PHP Deserialization
#### Theory
- https://vickieli.medium.com/diving-into-unserialize-pop-chains-35bc1141b69a (EN)


## XML External Entity (XXE)

### Theory 
- https://www.freebuf.com/articles/web/267506.html (ZH)
- https://www.anquanke.com/post/id/86075 (ZH)


## Java JNDI Injection
- Shameless self promotion 1(https://y4y.space/2021/06/04/learning-jndi-injection-from-cve-2021-21985/) (EN)

## Java Spring (Boot) FrameWork
### Theory
- Beans (https://blog.csdn.net/weixin_43232955/article/details/105755021) (ZH)
- Beans (https://blog.csdn.net/qq_39411208/article/details/88395875) (ZH)

# Code Review

## Java
- https://xz.aliyun.com/t/1633/ (ZH)
- https://www.freebuf.com/articles/web/194836.html (ZH)
- https://www.cnblogs.com/afanti/p/13156152.html (ZH)


# Pwn
## Heap 

### Articles
- https://www.anquanke.com/post/id/236832 (ZH)


## Browser 

### WebKit
- JSC Internals - 1 https://zon8.re/posts/jsc-internals-part1-tracing-js-source-to-bytecode/ (EN)
- 

### V8
- this guy has an entire series on V8 (https://www.anquanke.com/member.html?memberId=161290) (ZH)

# CodeQL

## Theory
- https://testbnull.medium.com/how-does-semmle-core-codeql-works-g%C3%B3c-nh%C3%ACn-phi%E1%BA%BFn-di%E1%BB%87n-v%E1%BB%81-c%C3%A1ch-ho%E1%BA%A1t-%C4%91%E1%BB%99ng-c%E1%BB%A7a-codeql-part-1-e821df1d910e (VI)
- https://testbnull.medium.com/how-does-the-semmle-core-works-part-2-75feed1bb390 (VI)

## Documents
- https://github.com/xsser/codeql_chinese (ZH)

## Developing \ Real Life Example
### General Learning Series
- https://www.4hou.com/search-post?page=2&keywords=codeql (ZH)

### Java
- https://cloud.tencent.com/developer/article/1621363 (ZH)
- JDK Proxy related (https://www.jianshu.com/p/269afd0a52e6) (ZH)

### Research
- Shameless self promotion 3 (https://y4y.space/2021/06/25/a-research-on-generating-codeql-database-for-close-sourced-applications/) (EN)

# BlockChain
- Devansh's entire series on blockchain security (https://devansh.xyz/posts/) (EN)

# CTF

## General Write Up
- https://www.anquanke.com/post/id/242237 (ZH)

## Web

- PHP Disabled Functions Bypass (https://www.anquanke.com/post/id/240036) (ZH)
- PHP Dangerous Functions (https://chybeta.github.io/2017/08/08/php%E4%BB%A3%E7%A0%81-%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E/) (ZH)
- All Talks\Presentations By Orange Tsai (https://github.com/orangetw/My-Presentation-Slides) (ZH/EN)

# Vulnerability/CVE Analysis
- testanull's blog (https://testbnull.medium.com/) (VI)
- my blog, I mean I didn't analyze many but here you go (https://y4y.space) (EN)
- follow Orange Tsai's twitter

# OSCP
- ippsec's video
- hackthebox
- as of December of 2021, to be fair, OSCP is not that hard to pass, it's more about enumeration. The buffer overflow machine is a freebie, don't skip that shit. There are literally a million write ups/posts on how to take on OSCP, just search for your own benefit.
