---
description: 수술 영상 API
---

# 📹 Videos

{% hint style="info" %}
Annotation을 진행할 Video Data를 다루는 API입니다.
{% endhint %}

## Fetch Videos

Video 리스트 받아오기

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/videos" method="get" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Fetch Video

Video Stream 받아오기

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/videos/{id}" method="get" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Update Videos

Video 일괄 업데이트

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/videos/update-many" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}

## Delete Videos

Video 일괄 삭제

{% swagger src="../../.gitbook/assets/h-vat.yaml" path="/videos/delete-many" method="post" %}
[h-vat.yaml](../../.gitbook/assets/h-vat.yaml)
{% endswagger %}
