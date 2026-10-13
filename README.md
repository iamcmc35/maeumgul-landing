# 마음글독서논술 상담 랜딩페이지 MVP

목표: 최소 기능으로 `기획 → 제작 → GitHub 저장 → Vercel 배포 → 상담링크 연결`의 전체 과정을 체험합니다.

## 1. 현재 포함된 기능
- 학원 소개
- 학부모 고민 제시
- 수업방식 안내
- 프로그램 소개
- 상담 CTA
- 모바일 반응형

## 2. 배포 전 반드시 수정할 곳
`index.html`에서 아래 두 문자열을 검색해 실제 값으로 바꾸세요.

- `NAVER_BOOKING_URL` → 네이버 스마트플레이스 예약 URL
- `PHONE_NUMBER` → 상담 전화번호 (예: 0551234567)

그 외 실제 운영 내용에 맞춰 프로그램명, 대상 학년, 주소, 원장 소개 등을 수정합니다.

## 3. GitHub에 올리기 — 가장 쉬운 방법
1. GitHub에서 새 repository 생성 (예: `maeumgul-landing`)
2. `Add file` → `Upload files`
3. `index.html`, `README.md` 업로드
4. Commit

## 4. Vercel 배포
1. Vercel 로그인
2. `Add New Project`
3. GitHub의 `maeumgul-landing` repository Import
4. Framework Preset은 정적 HTML이면 기본 설정으로 진행
5. Deploy
6. 생성된 URL로 모바일/PC 확인

## 5. 이번 MVP에서 일부러 제외한 기능
- 로그인
- 학생 개인정보 저장
- DB
- 결제
- 출결관리
- AI/API 연동

먼저 상담 랜딩페이지 1개를 정상 배포한 뒤 다음 단계에서 하나씩 추가합니다.
