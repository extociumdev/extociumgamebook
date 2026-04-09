---
description: 🛑 Information on this page may differ from the current in-game data.
---

# 5️⃣ Buff Guide

{% tabs %}
{% tab title="ENG" %}
**❓This guide explains how Buffs, Debuffs, Status Effects, and Rune Debuffs are calculated in a simple way.**

### ◾Understanding Buffs

* Buff types are categories of effects.\
  Different types—like Damage, Shield, and Movement Speed—are calculated separately.
* Buffs of the same type are grouped together and calculated first.
* When multiple **Active Buffs** of the same type overlap, an **overload penalty** occurs, reducing efficiency from the second buff onward.
* When multiple **Debuffs** of the same type are applied, only the strongest one takes effect first.
* **Rune Debuffs** work on a 1:1 basis and are applied **last**, after all other calculations.

***

### ◾Terminology

<table><thead><tr><th width="124.727294921875">Term</th><th>Description</th><th>Example</th></tr></thead><tbody><tr><td>Status Effect</td><td>An effect that forcibly moves you or the target, or restricts actions.</td><td>Knockback, Stun</td></tr><tr><td>Buff</td><td>Broadly, this refers to any effect that changes stats. In-game, it usually means a beneficial effect.</td><td>Damage Increase, Shield, Movement Speed Increase</td></tr><tr><td>Debuff</td><td>An effect that lowers stats or puts the target at a disadvantage.</td><td>Movement Speed Decrease, Healing Reduction</td></tr><tr><td>Buff Type</td><td>The label or category of an effect. Only effects of the same type are compared or combined.</td><td>Damage Buff, Shield Buff, Movement Speed Buff</td></tr></tbody></table>

***

### ◾Common Symbols in Tables

<table><thead><tr><th width="159">Notation</th><th>Meaning</th></tr></thead><tbody><tr><td>n%</td><td>The percentage of increase or decrease.</td></tr><tr><td>m sec</td><td>Occurs once every m seconds.</td></tr><tr><td>N sec</td><td>How long the effect lasts.</td></tr><tr><td>Final Value</td><td>The value that remains after the base value and all buff/debuff calculations are completed.</td></tr></tbody></table>

***

### ◾Active Buff vs Passive Buff

<table><thead><tr><th width="145.63641357421875">Type</th><th>Simple Explanation</th><th>Main Categories / Examples</th></tr></thead><tbody><tr><td>Active Buff</td><td>A buff that the player activates directly and that lasts for a set time. It can be removed or weakened by enemies or by the system.</td><td>Hero Skill (2), Weapon Skill (1), Inheritance Skill (1), Food Skill</td></tr><tr><td>Passive Buff</td><td>An effect that is always applied as long as its condition is met. It has no duration, and the system keeps it active continuously.</td><td>Arena Champion Effect, PKer Debuff, Party Formation Buff, Famine and Abundance</td></tr></tbody></table>

### ◾Buff Calculation

#### 1️⃣ Basic Formula (Easy Version)

Buffs of the same type can be summed in one line.

{% hint style="success" %}
#### Basic Formula

> Final Value = Base Value × <mark style="color:purple;">**(1 +**</mark> <mark style="color:$danger;">**Total Buff**</mark><mark style="color:purple;">**)**</mark>

Example:\
Base Damage = 100\
Buffs = 30% + 20%

→ 100 × (1 + 0.3 + 0.2) = 150\
→ Result: 100 becomes 150
{% endhint %}

> This is the simplest way to understand the system.
>
> However, in real combat, **Active Buff Overload** applies.

#### 2️⃣ Active Buff Overload

<figure><img src="../../../../.gitbook/assets/Skill_Overload.png" alt=""><figcaption></figcaption></figure>

When multiple Active Buffs of the same type overlap, their efficiency decreases in order, starting from the highest value.

| Rank                | Applied Rate     |
| ------------------- | ---------------- |
| 1st (Highest Value) | 100%             |
| 2nd                 | 80%              |
| 3rd                 | 60%              |
| 4th                 | 40%              |
| 5th                 | 20%              |
| 6th and beyond      | 0% (Not Applied) |

{% hint style="info" %}
**Calculation Order**

1\) Gather only Active Buffs of the same type

2\) Sort them from highest to lowest

3\) Apply scaling:

* 1st: 100%
* 2nd: 80%
* 3rd: 60%

4\) Add adjusted values together

