---
description: 수술 영상 Tasks API
---

# 🕹 Video Tasks

{% hint style="info" %}
Video Data를 이용한 Task들을 다루는 API입니다.&#x20;
{% endhint %}

## Fetch Video Tasks

VideoTask 리스트 받아오기

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks" method="get" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Fetch Video Task

Video Task Detail 가져오기

{% swagger src="../../.gitbook/assets/h-vat (1) (1) (1).yaml" path="/video-tasks/{id}" method="get" %}
[h-vat (1) (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1) (1).yaml>)
{% endswagger %}

## Create Video Task

Video Task 생성

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks" method="post" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Update Video Task Status

Video Task Status 변경

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks/{id}/status" method="put" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Update Video Tasks

Video Task 일괄 업데이트

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks/update-many" method="post" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Fetch(Download) Video Tasks

Video Task 일괄 다운로드

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks/download-many" method="post" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Delete Video Tasks

Video Task 일괄 삭제

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/video-tasks/delete-many" method="post" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}
