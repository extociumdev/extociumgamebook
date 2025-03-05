---
description: 🛑 This information may be updated later than the game server data.
---

# ✨ Orb Stats

{% tabs %}
{% tab title="ENG" %}
💡**When an orb is created, it triggers one of the following four types of '**[**stat** ](../../heroes/stats/)**options':** Additionally, when an orb is [enchanted](../enchantment/orb-enchantment.md), stat options corresponding to the enchantment level are added.

1. [Fixed option ](orb-stats.md#id-1-fixed-option)
2. [Primary stat option (probabilistic) ](orb-stats.md#id-2-primary-stat-option-probabilistic)
3. [Secondary stat option (probabilistic) ](orb-stats.md#id-3-secondary-stat-option-probabilistic)
4. [Compatibility option (probabilistic) ](orb-stats.md#id-4-compatibility-option-probabilistic)
5. [Enchantment options depending on the orb enchantment](orb-stats.md#id-5-enchantment-options-depending-on-the-orb-enchantment)

#### <mark style="color:blue;">1️⃣Fixed option</mark>

An option that is 100% applied to all orbs. \
The fixed option is randomly applied within a predefined minimum to maximum range for each weapon. The fixed value varies for each weapon in terms of the primary stat.

| Option        | Spawn Probability (%) |
| ------------- | --------------------- |
| Agility (AGI) | 100                   |
| HP            | 100                   |
| STR           | 0 or 100              |
| DEX           | 0 or 100              |
| INT           | 0 or 100              |
| CON           | 0 or 100              |
| WIZ           | 0 or 100              |
| CHA           | 0 or 100              |

💡 **Equipment Fixed Option Range Guide**

👉[ **Click here**](orb-stats.md#fixed-option-range) to check the **minimum and maximum fixed stat values for each piece of equipment!**

#### <mark style="color:blue;">2️⃣Primary stat option (probabilistic)</mark>

When an orb is created, a primary stat option can be randomly applied. \
The probability value varies for each weapon, and similarly, it is randomly applied within the predefined minimum to maximum range for each orb. \
The higher the orb's level, the higher the probability of generating stats. \
When applying the primary stat probability, it is treated as an independent probability.

| Option | Spawn Probability (%) |
| ------ | --------------------- |
| STR    | 5\~8                  |
| DEX    | 5\~8                  |
| INT    | 5\~8                  |
| CON    | 5\~8                  |
| WIZ    | 5\~8                  |
| CHA    | 5\~8                  |

#### <mark style="color:blue;">3️⃣Secondary stat option (probabilistic)</mark>

When an orb is created, a secondary stat option can be randomly applied. \
The probability value varies for each orb, and similarly, it is randomly applied within the predefined minimum to maximum range. \
The higher the orb's level, the higher the probability of generating stats. \
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
| Agility (AGI)               | 0.2\~0.5              |

#### <mark style="color:blue;">4️⃣Compatibility option (probabilistic)</mark>

When creating an orb, a compatibility-based additional damage option can be randomly applied. The probability value varies for each orb, and it is randomly applied within the predefined minimum to maximum values. \
The higher the orb's level, the higher the probability of stat generation.

{% hint style="info" %}
The additional damage option according to compatibility is interpreted as follows:

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
This indication means that it inflicts 2% additional damage to opponents (both PCs and NPCs) that have the 'Light Attribute'. If the final damage I deal to an enemy is 200, then when the enemy has the 'Light Attribute', the final damage becomes 204.

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣Enchantment options depending on the orb enchantment</mark>

With each enchantment, as the orb reaches increments of '5' in enchantment level, an additional random option is granted. At this time, only one type of option is granted. \
As the orb level increases, the minimum to maximum values of the options also increase.

| Orb type                                                                  | Enchant Option                                                    | Min \~Max |
| ------------------------------------------------------------------------- | ----------------------------------------------------------------- | --------- |
| <p>Orb of Wind <br>Orb of Darkness <br>Abyssal Orb <br>Orb of Clarity</p> | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1    |
| <p>Wind of Flame <br>Wings of Light <br>Burst Energy</p>                  | "                                                                 | 1\~2      |
| <p>Hand of the Demon <br>Wings of the Demon <br>Orb of Judgment</p>       | "                                                                 | 1\~3      |
| Rainbow                                                                   | "                                                                 | 2\~4      |
| Wrath of Water                                                            | "                                                                 | 2\~5      |
{% endtab %}

{% tab title="한국어" %}
💡**오브가 생성 될 때는 아래와 같은 네 가지 조건의 ‘**[**스탯**](../../heroes/stats/) **옵션’이 발동됩니다.**\
또한 오브를 [인챈트](../enchantment/weapon-enchantment.md) 하는 경우, 인챈트 레벨에 따른 스탯 옵션이 추가됩니다.

1. [고정 옵션](orb-stats.md#id-1)
2. [1차 스탯 옵션 (확률적)](orb-stats.md#id-2-1)
3. [2차 스탯 옵션 (확률적)](orb-stats.md#id-3-2)
4. [상성 옵션 (확률적)](orb-stats.md#id-4)
5. [오브 인챈트에 따른 인챈트 옵션](orb-stats.md#id-5)

#### <mark style="color:blue;">1️⃣고정 옵션</mark>

모든 오브에 100% 적용되는 옵션입니다. \
고정 옵션은 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤하게 적용됩니다.\
1차 스탯의 경우, 무기마다 적용되는 고정 값이 다릅니다.

| 옵션       | 생성 확률 (%) |
| -------- | --------- |
| 민첩 (AGI) | 100       |
| HP       | 100       |
| STR      | 0 or 100  |
| DEX      | 0 or 100  |
| INT      | 0 or 100  |
| CON      | 0 or 100  |
| WIZ      | 0 or 100  |
| CHA      | 0 or 100  |

💡 **장비 고정 옵션 범위 안내**

👉 [**여기를 클릭**](orb-stats.md#fixed-option-range)하여 **장비별 적용 가능한 고정 스탯의 최소\~최대값**을 확인하세요!

#### <mark style="color:blue;">2️⃣1차 스탯 옵션 (확률적)</mark>

오브를 생성할 때 랜덤하게 1차 스탯 옵션이 적용될 수 있습니다. \
각 확률 값은 무기마다 다르며, 마찬가지로 각 오브에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. \
오브의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다.  \
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

오브를 생성할 때 랜덤하게 2차 스탯 옵션이 적용될 수 있습니다. \
각 확률 값은 오브마다 다르며, 마찬가지로 각 오브에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. \
오브의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다. \
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
| 민첩 (AGI)         | 0.2\~0.5  |

#### <mark style="color:blue;">4️⃣상성 옵션 (확률적)</mark>

오브를 생성할 때 랜덤하게 상성에 따른 부가 데미지 옵션이 적용될 수 있습니다. \
각 확률 값은 오브마다 다르며, 마찬가지로 각 오브에 정해진 최소 \~ 최대 값 안에서 랜덤 하게 적용됩니다. 오브의 레벨이 높아질 수록 스탯 생성 확률도 높아집니다.

{% hint style="info" %}
상성에 따른 부가 데미지 옵션은 아래와 같이 해석됩니다.

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
이 표시의 의미는 '빛속성'을 가진 상대 (PC, NPC모두 포함)에게 2%의 부가 데미지를 입히는 것입니다. 만약 내가 적에게 입힐 최종 데미지가 200 이라면, 해당 적이 '빛속성'일 때, 최종 데미지가 204가 됩니다.

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣오브 인챈트에 따른 인챈트 옵션</mark>

인챈트를 통해 오브의 인챈트 레벨이 '5' 단위를 달성할 때 마다, 추가적인 랜덤 옵션이 부여됩니다.\
이 때, 옵션은 1종만 부여됩니다.\
오브의 레벨이 높아지면 옵션의 최소 \~ 최대 값도 높아집니다.

| 오브 종류                                          | 인챈트 옵션                                                            | 최소 \~ 최대 값 |
| ---------------------------------------------- | ----------------------------------------------------------------- | ---------- |
| <p>바람의 오브 <br>어둠의 오브 <br>심연의 오브 <br>청명의 오브</p> | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1     |
| <p>화염의 바람 <br>빛의 날개 <br>폭렬 에너지</p>             | "                                                                 | 1\~2       |
| <p>악마의 손 <br>악마의 날개 <br>심판의 오브</p>             | "                                                                 | 1\~3       |
| 레인보우                                           | "                                                                 | 2\~4       |
| 물의 분노                                          | "                                                                 | 2\~5       |
{% endtab %}

{% tab title="日本語" %}
💡**オーブが生成される際、以下の4種類の「**[**ステータスオプション**](../../heroes/stats/)**」が発動されます。**&#x20;

また、[オーブをエンチャントする場合](../enchantment/orb-enchantment.md)、エンチャントレベルに応じたステータスオプションが追加されます。

1. 固定オプション
2. 1次ステータスオプション（確率的）
3. 2次ステータスオプション（確率的）
4. 相性オプション（確率的）
5. オーブエンチャントによるエンチャントオプション

#### <mark style="color:blue;">1️⃣固定オプション</mark>

すべてのオーブに100%適用されるオプションです。 \
固定オプションは、各武器に設定された最小値～最大値の範囲内でランダムに適用されます。\
&#x20;1次ステータスの場合、武器ごとに適用される固定値が異なります。

| オプション       | 生成確率 (%) |
| ----------- | -------- |
| アジャイル (AGI) | 100      |
| HP          | 100      |
| STR         | 0 or 100 |
| DEX         | 0 or 100 |
| INT         | 0 or 100 |
| CON         | 0 or 100 |
| WIZ         | 0 or 100 |
| CHA         | 0 or 100 |

💡 **装備固定オプション範囲ガイド**

👉 [**こちらをクリック** して](orb-stats.md#fixed-option-range)、**各装備に適用される固定ステータスの最小～最大値**を確認しましょう！

#### <mark style="color:blue;">2️⃣1次ステータスオプション（確率的）</mark>

オーブを生成する際、ランダムに1次ステータスオプションが適用される可能性があります。 \
各確率値は武器ごとに異なり、同様に各オーブに設定された最小値～最大値の範囲内でランダムに適用されます。 \
オーブのレベルが高くなるほど、ステータス生成の確率も高まります。 \
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

オーブを生成する際、ランダムに2次ステータスオプションが適用される可能性があります。 各確率値はオーブごとに異なり、同様に各オーブに設定された最小値～最大値の範囲内でランダムに適用されます。 \
オーブのレベルが高くなるほど、ステータス生成の確率も高まります。 \
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
| アジャイル (AGI)         | 0.2\~0.5 |

#### <mark style="color:blue;">4️⃣相性オプション（確率的）</mark>

オーブを生成する際、ランダムに相性に応じた追加ダメージオプションが適用されることがあります。 各確率値はオーブごとに異なり、同様に各オーブに設定された最小値～最大値の範囲内でランダムに適用されます。\
オーブのレベルが高くなるほど、ステータス生成の確率も高まります。

{% hint style="info" %}
相性に応じた追加ダメージオプションは以下のように解釈されます。

<img src="../../../.gitbook/assets/image (621).png" alt="" data-size="original">\
この表示の意味は、「光属性」を持つ相手（PC、NPC両方含む）に対して2%の追加ダメージを与えることです。もし私が敵に与える最終ダメージが200なら、その敵が「光属性」の場合、最終ダメージは204になります。

❓<mark style="color:blue;">200\*(1+0.02)=204</mark>
{% endhint %}

#### <mark style="color:blue;">5️⃣オーブエンチャントによるエンチャントオプション</mark>

エンチャントを通じてオーブのエンチャントレベルが「5」単位を達成するごとに、追加のランダムオプションが付与されます。 この時、オプションは1種のみ付与されます。 オーブのレベルが高くなると、オプションの最小～最大値も高くなります。

| オブタイプ                                        | エンチャントオプション                                                       | 最小～最大値 |
| -------------------------------------------- | ----------------------------------------------------------------- | ------ |
| <p>風のオーブ <br>闇のオーブ <br>深淵のオーブ <br>澄みのオーブ</p> | <p>STR </p><p>DEX </p><p>INT </p><p>CON </p><p>WIZ </p><p>CHA</p> | 1 \~ 1 |
| <p>炎の風 <br>光の翼 <br>爆裂エネルギー</p>               | "                                                                 | 1\~2   |
| <p>悪魔の手 <br>悪魔の翼 <br>審判のオーブ</p>              | "                                                                 | 1\~3   |
| レインボー                                        | "                                                                 | 2\~4   |
| 水の怒り                                         | "                                                                 | 2\~5   |
{% endtab %}
{% endtabs %}

#### **💡 Fixed Option Range**

| **Orb**          | **Min HP** | **Max HP** | **Min Agility** | **Max Agilit**y |
| ---------------- | ---------- | ---------- | --------------- | --------------- |
| Orb of Wind      | 500        | 510        | 1               | 1.5             |
| Dark Orb         | 1,000      | 1,680      | 1.6             | 2.3             |
| Abyssal Orb      | 3,000      | 4,838      | 2.4             | 3.5             |
| Orb of Clarity   | 8,000      | 11,059     | 3.7             | 4.8             |
| Wind of Fire     | 17,000     | 20,908     | 4.9             | 6               |
| Wings of Light   | 30,736     | 36,455     | 6.2             | 8               |
| Explosion Energy | 53,590     | 67,204     | 8.2             | 10              |
| Devil's Hand     | 98,790     | 133,920    | 10.2            | 12              |
| Devil's Wings    | 196,862    | 265,685    | 12.2            | 13.5            |
| Orb of Judgment  | 420,000    | 528,988    | 15              | 18              |
| Rainbow          | 880,000    | 1,035,141  | 21              | 24              |
| Water Wrath      | 1,666,577  | 1,966,272  | 25              | 27              |

