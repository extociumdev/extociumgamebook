---
description: 🛑 Information on this page may differ from the current in-game data.
---

# 3️⃣ Calculate stats

{% tabs %}
{% tab title="ENG" %}
### 🧮 Calculate Stats

💡 **Let’s take a look at how Combat Stats and Special Stats combine to form your final combat power.**

* To make things easier to understand, this guide uses **Phys. DMG (Physical Damage)** as an example.

***

### ◾ What Is Phys. DMG?

**Phys. DMG** is the base physical damage applied when a Hero performs\
**normal attacks, melee attacks, or combo attacks**.

Phys. DMG is **not determined by equipment alone**.\
Skill effects and Special Stats are also taken into account\
to calculate the final damage value.

***

### ✅ 3-Step Guide to Calculating Phys. DMG

#### 1️⃣ Base Phys. DMG + Equipment Phys. DMG

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

First, add together:

* The Hero’s **base Phys. DMG**
* All **Phys. DMG values provided by equipped gear**

In simple terms, this step calculates:

> “My Hero’s base physical damage + all physical damage gained from equipment.”

***

#### 2️⃣ Apply Skill Phys. DMG & Multi-Hit Attack Power Allocation

Next, add the **Phys. DMG granted by skills** to the value calculated in Step 1️⃣.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

Then, multiply the result by the\
**Multi-Hit Attack Power Allocation** assigned to each skill.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

_This process prevents excessive damage when a skill hits multiple times_\
_by distributing the total damage based on the expected number of hits._

_As a result, even multi-hit skills maintain balanced total damage output._

***

#### 3️⃣ Apply Special Stats

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

In the final step, **Special Stat bonuses** are applied.

* Each Special Stat \[ **STR, DEX, INT, CON, WIS, CHA ]** \
  provides a **percentage-based bonus** to Phys. DMG.

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

📘 You can check how much each stat affects Phys. DMG\
on the [**Special Stats – Coefficient**](special-stats/special-stats-coefficient.md) page.

The calculated Special Stat bonuses are applied\
as additional multipliers based on the base Phys. DMG.

***

{% hint style="info" %}
### 📊 Final Phys. DMG Calculation Structure

\[ (Base Phys. DMG + Total Phys. DMG from all equipped items + Skill Phys. DMG) \* Multi-Hit Attack Power Allocation ] \* { 1 + (STR Total \* Phys. DMG-STR Coefficient) + (DEX Total \* Phys. DMG-DEX Coefficient) + (INT Total \* Phys. DMG-INT Coefficient) + (CON Total \* Phys. DMG-CON Coefficient) + (WIS Total \* Phys. DMG-WIS Coefficient) + (CHA Total \* Phys. DMG-CHA Coefficient) }
{% endhint %}
{% endtab %}

{% tab title="한국어" %}
### 🧮 Calculate Stats (스탯 계산)

💡 **전투 스탯과 스페셜 스탯이 어떻게 합쳐져 최종 전투력이 되는지 알아볼까요?**

* 이 가이드에서는 이해를 돕기 위해 **Phys. DMG(물리 데미지)**&#xB97C; 예시로 설명합니다.

***

### ◾ Phys. DMG(물리 데미지)란?

**Phys. DMG**는\
영웅이 **일반 공격 / 근접 공격 / 콤보 공격**을 할 때 적용되는 기본 물리 데미지 수치입니다.

Phys. DMG는 단순히 장비 수치만으로 결정되지 않으며,\
스킬 효과와 스페셜 스탯까지 모두 반영되어 최종 데미지로 계산됩니다.

***

### ✅ Phys. DMG 계산을 위한 3단계 가이드

#### 1️⃣ 기본 Phys. DMG + 장비 Phys. DMG 계산

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

가장 먼저,\
영웅이 기본적으로 가지고 있는 **Phys. DMG**와 장착한 장비에 부여된 **모든 Phys. DMG를 합산**합니다.

쉽게 말해,

> “내 캐릭터의 기본 물리 데미지 + 장비로 얻은 모든 물리 데미지”

를 모두 더하는 단계입니다.

***

#### 2️⃣ 스킬 Phys. DMG 적용 & 공격력 분배

다음으로,\
스킬에 부여된 **Phys. DMG**를 1️⃣ 단계에서 계산한 값에 추가합니다.

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

그 후,\
각 스킬에 설정된 **스킬마다 부여된 다단히트 공격력 분배(Multi-Hit Attack Power Allocation)**&#xB97C; 곱해줍니다.

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

_이는 스킬이 여러 번 타격할 경우,_\
_각 타격의 데미지가 과도해지는 것을 방지하기 위해_\
_총 데미지를 예상 타격 횟수 기준으로 분배하기 위함입니다._

_이를 통해 다단히트 스킬이라도_\
_전체 피해량이 균형 있게 유지됩니다._

***

#### 3️⃣ 스페셜 스탯 적용

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

