---
description: 🛑 This information may be updated later than the game server data.
---

# 3️⃣ Calculate stats

{% tabs %}
{% tab title="ENG" %}
💡 **Shall we explore how to calculate the final combat stats using combat stats and special stats?**

Let's take **Attack Points (AP)** as an example!

## ✅3-Step Guide for Calculating AP

**AP (Attack Points)** refers to the attack power used by a hero during normal/melee/combo attacks, and it is calculated in the following 3 steps:

### **1️⃣** Calculate the total of base AP and equipment AP

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

* First, calculate the total AP attached to the equipment. This also includes the base AP value assigned to the hero.
* In other words, you add together the **hero's base attack power** and the **attack power gained from equipment**.

### **2️⃣** Add skill AP and distribute attack power

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

* Add the AP attached to the skill to the value obtained in step 1️⃣.

<figure><img src="../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

* Next, multiply it by the **Multi-Hit Attack Power Allocation** assigned to each skill.
  * For example, if a skill fires multiple projectiles, the total attack power is divided by the number of projectiles or expected hit counts to prevent each projectile's attack power from being too high. This way, the attack power is evenly distributed even if the skill hits multiple times.

### **3️⃣** Apply special stats

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

* Finally, apply the special stats. These special stats are additional bonuses based on attributes like **STR, DEX, CON, WIS, CHA**.

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* Refer to the coefficient table related to AP in the diagram, and multiply the total value of each stat (e.g., STR, DEX) by its respective coefficient. For more details, refer to the [**Special Stats - Coefficient**](special-stats/special-stats-coefficient.md) page.
* Add **1** to the calculated result to make it a positive percentage value, representing the bonus rate added to the base attack power.

{% hint style="info" %}
#### 📊 AP Final Calculation Example

* The final calculation formula for **AP (Attack Points)** is structured as follows:

\[ (Initial AP + Total AP from all equipped items + Skill AP) \* Multi-Hit Attack Power Allocation ] \* { 1 + (STR Total \* AP-STR Coefficient) + (DEX Total \* AP-DEX Coefficient) + (INT Total \* AP-INT Coefficient) + (CON Total \* AP-CON Coefficient) + (WIS Total \* AP-WIS Coefficient) + (CHA Total \* AP-CHA Coefficient) }
{% endhint %}
{% endtab %}

{% tab title="한국어" %}
💡 **전투 스탯과 스페셜 스탯을 이용해 최종 전투스탯을 계산하는 방법을 알아볼까요?**&#x20;

어택포인트 (AP)를 예시로 들어볼게요!

## ✅AP 계산을 위한 3단계 가이드

**AP** (어택 포인트)는 영웅이 일반공격/밀리공격/콤보공격을 할 때 사용되는 공격력을 의미하며, 이를계산하기 위해 아래 3단계를 거칩니다.

### **1️⃣ 기본 AP와 장비 AP의 총합 계산**

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

* 먼저, **장비에 붙어 있는 AP의 총합**을 구합니다. 여기에는 **영웅에게 부여된 기본 AP 값**도 포함됩니다.
* 쉽게 말해, **영웅의 기본 공격력**과 **장비를 통해 얻은 공격력**을 모두 더하는 것입니다.

### **2️⃣ 스킬 AP 추가 및 공격력 분배**

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

* **스킬에 붙은 AP**를 **1️⃣**에서 구한 값에 더합니다.

<figure><img src="../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

* 그 다음, \*\***스킬마다 부여된 다단히트 공격력 분배(Multi-Hit Attack Power Allocation)**\*\*를 곱해줍니다.
  * 예를 들어, 스킬이 여러 개의 탄환을 발사할 경우, 각 탄환의 공격력이 너무 높아지는 것을 막기 위해 **총 공격력을 탄환의 수 혹은 예상 타격 횟수로 나누어** 계산합니다. 이렇게 하면 스킬이 여러 번 타격을 해도 **공격력이 균형 있게 분배**됩니다.

### **3️⃣ 스페셜 스탯 적용**

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

