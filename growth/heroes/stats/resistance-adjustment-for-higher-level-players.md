---
description: 🛑 Information on this page may differ from the current in-game data.
---

# 6️⃣ Resistance Adjustment for Higher-Level Players

{% tabs %}
{% tab title="ENG" %}
### Minimum Resistance Adjustment for Higher-Level Players

> When a higher-level player faces a lower-level player,\
> a **minimum resistance adjustment** is applied so that disadvantages in battle do not become excessive.

### What is this system?

This system is applied **from Level 40 onward**,\
and only when a **higher-level player is fighting a lower-level player**.

It works separately from existing values such as Accuracy, Evasion, Buffs, and Debuffs,\
and serves to provide a **minimum level of resistance adjustment** in certain situations.

In other words, this system is not meant to drastically change battle outcomes.\
Instead, it is designed so that:

* a higher-level player
* when facing a lower-level player
* receives a **minimum resistance adjustment**
* in areas such as debuff duration, accuracy, and evasion.

### When does it apply?

This adjustment applies only when all of the following conditions are met:

* **Level 40 or higher**
* **Your level is higher than your opponent’s**
* **It does not apply between players of the same level**
* **It does not apply when fighting a higher-level opponent**

### What does it affect?

This adjustment applies to the following:

* **Debuff duration reduction**
* **Accuracy adjustment**
* **Evasion adjustment**

***

### 1. Debuff Duration Reduction

When a higher-level player receives a debuff from a lower-level opponent,\
the duration of certain debuffs may be reduced slightly.

#### How does it work?

Debuff duration is reduced as follows:

```
Final Debuff Duration = Original Debuff Duration × (1 - Adjustment Value)
```

For example, if the original debuff lasts 8 seconds,\
the actual applied duration may become slightly shorter depending on the adjustment value.

#### Example

* Original debuff duration: **8 seconds**
* After adjustment: **7.4 seconds**

This means that when a higher-level player receives a debuff from a lower-level player,\
the duration of that debuff may be reduced slightly.

#### Notes

The following crowd control effects are **not** affected by this adjustment:

* Stun
* Knockback
* Black Hole

In other words, this applies only to **general debuff duration**,\
while certain hard control effects are handled separately.

***

### 2. Accuracy Adjustment

When a higher-level player attacks a lower-level player,\
a **minimum accuracy adjustment** is applied so that the lower-level player’s evasion does not create an excessive disadvantage.

#### How should this be understood?

Even if the target has high evasion,\
a level advantage will reduce that gap slightly,\
helping secure a **minimum amount of accuracy**.

This does **not** mean accuracy increases dramatically.\
Rather, it is an adjustment that **partially reduces the disadvantage caused by evasion**.

#### Example

* My Accuracy: **20**
* Opponent’s Evasion: **60**

Normally, this creates a large gap,\
but when the level adjustment applies, that gap is partially reduced.

Example:

```
Original gap: 40
After adjustment: 36.25
```

This means the higher-level player does not take the full impact of the opponent’s evasion as-is,\
and instead receives a **minimum accuracy adjustment**.

***

### 3. Evasion Adjustment

When a higher-level player is attacked by a lower-level player,\
a **minimum evasion adjustment** is applied so that the lower-level player’s attack does not become excessively favorable.

#### How should this be understood?

Even if the higher-level player’s evasion and the lower-level player’s accuracy are similar or equal,\
a level advantage allows the higher-level player to secure a **minimum amount of evasion margin**.

This also does **not** mean evasion increases dramatically.\
It is simply an adjustment that secures a **minimum defensive evasion baseline**.

#### Example

* My Evasion: **30**
* Opponent’s Accuracy: **30**

Under normal conditions, the values are equal,\
but with level adjustment applied, the result may become:

```
Base difference: 0
After adjustment: 3.75
```

This means that even under the same stat conditions,\
a higher-level player receives a **minimum evasion adjustment** when facing a lower-level player.

***

### At a Glance

#### Conditions

* Level 40 or above
* Applies only against lower-level opponents
* Does not apply to same-level or higher-level opponents

#### Affected Areas

* Debuff duration reduction
* Accuracy adjustment
* Evasion adjustment

#### Core Purpose

* To apply a **minimum resistance adjustment** when a higher-level player faces a lower-level player

***

### Level Resistance Point Table

