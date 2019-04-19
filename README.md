# 스프링부트 api 기본 설정 프로젝트 (springboot-api-default-setting)

- 스프링부트(springboot) 기반으로 api 기본셋팅하여 설정한 프로젝트 파일입니다. 
- controller, service, dao, model, mapper, common, util, config, exception, log 패키지로 구성되어 있습니다.
- aws rds maria db로 연결해 조회[GET] api 한개를 테스트로 만들었습니다.
- log4j를 이용해 기본적인 로그는 모두 설정했습니다.(쿼리 실행 로그 및 오류로그) 
- application.yml 파일 수정을 통해 필요에 따라 db연결을 바꿔 oracle, mysql 선택 가능합니다.
- postman을 통해 localhost로 api를 실행한 후 테스트 가능합니다.
  - http://localhost:포트번호/demo-api/selectBurger/list
- maven을 사용하여 maven install, update project가 필요할 수 있습니다.