5\) Multiply by base value
{% endhint %}

> **Example**\
> Hero Skill Damage Buff: 70%\
> Food Damage Buff: 20%
>
> → 70% × 100% = 70%\
> → 20% × 80% = 16%\
> → Total Buff = 86%
>
> Final Damage = Base Damage × (1 + 0.86)
>
> If base damage is 100 → Result = 186

#### 3️⃣ Different Types Are Calculated Separately

Damage Buff and Movement Speed Buff are different types.\
They do not compete and are calculated independently.

***

#### ◾Debuff Calculation

Unlike buffs, Debuffs of the same type do **not stack**.

{% hint style="info" %}
**Rules**

1\) Only the highest value is applied first

2\) If values are equal, the longer duration applies

3\) If both exist:

* Highest value applies first
* When it ends, the longer duration continues
{% endhint %}

> **Example**\
> Movement Speed -40% (3s) + -30% (10s)
>
> → First 3s: -40%\
> → Next 7s: -30%
>
> Debuffs don’t stack—they **take turns**, starting from the strongest.

***

### ◾Rune Debuff Application

❓Succession Heroes can [equip Runes on Succession skills](../../../hero-ascension/succession/skill-rune.md).

<figure><img src="../../../../.gitbook/assets/SkillRune_6_white.png" alt=""><figcaption></figcaption></figure>

#### 1️⃣ Rune Works 1:1

Rune effects apply only between you and the target.

> **Example:**
>
> Target has 60% Shield\
> You apply 20% Shield Penetration Rune
>
> → For you: Shield is treated as 40%\
> → For others: Still 60%

#### 2️⃣ Same-Type Runes Stack

Runes of the same type are added together.

Example:\
10% + 15% → Total 25%

#### 3️⃣ Runes Apply Last

{% hint style="info" %}
**Order**

1\) Calculate target’s base stats

2\) Apply skill buffs/debuffs

3\) Finalize target’s stats

4\) Apply your Rune Debuff
{% endhint %}

> **Example: CDR → Rune**
>
> Base CDR = 10\
> Buff +50% → 10 × (1 + 0.5) = 15
>
> Apply Rune (-10 Reload Time) → Final = 5s
>
> 👉 Key Point: Runes don’t interrupt the process—they modify the **final result**.
{% endtab %}

{% tab title="한국어" %}
**❓이 문서는 버프, 디버프, 상태이상, 룬 디버프의 계산 원리를 쉽게 풀어 설명합니다.**

### ◾버프 이해하기

* 버프 타입은 효과의 종류표입니다. 데미지, 실드, 이동속도처럼 종류가 다르면 서로 따로 계산합니다.&#x20;
* 같은 타입의 버프는 먼저 한 바구니에 모아서 계산합니다.&#x20;
* 같은 타입의 액티브 버프가 여러 개 겹치면 과부하가 생겨, 두 번째 버프부터 효율이 줄어듭니다.&#x20;
* 같은 타입의 디버프가 여러 개 걸리면 가장 강한 1개만 먼저 적용됩니다.&#x20;
* 룬 디버프는 1:1로만 작동하고, 모든 스킬 버프/디버프 계산이 끝난 뒤 마지막에 다시 적용됩니다.

***

### ◾용어 정리

<table><thead><tr><th width="124.727294921875">용어</th><th>설명</th><th>예</th></tr></thead><tbody><tr><td>상태이상</td><td>나 또는 대상을 강제로 움직이게 하거나 행동을 제한하는 효과입니다.</td><td>넉백, 스턴</td></tr><tr><td>버프</td><td>넓게는 능력치에 영향을 주는 효과 전반을 가리키는 말입니다. 게임 안에서는 보통 좋은 효과를 뜻합니다.</td><td>데미지 증가, 실드, 이동속도 증가</td></tr><tr><td>디버프</td><td>능력치를 깎거나, 상대에게 불리한 상태를 만드는 효과입니다.</td><td>이동속도 감소, 회복량 감소</td></tr><tr><td>버프 타입</td><td>효과의 이름표입니다. 같은 타입끼리만 서로 비교하거나 합쳐집니다.</td><td>데미지 버프, 실드 버프, 이동속도 버프</td></tr></tbody></table>

***

### ◾표를 읽을 때 자주 나오는 기호

