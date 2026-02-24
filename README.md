<section id="top">
    <p style="text-align:center;" align="center">
        <img align="center" src="/res/plugin/wrathcombo.png" width="250" />
    </p>
    <h1 style="text-align:center;" align="center">Wrath Combo</h1>
    <p style="text-align:center;" align="center">
        콤보 공격과 상호 배타적인 능력을 하나의 버튼으로 압축한 다음 일부 버튼으로 압축합니다.
    </p>
</section>

<!-- Badges -->
<p align="center"> 
<!-- Build & commit activity -->
  <!--no workflow on wrathcombo yet <a href="https://github.com/PunishXIV/WrathCombo/actions/workflows/build.yml" alt="Build">
    <img src="https://img.shields.io/github/actions/workflow/status/PunishXIV/WrathCombo/build.yml?branch=main&style=for-the-badge" /></a>-->
  <a href="https://github.com/PunishXIV/WrathCombo/commits/main" alt="Commits">
    <img src="https://img.shields.io/github/last-commit/PunishXIV/WrathCombo/main?color=00D162&style=for-the-badge" /></a>
   <a href="https://github.com/PunishXIV/WrathCombo/commits/main" alt="Commit Activity">
    <img src="https://img.shields.io/github/commit-activity/m/PunishXIV/WrathCombo?color=00D162&style=for-the-badge" /></a>
  <br> 
<!-- Other -->
  <a href="https://github.com/PunishXIV/WrathCombo/issues" alt="Open Issues">
    <img src="https://img.shields.io/github/issues-raw/PunishXIV/WrathCombo?color=EA9C0A&style=for-the-badge" /></a>
  <a href="https://github.com/PunishXIV/WrathCombo/graphs/contributors" alt="Contributors">
    <img src="https://img.shields.io/github/contributors/PunishXIV/WrathCombo?color=009009&style=for-the-badge" /></a>
<br>
<!-- Version -->
  <a href="https://github.com/PunishXIV/WrathCombo/tags" alt="Release">
    <img src="https://img.shields.io/github/v/tag/PunishXIV/WrathCombo?label=Release&logo=git&logoColor=ffffff&style=for-the-badge" /></a>
<br>
  <a href="https://discord.gg/Zzrcc8kmvy" alt="Discord">
    <img src="https://discordapp.com/api/guilds/1001823907193552978/embed.png?style=banner2" /></a>
</p>

<br><br>

<section id="about">

# Wrath Combo 소개

<p> Wrath Combo는 <a href="https://goatcorp.github.io/" alt="XIVLauncher">XIVLuncher</a>용 플러그인입니다.<br><br>
    이는 XIVCombo 플러그인을 대폭 강화한 버전으로, 
    사용자가 PvE, PvP 등 다양한 콘텐츠에서 자신만의 딜/힐사이클을 가능한 한 세밀하게 또는 단순하게
    심지어 단일 버튼 수준까지 설정할 수 있도록 커스터마이즈 가능한 기능과 옵션을 제공합니다.”
    <br><br>
    Wrath Combo는 새로운 기능을 추가하고 파이널 판타지 XIV의
    최신 직업 변경 사항을 반영하기 위해 정기적으로 업데이트됩니다.
    <br><br>
    <img src="/res/readme_images/demo.gif" width="450" />
    <br>
    해당 클립에서는 플러그인이 특정 직업의 전체 딜/힐사이클을 
    단일 버튼으로 압축하도록 설정되어 있으며, 그 버튼을 반복해서 누르고 있습니다.
    시연을 위해 실행된 모든 기술은 타임라인에 표시됩니다.
</p>
</section>

<!-- Installation -->
<section>

# Installation

<img src="/res/readme_images/adding_repo.jpg" width="450" />

게임 내에서 Dalamud 설정 메뉴를 열고 아래의 단계를 따라주세요.
이는 플러그인 설치 관리자 하단의 버튼을 통해서도 가능하며,
채팅창에 `/xlsettings` 를 입력해서도 열 수 있습니다.

1. 커스텀 플러그인 저장소 항목에서 하단의 빈 입력란에 `https://love.puni.sh/ment.json` 을 입력합니다.
2. "+" 버튼을 클릭합니다.
3. "변경사항 저장하고 닫기" 버튼을 클릭합니다.

게임 내에서 Dalamud 플러그인 설치 관리자 메뉴를 열고 아래의 단계를 따라주세요.
이는 채팅창에 `/xlplugins` 를 입력하여 열 수 있습니다.

1. 왼쪽의 "모든 플러그인" 탭을 클릭합니다.
2. "Wrath Combo" 를 검색합니다.
3. "설치" 버튼을 클릭합니다.

<p align="right"><a href="#top" alt="Back to top"><img src=/res/readme_images/arrowhead-up.png width ="25"/></a></p>
</section> <br>

<!-- Features -->
<section>

# 기능

