<div align="center">

# rclone-drive

**개인용 Google Drive 백업·동기화 도구(rclone)의 OAuth 개인정보처리방침과 이용약관을 제공하는 GitHub Pages 사이트입니다.**

Google OAuth 동의 화면이 요구하는 공개 URL을 제공하기 위해 정적 HTML로 구성했습니다.

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

[사이트 열기](https://younghwan91.github.io/rclone-drive/) · [빠른 시작](#빠른-시작) · [페이지 구성](#페이지-구성) · [개인정보와 권한 철회](#개인정보와-권한-철회) · [라이선스](#라이선스)

</div>

## 빠른 시작

외부 의존성 없이 인라인 스타일만 사용하는 정적 HTML입니다. 로컬에서 바로 확인하려면 브라우저로 `index.html`을 엽니다.

```bash
# 로컬 미리 보기
python3 -m http.server 8000
```

공개 사이트는 <https://younghwan91.github.io/rclone-drive/> 에서 확인할 수 있습니다.

## 페이지 구성

| 파일 | 내용 |
|---|---|
| `index.html` | 소개 — 소유자 본인 한 사람이 자기 Google Drive를 백업·동기화하는 데 쓰는 개인용 애플리케이션이며, 제3자에게 제공하는 서비스가 아님을 안내합니다 |
| `privacy.html` | 개인정보처리방침 — 소유자 본인 계정의 파일만 다루고 제3자·분석·광고주에게 데이터를 보내지 않으며, Google API Services User Data Policy(Limited Use 포함)를 준수합니다 |
| `terms.html` | 이용약관 — 소유자 본인만 쓰는 개인용이며 보증 없이 있는 그대로 제공합니다. Google Drive 이용에는 Google의 약관이 적용됩니다 |

## 개인정보와 권한 철회

- **단독 사용**: 제3자에게 서비스를 제공하거나 데이터를 공유하지 않습니다.
- **정책 준수**: Google API Services User Data Policy(Limited Use 포함)를 따릅니다.
- **권한 철회**: 접근 권한은 Google 계정 보안 설정에서 언제든 철회할 수 있습니다.

## 라이선스

MIT — [LICENSE](LICENSE).
