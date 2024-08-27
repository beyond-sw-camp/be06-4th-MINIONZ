![IMG_8019](https://github.com/user-attachments/assets/30cc279e-a4c1-47e0-b59c-8e855987c92c)


# 👀 팀원 구성

팀장: 차윤슬 <br>
팀원: 박성준, 최승은, 강혜정, 지연희

---

|                     **차윤슬**                      |                  **박성준**                   |                 **최승은**                  |                     **강혜정**                     |             **지연희**              |
|:------------------------------------------------:|:------------------------------------------:|:----------------------------------------:|:-----------------------------------------------:|:--------------------------------:|
| <img src="https://soopool.art/img/infoacna/i/Judy/192px-Judy's_Poster_NH_Texture.png" width="128px"/> | <img src="https://soopool.art/img/infoacna/i/Ace/128px-Ace's_Poster_NH_Texture.png"/> | <img src="https://soopool.art/img/infoacna/i/Rio/128px-Rio's_Poster_NH_Texture.png"/> | <img src="https://soopool.art/img/infoacna/i/Felicity/128px-Felicity's_Poster_NH_Texture.png"/> | <img src="https://soopool.art/img/infoacna/i/Rosie/128px-Rosie's_Poster_NH_Texture.png"/> |
| [@yunseul-dev](https://github.com/yunseul-dev) | [@seongxun](https://github.com/seongxun) | [@xeunnie](https://github.com/xeunnie) | [ @hyejeung](https://github.com/hyejeung) | [@Aqulog](https://github.com/Aqulog) |



<br/>

# 🌟 프로젝트 목표

빠른 개발 속도와 품질 향상

---
	1. 개발 속도 향상
       CI/CD를 통해 개발자들이 코드를 더욱 빠르게 통합하고 배포할 수 있습니다. 자동화된 프로세스로 인해 통합과 배포가 간소화되어 전체 개발 주기가 단축됩니다.
	2. 자동화된 프로세스:
       빌드, 테스트, 배포 등 반복적인 작업을 자동화하여 개발자는 코드 작성에 더 많은 시간을 투자할 수 있습니다. 이는 생산성 향상으로 이어지며, 실수 발생 가능성을 줄입니다.
	3. 반복 작업의 최소화:
       소스 코드 통합 시 수작업을 줄이고, 자동화된 테스트와 무중단 배포, 이전 버전으로의 롤백 등 불필요한 반복 작업을 최소화합니다. 이를 통해 개발 효율성을 극대화하고 오류를 방지할 수 있습니다.
	4. 지속적인 품질 관리:
       CI/CD를 통해 개발 주기 내내 지속적으로 코드 품질을 유지하고 관리할 수 있습니다. 자동화된 테스트와 배포로 안정적인 운영 환경을 유지하며, 문제 발생 시 신속한 대응이 가능합니다.

# ⚒️ 기술 스택

---

### CI/CD

<img src="https://img.shields.io/badge/Git-000?style=style&logo=Git&logoColor=F05032&color=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=GitHub&logoColor=black&color=white"> <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=D24939&color=white"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=Docker&logoColor=2496ed&color=white"/><img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=Kubernetes&logoColor=326ce5&color=white"/>

### 모니터링
<img src="https://img.shields.io/badge/Prometheus-181717?style=flat&logo=Prometheus&logoColor=E6522C&color=white"> <img src="https://img.shields.io/badge/Grafana-181717?style=flat&logo=Grafana&logoColor=F46800&color=white">

### 웹 애플리케이션 프로그램
<img src="https://img.shields.io/badge/Vue-181717?style=flat&logo=Vue.js&logoColor=4FC08D&color=white"> <img src="https://img.shields.io/badge/SpringBoot-181717?style=flat&logo=SpringBoot&logoColor=6DB33F&color=white">

<br>
<br>

# 🌏 Devops 운영 환경

---

### Kubernetes 클러스터 노드 구성
💻 Master 1대, 💻 Worker 4대의 클러스터 구성<br>
➡️ 이 구조를 통해 운영 환경에서의 일관성과 안정성을 유지하면서도 개발 프로세스의 효율성을 크게 높였습니다.

### 기대효과
    • 안정적인 프라이빗 클라우드 운영:
      Kubernetes는 프라이빗 클라우드 인프라에서 안정적으로 실행될 수 있는 기능을 제공합니다. 이를 통해 서비스가 안정적으로 운영되며, 개발 및 배포 과정이 더욱 효율적으로 진행되었습니다.
	• 클러스터 구성:
      클러스터는 마스터 노드 1대와 워커 노드 4대로 구성되었습니다. 이러한 구성은 안정적이고 확장 가능한 서비스 운영을 가능하게 하였습니다.
<details>
    <summary>
<span style="font-size:150%"> k8s 전체 서비스 아키텍쳐 </span></summary>
</br>


<p align="center">
	
![시퀀스 다이어그램 - 1페이지 (2)](https://github.com/user-attachments/assets/315c3b76-cb4d-4df4-a9c8-46f108bfd8ee)

</details>
<details>
    <summary>
<span style="font-size:150%"> k8s 내부 서비스 아키텍쳐 </span></summary>
</br>


<p align="center">

![시퀀스 다이어그램 - 1페이지 (1)](https://github.com/user-attachments/assets/644d96a7-c35c-4cc9-bdc7-e0f1cc76eef4)

</details>
<br>
<br>

# CI/CD 시나리오

GitHub, Jenkins, Docker, Kubernetes를 활용하여 프론트엔드와 백엔드 애플리케이션을 각각 자동화하는 과정의 시나리오입니다.

---

### CI/CD 시나리오

#### 1. 프로젝트 개요
프론트엔드(Vue)와 백엔드(SpringBoot)로 구성된 웹 애플리케이션입니다.
GitHub에 호스팅되며, CI/CD 파이프라인을 통해 자동으로 빌드, 테스트, Docker 이미지 생성 및 Kubernetes 클러스터로의 배포가 이루어집니다.
CI/CD 파이프라인은 Jenkins를 통해 프론트와 백엔드 각각 관리되며, 모든 빌드와 배포 과정은 Docker와 Kubernetes를 사용해 자동화됩니다.

#### 2. CI/CD 파이프라인 개요
CI/CD 파이프라인은 GitHub 저장소에 `feature` 단위의 `merge`를 받은 `backend`, `front` 두 브랜치 각각에 연동됩니다.
두 브랜치에 `push`라는 이벤트가 발생할 때마다 자동으로 트리거됩니다.
프론트엔드와 백엔드는 각각의 Jenkins 파이프라인에 의해 처리되며, Docker 이미지를 생성하여 Kubernetes 클러스터에 배포합니다.

파이프라인은 다음과 같은 주요 단계로 구성됩니다.

#### 3. CI/CD 파이프라인 단계

##### 1) GitHub 웹훅 트리거
- **상황**: GitHub의  코드를 푸시하거나 Pull Request(PR)를 생성합니다.
- **결과**: GitHub에서 설정된 웹훅을 통해 Jenkins 서버로 이벤트가 전달됩니다. Jenkins는 이 이벤트를 감지하고 해당 프로젝트의 파이프라인을 트리거합니다.

##### 2) 코드 체크아웃
- **상황**: Jenkins 파이프라인이 시작되면, 첫 번째 단계로 GitHub 저장소에서 최신 코드를 가져옵니다.
- **결과**: 프론트엔드와 백엔드 각각에 대해 코드가 Jenkins 워크스페이스로 체크아웃됩니다.

##### 3) 빌드 및 테스트
- **프론트엔드**:
    - **상황**: Jenkins는 Node.js 환경에서 `npm install`을 실행하여 필요한 의존성을 설치한 후, `npm run build` 명령어를 사용해 빌드합니다.

- **백엔드**:
    - **상황**: Jenkins는 Gradle을 사용해 백엔드 애플리케이션을 빌드합니다.

##### 4) Docker 이미지 빌드 및 푸시
- **상황**: 빌드가 완료된 후, Jenkins는 Docker 이미지를 생성합니다. Dockerfile을 기반으로 각각의 애플리케이션(프론트엔드, 백엔드)에 대해 이미지를 빌드합니다.
- **결과**: 빌드된 Docker 이미지는 지정된 Docker Hub로 푸시됩니다. 이때 각 이미지의 tage name은 Jenkins 빌드 횟수를 기준으로 지정됩니다.

##### 5) Kubernetes 배포
- **상황**:  Jenkins는 Kubernetes 클러스터에 해당 이미지를 배포합니다. 각 파이프라인은 Kubernetes YAML 파일(`k8s-frontend.yml`, `k8s-backend.yml`)을 사용해 Deployment와 Service를 정의합니다.
- **결과**: Kubernetes 클러스터에서 새로운 버전의 애플리케이션이 배포되며 최신 이미지를 가져옵니다.

##### 6) 모니터링 및 피드백
- **상황**: 배포가 완료된 후, Jenkins는 모니터링 도구로 Prometheus, Grafana를 사용해 애플리케이션 상태를 확인하고, Slack 또는 이메일을 통해 개발자에게 피드백을 제공합니다.
- **결과**: 애플리케이션이 정상적으로 배포되었는지 확인하고, 문제가 있을 경우 즉시 알림을 받아 대응할 수 있습니다.

<br>
<br>