<table><thead><tr><th width="159">표기</th><th>뜻</th></tr></thead><tbody><tr><td>n%</td><td>증가 또는 감소하는 비율입니다.</td></tr><tr><td>m초</td><td>몇 초마다 한 번 일어나는지를 뜻합니다.</td></tr><tr><td>N초</td><td>효과가 얼마 동안 유지되는지를 뜻합니다.</td></tr><tr><td>최종값</td><td>기본값과 각종 버프/디버프 계산이 끝난 뒤 마지막에 남는 값입니다.</td></tr></tbody></table>

***

### ◾액티브 버프와 패시브 버프

<table><thead><tr><th width="145.63641357421875">구분</th><th>쉽게 설명하면</th><th>대표 분류/예시</th></tr></thead><tbody><tr><td>액티브 버프</td><td>유저가 직접 발동해서 일정 시간 동안 유지되는 버프입니다. 상대나 시스템에 의해 지워지거나 약해질 수 있습니다.</td><td>영웅 스킬(2), 무기 스킬(1), 계승 스킬(1), 음식 스킬</td></tr><tr><td>패시브 버프</td><td>조건만 맞으면 항상 적용되는 효과입니다. 지속시간이 없고, 시스템이 계속 유지해 줍니다.</td><td>아레나 우승자 효과, PKer 디버프, 파티 결성 버프, 기근과 풍요</td></tr></tbody></table>

### ◾버프 계산 방식

#### 1️⃣**가장 쉬운 기본식**

같은 타입의 버프는 먼저 한 줄로 더해서 생각하면 쉽습니다.

{% hint style="success" %}
#### Basic Formula

> **최종 수치 = 기본 수치 ×&#x20;**<mark style="color:purple;">**(1 +**</mark>**&#x20;**<mark style="color:orange;">**더해진 버프 총합**</mark><mark style="color:purple;">**)**</mark>&#x20;

예를 들어, 기본 데미지가 100이고 데미지 버프가 30%와 20%라면:\
· 100 × (1 + 0.3 + 0.2) = 150\
· 즉, 100이 150이 됩니다.
{% endhint %}

> 위 식은 원리를 이해하기 가장 쉬운 모습입니다.
>
> 실제 전투에서 같은 타입의 액티브 버프가 겹치면 아래의 과부하 규칙이 추가됩니다.

#### 2️⃣액티브 버프 과부하

<figure><img src="../../../../.gitbook/assets/Skill_Overload.png" alt=""><figcaption></figcaption></figure>

같은 타입의 액티브 버프가 여러 개 겹치면, 큰 값부터 차례대로 효율이 줄어듭니다.

| 순서          | 적용 비율    |
| ----------- | -------- |
| 1순위(가장 큰 값) | 100%     |
| 2순위         | 80%      |
| 3순위         | 60%      |
| 4순위         | 40%      |
| 5순위         | 20%      |
| 6순위부터       | 0% 이하 없음 |

{% hint style="info" %}
**계산 순서**

1\) 같은 타입의 액티브 버프만 모읍니다.

2\) 큰 값부터 줄을 세웁니다.

3\) 1등은 100%, 2등은 80%, 3등은 60%만 인정합니다.

4\) 인정된 값들을 모두 더합니다.

5\) 마지막에 기본값에 곱합니다.
{% endhint %}

> 예시: 영웅 스킬 데미지 버프 70% + 음식 데미지 버프 20%
>
> 70% × 100% = 70%
>
> 20% × 80% = 16%
>
> 총 적용 버프 = 86%
>
> 최종 데미지 = 기본 데미지 × (1 + 0.86)
>
> 기본 데미지가 100이면 186이 됩니다.

#### 3️⃣같은 타입이 아니면 따로 계산

데미지 버프와 이동속도 버프는 서로 다른 버프 타입입니다. \
따라서 서로 경쟁하지 않고 각자 자기 바구니에서 따로 계산합니다.

***

#### ◾디버프 계산 방식

디버프는 버프와 달리, 같은 타입의 디버프가 여러 개 걸려도 모두 더해지지 않습니다. \
규칙은 아주 단순합니다.

{% hint style="info" %}
**디버프 규칙**

1\) 가장 높은 값 1개만 먼저 적용됩니다.

2\) 값이 같다면, 더 오래 남는 것이 적용됩니다.

3\) 높은 값 1개와 시간이 긴 것 1개가 같이 있으면, 높은 값이 먼저 적용되고 그 시간이 끝나면 긴 시간 디버프가 바로 이어서 적용됩니다.
{% endhint %}