* 마지막으로, **스페셜 스탯**을 적용해줍니다. 이 **스페셜** 스탯은 **STR, DEX, CON, WIS, CHA** 등의 능력치를 기반으로 한 추가 보너스입니다.

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* 도표에서 **AP와 관련된 계수**를 참고하여 **각각의 스탯(STR, DEX, 등등)의 총합**에 계수**를 곱한 값**을 모두 더합니다. [Special Stats - Coefficient ](special-stats/special-stats-coefficient.md)페이지를 참고해주세요.
* 계산된 결과에 **1을 더하여 최종 양수 퍼센트 형태로** 만들어줍니다. 이 값은 **기본 공격력에 추가되는 보너스 비율**을 나타냅니다.

{% hint style="info" %}
#### 📊 AP 최종 계산 방식 예시

* AP(어택 포인트)의 최종 계산 방식은 아래와 같은 구조입니다:

\[ (AP최초값 + 장착된 장비에 붙은 모든 AP의 총합 + 스킬 공격력 ) \* **다단히트 공격력 분배** ] \* { 1 + ( STR총합 \* AP-STR계수 ) + ( DEX총합 \* AP-DEX계수 ) + ( INT총합 \* AP-INT계수 ) } + ( CON총합 \* AP-CON계수 ) } + ( WIS총합 \* AP-WIS계수 ) } + ( CHA총합 \* AP-CHA계수 ) }
{% endhint %}


{% endtab %}

{% tab title="日本語" %}
💡 **戦闘ステータスとスペシャルステータスを使用して最終的な戦闘ステータスを計算する方法を見てみましょうか？**

アタックポイント (AP)を例にしてみます！

## ✅AP計算のための3ステップガイド

\*\*AP（アタックポイント）\*\*は英雄が通常/近接/コンボ攻撃を行う際に使用される攻撃力を指し、以下の3つのステップで計算されます。

### **1️⃣** 基本APと装備APの合計を計算

<figure><img src="../../../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

* まず、装備に付与されているAPの合計を求めます。ここには、英雄に割り当てられた基本APの値も含まれます。&#x20;
* つまり、英雄の基本攻撃力と装備から得た攻撃力を全て足し合わせます。

### **2️⃣** スキルAPの追加と攻撃力の分配

<figure><img src="../../../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

* スキルに付与されているAPをステップ1️⃣で求めた値に加えます。

<figure><img src="../../../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

* その後、各スキルに割り当てられた**マルチヒット攻撃力の分配**を掛けます。
  * 例えば、スキルが複数の弾を発射する場合、各弾の攻撃力が高くなりすぎないように、総攻撃力を弾の数や予想されるヒット回数で割って計算します。これにより、スキルが複数回ヒットしても攻撃力が均等に分配されます。

### **3️⃣** スペシャルステータスの適用

<figure><img src="../../../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

* 最後に、スペシャルステータスを適用します。これらのスペシャルステータスは、**STR、DEX、CON、WIS、CHA**などの属性に基づく追加ボーナスです。

<figure><img src="../../../.gitbook/assets/image (43).png" alt=""><figcaption></figcaption></figure>

* APに関連する係数表を参照し、各ステータス（例えばSTR、DEXなど）の合計にそれぞれの係数を掛けた値を全て足します。詳細については、[**Special Stats - Coefficient**](special-stats/special-stats-coefficient.md)ページを参照してください。
* 計算結果に**1を加えて**最終的に正のパーセンテージの形にします。この値は基本攻撃力に追加されるボーナス率を表します。

{% hint style="info" %}
#### 📊 AP最終計算例

* \*\*AP（アタックポイント）\*\*の最終計算式は次のような構造です：

\[ (初期AP + 装備したすべてのAPの合計 + スキルAP) \* マルチヒット攻撃力分配 ] \* { 1 + (STR合計 \* AP-STR係数) + (DEX合計 \* AP-DEX係数) + (INT合計 \* AP-INT係数) + (CON合計 \* AP-CON係数) + (WIS合計 \* AP-WIS係数) + (CHA合計 \* AP-CHA係数) }
{% endhint %}
{% endtab %}
{% endtabs %}







