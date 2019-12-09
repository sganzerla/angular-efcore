# angular-efcore
Midlleware C# .Net Core 2.2 com API Rest, ORM Entity e Identity Framework, autenticação JWT, persistência MSSQL Server e frontend Angular 7

Originalmente criado por Vinícius de Andrade "Seja Fullstack com Asp.NET Core 2, Angular 7, EF Core 2" https://www.udemy.com/share/100QgoBEsTc15QQX4=/

#### Tecnologias
 
- .NET Core 2.2
- .NET EntityFramework Core
* .NET Identity Framework Core
- Autenticação JWT
- MSSQL Server
- Angular 7
- Swagger API Document

 ##### Requisitos
 
- [SDK .NET Core 2.2](https://dotnet.microsoft.com/download/dotnet-core/2.2)
- [Node.js](https://nodejs.org/en/download/)
- [MSSQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads)
- [CLI Angular](https://cli.angular.io/quickstart)
 ```
 npm install -g @angular/cli</li>
 ``` 


 ##### Como usar
 
 ###### Preparar Banco de dados
 Alterar connectionStrings em appsettings.Development.json e realizar as migrations
 ```
 dotnet ef --startup-project ..\ProAgil.WebAPI migrations add helloworld  
 dotnet ef --startup-project ..\ProAgil.WebAPI database update  
 ``` 
 ##### Backend (ProAgil.WebAPI)
 
 Executar os comandos no diretório ProAgil.WebAPI
 
 ```
 dotnet restore
 dotnet watch run
 ```
 Acessar no navegador ou Postman http://localhost:5000
 
 ###### Frontend (ProAgil-App)
  Executar os comandos no diretório ProAgil-App
 ```
 npm install
 npm build 
 ng serve -o
 ```
Acessar no navegador localhost:4200
 
 <h5>Tela Eventos</h5>
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/61652208-d414a600-ac8d-11e9-8f80-c8487e7fce3a.png">
<img src="https://user-images.githubusercontent.com/22710963/61652208-d414a600-ac8d-11e9-8f80-c8487e7fce3a.png" alt="reset" style="max-width:100%;"></a></p> 
 
 <h5>Login</h5>
 <p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/61652753-14285880-ac8f-11e9-8806-b56b95f5fdd3.png">
 <img src="https://user-images.githubusercontent.com/22710963/61652753-14285880-ac8f-11e9-8806-b56b95f5fdd3.png" alt="reset" style="max-width:100%;"></a></p> 
  
 <h5>Editar Evento</h5>
 <p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/61652913-6c5f5a80-ac8f-11e9-9073-73fe8a1acd58.png">
 <img src="https://user-images.githubusercontent.com/22710963/61652913-6c5f5a80-ac8f-11e9-9073-73fe8a1acd58.png" alt="reset" style="max-width:100%;"></a></p> 
 
 <h5>JWT</h5>
  <p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/61660050-66717580-ac9f-11e9-829d-af442dc7355b.png">
 <img src="https://user-images.githubusercontent.com/22710963/61660050-66717580-ac9f-11e9-829d-af442dc7355b.png" alt="reset" style="max-width:100%;"></a></p> 

<h5>Swagger API Document</h5>
<p><a target="_blank" rel="noopener noreferrer" href="https://user-images.githubusercontent.com/22710963/61677991-e7e4fa00-acd7-11e9-9196-1593b648548c.png">
 <img src="https://user-images.githubusercontent.com/22710963/61677991-e7e4fa00-acd7-11e9-9196-1593b648548c.png" alt="reset" style="max-width:100%;"></a></p> 

 
#### Pacotes npm instalados
 
CLI Angular (https://cli.angular.io/quickstart) 
```
npm install -g @angular/cli
```
Bootstrap (https://getbootstrap.com.br/docs/4.1/getting-started/download/)
```
npm install bootstrap
```
Ngx Bootstrap (https://valor-software.com/ngx-bootstrap/#/)
```
npm install ngx-bootstrap --save 
```
Fonte Awesome (https://fontawesome.com/how-to-use/on-the-web/setup/using-package-managers)
```
npm install --save-dev @fortawesome/fontawesome-free
```
Notificações Toastr
```
npm install ngx-toastr --save
npm install @angular/animations --save 
```
JWT 
```
npm i @auth0/angular-jwt
```
Instalar Mascara dinheiro
```
npm i ngx-currency 
```
Mask (https://www.npmjs.com/package/ngx-mask)
```
npm install --save ngx-mask
```
Angular Guard
```
ng g g auth/auth 
```
Instalar Tabs (https://valor-software.com/ngx-bootstrap/#/tabs
```
ng add ngx-bootstrap --component tabs 
```

  
 

 
 
