# devspoon-beauty-smart-mirror-apps-tizen
it's tizen hackathon project for beauty AI smart mirror service 

## 팀명 및 팀원 
* **팀명** :  Devspoon 
* **팀장** : 임도현 - Software Part : 기획/설계/개발/서버/SDK/발표
* **개발자** : 강동훈 - Hardware Part : 기획/설계/개발/App
* **디자이너** : 임태연 - Design : 기획/설계/디자인

## 프로젝트 제목
* Beauty AI 스마트미러

## 프로젝트 배경 혹은 목적
* **프로젝트 목적** : 여성 생활 패턴에 가장 많이 사용되는 거울을 IoT 기술과 접목하여 서비스 Hub로서 다양한 기능을 제공하는데 목적을 가지고 있으며 코로나바이러스(COVID-19)로 인해 요구되는 언택트 기술을 제공하고자 화장품 샘플을 배송받아 QR-Code를 인식하여 사용자에게 AI기술이 결합된 최적의 서비스를 제공하고자 함     
 
* **세부 목표**
1. 타이젠 기반 Beauty AI 스마트미러는 음성으로 터치 없이 명령을 실행시키고 탑재된 카메라를 통해 사용자의 얼굴 형태, 피부 상태 등을 인식하여 실시간으로 사용자의 장점을 향상시켜 줄 수 있는 화장 방법을 분석하여 제공함.

2. 사용자가 QR 코드로 제품을 인식시키면 제품의 특성에 따라, 사용자가 보유한 제품들 중 함께 사용하면 좋을 화장품 종류를 알려주고 효율적인 화장 순서 및 방법을 제공함. 이로 인해 사용자는 배송 받은 화장품 샘플과 거울에 비친 사용자의 얼굴을 바탕으로, 전문가 수준의 화장 방법을 비대면, 개인 맞춤형으로 제공받을 수 있음.

## 파일 리스트 
* 팀원이 소스 파일을 직접 만든 경우, 해당 파일을 적어주세요. 
* 오픈소스(타이젠 등)로부터 가져왔지만, 팀원이 내용을 수정하거나 덧붙인 경우, 해당 파일을 적어주세요. 
* 오픈소스(타이젠 등)를 그대로 가져다가 사용한 파일은 적지 말아주세요. 
* 헤더와 소스만 적어주세요. 
* 디자인 등의 리소스는 적지 말아주세요. 
* 예시 
  * inc/resource_1.h 
  * inc/resource_2.h 
  * src/resource_1.c 
  * src/resource_2.c

## 코드 기여자 
### **Tizen-Apps**
* 각자 개발한 코드를 빠짐없이 기입해주세요.
* 파일 단위 혹은 함수 단위로 적어주세요. 
* 라인 단위로는 적지 말아주세요. 
* 팀원의 이름을 반드시 명시해주세요. 
* 예시 
  * 철수가 파일 전체를 개발한 경우 
    * inc/resource_1.h 철수 
    * src/resource_1.c 철수 
  * 철수와 영희가 각각 특정 파일의 함수를 개발한 경우 
    * src/resource_2.c function_1 영희 
    * src/resource_2.c function_2 철수 
  * 영희가 오픈소스에 특정 함수를 개발한 경우 
    * src/tizen.c function_3 영희

### **Server**
* 각자 개발한 코드를 빠짐없이 기입해주세요.
* 파일 단위 혹은 함수 단위로 적어주세요. 
* 라인 단위로는 적지 말아주세요. 
* 팀원의 이름을 반드시 명시해주세요. 
* 예시 
  * 철수가 파일 전체를 개발한 경우 
    * inc/resource_1.h 철수 
    * src/resource_1.c 철수 
  * 철수와 영희가 각각 특정 파일의 함수를 개발한 경우 
    * src/resource_2.c function_1 영희 
    * src/resource_2.c function_2 철수 
  * 영희가 오픈소스에 특정 함수를 개발한 경우 
    * src/tizen.c function_3 영희

## 보드 
* 프로젝트에서 사용하는 보드(RPI4 or 아두이노 등)를 적어주세요. 
* 사용하는 보드마다 각각의 목적을 적어주세요. 
* 사용하는 보드마다 설치되는 깃허브의 Repo를 적어주세요. 
* 예시 : 한 대만 사용한 경우 
  * RPI4 : 이미지 분석 및 센서 연동, github.com/theojin/hackathon-example 
* 예시 : 서로 다른 모델의 보드를 두 대 이상 사용한 경우 
  * RPI4 : 이미지 분석, github.com/theojin/hackathon-example-1 
  * 아두이노 : 센서 연동, github.com/theojin/hackathon-example-2 
* 예시 : 동일 모델을 두 대 이상 사용한 경우 
  * RPI4 1 : 이미지 분석, github.com/theojin/hackathon-example-1 
  * RPI4 2 : 센서 연동, github.com/theojin/hackathon-example-2
  
## 구현사항(가산점) 
  * Peripheral GPIO / I2C / UART / SPI 중 사용한 프로토콜 명시