| Level | Level Resistance Points |
| ----- | ----------------------- |
| 40    | 10                      |
| 41    | 11                      |
| 42    | 12                      |
| 43    | 13                      |
| 44    | 14                      |
| 45    | 15                      |
| 46    | 16                      |
| 47    | 17                      |
| 48    | 18                      |
| 49    | 19                      |
| 50    | 20                      |
| 51    | 21                      |
| 52    | 22                      |
| 53    | 23                      |
| 54    | 24                      |
| 55    | 25                      |
| 56    | 26                      |
| 57    | 27                      |
| 58    | 28                      |
| 59    | 29                      |

### Adjustment Settings Table

<table><thead><tr><th width="166.81817626953125">Adjustment Type</th><th width="83.0909423828125">Coefficient</th><th>Description</th><th>Calculation Example</th></tr></thead><tbody><tr><td>Debuff Duration</td><td>0.5</td><td>When a higher-level player receives a debuff of <strong>M seconds</strong> from a lower-level opponent, the <strong>debuff duration is reduced</strong> by the adjusted amount. Crowd control effects such as <strong>Stun, Black Hole, and Knockback</strong> are not included. This adjustment is applied to the final debuff duration.</td><td><strong>Formula:</strong> <code>M sec × (1 - n%)</code><br><strong>Example:</strong> Level 45 → Resistance Points 15<br><code>15 × 0.5 = 7.5(%)</code><br><code>7.5 ÷ 100 = 0.075</code><br><code>8 sec × (1 - 0.075) = 7.4 sec</code></td></tr><tr><td>Accuracy (ACC)</td><td>0.25</td><td>When attacking a lower-level opponent, a <strong>minimum accuracy adjustment</strong> is applied. This is not a percentage amplification. Instead, it partially reduces the disadvantage caused by the target’s evasion.</td><td><strong>Formula:</strong> <code>[Target EVA - My ACC] - n</code><br><strong>Example:</strong> My ACC 20 / My Level 45 / Target EVA 60<br><code>15 × 0.25 = 3.75</code><br><code>(60 - 20) - 3.75 = 36.25</code></td></tr><tr><td>Evasion (EVA)</td><td>0.25</td><td>When being attacked by a lower-level opponent, a <strong>minimum evasion adjustment</strong> is applied. This is not a percentage amplification. Instead, it secures a minimum evasion margin.</td><td><strong>Formula:</strong> <code>[My AGI(EVA) - Target ACC] + n</code><br><strong>Example:</strong> My EVA 30 / My Level 45 / Target ACC 30<br><code>15 × 0.25 = 3.75</code><br><code>(30 - 30) + 3.75 = 3.75</code></td></tr></tbody></table>
{% endtab %}

{% tab title="한국어" %}
## 높은 레벨 유저 대상 최소 저항 보정

> 높은 레벨 유저가 낮은 레벨 유저를 상대할 때,\
> 전투에서 불리함이 과도하게 커지지 않도록 **최소한의 저항 보정**이 적용됩니다.

***

### 이 시스템은 무엇인가요?

이 시스템은 **40레벨 이후**,\
**레벨이 더 높은 유저가 더 낮은 레벨 유저를 상대할 때만** 적용되는 보정입니다.

기존의 명중, 회피, 버프, 디버프 같은 수치와는 별개로 작동하며,\
일부 상황에서 **최소한의 방어선**을 보정해주는 역할을 합니다.

즉, 이 보정은 전투 결과를 크게 뒤집기 위한 장치가 아니라,

* 높은 레벨 유저가
* 낮은 레벨 유저를 상대로 싸울 때
* 디버프, 명중, 회피 영역에서
* **일정 수준의 저항 보정**을 받도록 설계된 시스템입니다.

***

### 언제 적용되나요?

다음 조건을 모두 만족할 때 적용됩니다.

* **40레벨 이상**
* **상대보다 내 레벨이 높을 때만 적용**
* **동일 레벨끼리는 적용되지 않음**
* **나보다 높은 레벨의 상대에게는 적용되지 않음**

***

### 어떤 항목에 적용되나요?

이 보정은 아래 3가지에 적용됩니다.

* **디버프 시간 감소**
* **명중 보정**
* **회피 보정**

***

## 1. 디버프 시간 감소

내가 낮은 레벨의 상대에게 디버프를 받을 때,\
일부 디버프는 **지속 시간이 조금 줄어들 수 있습니다.**

### 어떻게 적용되나요?

디버프 시간이 아래 방식으로 감소합니다.

