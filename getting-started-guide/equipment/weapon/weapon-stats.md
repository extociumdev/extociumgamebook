---
description: 🛑 This information may be updated later than the game server data.
---

# ✨ Weapon Stats

{% tabs %}
{% tab title="ENG" %}
💡**When a weapon is created, it triggers one of the following four types of '**[**stat** ](../../heroes/stats/)**options':** Additionally, when a weapon is [enchanted](../enchantment/weapon-enchantment.md), stat options corresponding to the enchantment level are added.

1. [Fixed option ](weapon-stats.md#id-1-fixed-option)
2. [Primary stat option (probabilistic) ](weapon-stats.md#id-2-primary-stat-option-probabilistic)
3. [Secondary stat option (probabilistic) ](weapon-stats.md#id-3-secondary-stat-option-probabilistic)
4. [Compatibility option (probabilistic) ](weapon-stats.md#id-4-compatibility-option-probabilistic)
5. [Enchantment options depending on the weapon enchantment](weapon-stats.md#id-5-enchantment-options-depending-on-the-weapon-enchantment)

#### <mark style="color:blue;">1️⃣Fixed Option</mark>

An option that is 100% applied to all weapons. \
The fixed option is randomly applied within a predefined minimum to maximum range for each weapon. \
The fixed value varies for each weapon in terms of the primary stat.

| Option                   |  Spawn Probability (%) |
| ------------------------ | ---------------------- |
| Attack Point (AP)        | 100                    |
| Skill Attack Point (SAP) | 100                    |
| STR                      | 0 or 100               |
| DEX                      | 0 or 100               |
| INT                      | 0 or 100               |
| CON                      | 0 or 100               |
| WIZ                      | 0 or 100               |
| CHA                      | 0 or 100               |

#### <mark style="color:blue;">2️⃣Primary Stat Option (Probabilistic)</mark>

When a weapon is created, a primary stat option can be randomly applied. \
The probability value varies for each weapon and is likewise randomly applied within the predefined minimum to maximum range. \
The higher the weapon's level, the higher the probability of generating stats. \
When applying the primary stat probability, it is treated as an independent probability.

| Option | Spawn Probability (%) |
| ------ | --------------------- |
| STR    | 5\~8                  |
| DEX    | 5\~8                  |
| INT    | 5\~8                  |
| CON    | 5\~8                  |
| WIZ    | 5\~8                  |
| CHA    | 5\~8                  |

#### <mark style="color:blue;">3️⃣Secondary Stat Option (Probabilistic)</mark>

When a weapon is created, a secondary stat option can be randomly applied. \
The probability value varies for each weapon and is likewise randomly applied within the predefined minimum to maximum range. \
The higher the weapon's level, the higher the probability of generating stats. \
When applying the secondary stat probability, it is treated as an independent probability.

| Option                      | Spawn Probability (%) |
| --------------------------- | --------------------- |
| Attack Point (AP)           | 8\~10                 |
| HP                          | 8\~10                 |
| MP                          | 8\~10                 |
| Critical Bonus (CB)         | 8\~10                 |
| Critical Chance (CP)        | 3\~5                  |
| Skill Attack Point (SAP)    | 8\~10                 |
| Skill Critical Bonus (SCB)  | 8\~10                 |
| Skill Critical Chance (SCP) | 8\~10                 |
| Cooltime Reduction (CR)     | 3\~5                  |

#### <mark style="color:blue;">4️⃣Compatibility Option (Probabilistic)</mark>

When a weapon is created, an additional damage option based on compatibility can be randomly applied. The probability value varies for each weapon and is likewise randomly applied within the predefined minimum to maximum range. The higher the weapon's level, the higher the probability of generating stats.

{% hint style="info" %}
The additional damage option according to compatibility is interpreted as follows:

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
This indication means that it deals 2% additional damage to opponents (both PCs and NPCs) that possess the 'Light Attribute'. If the final damage I deal to an enemy is 200, then when the enemy has the 'Light Attribute', the final damage becomes 204.

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣Enchantment options depending on the weapon enchantment</mark>

With each enchantment level reaching increments of '5', an additional random option is granted to the weapon. At this time, only one type of option is granted. As the weapon level increases, the minimum to maximum values of the options also increase.

| Weapon                                                     | Option                                                            | Min \~ Max |
| ---------------------------------------------------------- | ----------------------------------------------------------------- | ---------- |
| <p>Wooden Sword Bronze Sword <br>Steel Sword Flamberge</p> | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1     |
| Paladin's Sword Eye of the Orc Damascus                    | "                                                                 | 1\~2       |
| Savage Sword Oracle Sword Demon Sword                      | "                                                                 | 1\~3       |
| Awakening Darkness                                         | "                                                                 | 2\~4       |
| Sword of Light                                             | "                                                                 | 2\~5       |
{% endtab %}

{% tab title="한국어" %}
💡**무기가 생성 될 때는 아래와 같은 네 가지 조건의 ‘**[**스탯**](../../heroes/stats/) **옵션’이 발동됩니다.**\
또한 무기를 [인챈트](../enchantment/weapon-enchantment.md) 하는 경우, 인챈트 레벨에 따른 스탯 옵션이 추가됩니다.

1. [고정 옵션](weapon-stats.md#id-1)
2. [1차 스탯 옵션 (확률적)](weapon-stats.md#id-2-1)
3. [2차 스탯 옵션 (확률적)](weapon-stats.md#id-3-2)
4. [상성 옵션 (확률적)](weapon-stats.md#id-4)
5. [무기 인챈트에 따른 인챈트 옵션](weapon-stats.md#id-5)

#### <mark style="color:blue;">1️⃣고정 옵션</mark>

모든 무기에 100% 적용되는 옵션입니다. \
고정 옵션은 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤하게 적용됩니다.\
1차 스탯의 경우, 무기마다 적용되는 고정 값이 다릅니다.

| 옵션           | 생성 확률 (%) |
| ------------ | --------- |
| 공격력 (AP)     | 100       |
| 스킬 공격력 (SAP) | 100       |
| STR          | 0 or 100  |
| DEX          | 0 or 100  |
| INT          | 0 or 100  |
| CON          | 0 or 100  |
| WIZ          | 0 or 100  |
| CHA          | 0 or 100  |

#### <mark style="color:blue;">2️⃣1차 스탯 옵션 (확률적)</mark>

무기를 생성할 때 랜덤하게 1차 스탯 옵션이 적용될 수 있습니다. \
각 확률 값은 무기마다 다르며, 마찬가지로 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. \
무기의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다.  \
1차 스탯의 확률을 적용할 때는 모두 독립 확률로 적용됩니다.

| 옵션   | 생성 확률 (%) |
| ---- | --------- |
| STR  | 5\~8      |
| DEX  | 5\~8      |
| INT  | 5\~8      |
| CON  | 5\~8      |
| WIZ  | 5\~8      |
| CHA  | 5\~8      |

#### <mark style="color:blue;">3️⃣2차 스탯 옵션 (확률적)</mark>

무기를 생성할 때 랜덤하게 2차 스탯 옵션이 적용될 수 있습니다. \
각 확률 값은 무기마다 다르며, 마찬가지로 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. \
무기의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다. \
2차 스탯의 확률을 적용할 때는 모두 독립 확률로 적용됩니다.

| 옵션               | 생성 확률 (%) |
| ---------------- | --------- |
| 공격력 (AP)         | 8\~10     |
| HP               | 8\~10     |
| MP               | 8\~10     |
| 치명타 보너스 (CB)     | 8\~10     |
| 치명타 확률 (CP)      | 3\~5      |
| 스킬 공격력 (SAP)     | 8\~10     |
| 스킬 치명타 보너스 (SCB) | 8\~10     |
| 스킬 치명타 확률 (SCP)  | 8\~10     |
| 쿨타임 감소 (CR)      | 3\~5      |

#### <mark style="color:blue;">4️⃣상성 옵션 (확률적)</mark>

무기를 생성할 때 랜덤하게 상성에 따른 부가 데미지 옵션이 적용될 수 있습니다. \
각 확률 값은 무기마다 다르며, 마찬가지로 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. 무기의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다.

{% hint style="info" %}
상성에 따른 부가 데미지 옵션은 아래와 같이 해석됩니다.

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
이 표시의 의미는 '빛속성'을 가진 상대 (PC, NPC모두 포함)에게 2%의 부가 데미지를 입히는 것입니다. 만약 내가 적에게 입힐 최종 데미지가 200 이라면, 해당 적이 '빛속성'일 때, 최종 데미지가 204가 됩니다.

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣무기 인챈트에 따른 인챈트 옵션</mark>

인챈트를 통해 무기의 인챈트 레벨이 '5' 단위를 달성할 때 마다, 추가적인 랜덤 옵션이 부여됩니다.\
이 때, 옵션은 1종만 부여됩니다.\
무기의 레벨이 높아지면 옵션의 최소 \~ 최대 값도 높아집니다.

| 무기 종류                              | 인챈트 옵션                                                            | 최소 \~ 최대 값 |
| ---------------------------------- | ----------------------------------------------------------------- | ---------- |
| <p>목검<br>청동검<br>강철검<br>플람베르그</p>   | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1     |
| <p>팔라딘의 검 <br>오크의 눈 <br>다마스커스</p>  | "                                                                 | 1\~2       |
| <p>야만의 검 <br>오라클 스워드 <br>악마의 검</p> | "                                                                 | 1\~3       |
| 깨어나는 어둠                            | "                                                                 | 2\~4       |
| 빛의 검                               | "                                                                 | 2\~5       |
{% endtab %}

{% tab title="日本語" %}
💡**武器が生成される際、以下の4種類の「**[**ステータスオプション**](../../heroes/stats/)**」が発動されます。** また、[武器をエンチャントする場合](../enchantment/weapon-enchantment.md)、エンチャントレベルに応じたステータスオプションが追加されます。

1. [固定オプション](weapon-stats.md#id-1opushon)&#x20;
2. [1次ステータスオプション（確率的） ](weapon-stats.md#id-21suttasuopushon)
3. [2次ステータスオプション（確率的） ](weapon-stats.md#id-32suttasuopushon)
4. [相性オプション（確率的） ](weapon-stats.md#id-4opushon)
5. [武器エンチャントによるエンチャントオプション](weapon-stats.md#id-5enchantoniyoruenchantoopushon)

#### <mark style="color:blue;">1️⃣固定オプション</mark>

すべての武器に100%適用されるオプションです。 固定オプションは、各武器に設定された最小値～最大値の範囲内でランダムに適用されます。 1次ステータスの場合、武器ごとに適用される固定値が異なります。

| オプション        | 生成確率 (%) |
| ------------ | -------- |
| 攻撃力 (AP)     | 100      |
| スキル攻撃力 (SAP) | 100      |
| STR          | 0 or 100 |
| DEX          | 0 or 100 |
| INT          | 0 or 100 |
| CON          | 0 or 100 |
| WIZ          | 0 or 100 |
| CHA          | 0 or 100 |

#### <mark style="color:blue;">2️⃣1次ステータスオプション（確率的）</mark>

武器を生成する際、ランダムに1次ステータスオプションが適用される可能性があります。 各確率値は武器ごとに異なり、同様に各武器に設定された最小値～最大値の範囲内でランダムに適用されます。 \
武器のレベルが高くなるほど、ステータス生成の確率も高まります。 \
1次ステータスの確率を適用する際は、すべて独立確率で適用されます。

| オプション | 生成確率 (%) |
| ----- | -------- |
| STR   | 5\~8     |
| DEX   | 5\~8     |
| INT   | 5\~8     |
| CON   | 5\~8     |
| WIZ   | 5\~8     |
| CHA   | 5\~8     |

#### <mark style="color:blue;">3️⃣2次ステータスオプション（確率的）</mark>

武器を生成する際、ランダムに2次ステータスオプションが適用される可能性があります。 各確率値は武器ごとに異なり、同様に各武器に設定された最小値～最大値の範囲内でランダムに適用されます。 \
武器のレベルが高くなるほど、ステータス生成の確率も高まります。 \
2次ステータスの確率を適用する際は、すべて独立確率で適用されます。

| オプション               | 生成確率 (%) |
| ------------------- | -------- |
| 攻撃力 (AP)            | 8\~10    |
| HP                  | 8\~10    |
| MP                  | 8\~10    |
| クリティカルボーナス (CB)     | 8\~10    |
| クリティカル確率 (CP)       | 3\~5     |
| スキル攻撃力 (SAP)        | 8\~10    |
| スキルクリティカルボーナス (SCB) | 8\~10    |
| スキルクリティカル確率 (SCP)   | 8\~10    |
| クールタイム減少 (CR)       | 3\~5     |

#### <mark style="color:blue;">4️⃣相性オプション（確率的）</mark>

武器を生成する際、ランダムに相性に応じた追加ダメージオプションが適用される可能性があります。 各確率値は武器ごとに異なり、同様に各武器に設定された最小値～最大値の範囲内でランダムに適用されます。武器のレベルが高くなるほど、ステータス生成の確率も高まります。

{% hint style="info" %}
相性による追加ダメージオプションは以下のように解釈されます。

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
この表示の意味は、「光属性」を持つ相手（PC、NPC両方含む）に対して2%の追加ダメージを与えることです。もし私が敵に与える最終ダメージが200なら、その敵が「光属性」の場合、最終ダメージは204になります。

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣武器エンチャントによるエンチャントオプション</mark>

エンチャントを通じて武器のエンチャントレベルが「5」単位を達成するごとに、追加のランダムオプションが付与されます。 この時、オプションは1種のみ付与されます。 武器のレベルが高くなると、オプションの最小～最大値も高くなります。

| 武器種類                                          |  エンチャントオプション                                                      | 最小～最大値 |
| --------------------------------------------- | ----------------------------------------------------------------- | ------ |
| <p>木剣</p><p>青銅剣 </p><p>鋼の剣 </p><p>フランベルジュ</p> | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1 |
| <p>パラディンの剣 </p><p>オークの目 </p><p>ダマスカス</p>      | "                                                                 | 1\~2   |
| <p>野蛮な剣 </p><p>オラクルソード </p><p>悪魔の剣</p>        | "                                                                 | 1\~3   |
| 目覚める闇                                         | "                                                                 | 2\~4   |
| 光の剣                                           | "                                                                 | 2\~5   |
{% endtab %}
{% endtabs %}

