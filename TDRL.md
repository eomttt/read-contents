# Today I Read or Learn

## 가볍게 읽은 글들 정리
## 영감을 많이 받거나 유용한 글이라고 판단하면 [README](https://github.com/eomttt/studies) 로 옮김

### 20210827

### 20210826
[Zero to Hero: Front End Developer Roadmap](https://dev.to/ruppysuppy/front-end-developer-roadmap-zero-to-hero-4pkf)
  - 로드맵 까지는 아니고 기본적으로 알아야할것들 설명
  - HTML, CSS, JS
  - Git, REST Api
  - PWA, GraphQL, Cross-Platform Application

[All CSS Properties You Need to Know to Build a Website](https://dev.to/domagojvidovic/all-css-properties-you-need-to-know-to-build-a-website-3dbb)
  - 너무 기본적인 속성들만 나열한 글
  - flex 에서
    - justify-content: main axis
    - align-items: cross aixs
  
[What’s New in TypeScript 4.4?](https://betterprogramming.pub/whats-new-in-typescript-4-4-e17d63b84b86)
  - Control flow analysis of aliased conditional expressions
    - const, readonly 변수에 if statement 에서 타입 가드
  - Index signatures for symbols and template literal strings
    - 객체 키에 다양한 하게 타입 정의 가능
  - Defaulting to the unknown Type in Catch Variables
    - try... catch 에서 catch error 타입 unknown으로 수정
  - Exact Optional Property Types
    - 객체에서 optional value 굳이 undefined 안해도되도록 수정

[How Good Developers Repair Bad Codebases](https://levelup.gitconnected.com/how-good-developers-repair-bad-codebases-64cd1e3ec7de)
  - 크게 영감을 받진 않았고 기본적인 내용들을 쉽게 서술해놓음
    - 코드 룰을 정의하자
    - 기술 부채의 주의하자
    - 수선자 보다는 만드는 사람이 되자
      - 코더 보다는 프로그래머가 되자 라는 생각은 예전 부터 하고 있었음
      - 그러나 요즘 계속 코더가 되는듯한 느낌적인 느낌 (따라서 생각하면서 코딩하자!)

[Skeleton for Node.js Apps written in TypeScript (with Setup Instructions for ESLint, Prettier, and Husky)](https://javascript.plainenglish.io/skeleton-for-node-js-apps-written-in-typescript-444fa1695b30)
  - 프로젝트 세팅에 보일러플레이트 정리
    - eslint
    - prettier
    - husky

[1. 코로나 시대에서의 WebRTC](https://brunch.co.kr/@springboot/639)
  - WebRTC 기술에 대하여
  - 클라이언트에서 짧은 지연시간으로 오디오 및 동영상 제공 하는 곳에서 사용이 많이 됨
    - 클럽하우스
    - 구글 화상 Meet
    - 하이퍼커넥트
    - 게임 스트리밍

### 20210825
[7 Tips for Empathetic Code Reviews](https://betterprogramming.pub/7-tips-for-empathetic-code-reviews-901e8b049a88)
  - 코드를 바로 읽지 마라 (테스트 코드 같이 상황을 파악한뒤 코드를 일고 내 생각을 적어라)
  - WTF 순간을 조심해라 (몇번 읽어도 이해가 안되는 코드, 이상한 테스트 코드들을 찾아서 어렵게 생각하지 말고 코멘트 해라)
  - 코멘트를 의문형 형식으로 해라 (저 변수가 null 이면 어떻게 될까요? 같은 류의 생각을 할 수 있게 하는 코멘트를 달아라)
  - 학습을 할 수 있도록 해라 (나 혼자 모든걸 다 할 수 없기 때문에 같이 일하는 동료들의 수준을 높일 수 있는 질문을 코멘트 해서 학습을 유도해라)
  - 코드 작성자가 제일 코드를 잘 안다 (이점을 명시해서 코드 리뷰에 균형을 잡아가야한다)
  - 실용적으로 진행해라 (코드 가독성과 성능을 위해 짜다보면 코드가 너무 복잡해 질 수 있다. 그렇기 때문에 너무 디테일에 잠식 될 필요가 없다)
    - 가독성과 코드 최적화 사이에 몇가지 경험에 따른 원칙들
    - 이 코드가 다른곳으로 가면 더 좋을까?
    - 긍정에 대상이면 적지 않는것이 좋다
    - 나에게 물어보라. 내가 승인하고 작성자가 작업을 완료하기 위해 변경 사항에서 놓친게 무엇인지.
  - 개인적으로 진행해라 (언제나 동료가 늘 옆에 있을 수는 없다.)

[7 Useful HTML Attributes that You Probably Don’t Know](https://javascript.plainenglish.io/7-useful-html-attributes-that-you-probably-dont-know-661784fe21e)
  - input
    - accept
    - multiple
    - pattern (정규식에 따라 input 에서 허용)
  - contenteditable
    - 사용자가 컨텐츠를 수정 할 수 있게 해줌
  - download
  - translate
    - 특정 텍스트 번역
  - poster
    - 비디오세어 썸네일

[Building useReducer with logger](https://staleclosures.dev/building-usereducer-with-logger/)
  - useReducer 를 이용하여 이전 상태, 다음 상태 group 하여 로그 남기기.

[트렁크 기반 개발 TBD](https://code-masterjung.tistory.com/73)
  - Git branch 방법론으로 한 브렌치에서 여러명이 작업하는 방향
  - 코드가 쉽게 공유되고 팀으로 움직일때에 많은 시간이 절약됨.
  - 작은 단위에 (max 2 days) feature 정도는 허용됨.