```
최종 디버프 시간 = 원래 디버프 시간 × (1 - 보정값)
```

즉, 원래 8초 디버프를 받았다면\
보정값에 따라 실제 적용 시간은 그보다 조금 짧아질 수 있습니다.

### 예시

* 원래 디버프 시간: **8초**
* 보정 적용 후: **7.4초**

→ 이런 식으로, 높은 레벨 유저는 낮은 레벨 유저에게 받은 디버프의 지속시간이 일부 줄어들 수 있습니다.

### 주의사항

아래 상태이상은 이 보정 대상에 포함되지 않습니다.

* 스턴
* 넉백
* 블랙홀

즉, **일반적인 디버프 시간에만 적용**되며,\
행동 자체를 강하게 제한하는 일부 상태이상은 별도로 처리됩니다.

***

## 2. 명중 보정

높은 레벨 유저가 낮은 레벨 유저를 공격할 때,\
상대의 회피 효과 때문에 공격이 과도하게 빗나가지 않도록\
**최소한의 명중 보정**이 적용됩니다.

### 어떻게 이해하면 되나요?

상대의 회피가 높더라도,\
레벨 우위가 있는 경우에는 그 차이를 일부 줄여서\
**최소 명중 여유를 확보**하는 방식입니다.

이 보정은 “명중률이 크게 올라간다”는 개념이 아니라,\
**회피에 의해 불리해지는 폭을 일부 줄여주는 보정**입니다.

### 예시

* 내 명중: **20**
* 상대 회피: **60**

원래는 차이가 크게 벌어져 있지만,\
레벨 보정이 적용되면 그 차이를 일부 줄여\
최종적으로는 더 완화된 값으로 계산됩니다.

예:

```
기존 차이: 40
보정 적용 후: 36.25
```

→ 즉, 상대 회피의 영향을 그대로 전부 받는 것이 아니라,\
높은 레벨 유저에게 **최소한의 명중 보정**이 추가됩니다.

***

## 3. 회피 보정

높은 레벨 유저가 낮은 레벨 유저의 공격을 받을 때,\
상대의 공격이 과도하게 유리하게 작동하지 않도록\
**최소한의 회피 보정**이 적용됩니다.

### 어떻게 이해하면 되나요?

내 회피와 상대 명중이 비슷하거나 같더라도,\
레벨 우위가 있는 경우에는 일정 수준의 회피 여유를 확보하게 됩니다.

이 역시 “회피율이 크게 올라간다”는 개념이 아니라,\
**최소한의 회피 방어선을 확보하는 보정**입니다.

### 예시

* 내 회피: **30**
* 상대 명중: **30**

기본적으로는 같은 수치지만,\
레벨 보정이 적용되면 다음과 같이 계산될 수 있습니다.

```
기본 차이: 0
보정 적용 후: 3.75
```

→ 즉, 동일한 수치 조건에서도\
높은 레벨 유저는 낮은 레벨 유저를 상대로 **최소 회피 보정**을 받습니다.

***

## 한눈에 보기

### 적용 조건

* 40레벨 이상
* 나보다 낮은 레벨의 상대에게만 적용
* 동레벨 / 상위 레벨 상대에게는 적용되지 않음

### 적용 항목

* 디버프 시간 감소
* 명중 보정
* 회피 보정

### 핵심 의도

* 높은 레벨 유저가 낮은 레벨 유저를 상대할 때
* **최소한의 저항 보정**을 적용하는 시스템

***

### 레벨 저항 포인트 표

| 레벨 | 레벨 저항 포인트 |
| -- | --------- |
| 40 | 10        |
| 41 | 11        |
| 42 | 12        |
| 43 | 13        |
| 44 | 14        |
| 45 | 15        |
| 46 | 16        |
| 47 | 17        |
| 48 | 18        |
| 49 | 19        |
| 50 | 20        |
| 51 | 21        |
| 52 | 22        |
| 53 | 23        |
| 54 | 24        |
| 55 | 25        |
| 56 | 26        |
| 57 | 27        |
| 58 | 28        |
| 59 | 29        |

### 보정 설정 표

