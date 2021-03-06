---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Управление версиями. Git"
subtitle: ""
summary: ""
authors: [Парфенова Елизавета]
tags: []
categories: []
date: 2022-05-06T19:55:31+03:00
lastmod: 2022-05-06T19:55:31+03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: 'Image credit: [**Unsplash**](featured.jpg)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin
  - 吳恩達

tags:
  - Academic
  - 开源

categories:
  - Demo
  - 教程
---


---
**Введение**

Этот пост познакомит вас с термином «система управления версиями». Вы узнаете о git, принципах его работы и о том, что нужно сделать, чтобы начать с ним работать.

**Содержание**

1. Что такое система управления версиями
2. Где применяются системы управления версиями
3. Что такое git, и как он работает
4. Работа с Git
5. Критика git

**Что такое система управления версиями?**

Система управления версиями (также используется определение «система контроля версий», от англ. Version Control System, VCS или Revision Control System) — программное обеспечение для облегчения работы с изменяющейся информацией. Система управления версиями позволяет хранить несколько версий одного и того же документа, при необходимости возвращаться к более ранним версиям, определять, кто и когда сделал то или иное изменение, и многое другое.

**Где применяются системы управления версиями?**

Такие системы наиболее широко используются при разработке программного обеспечения для хранения исходных кодов разрабатываемой программы. Однако они могут с успехом применяться и в других областях, в которых ведётся работа с большим количеством непрерывно изменяющихся электронных документов. В частности, системы управления версиями применяются в Системах автоматизированного проектирования, обычно в составе систем управления данными об изделии (PDM). Управление версиями используется в инструментах конфигурационного управления (Software Configuration Management Tools).

**Что такое git, и как он работает?**

Git — абсолютный лидер по популярности среди современных систем управления версиями. Это развитый проект с активной поддержкой и открытым исходным кодом. Система git была изначально разработана в 2005 году Линусом Торвальдсом — создателем ядра операционной системы Linux. Git применяется для управления версиями в рамках колоссального количества проектов по разработке ПО, как коммерческих, так и с открытым исходным кодом. Система используется множеством профессиональных разработчиков программного обеспечения. Она превосходно работает под управлением различных операционных систем и может применяться со множеством интегрированных сред разработки (IDE).
Контроль версий позволяет вам посмотреть изменения на любом этапе разработки, а также вернуться к любому моменту.  Но это не совсем так. Изменения сохраняются в виде коммитов. По-русски - фиксация. Вы делаете начальный коммит, чтобы сохранить начальное состояние проекта, а затем для каждого изменения. Это работает как снимки состояния.

Кроме того, git позволяет отправлять данные на удаленный сервер. Отправляются не только готовая версия, но и все снимки, таким образом, любой человек из команды может посмотреть историю изменений. К каждому снимку нужно делать комментарий, так работа с git будет проще и понятнее.

Разработка в git ориентирована на обеспечение высокой производительности, безопасности и гибкости распределенной системы.

**Работа с git**

Чтобы начать работать с git,  нужно сделать некоторые действия.  Сначала пользователь должен создать учетную запись на GitHub.  Затем через терминал необходимо установить и настроить некоторые функции и параметры, которые могут понадобиться. Следующим шагом является создание удаленного репозитория (или его клонирование) и подключение к нему системы. В принципе, git готов к работе. Нужные файлы можно локально (в системе) переносить в нужные директории и прописывать команды, которые согласуют локальный репозиторий. Команды: - git add .  - сохранение изменений текущего каталога; -git commut — пояснение к изменениям; - git push — отправка в центральный репозиторий. Есть еще одна команда, которую лучше выполнять перед предыдущими тремя. Это команда git pull, которая загружает изменения, внесенные кем-то другим (или с другой системы). 

**Заключение**

Git нередко критикуют за сложность освоения: одни термины могут быть незнакомы новичкам, а другие — иметь иное значение. Тем не менее git — очень мощная система, предлагающая пользователям широкие возможности. Их изучение займет какое‑то время, однако усвоенные навыки помогут участникам команды работать намного быстрее.