아래에서는 Wrath Combo에서 제공하는 기능과 옵션 중 일부를 간단한 예시로 확인하실 수 있습니다. <br>
참고로, 이것은 일부 발췌일 뿐이며 전체 기능을 모두 보여주는 것은 아닙니다.


  <details><summary>PvE 기능</summary> <br>

 - 많은 직업에서 사용할 수 있는 "간단" (원버튼) 모드
 - 많은 직업에서 사용할 수 있는 "고급" 모드, 원하는 만큼 단순하게 조정 가능
 - 자동 딜/힐 사이클, 설정에 따라 딜/힐사이클을 자동으로 실행
 - 변형 던전 전용 기능
<br><br>
 - 탱커용 기술 앙갚음 겹침 보호
 - 탱커용 기술 끊기 기능
 - 힐러용 부활 기능
 - 마법 원거리 딜러용 정신 교란 겹침 보호
 - 마법 원거리 딜러용 부활 기능
 - 근접 딜러용 견제 겹침 보호
 - 근접 딜러용 진북 보호
 - 물리 원거리 딜러용 피해량 감소 버프 겹침 보호
 - 물리 원거리 딜러용 기술 끊기 기능
    
 그리고 훨씬 더 많은 기능들!

  </details>

  <details><summary>PvP 기능</summary> <br>

 - 모든 직업을 위한 "버스트 모드" 공격 기능
 - 긴급 힐
 - 긴급 방어
 - 빠른 정화
 - 방어 취소 방지
    
그리고 훨씬 더 많은 기능들!

  </details>

  <details><summary>기타 기능</summary> <br>

- 무인도 개척 질주 기능
- [BTN/MIN] 에우레카 기능
- [BTN/MIN] 눈 &  탐구자 기능
- [FSH] 낚싯대 던지기 낚아채기 기능
- [FSH] 잠수 기능

 그리고 훨씬 더 많은 기능들!

  </details>