마지막 단계에서는 **스페셜 스탯 보너스**가 적용됩니다.

* STR, DEX, INT, CON, WIS, CHA\
  각 스페셜 스탯은 Phys. DMG에 **비율 기반 보너스**를 제공합니다.

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

📘 각 스탯이 Phys. DMG에 얼마나 영향을 주는지는\
[**Special Stats – Coefficient**](special-stats/special-stats-coefficient.md) 페이지에서 확인할 수 있습니다.

계산된 스페셜 스탯 보너스는 **기본 Phys. DMG를 기준으로 한 추가 배율**로 적용됩니다.

***

{% hint style="info" %}
### 📊 Phys. DMG 최종 계산 구조

\[ (Phys. DMG최초값 + 장착된 장비에 붙은 모든 Phys. DMG의 총합 + 스킬 공격력 ) \* **다단히트 공격력 분배** ] \* { 1 + ( STR총합 \* Phys. DMG-STR계수 ) + ( DEX총합 \* Phys. DMG-DEX계수 ) + ( INT총합 \* Phys. DMG-INT계수 ) } + ( CON총합 \* Phys. DMG-CON계수 ) } + ( WIS총합 \* Phys. DMG-WIS계수 ) } + ( CHA총합 \* Phys. DMG-CHA계수 ) }
{% endhint %}
{% endtab %}

{% tab title="日本語" %}
### 🧮 ステータス計算（Calculate Stats）

💡 **戦闘ステータス**と**スペシャルステータス**が、\
どのように組み合わさって最終的な戦闘力になるのかを見ていきましょう。

* 本ガイドでは、理解を深めるために **Phys. DMG（物理ダメージ）** を例として説明します。

***

### ◾ Phys. DMG（物理ダメージ）とは？

**Phys. DMG** は、\
ヒーローが **通常攻撃・近接攻撃・コンボ攻撃** を行う際に適用される\
基本的な物理ダメージ数値です。

Phys. DMGは装備の数値だけで決まるものではなく、\
スキル効果やスペシャルステータスを含めて 最終ダメージとして計算されます。

***

### ✅ Phys. DMG計算 3ステップガイド

#### 1️⃣ 基本Phys. DMG ＋ 装備Phys. DMG

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

まず最初に、以下をすべて合算します。

* ヒーローが元々持っている **基本Phys. DMG**
* 装備に付与されている **すべてのPhys. DMG**

簡単に言うと、

> 「キャラクターの基本物理ダメージ＋装備から得た物理ダメージ」

を合計する段階です。

***

#### 2️⃣ スキルPhys. DMG適用 ＆ 多段ヒット攻撃力分配

次に、\
スキルに設定されている **Phys. DMG** を1️⃣で算出した数値に加算します。

<figure><img src="../../../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption></figcaption></figure>

その後、\
各スキルに設定された\
**多段ヒット攻撃力分配（Multi-Hit Attack Power Allocation）**&#x3092;掛け合わせます。

<figure><img src="../../../.gitbook/assets/image (2) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

_これは、スキルが複数回ヒットする場合に_\
_1ヒットあたりのダメージが過剰にならないよう、_\
_総ダメージを想定ヒット回数に応じて分配するための仕組みです。_\
_この処理により、多段ヒットスキルでも_\
_全体のダメージ量がバランスよく保たれます。_

***

#### 3️⃣ スペシャルステータス適用

<figure><img src="../../../.gitbook/assets/image (5) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

最後に、**スペシャルステータスのボーナス**が適用されます。

* STR / DEX / INT / CON / WIS / CHA\
  それぞれのスペシャルステータスは、\
  Phys. DMGに対して **割合ベースのボーナス** を提供します。

<figure><img src="../../../.gitbook/assets/image (4) (1) (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

📘 各ステータスがPhys. DMGに どの程度影響するかについては、\
[**Special Stats – Coefficient**](special-stats/special-stats-coefficient.md) ページで確認できます。

算出されたスペシャルステータスのボーナスは、\
基本Phys. DMGを基準とした 追加倍率として適用されます。

***

{% hint style="info" %}
### 📊 Phys. DMG 最終計算構造

\[ (基本Phys. DMG + 装備によって付与されたPhys. DMGの合計 + スキル攻撃力 ) \* **多段ヒット攻撃力分配** ] \* { 1 + ( STR合計 × Phys. DMG-STR係数 ) + ( DEX合計 × Phys. DMG-DEX係数 ) + ( INT合計 × Phys. DMG-INT係数 ) } + ( CON合計 × Phys. DMG-CON係数 ) } + ( WIS合計 × Phys. DMG-WIS係数 ) } + ( CHA合計 × Phys. DMG-CHA係数 ) }
{% endhint %}
{% endtab %}
{% endtabs %}

<p align="right"><sup><em>※ This guide was written based on the game status as of December 30, 2025,</em></sup> <br><sup><em>and its contents may change with future updates.</em></sup></p>











