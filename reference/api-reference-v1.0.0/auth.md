---
description: 인증 API
---

# 🔐 Auth

{% hint style="info" %}
User의 Login 정보 (Tokens)를 다루는 API입니다.
{% endhint %}

{% hint style="success" %}
JWT를 통해 생성된 AccessToken을 사용합니다.
{% endhint %}

{% hint style="warning" %}
RefreshToken을 사용한 Restore AccessToken 등 보완이 필요합니다.
{% endhint %}

## Check Token

현재 로그인한 유저의 인증 정보 (AccessToken) 확인

{% swagger src="../../.gitbook/assets/h-vat (1).yaml" path="/auth" method="get" %}
[h-vat (1).yaml](<../../.gitbook/assets/h-vat (1).yaml>)
{% endswagger %}
