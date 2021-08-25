# Today I Read or Learn

## 가볍게 읽은 글들 정리
## 영감을 많이 받거나 유용한 글이라고 판단하면 [README](https://github.com/eomttt/studies) 로 옮김

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
