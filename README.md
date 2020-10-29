<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="./ui/static/img/logo.png" alt="Project logo"></a>
</p>

<h3 align="center">Snippetbox</h3>

<div align="center">

</div>

---

<p align="center"> Write your snippets here!
    <br> 
</p>

## 📝 Table of Contents

- [About](#about)
- [Usage](#usage)
- [Built Using](#built_using)
- [Acknowledgments](#acknowledgement)

## 📟 About <a name = "about"></a>

A web application based on [@Alex's](https://github.com/alexedwards) book *Let's Go*. The web app was fully developed using Go and taking advantage of popular packages. 

With the books help I implemented:
- Database pool connection pattern that allows for easy testing - Optimized the project work flow 
- Security standards, which includes: tls, csrf, escaping input, and session managment
- Unit and integration testing
- a cache for quicker performance.



## 🔑 Usage <a name="usage"></a>

**Landing Page**<br>
<img src="/assets/home.png"><br>
**Signing Up**<br>
<img src="/assets/signup.png"><br>
**Logging In**<br>
<img src="/assets/login.png"><br>
**Creating a Snippet**<br>
<img src="/assets/create.png"><br>
**Logged Out**<br>
<img src="/assets/logout.png"><br>
**GIF: ONLY Authenticated Users can create Snippets Page**<br>
<img src="/assets/redirect.gif"><br>

## ⛏️ Built Using <a name = "built_using"></a>

- [MySql](https://www.mysql.com/) - Database
- [Go](https://golang.org/) - Server Framework
  - [net/http Package](https://golang.org/pkg/net/http/) - Web Framework
  - [alice](https://github.com/justinas/alice) - Middleware Management
   - [nosurf](https://github.com/justinas/nosurf) - CSRF Tool
   - [crypto Package](https://github.com/golang/crypto) - Bcrypt for password encryption
   - [Sessions](https://github.com/golangcollege/sessions) - Session Management
- Vanilla JS and CSS

## ✍️ Authors <a name = "authors"></a>

- [@omar](https://github.com/omaralaniz) - Coded

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- *Lets* Go by [@Alex](https://github.com/alexedwards)
