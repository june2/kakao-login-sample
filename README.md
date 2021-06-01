### IOS

- iOS 앱이 실행되지 않을 때는 XCode를 열고 테스트 해주세요. 이는 RN 0.64.0에서 발생되고 있는 문제입니다.
- KAKAO_APP_KEY등 필요한 SDK 연동 설정은 기본으로 되어 있습니다. info.plist 수정

```
$ yarn
$ npx pod-install
$ yarn ios
```
