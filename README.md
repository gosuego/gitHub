# Semantic Commit Messages

- 검색하기 편하도록 태그는 []:
- 커밋 메시지의 시작은 영어 대문자 동사로 시작.

## 커밋 메세지 정리

![demo](./images/values.png)

- [feat]: 페이지(html), 함수(js)가 새로 추가됨
- [fix]: 페이지(html), 함수(js)가 수정됨
- [refactor]: 페이지(html), 함수(js) 가 필요없어서 삭제하거나, 이름이 마음에 안들어서 바꿈
- [style]: 스타일(css)이 추가, 수정, 삭제되거나 html 이랑 link 됨
- [docs]: 문서(md)가 추가, 수정, 삭제됨
- [test]: 테스트 코드를 추가, 수정 삭제함
- [chore]: 그외 기타

## 커밋 메시지 자주 쓰는 동사

- 추가(Add)
- 수정(Update)
- 삭제(Delete)

## 예시
- [refactor]: Delete plus function from practice/prac03/index.js
- [style]: Add practice/background.js
- [fix]: Add meta property to index.html
- [docs]: Update README.md
- [feat]: Connect weather API

## 참고 링크

- [gist.github.com](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
- [seesparkbox.com](https://seesparkbox.com/foundry/semantic_commit_messages)
- [conventionalcommits.org](https://www.conventionalcommits.org/en/v1.0.0/)
- [karma-runner](http://karma-runner.github.io/1.0/dev/git-commit-msg.html)

------
### 오답노트

- 파일을 삭제했는데 git으로 파일을 가져올 수 있나요? pull로는 Already up to date라고 떠요 ㅠ 
- commit을 했는데 이전 버전으로 바꾸고 거기서 branch를 만들어서 작업하고 싶어요 기존거는 냅두고 어떻게 할 수 있을까요? 순서 정리가 안돼요

- 파일을 삭제했는데 과거에 그 파일이 존재한 커밋이 있다면 당연히 복구가능함
- 그리고 commit 을 했는데 이전버전으로 바꾸고 거기서 branch 를 만들어서 작업하는 것도 가능함
- how?
