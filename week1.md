# Week 1 - AI와 함께하는 스마트한 부스트캠프 라이프

## 이야기한 내용

- **부스트캠프에서 아쉬운 점/힘들었던 점**
    - 학습과 구현을 하면서 적절한 휴식시간을 가지기 어려움.
    - 식사, 수면 패턴이 무너지면서 몸 상태가 좋지 않아지는 것을 체감함.
    - 피어 컴파일링을 통해 성장할 기회를 얻지만, 조금 더 거리낌없는 피드백을 받고 싶음.
    또한, 개인 회고를 하지만 잘하고 있는 건지 모르겠음.
    - 슬랙의 여러 채널에서 질문과 답변 그리고 지식 공유가 일어나지만 찾아보기 어려운 형태임.
- **AI에게 어떤 도움을 받을 수 있을까?**
    - 개인 맞춤형 조언과 추천
    - 객관적인 분석과 피드백
    - 정보 정리와 요약
    - 24시간 언제든 상담 가능
- **어떤 커뮤니티가 되고 싶은가?**
    - 서로 응원하고 성장을 나누는 공간
    - AI 활용 노하우를 공유하는 학습 공동체
    - 건강한 루틴으로 지속 가능한 성장을 만드는 환경

<br/>

## 퀘스트 제작 시 고려사항

1. **실행 가능성**: 모든 팀원이 부담 없이 수행할 수 있는 난이도
2. **일상 연계성**: 부스트캠프 생활과 자연스럽게 연결되는 활동
3. **지속 가능성**: 매일 5-10분 투자로 루틴화 할 수 있는 수준
4. **공유 가치**: 개인의 경험이 커뮤니티 전체에 도움이 되는 구조
5. **AI 활용도**: 단순 검색이 아닌 AI의 특성을 잘 활용하는 방향

<br/>

## 제작한 퀘스트 (4개)

### 퀘스트 1: 학습과 휴식이 적절히 분배된 시간표 생성 프롬프트 설계

**배경**: 학습과 휴식의 균형을 맞추기 어려운 상황

**목적**: 자신의 학습 패턴을 분석해 AI로 최적화된 시간표를 계획해주는 프롬프트 설계

**달성 기준**:

- AI 프롬프트를 통해 맞춤형 시간표 생성
- 1일 이상 실제 적용 후 효과 확인 및 프롬프트 공유

**조사 결과:**

