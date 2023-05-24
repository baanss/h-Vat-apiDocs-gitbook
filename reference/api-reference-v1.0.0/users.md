---
description: h-vat 사용자 API
---

# 👨⚕ Users

{% hint style="info" %}
User(사용자) 정보를 다루는 API입니다.
{% endhint %}

{% hint style="success" %}
사용자의 권한은 Annotation 작업을 진행할 수 있는\
**Annotator**, **Inspector** 의 권한과

사용자들을 관리하는 **Admin** 의 권한이 존재합니다.
{% endhint %}

## Create User

User 생성

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Fetch Users

User 리스트 가져오기

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users" method="get" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Patch Specific User

User 정보 변경

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users/{id}" method="patch" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Change user Password

User password 변경

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users/{id}/password" method="put" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Delete User

User 삭제

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users/{id}" method="delete" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}
