# 🎬 AI 브랜드 광고 스토리보드 기획 문서

---

## ⚠️ 에셋 출처 선언

> 본 프로젝트는 **직접 촬영 소재 및 유료 스톡 이미지/영상을 일체 사용하지 않습니다.**  
> 모든 시각·청각 에셋은 아래 명시된 AI 생성 도구를 통해 제작되었습니다.

| 에셋 유형 | 출처 | 직접촬영 여부 | 유료스톡 여부 |
|-----------|------|--------------|--------------|
| 이미지 | Bing Image Creator (AI 생성) | ❌ 없음 | ❌ 없음 |
| 영상 | Runway Gen-4 Turbo (AI 생성) | ❌ 없음 | ❌ 없음 |
| BGM | Suno (AI 생성) | ❌ 없음 | ❌ 없음 |
| 나레이션 | Vrew AI (AI 생성) | ❌ 없음 | ❌ 없음 |

---

## 1. 브랜드 아이덴티티

| 항목 | 내용 |
|------|------|
| **브랜드명** | MORN |
| **가상/실제 여부** | 가상 |
| **타겟** | 25~35세 도시 직장인 |
| **톤앤매너** | 시네마틱, 절제된 감성, 현실적 공감 |
| **USP** | "하루의 첫 감각을 설계한다." |
| **브랜드 컬러/비주얼 키워드** | 콜드 블루 새벽, 고요한 침실, 도시 스카이라인, 김이 오르는 커피잔 |

---

## 2. 캠페인 목표 & 핵심 메시지

| 항목 | 내용 |
|------|------|
| **광고 목적** | 브랜드 인지 |
| **타겟 행동 목표** | 브랜드명, 슬로건 기억 + 브랜드 감성 공감 |
| **핵심 메시지 (한 문장)** | "매일 새벽, 그래도 일어나는 사람들에게." |
| **광고 전체 톤** | 현실적 피로감 -> 조용한 위로 -> 담담한 각오 |

---

## 3. 사용 도구

### 도구 선정 기준
> 품질 > 속도 > 비용 순으로 우선순위를 두고 선정

| 카테고리 | 메인 도구 | 대체 도구 | 사용 목적 | 선정 근거 |
|----------|-----------|-----------|-----------|-----------|
| 이미지 생성 (T2I) | Bing Image Creator | Midjourney | 씬별 키비주얼 생성 | 무료 사용 가능, 빠른 생성 속도, 실사 품질 우수 |
| 비디오 변환 (I2V) | Runway Gen-4 Turbo | Kling AI | 이미지 → 모션 영상 변환 | 세밀한 모션 제어 가능, 시네마틱 품질 우수 |
| BGM 생성 | Suno | Udio | 배경음악 생성 | 장르·무드 키워드 기반 생성, 무료 플랜 제공 |
| 나레이션 | Vrew AI | ElevenLabs | 나레이션 음성 생성 | 한국어 지원 우수, 무료 사용 가능 |
| 통합 편집 | CapCut | Adobe Premiere Pro | 컷편집 / 자막 / BGM 합성 | 직관적 UI, 무료 사용 가능 |

### T2I vs I2V 비교

| 구분 | T2I (Text to Image) | I2V (Image to Video) |
|------|--------------------|--------------------|
| 역할 | 텍스트 프롬프트 → 정지 이미지 생성 | 정지 이미지 → 모션 영상 변환 |
| 본 프로젝트 사용 도구 | Bing Image Creator | Runway Gen-4 Turbo |
| 선택 근거 | 콜드 블루 무드의 시네마틱 키비주얼을 빠르게 확보 | 생성된 이미지를 기반으로 일관된 무드의 영상 확보 |

### 대체 도구 품질·속도·비용 비교

| 도구 | 품질 | 속도 | 비용 |
|------|------|------|------|
| Bing Image Creator | ★★★★☆ | 빠름 | 무료 |
| Midjourney | ★★★★★ | 보통 | 유료 ($10/월~) |
| Runway Gen-4 Turbo | ★★★★★ | 보통 | 부분 유료 |
| Kling AI | ★★★★☆ | 빠름 | 부분 유료 |

