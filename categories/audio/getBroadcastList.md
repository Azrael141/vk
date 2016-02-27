---
layout: default
title: Метод Audio.GetBroadcastList
permalink: audio/getBroadcastList/
comments: true
---
# Метод Audio.GetBroadcastList
Возвращает список друзей и сообществ пользователя, которые транслируют музыку в статус.

Страница документации ВКонтакте [audio.getBroadcastList](https://vk.com/dev/audio.getBroadcastList).

## Синтаксис
``` csharp
public bool GetBroadcastList(string filter, bool? active)
```

## Параметры
+ **filter** - Определяет, какие типы объектов необходимо получить. Возможны следующие значения параметра:

friends — только друзья;
groups — только сообщества;
all — друзья и сообщества. строка, по умолчанию all
+ **active** - 1 — будут возвращены только друзья и сообщества, которые транслируют музыку в данный момент. По умолчанию возвращаются все. флаг, может принимать значения 1 или 0

## Результат
После успешного выполнения возвращает список объектов друзей и сообществ с дополнительным полем status_audio — объект аудиозаписи, установленной в статус (если аудиозапись транслируется в текущей момент).

## Пример
``` csharp
// Пример кода
```

## Версия Вконтакте API v.5.44
Дата обновления: 26.01.2016 19:20:10