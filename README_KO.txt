VisualSampler v1.0.1 FREE
for SP-404MK2
============================================================

Sample Your City. Remix Your Reality.

【1. VisualSampler란】

VisualSampler는 Roland SP-404MKII로 정지 이미지를 연주하는
macOS용 비주얼 샘플러입니다.

음악을 샘플링하듯 도시의 풍경과 일상의 사진을 샘플링하세요.
16개의 PAD로 이미지를 전환하며 실시간 영상 표현을 즐길 수 있습니다.

좋아하는 사진을 넣고 PAD를 두드리기만 하면 됩니다.
여러분의 일상을 영상 샘플로 만들어 보세요.

【2. 실행 환경】

・지원 OS: macOS(포함된 런타임의 최소 요구 사항은 11.0이며, OS 버전별 검증은 아직 완료되지 않았습니다)
・지원 Mac: Apple Silicon 탑재 Mac(M 시리즈)
・컨트롤러: Roland SP-404MKII
・연결: USB MIDI
・Processing을 기반으로 제작
・배포 앱에 Java 런타임 포함(일반적으로 별도 설치 불필요)

※이 배포 버전은 Apple Silicon 탑재 Mac 전용입니다. Intel Mac 및 Windows는 지원하지 않습니다.

【3. 앱 배치 및 실행】

1. 배포 ZIP 파일의 압축을 풉니다.
2. SP-404MKII를 USB로 Mac에 연결하고 전원을 켭니다.
3. SP-404MKII의 MIDI 설정을 확인합니다(아래 참조).
4. VisualSampler.app을 실행합니다.
5. SP-404MKII의 PAD를 눌러 이미지를 전환합니다.

SP-404MKII의 필수 MIDI 설정:
  SHIFT + PAD 13（UTILITY）→ SYSTEM → MIDI
  ・MIDI Mode：A
  ・PAD Note Out：ON

※이 두 항목은 VisualSampler 조작에 필수입니다.
  MIDI Mode가 B이면 PAD의 MIDI 노트/채널 할당이
  VisualSampler에서 예상하는 할당과 달라 정상적으로 조작할 수 없습니다.
  PAD Note Out이 OFF이면 PAD 조작에 따른 MIDI 신호가 전송되지 않습니다.
※VisualSampler 조작 시 MIDI EXT Src（TOGGLE / GATE / THROUGH）는
  특정 설정을 필수로 요구하지 않습니다.

Banks 폴더를 VisualSampler.app과 같은 위치에 두면 관리하기 쉽습니다.
시작할 때 Banks 위치를 묻는 경우 BankA와 BankB가 들어 있는 상위 “Banks” 폴더를 선택하세요.
선택한 위치는 저장되며 다음 실행에도 사용됩니다.
저장된 위치를 찾을 수 없으면 폴더 선택 창이 다시 나타납니다.
취소하거나 잘못 선택한 경우 앱 화면에서 R 키를 눌러 다시 선택할 수 있습니다.
Banks/BankA와 Banks/BankB에는 각각 01~16번 이미지가 모두 있어야 합니다.

올바른 배치 예시:

VisualSampler_v1.0.1_macOS_AppleSilicon/
├── VisualSampler.app
├── Banks/
│   ├── BankA/
│   │   ├── 01.jpg
│   │   ├── 02.jpg
│   │   └── ... 16.jpg
│   └── BankB/
│       ├── 01.jpg
│       ├── 02.jpg
│       └── ... 16.jpg
├── README_JP.txt
├── README_EN.txt
├── README_ES.txt
├── README_ZH_CN.txt
└── README_KO.txt

※폴더 이름은 “Banks”, “BankA”, “BankB”입니다.
  “BANK_A”, “BANK_B” 등으로 변경하지 마세요.
※Banks를 .app 내부로 이동하지 마세요.
【처음 실행: 개인정보 보호 및 보안】

이 배포판은 Developer ID 서명과 Apple 공증을 받지 않았습니다.
따라서 처음 실행할 때 Apple이 안전성을 확인할 수 없다는 경고가 나타날 수 있습니다.
다운로드 출처를 신뢰하며 파일이 변조되지 않았음을 확인한 경우에만 다음 절차를 진행하세요.

1. ZIP 압축을 풀고 VisualSampler.app을 한 번 열어 봅니다.
2. Apple이 악성 소프트웨어 포함 여부를 확인할 수 없다는 경고가 나타나면 경고를 닫습니다.
3. Apple 메뉴에서 “시스템 설정”을 엽니다.
4. “개인정보 보호 및 보안”을 선택하고 아래의 “보안” 항목으로 이동합니다.
5. VisualSampler 차단 알림 옆의 “확인 없이 열기”(Open Anyway)를 클릭합니다.
6. 인증이나 확인을 요청하면 내용을 검토하고, 계속 실행하려는 경우 “열기”를 선택합니다.
7. 앱이 실행되면 필요한 경우 Banks 폴더를 선택합니다.