> 대체 도구(Midjourney, Kling AI)는 품질은 높으나 비용이 발생하므로,  
> 메인 도구 크레딧 소진 시 우선 검토 대상으로 설정함

---

## 🔄 제작 프로세스

### 단계별 절차 및 산출물

| 단계 | 절차 | 산출물 | 체크포인트 |
|------|------|--------|-----------|
| **1. 기획** | 브랜드 정의 → 핵심 메시지 확정 → 씬 구성 → 프롬프트 초안 작성 | `storyboard.md` | 씬 수·길이·메시지 확정 여부 |
| **2. 생성** | 이미지 생성 → 영상 변환 → BGM 생성 → 나레이션 생성 | 씬별 이미지/영상/오디오 파일 | 각 씬 무드·색감·구도 일치 여부 |
| **3. 검수** | 씬별 품질 확인 → 편집 합성 → 최종 출력 | `Morn_AD.mp4` | 해상도·코덱·색감·자막 최종 확인 |

### 검수 체크리스트

- [ ] 직접촬영·유료스톡 미사용 확인
- [ ] 전 씬 콜드 블루 톤 일관성 확인
- [ ] 해상도 1920×1080 / 60fps 확인
- [ ] 비디오 코덱 H.264 / 오디오 코덱 AAC 확인
- [ ] MORN 로고 씬3 3초 시점 등장 확인
- [ ] 자막 가독성 확인

---

## 🔁 생성 시도 규칙

### 시도 횟수 상한
| 에셋 유형 | 메인 도구 최대 시도 | 대체 도구 전환 조건 |
|-----------|-------------------|-------------------|
| 이미지 | 5회 | 5회 내 원하는 결과 미달 시 |
| 영상 | 3회 | 3회 내 원하는 결과 미달 시 |
| BGM | 3회 | 3회 내 원하는 결과 미달 시 |
| 나레이션 | 3회 | 3회 내 원하는 결과 미달 시 |

### 대체 도구 전환 우선순위
| 순위 | 상황 | 대응 |
|------|------|------|
| 1순위 | 메인 도구 시도 횟수 초과 | 대체 도구로 전환 |
| 2순위 | 메인 도구 크레딧 소진 | 대체 도구로 전환 |
| 3순위 | 메인 도구 서비스 장애 | 대체 도구로 즉시 전환 |

| 카테고리 | 메인 도구 | 대체 도구 |
|----------|-----------|-----------|
| 이미지 | Bing Image Creator | Midjourney |
| 영상 | Runway Gen-4 Turbo | Kling AI |
| BGM | Suno | Udio |
| 나레이션 | Vrew AI | ElevenLabs |

---

## 📐 에셋 표준 규격

| 에셋 유형 | 해상도 | 비율 | 색공간 | 비고 |
|-----------|--------|------|--------|------|
| 이미지 (키비주얼) | 1920×1080 | 16:9 | sRGB | JPG/PNG |
| 영상 | 1920×1080 | 16:9 | sRGB | MP4, H.264 |
| BGM | - | - | - | MP3, 44.1kHz |
| 나레이션 | - | - | - | WAV, 44.1kHz |

---

## 🖥 해상도 & 색감 보정 절차

### 도구별 출력 해상도 및 보정 전략
| 도구 | 기본 출력 해상도 | 목표 해상도 | 처리 방법 |
|------|----------------|------------|-----------|
| Bing Image Creator | 1024×1024 | 1920×1080 | CapCut에서 16:9 크롭 후 업스케일 |
| Runway Gen-4 Turbo | 1280×768 | 1920×1080 | CapCut에서 업스케일 리사이즈 |
| Suno / Vrew AI | 오디오 전용 | - | 별도 처리 불필요 |

