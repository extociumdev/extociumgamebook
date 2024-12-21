# 🎲 XTO ↔ GOLD Swap

🛑 This information may be updated later than the game server data.\
🛑 이 내용은 게임 서버 데이터보다 늦게 업데이트 될 수 있습니다.\
🛑 この情報はゲームサーバーデータよりも遅れて更新される場合があります。



📢 _**Contents**_

* [XTO SWAP SERVICE](xto-gold-swap.md#xto-swap-service)
* [Abundance and Famine System](xto-gold-swap.md#abundance-and-famine-system)
* [Changes in game state based on swap amount](xto-gold-swap.md#changes-in-game-state-based-on-swap-amount)
* [BURN](xto-gold-swap.md#burn)





## XTO SWAP SERVICE

<div align="center"><figure><img src="../../.gitbook/assets/image (587).png" alt="" width="296"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/image (263).png" alt="" width="246"><figcaption></figcaption></figure></div>

The GOLD that players collect while playing the game can be swapped for XTO coins from Yeyilel at the bank. The amount of swap depends on your accumulated TP. See the table below.\
&#x20;                                                                         💠\
플레이어들이 게임을 즐기며 모은 GOLD는 은행의 Yeyilel에게서 XTO코인으로 스왑할 수 있습니다. \
누적 TP에 따라 스왑량이 달라집니다. 아래 표에서 확인하세요.\
&#x20;                                                                         💠\
プレイヤーがゲームを楽しみながら集めたGOLDは、銀行のYeyilelからXTOコインにスワップできます。累積TPによってスワップ量が異なります。 下の表で確認してください。

|    Accumulated TP  | Amount of Swap |
| :----------------: | :------------: |
|  TP 1k and higher  |       50       |
|  TP 50k or higher  |       100      |
| TP 150k and higher |       250      |
| TP 200k and higher |       350      |
| TP 300k and higher |       500      |

&#x20;                             **\*2023.10: Daily XTO swap amount change according to cumulative TP** &#x20;







## Abundance and Famine System

In EXTOCIUM, there exists a system called the _Abundance and Famine System_ to prevent rapid inflation of the XTO coin.

This system is closely related to the XTO swap service. _The Abundance and Famine System_ operates in _8-hour cycles_ and adjusts the game's state based on the amount of XTO swapped in the _previous 8 hours_. XTO coins are set to be swapable up to 15,000 per day. \
(Please note that the ratio of Gold to XTO and the daily swap limit may change if XTO coin experiences fluctuations in value.)\
&#x20;                                                                         💠\
EXTOCIUM에는 XTO coin의 가파른 인플레이션을 방지하기 위한 반감기 시스템이 존재한다. 우리는 그것을 풍요와 기근 시스템이라고 부른다.

이 시스템은 XTO 스왑 서비스와 밀접한 연관이 있다. Abundance and Famine System은 8시간 단위로 작동되며, 이전 8시간 동안 스왑된 XTO의 양을 기준으로 게임의 상태를 변경한다. XTO 코인은 하루 1만 5천개까지 스왑될 수 있도록 설정되어 있다. \
(물론, XTO 코인이 가치의 변동을 겪게 될 경우 골드와 XTO의 비율, 하루 스왑 가능량은 변동될 수 있음을 명시한다.)\
&#x20;                                                                         💠\
EXTOCIUMにはXTOcoinの急激なインフレを防止するための半減期システムが存在します。 私たちはそれを豊かさと飢饉システムと呼びます。 \
\
このシステムは、XTOスワップサービスと密接に関連しています。 Abundance and Famine Systemは8時間単位で動作し、過去8時間にスワップされたXTOの量を基準にゲームの状態を変更します。 XTOコインは1日1万5千個までスワップできるように設定されています。 \
(もちろん、XTOコインが価値の変動を経験する場合、ゴールドとXTOの比率、一日スワップ可能量は変動する可能性があることを明示します。)\


\


## Changes in game state based on swap amount



**Famine Condition:**

* If more than 3,300 XTO tokens are swapped in the last 8 hours, a Famine occurs in the EXTOCIUM game.
* During a Famine , the drop rates for items and gold decrease by 15%.
* If there is another Famine in the next step, the drop rates decrease by an additional 15% (total reduction of 30%).
* This condition can progress up to 5 steps (a maximum reduction of 75%).
* If the game continues in a Famine beyond this, the Famine level resets to 1 for each turn.
* If the Famine condition changes to a different state, regardless of previous effects, the drop rates immediately adjust to the drop rate of the new state.

**Normal Condition:**

* If XTO tokens are swapped between 666 and 3,300 in the last 8 hours, no special effects are applied.
* Drop rate adjustment: 0%

**Abundance Condition:**

* If fewer than 666 XTO tokens are swapped in the last 8 hours, abundance comes to EXTOCIUM.
* During abundance, the drop rates for items and gold increase by 5%.
* If there is another abundance in the next step, the drop rates increase by an additional 5% (total increase of 10%).
* This condition can progress up to 5 steps (a maximum increase of 25%).
* If the game continues in an abundance state beyond this, the abundance level resets to 1 for each turn.
* If the abundance condition changes to a different state, regardless of previous effects, the drop rates immediately adjust to the drop rate of the new state.

&#x20;                                                                         💠

**기근 상태:**

* XTO가 직전 8시간동안 3300개를 초과하여 스왑되면 EXTOCIUM 게임 내 기근이 찾아온다.
* 기근 상태에서는 아이템과 골드의 드랍률이 15% 감소한다.
* 다음 스텝에도 기근이 되면 드랍률이 15% 더 감소한다. ( 총 30% 감소 )
* 이 단계는 5단계 까지 진행된다. ( 최종 75% 감소 )
* 5단계를 지나 계속 기근이 유지되면, 매 턴당 기근 1단계부터 재 반복한다.
* 기근 상태에서 다른 상태로 변경될 경우, 이전 효과 누적에 관계없이 해당 상태의 드랍률 보정 값으로 즉시 변경된다.

**정상 상태:**

* XTO가 직전 8시간동안 3300개 이하, 666개 이상으로 스왑되면 어떠한 효과도 적용되지 않는다.
* 드랍률 보정 0%

**풍요 상태:**

* XTO가 직전 8시간동안 666개 미만으로 스왑되면 EXTOCIUM 게임 내 풍요가 찾아온다.
* 풍요 상태에서는 아이템과 골드의 드랍률이 5% 증가한다.
* 다음 스텝에도 풍요가 되면 드랍률이 5% 더 증가한다. ( 총 10% 증가 )
* 이 단계는 5단계 까지 진행된다. ( 최종 25% 증가 )
* 5단계를 지나 계속 풍요가 유지되면, 매 턴당 풍요 1단계부터 재 반복한다.
* 풍요 상태에서 다른 상태로 변경될 경우, 이전 효과 누적에 관계없이 해당 상태의 드랍률 보정 값으로 즉시 변경된다.

&#x20;                                                                         💠

**飢饉の状態:**

* XTOが直前の8時間で3300個を超過してスワップされると、EXTO CIUMゲーム内の飢饉が訪れます。
* 飢饉の状態では、アイテムとゴールドのドロップ率が 15% 減少します。
* 次のステップでも飢饉になるとドロップ率がさらに15%減少します。 (合計30%減少)
* この段階は5段階まで行われます。 (最終75%減少)
* 5段階を過ぎて飢饉が維持されれば、毎ターン当たり飢饉1段階から再繰り返します。
* 飢饉状態から別の状態に変更された場合、以前の効果累積に関係なく、その状態のドロップ率補正値に直ちに変更されます。

**正常状態:**

* XTOが直前の8時間で3300個以下、666個以上にスワップされれば、いかなる効果も適用されません。
* ドロップ率補正0%

**豊かな状態:**

* XTOが直前の8時間で666個未満にスワップされれば、EXTO CIUMゲーム内の豊かさが訪れます。
* 豊かな状態では、アイテムとゴールドのドロップ率が 5% 増加します。
* 次のステップでも豊かになるとドロップ率がさらに5%増加します。 (合計10%増)
* この段階は5段階まで行われます。 (最終 25% 増加 )
* 5段階を過ぎて豊かさが維持されれば、1ターンごとに豊かさ1段階から再繰り返します。
* 豊かな状態から別の状態に変更された場合、以前の効果累積に関係なく、その状態のドロップ率補正値に直ちに変更されます。



\


## BURN

XTO coins and Gold currency closely related to XTO coins will be continuously burned (converted to the development account/coin mining pool) under the following circumstances:

* When XTO coins are swapped for Gold, all paid XTO will be converted to the swap pool (coin mining pool). Additionally, Gold fees will be burned.
* When Gold is swapped for XTO coins, Gold fees and the amount of Gold swapped will be burned.
* When purchasing items with XTO coins, all paid XTO will be converted to the coin mining pool.

To prevent indiscriminate swapping, Gold fees are calculated based on the following bundles. The table below represents the current swap rates, and it should be noted that fee rates and the price of Gold may change based on in-game inflation situations.\
\
\*\*_Please note that "burning" in this context refers to the process of removing or reducing the supply of XTO coins and Gold currency by converting them into a development account or coin pool, effectively taking them out of circulation. This process helps manage the economy and prevent excessive swapping._\
\
\
XTO코인 및 XTO코인과 밀접하게 관련된 골드 재화는 아래와 같은 경우 지속적으로 소각(개발계정(채굴 풀)으로 환원)됩니다.

* XTO코인을 골드로 스왑했을 경우, 지불된 모든 XTO는 스왑 풀로 환원됩니다. (코인 채굴 풀) 또한, 골드 수수료가 소각 됩니다.&#x20;
* 골드를 XTO코인으로 스왑했을 경우, 골드 수수료와 스왑된 분량의 골드가 소각 됩니다.&#x20;
* XTO코인으로 아이템을 구매할 경우, 지불된 모든 XTO는 코인 채굴 풀로 환원됩니다.

또한 무분별한 스왑을 막기 위해, 아래와 같은 묶음 별 골드 수수료가 산정됩니다. 아래는 현재 스왑 도표이며, 게임 내 인플레이션 상황에 따라 수수료율 및 골드의 가격이 변경될 수 있음을 명시합니다.\
\
&#xNAN;_\*\*"소각"이란 XTO 코인과 골드를 개발 계정 또는 코인 풀로 전환하여 시장으로 부터 회수함으로써 공급을 제거하거나 감소시키는 과정을 의미합니다. 이 프로세스는 경제를 관리하고 과도한 스와핑을 방지하는 데 도움이 됩니다._\
\
\
XTOコインおよびXTOコインと密接に関連するゴールド財貨は、以下の場合、継続的に焼却(開発勘定(採掘プール)に還元)されます。

* XTOコインをゴールドにスワップした場合、支払われたすべてのXTOはスワッププールに還元されます。 （コイン採掘プール）また、ゴールド手数料が焼却されます。
* ゴールドをXTOコインにスワップした場合、ゴールド手数料とスワップ分のゴールドが焼却されます。
* XTOコインでアイテムを購入する場合、支払われたすべてのXTOはコイン採掘プールに還元されます。

また、無分別なスワップを防ぐために、以下のような束別ゴールド手数料が算定されます。 以下は現在のスワップ図表であり、ゲーム内のインフレ状況に応じて手数料率およびゴールドの価格が変更される可能性があることを明示しています。\
\
&#xNAN;_\*\*「焼却」とは、XTOコインとゴールドを開発アカウントまたはコインプールに転換して市場から回収することで供給を除去または減少させる過程を意味します。 このプロセスは、経済を管理し、過度のスワップを防止するのに役立ちます。_





Current Ratio: **1 XTO = 13,000 GOLD**

_<mark style="background-color:orange;">**GOLD > XTO**</mark>_

<table data-full-width="false"><thead><tr><th width="190" align="center">XTO</th><th width="254" align="right">GOLD*fee</th><th width="176" align="right">GOLD</th><th align="center">fee</th></tr></thead><tbody><tr><td align="center">50</td><td align="right">747,500</td><td align="right">650,000</td><td align="center">0.15</td></tr><tr><td align="center">100</td><td align="right">1,482,000</td><td align="right">1,300,000</td><td align="center">0.14</td></tr><tr><td align="center">250</td><td align="right">3,672,500</td><td align="right">3,250,000</td><td align="center">0.13</td></tr><tr><td align="center">350</td><td align="right">5,096,000</td><td align="right">4,550,000</td><td align="center">0.12</td></tr><tr><td align="center">500</td><td align="right">7,150,000</td><td align="right">6,500,000</td><td align="center">0.1</td></tr></tbody></table>



_<mark style="background-color:blue;">**XTO > GOLD**</mark>_

<table data-full-width="false"><thead><tr><th width="190" align="center">XTO</th><th width="254" align="right">GOLD*fee</th><th width="176" align="right">GOLD</th><th align="center">fee</th></tr></thead><tbody><tr><td align="center">50</td><td align="right">630,500</td><td align="right">650,000</td><td align="center">0.03</td></tr><tr><td align="center">200</td><td align="right">2,522,000</td><td align="right">2,600,000</td><td align="center">0.03</td></tr><tr><td align="center">1000</td><td align="right">12,610,000</td><td align="right">13,000,000</td><td align="center">0.03</td></tr><tr><td align="center">2500</td><td align="right">31,525,000</td><td align="right">32,500,000</td><td align="center">0.03</td></tr><tr><td align="center">5000</td><td align="right">63,050,000</td><td align="right">65,000,000</td><td align="center">0.03</td></tr></tbody></table>



