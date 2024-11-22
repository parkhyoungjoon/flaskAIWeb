# K-Digital 프로젝트 4개모델 한개의 웹으로 서비스

K-Digital 과정에서 팀프로젝트를 통해 개발한 4가지 모델은 한개의 웹에서 작동하도록 구축하였습니다.  
Flask를 사용했지만 공부과정이 미흡하여 MVC 패턴으로 완성하지 못함

## 시작하기에 앞서

본 프로젝트는 개발공부 및 테스트 목적으로 로컬환경에서 실행되는 프로젝트 입니다.

### 개발환경

- Python : 3.8.2
- Server : Flask(3.0.3) 내장서버

### 사용 라이브러리
flask : 3.0.3
import joblib
torch : 2.4.1
numpy : 1.24.3
pandas : 2.0.3
konlpy : 0.6.0


### 커스텀 모델
MLPModel 
SkinKitModel
ReviewClassifierModel
## 테스트

로컬환경에서 테스트 진행
2024-11-22 - 문제없이 프론트엔드 화면 출력 

## 전개
csv : 피부병 관련 질환 정보가 담겨있는 csv 파일 위치
data : 불용어 리스트.txt 위치
models : 커스텀 모델 + 전처리에 사용된 단어사전, 스케일러 위치
modules : 개인 라이브러리 파일
static : 웹에서 사용될 images, js, css 등이 위치 
templates : 페이지 템플릿(html) 위치

## 작성자

* **박형준** - *초기작업* - [PurpleBooth](https://github.com/parkhyoungjoon)

## 감사의 말

* 프로젝트를 수행할 수 있도록 도와준 경북대학교 데이터융복합연구원 강사님들에게 감사합니다.
