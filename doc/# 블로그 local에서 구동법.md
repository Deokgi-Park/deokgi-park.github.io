# 로컬 실행 (Windows)

## 1) Ruby + DevKit(MSYS2/GCC) 설치

`winget`으로 Ruby(DevKit 포함)를 설치합니다.

```bash
winget install -e --id RubyInstallerTeam.RubyWithDevKit.3.4 --accept-package-agreements --accept-source-agreements
```

설치 후 터미널을 완전히 닫고 새로 엽니다.

## 2) DevKit(MSYS2/GCC) 초기화

아래 명령을 `명령 프롬프트(cmd)` 또는 `PowerShell`에서 1회 실행합니다.

```bat
ridk install
```

화면에서 기본 추천 항목(MSYS2 toolchain)을 설치합니다.

## 3) 설치 확인

```bash
ruby -v
gem -v
bundle -v
gcc --version
```

## 4) 블로그 의존성 설치 및 실행

프로젝트 루트(`deokgi-park.github.io`)에서 실행:

```bash
bundle install
bundle exec jekyll serve
```

브라우저에서 `http://127.0.0.1:4000` 접속

## 5) 자주 나는 오류

- `bundle: command not found`
  - 터미널 재시작 후 다시 시도
  - 그래도 안 되면 Ruby 설치 경로(`C:\Ruby34-x64\bin`)가 PATH에 있는지 확인
- native extension 빌드 실패(ffi 등)
  - `ridk install`을 다시 실행해 MSYS2/GCC toolchain 설치 확인
