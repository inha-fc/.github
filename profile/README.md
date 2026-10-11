<p>
  <img src="https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/banner.svg" width="100%" alt="인하대학교 OSS · Open Source Software — 코드를 나누고, 가능성을 더하다. 인하대학교 학생들의 아이디어가 함께 만드는 소프트웨어로 이어집니다." />
</p>

인하대학교 학생 누구나 오픈소스 프로젝트와 협업에 참여할 수 있습니다.<br />
수업, 동아리, 개인 프로젝트까지. 전공과 경험에 관계없이 동료를 찾고, 코드를 공유하고, 함께 개선해보세요.

<p>
  <a href="https://oss.inha.ac.kr"><img src="https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/homepage.svg" width="23%" alt="인하대학교 OSS 홈페이지" /></a>
  <a href="https://github.com/inha-oss?tab=repositories"><img src="https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/repositories.svg" width="23%" alt="저장소 둘러보기" /></a>
  <a href="https://github.com/inha-oss/.github/issues/new?template=collaboration.yml"><img src="https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/collaborate.svg" width="23%" alt="협업 제안하기" /></a>
  <a href="https://github.com/inha-oss/.github/issues/new?template=join.yml"><img src="https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/join.svg" width="23%" alt="조직 참여하기" /></a>
</p>

---

### 이런 일이 있을 때 함께해요

**함께할 사람이 필요할 때**<br />
수업 팀 프로젝트, 동아리 활동, 개인 프로젝트, 같이 해결하고 싶은 문제를 제안해주세요. 하고 싶은 일과 필요한 도움을 적으면 협업을 시작하기 좋습니다.

**같이 작업할 공간이 필요할 때**<br />
코드와 문서를 저장소에 모으고, 이슈에서 할 일을 나누고, Pull Request로 변경 내용을 검토하세요. 각자 가능한 시간에 작업하면서도 진행 상황을 함께 볼 수 있습니다.

**다른 경험이 필요할 때**<br />
개발뿐 아니라 기획, 디자인, 문서, 검토로도 참여할 수 있습니다. 서로 다른 전공과 경험, 관심 분야가 다른 학우의 작업에 도움이 될 수 있습니다.

관심 있는 협업 제안이 있다면 해당 이슈에 댓글로 참여 의사를 남겨주세요.

> 관심 있습니다! 화면 개발을 도울 수 있고, 주말에 참여 가능합니다. 먼저 함께할 작업이 있을까요?

역할이 정해지지 않았어도 질문부터 시작할 수 있습니다. [다른 참여 댓글 예시](https://github.com/inha-oss/.github/blob/main/docs/community-replies.md#학우의-참여-댓글)도 참고해주세요.

### 처음 오신 학우라면

[조직 참여 요청](https://github.com/inha-oss/.github/issues/new?template=join.yml)에 간단한 소개와 관심 분야를 남겨주세요. 관리자가 확인한 뒤 초대를 안내합니다. 처음부터 프로젝트가 정해져 있지 않아도 괜찮습니다.

### 작업하다 막힐 때 꺼내 보는 자료

| 자료 | 필요할 때 |
| :--- | :--- |
| [Pro Git · 한국어](https://git-scm.com/book/ko/v2) | Git 기본 개념부터 브랜치와 협업 흐름까지 차근차근 확인하기 |
| [GitHub 시작 안내](https://docs.github.com/ko/get-started/start-your-journey/git-and-github-learning-resources) | GitHub 사용법과 학습 자료 찾아보기 |
| [Pull Request 만들기](https://docs.github.com/ko/pull-requests/how-tos/create-pull-requests/creating-a-pull-request) | 내 변경 내용을 동료에게 검토 요청하기 |
| [Learn Git Branching · 한국어](https://learngitbranching.js.org/?locale=ko) | 브랜치와 커밋의 움직임을 화면으로 보며 연습하기 |

<details>
<summary><strong>자주 쓰는 Git 명령어 · 처음 설정부터 첫 Pull Request까지</strong></summary>

<br />

**처음 한 번 설정하기**

[Git을 설치](https://git-scm.com/downloads)한 뒤 자신의 이름과 이메일로 바꿔 실행하세요.

```sh
# 커밋에 기록할 작성자 정보
git config --global user.name "Hong Gildong"
git config --global user.email "honggildong@inha.edu"
```

**저장소 가져오고 작업 브랜치 만들기**

아래 주소와 폴더 이름은 실제 작업할 저장소로 바꿔주세요. 푸시 권한이 없으면 GitHub에서 저장소를 포크하고 자신의 포크 주소를 사용합니다.

```sh
git clone https://github.com/OWNER/REPOSITORY.git
cd REPOSITORY
git switch -c feature/my-work
```

**변경 확인하고 커밋하기**

```sh
# 작업 상태와 수정 내용 확인
git status
git diff

# 커밋할 파일을 지정하고 저장
git add README.md
git diff --staged
git commit -m "작업 내용 요약"

# 내 브랜치를 GitHub에 올리기
git push -u origin feature/my-work
```

`README.md`는 실제 수정한 파일 이름으로 바꾸고, 커밋 메시지는 해당 저장소의 규칙을 따라주세요. 푸시 후 GitHub에서 Pull Request를 열어 변경 내용과 확인한 결과를 공유합니다.

**동료의 변경 가져오기**

작업 내용을 먼저 커밋하고 실행하세요. 기본 브랜치 이름이 `main`이 아닌 저장소에서는 해당 이름으로 바꿔주세요.

```sh
git switch main
git pull --ff-only
git switch feature/my-work
git merge main
```

충돌이 나면 `git status`로 파일을 확인하고, 동료와 변경 내용을 맞춘 뒤 해결합니다.

**상태와 기록 빠르게 확인하기**

| 명령어 | 용도 |
| :--- | :--- |
| `git status` | 현재 브랜치와 수정 파일 확인 |
| `git diff` | 아직 스테이징하지 않은 변경 확인 |
| `git diff --staged` | 커밋에 포함할 변경 확인 |
| `git log --oneline -10` | 최근 커밋 10개 확인 |
| `git branch` | 로컬 브랜치 목록 확인 |
| `git remote -v` | 연결된 원격 저장소 주소 확인 |
| `git help 명령어` | 해당 명령어의 도움말 확인 |

</details>

<details>
<summary>참여 안내와 문의</summary>

<br />

- 조직 초대는 GitHub 알림과 이메일에서 확인해주세요.
- 학교 이메일은 [GitHub 이메일 설정](https://github.com/settings/emails)에서 추가할 수 있습니다. 기본 이메일 지정은 선택입니다.
- 참여할 저장소의 README와 기여 안내를 먼저 확인해주세요.
- 인하대학교 OSS 홈페이지는 [oss.inha.ac.kr](https://oss.inha.ac.kr)에서 방문할 수 있습니다.
- GitHub 조직 참여와 협업 관련 문의나 제안은 [이슈](https://github.com/inha-oss/.github/issues)에 남겨주세요.
- 관리자는 [답변 템플릿](https://github.com/inha-oss/.github/blob/main/docs/community-replies.md#관리자-답변-템플릿)을 참고할 수 있습니다.
- 공개 공간에는 개인정보나 공개 권한이 없는 자료를 올리지 마세요. 코드 사용 조건은 각 저장소의 `LICENSE`를 확인해주세요.

</details>
