# 👋 이 그룹에 참여하게 된 걸 진심으로 환영합니다.

## GitHub 조직에 등록하는 방법

GitHub 조직에 참여를 원하시면 해당 저장소의 이슈를 작성하여 게시글을 작성하시면 됩니다. 관리자가 확인 후 멤버 권한을 부여해드릴 것입니다. 이 과정을 따르세요:

1. [등록 요청하기](https://github.com/inha-fc/.github/issues)을 클릭해주세요
2. 상단 탭에서 Issues를 클릭하세요.
3. 오른쪽 상단에 있는 초록색 New issue 버튼을 클릭하세요.
4. Title과 Leave a comment 섹션에 요청 내용을 작성하세요. 예를 들어, 조직 참여를 원한다는 내용을 작성해주세요
5. 작성이 완료되면 하단의 Submit new issue 버튼을 클릭하여 이슈를 생성하세요.
6. 관리자가 해당 이슈를 확인한 후, 멤버 권한을 부여하게 됩니다. 이메일이나 GitHub에서 알림을 확인하세요.
7. 이제 GitHub 조직에 참여하실 수 있습니다. 조직의 멤버로 등록되면 해당 조직의 프로젝트에 기여하거나, 토론에 참여하실 수 있습니다.

## Github에 학교 이메일 등록하기

Github 계정에 이메일을 등록하려면 다음 단계를 따르세요:

1. Github에 로그인한 후 상단 오른쪽에 있는 프로필 아이콘을 클릭하고 Settings를 선택하세요.
2. 왼쪽 사이드바에서 Emails를 클릭하세요.
3. Add email address 섹션에 인하대학교 이메일 주소(예: honggildong@inha.edu)를 입력한 후 Add 버튼을 클릭하세요.
4. 이메일 인증 메일이 인하대학교 이메일로 발송됩니다. 이메일을 확인하고, 인증 메일에 있는 링크를 클릭해 이메일 주소를 인증하세요.
5. Github Emails 설정 페이지로 돌아와서, 인하대학교 이메일 주소 옆에 있는 Set as primary 버튼을 클릭하여 기본 이메일로 설정하세요. 이렇게 하면 Github에서 사용되는 모든 통신에 해당 이메일이 사용됩니다. (필수 아님)
6. 이제 인하대학교 이메일 주소가 Github 계정에 등록되었습니다.

## Git 사용자 정보 설정하기: 이름과 이메일 변경 방법

Git [공식홈페이지](https://git-scm.com/downloads)에서 Git 설치 후 맥OS(macOS)와 리눅스(Linux)에서는 Terminal(터미널)을 열고 Windows(윈도우)의 경우 Powershell(파워셀)을 실행해주세요 그리고 이 과정을 따르세요:

1. 홍길동으로 이름을 설정하기
``` sh
$ git config --global user.name "Hong Gildong"
```

2. 홍길동으로 이메일 주소를 설정하기
``` sh
$ git congig --global user.email "honggildong@inha.edu"
```

3. 정보가 올바르게 입력되었는지 확인하기
``` sh
$ git config --list | grep -E 'name|email'
```

## 프로젝트 기여 방법

프로젝트에 기여하려면 다음 단계를 따르세요.

1. 기여하려는 저장소를 포크하세요.

2. 로컬에 저장소를 복제하세요.
``` sh
$ git clone [기여하려는 저장소 주소]
```

3. 새로운 브랜치를 만드세요.

``` sh
$ git checkout -b my-new-feature
```

4. 변경 사항을 커밋하세요.
``` sh
$ git commit -am "Add some feature"
```

5. 브랜치를 원격 저장소에 푸시하세요.
``` sh
$ git push origin my-new-feature
```

6. 원본 저장소에 풀 리퀘스트를 생성하세요.

원하는 프로젝트에 기여하는 방법에 대한 자세한 정보는 해당 프로젝트의 `CONTRIBUTING.md` 파일을 참조하세요.

## 연락처

문의사항이나 건의사항이 있으시면 [이슈](https://github.com/inha-fc/.github/issues) 등록을 통해 요청해주세요

## 라이선스

이 조직에서 제공되는 코드들은 기본적으로 `MIT` 라이선스 기반을 따르고 있습니다. 다만 일부 프로젝트의 경우 제약이 있을 수 있습니다. 자세한 정보는 각 프로젝트 저장소의 [LICENSE](/LICENSE) 파일을 참조하세요.