---
description: 🛑 Information on this page may differ from the current in-game data.
---

# 🌿 Skill Buff Type

{% tabs %}
{% tab title="ENG" %}

{% endtab %}

{% tab title="한국어" %}
**❓이 문서는 액티브 스킬 버프 타입에 대한 상세 정보를 제공합니다.**

### ◾Damage Buffs / Debuffs (데미지 증감 계열)

<table><thead><tr><th width="77.6363525390625">No.</th><th width="200.181884765625">내용</th><th width="175.0909423828125">버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>데미지를 n% 증가</td><td>대상의 최종 데미지*(1+n%)</td><td><p>대상의 최종 데미지*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>2</td><td>데미지를 n% 증가 *동일 카테고리 내 레이어 타입 버프</td><td>대상의 최종 데미지*(1+n%)</td><td><p>대상의 최종 데미지*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>3</td><td>데미지를 n% 증가 *동일 카테고리 내 레이어 타입 버프</td><td>대상의 최종 데미지*(1+n%)</td><td><p>대상의 최종 데미지*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>4</td><td>데미지 버프를 n% 감소</td><td>적용된 스킬 없음</td><td><p>대상이 가진 모든 데미지 버프 합산 값*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>5</td><td>Phys. DMG (물리 데미지)를 n% 증가</td><td>대상의 최종 물리 데미지*(1+n%)</td><td><p>대상의 최종 물리 데미지*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>6</td><td>Mag. DMG (마법 데미지)를 n% 증가</td><td>대상의 최종 마법 데미지*(1+n%)</td><td><p>대상의 최종 마법 데미지*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>7</td><td>EBD (Elemental Bonus Damage)를 n% 증가</td><td>대상의 최종 EBD*(1+n%)</td><td>적용된 스킬 없음</td></tr></tbody></table>

***

### ◾Critical Buffs / Debuffs (크리티컬 계열)

<table><thead><tr><th width="103.09088134765625">No.</th><th>내용</th><th>버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>Phys. Crit % (물리 치명타 확률)을 n% 증가</td><td>대상의 최종 Phys. Crit %*(1+n%)</td><td><p>대상의 최종 Phys. Crit %*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>2</td><td>Mag. Crit % (마법 치명타 확률)을 n% 증가</td><td>대상의 최종 Mag. Crit %*(1+n%)</td><td><p>대상의 최종 Mag. Crit %*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>3</td><td>Phys. Crit DMG (물리 치명타 데미지)를 n% 증가</td><td>대상의 최종 Phys. Crit DMG*(1+n%)</td><td><p>대상의 최종 Phys. Crit DMG*(1-n%) </p><p>0이하 처리 안함</p></td></tr><tr><td>4</td><td>Mag. Crit DMG (마법 치명타 데미지)를 n% 증가</td><td>대상의 최종 Mag. Crit DMG*(1+n%)</td><td><p>대상의 최종 Mag. Crit DMG*(1-n%) </p><p>0이하 처리 안함</p></td></tr></tbody></table>

***

### ◾Utility Cooldowns (유틸리티 / 쿨다운 계열)

<table><thead><tr><th width="84.90911865234375">No.</th><th>내용</th><th>버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>대상의 이동속도를 조절</td><td>대상의 이동속도*(1+n%)</td><td>대상의 이동속도*(1-n%)</td></tr><tr><td>2</td><td>회피율(EVA)을 n% 증가</td><td>대상의 최종 EVA*(1+n%)</td><td>적용된 스킬 없음</td></tr><tr><td>3</td><td>Cool Down Reload (CDR)을 n% 증가</td><td>대상의 최종 CDR*(1+n%) *CDR 증가 = 스킬 리로드 타임 감소</td><td><p>대상의 최종 CDR*(1-n%) </p><p><strong>CDR 100% 초과 시 음수 처리</strong> </p><p>음수 CDR = 스킬 리로드 타임 증가 (Cycle Disruption)</p></td></tr></tbody></table>

***

### ◾Survival (생존 계열)

