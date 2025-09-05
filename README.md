# 💻 Smart bearing condition monitoring service (English Version)
A smart factory system project implementing a bearing degradation monitoring service using an AI model trained on the PHM-2012 dataset.
<div >
<img width="1000" alt="스크린샷 2023-08-23 오전 3 53 04" src="https://github.com/SWTeam2/learning_infer/assets/139730231/2a3e5652-f73e-4970-b68d-8a74131a5ce1">
<div/>
<br>

## 💡 Project Introduce
- 2023.07.26 - 2023.08.23
- Anomaly detection and Remaining Useful Life (RUL) prediction services in a smart factory environment bring revolutionary changes to the industrial field. Since equipment failure can lead to production line shutdowns and increased costs, it is crucial to monitor machine conditions, detect anomalies at an early stage, and perform necessary maintenance. This not only enhances productivity but also reduces operational costs.
  <br><br>
 
## 🧞‍♂️ Service Features
+ Dashboard Service
![대시보드 서비스 시연영상](
https://github.com/K-Software-BootCamp/2023KEB_SKII/assets/76683835/a2d6f7cc-a236-45e5-bfcd-93b501b6403a
)

+ User Management Interface
![회원관리 시연영상](
https://github.com/K-Software-BootCamp/2023KEB_SKII/assets/76683835/c5b92833-71ae-42db-9722-c50fcc8dcb32)

- Implemented a system that integrates real-time sensor data collection with prediction results from the AI model.
  
- Built a predictive service using a CNN-LSTM hybrid model to identify patterns between bearing condition changes and remaining useful life.
  
- Developed a deployable service framework that goes beyond research, providing practical tools for managing component life cycles and improving safety in real-world industrial applications.

<br><br>

## 📄 Project Docs
- [Notion Link](https://www.notion.so/choheeyeon/SK2-Smart-Bearing-af1f4c8346c049489b396224684dd3f5)
- [GitHub Organization](https://github.com/SWTeam2)
<br><br>

## 📁 Directories
1. [Data_preprocessing](https://github.com/SWTeam2/Data_preprocessing)
    - Data augmentation and preprocessing steps
2. [DB_server](https://github.com/SWTeam2/DB_server)
    - Database server implementation and API communication 
3. [modeling_inferServer](https://github.com/SWTeam2/learning_infer)
    - Neural network modeling, optimization, and inference server implementation
5. [web_service](https://github.com/SWTeam2/SmartBearing)
   - Backend and frontend implementation for the web service
<br><br>

## 🤖 Model
- CNN encoder
![CNN encoder](https://github.com/K-Software-BootCamp/2023KEB_SKII/assets/76683835/4ac06e1a-2174-4248-aefe-32681a34803d)
- CNN-LSTM model
![CNN-LSTM model](https://github.com/K-Software-BootCamp/2023KEB_SKII/assets/76683835/3b356554-16e6-4894-9a2b-494ef07a3fed)
<br><br>

## 📋 Service Sequence
### - Bearing data work flow
![sequence_bearing](https://github.com/chy0503/SmartBearing/blob/main/document/sequence/sequence_bearing.png)
<br><br>

### - Log in & out work flow
![sequence_member](https://github.com/chy0503/SmartBearing/blob/main/document/sequence/sequence_member.png)
<br><br>

### - Employee
![sequence employee](https://github.com/chy0503/SmartBearing/blob/main/document/sequence/sequence_employee.png)
<br>

### - Notification
<img src="https://github.com/chy0503/SmartBearing/blob/main/document/sequence/sequence_notification.png" alt="sequence notification" height="450">
<br><br>

## 📈 Service Structure
![usecase diagram](https://github.com/SWTeam2/learning_infer/assets/139730231/43820183-0401-41d8-ab88-b8ac5abe88f0)
<br><br>

## ⚙️ CI/CD Architecture
![ci/cd diagram](https://github.com/SWTeam2/SmartBearing/blob/main/document/CICD.png)
<br><br>

## 🛠️ Tech Stack

### Frontend
<img src="https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=Figma&logoColor=white"/> <img src="https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white"/> <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/Chart.js-FF6384.svg?style=for-the-badge&logo=chartdotjs&logoColor=white"/>

### Backend
<img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=Spring%20Boot&logoColor=white"/> <img src="https://img.shields.io/badge/Spring DATA JPA-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"/> <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=Spring%20Security&logoColor=white"/> <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white"/><br>
<img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white"/> <img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>

### Data engineering & Modelling
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/postgresql-4169E1?style=for-the-badge&logo=postgresql&logoColor=white">
<br>
<img src="https://img.shields.io/badge/anaconda-44A833?style=for-the-badge&logo=anaconda&logoColor=white">
<img src="https://img.shields.io/badge/fastapi-009688?style=for-the-badge&logo=fastapi&logoColor=white">
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/scikitlearn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/maplibre-396CB2?style=for-the-badge&logo=maplibre&logoColor=white">

### Server Infra
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=Amazon%20EC2&logoColor=white"> <img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=GitHub%20Actions&logoColor=white">

### Team Tools
<img src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"/> <img src="https://img.shields.io/badge/gitkraken-%179287.svg?style=for-the-badge&logo=gitkraken&logoColor=white"/> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/> <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/>
<br><br>

## 👥 Member

|                                                        Sungboo Park                                                        |                                      김찬영                                       |                                                        최병훈                                                        |
|:-----------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/eac504ea-b35c-4a12-8775-0b3270eeb51f" /> | <img width="200" src="https://github.com/K-Software-BootCamp/2023KEB_SKII/assets/139730231/7658b916-1bba-4d9d-b457-3ef09cec8e4e" /> | <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/37be928a-cc07-46f8-a07b-6ce2de625b90" /> |
|                                   Team Leader<br/>Modeling<br/>Data Engineering                                   |                                    Modeling                                    |                                                     Modeling                                                      |
|                                     [@parksboo](https://github.com/parksboo)                                      |                   [@Cksdud123](https://github.com/Cksdud123)                   |                                     [@choi4624](https://github.com/choi4624)                                      |

|                                                        김정호                                                        |                                                        방가윤                                                        |                                                        윤정우                                                        |
|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
| <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/86cae49c-c6c0-4d5d-a7e0-5d061580e2cb" /> | <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/44161649-7ec2-41ed-a8a9-b614b7c92e1c" /> | <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/6071373c-abc1-44a6-9beb-f669a246e300" /> |
|                                           Modeling<br/>Data Engineering                                           |                                                 Data Engineering                                                  |                                                 Data Engineering                                                  |
|                                    [@KimJeongHo](https://github.com/Jeongho-K)                                    |                                        [@novzs](https://github.com/novzs)                                         |                                [@Yoon-jeongwoo](https://github.com/Yoon-jeongwoo)                                 |

|                                                               김다은                                                               |                                                        이낙규                                                        |                                      조희연                                       |
|:-------------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------:|
| <img width="200" src="https://user-images.githubusercontent.com/77656241/215424915-043d3e72-5605-41c5-84af-4925d72732d2.png" /> | <img width="200" src="https://github.com/chy0503/chy0503/assets/90389517/748e8440-d87e-448f-8894-76efbd762ed1" /> | <img width="200" src="https://avatars.githubusercontent.com/u/90389517?v=4" /> |
|                                                             Backend                                                             |                                               Backend<br/>Frontend                                                |                              Backend<br/>Frontend                              |
|                                           [@DaeunKim9](https://github.com/DaeunKim9)                                            |                                        [@naku2](https://github.com/naku2)                                         |                     [@chy0503](https://github.com/chy0503)                     |

<br>

## Acknowledgement
```
“This work was carried out as part of the SW Professional Talent Development Project funded by the Ministry of Science and ICT (MSIT) and the Institute of Information & Communications Technology Planning & Evaluation (IITP) (2022-0-01127).”```