### 색감 보정 절차
| 순서 | 항목 | 방법 |
|------|------|------|
| 1 | 색온도 통일 | CapCut 색보정 필터 — 쿨톤(블루) 방향으로 조정 |
| 2 | 밝기 통일 | 전체 씬 노출값 동일하게 맞춤 |
| 3 | LUT 적용 | 시네마틱 콜드 LUT 적용으로 씬 간 색감 일관성 확보 |
| 4 | 최종 확인 | 씬 1→2→3 연속 재생 시 색감 튀는 구간 없는지 검수 |

> ✅ 업스케일 시 화질 열화 최소화를 위해 CapCut 고화질 출력 옵션 사용

---

## 📁 파일명 규칙

### 네이밍 컨벤션
scene[씬번호]_[에셋유형]_v[버전].확장자
| 예시 파일명 | 설명 |
|------------|------|
| `scene01_keyvisual_v1.jpg` | 씬1 키비주얼 최초 생성본 |
| `scene01_keyvisual_v2.jpg` | 씬1 키비주얼 수정본 |
| `scene01_video_v1.mp4` | 씬1 영상 최초 생성본 |
| `scene01_bgm_v1.mp3` | 씬1 BGM 최초 생성본 |

### 재사용 가이드
> - 씬별 에셋은 독립 모듈로 관리하여 씬 순서 변경 시 개별 교체 가능
> - v1은 원본 보존, 수정 시 반드시 버전 번호 올려서 저장

---

## 4. 씬 구성 (Scene Breakdown)

---

### 🎬 씬 1

| 필드 | 내용 |
|------|------|
| **씬 번호** | 1 |
| **씬 길이** | 3초 |
| **목표 메시지** | 반복되는 일상에 지친 직장인의 새벽, 하루를 시작하기 전 공허한 순간 |

**화면 구성**
- 구도: 미디엄샷 (측면 프로필)
- 피사체: 침대에 기대앉아 창밖을 바라보는 남성 직장인
- 배경: 새벽녘 도시 스카이라인이 보이는 어두운 침실
- 텍스트 유무: 없음

**내레이션 / 화면 카피**
> 없음

**사용 도구 & 목적**
| 카테고리 | 도구명 | 사용 목적 |
|----------|--------|-----------|
| 이미지 | Bing Image Creator | 새벽 침실 키비주얼 생성 |
| 비디오 | Runway Gen-4 Turbo | 콜드 블루 무드의 시네마틱 영상 확보 |
| 오디오 | Suno | 잔잔하고 공허한 새벽 무드 BGM 생성 |

**입력 프롬프트 (원문)**
- 이미지 생성 :
COMPLETELY DARK ROOM,ZERO artificial lighting,
NO lamps,NO ceiling lights,NO ambient light,
Young man on LARGE bed,leaning against headboard,
eyes and face turned toward window,
gaze fixed on window,side profile,
gray t-shirt,shorts,knees bent,
LARGE fluffy blanket,heavy volume and folds,
short hair,
ONLY cold blue light from window,
large window fills frame,city skyline,pre-dawn,
cinematic,ultra-realistic,no text,no logo

- 비디오 생성 :
A young Asian man sitting on a bed, leaning against the headboard,
slowly turning his head to the left toward the window.
Head turn is extremely slow and subtle, barely noticeable motion.
Side profile gradually shifting, eyes gazing toward the city outside.
Gray t-shirt, knees bent, large fluffy blanket around him.

Room is completely dark, zero artificial lighting.
Only cold blue light coming through the large window.

Through the large window in the background:
- City lights flickering on and off randomly across buildings
- Cars moving slowly and silently along the streets below
- Distant buildings with subtle light changes
- City feels alive but quiet, pre-dawn atmosphere

Camera stays completely still, no camera movement.
Only the man's head and the city outside are moving.
Extremely slow motion feel, melancholic and quiet mood.
Cold blue tones only, cinematic, 35mm film style.

- 배경음 생성 :
  Genre: Ambient/Cinematic
Mood: Calm, Bittersweet, Determined
Instruments: Minimal piano, subtle strings, soft electronic pads
Tempo: Slow (60-70 BPM)
Vibe: Early morning, quiet struggle mixed with resolve, 
      cold atmosphere with subtle melancholy
