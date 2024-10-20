# 꾸욱 - 키오스크 연습 어플
<img src="https://github.com/user-attachments/assets/0e899d35-b0b2-400a-bb46-b3be9f06f1e0" alt="appstore" width="120" height="120">

## 프로젝트 소개
'꾸욱'은 키오스크 환경에서 유저가 다양한 인터페이스를 연습할 수 있도록 개발된 어플리케이션입니다. 사용자는 Lottie 애니메이션과 AVFoundation으로 구현된 효과음을 통해 시각적, 청각적 피드백을 얻으며 인터페이스 사용을 익힐 수 있습니다. 이 앱은 자주 사용하는 키오스크 기능에 대한 사용 편의성을 높이기 위해 직관적인 UI로 설계되었습니다.

## 프로젝트 파일
[프로젝트 파일](https://github.com/Acasiax/kkookApp)

## 스크린샷
![꾸욱-스크린샷](https://github.com/user-attachments/assets/kkook-app-screenshot.png)

## 📱 시뮬레이션
| 메인 화면 | 기능 선택 화면 | 사용 방법 화면 | 완료 화면 |
|---------------|---------------|---------------|---------------|
| <img src="https://github.com/user-attachments/assets/main-screen.png" width="200" /> | <img src="https://github.com/user-attachments/assets/feature-select.png" width="200" /> | <img src="https://github.com/user-attachments/assets/how-to-use.png" width="200" /> | <img src="https://github.com/user-attachments/assets/completion.png" width="200" /> |

## ⚙️ 주요 기능
- **Lottie 애니메이션**: 화면 전환 및 주요 버튼에 애니메이션 효과 제공  
- **AVFoundation**: 버튼을 눌렀을 때 청각적인 피드백 제공  
- **사용자 교육 모드**: 다양한 키오스크 기능 연습을 위한 단계별 가이드  
- **성공/실패 피드백**: 각 단계 완료 시 즉각적인 피드백 제공  

## 💻 개발 환경
- **개발 기간**: 2024년 8월 20일 ~ 2024년 9월 10일  
- **개발 인원**: 1명  
- **개발 도구**:  
- **IDE**: Xcode 14.0  

## 🛠️ 기술 스택
- **UI**: UIKit – 사용자 인터페이스 구성  
- **애니메이션**: Lottie – 버튼 및 화면 전환 애니메이션 적용  
- **멀티미디어**: AVFoundation – 사용자 입력 시 사운드 제공  

## 라이브러리
- UIKit, Lottie, AVFoundation

## 📁 디렉토리 구조


## 🤔 고민한 부분
- **Lottie 애니메이션**: Lottie를 이용해 자연스러운 인터페이스 전환을 구현하는 동시에 메모리 관리에 신경을 썼습니다.
- **사용자 피드백**: 시각적, 청각적 피드백의 적절한 균형을 맞추는 데에 중점을 두었습니다.

## 😨 트러블 슈팅
- **AVFoundation 음향 지연**: 초기 앱 실행 시 음향 지연 현상이 발생하여, 사운드 파일을 미리 로드하는 방식으로 문제를 해결했습니다.
- **Lottie 애니메이션 최적화**: 무거운 애니메이션이 메모리를 과도하게 사용하는 문제를 해결하기 위해 애니메이션 파일 크기를 줄이고, 필요할 때만 로드하도록 변경했습니다.