<table><thead><tr><th width="86.72723388671875">No.</th><th>내용</th><th>버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>실드 (피격 데미지 감소율)를 n% 증가</td><td>대상이 받을 최종 데미지*(1-n%)</td><td>적용된 스킬 없음</td></tr><tr><td>2</td><td>무적</td><td>-</td><td>-</td></tr><tr><td>3</td><td><p>부활 </p><p>*부활의 깃털 아이템용 </p><p>추후 공성전 길드 스킬 도입 가능</p></td><td>-</td><td>-</td></tr><tr><td>4</td><td>상방 공격 (블리자드류)을 무시</td><td>-</td><td>-</td></tr><tr><td>5</td><td><p>휠윈드 상태. </p><p>이동속도가 빨라지고 데미지를 n% 감쇠하여 받음</p></td><td><p>이동속도 7로 고정 + 데미지 감쇠 </p><p>*추가 이속 버프 중첩 안됨<br>*이 타입에서 실드 버프를 중첩 사용할 경우, 휠윈드의 데미지 감소를 먼저 적용 후 실드 버프가 추가 적용됨. (합산이 아님)</p></td><td>-</td></tr></tbody></table>

***

### ◾Recovery (회복 계열)

<table><thead><tr><th width="85.81817626953125">No.</th><th>내용</th><th>버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>m초마다 MP를 n% 회복</td><td>대상의 MAX MP*(1+n%)씩 m초마다 회복</td><td>적용된 스킬 없음</td></tr><tr><td>2</td><td>m초마다 HP를 n% 회복</td><td>대상의 MAX HP*(1+n%)씩 m초마다 회복</td><td>적용된 스킬 없음</td></tr><tr><td>3</td><td>부식이 걸린 시간 동안 n의 데미지를 m초마다 부여</td><td>적용된 스킬 없음</td><td>-</td></tr></tbody></table>



***

### ◾Recovery Debuffs (회복 방해 계열)

<table><thead><tr><th width="103.0909423828125">No.</th><th>내용</th><th>버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>대상의 MP 사용량을 n% 증가</td><td>적용된 스킬 없음</td><td>대상이 시전한 스킬 사용 시 소모되는 MP량*(1+n%)</td></tr><tr><td>2</td><td>대상의 HP 회복량을 n% 감소</td><td>적용된 스킬 없음</td><td>대상이 시전한 회복 스킬의 회복량*(1-n%)</td></tr></tbody></table>

***

### ◾CC (군중 제어 계열)

<table><thead><tr><th width="93.0909423828125">No.</th><th>내용</th><th>Cure 영향 여부</th></tr></thead><tbody><tr><td>1</td><td>N초간 n 미터 밀려남</td><td>x</td></tr><tr><td>2</td><td>N초간 중앙으로 끌어당김</td><td>x</td></tr><tr><td>3</td><td>N초간 스턴</td><td>O</td></tr><tr><td>4</td><td>대시 어택</td><td>x</td></tr><tr><td>5</td><td>점프 어택</td><td>x</td></tr><tr><td>6</td><td>대상을 내 앞으로 끌어당겨옴</td><td>x</td></tr></tbody></table>



***

### ◾Cure (해제 계열)

| No. | 내용              |
| --- | --------------- |
| 1   | 대상의 디버프/상태이상 삭제 |
| 2   | 대상의 버프 삭제       |



***

### ◾Piercing (관통 계열)

<table><thead><tr><th width="91.272705078125">No.</th><th width="203">내용</th><th width="160.1817626953125">버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>EVA 관통. 타겟의 회피율(EVA)을 n% 무시</td><td>적용된 스킬 없음</td><td><p>대상의 최종 EBD(%) - n% </p><p>*EVA 0이하 처리하지 않음</p></td></tr><tr><td>2</td><td>실드 관통. 타겟의 실드를 n% 무시</td><td>적용된 스킬 없음</td><td><p>대상의 최종 실드 버프(%) - n% </p><p>*실드 버프 없을 경우 처리하지 않음</p></td></tr></tbody></table>



***

### ◾Stealth & Detection Cooldowns (은신 / 감지 계열)

<table><thead><tr><th width="89.45452880859375">No.</th><th width="270.1817626953125">내용</th><th width="193.5455322265625">버프 효과</th><th>디버프 효과</th></tr></thead><tbody><tr><td>1</td><td>다른 플레이어들이 볼 수 없도록 은신 상태가 됨 은신 상태 첫 공격에 부가 데미지 n%</td><td>대상의 최종 데미지*(1+n%)</td><td>-</td></tr><tr><td>2</td><td>레이더 범위 안에서 은신한 대상을 볼 수 있음</td><td>-</td><td>-</td></tr><tr><td>3</td><td>은신한 대상에게 추가 데미지를 n%</td><td>대상의 최종 데미지*(1+n%)</td><td>-</td></tr></tbody></table>

&#x20;
{% endtab %}

{% tab title="日本語" %}

{% endtab %}
{% endtabs %}
