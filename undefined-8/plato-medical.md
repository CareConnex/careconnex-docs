---
description: >-
  Dr.OZ와 Plato Medical을 연동하여 Plato에 등록된 환자 정보와 의료기록을 Dr.OZ에서 확인할 수 있도록 설정하는 방법을
  안내합니다.
---

# Plato Medical 연동

{% hint style="info" %}
📘 **이 페이지에서 배우는 내용**

* Plato Medical 연동에 필요한 정보
* Plato Medical 연동 설정 방법
* 연결 테스트 및 연동 완료 방법
{% endhint %}

### Plato Medical 연동 설정

Dr.OZ와 Plato Medical을 연동하면 **Plato에 등록된 환자와 Dr.OZ 환자를 연결**하여 Dr.OZ의 환자 상세 화면에서 Plato 의료기록을 확인할 수 있습니다.

📌 **경로: 설정 > 병원 설정 > Plato Medical 연동**

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption></figcaption></figure>

#### ① 연동 정보 입력

Plato Medical 연동에 필요한 정보를 입력합니다.

* **데이터베이스 이름**: Plato에서 사용하는 데이터베이스 이름을 입력합니다.
* **API 키**: Plato에서 발급받은 Bearer API Key를 입력합니다.
* **기본 캘린더 ID**: Plato에서 사용할 기본 캘린더 ID를 입력합니다.
* **기본 위치**: 기본 진료 위치를 입력합니다.
* **기본 의사 코드**: 기본으로 사용할 의사 코드를 입력합니다.

> 💡 **API Key 확인 방법**
>
> Plato의 **System Setup > General Settings > API > Generate API Key**에서 API Key를 발급할 수 있습니다.

> 💡 Plato Medical 연동 정보는 병원별 Plato 환경에 따라 다를 수 있습니다.\
> 정확한 **데이터베이스 이름, 캘린더 ID, 위치 및 의사 코드​**는 병원에서 사용 중인 Plato 설정을 확인해 주세요.

#### ② 연결 테스트

필요한 정보를 모두 입력한 후 **연결 테스트**를 클릭합니다.

연결 테스트를 통해 입력한 정보로 Plato Medical과 정상적으로 연결되는지 확인합니다.

#### ③ 설정 저장

연결이 정상적으로 확인되면 **저장**을 클릭하여 연동 설정을 완료합니다.

***

### 연동 완료 후

Plato Medical 연동이 완료되면 **환자 > 환자 상세 > Plato 의료기록**에서 Dr.OZ 환자와 Plato 환자를 연결하고 해당 환자의 의료기록을 확인할 수 있습니다.

환자 연결, Plato 환자 검색, 의료기록 조회, 새로고침 및 연결 해제 방법은 **「Plato 의료기록」 가이드**를 참고해 주세요.