> 예시: 이동속도 감소 -40%(3초) + -30%(10초)
>
> 처음 3초: -40% 적용
>
> 그 다음 7초: -30% 적용
>
> 즉, 디버프는 버프처럼 계속 더해지는 구조가 아니라 가장 센 것 1개가 앞에 서는 구조입니다.

***

### ◾룬 디버프 적용 방식

❓계승 영웅의 경우, [계승 스킬에 룬을 세팅할 수 있습니다.](../../../hero-ascension/succession/skill-rune.md#undefined-2)

<figure><img src="../../../../.gitbook/assets/SkillRune_6_white.png" alt=""><figcaption></figcaption></figure>

#### 1️⃣룬은 1:1로만 작동합니다.

룬 효과는 나와 대상 사이에서만 계산됩니다.

> **예시**
>
> 대상이 실드 60%를 켜고 있고, 내가 실드 관통 룬 20%를 적용했다면:
>
> 나와 그 대상 사이에서는 실드 40%처럼 계산됩니다.
>
> 하지만 다른 플레이어와 그 대상 사이에서는 여전히 실드 60%가 유지됩니다.

#### 2️⃣같은 타입 룬은 합산합니다.

같은 타입 룬을 여러 개 장착했다면 값을 더해서 적용합니다. \
예를 들어 관통 룬 10%와 15%를 함께 장착했다면 총 25%로 계산합니다.

#### 3️⃣룬은 항상 마지막에 적용됩니다.

{% hint style="info" %}
**순서**

1\) 대상의 기본 스탯 계산

2\) 대상이 가진 스킬 버프/디버프 반영

3\) 대상의 최종값 완성

4\) 그 다음에 내 룬 디버프 적용
{% endhint %}

> 예시: CDR 버프 후 룬 디버프 적용
>
> 대상의 기본 CDR = 10
>
> 대상이 CDR 버프 50% 사용 → 10 × (1 + 0.5) = 15
>
> 여기에 내 Reload Time Increase -10% 룬 적용 → 15 - 10 = 5s 최종값
>
> 핵심은 룬이 중간에 끼어들지 않고, 마지막 결과값을 다시 깎는다는 점입니다.
{% endtab %}

{% tab title="日本語" %}
**❓このガイドでは、バフ・デバフ・状態異常・ルーンデバフの計算方法をわかりやすく説明します。**

### ◾バフの理解

* バフタイプは効果の種類です。\
  ダメージ、シールド、移動速度など、種類が違えば別々に計算されます。
* 同じタイプのバフは、まず一つにまとめて計算します。
* 同じタイプのアクティブバフが重なると「過負荷」が発生し、2つ目から効率が下がります。
* 同じタイプのデバフは、最も強い1つだけが先に適用されます。
* ルーンデバフは1対1で動作し、すべての計算が終わった後に最後に適用されます。

***

### ◾用語整理

<table><thead><tr><th width="124.727294921875">用語</th><th>説明</th><th>例</th></tr></thead><tbody><tr><td>状態異常</td><td>自分または対象を強制的に動かしたり、行動を制限したりする効果です。</td><td>ノックバック、スタン</td></tr><tr><td>バフ</td><td>広い意味では、能力値に影響を与える効果全体を指します。ゲーム内では通常、有利な効果を意味します。</td><td>ダメージ増加、シールド、移動速度増加</td></tr><tr><td>デバフ</td><td>能力値を下げたり、相手に不利な状態を与えたりする効果です。</td><td>移動速度減少、回復量減少</td></tr><tr><td>バフタイプ</td><td>効果のラベルや分類です。同じタイプ同士だけ比較したり、合算したりします。</td><td>ダメージバフ、シールドバフ、移動速度バフ</td></tr></tbody></table>

***

### ◾表でよく使う記号

<table><thead><tr><th width="159">表記</th><th>意味</th></tr></thead><tbody><tr><td>n%</td><td>増加または減少する割合です。</td></tr><tr><td>m秒</td><td>何秒ごとに1回発生するかを表します。</td></tr><tr><td>N秒</td><td>効果がどれくらいの時間持続するかを表します。</td></tr><tr><td>最終値</td><td>基本値と各種バフ・デバフ計算がすべて終わったあとに残る値です。</td></tr></tbody></table>

***

### ◾アクティブバフとパッシブバフ

