# ![image](https://github.com/HnueeJimin/softverse/assets/171033088/5ec6b8e3-b85a-4b55-a64c-3ed47f4aa4c0) Dev


## 시작하기(Getting started)

GitHub 설정을 위해 아래 사항을 따라주세요.
To make it easy for you to started GitHub, please follow the instructions below.

## Git 계정 설정(Setup Account for Git)
터미널에서 아래 명령어를 입력해주세요.

```
git config --global user.name "your name"
git config --global user.email "example@gmail.com"
```

## 파일 업로드(Add your files)
당신이 수정한 파일을 GitHub에 올릴 수 있습니다.
You can upload your modified file to GitHub.

```
cd existing_repo -> 만들어둔 개인 폴더로 이동
git remote add origin https://github.com/softverse-1.git -> origin 부분은 Git의 별칭 지정
git branch -M main -> Git의 기본 브랜치 이름을 main으로 변경(master로 되어 있는 경우에만, 할 필요 없음)
git push -uf origin main -> 나의 파일을 main에 업로드 (이 부분은 좀 더 수정 및 보완 예정)
```

## 파일 다운로드(Download GitHub Files)
업로드된 최신 상태의 파일을 다운받을 수 있습니다.
You can download the latest status of files uploaded to GitHub.

```
git fetch origin -> Git의 '상태'를 로컬에 다운로드 (브랜치 업데이트 x)
git pull origin main -> main 항목을 나의 로컬에 병합
```

## 개인 Branch 생성 및 전환(Making Your Branch and Changing)
본인의 브랜치를 만들어 Develop 브랜치와 사용 ※ main에 바로 업로드할 경우 협업 문제 발생
Create your Branch and use with Develop Branch ※ If you push directly to main, there will be a problem during collaboration

```
git branch <branch-name> -> 새로운 브랜치 생성
git switch <branch-name> -> 생성한 브랜치로 전환, switch main 시 메인 브랜치로 돌아옴
```