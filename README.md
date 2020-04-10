Домашнее задание к лекции «Внедрение системы контроля версий»

# NeuroStartUp 

![Logo_Neuro](https://camo.githubusercontent.com/c6727c717cad1e4820481abb87524f90782445c5/68747470733a2f2f692e696d6775722e636f6d2f495a4f525769492e706e67)

**NeuroStartUp** — динамически развивающийся стартап, специализирующийся на поиске с использованием новейших технологий искусственного интеллекта. Наши преимущества:

* Высокая точность поиска
* Высокая скорость поиска
* Низкая цена

Вы можете встроить NeuroStartUp в ваши приложения с помощью следующих сниппетов (кусочков) кода.

JavaScript:
<script src="https://localhost/neuro.sdk.min.js"></script>
Java (Maven):
```

<dependency>
  <groupId>neuro</groupId>
  <artifactId>sdk</artifactId>
  <version>1.0.0</version>
</dependency>

```
iOS (добавьте код в ваш Podfile):

platform :ios, '8.0'
pod "neuro-ios-sdk"

Git — распределённая система контроля версий, которая даёт возможность разработчикам отслеживать изменения в файлах и работать совместно с другими разработчиками. Они могут просто откатить код до рабочего состояния вместо того, чтобы тратить часы на поиски маленькой ошибки или ошибок, ломающих весь код.
Если кратко, то работа Git выглядит так: 
Каждый разработчик скачивает свою локальную версию проекта с сервера Git при помощи команды git clone. Разработчики пишут свои изменения в код проекта. Если в результате разработки, программист создает новый файл с исходным кодом, то ему нужно выполнить команду git add. Чтобы поделиться своими изменениями, нужно выполнить команду git commit, которая сохраняет все изменения в локальную версию проекта, и выполнить команду git push, чтобы отправить свои изменения на сервер. Другие разработчики выполняют команду git pull чтобы скачать все изменения с сервера, в свою локальную версию.

![image_directory](https://user.oc-static.com/upload/2019/07/02/1562070846258_07.jpg)

## Начало работы

Git можно использовать на локальной машине, в одиночной разработке. Более того, для большинства операций достаточно
локальных файлов, Git не будет тормозить из-за сетевых задержек: все операции, которые можно
провести без сети, будут проведены без сетевых обращений.

* установить терминал на ПК, скачав его с оф.сайта
* создать проект
* сохранить изменения
* отправить изменения на сервер
* скачать изменения с сервера на локальную машину
* внести изменения и отправить эти изменения на сервер

Когда вы производите какие-то действия с файлами, Git практически всегда добавляет новые данные
в свою базу. Удалить что-то почти невозможно: как в Wiki-системе, что-то, добавленное один раз,
навсегда остается в истории системы. Вы в любой момент можете откатиться в любую точку и
получить копию даже удаленных файлов.

## Prerequisites

для системы **Windows** скачайте файл по ссылке https://git-for-windows.github.io/
**Linux** — необходимо открыть терминал и установить приложение при помощи пакетного менеджера вашего дистрибутива.
Для **Ubuntu** команда будет выглядеть следующим образом:
<pre class="lang:bash decode:true">sudo apt-get install git</pre>
OS X — воспользуйтесь homebrew. После его установки запустите в терминале:
<pre class="lang:bash decode:true">brew install git</pre>


Примеры
Установка и запуск

## Пошаговый процесс установки и запуска

После устанвоки git, необходимо добавить немного настроек.
Откройте терминал и запустите команды:

</p>
<pre class="lang:bash decode:true">git config --global user.name "My Name"
git config --global user.email myEmail@example.com</pre>

Теперь каждое наше действие будет отмечено именем и почтой. Таким образом, пользователи всегда будут в курсе, кто отвечает за какие изменения — это вносит порядок.
 

## Лицензия
The MIT License (MIT)

Copyright (c) 2016 Lucas Ross Perkins

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE. 