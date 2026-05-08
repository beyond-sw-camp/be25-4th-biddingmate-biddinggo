# BiddingGo 

<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/1e36c230-8248-44f6-b5f0-971a78c39e9b" width="300"/>
</p>

<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/e839d356-1bb6-477b-a87f-feeed40d6e67"  width="1200"/>
</p>


# Bidding mate

<table>
  
  <tr>
    <th>김진혁</th>
    <th>박선우</th>
    <th>윤정윤</th>
    <th>이민경</th>
    <th>이애은</th>
    <th>한규진
  </tr>
  
  <tr>
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="김진혁" src="https://github.com/user-attachments/assets/d44abc12-4269-4be2-a6a9-f76a531a963f" /></td>
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="박선우" src="https://github.com/user-attachments/assets/cf47d2b7-7633-4f17-8cbe-8b6429ceef67" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="윤정윤" src="https://github.com/user-attachments/assets/5cde1533-77e1-4783-8ce9-d48ec236c25d" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="이민경" src="https://github.com/user-attachments/assets/f62ebf05-846f-462e-b4d3-3fa3c58ce4fb" /></td>  
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="이애은" src="https://github.com/user-attachments/assets/79be4278-e3e9-44c5-af71-57d1831e9406" /></td>   
    <td align="center"><img width="150" height="210" style="object-fit: cover;" alt="한규진" src="https://github.com/user-attachments/assets/45b114ef-0e30-4bcc-94d2-dfd548aa9b7c" /></td>  
  </tr>

  <tr>
    <td align="center">
      <a href="https://github.com/jin605"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td> 
    <td align="center">
      <a href="https://github.com/melly8954"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/penep0"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/alskung1101"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/nueeaeel"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
    <td align="center">
      <a href="https://github.com/softworldqjin"><img src="https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logoColor=white" /></a>
    </td>
  </tr>
</table>
    
---


# 목차
<br/>

