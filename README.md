# Waruru_POLICY

와르르 서비스의 이용약관 및 개인정보 처리방침을 제공하는 정적 웹사이트입니다.

## 구조

```text
Waruru_POLICY/
├── index.html
├── terms/
│   └── index.html
├── privacy/
│   └── index.html
├── assets/
│   └── policy.css
├── vercel.json
└── README.md
```

## 로컬 실행

별도 빌드 과정이 없습니다.

```bash
python3 -m http.server 3000
```

실행 후:

- http://localhost:3000/terms/
- http://localhost:3000/privacy/

## Vercel 배포

Vercel에서 해당 Git 저장소를 연결하고 Framework Preset을 `Other`로 선택하면 됩니다.
빌드 명령어는 필요하지 않습니다.

배포 후 앱에서 다음 URL을 WebView로 열어 사용합니다.

```text
https://<your-domain>/terms/
https://<your-domain>/privacy/
```

## 출시 전 수정할 항목

- 시행일
- `[회사명]`
- 대표자
- 사업자등록번호
- 주소
- 실제 앱 권한 및 개인정보 처리 현황과 문서 내용의 일치 여부