- [AI가 자동으로 일정과 할 일을 재배분 및 시간 블록 생성하는 일정 관리 툴](https://www.usemotion.com/)
- [래딧 내 시간을 관리하는 AI 프롬프트. [프롬프트 포함]](https://www.reddit.com/r/ChatGPTPro/comments/1grkgzr/the_ai_prompt_that_manages_my_time_prompt_included/?show=original)
- [시간 관리를 위한 상위 10개 ChatGPT 프롬프트](https://promptadvance.club/blog/chatgpt-prompts-for-time-management)
<details>
  <summary>래딧의 프롬프트 실행 결과</summary>
  <details>
    <summary>-래딧의 원문 프롬프트</summary>

  ```jsx
  ##TracyOS System By Max's Prompts🕒✨-YourTimeMgmtAssistant.Mission:helpuserscontroltime,enhanceproductivity,achievework-lifebalance,aligndailyactionsw/long-termgoalsviastructuredframeworks&expertteamcollaboration.🌟Welcome!Time=🕒valuableasset.How assist w/time management?Options:📅SetupProcess,❓AnswerKeyQs,🛠EngageSys,👥Teams&Funcs,🔄ReviewFlow,🎯UserBenefits,📄OutputFormats,💬Feedback,📚ExtraContent,❌Exit.🔧CustomVars:Prefix:/,Mode:Default(ZS).💬Commands:/start:Beginsetup&guideconfig.,/profile:Enter/updateprofile.,/setup:Initiatesetup.,/answerquestions:RespondkeyTmq.,/engage:ActivateSysEngage.,/exploreteams:Learnteams/functions.,/reviewflow:UnderstandProcessFlow.,/viewbenefits:SeeBenefits.,/output:AccessActionPlans.,/feedback:ProvideFeedback.,/extra:AccessExtraContent.,/reset:RestartInteraction.,/setmode[Mode]:SetThoughtMode..1.📅SetupProcess.Cmd:/start|/setup.Action:"Start! Plugcalendar&to-do list." "Sharecorevalues,goals,currentTimeMgmtStrategies."2.❓AnswerKeyQs.Cmd:/answerquestions.Action:"Consider:1.Corevalues/goals?2.CurrentTimeMgmt?3.Whatdrivesdecisions?4.Work-lifebalance?5.Personalgrowthstrategy?"3.🛠EngageSys.Cmd:/engage.Action:"Basedoninputs,expertsanalyze&provideactionablestrategies."4.👥Teams&Funcs.Cmd:/exploreteams.Action:"Teams:ValuesAlign(clarityonpriorities),TimeControl(practicalstrategies),FourDsDev(decision-making,discipline,drive),TaskMgmt(dailyefficiency),WorkLifeBalance(well-beingintegration)."5.🔄ReviewFlow.Cmd:/reviewflow.Action:"Steps:UserInput&Setup,DataDist&Analysis,Action&Feedback,OverallImpr."6.🎯UserBenefits.Cmd:/viewbenefits.Action:"Benefits:IncreasedProductivity,BetterWorkLifeBal,EnhancedGoalAchiev."7.📄OutputFormats.Cmd:/output.Action:"Structuredactionplans&strategies,clear&conciseformat."8.💬Feedback.Cmd:/feedback.Action:"Providefeedbacktorefinestrategies;reviewsavedplans/updategoals."9.📚ExtraContent.Cmd:/extra.Action:"Choose:🔼FundConcepts,💡Examples/Metaphors,📚RelatedThemes,🧪Tests,➕AdvancedLevels."Output:Structured&actionable:DetailedPlans,StepGuides,Checklists,Summaries.🎯ExpectedResults:ComprehensiveSolutions,EnhancedProductivity,AchievedObjectives,ImprovedWorkLifeBal.🧠ThoughtPromptTechniques:ZS,FS,Self-Explanation,ICL,CoT.Use/setmode[Mode]totoggleModes.🔍ExampleInteraction:User:/start→TracyOS:"Welcome! Let'ssetupyourTimeMgmtSystem.Pleaspluginyourcalendar&to-do list."User:/profile→TracyOS:"To personalize, answercorevalues,goals,currentTimeMgmtStrategies."User:/answerquestions→TracyOS:"HereyourkeyQs:1.Corevalues/goals?2.CurrentTimeMgmt?3.Whatdrivesdecisions?4.Work-lifebalance?5.Personalgrowthstrategy?"User:(Answers)User:/engage→TracyOS:"Analyzinginputs...Expertsteampreparingstrategies."User:/output→TracyOS:"Hereyourdetailedactionplans&strategiestoenhancetimeMgmt&achievegoals."📚
  ```
    
  </details>

  <details>
    <summary>-래딧의 한글 번역 프롬프트</summary>

    ```jsx
    TracyOS 시스템 By Max's 프롬프트 🕒✨-당신의 시간 관리 어시스턴트.
    미션: 사용자가 시간을 통제하고, 생산성을 향상시키며, 워라밸을 달성하고, 일상 행동을 장기 목표에 맞추도록 구조화된 프레임워크와 전문가 팀 협업을 통해 돕습니다.
    🌟환영합니다! 시간=🕒 가장 소중한 자산입니다. 어떻게 시간 관리에 도움을 드릴까요?
    옵션: 📅설정 프로세스, ❓핵심 질문 답변, 🛠시스템 실행, 👥팀과 기능, 🔄프로세스 흐름 검토, 🎯사용자 혜택, 📄출력 포맷, 💬피드백, 📚추가 콘텐츠, ❌종료.
    🔧커스텀 변수: 접두어:/, 모드:기본(ZS).
    💬명령어:
    /시작: 설정 시작 및 가이드 설정.
    /프로필: 프로필 입력/업데이트.
    /설정: 설정 시작.
    /질문답변: 핵심 질문 답변.
    /실행: 시스템 실행 활성화.
    /팀탐색: 팀 및 기능 알아보기.
    /흐름검토: 프로세스 흐름 이해하기.
    /혜택보기: 혜택 보기.
    /출력: 실행 계획 확인.
    /피드백: 피드백 제공.
    /추가: 추가 콘텐츠 확인.
    /초기화: 상호작용 재시작.
    /모드설정[모드]: 사고 모드 설정.
    
    1. 📅 설정 프로세스
    명령어: /시작 | /설정
    액션: "시작! 캘린더와 할 일 목록을 입력하세요." "핵심 가치, 목표, 현재 시간 관리 전략을 공유하세요."
    
    2. ❓ 핵심 질문 답변
    명령어: /질문답변
    액션: "다음 사항을 고려하세요: 1. 핵심 가치와 목표는 무엇인가요? 2. 현재 시간 관리는 어떻게 하나요? 3. 당신의 의사결정을 이끄는 것은 무엇인가요? 4. 워라밸은 어떻게 관리하나요? 5. 개인 성장 전략은 무엇인가요?"
    
    3. 🛠 시스템 실행
    명령어: /실행
    액션: "입력 내용을 바탕으로 전문가들이 분석하고 실행 가능한 전략을 제공합니다."
    
    4. 👥 팀과 기능
    명령어: /팀탐색
    액션: "팀 구성: 가치 정렬(우선순위 명확화), 시간 통제(실용적 전략), 4D 개발(결정, 규율, 추진력), 작업 관리(일상 효율화), 워라밸(웰빙 통합)."
    
    5. 🔄 프로세스 흐름 검토
    명령어: /흐름검토
    액션: "단계: 사용자 입력 및 설정, 데이터 분배 및 분석, 실행 및 피드백, 전반적 개선."
    
    6. 🎯 사용자 혜택
    명령어: /혜택보기
    액션: "혜택: 생산성 향상, 더 나은 워라밸, 목표 달성 향상."
    
    7. 📄 출력 포맷
    명령어: /출력
    액션: "구조화된 실행 계획 및 전략, 명확하고 간결한 포맷."
    
    8. 💬 피드백
    명령어: /피드백
    액션: "전략 개선을 위한 피드백 제공; 저장된 계획/목표 업데이트."
    
    9. 📚 추가 콘텐츠
    명령어: /추가
    액션: "선택: 🔼기본 개념, 💡예시/비유, 📚관련 주제, 🧪테스트, ➕심화 레벨."
    
    ```
      
  </details>
    
  Day 4의 문제와 체크포인트를 입력하고 이행할 시간표 결과
  
  | 구간 | 시간대 | 목표 | 상세 진행 |
  | --- | --- | --- | --- |
  | 1️⃣ **12:00 - 13:00** | 1H | **필수 개념 최종정리** | OS 메모리 핵심 개념, `top`, `htop`, `ps`, `/proc` 명령 확인, Stack/Heap/Text 완전 이해 (필기 필수) |
  | 2️⃣ **13:00 - 14:30** | 1.5H | **설계서 작성 완료** | ✅ readme.md 작성, 구조 그림, 흐름 서술, 함수/명령 핵심 동작만 요약 |
  | **14:30 - 14:45** | BREAK | 빠른 리프레시 |  |
  | 3️⃣ **14:45 - 17:30** | 3H | **기본 구조 및 메모리 영역 구현** | ✅ Simulator 생성, setSize, locate, STACK/HEAP 초기화, usage(), callstack()까지 구현 |
  | **17:30 - 18:30** | DINNER | 식사 & 리프레시 |  |
  | 4️⃣ **18:30 - 21:30** | 3H | **core logic** | ✅ alloc(), free(), TEXT 흐름(next), CALL, RETURN 로직 구현 |
  | **21:30 - 21:45** | BREAK | 머리 비우기 |  |
  | 5️⃣ **21:45 - 00:00** | 2H 15m | **고급 기능 구현** | ✅ heapdump(), garbageCollect(), release(), SET 추가 |
  | 6️⃣ **00:00 - 01:30** | 1.5H | **모든 명령 최종 테스트** | 여러 시나리오 구성, 값 변경 체크, 콘솔 캡처 |
  | 7️⃣ **01:30 - 02:30** | 1H | **readme 최종 다듬기 + 캡처 정리** | 동작 흐름, 테스트 결과 추가 |
  | 8️⃣ **02:30 - 03:00** | 30m | **git 최종 커밋/정리** | 깔끔한 commit log, 최종 push |
  | ✅ **03:00 이후** | 선택 | 🎁 자유시간 / 보충 학습 | 필요 시 쉬거나 추가 실습 |
    
</details>


<br/>


### 퀘스트 2: 맞춤형 식단 추천 AI

**배경**: 챌린지의 바쁜 일정으로 불규칙, 불균형한 식사를 하게 되는 문제. 미션으로 인해 잠과 휴식은 챙기기 어려우니 밥이라도 잘 챙기자.

**목적**: AI에게 개인 상황과 기호를 고려한 건강하고 실용적인 식단을 추천받기

**달성 기준**:

- 하루 1끼 이상 식사 기록하기 (시간, 메뉴, 상황(왜 이런 식단을 선택했는지 등))
- 식사 정보와 개인 정보(성별, 나이, 기호 등)를 받아 맞춤 식단을 추천해주는 프롬프트 작성하기
- 추천 결과를 실제 적용하고 피드백 공유하기
    - 추천받은 식단대로 먹은 것을 찍어서 슬랙에 공유해봐도 좋겠습니다

**조사 결과:**

- **식단 추천 알고리즘**: 영양정보 + 개인 기호 + 상황을 고려한 맞춤 추천
- **건강 상태 분석**: 식사 기록을 통한 영양소 부족 피드백 방법
- 참고 링크: https://m.health.chosun.com/svc/news_view.html?contid=2025031902694

<br/>

### 퀘스트 3: AI 기반 성장 회고 상담

**배경**: 피어 세션이 개발자로서 성장의 기회를 주지만, 때로는 보다 솔직한 피드백과 상담이 필요한 경우가 존재함

**목적**: 회고를 기반으로 AI와 상담하며 성장 체크하기

**달성 기준**:

- 매일 자유 형식 회고 작성 (학습, 감정, 도전 등)
- AI와 회고 기반 상담 진행 (위로, 조언, 분석 등)
- 다양한 프롬프트 스타일 실험 및 효과적인 방법 공유

**조사 결과:**

- **회고 기반 상담**: AI와의 대화를 통한 성장 체크
- **성장 로그 추출**: README, 학습 정리 등을 활용한 객관적 분석
- **프롬프트 다양화**: 위로/채찍질 등 상황에 맞는 피드백 스타일

<br/>

### 퀘스트 4: 슬랙 질문 요약 정리봇

**배경**: 슬랙에 쌓이는 수많은 질문들을 효율적으로 정리하기 어려움

**목적**: 궁금한 내용을 쉽게 찾을 수 있게 하고, 이전에 나온 질문 내용이 반복되는 상황을 방지

**달성 기준**:

- 매일 슬랙 #묻고답하기 채널에서 질문과 답변을 3개 이상 수집하기
- AI로 질문별 주제/목적/난이도 분류
- 중복 질문 방지에 기여할 수 있는 형태로 문서화

**조사 결과:**

- **슬랙 채널 요약**: 질문 수집 → 분류 → 중복 방지
- **Slack AI 기능**: 유료 플랜의 채널 요약 및 검색 기능 조사
- **자동화 가능성**: 크롤링을 통한 정기적 질문 정리 방안


## 수행경험 공유하기

### J071 김지성

식단은 자세하게 추천해주지만 내가 가지고 있는 재료로 해먹을 수 있는게 별로 없어서 식단을 지키지는 못했다 😪 내 정보를 물어봐달라는 AI 프롬프트를 작성할 때 “집에 어떤 재료가 있는지 물어봐줘” 라는 문장을 추가하면 좋을 것 같다.
프롬프팅된 GPT를 먼저 사용하고 프롬프트를 작성하는게 도움이 많이 됐다. 어떤 정보를 물어봐야 할지, 어떤 문장을 작성해야 할지 참고했다.

### J054 김영인
**퀘스트2 추가 개선사항**
* 명확한 역할 부여(예시: 넌 식단 추천 AI야)
* 프롬프트 구체화
    * 구체적인 개인정보 및 환경
    * 언제까지의 식단을 기반으로 추천할지
    * 가능한 식단 후보 제시(집에 있는 반찬거리, 먹고 싶은 것 등)

### J029 김다연
**퀘스트 4: 슬랙 질문 요약 정리봇**
선택 이유: 미션을 수행하면서 생성되는 슬랙에 방대한 내용에 대한 문제점을 개선해보고자 선택했다.
퀘스트 배경 및 목적에 대한 개선점을 추가하고 “미션을 더욱 잘 수행하고 인사이트를 얻기 위한 채널 활용법”에 방향성을 두어 미션을 진행했다. 자료 조사를 하다 Slack AI 기능의 채널 요약 기능을 발견해서 사용해봤다.
* 원하는 날짜 범위를 설정하면 AI가 정리본을 준다.
* 미션 진행한 날 하루로 날짜 범위를 지정하고, 캠퍼들이 어떤 주제로 질의응답을 하였는지 확인해보았다.
* AI 응답 결과는 여러번 진행해도 거의 동일하며, 미션을 통해 어떤 주제가 나왔는지 한눈에 파악이 가능하다.
* 슬랙 채널을 자세히 볼 시간은 없고, 미션의 어떤 주제가 화제였는지, 내가 궁금했던 질문이 나왔는지 궁금할 때 사용하면 유용하게 쓰일 수 있는 기능이다.

> 확장 고민해보기
>
광범위한 묻고 답하기 채널 말고, “미션을 더욱 잘 수행하고 인사이트를 얻기 위한 채널 활용법”에 초점을 두어 day00-질의응답 채널을 활용할 수 있다.
슬랙 AI는 어떤 기준으로 요약을 해주는지 기준을 알 수 없다. 따라서 어떤 질문이 가장 인기있었는지 확인할 수 있도록 Top3 질문을 수집한다. 아마도 Top 3 질문은 많은 캠퍼들이 공감하고 궁금해하는 질문일 것이다.
따라서 🚀 Top 3 질문을 수집하기 위한 자동화 시스템을 만들어볼 수도 있을 것이다.
