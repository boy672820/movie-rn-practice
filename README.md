# React-Native for iOS in m1 mac

## Node.js & watch 설치

- Watchman 파일 시스템 변경사항 관찰 / Facebook 도구
- Ruby 버전 확인
    - React-Native에서 요구하는 버전은 2.7.5
    - 맥에서 확인해보니 2.6.8 버전 사용 중
    - Ruby 버전관리자(rbenv)로 해당 버전 설치
    - Gem은 Ruby 패키지 매니저로 현재 이미 설치되어 있음

## CocoaPods

- Xcode 패키지 매니저로, 기본적으로 Ruby가 설치되어 있어야 됨

<aside>
💡 M1 Mac과 호환되지 않아 설치 시 다음 명령어로 설치

```bash
$ sudo arch -x86_64 gem install ffi
```

</aside>

## React-Native 실행

### React-native 실행 시 npx 사용

- 런타임 시 현재버전을 사용하는게 좋음
- 현재 전역으로 설치되었을 경우 문제가 될 수 있음(삭제 필요)

### Metro 먼저 실행

- React-Native 앱이 Metro에서 열리도록 해야 한다는데 뭔 소린지 모르겠음
- React-Native iOS 실행

<aside>
💡 React Native 프로젝트 생성 시 이름에 특수문자가 들어가면 안됨(영문, 숫자만 허용)

</aside>