# GreenSmart Controller 공개 안내·릴리즈

Controller는 GreenSmart 현장 장치 연결과 제어 실행을 담당합니다. 이 저장소에는 승인된 Controller 설치·업데이트·복구 안내와 Controller 전용 산출물만 게시합니다.

- [GreenSmart 전체 안내](https://github.com/greenity-corp/greensmart_release)
- [Controller Releases](https://github.com/greenity-corp/green_smart-controller-releases/releases)
- 함께 사용하는 [Cloud 안내](https://github.com/greenity-corp/green_smart-cloud-releases) · [Edge 안내](https://github.com/greenity-corp/green_smart-edge-releases)

## 현재 게시 상태

2026-10-15 기준 이 GitHub 채널의 Releases는 0개입니다. 이 채널의 게시 현황이며 기존 제품 운영·설치 부재를 의미하지 않습니다. 지원 장치·프로필·버전 조합과 설치 명령은 실제 검증 후 게시합니다.

기존 고객의 설치 파일 전달은 Cloud의 **설치 및 업데이트** 메뉴를 따릅니다. 공개 안내 정비로 다운로드 권한이나 기존 Edge를 통한 장치 업데이트 경로가 변경되지는 않습니다.

## 장치·프로필·Edge 호환성

공개 릴리즈에는 실제 검증한 장치 유형·프로필과 Edge 버전 조합, 필요한 Cloud 버전 조건을 기록합니다. Controller의 표시 이름을 정비하더라도 기존 설치 경로·서명 번들의 `gateway` 식별자를 문서 변경만으로 바꾸지 않습니다.

- Controller 버전·검토한 원본 커밋·서명 번들 식별자와 공개 변경 내역
- 지원 장치·프로필·Edge 조합과 미검증·미지원 조합
- 사전 안전 조건, 적용 순서, 업데이트 중단·복구 및 되돌림 제한
- 설치 후 실제 상태 확인 방법, 알려진 제한, 체크섬과 서명·출처 검증 방법

장치 응답과 실제 상태 확인 결과를 함께 검토하고, 다운로드 성공만으로 설치·제어 성공을 판단하지 않습니다. 검증되지 않은 조합을 임의로 지원한다고 표시하지 않습니다.

## 검증과 공개 범위

태그 형식은 `controller-vMAJOR.MINOR.PATCH`, 제목은 `Controller vMAJOR.MINOR.PATCH`를 사용합니다. 이는 표기 규칙이며 현재 출고 버전을 뜻하지 않습니다.

Controller 자체 시험, Edge와의 계약·중복·만료·상태 확인 시험, 통합 회귀와 필요한 이전/새 버전 혼용 시험을 확인합니다. 실제 장치·설치·업데이트·복구 검증을 가상 환경 결과와 구분하고, 생략·미실행 항목을 명시한 뒤 출고 승인을 받습니다.

Cloud·Edge 파일은 각 전용 채널로 안내합니다. 소스 코드·상세 내부 설계·운영 설정·인증정보·고객 데이터는 공개하지 않습니다. 필요한 SBOM·출처 증거는 공개 대상을 검토한 뒤 제공합니다.
