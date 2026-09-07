# [게임 이름 : 일격]

<img width="900" height="600" alt="Notion페이지 사용용도" src="https://github.com/user-attachments/assets/4a208d74-dc3c-49b6-a6f3-a336162f74ef" />

## 프로젝트 소개
본 프로젝트는 격투 게임 **FOOTSIES** 오픈소스를 참고하여
2D 격투 게임의 핵심 메커니즘을 학습하고,
이를 바탕으로 직접 구현하고 기능을 확장한 **학습용 프로젝트**입니다.

방향키와 공격 버튼 하나로 즐길 수 있는 간단한 2D 격투게임입니다. 

일반적인 격투 게임과 달리 체력바가 없으며, 강력한 기술 한방으로 상대방을 쓰러뜨리는 게임입니다.

하나의 키보드로 두 명이 대결하는 로컬 2인 대전을 지원합니다.

상대와의 거리를 조절하고 공격을 유도하며, 빈틈을 노린 강력한 일격으로 승리를 거머쥐세요!

---

### 출처 및 라이선스 (Attribution & License)
* **Original Project:** [FOOTSIES by hifight](https://github.com/hifight/Footsies)
* **License:** GNU General Public License v3.0 (GPLv3)
  * 본 프로젝트는 원작 프로젝트의 라이선스 조건을 따라 **GPLv3**로 공개됩니다.

---

## 플레이 영상
>클릭하면 유튜브 영상으로 넘어갑니다.
<img width="600" height="322" alt="플레이" src="https://github.com/user-attachments/assets/224d19de-eb56-409d-bc67-35219d9a1b2d" />

---

## 게임정보

- 장르 : 2D 격투게임
- 플레이 타임 : 5분 이내
- 플랫폼 : Windows
- 개발 환경 : 6000.3.9f1

---

## 플레이어 조작방법

### 1P 입력
이동 : FGH

공격 : A
### 2P 입력
이동 : 방향키(←↓→)

공격 : 오른쪽 Shift

---

## 게임상세

### 타이틀 화면

마우스, 키보드로 메뉴 선택이 가능합니다.

<img width="816" height="457" alt="image" src="https://github.com/user-attachments/assets/d8e4a688-20de-4759-b837-2957e1631078" />

#### 마우스 조작법
마우스 클릭으로 메뉴 진입

#### 키보드 조작법
위 아래 방향키 / WS로 메뉴 선택 가능, Enter로 메뉴 진입

<img width="420" height="333" alt="image" src="https://github.com/user-attachments/assets/cbd2e025-ab6e-4201-8448-5dc79e3a70ac" />

OPTION 메뉴 진입 시, 볼륨 조절 가능

#### 마우스 조작법
볼륨크기 양옆에 있는 화살표를 클릭하여 볼륨 조절, QUIT 클릭 시 타이틀 화면으로 돌아감

#### 키보드 조작법
위 아래 방향키 / WS로 볼륨 메뉴 선택 가능, 왼쪽 오른쪽 방향키 / AD로 선택한 볼륨의 볼륨 조절 가능, QUIT를 선택하고 Enter 입력 시 타이틀 화면으로 돌아감


### 기술표
※1P기준

#### 가드 : ←

<img width="400" height="205" alt="가드" src="https://github.com/user-attachments/assets/b28e2157-d5b7-4ce2-8c81-11a28414bd11" />

상대방이 공격하고 있을 때 후방키를 누르고 있으면 자동으로 가드합니다. 

#### 앞 대쉬 : →→

<img width="400" height="205" alt="앞대쉬" src="https://github.com/user-attachments/assets/01d112bd-2751-4edc-a11e-b1c05b07357a" />

앞으로 빠르게 전진합니다. 잔깜동안 무적시간이 있고, 상대방의 뒤로 이동이 가능합니다.
#### 백 대쉬 : ←← 

<img width="400" height="205" alt="백대쉬" src="https://github.com/user-attachments/assets/ebf40e65-1016-48f4-adac-f3f98ec9320d" />

뒤로 빠르게 후퇴합니다. 앞 대쉬처럼 무적시간이 있지 않습니다. 
#### 하단 공격 : 공격 버튼

<img width="400" height="205" alt="하단공격" src="https://github.com/user-attachments/assets/90374851-b816-4af8-a201-c4a610bf0463" />

5프레임 발동 공격입니다. 무릎 공격보다 느리지만 무릎 공격보다 공격 거리가 깁니다. 공격력은 0입니다.

#### 무릎 공격 : → + 공격버튼 OR ← + 공격버튼

<img width="400" height="205" alt="무릎공격" src="https://github.com/user-attachments/assets/6da688a6-0480-4ab7-a432-f613ee3b977d" />

3프레임 발동 공격입니다. 빠르게 발동 되지만 하단 공격보다 공격 거리가 짧습니다. 공격력은 0입니다.
#### 전진 기술 : ↓↙← + 공격 버튼

<img width="400" height="205" alt="전진기술" src="https://github.com/user-attachments/assets/a8257dfc-20e4-4e6b-88f8-1040853fa94c" />

전진성이 있는 기술입니다. 공격력은 1입니다.
#### 무적기 기술: →↓↘ + 공격 버튼

<img width="400" height="205" alt="무적기기술" src="https://github.com/user-attachments/assets/2c3c8205-9403-40b7-a80b-e16c60675f9a" />

6프레임간의 무적기가 있는 기술입니다. 공격력은 1입니다.

**하단 공격, 무릎 공격에서 전진 기술과 무적기로 캔슬할 수 있습니다.**

<img width="400" height="205" alt="하단캔슬" src="https://github.com/user-attachments/assets/d1efef33-2aa6-482b-aee8-e1bc378987f6" />
<img width="400" height="205" alt="무릎캔슬" src="https://github.com/user-attachments/assets/c21609a3-b640-4393-bb83-1644fdf0f204" />

---

## 플레이 방법

### 게임 화면 설명

<img width="600" height="379" alt="게임화면" src="https://github.com/user-attachments/assets/5f00e1ec-b3b9-4ad5-bf28-1672c20cdb91" />

- 가드 브레이크 게이지</br><img width="400" height="205" alt="가드 브레이크" src="https://github.com/user-attachments/assets/8ea1aee9-067d-4d87-bf2f-9895a9cb4823" /></br>
각 플레이어는 3칸의 가드 브레이크 게이지를 가지며, 공격을 가드하거나 피격될 때마다 1칸씩 감소합니다.
게이지가 모두 소진된 상태에서 추가로 공격을 가드하면 가드 브레이크가 발생합니다.
가드 브레이크 상태에서는 일정 시간 행동할 수 없어 상대에게 공격 기회를 내주므로, 남은 게이지를 고려한 신중한 플레이가 필요합니다.


- 라운드 승리 표시<br>
라운드에서 승리할 때마다 해당 플레이어의 가드 브레이크 게이지 밑에 있는 칸에 X 표시가 하나씩 추가되어, 현재까지 승리한 라운드 수를 확인할 수 있습니다. 
3개의 라운드를 먼저 선취한 쪽의 플레이어가 최종 승리합니다.

### 라운드 승리 조건

모든 플레이어의 체력은 1이며, 공격력이 1인 전진 기술 또는 무적기 기술을 상대에게 적중시키면 해당 라운드에서 승리합니다.

상대의 가드 브레이크 게이지를 조금씩 깎아 방어를 무너뜨리거나, 앞대시와 무적기의 무적 시간을 활용해 상대의 공격 타이밍을 노려보세요. 상대가 공격을 마친 뒤 생기는 빈틈을 노리는 것도 좋은 방법입니다.

**상대와의 심리전에서 한 방의 기회를 만들어, 먼저 3개 라운드에서 승리해 보세요!**

---

## 프로젝트 기간

[2026/06/02~ 2026/7/16]

---

## 기술문서

https://app.notion.com/p/3bad6207415c801eb92af9f9221e85dd