<table><thead><tr><th width="120.0909423828125">보정 구분</th><th width="84">보정 계수</th><th>설명</th><th>계산 예시</th></tr></thead><tbody><tr><td>디버프 타임</td><td>0.5</td><td>내가 낮은 레벨 상대에게서 <strong>M초 디버프</strong>를 받았을 때, 보정값만큼 <strong>디버프 유지시간이 감소</strong>합니다. 상태이상(스턴, 블랙홀, 넉백)은 포함되지 않습니다. 이 보정은 최종 디버프 시간에 적용됩니다.</td><td><strong>공식:</strong> <code>M초 × (1 - n%)</code><br><strong>예시:</strong> 레벨 45 → 저항 포인트 15<br><code>15 × 0.5 = 7.5(%)</code><br><code>7.5 ÷ 100 = 0.075</code><br><code>8초 × (1 - 0.075) = 7.4초</code></td></tr><tr><td>명중 (ACC)</td><td>0.25</td><td>내가 낮은 레벨 상대를 공격할 때, <strong>최소한의 명중 보정</strong>이 적용됩니다. 퍼센트 증폭 개념이 아니라, 상대 회피로 인해 불리해지는 값을 일부 줄여주는 방식입니다.</td><td><strong>공식:</strong> <code>[대상의 EVA - 나의 ACC] - n</code><br><strong>예시:</strong> 내 명중 20 / 내 레벨 45 / 대상 EVA 60<br><code>15 × 0.25 = 3.75</code><br><code>(60 - 20) - 3.75 = 36.25</code></td></tr><tr><td>회피 (EVA)</td><td>0.25</td><td>내가 낮은 레벨 상대에게 피격될 때, <strong>최소한의 회피 보정</strong>이 적용됩니다. 퍼센트 증폭 개념이 아니라, 최소 회피 여유를 확보하는 방식입니다.</td><td><strong>공식:</strong> <code>[나의 AGI(EVA) - 대상의 ACC] + n</code><br><strong>예시:</strong> 내 회피 30 / 내 레벨 45 / 대상 명중 30<br><code>15 × 0.25 = 3.75</code><br><code>(30 - 30) + 3.75 = 3.75</code></td></tr></tbody></table>
{% endtab %}

{% tab title="日本語" %}
### 高レベルプレイヤー向け最小抵抗補正

> 高レベルプレイヤーが低レベルプレイヤーと戦う場合、\
> 戦闘での不利が過度に大きくならないよう、**最小限の抵抗補正**が適用されます。

### このシステムとは？

このシステムは**レベル40以降**、\
**自分よりレベルの低い相手と戦う場合にのみ**適用されます。

命中、回避、バフ、デバフといった既存の数値とは別に動作し、\
特定の状況で**最小限の抵抗補正**を与える仕組みです。

つまり、この補正は戦闘結果を大きく覆すためのものではなく、

* 高レベルプレイヤーが
* 低レベルプレイヤーと戦うときに
* デバフ、命中、回避の領域で
* **最小限の抵抗補正**を受ける

ためのシステムです。

### いつ適用されますか？

以下の条件をすべて満たした場合に適用されます。

* **レベル40以上**
* **自分のレベルが相手より高い**
* **同レベル同士では適用されない**
* **自分より高レベルの相手には適用されない**

### 何に適用されますか？

この補正は以下の3項目に適用されます。

* **デバフ時間の短縮**
* **命中補正**
* **回避補正**

***

### 1. デバフ時間の短縮

高レベルプレイヤーが低レベルの相手からデバフを受けた場合、\
一部のデバフは**持続時間が少し短くなることがあります。**

#### どのように適用されますか？

デバフ時間は以下の形で短縮されます。

```
最終デバフ時間 = 元のデバフ時間 × (1 - 補正値)
```

たとえば元のデバフ時間が8秒であれば、\
補正値に応じて実際の適用時間はそれより少し短くなる場合があります。

#### 例

* 元のデバフ時間: **8秒**
* 補正適用後: **7.4秒**

つまり、高レベルプレイヤーは低レベルプレイヤーから受けるデバフについて、\
その持続時間が一部短縮されることがあります。

#### 注意事項

以下の状態異常はこの補正の対象外です。

* スタン
* ノックバック
* ブラックホール

つまり、これは**一般的なデバフ時間**のみに適用され、\
行動を強く制限する一部の状態異常は別扱いになります。

***

### 2. 命中補正

高レベルプレイヤーが低レベルプレイヤーを攻撃する場合、\
相手の回避によって不利が過度に大きくならないよう、\
**最小限の命中補正**が適用されます。

#### どう理解すればいいですか？

相手の回避が高くても、\
レベル優位がある場合はその差を一部縮めて、\
**最低限の命中余裕を確保する**仕組みです。

