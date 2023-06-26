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

1. request header cookie의 유저 토큰 검사,
   1. 유저의 토큰이 유효하지 않을 때 : 401 Unauthorized
2. 사용자가 admin인지 확인
   1. admin이 아닌 경우 : 403 Forbidden
3. User 생성
4. 생성된 annotator의 이메일로 로그인 경로 및 방법 전송
5. 성공여부 response

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/users" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Fetch Users

User 리스트 가져오기

{% hint style="info" %}
_입력 가능한 Role (Annotator, Inspector)_
{% endhint %}

* 입력한 Role에 따른 결과가 출력되며, 미입력시 Admin을 제외한 User 목록을 전달.

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/users" method="get" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Patch Specific User

User 정보 변경

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/users/{id}" method="patch" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Change user Password

User password 변경

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/users/{id}/password" method="put" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}

## Delete User

User 삭제

{% swagger src="../../.gitbook/assets/h-vat (1) (1).yaml" path="/users/{id}" method="delete" %}
[h-vat (1) (1).yaml](<../../.gitbook/assets/h-vat (1) (1).yaml>)
{% endswagger %}