Duration: 30 seconds

Style: Atmospheric, introspective, gently melancholic but hopeful
✅ Add: Subtle sadness, tender emotion
✅ Keep: Quiet strength, empowering feeling


**출력 결과 요약**
> 새벽 도시를 바라보는 남성의 측면 프로필 — 콜드 블루 무드의 시네마틱 키비주얼 및 모션 영상 확보, 공허하고 잔잔한 새벽 BGM 생성

**생성 결과 파일명**
- 이미지: `scene01_keyvisual_v1.jpg`
- 비디오: `scene01_video_v1.mp4`
- 오디오: `scene01_bgm_v1.mp3`

---

### 🎬 씬 2

| 필드 | 내용 |
|------|------|
| **씬 번호** | 2 |
| **씬 길이** | 2초 |
| **목표 메시지** | 말 없이 커피를 준비하는 손, 하루를 버티기 위한 작은 의식 |

**화면 구성**
- 구도: 익스트림 클로즈업 (손 중심)
- 피사체: 커피를 따르는 손, 피어오르는 김
- 배경: 새벽 도시 스카이라인이 보이는 대형 창문
- 텍스트 유무: 없음

**내레이션 / 화면 카피**
> 없음

**사용 도구 & 목적**
| 카테고리 | 도구명 | 사용 목적 |
|----------|--------|-----------|
| 이미지 | Bing Image Creator | 커피를 따르는 손 클로즈업 키비주얼 생성 |
| 비디오 | Runway Gen-4 Turbo | 김이 피어오르는 시네마틱 영상 확보 |

**입력 프롬프트 (원문)**
- 이미지 생성 : 
Extreme close-up of hands pouring hot coffee into ceramic cup, 
steam rising slowly. Person standing, silhouette only. 
Large window in background showing pre-dawn city skyline, 
dark sky, city lights still on. Room remains dark, 
cold blue tones throughout, no warm lighting. 
Same cinematic cold blue mood as previous scene, 
shallow depth of field, 35mm film style.


- 비디오 생성 :
Extreme close-up of Asian hands slowly tilting a coffee pot, 
pouring hot coffee into a white ceramic cup.
Steam rising naturally and continuously from the cup, 
drifting upward in soft wisps.

In the background through the large window:
- City lights flickering on and off randomly
- Cars moving slowly along the streets below
- City alive with subtle motion, distant buildings visible

Room stays completely dark, cold blue tones only.
No warm light, no color change.
Camera stays still, only subjects move.
Slow motion feel, cinematic, 35mm film style.
Steam and pour are the main focus.


**출력 결과 요약**
> 새벽 창가에서 커피를 따르는 손 클로즈업 — 김이 피어오르는 시네마틱 영상 확보

**생성 결과 파일명**
- 이미지: `scene02_keyvisual_v1.jpg`
- 비디오: `scene02_video_v1.mp4`

---

### 🎬 씬 3 (마무리 씬 — 브랜딩 장치 필수 포함)

| 필드 | 내용 |
|------|------|
| **씬 번호** | 3 |
| **씬 길이** | 5초 |
| **목표 메시지** | 그래도 오늘을 시작하는 사람들에게 건네는 MORN의 조용한 위로 |

**화면 구성**
- 구도: 미디엄샷 (후면)
- 피사체: 뒤돌아서서 커피를 마시며 창밖을 응시하는 남성 실루엣
- 배경: 새벽 도시 스카이라인, 어두운 방, 창문에서만 콜드 블루 빛 유입
- 텍스트 유무: 있음
> 0\~2초: 텍스트 없음 (정적인 실루엣 유지)
> 3\~5초 : MORN 로고 등장
- ⚠️ **브랜딩 장치**: MORN 로고

**내레이션 / 화면 카피**
> (1초 후 시작) "매일 새벽, 그래도 일어나는 사람들에게. MORN."

