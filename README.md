# JavaSpringBoot
## 2022.03.03
## Author: Zhakyp 
### Java Spring Boot and Git practice 
![image](https://user-images.githubusercontent.com/73534500/156514291-04930c6b-f994-419d-a19d-0ca4e8a8aed3.png)
``` java
package com.example.springboot; 


import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class HelloController {

	@GetMapping("/")
	public String index() {
		return "Greetings from Spring Boot!";
	}

} 
```
