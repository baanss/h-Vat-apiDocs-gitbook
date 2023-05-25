---
description: h-vat API 명세입니다 (v1.0.0)
---

# API Reference (v1.0.0)

링크를 클릭하여 각 스키마에 대한 API를 확인하실 수 있습니다.

## Users

h-vat을 사용하는 사용자와 관련된 API

{% content-ref url="users.md" %}
[users.md](users.md)
{% endcontent-ref %}

* [**POST** /users](users.md#users)
* [**GET** /users](users.md#users-1)
* [**PATCH** /users/{id}](users.md#users-id)
* [**PUT** /users/{id}/password](users.md#users-id-password)
* [**DELETE** /users/{id}](users.md#users-id-1)

## Login

사용자 로그인 API

{% content-ref url="login.md" %}
[login.md](login.md)
{% endcontent-ref %}

* [**POST** /login](login.md#login)

## Auth

사용자의 토큰 확인

{% content-ref url="auth.md" %}
[auth.md](auth.md)
{% endcontent-ref %}

* [**GET** /auth](auth.md#auth)

## Videos

작업 대상 Video API

{% content-ref url="videos.md" %}
[videos.md](videos.md)
{% endcontent-ref %}

* [**GET** /videos](videos.md#videos)
* [**GET** /videos/{id}](videos.md#videos-id)
* [**POST** /videos/update-many](videos.md#videos-update-many)
* [**POST** /videos/delete-many](videos.md#videos-delete-many)

## Video Tasks

Video Tasks API

{% content-ref url="video-tasks.md" %}
[video-tasks.md](video-tasks.md)
{% endcontent-ref %}

* [**GET** /video-tasks](video-tasks.md#video-tasks)
* [**GET** /video-tasks/{id}](video-tasks.md#video-tasks-id)
* [**POST** /video-tasks](video-tasks.md#video-tasks-1)
* [**PUT** /video-tasks/{id}/status](video-tasks.md#video-tasks-id-status)
* [**POST** /video-tasks/update-many](video-tasks.md#video-tasks-update-many)
* [**POST** /video-tasks/download-many](video-tasks.md#video-tasks-download-many)
* [**POST** /video-tasks/delete-many](video-tasks.md#video-tasks-delete-many)

## Notification

알림 메시지 API

{% content-ref url="notification.md" %}
[notification.md](notification.md)
{% endcontent-ref %}

* [**GET** /notifications](notification.md#notifications)
* [**POST** /notifications/markAsRead](notification.md#notifications-markasread)

## Annotation

Annotation API

{% content-ref url="annotation.md" %}
[annotation.md](annotation.md)
{% endcontent-ref %}

* [**PUT** /annotations/{id}/data](annotation.md#annotations-id-data)
* [**GET** /anntations/download](annotation.md#annotations-download)
