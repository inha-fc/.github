<p align="center">
  <img src="profile/assets/banner.svg" width="100%" alt="인하대학교 OSS · Open Source Software — 코드를 나누고, 가능성을 더하다" />
</p>

# 인하대학교 OSS · .github

인하대학교 학생들의 오픈소스 협업을 위한 **조직 소개와 참여 안내**를 관리하는 저장소입니다. OSS는 **Open Source Software**의 약자입니다.

[OSS 홈페이지](https://oss.inha.ac.kr) · [GitHub 조직](https://github.com/inha-oss) · [협업 제안하기](https://github.com/inha-oss/.github/issues/new?template=collaboration.yml) · [조직 참여하기](https://github.com/inha-oss/.github/issues/new?template=join.yml)

## 함께 시작하기

전공과 경험에 관계없이 인하대학교 학생 누구나 참여할 수 있습니다. 수업 팀 프로젝트, 동아리 활동, 개인 프로젝트에서 함께할 동료를 찾거나 관심 있는 작업에 힘을 보태주세요.

- **협업을 제안하려면**: 협업 제안 양식에 함께할 일과 필요한 도움을 적어주세요.
- **조직에 참여하려면**: 참여 요청 양식에 간단한 소개를 남겨주세요. 관리자가 확인한 뒤 초대를 안내합니다.
- **다른 학우의 제안에 참여하려면**: 해당 이슈에 질문이나 도울 수 있는 부분을 댓글로 남겨주세요. [댓글 예시](docs/community-replies.md#학우의-참여-댓글)를 참고할 수 있습니다.
- **프로젝트에 기여하려면**: 해당 저장소의 README와 기여 안내를 확인해주세요. 개발뿐 아니라 기획, 디자인, 문서, 검토로도 함께할 수 있습니다.

Git 기본 명령어와 참고 자료는 [조직 프로필의 Git 안내](profile/README.md#작업하다-막힐-때-꺼내-보는-자료)에 모아두었습니다.

## 이 저장소의 구성

| 파일 | 역할 |
| :--- | :--- |
| [`README.md`](README.md) | 이 저장소의 소개와 관리 안내 |
| [`profile/README.md`](profile/README.md) | GitHub 조직 첫 화면에 표시되는 프로필 |
| [`profile/assets/`](profile/assets/) | 프로필 배너와 SVG 링크 버튼 |
| [`.github/ISSUE_TEMPLATE/collaboration.yml`](.github/ISSUE_TEMPLATE/collaboration.yml) | 학우 협업 제안 입력 양식 |
| [`.github/ISSUE_TEMPLATE/join.yml`](.github/ISSUE_TEMPLATE/join.yml) | 조직 참여 요청 입력 양식 |
| [`docs/community-replies.md`](docs/community-replies.md) | 학우 참여 댓글과 관리자 답변 예시 |

실제 프로젝트의 코드와 작업은 각 프로젝트 저장소에서 관리합니다.

## 소개와 안내를 개선하려면

오타, 불편한 안내, 끊어진 링크를 발견하면 [이슈](https://github.com/inha-oss/.github/issues)에 알려주세요. 직접 수정할 때는 브랜치에서 작업한 뒤 Pull Request를 열어 변경 내용과 확인한 결과를 적어주세요.

- 조직 첫 화면의 문구는 `profile/README.md`, 배너와 버튼은 `profile/assets/`에서 수정합니다.
- 프로필 이미지의 공개 주소는 `https://raw.githubusercontent.com/inha-oss/.github/main/profile/assets/파일명.svg` 형식을 사용합니다.
- 참여 양식은 `.github/ISSUE_TEMPLATE/`에서 수정합니다. 프로필 버튼의 `template` 값과 파일 이름이 일치해야 합니다.
- SVG를 바꿨다면 글자가 잘리지 않는지, 링크를 바꿨다면 원하는 페이지나 양식이 열리는지 확인해주세요.
- 이슈 양식은 YAML 문법, 필수 항목, 예시 문구와 실제 작성 화면을 확인해주세요. 관리자 답변 예시는 자동 등록되지 않으므로 상황에 맞게 복사해 사용합니다.

### 조직 공통 템플릿의 적용 범위

이 저장소는 이름이 `.github`인 공개 조직 저장소입니다. 여기에 둔 이슈 템플릿은 **자체 이슈 템플릿이나 설정이 없는 조직 내 다른 저장소에도 기본 양식으로 표시될 수 있습니다**. 프로젝트별 양식이 필요하면 해당 저장소의 `.github/ISSUE_TEMPLATE/`에 구성해주세요. [GitHub의 기본 커뮤니티 파일 안내](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)에서 적용 방식을 확인할 수 있습니다.

## 공개 정보와 사용 조건

이슈와 문서는 공개됩니다. 학번, 개인 연락처, 인증 정보, 공개 권한이 없는 자료를 올리지 마세요. 각 프로젝트의 코드 사용 조건은 해당 저장소의 `LICENSE`와 안내 문서를 확인해주세요.
