# 📊 Stockly

<div align="center">
    <img src="https://github.com/user-attachments/assets/93042c12-4dbe-40ed-812e-cf2ff8d1b761" alt="banner" width="600" height="auto">
</div>


# 📚Table of Contents
- [Introduction](#-Introduction)
- [WEB Demo](#-APP-Demo)
- [APP Demo](#-APP-Demo)
- [System Architechture](#-System-Architechture)
- [Tech stack](#-Tech-stack)
- [Swagger](#-Swagger)
- [Kafka Workflows](#-Kafka-Workflows)
- [Directory Structure](#-Directory-Structure)
- [Environment](#-Environment)
- [How to Start](#-How-to-Start)
- [Monitoring](#-Monitoring)

# 👩‍💻 Introduction
## EPH(Elevator Pitch Framework)
- STOCKLY는 주식 투자에 관심이 있지만 시작을 어려워 하는 개인들에게 실전에 가까운 투자 경험과 위험 없는 투자 학습 환경을 제공한다. 더불어 우리는 사용자의 자산을 시각화하여 편리한 자산관리를 돕는다.

## 기획서
[STOCKLY 기획서.pdf](https://github.com/user-attachments/files/18055099/STOCKLY.pdf)

## 요구사항 정의서
https://docs.google.com/spreadsheets/d/19aW18ExV1BCzs6UfrxL9yfCzEoTpt5gRazA9k0vFh2s/edit?gid=211065193#gid=211065193

## 기능 명세서
https://docs.google.com/spreadsheets/d/1AiwZ3q3cILC9flWU6uRUhQqEs2Dz1rtel5Zh-Gp1QXU/edit?gid=0#gid=0

## 프로세스 명세서(액티비티 다이어그램)
https://drive.google.com/file/d/1RCKO13ue1S7Rjw33bm4f2IzVcdGs1_K7/view

## 연동 정의서 
https://docs.google.com/spreadsheets/d/1U215_Mel70mujcQGGkk4Bi_EC_e49PN1USf27GLKk7c/edit?gid=785057080#gid=785057080

# 🌈 WEB DEMO


  <table>
    <tr>
      <th>온보딩 페이지</th>
      <th>회원가입/로그인 페이지</th>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/c51aa558-18d5-41ca-8764-ea820eb450bd" width="475">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/d11aa254-d70f-4b10-82ac-38626ed2946e" width="475">
      </td>
    </tr>
    <tr>
      <th>메인 주식 차트 페이지</th>
      <th>주식 상세 페이지</th>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/358fb2e5-085c-43a4-b4fe-f82e33d86328" width="475">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/d11aa254-d70f-4b10-82ac-38626ed2946e" width="475">
      </td>
    </tr>
    <tr>
      <th>알림 페이지</th>
      <th>마이 페이지</th>
    </tr>
    <tr>
      <td>
        <img src="https://github.com/user-attachments/assets/358fb2e5-085c-43a4-b4fe-f82e33d86328" width="475">
      </td>
      <td>
        <img src="https://github.com/user-attachments/assets/d11aa254-d70f-4b10-82ac-38626ed2946e" width="475">
      </td>
    </tr>
  </table>






# 🌈 APP DEMO


# ⚙ System Architecture

# 🛠 Tech Stack
<br>
<div align="left">

분야| 사용 기술|
:--------:|:------------------------------:|
**Fronted** | <img src="https://techstack-generator.vercel.app/react-icon.svg" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://techstack-generator.vercel.app/ts-icon.svg" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/3f4dc890-11fa-4761-97ca-63a588fb7ee8" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**APP** | 
**Backend** | <img src="https://techstack-generator.vercel.app/restapi-icon.svg" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/2e4e3521-df04-4934-a236-dc52df8b4f28" width="60" height="60"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://techstack-generator.vercel.app/python-icon.svg" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://techstack-generator.vercel.app/mysql-icon.svg" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/b4cb23f8-69d7-461e-9c95-89713ea2a2a5" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/f14de573-f552-4d1d-b6f2-ed63faa49693" width="70" height="70"/> 
**DevOps** | <img src="https://techstack-generator.vercel.app/kubernetes-icon.svg" width="70" height="70" style="vertical-align: middle;"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="https://github.com/user-attachments/assets/3feef2da-8845-4c62-ae5b-d6508a79be21" height="60"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/d17e8051-0244-473f-8e36-130808d56c27" width="70" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/73b7273b-086d-4916-a0dc-db5ee8055b8a" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/e1c6b019-447b-4356-ab02-ff101479bf4e" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
**Monitoring** | 
**etc** | <img src="https://github.com/user-attachments/assets/cecfad68-e740-4c8c-8e11-dd5c2d43b885" height="60"/>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/d19733ef-9071-4e6d-b31f-18da406e0690" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/0c8e87e3-8453-4b5b-9ca0-dccf94e67cc0" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/d4c9686b-38fb-47d3-be78-09e5b6b7c825" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="https://github.com/user-attachments/assets/29a7e4e4-f8c7-4dd1-ab32-1fcb55a41292" height="70"/> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
</div>





# 💾 ERD

<img src="https://github.com/user-attachments/assets/cf0d1092-ac1e-4cbd-b8aa-686967497d11">

# <img src="https://github.com/user-attachments/assets/b043ab14-fb35-4e59-b26c-6f6c31a613ad" alt="Swagger icon" width="28"/> Swagger
## 주식 차트 알림 Producer
<img width="1462" alt="image" src="https://github.com/user-attachments/assets/275bd32a-b38f-4201-ba67-429f6f5cb640">

## 주식 차트, 알림 Consumer
<img width="1468" alt="image" src="https://github.com/user-attachments/assets/2778e07e-d3ec-40ce-b407-51366d1546c8">

## 모의투자 Consumer Server
<img width="1491" alt="image" src="https://github.com/user-attachments/assets/671b68ba-862a-453d-b560-3d256db3acfa">


# ⚙ Kafka Workflows
## 주식 차트 기능
<img src="https://github.com/user-attachments/assets/0d782f3b-4a5e-4fd8-a71c-7dbe81d6f82c">

## 알림 기능
<img src="https://github.com/user-attachments/assets/86c698b2-af5f-4c5a-9437-b5b6e83e7627">

# 📂 Directory Structure

# <img src="https://github.com/user-attachments/assets/6f430ebb-b28d-4898-9295-bb7f0b0aa785" alt=".ENV icon" width="24"/> Environment
* backend/.env
```
MYSQL_ROOT_PASSWORD=
MYSQL_DATABASE=
MYSQL_USER=
MYSQL_PASSWORD=
MYSQL_HOST=

REDIS_URL=

# 한국 투자 증권 앱 키 
APP_KEY=
APP_SECRET=
SSE_KEY=
SSE_SECRET=
HOGA_KEY=
HOGA_SECRET=

```

# 🚀 How to Start
## backend
```
# Docker Desktop 실행 -> Settings -> Kubernetes -> Enable Kubernetes

# Kubernetes, helm 설치 
brew install kubectl
brew install helm

# 트래픽 활성화
helm repo add traefik https://helm.traefik.io/traefik
helm repo update
helm install traefik traefik/traefik --namespace kube-system --set "dashboard.enabled=true" --set "service.type=LoadBalancer"

# 로컬에서 트래픽 사용을 위한 설정
sudo nano /etc/hosts

127.0.0.1   localhost.stock-service
127.0.0.1   localhost.stock-server
127.0.0.1   localhost.order-service
127.0.0.1   traefik.internal

127.0.0.1   localhost.traefik
127.0.0.1   localhost.kafka
127.0.0.1   localhost.zookeeper
127.0.0.1   localhost.argocd

# 위의 내용을 복사, 붙여넣기 후 저장 

# 네임스페이스 생성
kubectl create namespace stockly
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

# argoCD 실행
kubectl apply -f argoCD/app.yaml

# argoCD 접속
kubectl port-forward svc/argocd-server -n argocd 8080:443
kubectl -n argocd get secret argocd-initial-admin-secret -o jsonpath="{.data.password}" | base64 -d; echo # 비밀번호 화인 명령어(아이디는 Admin)

```

# 💡 Monitoring
