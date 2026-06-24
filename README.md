# 1985 COFFEE Official Website

1985커피 공식 반응형 홈페이지의 1차 시안입니다.

## 실행 및 검증

```sh
bash scripts/build.sh
node scripts/validate-artifact.mjs
```

## 에셋 준비 목록

아래 파일명을 그대로 사용해 준비하면 코드 수정 없이 이미지와 영상이 적용됩니다.

| 파일 경로 | 사용 위치 | 권장 크기 | 촬영 및 선택 기준 |
| --- | --- | --- | --- |
| `assets/images/logo-main.png` | 상단 및 하단 로고 | 가로 800px 이상, PNG | 기존 1985커피 원본 로고 |
| `assets/videos/hero-main.mp4` | 첫 화면 배경 영상 | 1920 x 1080px 이상, 6~12초 루프 | 로스팅, 바리스타 작업 또는 매장 전경 영상. 자동 재생을 위해 소리 없는 MP4 권장 |
| `assets/images/hero-main.jpg` | 첫 화면 영상 포스터 및 fallback 이미지 | 2400 x 1600px 이상 | 영상 로딩 전 또는 영상 미지원 환경에서 보일 이미지. 좌측에 문구가 들어가므로 주요 피사체는 중앙 또는 우측 |
| `assets/images/service-consulting.jpg` | 개인 카페 컨설팅 | 1200 x 1500px | 도면, 상담 자료와 함께 대화하는 실제 장면 |
| `assets/images/service-beans.jpg` | 원두 납품 | 1200 x 1500px | 로스팅 원두, 로스터 또는 포장 작업을 선명하게 촬영한 사진 |
| `assets/images/service-interior.jpg` | 인테리어 디자인 | 1200 x 1500px | 직접 진행한 카페 인테리어 완공 사례 |
| `assets/images/factory.jpg` | 본사·공장 카드 | 1600 x 1100px | 로스터와 생산 공간 또는 상담 공간이 함께 보이는 사진 |
| `assets/images/store-dongtan.jpg` | 동탄점 카드 | 1600 x 1100px | 외관 1장 또는 매장 전체 분위기가 보이는 실내 |
| `assets/images/store-anjung.jpg` | 평택안중점 카드 | 1600 x 1100px | 외관 1장 또는 매장 전체 분위기가 보이는 실내 |

사진은 JPG 기준 품질 80~85%, 개별 파일 500KB 이하를 권장합니다. 히어로 영상은 가능하면 5~15MB 이하로 압축하는 편이 좋습니다. 로고는 현재 상단 헤더와 하단 푸터에 직접 표시됩니다.

현재 1차 화면에서는 위 표의 모든 에셋이 직접 사용됩니다. 파일이 아직 없어도 화면은 깨지지 않고 어두운 배경 또는 fallback 이미지로 표시됩니다.

## 확정이 필요한 정보

- 공식 상담 이메일
- 사업자명, 대표자명, 사업자등록번호 등 푸터 표기 정보
- 동탄점과 평택안중점의 지도 링크
- 인스타그램, 블로그, 유튜브 공식 주소
- 개인정보처리방침
