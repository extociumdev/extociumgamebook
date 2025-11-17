---
description: 🛑 This information may be updated later than the game server data.
icon: square-root
---

# Skill Level Cap System

{% tabs %}
{% tab title="ENG" %}
**💡The Skill Level Cap System limits the effectiveness of a skill based on the level of the equipped hero.**

In EXTOCIUM, heroes can grow through various means such as trading and reloads. This may lead to differences in hero level, weapon grade, and skill level.&#x20;

To preserve the value of invested skills and prevent situations where high-level weapons obtained through trades become unusable due to excessive MP consumption, the following system has been introduced:

## ✅Rules

**⏫When using a skill above the user’s level:**

❗ If the skill level is higher than the user level, MP consumption is based on the user level. \
❗ If the skill level is 5 or more levels above the user level (e.g., 10 vs. 15), the skill level will be adjusted.

{% hint style="info" %}
**❓Skill Level Adjustment:**

**(Skill Level - User (Equipped Hero) Level) \* Weight (50%) = Reduction Level**&#x20;

Example: Hero Level 10, Skill Level 15 \
(15-10)\*0.5=2.5 -> Rounding down to 2 \
10+2=12&#x20;

The skill will consume MP based on level 10 and have effects based on level 12.
{% endhint %}

**⏬When using a skill below the user’s level:**

❗ If the skill level is lower than the user level, an effect debuff will apply. \
❗ If the skill level is 5 levels or more below the user level (e.g., 55 vs. 50), \
👉 The effectiveness will be reduced by a percentage equal to the level difference. \
👉 (e.g., if skill level is 6 levels lower, effect decreases by 6%; if 55 levels lower, effect decreases by 55%). \
❗ \[COST\_MP] remains unchanged.
{% endtab %}

{% tab title="한국어" %}
**💡스킬 레벨 캡 시스템은 착용 중인 영웅의 레벨에 따라 스킬 효과의 범위를 제한하는 시스템입니다.**

EXTOCIUM은 거래 및 리로드 등을 통해 다양한 방식으로 영웅을 성장 시킬 수 있습니다. 이에 따라 영웅의 레벨, 무기 등급, 스킬 레벨 등에 차이가 발생될 수 있습니다.&#x20;

스킬에 투자한 사용자의 가치를 유지하고, 거래를 통해 얻은 무기를 높은 MP소모량으로 사용할 수 없게 되는 상황 등을방지하기 위해 아래와 같은 시스템이 도입되었습니다.

## ✅규칙

**⏫자신 의 레벨보다 높은 레벨의 스킬을 사용할 경우**

❗ 사용자 레벨보다 스킬 레벨이 높을 경우, 사용자 레벨 기반의 MP소모량을 사용합니다.\
❗ 사용자 레벨보다 스킬 레벨이 5 이상 높을 경우 ( 예 ; 10, 15 ) - 스킬 레벨이 보정 됩니다.

{% hint style="info" %}
**❓스킬 레벨 보정하기 :**

**( 스킬 레벨 - 사용자(착용 영웅)레벨 ) \* 가중치(50%) = 감소 레벨**

예 : 영웅 10 Lv, 스킬 15 Lv\
(15-10)\*0.5=2.5 -> 2.5 에서 소수점 버림 처리\
10+2=12

스킬의 MP소모량은 10레벨 기준, 효과 값은 12레벨 기준으로 사용
{% endhint %}

**⏬자신의 레벨 보다 낮은 레벨의 스킬을 사용할 경우**

❗사용자 레벨보다 스킬 레벨이 낮은 경우 효과 디버프가 발생됩니다.\
❗사용자 레벨보다 스킬 레벨이 5 차이 이상일 경우 ( 예 ; 55, 50 ) \
👉레벨 차이 만큼의 효과 감소 %를 적용 \
👉( 예 : 스킬 레벨 6 차이면 효과 6% 감소, 55차이면 55% 감소 )\
❗\[COST\_MP] 는 그대로 적용
{% endtab %}

{% tab title="日本語" %}
💡 **スキルレベルキャップシステムは、装備中の英雄のレベルに基づきスキル効果の範囲を制限するシステムです。**

EXTOCIUMでは、取引やリロードを通じて英雄を様々な方法で成長させることが可能です。これにより、英雄レベル、武器グレード、スキルレベルに差異が生じる場合があります。

投資したスキルの価値を保持し、取引で得た武器が高いMP消費で使用できなくなる状況を防ぐため、以下のシステムが導入されました。

## ✅ルール

**⏫ユーザーレベルより高いレベルのスキルを使用する場合**

❗ スキルレベルがユーザーレベルより高い場合、ユーザーレベルに基づいたMP消費量を使用します。 \
❗ スキルレベルがユーザーレベルより5以上高い場合（例：10、15）、スキルレベルが調整されます。

{% hint style="info" %}
❓ スキルレベル調整

(スキルレベル - ユーザー（装着英雄）レベル) \* 重み（50％） = 減少レベル

&#x20;例：英雄10Lv、スキル15Lv \
(15-10)\*0.5=2.5 -> 小数点切り捨てで2 \
10+2=12&#x20;

スキルのMP消費は10レベル基準、効果値は12レベル基準で使用されます。
{% endhint %}

**⏬ユーザーレベルより低いレベルのスキルを使用する場合**

❗ スキルレベルがユーザーレベルより低い場合、効果ディバフが発生します。 \
❗ スキルレベルがユーザーレベルより5以上差がある場合（例：55、50） \
👉 レベル差に応じた効果減少％が適用されます。 \
👉（例：スキルレベルが6レベル差であれば効果6％減少、55レベル差であれば55％減少） \
❗ \[COST\_MP] はそのまま適用されます。
{% endtab %}
{% endtabs %}

