# STM32H750-Development-Board
가격이 저렴하면서도 480MHz의 클럭으로 돌아가고 내장 메모리가 1MByte 나 되는 ST 의 STM32H750VBT6 마이크로 컨트롤러를 학습하고 테스트할 수 있는 개발보드를 만들었습니다.

![](https://github.com/uraetech/STM32H750-Development-Board/blob/master/Image/750vbt6-20200129.jpg)

구성은 다음과 같습니다.

![](https://github.com/uraetech/STM32H750-Development-Board/blob/master/Image/map.jpg)

---
## 특징
기본적이고 필수적이라고 생각되는 USB, QSPI FLASH, Micro SD Socket, UART 를 탑재하고 있습니다.  또한 모든 핀을 핀헤더로 배치해 놓아 모든 기능을 테스트할 수 있게 했습니다.

1. Micro USB 
>- Full Speed USB를 컨텍터를 달았습니다.  예제는 간단한 CDC 를 포함합니다.

2. QSPI Flash
>- Winbond 사의 W25Q128FV. XiP 등을 테스트해 볼 수 있습니다.

3. UART1
>- 디버깅 용도 및 시리얼 통신을 테스트합니다.

4. MicroSD Socket
>- TF 카드를 통해 FatFS 테스트할 수 있는 예제가 제공됩니다.

5. SWD 컨넥터
>- 펌웨어 다운로드 및 디버깅

6. 리셑 스위치 및 사용자 LED
>- 리셑 스위치와 PC15에 LED를 달아 테스트용으로 쓸 수 있습니다.

----

## 제품 구입
제품을 구입하고 싶으시면 [유래텍](https://uraetech.co.kr)을 방문해 주세요.