보통 허용 내용은 저장되므로 다음부터는 더블 클릭하여 열 수 있습니다.
업데이트된 버전에서는 다시 허용해야 할 수 있습니다.
“확인 없이 열기”가 보이지 않으면 앱을 한 번 열어 본 직후 설정 화면을 확인하세요.
회사나 학교에서 관리하는 Mac에서는 이 옵션을 사용할 수 없을 수 있습니다.

“손상됨”, “Mac을 손상시킴”, “악성 소프트웨어 감지” 등의 경고가 나타나면
이 절차만으로 계속 진행하지 말고 공식 배포 출처와 다운로드 파일을 확인하세요.
“응답하지 않음”이 나타나면 반복 실행하지 말고 앱을 종료한 뒤 다시 확인하세요.

Apple 공식 안내:
https://support.apple.com/ja-jp/102445

【4. BANK 안내】

VisualSampler v1.0.1 FREE에서는 BANK A와 BANK B만 사용할 수 있습니다.
각 BANK에 16장씩, 총 최대 32장의 이미지를 할당할 수 있습니다.

BANK A: 도쿄의 일상 풍경을 촬영한 사진 16장(기본 수록)
BANK B: BANK A 사진을 모티브로 한 2색 만화풍 이미지 16장(기본 수록)

BANK C 이후에 이미지를 넣어도 FREE 버전에서는 불러오거나 표시하지 않습니다.
향후 VisualSampler PRO 버전에서는 사용할 수 있는 BANK를 늘릴 예정입니다.
※PRO 버전의 사양과 공개 시기는 미정이며 변경될 수 있습니다.

【5. 자신의 이미지 사용하기】

1. VisualSampler를 종료합니다.
2. Banks/BankA 또는 Banks/BankB를 엽니다.
3. 기존 이미지를 백업하고 원하는 이미지로 교체합니다.
4. VisualSampler를 다시 실행하여 확인합니다.

지원 이미지 형식:
  .jpg   (우선순위 1)
  .jpeg  (우선순위 2)
  .png   (우선순위 3)

확장자는 대소문자를 구분하지 않습니다.

파일 이름 규칙:
・PAD 01~16에 대응하는 “01”~“16”으로 시작합니다.
・번호만 사용하거나 “번호_원하는 이름”을 사용할 수 있습니다.
・예: 01.jpg / 01_tokyo.jpg / 16_night.png
・“01tokyo.jpg”처럼 번호 바로 뒤에 밑줄이 없는 이름은
  인식 대상이 아닙니다.

같은 PAD 번호에 여러 후보 파일이 있을 때의 우선순위:
  1. 확장자: .jpg → .jpeg → .png
  2. 확장자가 같으면 확장자를 제외한 파일 이름이 짧은 파일
  3. 길이가 같으면 파일 이름의 알파벳순(대소문자 구분 없음)

예: 01.jpg / 01_city.jpg / 01_tokyo.png가 있으면
    01.jpg를 불러옵니다.

혼동을 피하려면 PAD 번호 하나당 이미지 파일 하나를 권장합니다.

【6. 권장 이미지 비율 및 파일 크기】

앱의 기준 창 크기는 768 × 1024 px(가로:세로 = 3:4)입니다.
화면 비율에 맞춰 소재를 제작하려면 세로형 3:4 비율을 기준으로 삼으세요.

권장 예: 768 × 1024 px 또는 1536 × 2048 px 정도.
※이는 제작 시 참고 기준이며 필수 조건은 아닙니다.
※이미지 표시 방식에 따라 잘림, 여백, 변형이 다르게 보일 수 있습니다.
  실제 표시 결과를 확인하세요.

이미지 파일 크기나 해상도가 클수록 실행 시 BANK 이미지를
불러오는 시간이 길어질 수 있습니다.
시작 화면에서 메인 화면으로 넘어가는 데 오래 걸리면
이미지를 적절한 크기로 축소하거나 압축하세요.

【7. Mac 키보드로 창 크기 변경하기】

Shift + 1 ：384 × 512 px（50%）
Shift + 2 ：576 × 768 px（75%）
Shift + 3 ：768 × 1024 px（100%）

※이미지 파일 자체의 크기가 아니라
  앱의 창 크기를 전환하는 조작입니다.
※키보드 배열이나 입력 설정에 따라 동작이 달라질 수 있습니다.

