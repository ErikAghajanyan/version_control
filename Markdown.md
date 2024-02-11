# Introduction

## Work with text

**Bold text**

__Bold text__

*Italics*

_Italics_

~~Example~~

***Bold Italics***

_**Bold Italics**_

## Work with lists

* example

+ example

1. first

2. second

3. three

## Work with images

![ALBERT](IMG_0118.jpg "1 years")

![image with url](https://logos.flamingtext.com/Name-Logos/Sa-design-china-name.png "sa")
## Work with links

[link](https://www.google.ru/search?q=super+programist&tbm=isch&ved=2ahUKEwj-uIG4_5GEAxXIgv0HHY27Bz4Q2-cCegQIABAA&oq=super+programist&gs_lp=EgNpbWciEHN1cGVyIHByb2dyYW1pc3RI-nBQ10hYvWxwAHgAkAEAmAHZAaABphOqAQYwLjE2LjG4AQPIAQD4AQGKAgtnd3Mtd2l6LWltZ8ICChAAGIAEGIoFGEPCAg0QABiABBiKBRhDGLEDwgIFEAAYgATCAgsQABiABBixAxiDAcICDhAAGIAEGIoFGLEDGIMBwgIEEAAYHsICBxAAGIAEGAKIBgE&sclient=img&ei=kqy_Zf6nJsiF9u8Pjfee8AM&bih=738&biw=1536 "super")

# Основы Git - Работа с удалёнными репозиториями

## Просмотр удалённых репозиториев

```sd 
$ git clone https://github.com/schacon/ticgit
Cloning into 'ticgit'...
remote: Reusing existing pack: 1857, done.
remote: Total 1857 (delta 0), reused 0 (delta 0)
Receiving objects: 100% (1857/1857), 374.35 KiB | 268.00 KiB/s, done.
Resolving deltas: 100% (772/772), done.
Checking connectivity... done.
$ cd ticgit
$ git remote origin
```

## Добавление удалённых репозиториев

``` sd
$ git remote
origin
$ git remote add pb https://github.com/paulboone/ticgit
$ git remote -v
origin	https://github.com/schacon/ticgit (fetch)
origin	https://github.com/schacon/ticgit (push)
pb	https://github.com/paulboone/ticgit (fetch)
pb	https://github.com/paulboone/ticgit (push)
```