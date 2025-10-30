# Kacky Dashboard Automator
https://github.com/user-attachments/assets/3290196c-27ca-4681-aa07-b364f1e01e16

An automated tool to transfer records from **Kacky Event** in Trackmania to Google Sheets.

## Description
It is a program that retrieves a user's name, cleared maps, ranking, and record data from [https://kackiestkacky.com](https://kackiestkacky.com) and [https://kackyreloaded.com](https://kackyreloaded.com), then automatically inputs the data into a Google Sheet.
It also includes features such as accessing user pages, connecting to the LIS spreadsheet, and comparing rankings with friends.

### Source
#### Spreadsheet (by. Zemus42)
> [Kackiest Kacky (TMNF) Dashboard](https://docs.google.com/spreadsheets/d/1G44h9PAHVSKkYwD4ek_v6WpI696QPMAJPo1dMVi1IdM/edit?gid=92899346#gid=92899346)  
> [Kacky Reloaded (TM2020) Dashboard](https://docs.google.com/spreadsheets/d/1KoqfsvTzuKrHSlHEV9SBYpLdJLxni0lkM3P3NB_fOcg/edit?gid=92899346#gid=92899346)

#### Icon
> <a href="https://www.flaticon.com/kr/free-icon/stop-button_4340168?related_id=4340168" title="stop-button">stop-button: Kalashnyk - Flaticon</a>  
> <a href="https://www.flaticon.com/kr/free-icon/globe_12871678?term=%EC%A7%80%EA%B5%AC&page=1&position=25&origin=tag&related_id=12871678" title="globe">globe: SumberRejeki - Flaticon</a>  
> <a href="https://www.flaticon.com/kr/free-icon/settings_667416" title="settings">settings: Freepik - Flaticon</a>

## Installation
Download the latest version of `Kacky-Dashboard-Automator.zip` file from the **[Release](https://github.com/Viun2232/kackiest-kacky-dashboard-automator/releases)** tab on the left and extract it.

## How to use
### Get the pid
1. Go to the Kacky website and search for your nickname (or find it manually)  
> https://kackiestkacky.com or https://kackyreloaded.com

2. Open your user profile and copy the corresponding pid  
`https://kackiestkacky.com/hunting/editions/players.php?pid=OOOO&edition=0`
> OOOO is your pid.

3. Enter the pid in the program.

### Get the SHEET_ID
1. Click the `Open Dashboard` button in the program or access the link below directly.
> [Kackiest Kacky (TMNF) Dashboard](https://docs.google.com/spreadsheets/d/1G44h9PAHVSKkYwD4ek_v6WpI696QPMAJPo1dMVi1IdM/edit?gid=92899346#gid=92899346)  
> [Kacky Reloaded (TM2020) Dashboard](https://docs.google.com/spreadsheets/d/1KoqfsvTzuKrHSlHEV9SBYpLdJLxni0lkM3P3NB_fOcg/edit?gid=92899346#gid=92899346)

2. Make a copy of the Google Sheet.  
`File - Make a copy`

3. Click the Share button and change access permissions to **Anyone with the link**.  
Then change the role to **Editor**.

4. Copy the part of the URL corresponding to the SHEET ID  
`https://docs.google.com/spreadsheets/d/{SHEET_ID}/edit?usp=sharing`

5. Enter the SHEET ID in the program.

6. Click the run button.

## Config
* language = `en`, `kr`
* event = `Kackiest Kacky (TMNF)`, `Kacky Reloaded (TM2020)`
* kacky_color = `positive`, `negative`, `reloaded`, `og`

## 설치
왼쪽 **[Release](https://github.com/Viun2232/kackiest-kacky-dashboard-automator/releases)** 탭에서 가장 최신 버전의 `Kacky-Dashboard-Automator.zip` 파일을 다운받고 압축 해제 하세요.

## 사용 방법
### PID 가져오기
1. Kacky 웹사이트에 접속하여 자신의 닉네임을 검색하거나 수동으로 찾습니다.  
> https://kackiestkacky.com 또는 https://kackyreloaded.com

2. 유저 프로필을 열고 해당 PID를 복사합니다.  
`https://kackiestkacky.com/hunting/editions/players.php?pid=OOOO&edition=0`
> OOOO는 당신의 PID입니다.

3. 프로그램에 PID를 입력합니다.

### SHEET_ID 가져오기
1. 프로그램에서 `대시보드 열기` 버튼을 누르거나, 아래 링크에 직접 접속합니다.  
> [Kackiest Kacky (TMNF) Dashboard](https://docs.google.com/spreadsheets/d/1G44h9PAHVSKkYwD4ek_v6WpI696QPMAJPo1dMVi1IdM/edit?gid=92899346#gid=92899346) 또는 [Kacky Reloaded (TM2020) Dashboard](https://docs.google.com/spreadsheets/d/1KoqfsvTzuKrHSlHEV9SBYpLdJLxni0lkM3P3NB_fOcg/edit?gid=92899346#gid=92899346)

2. Google 시트를 복사합니다.    
`파일 - 사본 만들기`

3. **공유** 버튼을 눌러 접근 권한을 **링크가 있는 모든 사용자**로 변경합니다.  
그다음 역할을 **편집자**로 바꿉니다.

4. URL 중 SHEET ID에 해당하는 부분을 복사합니다.  
`https://docs.google.com/spreadsheets/d/{SHEET_ID}/edit?usp=sharing`

5. 프로그램에 SHEET ID를 입력합니다.

6. 실행 버튼을 클릭합니다.

## 구성
* language = `en`, `kr`
* event = `Kackiest Kacky (TMNF)`, `Kacky Reloaded (TM2020)`
* kacky_color = `positive`, `negative`, `reloaded`, `og`