**사용 도구 & 목적**
| 카테고리 | 도구명 | 사용 목적 |
|----------|--------|-----------|
| 이미지 | Bing image Creator | 실루엣 후면 키 비주얼 생성 |
| 비디오 | Runway Gen-4 Turbo | 콜드 블루 톤 시네마틱 영상 확보 |
| 오디오 | Vrew Ai | 나레이션 음성 생성 ("매일 새벽, 그래도 일어나는 사람들에게. MORN.") |

**입력 프롬프트 (원문)**
- 이미지 생성 :
Same high-rise apartment, same large floor-to-ceiling window, 
pre-dawn city skyline in background. Asian man standing with 
his back to camera, drinking coffee from ceramic cup, 
gazing out at city. Room is dark, man shown as dark silhouette only, 
face not visible, no detail on figure. 
Cold blue light coming only from window. 
Same cinematic cold blue mood as previous scenes, 
shallow depth of field, 35mm film style. 
City lights still on, dark sky outside.


- 비디오 생성 :
A young Asian man standing by a large floor-to-ceiling window,
holding a white ceramic coffee cup with both hands.

At the very beginning of the shot,
he raises the cup slowly and takes only one tiny, quiet sip.
Just a small, subtle sip — lips barely touch the cup.
The sipping motion completes within the first 4 seconds.
After the sip, he lowers the cup gently and holds it still.
No big gulping, no exaggerated drinking motion.

Thin steam rising gently from the cup throughout the shot.

Camera very slowly pans to the right,
causing the man to drift slightly toward the left side of the frame.
Movement is extremely subtle, almost imperceptible.
Man stays fully within the frame at all times, never exits.
By the end, the city view through the window becomes the main focus.

Through the large window:
- Massive city skyline stretching across the horizon
- Building lights flickering on and off naturally
- Cars and traffic moving slowly far below
- Pre-dawn blue atmosphere, city quietly waking up
- Subtle light changes across distant buildings

Room interior stays dark, silhouette of the man visible.
Cold blue tones only, no warm colors except the faint cup glow.
Camera pan is the only camera movement, very slow and smooth.
Cinematic, 35mm film style, melancholic and quiet mood.

**출력 결과 요약**
> 커피잔을 든 채 도시 스카이라인을 바라보는 실루엣 — 콜드 블루 톤 시네마틱 영상 확보, 나레이션('매일 새벽, 그래도 일어나는 사람들에게. MORN.') 생성

**생성 결과 파일명**
- 이미지: `scene03_keyvisual_v1.png`
- 비디오: `scene03_video_v1.mp4`
- 오디오: `scene03_voice_v1.wav`

---

## 🎥 비주얼 파라미터 & 후처리 절차 

### 핵심 카메라 파라미터
| 파라미터 | 설정값 | 적용 목적 |
|----------|--------|-----------|
| 렌즈 스타일 | 35mm film | 자연스러운 원근감, 시네마틱 느낌 |
| 색온도 | 5000K 이하 (쿨톤) | 콜드 블루 새벽 분위기 유지 |
| 심도 | 얕은 심도 (Shallow DOF) | 피사체 집중, 배경 흐림 |
| 무드 | Melancholic, Quiet | 절제된 감성 표현 |

### 캐릭터 고정성 유지 방법
> - 씬 1~3 전체에 동일한 인물 묘사 키워드 반복 사용
>   (`Young Asian man`, `gray t-shirt`, `short hair`)
> - 씬 간 연속성 확보를 위해 이전 씬 이미지를
>   Runway 입력 레퍼런스로 활용

### 후처리 절차
| 순서 | 항목 | 도구 | 내용 |
|------|------|------|------|
| 1 | 색감 보정 | CapCut | 전체 씬 콜드 블루 톤 통일 |
| 2 | 밝기/대비 조정 | CapCut | 어두운 실내 분위기 유지 |
| 3 | 자막 삽입 | CapCut | 씬3 나레이션 자막 추가 |
| 4 | 로고 합성 | CapCut | 씬3 3초 시점 MORN 로고 오버레이 |
| 5 | BGM 믹싱 | CapCut | BGM + 나레이션 볼륨 밸런스 조정 |

---

