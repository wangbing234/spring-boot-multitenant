# spring-boot-multitenant
Spring Boot Multi-tenant Sample


curl -X GET "http://localhost:8080/products"


curl -X GET -H "tenant:secondDS" "http://localhost:8080/products"