<table><thead><tr><th width="145.63641357421875">区分</th><th>かんたんに言うと</th><th>代表的な分類・例</th></tr></thead><tbody><tr><td>アクティブバフ</td><td>プレイヤーが直接発動し、一定時間維持されるバフです。相手やシステムの影響で解除されたり、弱くなったりすることがあります。</td><td>英雄スキル(2)、武器スキル(1)、継承スキル(1)、料理スキル</td></tr><tr><td>パッシブバフ</td><td>条件を満たしている限り、常に適用される効果です。持続時間はなく、システムが継続して維持します。</td><td>アリーナ優勝者効果、PKerデバフ、パーティ結成バフ、飢饉と豊穣</td></tr></tbody></table>

### ◾バフ計算方式

#### 1️⃣基本式（いちばん簡単）**장 쉬운 기본식**

同じタイプのバフはまとめて足して考えます。

{% hint style="success" %}
#### **基本式**

> **最終値 = 基本値 ×&#x20;**<mark style="color:purple;">**(1 +**</mark> <mark style="color:$danger;">**バフ合計**</mark><mark style="color:purple;">**)**</mark>

例：\
基本ダメージ100\
バフ30% + 20%

→ 100 × (1 + 0.3 + 0.2) = 150\
→ 100が150になります。
{% endhint %}

> この式が一番わかりやすい基本形です。
>
> ただし、実戦では「過負荷ルール」が追加されます。

#### 2️⃣ アクティブバフ過負荷

<figure><img src="../../../../.gitbook/assets/Skill_Overload.png" alt=""><figcaption></figcaption></figure>

同じタイプのアクティブバフが複数重なると、数値が大きいものから順に効率が下がります。

| 順位        | 適用率      |
| --------- | -------- |
| 1位（最も高い値） | 100%     |
| 2位        | 80%      |
| 3位        | 60%      |
| 4位        | 40%      |
| 5位        | 20%      |
| 6位以降      | 0%（適用なし） |

{% hint style="info" %}
**計算順序**

1\) 同じタイプのアクティブバフを集める

2\) 大きい順に並べる

3\) 適用倍率

* 1位：100%
* 2位：80%
* 3位：60%

4\) 合計する

5\) 最後に掛ける
{% endhint %}

> **例**\
> スキルバフ70% + 食事バフ20%
>
> → 70% × 100% = 70%\
> → 20% × 80% = 16%\
> → 合計 = 86%
>
> 最終ダメージ = 基本値 × (1 + 0.86)
>
> 基本100 → 186

#### 3️⃣ タイプが違えば別計算

ダメージバフと移動速度バフは別タイプです。\
お互いに影響せず、それぞれ計算されます。

***

#### ◾デバフ計算方式

デバフはバフと違い、重なっても加算されません。

{% hint style="info" %}
**デバフルール**

1\) 最も高い値1つだけ適用

2\) 同じ値なら時間が長い方

3\) 両方ある場合

* 高い値 → 先に適用
* 終了後 → 長時間のものが続く
{% endhint %}

> **例**\
> 移動速度 -40%（3秒） + -30%（10秒）
>
> → 最初3秒：-40%\
> → 次の7秒：-30%
>
> デバフは足し算ではなく、「強いものが前に出る」構造です。

***

### ◾ルーンデバフ適用方式

❓継承英雄は[継承スキルにルーンを装着できます。](../../../hero-ascension/succession/skill-rune.md)

<figure><img src="../../../../.gitbook/assets/SkillRune_6_white.png" alt=""><figcaption></figcaption></figure>

#### 1️⃣ルーンは1対1

ルーン効果は自分と対象の間でのみ適用されます。

> **例：**\
> 対象シールド60%\
> 自分の貫通ルーン20%
>
> → 自分から見ると40%\
> → 他プレイヤーは60%のまま

#### 2️⃣同タイプルーンは合算

同じタイプのルーンは合計されます。

例：\
10% + 15% → 合計25%

#### 3️⃣ルーンは最後に適用

{% hint style="info" %}
**順序**

1\) 基本ステータス計算

2\) スキルバフ・デバフ適用

3\) 最終値確定

4\) ルーンデバフ適用
{% endhint %}

> **例：CDR → ルーン**
>
> 基本CDR = 10\
> バフ50% → 15
>
> ルーン適用 → 最終 5秒
>
> 👉ポイント ルーンは途中に入らず、**最後の結果を削る役割**です。
{% endtab %}
{% endtabs %}





