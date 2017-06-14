# Game

> Пройди несложную игру
> `ssh game.nsychev.ru:5001, game:game`

## Write-up

*Весь таск, в том числе исходники игры взяты с [QCTF Starter 2016](https://github.com/HackerDom/qctf-starter-2016/wiki/%D0%9A%D0%BE%D0%BE%D1%80%D0%B4%D0%B8%D0%BD%D0%B0%D1%82%D0%BE%D1%80%D1%8B-III)*

Было два варианта решения таска: первый — просто взять и пройти игру вручную, второй — написать эксплойт.

Со вторым вариантом были проблемы, т.к. самая популярная SSH-библиотека на Python (Paramiko) почему-то не работала с моим дефолтным шеллом
(игра была поставлена как default shell у пользователя game). Однако, есть успешный эксплойт на C# от Ильи Гаврилова.

Флаг: *uctf_you_have_won*