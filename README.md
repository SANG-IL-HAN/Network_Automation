# Network_Automation

파이썬 네트워크 자동화 관련 실습을 진행한 기록입니다.

이 레파지토리는 3장까지 학습 후 만들어졌습니다. ( 2022 / 01 /09 ~ )


# -사용한 교재- 


![1562888590Ag5u1Tl7](https://user-images.githubusercontent.com/43851230/148686705-23680cfa-5884-4ba1-969a-e3ca0548da68.png)

이 책의 구성

우리가 네트워크 자동화에 첫 걸음을 내딛고 자동화에 다가간다는 의미에서 이 책은 크게 다섯 발걸음(five steps)으로 나눌 수 있을 것 같습니다.

첫 걸음은 1장에서 현재 IT 엔지니어들의 능력과 본인의 능력을 비교 분석해 봄으로서 어떻게 파이썬을 이용한 네트워크 자동화 공부를 시작해야 할지 함께 고민해 봅니다. 또한 이 책에서 다루는 전체적인 내용들과 네트워크 자동화 공부에 도움이 될 만한 사전 지식과 랩 구성에 필요한 요구사항을 간단히 둘러봅니다.

두 번째 발걸음은 2장에 속하며, VMware 워크스테이션 설치와 구성 그리고 기본 사용법 익히기, 가상 서버 설치해보기 등을 통해 실질적인 사용 방법을 익혀 봅니다. 그리고 GNS3을 사용한 가상화된 네트워크 랩 환경도 소개합니다. GNS3 설치와 설정 그리고 간단한 IOS 가상 랩 만들기를 통해 GNS3에서 사용되는 필수 기술들을 익힙니다. VMware 워크스테이션, GNS3 VM, GNS3에 시스코 IOS 이미지를 사용해 네트워크 자동화 랩 환경이 제대로 동작하는지 실행하면서 배워봅니다. VMware 워크스테이션과 GNS3의 설치는 곧 멀티 용도 랩을 만드는 초석이 됩니다. 차후 여러 벤더 기술 및 시스코 자격증 랩으로 사용 가능해집니다.

세 번째 발걸음인 3장에서는 이 책에서 사용할 파이썬을 리눅스와 윈도우 환경에 설치한 후 5장 랩에서 사용될 paramiko와 netmiko 파이썬 라이브러리를 설치하는 상세한 과정을 둘러봅니다. 처음으로 파이썬을 접하는 네트워크 엔지니어들은 파이썬과 파이썬 네트워킹 모듈과 관련된 설치과정을 이해하지 못하므로 하나에서 열까지 상세하게 설치 방법을 알려줍니다. 그리고 파이썬 코드 개발에 도움이 되는 텍스트 에디터들을 차례로 소개해 사용자가 본인 코딩 스타일에 맞는 텍스트 에디터 프로그램을 선택할 수 있도록 선택권을 드립니다.

네 번째 발걸음에 속하는 4장에서는 네트워킹 자동화 기술에 필수인 기본 리눅스 사용법을 배워 중요 네트워크 서비스인 FTP, SFTP, TFTP와 NTP 서버를 CentOS 7.5 리눅스 서버에 직접 구축해봅니다. 미래 여러 가지 시나리오의 랩을 실험할 때 이러한 올-인-원(All-in-one) 서버는 유용하게 사용될 수 있으며 POC(Proof-of-concept) 랩에서 꼭 필요한 요소입니다. 그리고 직접 파이썬 따라잡기를 통해 파이썬 기초 문법과 사용 방법을 간단히 익힐 수 있습니다. 4장을 통해 5장 네트워크 자동화 랩에서 필요한 여러 가지 리눅스 및 파이썬 기초 기술들을 습득합니다.

마지막으로 다섯 번째 발걸음은 5장으로 실습 네트워크 자동화 랩을 통해 이 책의 클라이맥스를 장식합니다. VMware 워크스테이션에서 만든 CentOS 리눅스 서버, GNS3 VM, GNS3에 시스코 L2 스위치 및 L3 라우터 이미지를 통합시켜 네트워크 자동화 랩 환경 만들기를 완성합니다. 2장에서 완성한 통합 랩 환경을 사용해 직접 사용자가 파이썬 3을 이용해 네트워크 자동화 스크립트를 손수 코딩하고 파이썬 코드를 사용해 직접 네트워킹 기기들을 제어 및 관리하게 됩니다.

코딩을 사용한 강력한 기술력을 직접 체험할 수 있으며 지금까지 궁금했던 텔넷과 ssh 접속을 이용한 시스코 네트워킹 장비 제어 및 관리 기술을 직접 손과 눈으로 그리고 머리로 배우면서 네트워크 자동화에 자연스럽게 입문하게 됩니다. 추가로 리눅스 작업 스케줄러인 크론(cron) 사용법을 익혀 직접 만든 파이썬 코드를 사용자 없이 실행해 봅니다. 또한, SNMP 개요를 통해 SNMP를 사용한 SNMP 파이썬 모니터링 코드 사용법도 간략하게 배웁니다. 마지막으로 파이썬 네트워크 자동화 코딩을 하면서 회사 내에서 도움이 되는 선택적 정보 공유를 끝으로 책을 마무리합니다.

이 책의 구성은 체계적으로 그리고 궁극적으로 교육의 목적으로 쓰여졌으므로, 책 전반부는 독자들의 이해를 돕기 위해 필자가 2년 동안 파이썬을 공부하면서 느끼고 생각했던 것을 정리했으며, 중반부는 한 발 더 나아가 직접 랩 설치 및 구성 후 기본기 다지기로 구성했습니다. 특히 VMware 워크스테이션 가상화 랩을 사용해 네트워크 자동화에 필요한 리눅스 및 파이썬 기본기를 직접 키보드를 통해 연습합니다. 마지막으로 GNS3 설치와 랩 환경을 완성시킨 후, 직접 코딩을 하고 완성한 파이썬 3 스크립트로 네트워킹 장비 자동화의 핵심인 telnet, SSH와 SNMP를 통한 시스코 IOS 기기 제어 방법의 기본기들을 배웁니다.

# -사용한 프로그램- 

![images](https://user-images.githubusercontent.com/43851230/148686784-ff48158b-5798-4339-ad54-800ff0563544.jpg)

![download](https://user-images.githubusercontent.com/43851230/148686791-22cb8e52-413b-4337-95f8-385cc9567933.jpg)

![images](https://user-images.githubusercontent.com/43851230/148686865-17a7da7a-1539-4e08-a8cc-6443743ab597.jpg)

![download](https://user-images.githubusercontent.com/43851230/148686813-89e2790c-ea48-4cc0-a7ce-d5770d6ccfd5.png)




