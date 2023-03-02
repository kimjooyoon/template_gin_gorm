### Template_gin_gorm

개인 목적으로 사용할 템플릿입니다.

Todos

- api generator
- openApi spec generator
- integration test generator



## a_api

a domain, rest api

- rest.go: gin 을 사용하고 controller 를 맵핑
- controller.go: request 를 통해 service 를 핸들링
- service.go: entity 의 use-case 를 구현
- repository.go: service 의 영속성 모델 interface 를 구현
- model.go: entity 를 구현

## util

유틸성 library
