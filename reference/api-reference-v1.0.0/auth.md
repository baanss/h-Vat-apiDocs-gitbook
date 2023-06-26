---
description: 인증 API
---

# 🔐 Auth

{% hint style="info" %}
User의 Login 정보 (Tokens)를 다루는 API입니다.
{% endhint %}

{% hint style="success" %}
JWT를 통해 생성된 AccessToken과 RefreshToken을 사용합니다.\


header -> set-cookie 에 RefreshToken을 위치하고\
bearerToken으로 AccessToken을 이용하여\


SecretOrKey를 통해 User와 Admin을 구분합니다.
{% endhint %}

## GET /auths

유저의 AccessToken (Bearer JWT Token) 을 확인하여\
현재 접속중인 유저의 정보를 전달

{% swagger src="../../.gitbook/assets/h-vat (1).yaml" path="/auths" method="get" %}
[h-vat (1).yaml](<../../.gitbook/assets/h-vat (1).yaml>)
{% endswagger %}

## POST /auths/login

사용자 로그인 (with email & password)

{% swagger src="../../.gitbook/assets/h-vat (1).yaml" path="/auths/login" method="post" %}
[h-vat (1).yaml](<../../.gitbook/assets/h-vat (1).yaml>)
{% endswagger %}

## POST /auths/logout

사용자 로그아웃 (AccessToken, RefreshToken BlackList로 관리)

유저의 AccessToken과 cookie의 RefreshToken을 만료처리

{% swagger src="../../.gitbook/assets/h-vat (1).yaml" path="/auths/logout" method="post" %}
[h-vat (1).yaml](<../../.gitbook/assets/h-vat (1).yaml>)
{% endswagger %}

## POST /auths/restore-token

AccessToken 재발급 ( cookie의 RefreshToken을 사용하여)

{% swagger src="../../.gitbook/assets/h-vat (1).yaml" path="/auths/restore-token" method="post" %}
[h-vat (1).yaml](<../../.gitbook/assets/h-vat (1).yaml>)
{% endswagger %}

