


## MockMvc - RESTful Testing

**MockMVC**  class is part of Spring MVC test framework which helps in testing the controllers explicitly starting a Servlet container. With MockMvc, . is possible to test a fully functional REST controller but without the overhead of deploying the app to a container.

MockMVC stands up controller, sends requests and then expects for a response.

**Main Features**
- Executes Request
- Validates HTTP Response
- Validate HTTP Headers
- Validate Response Body

```java
@Autowired 
private MockMvc mockMvc;
```
