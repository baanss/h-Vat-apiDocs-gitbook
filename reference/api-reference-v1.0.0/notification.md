---
description: 알림 API
---

# 🔔 Notification

{% hint style="info" %}
알림에 관한 Data를 다루는 API입니다.&#x20;
{% endhint %}

## Fetch Notifications

Notification List 받아오기

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/notifications" method="get" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Update Notification

Notification 읽음으로 변경

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/notifications/markAsRead" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}