これは「命中率が大きく上がる」という意味ではなく、\
**回避による不利を一部軽減する補正**です。

#### 例

* 自分の命中: **20**
* 相手の回避: **60**

通常は大きな差がありますが、\
レベル補正が適用されると、その差が一部緩和されます。

例:

```
元の差: 40
補正適用後: 36.25
```

つまり、高レベルプレイヤーは相手の回避の影響をそのまま受けるのではなく、\
**最小限の命中補正**を受けます。

***

### 3. 回避補正

高レベルプレイヤーが低レベルプレイヤーから攻撃を受ける場合、\
相手の攻撃が過度に有利にならないよう、\
**最小限の回避補正**が適用されます。

#### どう理解すればいいですか？

自分の回避と相手の命中が同じ、または近い場合でも、\
レベル優位があれば一定の回避余裕を確保できます。

これも「回避率が大きく上がる」という意味ではなく、\
**最低限の回避防御ラインを確保する補正**です。

#### 例

* 自分の回避: **30**
* 相手の命中: **30**

通常なら同じ数値ですが、\
レベル補正が適用されると次のようになります。

```
基準差: 0
補正適用後: 3.75
```

つまり、同じ数値条件でも、\
高レベルプレイヤーは低レベルプレイヤーに対して**最小限の回避補正**を受けます。

***

### ひと目でわかる要約

#### 適用条件

* レベル40以上
* 自分より低レベルの相手にのみ適用
* 同レベル / 上位レベルの相手には適用されない

#### 適用項目

* デバフ時間の短縮
* 命中補正
* 回避補正

#### 目的

* 高レベルプレイヤーが低レベルプレイヤーと戦う際に、**最小限の抵抗補正**を適用すること

***

### レベル抵抗ポイント表

| レベル | レベル抵抗ポイント |
| --- | --------- |
| 40  | 10        |
| 41  | 11        |
| 42  | 12        |
| 43  | 13        |
| 44  | 14        |
| 45  | 15        |
| 46  | 16        |
| 47  | 17        |
| 48  | 18        |
| 49  | 19        |
| 50  | 20        |
| 51  | 21        |
| 52  | 22        |
| 53  | 23        |
| 54  | 24        |
| 55  | 25        |
| 56  | 26        |
| 57  | 27        |
| 58  | 28        |
| 59  | 29        |

### 補正設定表

<table><thead><tr><th width="118.54547119140625">補正区分</th><th width="75.72723388671875">補正係数</th><th>説明</th><th>計算例</th></tr></thead><tbody><tr><td>デバフ時間</td><td>0.5</td><td>高レベルプレイヤーが低レベルの相手から <strong>M秒のデバフ</strong> を受けた場合、補正値に応じて <strong>デバフの持続時間が減少</strong> します。<strong>スタン、ブラックホール、ノックバック</strong> などの状態異常は含まれません。この補正は最終デバフ時間に適用されます。</td><td><strong>式:</strong> <code>M秒 × (1 - n%)</code><br><strong>例:</strong> レベル45 → 抵抗ポイント15<br><code>15 × 0.5 = 7.5(%)</code><br><code>7.5 ÷ 100 = 0.075</code><br><code>8秒 × (1 - 0.075) = 7.4秒</code></td></tr><tr><td>命中 (ACC)</td><td>0.25</td><td>低レベルの相手を攻撃する際、<strong>最小限の命中補正</strong> が適用されます。これは命中率を大きく上げるものではなく、相手の回避による不利を一部軽減する仕組みです。</td><td><strong>式:</strong> <code>[相手のEVA - 自分のACC] - n</code><br><strong>例:</strong> 自分の命中20 / 自分のレベル45 / 相手のEVA60<br><code>15 × 0.25 = 3.75</code><br><code>(60 - 20) - 3.75 = 36.25</code></td></tr><tr><td>回避 (EVA)</td><td>0.25</td><td>低レベルの相手から攻撃を受ける際、<strong>最小限の回避補正</strong> が適用されます。これは回避率を大きく上げるものではなく、最低限の回避余裕を確保するための仕組みです。</td><td><strong>式:</strong> <code>[自分のAGI(EVA) - 相手のACC] + n</code><br><strong>例:</strong> 自分の回避30 / 自分のレベル45 / 相手の命中30<br><code>15 × 0.25 = 3.75</code><br><code>(30 - 30) + 3.75 = 3.75</code></td></tr></tbody></table>
{% endtab %}
{% endtabs %}