## 5. ⚡ 프롬프트 수정 전/후 기록 (최소 1개 씬 필수)

### 씬 (번호) — 프롬프트 개선 로그

| 항목 | 내용 |
|------|------|
| **수정 대상 씬** | 씬 번호: 1 |
| **수정 전 의도** | 어두운 방에서 창문을 바라보는 남자의 새벽 감성 표현 |
| **수정 전 프롬프트** | "Young man sitting on bed, looking at window, dark room, city view, cinematic" |
| **문제점** | 	방 안에 불필요한 조명이 생성되거나, 남자가 카메라를 정면으로 바라보는 구도로 나옴. 어두운 분위기가 제대로 표현되지 않음 |
| **수정 후 프롬프트** | "COMPLETELY DARK ROOM, ZERO artificial lighting, NO lamps, NO ceiling lights... ONLY cold blue light from window" |
| **수정 이유** | 단순히 "dark"라고만 하면 AI가 임의로 조명을 추가함 → 부정어(NO, ZERO)를 명시적으로 반복해서 조명 제거를 강제함 |
| **결과 변화** | 인공 조명이 사라지고 창문의 차가운 블루 빛만 남아 의도한 새벽 감성이 표현됨 |

---

## 6. 최종 영상 파일 정보

| 항목 | 내용 |
|------|------|
| **파일명** | Morn_AD.mp4 |
| **총 길이** | 10 초 |
| **해상도** | 1920x1080 |
| **프레임레이트** | 60fps |
| **비디오 코덱** | H.264 |
| **오디오 코덱** | AAC |

## 🚨 비상대응 계획

### 크레딧 부족 시 대응 전략
| 상황 | 우선 유지 씬 | 대응 방법 |
|------|------------|-----------|
| 이미지 크레딧 소진 | 씬 3 (브랜딩 필수) | Midjourney 대체 또는 기존 생성 이미지 재활용 |
| 영상 크레딧 소진 | 씬 3 > 씬 1 > 씬 2 | Kling AI 대체 또는 정지 이미지 슬라이드쇼로 대체 |
| BGM 크레딧 소진 | - | Udio 대체 또는 무료 CC0 BGM 사용 |
| 나레이션 크레딧 소진 | - | ElevenLabs 대체 또는 자막 전용으로 전환 |

### 씬 단축 우선순위
| 우선순위 | 씬 | 이유 |
|---------|-----|------|
| 1순위 유지 | 씬 3 | MORN 로고 + 나레이션 포함, 브랜딩 핵심 씬 |
| 2순위 유지 | 씬 1 | 감성 도입부, 메시지 전달 필수 |
| 단축/삭제 가능 | 씬 2 | 전환 연결 씬, 없어도 흐름 유지 가능 |

## ✂️ 시간 축소 & 메시지 재구성 전략

### 핵심 메시지 우선순위
| 순위 | 메시지 요소 | 포함 씬 | 삭제 가능 여부 |
|------|------------|---------|--------------|
| 1순위 | MORN 로고 + 슬로건 | 씬 3 | ❌ 삭제 불가 |
| 2순위 | 새벽 감성 도입 | 씬 1 | ⚠️ 단축 가능 |
| 3순위 | 커피 의식 연결 | 씬 2 | ✅ 삭제 가능 |

### 시간 축소 시나리오
| 시나리오 | 총 길이 | 구성 | 적용 조건 |
|---------|--------|------|-----------|
| 풀버전 | 10초 | 씬1(3초) + 씬2(2초) + 씬3(5초) | 기본 |
| 단축버전 | 8초 | 씬1(3초) + 씬3(5초) | 크레딧/시간 부족 시 |
| 최소버전 | 5초 | 씬3(5초)만 | 긴급 상황 |

### 축약 규칙
> 1. 브랜딩 요소(로고·슬로건)는 어떤 상황에서도 삭제하지 않는다
> 2. 씬 삭제 시 BGM 페이드인/아웃으로 자연스럽게 연결한다
> 3. 씬 길이 단축 시 나레이션 싱크를 우선 재조정한다

