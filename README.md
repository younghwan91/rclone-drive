# rclone-drive

개인용 Google Drive 백업·동기화 도구(rclone)가 쓰는 OAuth 클라이언트의 **개인정보처리방침·이용약관 페이지**를 올려 두는 GitHub Pages 사이트다. Google OAuth 동의 화면이 공개 URL 의 방침·약관 페이지를 요구해서 만들었다. 코드는 없다.

사이트: <https://younghwan91.github.io/rclone-drive/>

| 파일 | 내용 |
|---|---|
| `index.html` | 소개 — 소유자 본인 한 사람이 자기 Google Drive 를 백업·동기화하는 데 쓰는 개인용 애플리케이션이며, 제3자에게 제공하는 서비스가 아니다 |
| `privacy.html` | 개인정보처리방침 — 소유자 본인 계정의 파일만 다루고, 제3자·분석 서비스·광고주에게 데이터를 보내지 않으며, Google API Services User Data Policy(Limited Use 포함)를 따른다. 접근 권한은 Google 계정 보안 설정에서 언제든 철회할 수 있다 |
| `terms.html` | 이용약관 — 소유자 본인만 쓰는 개인용이며 보증 없이 있는 그대로 제공한다. Google Drive 이용에는 Google 의 약관이 적용된다 |

세 파일은 외부 의존성 없이 스타일을 인라인으로 가진 정적 HTML 이다. 로컬에서 보려면 브라우저로 `index.html` 을 열면 된다.

## 라이선스

MIT — [LICENSE](LICENSE).
