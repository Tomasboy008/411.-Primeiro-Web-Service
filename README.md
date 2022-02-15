# 411.-Primeiro-Web-Service
testando mais de uma URL
INICIO
________________________________
package com.example.exerciciossb.controllers;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class PrimeiroController {
	
	@GetMapping(path = { "/ola", "/saudação"})
	public String ola() {
		return "Olá Spring Boot!";
	}
}
![image](https://user-images.githubusercontent.com/95525963/153973947-f8af71a4-3401-475d-98b8-59843e7427ff.png)
