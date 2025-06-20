# 🍎 iClone: Apple 페이지 만들기

## 📚 목차

1. [프로젝트 소개](#프로젝트-소개)
2. [기술 스택](#기술-스택)
3. [프로젝트 진행](#프로젝트-진행)
4. [개발 팀원 소개](#개발-팀원-소개)
5. [회고](#회고)

---

## 1. 📌 프로젝트 소개

### 📝 한줄 소개

HTML과 CSS를 활용해 Apple 홈페이지를 클론 구현한 프로젝트입니다.

### 🗂️ 프로젝트명

**iClone**

### 🗓️ 개발 기간

2025.05.27 \~ 2025.05.30

### 🎯 기획 배경

KDT 훈련생으로서 Git과 GitHub를 통해 협업하며, HTML과 CSS만으로도 실전 프로젝트를 수행해보고자 기획했습니다.

#### 🔎 배경

* 강사님을 따라 코드를 작성하는 방식으로 학습했기 때문에, 스스로 구현할 수 있는지를 점검해보고 싶었습니다.
* Git을 배우고 나서 HTML과 CSS를 복습할 시간이 부족해, 감을 되찾을 필요가 있었습니다.
* Git을 활용한 협업 경험이 거의 없어, 실제 프로젝트에 적용해보고 싶었습니다.

#### ✅ 기대 효과

* Git을 통한 작업 이력 관리 및 브랜치 전략 실습
* GitHub Issue 및 Pull Request 작성, 코드 리뷰 경험
* 실전 협업을 통해 팀 프로젝트 감각 익히기

### 💻 구현 화면

* 메인 페이지
* iPhone 상세 페이지
* 로그인 페이지

---

## 2. 🛠️ 기술 스택

### 💻 개발 환경

* **FrontEnd**: HTML5, CSS
* **협업 툴**: Git, GitHub

---

## 3. ⚙️ 프로젝트 진행

### 🧩 작업 방식

* 각자 맡은 페이지의 HTML/CSS를 개발
* 공통 요소(헤더, 푸터 등)는 시간 여유가 있는 팀원이 제작 후 공유
* 작업 완료 후 GitHub를 통한 병합(Merge)

### 🌿 Git 브랜치 전략

* Git Flow와 유사한 방식 채택
* 규모가 작아 organization을 활용한 간단한 협업 구성
* 팀장 주도로 Pull Request 및 Merge 관리

**브랜치 구조**

* `main`: 배포 및 최종본
* `feat/*`: 기능 개발 브랜치

**커밋 메시지 예시**

* `feat: 홈페이지 메인 구현 완료`
* `fix: 박스 간격 수정`

### 🔁 개발 플로우 예시

```bash
# 브랜치 생성 및 이동
git branch feat/main-page/top-section
git switch feat/main-page/top-section

# 작업 후 커밋
git add 파일명
git commit -m "feat: 메인 상단 구현"

# 원격 저장소로 push
git push origin feat/main-page/top-section

# Pull Request 요청 → Merge 후 정리
git switch develop
git pull origin develop
git branch -d feat/main-page/top-section
git push origin --delete feat/main-page/top-section
```

---

## 4. 👥 개발 팀원 소개

| 이름      | 역할                                   |
| ------- | ------------------------------------ |
| **강관주** | 팀장 / GitHub 관리, 코드 리뷰, iPhone 페이지 개발, 공통 헤더 제작 |
| **송민재** | 홈페이지 공통 푸터의 html, css 제작                             |
| **김다영** | 로그인 페이지 개발                                              |

---

## 5. 💬 회고

---

### 👤 강관주

이번 프로젝트는 Git을 활용해 처음으로 팀 프로젝트를 진행한 경험이었고, 그만큼 배운 점도 많았습니다.

처음에는 Git에 익숙하지 않아 팀장으로서 확인해야 할 여러 사항에 시간을 많이 소모했지만, Git과 GitHub에 많은 시간을 투자한 덕분에 다음 프로젝트에서는 훨씬 수월하게 협업할 수 있을 것이라 기대됩니다.

프로젝트가 총 4일간 짧게 진행되다 보니, 시작 단계에서 서로 상의하고 정해야 할 부분들을 미처 정하지 못해, 중간중간 조율하며 프로젝트를 진행해야 했습니다.  
만약 작업 흐름을 사전에 합의하고, PR과 이슈 템플릿을 준비하고, 브랜치 네이밍과 커밋 메시지 스타일을 통일했더라면 더 원활한 협업이 가능했을 거라 생각합니다.

또한 HTML, CSS 기반 프로젝트였기에 폴더 구조, 파일 및 클래스 이름, 글꼴 등 UI 측면에서도 일관성을 더 신경 썼다면 더 완성도 있는 결과물이 나왔을 것 같습니다.

개인적으로는 홈페이지 화면 구성에 너무 집중하다 보니 내가 직접 정하고 진행할 수 있는 영역에서도 시간을 많이 소비한 점이 아쉬웠습니다.  
하지만 결과물을 내기 위해 작업 단계를 쪼개어 하나씩 진행했던 점이 결국 일관성 있는 결과로 이어져 뿌듯했습니다.

무엇보다도, 함께 열심히 해준 팀원들 덕분에 좋은 결과물을 만들어낼 수 있었습니다.  
서로의 부족한 부분을 채워가며 협력했던 과정 자체가 값진 경험이었고, 이 경험을 바탕으로 다음 팀 프로젝트는 더 잘할 수 있을 거란 자신이 생겼습니다.

---

### 👤 송민재

Git을 여러 명이서 사용해보니 확실히 더 어려웠습니다.  
처음으로 제대로 협업을 하면서 여러 실수도 했지만, 팀 안에서 주제와 규칙을 정하고 하나의 목표를 위해 협력하는 것이 즐거웠습니다.  
특히 처음인데도 GitHub 관리를 잘해준 팀장 형에게 감사했습니다.

**실수한 점**
- main 브랜치에서 직접 push함
- 불필요한 브랜치 생성, 브랜치 관리 부실
- git pull 후 머지 시 충돌 발생
- 다른 사람이 작업한 파일을 건드림

**개선점**
- 브랜치 이름을 명확하게 짓고 신중히 만들기
- 다른 사람이 작업한 파일은 최대한 건드리지 않기
- 주석을 더 꼼꼼히 작성하기

**좋았던 점**
- Git 사용법과 CSS 관련 명령어를 더 잘 알게 됨
- GitHub를 통해 협업(push, pull, review 등)을 경험함
- HTML 구조나 CSS 적용 방식에 대해 정리할 수 있었음

---

### 👤 김다영

처음으로 팀 단위 협업 프로젝트를 하면서 긴장도 되고 막막했지만,  
팀장님께서 전체 구조와 흐름을 먼저 잘 잡아주신 덕분에 훨씬 수월하게 작업할 수 있었습니다.

또, 모두 서로 도와주려는 분위기 덕분에 부담 없이 즐겁게 참여할 수 있었습니다.  
Git이나 PR 흐름 등도 실무처럼 경험할 수 있어서 정말 유익한 시간이었습니다.

