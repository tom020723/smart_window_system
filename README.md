# Smart Window System

STM32F411RETx 기반의 AI 빗소리 감지 및 스마트 창문 제어 프로젝트입니다.

이 프로젝트는 STM32CubeIDE에서 열어 사용하는 것을 기준으로 합니다.

## 구성

- `smart_window_system.ioc`: CubeMX 설정 파일
- `Core/`: 사용자 코드 및 STM32 HAL 코드
- `Core/Src/CMSIS_DSP/`: MFCC 처리를 위한 CMSIS-DSP 소스
- `X-CUBE-AI/`: rain detector TFLite 모델에서 생성된 X-CUBE-AI 코드

## 참고

`smart_window_system.ioc`에는 기존 PC의 모델 파일 절대 경로가 남아 있을 수 있습니다.
다른 PC에서 열 경우 CubeIDE/X-CUBE-AI 설정에서 TFLite 모델 경로를 다시 지정하세요.
