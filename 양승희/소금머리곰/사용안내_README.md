# 곰 캐릭터 공식 레퍼런스 패키지 (10종)

## 제작 방식
이 ZIP의 PNG 이미지는 **이전에 확정한 갈색·회색 혼합 머리 캐릭터 시트**에서 필요한 영역을 손실 없는 PNG로 분리한 것입니다. 얼굴이나 옷을 새로 그리지 않았으므로, 개별 생성 시 생길 수 있는 외형 변형을 최소화했습니다.

## 공식 마스터
- `PNG_레퍼런스/00_MASTER_얼굴_정면.png`를 **최우선 얼굴 기준**으로 사용합니다.
- 새 장면 제작에는 마스터 1장 + 필요한 각도/표정 보조 1~2장만 추가하는 것을 우선 권장합니다. 도구에 따라 허용되는 수는 다릅니다.
- `01_얼굴_45도.png`, `02_얼굴_측면.png`은 각도 참조용입니다.
- `05~08_전신`은 신체 비율 확인용입니다. 옷, 배낭 및 소품은 자유롭게 변경 가능합니다.
- `09_동작_자전거.png`은 포즈 샘플이며 자전거를 계속 등장시킬 필요는 없습니다.

## 캐릭터 정체성의 고정 요소
- 곰 형태의 따뜻한 갈색 털, 둥근 귀
- 동일한 얼굴형·주둥이·코·눈 배치
- 둥근 안경
- 쓸어넘긴 짙은 갈색 머리 + 은회색 가닥(소금후추 머리)
- 친근하고 활기찬 중장년 인상
- 기존 3D 애니메이션의 부드러운 질감

## 변경 가능한 요소
복장, 배낭, 안경 이외의 액세서리, 자전거와 각종 소품, 동작, 배경, 시간대, 촬영 구도, 감정과 표정. 원래 안경은 얼굴 정체성 요소이므로 변경하지 않는 것을 권장합니다.

## 참조 조합 예시
- 대화 장면: 00_MASTER + 03_표정_웃음
- 강의 장면: 00_MASTER + 01_얼굴_45도 + 04_표정_생각
- 걷는 장면: 00_MASTER + 02_얼굴_측면 + 08_전신_측면
- 자전거 장면: 00_MASTER + 09_동작_자전거

## 간단한 공통 영어 지시문
Use the attached master face reference as the absolute source of character identity. Preserve the same face shape, eye placement, muzzle, ears, round glasses, and swept-back dark ash-brown hair with subtle silver streaks. Maintain the same soft stylized 3D animated-film appearance. Clothing, props, pose, background, and activity may change freely. Do not redesign the face or introduce a different bear.

## 주의사항
- 원본 시트에는 실제 후면 전신이 없습니다. 후면 이미지를 새로 만들어 넣지 않았습니다.
- `06`과 `07`은 반대 방향이 아니라 비슷한 방향의 3/4 컷입니다. 잘못된 각도 표기를 피했습니다.
- 이 파일들은 원본 이미지의 픽셀 크기를 그대로 사용합니다. 인위적인 업스케일은 포함되지 않았습니다.
- 여러 참조 이미지를 사용해도 생성형 AI의 얼굴 일관성이 100% 보장되지는 않습니다. 결과를 00_MASTER 기준으로 검수하세요.