1. [프로젝트 개요](#1--프로젝트-개요)
2. [시스템 아키텍처](#2--시스템-아키텍처)
3. [CICD 파이프라인](#3--CICD-파이프라인)
4. [시현](#4--시현)
5. [회고](#5--회고)

<br/>

---


# 1.  프로젝트 개요
<br/> 

## 📍 프로젝트 소개
**Biddinggo는 실시간 경매 기반의 중고 및 리셀 거래 플랫폼입니다.**  
사용자는 상품을 등록하고 다양한 경매 방식(일반 경매, 연장 경매, 타임딜 등)을 통해 판매할 수 있으며, 구매자는 실시간 입찰을 통해 원하는 상품을 경쟁적으로 구매할 수 있습니다.  

또한, 실시간 알림(SSE) 기반으로 입찰 상황을 즉시 반영하여 사용자에게 몰입감 있는 거래 경험을 제공합니다.  
특히, **빅크리 경매(Vickrey Auction, 2등 가격 경매)** 방식을 도입하여 보다 공정하고 전략적인 가격 형성을 지원합니다.

---

## 📍 배경 (이 서비스가 필요한 이유)

### 1. 기존 중고 거래 플랫폼의 가격 결정 한계
- 번개장터, 당근마켓 등은 정가 기반 거래로 적정 가격 형성이 어려움  
- 협상 과정이 비효율적이며 사용자 경험 저하  

### 2. 리셀 시장 성장과 공정한 거래 필요성 증가
- 한정판 및 인기 상품은 가격 변동성이 큼  
- 경매 방식이 가장 합리적인 가격 형성 구조지만 지원 플랫폼이 제한적  

### 3. 기존 경매 플랫폼의 UX 및 기능 한계
- UI/UX가 직관적이지 않고 사용성이 떨어짐  
- 실시간 입찰 경험 부족 및 시스템 반응 속도 문제  

---

## 📍 기존 서비스와의 차별점

### 📌 기존 서비스

#### KREAM
- 패션/스니커즈 특화 플랫폼  
- 모든 거래에 검수 필수 → 거래 속도 느림  
- 경매 방식이 아닌 호가 기반 거래  

#### 코베이옥션
- 전통적인 경매 플랫폼  
- UI/UX가 올드하고 접근성이 낮음  
- 실시간성 및 사용자 경험 부족  

---

### ✅ Biddinggo의 차별점

#### 1. 빅크리(Vickrey) 기반 경매 시스템
- 최고 입찰자가 낙찰되지만, 실제 결제 금액은 두 번째로 높은 입찰가로 결정  
- 과도한 가격 경쟁 방지  
- 사용자가 자신의 최대 지불 의사를 정직하게 반영하도록 유도  

#### 2. AI 기반 상품 예측가 제공
- 과거 거래 데이터 및 유사 상품 데이터를 기반으로 적정 가격 제시  
- 판매자/구매자 모두 합리적인 의사결정 가능  

#### 3. AI 기반 유사 상품 검색
- 이미지 및 텍스트 기반 유사도 분석  
- 검색 효율 및 사용자 경험 향상  

#### 4. 다양한 경매 옵션 제공
- 연장 경매 (마감 직전 입찰 시 자동 연장)  
- 타임딜 경매 (짧은 시간 집중 경쟁)  
- 검수 경매 (신뢰 기반 거래)  

#### 5. 실시간 입찰 시스템 (SSE 기반)
- 입찰 상태 및 알림을 실시간 반영  
- 사용자 간 경쟁 상황을 즉각적으로 체감 가능  

#### 6. 100% 에스크로 기반 안전 거래
- 거래 금액을 중간 보관 후 완료 시 정산  
- 구매자/판매자 자산 보호  

#### 7. 현대적인 UI/UX
- 직관적인 경매 흐름 제공  
- 기존 경매 서비스 대비 사용성 개선  

---

## 📍 기대 효과

- **합리적인 가격 형성**
  - 빅크리 경매 구조를 통한 공정한 시장 가격 결정  

- **거래 신뢰도 향상**
  - 에스크로 + 검수 옵션 기반 안전 거래 환경  

- **사용자 참여도 증가**
  - 실시간 입찰 및 알림으로 몰입도 상승  

- **판매 효율 극대화**
  - 다양한 경매 옵션을 통한 유연한 판매 전략  

- **플랫폼 경쟁력 확보**
  - AI + 실시간 시스템 + 경매 구조 결합
<br/>

---

# 2.  시스템 아키텍처
<br/>
<img width="1235" height="1134" alt="Image" src="https://github.com/user-attachments/assets/96d61b52-ec98-406d-bae5-0f93b300c47b" />

<br/>

---

# 3.  CICD 파이프라인
<br/>

<details><summary>통합 관리 Jenkins 파이프라인</summary>
<br/>
<img width="1123" height="446" alt="Image" src="https://github.com/user-attachments/assets/6bb90a71-f81b-4b24-b9d6-31646931829a" />
<br/>
  
```
pipeline {
  agent any

  environment {
    FRONTEND_JOB = 'biddinggo-frontend'
    BACKEND_JOB = 'biddinggo-backend'
  }

  stages {
    stage('Check CI Skip') {
      steps {
        script {
          def skipStatus = sh(script: 'git rev-parse --is-inside-work-tree >/dev/null 2>&1 && git log -1 --pretty=%B | grep -q "\\[skip ci\\]"', returnStatus: true)
          env.SKIP_PIPELINE = skipStatus == 0 ? 'true' : 'false'
          if (env.SKIP_PIPELINE == 'true') {
              env.SKIP_REASON = 'latest commit contains [skip ci]'
              echo 'Skipping build because the latest commit contains [skip ci].'
          }
        }
      }
    }

    stage('Detect Changed Areas') {
      when {
        expression { env.SKIP_PIPELINE != 'true' }
      }
      steps {
        script {
          def baseCommit = env.GIT_PREVIOUS_SUCCESSFUL_COMMIT ?: env.GIT_PREVIOUS_COMMIT
          def changedText = ''

          if (baseCommit?.trim() && sh(script: "git cat-file -e ${baseCommit}^{commit}", returnStatus: true) == 0) {
            changedText = sh(script: "git diff --name-only ${baseCommit} HEAD", returnStdout: true).trim()
          } else {
            changedText = sh(script: "git show --name-only --pretty=format:'' HEAD", returnStdout: true).trim()
          }

          def changedFiles = changedText ? changedText.split('\n').findAll { it } : []

          env.FRONTEND_CHANGED = changedFiles.any { it.startsWith('infra/k8s/frontend/') }.toString()
          env.BACKEND_CHANGED = changedFiles.any { it.startsWith('infra/k8s/backend/') }.toString()

          echo "Changed files:\n${changedFiles.join('\n')}"
          echo "Frontend changed: ${env.FRONTEND_CHANGED}"
          echo "Backend changed: ${env.BACKEND_CHANGED}"
        }
      }
    }

    stage('Trigger Build Jobs') {
      when {
        expression { env.SKIP_PIPELINE != 'true' }
      }
      steps {
        script {
          if (env.FRONTEND_CHANGED == 'true') {
            echo "Triggering frontend job: ${env.FRONTEND_JOB}"
            def frontendBuild = build job: env.FRONTEND_JOB, wait: true
            env.FRONTEND_BUILD_NUMBER = frontendBuild.number.toString()
          }

          if (env.BACKEND_CHANGED == 'true') {
            echo "Triggering backend job: ${env.BACKEND_JOB}"
            def backendBuild = build job: env.BACKEND_JOB, wait: true
            env.BACKEND_BUILD_NUMBER = backendBuild.number.toString()
          }

          if (env.FRONTEND_CHANGED != 'true' && env.BACKEND_CHANGED != 'true') {
            echo 'No frontend/backend source changes detected. Nothing to trigger.'
          }
        }
      }
    }
  }

  post {
    success {
      script {
        if (env.SKIP_PIPELINE == 'true') {
          echo """
============================================================
  ⏭️  CI skipped
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  📝 Reason
    Message    : ${env.SKIP_REASON ?: 'latest commit contains [skip ci]'}

============================================================
"""
        } else {
          echo """
============================================================
  ✅ BiddingGo coordinator pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🚦 Trigger
    Frontend   : ${env.FRONTEND_CHANGED == 'true' ? env.FRONTEND_JOB : 'skipped'}
    Backend    : ${env.BACKEND_CHANGED == 'true' ? env.BACKEND_JOB : 'skipped'}

============================================================
"""
        }
      }
    }
    failure {
      echo """
============================================================
  ❌ BiddingGo coordinator pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}

```
<details><summary>파이프라인 상세</summary>
  Declarative: Checkout SCM : Jenkins가 GitHub 저장소를 자동 체크아웃 <br/>
  Check CI Skip : 최신 커밋 메시지에 [skip ci]가 있으면 파이프라인 스킵 <br/>
  Detect Changed Areas : 변경 파일을 기준으로 frontend/backend의 manifest 변경 여부 감지 <br/>
  Trigger Build Jobs : 변경된 영역의 하위 Jenkins Job을 순차 실행하고 빌드 번호 저장
  </details>  
  
</details>

<br/>

<details><summary>프론트엔드 Jenkins 파이프라인</summary>
<br/>
<img width="1127" height="440" alt="Image" src="https://github.com/user-attachments/assets/5c6c32db-d821-44ff-8f2c-358b3284f367" />
<br/>
  
```
pipeline {
  agent any

  options {
    disableConcurrentBuilds()
  }

  environment {
    GHCR_REGISTRY = 'ghcr.io'
    GHCR_OWNER = 'beyond-sw-camp'
    IMAGE_NAME = 'be25-3rd-biddingmate-biddinggo'
    GHCR_IMAGE_NAME = "${GHCR_REGISTRY}/${GHCR_OWNER}/${IMAGE_NAME}"

    CICD_REPO_URL = 'github.com/beyond-sw-camp/be25-4th-biddingmate-biddinggo.git'
    FRONTEND_DEPLOYMENT_MANIFEST = 'infra/k8s/frontend/deployment.yaml'

    VITE_API_BASE_URL = 'https://api.bidding-go.shop'
    VITE_TOSS_CLIENT_KEY = 'test_ck_4yKeq5bgrpPoPA0lxOkXrGX0lzW6'
  }

  stages {
    stage('Docker Build') {
      steps {
        script {
          env.IMAGE_TAG = "${env.BUILD_NUMBER}"
        }

        sh '''
          docker build --no-cache \
            --build-arg VITE_API_BASE_URL=$VITE_API_BASE_URL \
            --build-arg VITE_TOSS_CLIENT_KEY=$VITE_TOSS_CLIENT_KEY \
            -t $GHCR_IMAGE_NAME:$IMAGE_TAG \
            -t $GHCR_IMAGE_NAME:latest \
            .
        '''

        sh 'docker image inspect $GHCR_IMAGE_NAME:$IMAGE_TAG'
      }
    }

    stage('Push to GHCR') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            echo "$GITHUB_TOKEN" | docker login $GHCR_REGISTRY -u "$GITHUB_USER" --password-stdin
            docker push $GHCR_IMAGE_NAME:$IMAGE_TAG
            docker push $GHCR_IMAGE_NAME:latest
            docker logout $GHCR_REGISTRY
          '''
        }
      }
    }

    stage('Update Frontend Deployment') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            rm -rf cicd-repo
            git clone https://$GITHUB_USER:$GITHUB_TOKEN@$CICD_REPO_URL cicd-repo

            cd cicd-repo

            git config user.name "jenkins-bot"
            git config user.email "jenkins-bot@users.noreply.github.com"

            sed -i "s|image: .*|image: $GHCR_IMAGE_NAME:$IMAGE_TAG|" $FRONTEND_DEPLOYMENT_MANIFEST

            grep "image: $GHCR_IMAGE_NAME:$IMAGE_TAG" $FRONTEND_DEPLOYMENT_MANIFEST

            git diff -- $FRONTEND_DEPLOYMENT_MANIFEST
            git add $FRONTEND_DEPLOYMENT_MANIFEST
            git diff --cached --quiet && echo "No frontend image change." || git commit -m "ci: update frontend image to $IMAGE_TAG [skip ci]"
            git pull --rebase origin main
            git push origin main
          '''
        }
      }
    }
  }

  post {
    success {
      echo """
============================================================
  ✅ BiddingGo frontend pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🐳 Image
    Version    : ${env.GHCR_IMAGE_NAME}:${env.IMAGE_TAG}

============================================================
"""
    }

    failure {
      echo """
============================================================
  ❌ BiddingGo frontend pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}
```
<details><summary>파이프라인 상세</summary>
  Declarative: Checkout SCM : Jenkins가 GitHub 저장소를 자동 체크아웃 <br/>
  Docker Build : 프론트엔드 Docker 이미지를 Jenkins 빌드 번호 태그와 latest 태그로 빌드 <br/>
  Push to GHCR : 빌드된 프론트엔드 이미지를 GHCR에 push <br/>
  Update Frontend Deployment : Job 빌드 번호로 프론트엔드의 deployment.yaml 이미지 태그 수정 후 main에 push
</details>

</details>

<br/>

<details><summary>백엔드 Jenkins 파이프라인</summary>
<br/>
<img width="1121" height="442" alt="Image" src="https://github.com/user-attachments/assets/7b034184-27c5-470a-9f05-fa271e4390db" />
<br/>
  
```
pipeline {
  agent any

  options {
    disableConcurrentBuilds()
  }

  environment {
    GHCR_REGISTRY = 'ghcr.io'
    GHCR_OWNER = 'beyond-sw-camp'
    IMAGE_NAME = 'be25-2nd-biddingmate-biddinggo'
    GHCR_IMAGE_NAME = "${GHCR_REGISTRY}/${GHCR_OWNER}/${IMAGE_NAME}"

    CICD_REPO_URL = 'github.com/beyond-sw-camp/be25-4th-biddingmate-biddinggo.git'
    BACKEND_DEPLOYMENT_MANIFEST = 'infra/k8s/backend/deployment.yaml'
  }

  stages {
    stage('Docker Build') {
      steps {
        script {
          env.IMAGE_TAG = "${env.BUILD_NUMBER}"
        }

        sh '''
          docker build --no-cache \
            -t $GHCR_IMAGE_NAME:$IMAGE_TAG \
            -t $GHCR_IMAGE_NAME:latest \
            .
        '''

        sh 'docker image inspect $GHCR_IMAGE_NAME:$IMAGE_TAG'
      }
    }

    stage('Push to GHCR') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            echo "$GITHUB_TOKEN" | docker login $GHCR_REGISTRY -u "$GITHUB_USER" --password-stdin
            docker push $GHCR_IMAGE_NAME:$IMAGE_TAG
            docker push $GHCR_IMAGE_NAME:latest
            docker logout $GHCR_REGISTRY
          '''
        }
      }
    }

    stage('Update Backend Deployment') {
      steps {
        withCredentials([usernamePassword(credentialsId: 'github-token', usernameVariable: 'GITHUB_USER', passwordVariable: 'GITHUB_TOKEN')]) {
          sh '''
            rm -rf cicd-repo
            git clone https://$GITHUB_USER:$GITHUB_TOKEN@$CICD_REPO_URL cicd-repo

            cd cicd-repo

            git config user.name "jenkins-bot"
            git config user.email "jenkins-bot@users.noreply.github.com"

            echo "Before:"
            grep -n "image:" $BACKEND_DEPLOYMENT_MANIFEST

            sed -i "s|image: .*|image: $GHCR_IMAGE_NAME:$IMAGE_TAG|" $BACKEND_DEPLOYMENT_MANIFEST

            echo "After:"
            grep -n "$GHCR_IMAGE_NAME:$IMAGE_TAG" $BACKEND_DEPLOYMENT_MANIFEST

            git diff -- $BACKEND_DEPLOYMENT_MANIFEST
            git add $BACKEND_DEPLOYMENT_MANIFEST
            git diff --cached --quiet && echo "No backend image change." || git commit -m "ci: update backend image to $IMAGE_TAG [skip ci]"
            git pull --rebase origin main
            git push origin main
          '''
        }
      }
    }
  }

  post {
    success {
      echo """
============================================================
  ✅ BiddingGo backend pipeline succeeded
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🐳 Image
    Version    : ${env.GHCR_IMAGE_NAME}:${env.IMAGE_TAG}

============================================================
"""
    }

    failure {
      echo """
============================================================
  ❌ BiddingGo backend pipeline failed
============================================================

  🧭 Build
    Job        : ${env.JOB_NAME} #${env.BUILD_NUMBER}
    Duration   : ${currentBuild.durationString.replace(' and counting', '')}

  🔎 Debug
    Console    : ${env.BUILD_URL}console

============================================================
"""
    }
  }
}
```
<details><summary>파이프라인 상세</summary>
  Declarative: Checkout SCM : Jenkins가 GitHub 저장소를 자동 체크아웃 <br/>
  Docker Build : 백엔드 Docker 이미지를 Jenkins 빌드 번호 태그와 latest 태그로 빌드 <br/>
  Push to GHCR : 빌드된 백엔드 이미지를 GHCR에 push <br/>
  Update Frontend Deployment : Job 빌드 번호로 백엔드의 deployment.yaml 이미지 태그 수정 후 main에 push
</details>

</details>

---

# 4.  시연
<br/>

## 시나리오

<img width="1690" height="841" alt="Image" src="https://github.com/user-attachments/assets/566d743b-76c0-47d4-b212-ce2dcd0f451b" />
<br/>

1. Developer Push
    - 개발자가 코드를 수정하고 develop 브랜치에 push 합니다.

2. GitHub Webhook Trigger
    - GitHub Webhook이 Jenkins에 빌드 이벤트를 전달합니다.

3. Jenkins CI Pipeline
    - 최신 소스 코드를 checkout 합니다.
    - 애플리케이션 빌드 및 테스트를 수행합니다.
    - Docker 이미지를 생성합니다.
    - 생성된 이미지를 GHCR(GitHub Container Registry)에 Push 합니다.
    - Kubernetes Manifest의 이미지 태그를 최신 버전으로 변경합니다.

4. GitOps Manifest Update
    - 수정된 Kubernetes Manifest를 별도의 Manifest Repository(k8s/)에 Push 합니다.

5. Argo CD Sync Detection
    - Argo CD가 Manifest Repository 변경 사항을 감지합니다.

6. Kubernetes Deployment
    - 변경된 Manifest를 Kubernetes Cluster에 반영합니다.
    - Rolling Update 방식으로 무중단 배포를 수행합니다.

## 백엔드 
### 젠킨스 수행

📽️[ 백엔드 젠킨스 ](https://www.youtube.com/watch?v=8yNteZhcY50) 

<img width="1310" height="647" alt="Image" src="https://github.com/user-attachments/assets/8c411deb-4b74-4100-a17f-de567d52722b" />

### ArgoCD 배포

📽️[ 백엔드 ArgoCD ](https://www.youtube.com/watch?v=AGdeFLccURE)

<img width="1377" height="645" alt="Image" src="https://github.com/user-attachments/assets/bb3957e0-1e6d-4c8a-a2db-9a15f41dc6f0" />

### Manifests 결과

<img width="1907" height="876" alt="Image" src="https://github.com/user-attachments/assets/7d1f14ba-bc0d-4817-9f4a-18bb7c4f813b" />

<br/>

## 프론트
### 젠킨스 수행

📽️[ 프론트 젠킨스 ](https://youtu.be/bRz8vDVpGfo)

<img width="1240" height="617" alt="Image" src="https://github.com/user-attachments/assets/d7e409b2-1358-4b1a-bea4-0572d7c29440" />

### ArgoCD 배포

📽️[ 프론트엔드 ArgoCD ](https://youtu.be/EYA67qtOV-g)

<img width="1303" height="612" alt="Image" src="https://github.com/user-attachments/assets/f02b8098-34a3-4539-b46d-b3fca63f2bd3" />

### Manifests 결과

<img width="1918" height="956" alt="Image" src="https://github.com/user-attachments/assets/21a26651-5bf3-4905-ac68-7bf2eb10818e" />

<br/>

## 통합관리
### 젠킨스 수행

📽️[ 통합관리 젠킨스 ](https://youtu.be/LRn-8iS_6QM)

<img width="1235" height="611" alt="Image" src="https://github.com/user-attachments/assets/9d0f36a4-c56c-406e-8cdd-546b11510710" />

### ArgoCD 배포

📽️[ 통합관리 ArgoCD ](https://youtu.be/4KkbAsrXCrM)

<img width="1293" height="612" alt="Image" src="https://github.com/user-attachments/assets/ae486f21-ada4-4059-bf47-4afcad909ec0" />

---

<br/>

# 5.  회고

#### 김진혁
> Jenkins와 ArgoCD를 활용해 CI/CD 파이프라인을 구축하며 도구의 설정보다 전체적인 흐름을 이해하는 데 집중했습니다. 설정이 복잡한 도구 특성상 특정 인원에게 기술이 편중되는 것을 막기 위해, 팀원 모두가 각자의 코드로 파이프라인을 직접 구축하고 발표하는 시간을 가졌습니다. 이 과정을 통해 파이프라인 전반의 데이터 흐름을 팀 전체가 명확히 동기화하고 유기적인 협업 환경을 만들 수 있었습니다.
쿠버네티스 도입 과정에서는 Ingress와 Service, Pod로 이어지는 네트워크 라우팅 구조를 파악하는 것이 가장 큰 과제였습니다. 외부 트래픽이 각 컴포넌트를 거쳐 내부 서비스까지 도달하는 경로를 추적하며 생소했던 쿠버네티스 네트워킹 메커니즘을 익혔습니다. 단순히 설정 파일을 작성하는 것을 넘어 전체적인 시스템 아키텍처 내에서 데이터가 어떻게 이동하는지 시각화하며 설계 역량을 쌓았습니다.
운영 면에서는 쿠버네티스의 높은 자원 점유율로 인해 서버가 빈번히 다운되는 물리적 한계에 부딪혔습니다. 이를 해결하기 위해 경량화된 K3s를 도입하고, Jenkins와 ArgoCD 같은 관리 도구와 애플리케이션 배포 환경을 별도의 서버로 분리하여 부하를 분산시켰습니다. 이러한 시행착오를 통해 한정된 자원 내에서 시스템 안정성을 확보하기 위한 리소스 관리의 중요성을 체감하며 지속 가능한 운영 방식을 고민해 볼 수 있었습니다.
 
#### 박선우
> 11

#### 윤정윤
> 이번 프로젝트에서는 기존에 사용하던 GitHub Actions 기반 CI/CD 환경에서 벗어나 Jenkins와 ArgoCD를 직접 구축하며 Kubernetes 기반 운영 환경을 구성해볼 수 있었습니다. 특히 ArgoCD가 Kubernetes API Server를 통해 실제 클러스터 상태를 관리하는 구조를 이해하면서, Kubernetes가 단순한 컨테이너 실행 도구가 아니라 원하는 상태를 유지하기 위한 시스템이라는 점이 인상 깊었습니다.
구축 과정에서 가장 크게 느낀 부분은 서버 자원 관리의 중요성이었습니다. 단일 서버 환경에서 Jenkins, ArgoCD, ingress-nginx, Database 등을 함께 운영하다 보니 작은 설정 충돌이나 리소스 부족만으로도 ingress 연결이 실패하거나 API timeout이 발생하는 상황이 자주 발생했습니다. 처음에는 단순히 설정 문제라고 생각했지만, 실제로는 여러 인프라 요소들이 동시에 자원을 사용하면서 발생하는 문제인 경우도 많았습니다. 이를 해결하는 과정에서 기능 구현만큼이나 현재 서버 상태를 확인하고, 어떤 프로세스가 어떤 역할을 하는지 이해하는 것이 중요하다는 점을 느낄 수 있었습니다.

#### 이민경
> 이번 프로젝트를 진행하며 가장 큰 벽이자 도전이었던 부분은 CI/CD 파이프라인 구축이었습니다. 내가 만든 서비스를 사용자들이 실제로 이용할 수 있다는 점은 흥미로웠지만 그 과정은 생각보다 훨씬 복잡하고 정교한 설계가 필요했습니다. 사실 처음에는 배포에 대해 아무것도 몰랐기에 Docker, Jenkins, Argo CD 같은 도구들을 왜 써야 하는지조차 이해하기 어려워 막막하기만 했습니다. 설정 하나만 어긋나도 실패 메시지가 뜨는 탓에 환경 설정이나 권한 문제, 네트워크 이슈로 배포가 막힐 때마다 한계를 느끼기도 했습니다. 하지만 계속되는 실패를 복구하며 로그를 뜯어보고 쿠버네티스의 동작 원리를 하나씩 파헤치다 보니 어느덧 배포의 흐름이 보이기 시작했습니다. 잦은 에러 덕분에 오히려 트러블슈팅 역량을 제대로 키울 수 있었던 것 같습니다. 무엇보다 팀원분들이 다들 열심히 하셔서 저 또한 포기하지 않고 끝까지 할 수 있었습니다. 이번에 배운 기술과 협업의 소중함을 발판 삼아서 앞으로 더 단단하게 성장하는 개발자가 되겠습니다. 고생 많으셨습니다!

#### 이애은
> 이번 프로젝트를 진행하며 가장 크게 느낀 점은, 인프라와 DevOps 영역은 단순히 배포를 자동화하는 기술이 아니라 서비스의 안정성과 운영 흐름 전체를 설계하는 과정이라는 점이었습니다.
처음에는 단순히 코드가 빌드되고 서버에 올라가는 과정 정도로 생각했지만, 직접 구축해보니 작은 구조 하나에도 수많은 고민이 필요했습니다. 예를 들어 어떤 방식으로 무중단 배포를 구성할지, 컨테이너와 클러스터를 어떻게 분리하고 관리할지, 배포 자동화 과정에서 장애가 발생하면 어떤 방식으로 복구할지 등 단순 구현을 넘어 운영 관점의 설계가 중요하다는 것을 체감했습니다.
특히 백엔드나 프론트엔드처럼 결과가 화면에 바로 보이는 영역과 달리, 눈에 보이지 않는 흐름 속에서 동작하기 때문에 전체 구조를 명확히 이해하지 못하면 작은 설정 하나만으로도 배포가 실패하거나 서비스가 중단될 수 있었습니다. 그 과정에서 단순히 기능을 구현하는 개발자가 아니라, 서비스가 안정적으로 운영될 수 있는 구조를 고민하는 시야가 중요하다는 점을 배울 수 있었습니다.

#### 한규진
> CI/CD를 처음 공부할 때는 단순히 “자동 배포” 정도로만 이해했습니다. 하지만 Jenkins, GitHub Webhook, Docker, Kubernetes, Argo CD를 직접 연결하면서 많은 문제를 겪었고, 그 과정에서 전체 흐름을 이해하는 것이 중요하다는 것을 깨달았습니다.
처음에는 GitHub에 push를 했는데 Jenkins가 동작하지 않는 문제가 있었습니다. 원인을 찾아보니 Webhook 설정과 ngrok 주소 변경 문제였습니다. 이 경험을 통해 GitHub → Webhook → Jenkins로 이어지는 이벤트 기반 구조를 이해하게 되었습니다.
또한 Docker 이미지를 새로 빌드했는데 Kubernetes에서는 이전 버전 컨테이너가 계속 실행되는 문제도 있었습니다. 원인은 deployment yaml의 이미지 태그가 변경되지 않았기 때문이었고, 이를 해결하기 위해 Jenkins가 k8s manifest의 이미지 버전을 수정하고 Git에 다시 push하도록 구성했습니다.
이 과정에서 Argo CD의 역할도 제대로 이해하게 되었습니다. 처음에는 Argo CD가 직접 컨테이너를 실행하는 줄 알았지만, 실제로 Pod를 생성하고 배포를 수행하는 것은 Kubernetes였습니다. Argo CD는 Git에 저장된 deployment yaml의 변경 사항을 감지하고, Desired State와 Live State를 비교해 차이가 발생하면 Kubernetes에 적용을 요청하는 역할이라는 점을 알게 되었습니다.



<br/>

