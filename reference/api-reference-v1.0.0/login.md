---
description: 사용자의 로그인 API
---

# 🔑 Login

{% hint style="info" %}
사용자의 Login을 다루는 API입니다.
{% endhint %}

{% hint style="success" %}
JWT 토큰을 이용해 Header - Set-Cookie 값으로 AccessToken을 전달합니다.
{% endhint %}

{% hint style="warning" %}
유효기간 및 LogOut이 구현되어있지 않습니다. 보완이 필요합니다.
{% endhint %}

## User Login

사용자 로그인

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/login" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}
