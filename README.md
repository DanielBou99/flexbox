# flexbox
  
```  
.cabecalhoPrincipal .container {
    display: flex;
    align-items: center;
    justify-content: space-between;
}  
```  
  
<img src="img/exemplos/exemplo1.jpg">  
  
```  
.cabecalhoPrincipal-nav {
    display: flex;
}
```
    
  <img src="img/exemplos/exemplo2.jpg">
  
```  
.rodapePrincipal-patrocinadores .container {
    display: flex;
    justify-content: space-between;
}

.rodapePrincipal-patrocinadores-list {
    display: flex;
    align-items: center;
    justify-content: space-around;
    width: 70%;
    margin-right: 5%;
}

.rodapePrincipal-contatoForm {
    width: 25%;
}

.rodapePrincipal-contatoForm-fieldset {
    display: flex;
}
```  
  
<img src="img/exemplos/exemplo3.jpg">  
  
```  
/* Mapa de cursos */
.rodapePrincipal-navMap-list {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    height: 255px;
}
```  
  
<img src="img/exemplos/exemplo4.jpg">  
  
```  
/* Cards Cursos */
.conteudoPrincipal-cursos {
    display: flex;
    flex-wrap: wrap;
}

.conteudoPrincipal-cursos-link {
    width: 23%;
    margin: 1;
}

.conteudoPrincipal-cursos-link:nth-child(4n) {
    margin-right: 0;
}

.conteudoPrincipal-cursos-link:nth-child(4n+1) {
    margin-left: 0; 
}
```  
  
<img src="img/exemplos/exemplo5.jpg">  
  