【8. 비주얼 이펙트】

탑재 이펙트:
・GLITCH    : 디지털 노이즈 및 영상의 깨짐
・CRT       : 브라운관 TV 스타일의 표현
・PIXELATE  : 거친 픽셀 형태의 표현
・RGB SPLIT : RGB 색상 어긋남을 이용한 표현

SP-404MKII 조작:
・CTRL 1: 이펙트 선택
・CTRL 2 / CTRL 3: 선택한 이펙트의 효과 조절
・EXT SOURCE를 두 번 누르기: 이펙트 리셋

※이펙트의 모습과 조절 내용은 선택한 종류에 따라 다릅니다.

【9. 문제 해결】

이미지가 표시되지 않을 때:
・시작 시 선택 창에서 BankA나 BankB가 아닌 상위 Banks 폴더를 선택하세요.
・다시 선택하려면 안내 화면에서 R 키를 누르세요.
・저장된 위치의 Banks가 존재하고 읽을 수 있는지 확인하세요.
・“Banks/BankA”, “Banks/BankB”의 이름이 올바른지 확인하세요.
・이미지가 01~16 이름 규칙과 지원 형식을 따르는지 확인하세요.
・BANK C 이후에 이미지를 넣지 않았는지 확인하세요.
・이미지를 교체한 뒤 앱을 다시 실행했는지 확인하세요.

실행에 오래 걸릴 때:
・이미지 해상도나 파일 크기를 줄이고 다시 시도하세요.

SP-404MKII로 조작할 수 없을 때:
・USB 연결과 본체 전원을 확인하세요.
・SYSTEM → MIDI에서 “MIDI Mode：A”를 확인하세요.
・같은 화면에서 “PAD Note Out：ON”을 확인하세요.
・앱을 다시 실행하여 확인하세요.

【10. 이용 시 주의 사항 및 상표】

VisualSampler는 개인이 제작한 소프트웨어입니다.
환경에 따라 정상적으로 동작하지 않을 수 있습니다.
본 소프트웨어 사용으로 발생한 손해에 대해 제작자는
법률이 허용하는 범위에서 책임을 지지 않습니다.

이미지를 교체할 때는 저작권, 초상권 등의 권리를 준수하세요.
라이브 스트리밍이나 동영상 공개 시에도 사용 소재의 권리에 유의하세요.

VisualSampler는 Roland Corporation과 관계없는 독립 제작물이며,
해당 회사가 개발하거나 승인 또는 후원한 제품이 아닙니다.
Roland 및 SP-404MKII는 Roland Corporation의 상표 또는 등록 상표입니다.

【11. Credits / 제작자 정보】

VisualSampler v1.0.1 FREE
Created by：achamania
Concept / Design / Development：achamania

© 2026 achamania. All rights reserved.

YouTube：achamania
https://www.youtube.com/@achamania

X（Twitter）：@achamania
https://x.com/achamania

데모와 창작 활동은 위 SNS에서 확인하세요.

【12. Message from achamania】

여러분의 작품을 보여 주세요!

VisualSampler로 동영상을 제작하고 공개했다면
제 YouTube 채널 댓글로 꼭 알려 주세요!

라이브 퍼포먼스, 뮤직비디오, 도시 풍경을 활용한 영상 작품 등
어떤 활용 방식이든 환영합니다.

여러분이 VisualSampler로 어떤 작품을 만들어 낼지 정말 기대됩니다!

Show me what you've sampled!

YouTube：https://www.youtube.com/@achamania

Sample Your City. Remix Your Reality.

【v1.0.1 변경 사항 및 검증 상태】
・다운로드한 앱이 macOS의 격리된 위치에서 실행될 때(App Translocation) 외부 Banks를 찾지 못하는 문제를 수정했습니다.
・Banks 폴더 선택, 위치 저장 및 다시 선택 기능을 추가했습니다.
・앱 아이콘을 변경했습니다.
・Java가 포함되어 있어 일반적으로 Processing이나 별도 Java를 설치할 필요가 없습니다.

2026년 10월 15일, 개발에 사용한 Apple Silicon Mac에서 GitHub 재다운로드,
macOS 실행 허용, Banks 읽기 및 재선택 복구, 실제 기기의 MIDI/BANK/FX/CTRL 조작을 확인했습니다.
32개 이미지 전체와 PAD 처리도 자동화 시험으로 확인했습니다.
다른 Mac, 장시간 실행, 모든 매개변수 조합은 아직 검증하지 않았습니다.
기존 시작 화면에는 Ver. 1.00이 표시되지만 이 패키지는 v1.0.1입니다.
