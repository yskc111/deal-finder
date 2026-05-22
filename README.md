# 중고나라 급매 알리미 - GitHub Pages 배포 가이드

## 파일 구성
```
index.html   ← 앱 본체
manifest.json ← PWA 설치 정보
sw.js         ← 백그라운드 실행
icon-192.png  ← 앱 아이콘
icon-512.png  ← 앱 아이콘 (고해상도)
```

---

## 배포 방법 (5분)

### 1단계: GitHub 가입
https://github.com 접속 → Sign up

### 2단계: 새 저장소 생성
- 우측 상단 + → New repository
- Repository name: `jn-deal-finder` (아무 이름)
- **Public** 선택
- Create repository 클릭

### 3단계: 파일 업로드
- 저장소 페이지에서 **"uploading an existing file"** 클릭
- 이 폴더의 파일 5개를 모두 드래그앤드롭
- **Commit changes** 클릭

### 4단계: Pages 활성화
- 저장소 상단 **Settings** 탭
- 왼쪽 메뉴 **Pages**
- Source: **Deploy from a branch**
- Branch: **main** / **(root)** 선택
- **Save** 클릭

### 5단계: 앱 주소 확인 (1~2분 후)
```
https://[내깃허브아이디].github.io/jn-deal-finder/
```

---

## 안드로이드에서 설치
1. 위 주소를 **크롬**으로 열기
2. 주소창 오른쪽 또는 메뉴(⋮)에 **"앱 설치"** 배너 자동 등장
3. 설치 → 홈화면에 아이콘 생성
4. 아이콘 탭 → 앱처럼 전체화면으로 실행

---

## 사용법
1. ⚙️ 설정 → Claude API Key 입력 (필수)
2. 카카오 토큰 입력 (선택, 급매 발견 시 카톡 알림)
3. ▶ 버튼으로 시작
4. 껐다 켜도 자동 재시작됨
