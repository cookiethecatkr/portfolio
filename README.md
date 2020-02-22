# **Jin's Portfolio** 
Jin's Stackoverflow :  https://stackoverflow.com/users/10504469/jin-lee

## Education
- 자바(Java) 개발자 과정 수료 (800시간)
- 컴퓨터과학 학사
- 컴퓨터과학(정보과학) 석사

## Certification
- 토익만점(990점) 3회
- 정보처리 기사
- 정보보안 기사 필기 합격(2019)
- 아파치 카프카 개발자 자격증 (CCDAK)
- Microsoft 클라우드 자격증 (AZ-900) 

## Project (2019. 01 ~ 2020. 02)
**아래 프로젝트는 모두 혼자서 설계/구축/운영함.**
1. ELKK 모니터링 시스템 
   - LDAP 서버의 로그 파일과 메트릭 정보를 수집하여 카프카로 보내고 로그스태시에서 필터/가공하여 엘라스틱서치에 저장 후 키바나로 시각화 
   - 사용 스택 : Filebeat, Metricbeat, Kafka, Zookeeper, Logstash, Elasticsearch, Kibana
2. APM (애플리케이션 성능 모니터링) / SIEM (보안관제 시스템) 
   - APM agent를 설치하여 정보를 수집하여 APM 서버로 보낸 후 엘라스틱서치에 저장하여 키바나에서 시각화
   - 호스트 기반과 네트워크 기반의 데이터를 수집하여 키바나의 SIEM UI로 모니터링 (Auditbeat, Packetbeat 사용) 
3. Kubernetes 
   - 쿠버네티스에서 헬름차트를 이용해 카프카 서버 3대, 주키퍼 서버 3대 구축 후 운영 
   - 여러 헬름차트를 이용해 다양한 서비스를 테스트 
4. AWS & Azure
   - 클라우드 상에서 엘라스틱서치와 카프카를 프로덕션 레벨의 클러스터로 구축 
   - Devops (CI/CD) 도구들 분석 및 테스트 (개발 생산성 향상을 위해)
5. Docker image 빌드 연구
   - 기존의 monolithic한 회사 애플리케이션을 마이크로서비스화 한 뒤 컨테이너화 하기 위해서. 
