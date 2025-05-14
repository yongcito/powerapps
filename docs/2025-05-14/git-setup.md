# 🧰 GitHub 및 Git 사용 기록

본 문서는 PowerApps UI 프로젝트를 위한 Git 설정, 명령어 사용 및 작업 히스토리를 정리한 문서입니다.

---

## 📦 macOS Git 환경 구축

### ✅ Homebrew 설치

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### ✅ Git 설치

```bash
eval "$(/opt/homebrew/bin/brew shellenv)"
brew install git
```

---

## 🔗 GitHub 리포지토리 클론

```bash
git clone https://github.com/yongcito/powerapps.git
cd powerapps
```

---

## 📁 폴더 이동

```bash
mkdir -p docs
mv 250514 docs/250514
```

---

## ✅ 커밋 및 푸시

```bash
git add .
git commit -m "Move 250514 folder into docs/"
git push origin main
```

> GitHub에서 토큰 인증 오류 발생 → [Personal Access Token 생성](https://github.com/settings/tokens)

---

## 📝 추가한 파일

- `docs/250514/README.md` – UI 개선안 문서
- `docs/250514/스크린샷*.png` – 작업 이미지
- `CHANGELOG.md` – 변경 이력
- `docs/git-setup.md` – 본 문서

---

## 🤖 사용한 명령어 요약

| 명령 | 설명 |
|------|------|
| `git add .` | 변경된 모든 파일 스테이징 |
| `git commit -m "메시지"` | 커밋 메시지 작성 |
| `git push origin main` | GitHub에 푸시 |
| `open -e 파일명` | 텍스트 편집기로 열기 |
| `cat 파일명` | 터미널에 파일 내용 출력 |
| `nano 파일명` | 터미널에서 직접 편집 |
