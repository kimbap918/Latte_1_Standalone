# Latte_1 Standalone — 라테일 코디 시뮬레이터 (클라이언트 미설치용)

**This is a fan-made software utilizing assets from LaTale. To respect the original IP and due to internal reasons, the source code is private.**

라테일이 설치되어 있지 않은 PC에서도 바로 쓸 수 있는 **Latte_1 코디 시뮬레이터 독립 실행판**입니다! <br>
The standalone edition of the Latte_1 costume simulator — **no LaTale client installation required!**

<br>

![](https://i.imgur.com/aWAw7UP.png)

<br>
<br>

## 일반판과 무엇이 다른가요? (What's different from Latte_1?)

| | [Latte_1](https://github.com/kimbap918/Latte_1) | **Latte_1 Standalone** |
|---|---|---|
| 라테일 클라이언트 | 필요 (첫 실행 때 폴더 선택) | **필요 없음** |
| Requires LaTale client | Yes (asked on first launch) | **No** |
| 리소스 | 내 클라이언트에서 직접 불러옴 | **앱에 암호화되어 포함** |
| Resources | Loaded from your own client | **Bundled (encrypted)** |
| 리소스 업데이트 | 라테일 패치 후 "업데이트" 버튼 | **자동으로 내려받음** |
| Resource updates | "Update" button after a LaTale patch | **Downloaded automatically** |
| 용량 | 약 150MB | 약 240MB |
| Size | ~150MB | ~240MB |

라테일이 이미 설치되어 있고 Latte_1의 클라이언트 경로가 설정되어 있다면, 그 클라이언트의 데이터를 우선 사용합니다. <br>
If a LaTale client path is already configured, the client's data takes priority over the bundled data.

<br>
<br>

## Web Version
https://kimbap918.github.io/  <br>

현재 싱가포르의 서버를 사용중입니다. 로드 중 오랜 지연이나 에러 발생 시 30초~1분 뒤에 새로고침을 해주세요! <br>
설치 없이 바로 써보고 싶다면 웹 버전을, 서버 대기 없이 빠르게 쓰고 싶다면 이 독립 실행판을 추천해요.

Servers are based in Singapore. If you experience delays or errors, please refresh after 30s~1m. <br>
Prefer no waiting on a server? This standalone edition runs entirely on your PC.

<br>
<br>

## 다운로드 / 실행(Download / Run)

### ※ 가장 최신 버전의 릴리즈를 다운받아주시면 됩니다! Note: Please download the latest version of the release!

빌드된 실행 파일은 이 저장소의 [**Releases**](../../releases) 에서 zip으로 받아주세요! <br>
Get the built executable as a zip from this repository's [**Releases**](../../releases) page!

<br>

1. 최신 릴리스의 `Latte_1_standalone.zip` 다운로드 후 압축 해제 <br>
Download `Latte_1_standalone.zip` from the latest release and extract it.

<br>

2. 폴더 안의 `Latte_1.exe` 실행. **`Latte_1.exe`와 `_internal/` 폴더는 반드시 같은 위치에 함께 있어야 합니다!** (분리하면 실행되지 않음) <br>
Run `Latte_1.exe` inside the folder. **`Latte_1.exe` and the `_internal/` folder must stay in the same location together!** (It won't run if they're separated) <br>
  ![](https://i.imgur.com/HN09zQK.png)

<br>

3. 끝! 라테일 클라이언트를 고르는 과정 없이 바로 시작됩니다. 첫 실행은 데이터를 준비하느라 10초 정도 걸릴 수 있어요. <br>
That's it! There's no client-folder prompt. The first launch may take about 10 seconds while the data is prepared.

<br>
<br>

## 자동 업데이트(Auto Update)

### 리소스(데이터) 업데이트 / Resource (data) updates
라테일 패치로 새 아이템이 추가되면, 실행할 때 **바뀐 부분만** 자동으로 내려받습니다. (보통 수 MB 이하) <br>
받은 뒤에는 **프로그램을 다시 시작하면** 적용돼요. 상단의 버전 표시줄에 안내가 뜹니다. <br>
When a LaTale patch adds new items, only **the changed parts** are downloaded automatically on launch (usually a few MB). <br>
Restart the program to apply them. The version bar at the top tells you when new data is ready.

### 프로그램 업데이트 / App updates
새 버전의 프로그램이 나오면 상단에 **앱 업데이트** 버튼이 나타납니다. 누르면 자동으로 교체되고 다시 시작됩니다. <br>
When a new version of the program is released, an **App Update** button appears at the top. Click it and the app replaces itself and restarts.

<br>
<br>

## 기능(Features)

![](https://i.imgur.com/BFcmHVm.png)

<br>

### 1. 검색창(Search Bar)
머리/눈/피부/패션 등을 검색할수 있습니다. <br>
Search for hair, eyes, skin, fashion items, and more. <br>

![](https://i.imgur.com/UmjuNCF.png)

<br>

### 2. 버전확인(Version Check)
현재 사용 중인 리소스의 버전을 확인할수 있습니다. 독립 실행판에서는 새 데이터가 자동으로 내려받아지며, 받은 뒤 재시작하면 적용됩니다. <br>
Check the version of the resources currently in use. In the standalone edition, new data is downloaded automatically and applied after a restart. <br>

![](https://i.imgur.com/Jq3W4hX.png)

<br>

### 3. 전환 토글(Mode Toggle)
전투/패션 장비, 성별, 기본 의상의 전환이 가능합니다. <br>
Switch between combat/fashion equipment, gender, and default outfits. <br>

![](https://i.imgur.com/o7SPvTJ.png)

<br>

### 4. 로드/세이브(Load/Save)

빈 슬롯에 캐릭터 저장이 가능합니다. LOAD시 저장한 캐릭터의 정보를 불러올수 있습니다. <br>
Save your character to an empty slot. Use LOAD to load a saved character's information. <br>

![](https://i.imgur.com/rec4zKL.png)

![](https://i.imgur.com/BTI8VPH.png)

<br>

### 5. 포즈/모션/이모티콘(Poses/Motions/Emoticons)
걷기, 뛰기, 사다리타기, 이모티콘 등을 사용하여 캐릭터의 여러 동작을 확인할수 있습니다. <br>
아래의 자동재생 토글을 눌러야 캐릭터의 움직임이 보여요! <br>
Check out various character actions such as walking, running, climbing ladders, and emoticons. <br>
You need to turn on the auto-play toggle below to see the character's movement! <br>

![](https://i.imgur.com/Gv08KPP.gif)

<br>

### 6. 캐릭터 토글(Character Toggles)
패션 비활성 여부, 잔상, 이동테스트 등을 할수 있는 토글입니다. <br>
Toggles for disabling fashion, afterimage effects, movement test mode, and more. <br>

![](https://i.imgur.com/sMnJ9OV.png)

<br>

### 7. 배경/이미지 저장(Save Background/Image)
현재 캐릭터의 모습을 저장할수 있어요! <br>
Save the current look of your character! <br>

![](https://i.imgur.com/HCPBE5v.png)

<br>

### 8. 장비창(Equipment Window)
현재 캐릭터가 착용한 장비를 확인할 수 있습니다. X버튼을 누르거나 우클릭시 장착이 해제됩니다. <br>
Check the equipment currently worn by your character. Click the X button or right-click to unequip. <br>

![](https://i.imgur.com/QaZ5GVf.png)

<br>
<br>

## 자주 묻는 질문(FAQ)

**Q. 인터넷이 없어도 되나요? / Does it work offline?** <br>
네, 실행과 코디는 오프라인에서도 됩니다. 자동 업데이트 확인만 인터넷이 필요하고, 실패해도 기존 데이터로 정상 동작해요. <br>
Yes. Everything works offline; only the automatic update check needs internet, and it fails silently.

**Q. 저장한 캐릭터와 설정은 어디에 있나요? / Where are my saved characters and settings?** <br>
`%APPDATA%\charsim` 폴더에 저장됩니다. 프로그램을 업데이트해도 유지돼요. <br>
They are stored in `%APPDATA%\charsim` and are kept across app updates.

**Q. 일반판(Latte_1)과 같이 써도 되나요? / Can I use it alongside Latte_1?** <br>
네. 설정/저장 정보는 공유되고, 이미 일반판에서 라테일 클라이언트 경로를 설정했다면 독립 실행판도 그 클라이언트를 우선 사용합니다. <br>
Yes. Settings and saves are shared, and if a LaTale client path is already configured, the standalone edition uses the client first.

**Q. 새 데이터가 안 받아져요. / New data isn't being downloaded.** <br>
인터넷 연결을 확인하고 프로그램을 한 번 껐다 켜 주세요. 데이터 업데이트는 실행할 때마다 확인합니다. <br>
Check your connection and restart the program; updates are checked on every launch.

<br>
<br>

## 제작자
chipok(kimbap918)
![](https://i.imgur.com/cMyuo3o.png)

<br>

이 프로그램은 라테일(원작: Actoz Soft) 팬메이드 도구이며, 원작의 저작권은 Actoz Soft에 있습니다. <br>
프로그램에 포함된 게임 리소스는 암호화되어 있으며, 이를 추출하거나 재배포하는 행위는 허용되지 않습니다. <br>
This program is a fan-made desktop tool for LaTale. All original game copyrights belong to Actoz Soft. <br>
The game resources included in this program are encrypted; extracting or redistributing them is not permitted.
