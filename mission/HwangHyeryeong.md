### 1. 컨테이너 기술이란 무엇입니까? (100자 이내로 요약)
실행에 필요한 모든 파일을 포함한 전체 runtime 환경에서 애플리케이션을 패키징하고 격리할 수 있는 기술이다. 컨테이너는 환경까지 모두 포함하여 독립적으로 프로그램을 실행할 수 있도록 돕는다. 이를 통해 전체 기능을 유지하면서 컨테이너화된 애플리케이션을 환경(개발, 테스트, 프로덕션 등) 간 쉽게 이동할 수 있다.

(참고자료: https://www.redhat.com/ko/topics/containers)

<hr>

### 2. 도커란 무엇입니까? (100자 이내로 요약)
도커는 리눅스의 응용 프로그램들을 소프트웨어 컨테이너 안에 배치시키는 일을 자동화하기 위해 시작된 오픈소스 프로젝트이다. 애플리케이션을 신속하게 구축, 테스트, 배포할 수 있는 소프트웨어 플랫폼이다. 컨테이너를 이용해 소프트웨어를 컨테이너 유닛으로 알아서 패키징 해주며, 환경에 구애받지 않고 애플리케이션을 신속하게 배포 및 확장할 수 있다.

(참고자료: https://www.redhat.com/ko/topics/containers/what-is-docker)

<hr>

### 3. 도커 파일, 도커 이미지, 도커 컨테이너의 개념은 무엇이고, 서로 어떤 관계입니까?

**도커 파일**은 도커가 어떻게 이미지를 만들지 이해하도록 적은 파일이다. 도커 파일에 이비지를 어떻게 찍을지 작성하면, 도커가 그것을 읽고 이미지를 생성한다.

**이미지**는 컨테이너를 생성하기 위해 필요한 설계도이다. 도커는 이미지를 보고 컨테이너를 생성한다.

**도커 컨테이너**는 도커 파일을 기반으로 도커 이미지를 만들고, 빌드된 도커 이미지를 인스턴스화하여 실행한 것이다. 가상화된 공간을 생성하기 위해 리눅스 자체 기능인 chroot, 네임스페이스 cgroup을 사용함으로써 프로세스 단위의 격리 환경을 만들기 때문에 성능 손실이 없다.

<hr>

### 4. [실전 미션] 도커 설치하기 (참조: 도커 공식 설치 페이지)
빌드 완료
![image](https://github.com/HwangHyeryeong/docker-pro-2312/assets/75305711/9779f7c8-2693-4ad2-a84a-e0c729192b70)

실행 완료<br>
![image](https://github.com/HwangHyeryeong/docker-pro-2312/assets/75305711/c3ed0200-d296-417b-86c6-fc8d1c021785)
