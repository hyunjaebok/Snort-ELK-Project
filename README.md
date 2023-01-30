# ELK를 이용한 웹 해킹 로그 패턴 분석과 시각화
     웹 해킹 종류 별 Snort Rull 작성 및 탐지
     ELK Stack으로 로그 저장 및 분석, 시각화
     
## 진행 기간
- 2021.12.29 ~ 2022.1.3

</br>

## 팀 구성
- 개발환경 구성 1명, Snort 구성 1명, ELK Stack 구성 1명

</br>

## 사용 기술
#### OS
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=Ubuntu&logoColor=white"> <!--Ubuntu-->
#### IDS
<img src="https://img.shields.io/badge/Snort-000000?style=flat-squarelogo=Snort&logoColor=white"> <!--Snort-->
#### Monitoring
<img src="https://img.shields.io/badge/Filebeat-005571?style=flat-square&logo=Filebeat&logoColor=white"> <!--Filebeat-->
<img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=Elasticsearch&logoColor=white"> <!--Elasticsearch-->
<img src="https://img.shields.io/badge/Logstash-005571?style=flat-square&logo=Logstash&logoColor=white"> <!--Logstash-->
<img src="https://img.shields.io/badge/Kibana-005571?style=flat-square&logo=Kibana&logoColor=white"> <!--Kibana-->

</br>

## 담당한 업무
- Filebeat로 탐지한 웹 해킹 로그 파일을 실시간으로 수집하여 Logstash로 전달
- Logstash로 수집한 웹 해킹 로그를 선정해서 Elasticserch에 인덱싱하여 전달
- Elasticserch로 수집된 웹 해킹 로그를 저장소에 저장
- Kibana로 웹 해킹 로그 시각화

</br>

## 상세 내용 
### Infra Architecture
![kibana](https://user-images.githubusercontent.com/110655823/215553517-70c4d9c2-11cd-4110-902b-a6ee3c84e09a.png)
> - 총 탐지 로그, 시간당 로그 탐지 수, 웹 해킹별 탐지율, 공격자 IP를 Kibana 시각화

### - [Snort & ELK Stack](https://github.com/hyunjaebok/Snort_ELK_Project/tree/main/Snort%20%26%20ELK%20Stack)