제공되는 전체 기능을 경험하려면,
플러그인을 <a href="#installation" alt="install">설치</a> 하거나 더 많은 정보를
얻기 위해 [Discord](https://discord.gg/Zzrcc8kmvy) 서버를 방문하세요.

<p align="right"><a href="#top" alt="Back to top"><img src=/res/readme_images/arrowhead-up.png width ="25"/></a></p>

## 다른 플러그인과 함께 사용

### [Orbwalker](https://puni.sh/plugin/Orbwalker)

Wrath Combo는 Orbwalker 를 사용하여 자동 딜사이클 모드에서 플레이어의 움직임을 멈출 수 있으며, 
이는 플레이어가 캐스팅을 선택하기 전에 멈춰야 하는 필요성을 대체합니다.

1. Wrath Combo의 자동 딜사이클 설정을 엽니다: `/wrath autosettings`.
2. "Orbwalker 통합 활성화"를 체크합니다.
3. Orbwalker를 열고 설정을 확인합니다: `/orbwalker`.

### [AutoDuty](https://github.com/erdelf/AutoDuty)

Wrath Combo는 AutoDuty의 딜사이클 엔진으로 사용될 수 있으며,
던전 중에 Wrath Combo의 자동 딜사이클이 사용됩니다.
이를 활성화하려면:
1. AutoDuty의 설정 창을 엽니다: `/autoduty cfg`.
2. "Duty 설정" 섹션을 확장합니다.
3. "딜사이클 플러그인 상태 자동 관리"를 활성화합니다.
4. ("> Wrath Combo 설정 <" -> "자동 딜사이클을 위해 직업 자동 설정"도 체크)\
   (이미 직업 설정이 되어 있다면 이 단계는 건너뛸 수 있습니다)

### [Questionable](https://puni.sh/plugin/questionable)

Wrath Combo는 Questionable의 전투 모듈로 사용될 수 있으며,
퀘스트 중에 Wrath Combo의 자동 딜사이클이 사용됩니다.
이를 활성화하려면:
1. Questionable의 설정 창을 엽니다: `/qst config`.
2. "General" 탭으로 이동합니다.
3. "Preferred Combat Module"로 "Wrath Combo"를 선택합니다.

> 기본적으로 위의 두 플러그인은 Wrath에서 콤보가 설정되도록 보장하며, 
콤보가 설정되지 않은 경우 해당 콤보 아래의 
모든 설정을 `On` 으로 잠가 딜사이클이 실행되도록 합니다.

  <p align="right"><a href="#top" alt="Back to top"><img src=/res/readme_images/arrowhead-up.png width ="25"/></a></p>
</section> 

<!-- Commands -->
<section>

# 명령어

| **채팅 명령어**                       | **기능**                                                                                                                                                                   |
|:---------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `/wrath`                               | Toggles the main plugin window, where you can enable/disable features, access settings and more.                                                                               |
| `/wrath pve`                           | Opens the main plugin window, to the PvE tab.                                                                                                                                  |
| `/wrath pvp`                           | Opens the main plugin window, to the PvP tab.                                                                                                                                  |
| `/wrath settings`                      | Opens the main plugin window, to the Settings tab.                                                                                                                             |
| `/wrath autosettings`                  | Opens the main plugin window, to the Auto-Rotation tab.                                                                                                                        |
| `/wrath <X>`                           | Opens the main plugin window, to a specific job's PvE features.<br>Replace `<X>` with the jobs abbreviation.                                                                   |
| `/wrath auto`                          | Toggles Auto-Rotation **on** or **off**.                                                                                                                                       |
| `/wrath auto <X>`                      | Sets Auto-Rotation to a specific state.<br>Replace `<X>` with `on`, `off`, or `toggle`.                                                                                        |
| `/wrath auto target <X> <Y>`           | Sets Auto-Rotation targeting mode.<br>Replace `<X>` with `damage` or `healer`.<br>For damage, `<Y>` can be: `manual`, `highest_max`, `lowest_max`, `highest_current`, `lowest_current`, `tank_target`, `nearest`, `furthest`.<br>For healer, `<Y>` can be: `manual`, `highest_current`, `lowest_current`.                |
| `/wrath combo`                         | Toggles action replacing **on** or **off**.<br>When off, actions will not be replaced with combos from the plugin. Auto-Rotation will still work.                              |
| `/wrath combo <X>`                     | Sets action replacing to a specific state.<br>Replace `<X>` with `on`, `off`, or `toggle`.                                                                                     |
| `/wrath ignore`                        | Adds a targeted NPC, and all instances of it, to an ignore list for Auto-Rotation's auto-targeting.<br>Manage this list in the Auto-Rotation tab.                              |
| `/wrath toggle <X>`                    | Toggles a specific feature or option **on** or **off**. Does not work while in combat.<br>Replace `<X>` with its internal name (or ID).                                        |
| `/wrath set <X>`                       | Turns a specific feature/option **on**. Does not work when in combat.<br>Replace `<X>` with its internal name (or ID).                                                         |
| `/wrath unset <X>`                     | Turn a specific feature/option **off**. Does not work when in combat.<br>Replace `<X>` with its internal name (or ID).                                                         |
| `/wrath unsetall`                      | Turns all features and options **off** at once.                                                                                                                                |
| `/wrath list ...`                      | Prints lists of feature's internal names to the game chat based on filter arguments.<br>Requires an appended filter. See Below.                                                |
| `/wrath list set`<br/>`/wrath enabled` | Prints a list of all currently enabled features & options in the game chat.                                                                                                    |
| `/wrath list unset`                    | Prints a list of all currently disabled features & options in the game chat.                                                                                                   |
| `/wrath list all`                      | Prints a list of every feature & option in the game chat, regardless of state.                                                                                                 |
| `/wrath list ... <X>`                  | All list commands can also optionally accept a job parameter, to filter the list down to a specific job.<br>Replace `<X>` with the jobs abbreviation.                          |
| `/wrath opener`                        | Outputs your current openers status to chat.                                                                                                                                   |
| `/wrath debug`                         | Outputs a debug file to your desktop containing only relevant features/options for your current job.<br>To be sent to developers, to help in bug-fixing. Completely anonymous. |
| `/wrath debug <X>`                     | Outputs a debug file containing only job-relevant features/options.<br>Replace `<X>` with the jobs abbreviation.                                                               |
| `/wrath debug all`                     | Outputs a debug file containing all features/options.                                                                                                                          |

<p align="right"><a href="#top" alt="Back to top"><img src=/res/readme_images/arrowhead-up.png width ="25"/></a></p>
</section>

<!-- Contributing -->
<section>

# 기여

프로젝트에 대한 기여는 언제나 환영합니다 - GitHub에서
[pull request](https://github.com/PunishXIV/WrathCombo/pulls)를 자유롭게 제출해 주세요,
하지만 이상적으로는
[Discord](https://discord.gg/Zzrcc8kmvy) 서버에서 우리와 연락하여 필요한 변경 사항을 만들고
제출물을 검토할 수 있도록 소통할 수 있으면 좋습니다!


시작하는 데 도움이 될 [기여 정보](CONTRIBUTING.md)와
[사용 가능한 가이드](CONTRIBUTING.md#guides-on-using-specific-parts-of-wrath)도 찾을 수 있습니다.

   <p align="right"><a href="#top" alt="Back to top"><img src=/res/readme_images/arrowhead-up.png width ="25"/></a></p>
</section>

<br><br>

<!-- Attribution -->
<div align="center">
  <a href="https://puni.sh/" alt="Puni.sh">
    <img src="https://github.com/PunishXIV/AutoHook/assets/13919114/a8a977d6-457b-4e43-8256-ca298abd9009" /></a>
<br>
  <a href="https://discord.gg/Zzrcc8kmvy" alt="Discord">
    <img src="https://discordapp.com/api/guilds/1001823907193552978/embed.png?style=banner2" /></a>
</div>
