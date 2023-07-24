package com.example.demoRepasoEC3;

import org.springframework.stereotype.Controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.ResponseBody;

@Controller
public class MainController {
    
    @GetMapping(path="/")
    public @ResponseBody String home(){
        return "Hola Repaso Semana 8";
    }
}
