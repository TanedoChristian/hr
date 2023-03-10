# Summary
 
| Package        | Classtype    | Remarks  |
| ------------- |:-------------:| -----:|
| ```ph.com.alliance.jpa.common```    | *any* | Classes common to all Functions |
| ```ph.com.alliance.jpa.config```    | **@Configuration** classes  |  Classes that declare the @Bean methods |
|```ph.com.alliance.jpa.interceptor```    | Interceptor classes  |  Classes the prehandle or/and posthandle requests |
|```ph.com.alliance.jpa.listener```    | Listener classes  |  Classes that declare the @Bean methods|
|```ph.com.alliance.jpa.entity```    | **@Entity** classes  |  Entity classes auto-generated by JPA |
|```ph.com.alliance.jpa.functions```    | MVC classes  |  Classes representing the MVC of each function|
| ```ph.com.alliance.jpa.functions.*.controller``` | **@RestController** classes      |  Controller classes on each function |
| ```ph.com.alliance.jpa.functions.*.service``` | **@Service** classes      |  Service classes on each function |
| ```ph.com.alliance.jpa.functions.*.dao``` | **@Repository** classes      |  Repository classes on each function|
| ```ph.com.alliance.jpa.functions.*.model``` | Model classes | Custom model classes used for a function|
