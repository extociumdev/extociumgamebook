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

{% hint style="info" %}
⚠️ The minimum and maximum values of options may be adjusted based on a percentage due to balance updates.
{% endhint %}

#### <mark style="color:blue;">1️⃣Fixed option</mark>

An option that is 100% applied to all orbs. \
The fixed option is randomly applied within a predefined minimum to maximum range for each weapon. The fixed value varies for each weapon in terms of the primary stat.

| Option        | Spawn Probability (%) |
| ------------- | --------------------- |
| Agility (AGI) | 100                   |
| HP            | 100                   |

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

💡 **Primary Stat Option Range Guide** \
👉[ **Click here**](orb-stats.md#primary-stat-option-range) to check the minimum and maximum values for primary stat options!

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
| Critical Chance (CP)        | 3                     |
| Skill Attack Point (SAP)    | 8\~10                 |
| Skill Critical Bonus (SCB)  | 8\~10                 |
| Skill Critical Chance (SCP) | 3                     |
| Cooltime Reduction (CR)     | 4                     |
| Agility (AGI)               | 0.5\~1                |

💡 **Secondary Stat Option Range Guide** \
👉[ **Click here** ](orb-stats.md#secondary-stat-option-range)to check the minimum and maximum values for secondary stat options!

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

{% hint style="info" %}
⚠️ 옵션의 최소\~최대값은 밸런스 수정에 따라 일부 값이 '비율 기준'으로 조정될 수 있습니다.
{% endhint %}

#### <mark style="color:blue;">1️⃣고정 옵션</mark>

모든 오브에 100% 적용되는 옵션입니다. \
고정 옵션은 각 무기에 정해진 최소 \~ 최대 값 안에서 랜덤하게 적용됩니다.\
1차 스탯의 경우, 무기마다 적용되는 고정 값이 다릅니다.

| 옵션       | 생성 확률 (%) |
| -------- | --------- |
| 민첩 (AGI) | 100       |
| HP       | 100       |

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

💡 **1차 스탯 옵션 범위 안내** \
👉 [**여기를 클릭**](orb-stats.md#primary-stat-option-range)하여 1차 스탯 옵션의 최소\~최대값을 확인하세요!

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
| 치명타 확률 (CP)      | 3         |
| 스킬 공격력 (SAP)     | 8\~10     |
| 스킬 치명타 보너스 (SCB) | 8\~10     |
| 스킬 치명타 확률 (SCP)  | 3         |
| 쿨타임 감소 (CR)      | 4         |
| 민첩 (AGI)         | 0.5\~1    |

💡 **2차 스탯 옵션 범위 안내** \
👉 [**여기를 클릭**](orb-stats.md#secondary-stat-option-range)하여 2차 스탯 옵션의 최소\~최대값을 확인하세요!

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

{% hint style="info" %}
⚠️ オプションの最小～最大値は、バランス調整により一部の値が「割合基準」で調整される場合があります。
{% endhint %}

#### <mark style="color:blue;">1️⃣固定オプション</mark>

すべてのオーブに100%適用されるオプションです。 \
固定オプションは、各武器に設定された最小値～最大値の範囲内でランダムに適用されます。\
&#x20;1次ステータスの場合、武器ごとに適用される固定値が異なります。

| オプション       | 生成確率 (%) |
| ----------- | -------- |
| アジャイル (AGI) | 100      |
| HP          | 100      |

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

💡 **1次ステータスオプションの範囲案内** \
👉 [**こちらをクリックして**](orb-stats.md#primary-stat-option-range)、1次ステータスオプションの最小～最大値を確認してください！

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
| クリティカル確率 (CP)       | 3        |
| スキル攻撃力 (SAP)        | 8\~10    |
| スキルクリティカルボーナス (SCB) | 8\~10    |
| スキルクリティカル確率 (SCP)   | 3        |
| クールタイム減少 (CR)       | 4        |
| アジャイル (AGI)         | 0.5\~1   |

💡 **2次ステータスオプションの範囲案内** \
👉 [**こちらをクリックして**](orb-stats.md#secondary-stat-option-range)、2次ステータスオプションの最小～最大値を確認してください！

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

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-header-hidden data-full-width="true"><thead><tr><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Orb</strong></td><td><strong>Min HP</strong></td><td><strong>Max HP</strong></td><td><strong>Min Agility</strong></td><td><strong>Max Agilit</strong>y</td><td><strong>CON</strong></td><td><strong>WIZ</strong></td></tr><tr><td>Orb of Wind</td><td>500</td><td>510</td><td>1</td><td>1.5</td><td></td><td></td></tr><tr><td>Dark Orb</td><td>1,000</td><td>1,680</td><td>1.6</td><td>2.3</td><td></td><td></td></tr><tr><td>Abyssal Orb</td><td>3,000</td><td>4,838</td><td>2.4</td><td>3.5</td><td></td><td></td></tr><tr><td>Orb of Clarity</td><td>8,000</td><td>11,059</td><td>3.7</td><td>4.8</td><td></td><td></td></tr><tr><td>Wind of Fire</td><td>17,000</td><td>20,908</td><td>4.9</td><td>6</td><td></td><td></td></tr><tr><td>Wings of Light</td><td>30,736</td><td>36,455</td><td>6.2</td><td>8</td><td></td><td></td></tr><tr><td>Explosion Energy</td><td>53,590</td><td>67,204</td><td>8.2</td><td>10</td><td></td><td></td></tr><tr><td>Devil's Hand</td><td>98,790</td><td>133,920</td><td>10.2</td><td>12</td><td></td><td></td></tr><tr><td>Devil's Wings</td><td>196,862</td><td>265,685</td><td>12.2</td><td>13.5</td><td></td><td></td></tr><tr><td>Orb of Judgment</td><td>420,000</td><td>528,988</td><td>15</td><td>18</td><td></td><td></td></tr><tr><td>Rainbow</td><td>880,000</td><td>1,035,141</td><td>21</td><td>24</td><td>2</td><td>1</td></tr><tr><td>Water Wrath</td><td>1,666,577</td><td>1,966,272</td><td>25</td><td>27</td><td>4</td><td>3</td></tr></tbody></table>



#### 💡**Primary Stat Option Range**

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-full-width="true"><thead><tr><th>Orb</th><th>STR MIN</th><th>STR MAX</th><th>DEX MIN</th><th>DEX MAX</th><th>INT MIN</th><th>INT MAX</th><th>CON MIN</th><th>CON MAX</th><th>WIZ MIN</th><th width="144.79998779296875">WIZ MAX</th><th>CHA MIN</th><th>CHA MAX</th></tr></thead><tbody><tr><td>Orb of Wind</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Dark Orb</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Abyssal Orb</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Orb of Clarity</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Wind of Fire</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Wings of Light</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Explosion Energy</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Devil's Hand</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Devil's Wings</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Orb of Judgment</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Rainbow</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Water Wrat</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr></tbody></table>



#### 💡Secondary **Stat Option Range**

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-full-width="true"><thead><tr><th>Orb</th><th>AP MIN</th><th>AP MAX</th><th>HP MIN</th><th>HP MAX</th><th>MP MIN</th><th>MP MAX</th><th>CB MIN</th><th>CB MAX</th><th>CP MIN</th><th width="117.59991455078125">CP MAX</th><th>SAP MIN</th><th>SAP MAX</th><th>SCB MIN</th><th>SCB MAX</th><th>SCP MIN</th><th>SCP MAX</th></tr></thead><tbody><tr><td>Orb of Wind</td><td>3</td><td>9</td><td>30</td><td>300</td><td>15</td><td>150</td><td>3</td><td>9</td><td>1</td><td>1</td><td>3</td><td>9</td><td>3</td><td>9</td><td>1</td><td>1</td></tr><tr><td>Dark Orb</td><td>6</td><td>21</td><td>150</td><td>1,500</td><td>75</td><td>750</td><td>6</td><td>21</td><td>1</td><td>2</td><td>6</td><td>21</td><td>6</td><td>21</td><td>1</td><td>2</td></tr><tr><td>Abyssal Orb</td><td>15</td><td>36</td><td>600</td><td>2,400</td><td>300</td><td>1,200</td><td>15</td><td>36</td><td>1</td><td>3</td><td>15</td><td>36</td><td>15</td><td>36</td><td>1</td><td>3</td></tr><tr><td>Orb of Clarity</td><td>21</td><td>66</td><td>1,800</td><td>4,500</td><td>900</td><td>2,250</td><td>21</td><td>66</td><td>1</td><td>4</td><td>21</td><td>66</td><td>21</td><td>66</td><td>1</td><td>4</td></tr><tr><td>Wind of Fire</td><td>36</td><td>105</td><td>3,000</td><td>7,200</td><td>1,500</td><td>3,600</td><td>36</td><td>105</td><td>1</td><td>5</td><td>36</td><td>105</td><td>36</td><td>105</td><td>1</td><td>5</td></tr><tr><td>Wings of Light</td><td>54</td><td>150</td><td>4,200</td><td>9,000</td><td>2,100</td><td>4,500</td><td>54</td><td>150</td><td>1</td><td>6</td><td>54</td><td>150</td><td>54</td><td>150</td><td>1</td><td>6</td></tr><tr><td>Explosion Energy</td><td>72</td><td>210</td><td>5,400</td><td>12,000</td><td>2,700</td><td>6,000</td><td>72</td><td>210</td><td>1</td><td>7</td><td>72</td><td>210</td><td>72</td><td>210</td><td>1</td><td>7</td></tr><tr><td>Devil's Hand</td><td>105</td><td>270</td><td>7,200</td><td>18,000</td><td>3,600</td><td>9,000</td><td>105</td><td>270</td><td>1</td><td>8</td><td>105</td><td>270</td><td>105</td><td>270</td><td>1</td><td>8</td></tr><tr><td>Devil's Wings</td><td>400</td><td>3,000</td><td>12,000</td><td>24,000</td><td>6,000</td><td>12,000</td><td>400</td><td>3,000</td><td>1</td><td>9</td><td>400</td><td>3,000</td><td>400</td><td>3,000</td><td>1</td><td>9</td></tr><tr><td>Orb of Judgment</td><td>3,500</td><td>10,000</td><td>30,000</td><td>100,000</td><td>20,000</td><td>70,000</td><td>3,500</td><td>10,000</td><td>1</td><td>10</td><td>3,500</td><td>10,000</td><td>3,500</td><td>10,000</td><td>1</td><td>10</td></tr><tr><td>Rainbow</td><td>15,000</td><td>20,000</td><td>120,000</td><td>160,000</td><td>90,000</td><td>130,000</td><td>15,000</td><td>20,000</td><td>1</td><td>11</td><td>15,000</td><td>20,000</td><td>15,000</td><td>20,000</td><td>1</td><td>11</td></tr><tr><td>Water Wrat</td><td>25,000</td><td>30,000</td><td><mark style="color:blue;"><strong>300,000</strong></mark></td><td><mark style="color:blue;"><strong>400,000</strong></mark></td><td>150,000</td><td>190,000</td><td>25,000</td><td>30,000</td><td>4</td><td>14</td><td>25,000</td><td>30,000</td><td>25,000</td><td>30,000</td><td>4</td><td>14</td></tr></tbody></table>
