# 🔥 Git & GitHub Team Project 🔥

### 📝 프로젝트 소개
GitHub를 활용하여 협업 환경을 구성하는 프로젝트입니다.

---
### 👷 구성원 및 역할 분담
👽️ 혜진 - MD, issue

✨ 지혜 - commit convention

🧐 승우 - project, template

---

### 요구사항
* OS: Windows 11 Home(또는 Windows 10 Home)
* GitHub repo

---
### 주요 구성 내용
**1. commit convention Template**
> commit convention 적용 방법
1. '.gitmessage.txt' 파일 다운로드
2. 아래 명령어 실행하여 commit convention 적용
```
$ git config --global commit.template .gitmessage.txt
```
> commit convention 적용 화면
```
$ git commit
```
![Commit Convention](/commit_convention.PNG)


**2. Project Template**
> Project Template 적용 방법
* GitHub > Projects > [New project] > Planning 선택

> Project 화면
![Project](/project_template.PNG)


**3. Issue Template**
> issue Template 적용 방법
* GitHub 이용(GUI)
1. GitHub > Settings > Features - Issues > [Set up templates] 버튼 클릭
2. [Add template: select] > Custome template
3. [Preview and edit] > 연필 모양 아이콘 > 이슈 템플릿 작성
![Issue_template](/issue_template_settings.png)

> issue Template 적용 화면
![Issue](/issue_template.PNG)

---
### 기타
* git push conflict 관련 내용
Ref: 팀프로젝트.md