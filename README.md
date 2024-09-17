## Jenkins Pipeline

- 클라우드 환경의 모놀로틱 아키텍쳐에서 ECS(Fargate) & Beanstalk(Container) 기반으로 아키텍쳐 마이그레이션으로 인한 Jenkins를 활용한 배포 파이프라인 마이그레이션 과정을 기록한다.

- 실습은 빌드 파일을 특정 저장소 (S3, code commit(repository))에 저장후에 Agent에서 가져와서 배포하는 방식과 ECR에 이미지 배포후 Agent에서 가져오는 형식 크게 2가지 방식으로 진행한다.