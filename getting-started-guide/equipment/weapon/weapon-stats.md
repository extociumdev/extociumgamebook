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
| CHA                      | 0 or 100               |

💡 **Equipment Fixed Option Range Guide**

👉[ **Click here** ](weapon-stats.md#fixed-option-range)to check the **minimum and maximum fixed stat values for each piece of equipment!**

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

💡 **Primary Stat Option Range Guide** \
👉 [**Click here**](weapon-stats.md#primary-stat-option-range) to check the minimum and maximum values for primary stat options!

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

💡 **Secondary Stat Option Range Guide** \
👉 [**Click here**](weapon-stats.md#secondary-stat-option-range) to check the minimum and maximum values for secondary stat options!

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
| CHA          | 0 or 100  |

💡 **장비 고정 옵션 범위 안내**

👉 [**여기를 클릭**](weapon-stats.md#fixed-option-range)하여 **장비별 적용 가능한 고정 스탯의 최소\~최대값**을 확인하세요!

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

💡 **1차 스탯 옵션 범위 안내** \
👉 [**여기를 클릭**](weapon-stats.md#primary-stat-option-range)하여 1차 스탯 옵션의 최소\~최대값을 확인하세요!

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

💡 **2차 스탯 옵션 범위 안내** \
👉 [**여기를 클릭**](weapon-stats.md#secondary-stat-option-range)하여 2차 스탯 옵션의 최소\~최대값을 확인하세요!

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
| CHA          | 0 or 100 |

💡 **装備固定オプション範囲ガイド**

👉 [**こちらをクリック** して](weapon-stats.md#fixed-option-range)、**各装備に適用される固定ステータスの最小～最大値**を確認しましょう！

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

💡 **1次ステータスオプションの範囲案内** \
👉 [**こちらをクリック**](weapon-stats.md#primary-stat-option-range)**して**、1次ステータスオプションの最小～最大値を確認してください！

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

💡 **2次ステータスオプションの範囲案内** \
👉 [**こちらをクリックして**](weapon-stats.md#secondary-stat-option-range)、2次ステータスオプションの最小～最大値を確認してください！

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

#### 💡Fixed Option Range&#x20;

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-header-hidden><thead><tr><th></th><th width="114"></th><th></th><th></th><th></th><th width="79.3572998046875"></th><th width="80.26431274414062"></th><th width="84.49053955078125"></th><th></th></tr></thead><tbody><tr><td><strong>Weapon</strong></td><td><strong>Min AP</strong></td><td><strong>Max AP</strong></td><td><strong>Min SAP</strong></td><td><strong>Max SAP</strong></td><td><strong>STR</strong></td><td><strong>DEX</strong></td><td><strong>INT</strong></td><td><strong>CHA</strong></td></tr><tr><td>Wooden Sword</td><td>30</td><td>32</td><td>30</td><td>32</td><td></td><td></td><td></td><td></td></tr><tr><td>Bronze Sword</td><td>120</td><td>140</td><td>120</td><td>140</td><td></td><td></td><td></td><td></td></tr><tr><td>Steel Sword</td><td>260</td><td>336</td><td>260</td><td>336</td><td></td><td></td><td></td><td></td></tr><tr><td>Flamberg</td><td>620</td><td>768</td><td>620</td><td>768</td><td></td><td></td><td></td><td></td></tr><tr><td>Paladin's Sword</td><td>1,300</td><td>1,584</td><td>1,300</td><td>1,584</td><td></td><td></td><td></td><td></td></tr><tr><td>Orc eye</td><td>2,800</td><td>2,978</td><td>2,800</td><td>2,978</td><td></td><td></td><td></td><td></td></tr><tr><td>Damascus</td><td>5,400</td><td>5,545</td><td>5,400</td><td>5,545</td><td></td><td></td><td></td><td></td></tr><tr><td>Savage Sword</td><td>10,200</td><td>11,160</td><td>10,200</td><td>11,160</td><td></td><td></td><td></td><td></td></tr><tr><td>Oracle Sword</td><td>20,500</td><td>22,364</td><td>20,500</td><td>22,364</td><td></td><td></td><td></td><td></td></tr><tr><td>Devil's Sword</td><td>40,000</td><td>44,982</td><td>40,000</td><td>44,982</td><td>1</td><td></td><td>1</td><td></td></tr><tr><td>Awakening Darkness</td><td>78,000</td><td>89,856</td><td>78,000</td><td>89,856</td><td>2</td><td>1</td><td>2</td><td></td></tr><tr><td>Sword of Light</td><td>152,000</td><td>167,200</td><td>152,000</td><td>167,200</td><td>4</td><td>1</td><td>4</td><td>1</td></tr></tbody></table>



#### 💡 **Primary Stat Option Range**

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-header-hidden><thead><tr><th></th><th width="114"></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Weapon</strong></td><td><strong>Min</strong> <strong>STR</strong></td><td><strong>Max STR</strong></td><td><strong>Min</strong> <strong>DEX</strong></td><td><strong>Max DEX</strong></td><td><strong>Min</strong> <strong>INT</strong></td><td><strong>Max INT</strong></td><td><strong>Min</strong> <strong>CON</strong></td><td><strong>Max CON</strong></td><td><strong>Min</strong> <strong>WIZ</strong></td><td><strong>Max WIZ</strong></td><td><strong>Min</strong> <strong>CHA</strong></td><td><strong>Max CHA</strong></td></tr><tr><td>Wooden Sword</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Bronze Sword</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Steel Sword</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Flamberg</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Paladin's Sword</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Orc eye</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Damascus</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Savage Sword</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Oracle Sword</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Devil's Sword</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Awakening Darkness</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Sword of Light</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td><td>1</td><td>3</td></tr></tbody></table>



#### 💡 **Secondary Stat Option Range**

📢 The table is long, so use the scrollbar below to scroll left and right to view the full table!

<table data-header-hidden><thead><tr><th></th><th width="114"></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Weapon</strong></td><td><strong>Min AP</strong></td><td><strong>Max AP</strong></td><td><strong>Min HP</strong></td><td><strong>Max HP</strong></td><td><strong>Min MP</strong></td><td><strong>Max MP</strong></td><td><strong>Min CB</strong></td><td><strong>Max CB</strong></td><td><strong>Min CP</strong></td><td><strong>Max CP</strong></td><td><strong>Min SAP</strong></td><td><strong>Max SAP</strong></td><td><strong>Min SCB</strong></td><td><strong>Max SCB</strong></td><td><strong>Min SCP</strong></td><td><strong>Max SCP</strong></td><td><strong>Min CR</strong></td><td><strong>Max CR</strong></td></tr><tr><td>Wooden Sword</td><td>3</td><td>9</td><td>30</td><td>300</td><td>15</td><td>150</td><td>3</td><td>9</td><td>1</td><td>1</td><td>3</td><td>9</td><td>3</td><td>9</td><td>1</td><td>1</td><td>1</td><td>1</td></tr><tr><td>Bronze Sword</td><td>6</td><td>21</td><td>150</td><td>1,500</td><td>75</td><td>750</td><td>6</td><td>21</td><td>1</td><td>1</td><td>6</td><td>21</td><td>6</td><td>21</td><td>1</td><td>1</td><td>1</td><td>1.5</td></tr><tr><td>Steel Sword</td><td>15</td><td>36</td><td>600</td><td>2,400</td><td>300</td><td>1200</td><td>15</td><td>36</td><td>1</td><td>2</td><td>15</td><td>36</td><td>15</td><td>36</td><td>1</td><td>2</td><td>1</td><td>2</td></tr><tr><td>Flamberg</td><td>21</td><td>66</td><td>1800</td><td>4,500</td><td>900</td><td>2250</td><td>21</td><td>66</td><td>1</td><td>2</td><td>21</td><td>66</td><td>21</td><td>66</td><td>1</td><td>2</td><td>1</td><td>2.5</td></tr><tr><td>Paladin's Sword</td><td>36</td><td>105</td><td>3000</td><td>7,200</td><td>1500</td><td>3600</td><td>36</td><td>105</td><td>1</td><td>3</td><td>36</td><td>105</td><td>36</td><td>105</td><td>1</td><td>3</td><td>1</td><td>3</td></tr><tr><td>Orc eye</td><td>54</td><td>150</td><td>4,200</td><td>9,000</td><td>2100</td><td>4500</td><td>54</td><td>150</td><td>1</td><td>3</td><td>54</td><td>150</td><td>54</td><td>150</td><td>1</td><td>3</td><td>1</td><td>3.5</td></tr><tr><td>Damascus</td><td>72</td><td>210</td><td>5,400</td><td>12,000</td><td>2700</td><td>6000</td><td>72</td><td>210</td><td>1</td><td>4</td><td>72</td><td>210</td><td>72</td><td>210</td><td>1</td><td>4</td><td>1</td><td>4</td></tr><tr><td>Savage Sword</td><td>105</td><td>270</td><td>7,200</td><td>18,000</td><td>3600</td><td>9000</td><td>105</td><td>270</td><td>1</td><td>4</td><td>105</td><td>270</td><td>105</td><td>270</td><td>1</td><td>4</td><td>1</td><td>4.5</td></tr><tr><td>Oracle Sword</td><td>400</td><td>3,000</td><td>12,000</td><td>24,000</td><td>6000</td><td>12000</td><td>400</td><td>3000</td><td>1</td><td>5</td><td>400</td><td>3000</td><td>400</td><td>3000</td><td>1</td><td>5</td><td>1</td><td>5</td></tr><tr><td>Devil's Sword</td><td>3,500</td><td>10,000</td><td>30,000</td><td>100,000</td><td>20000</td><td>70000</td><td>3500</td><td>10000</td><td>1</td><td>10</td><td>3500</td><td>10000</td><td>3500</td><td>10000</td><td>1</td><td>10</td><td>1</td><td>5.5</td></tr><tr><td>Awakening Darkness</td><td>15,000</td><td>20,000</td><td>120,000</td><td>160,000</td><td>90000</td><td>130000</td><td>15000</td><td>20000</td><td>1</td><td>11</td><td>15000</td><td>20000</td><td>15000</td><td>20000</td><td>1</td><td>11</td><td>1</td><td>6</td></tr><tr><td>Sword of Light</td><td>25,000</td><td>30,000</td><td>300,000</td><td>400,000</td><td>150000</td><td>190000</td><td>25000</td><td>30000</td><td>4</td><td>14</td><td>25000</td><td>30000</td><td>25000</td><td>30000</td><td>4</td><td>14</td><td>4</td><td>6.5</td></tr></tbody></table>

