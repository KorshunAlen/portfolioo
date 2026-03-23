---
layout: default
title: Портфолио
---

<style>
.inner {
    max-width: 1000px;
    margin: 0 auto; /* центрирование по горизонтали */
    padding: 20px;  /* внутренние отступы для комфорта */
    box-sizing: border-box;
}

/* Чтобы все объекты внутри страницы тоже подстраивались */
* {
    box-sizing: border-box;
}

.hero {
    text-align: center;
    padding: 60px 20px;
}

.hero h1 {
    font-size: 40px;
}

.nav {
    position: sticky;
    top: 0;
    background: white; 
    text-align: center;
    z-index: 1000;
}

.nav a {
    display: inline-block;
    background: white;        
    color: black;              
    padding: 15px 20px;         
    margin: 10px;
    border-radius: 12px;        
    text-decoration: none;
    font-weight: bold;
    font-size: 20px;
    transition: 0.3s;
}

.nav a:hover {
    transform: translateY(-3px); 
}
    
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 40px;
}

.card {
    background: white;
    padding: 30px;
    border-radius: 12px;
    text-align: center;
    text-decoration: none;
    color: black;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

body {
    background: #f4f6f8;
    font-family: Arial;
}

</style>

<div class="nav">
  <a href="/portfolioo">Главная</a>
  <a href="/portfolioo/about">Обо мне</a>
  <a href="/portfolioo/year1">1 курс</a>
  <a href="/portfolioo/year2">2 курс</a>
  <a href="/portfolioo/year3">3 курс</a>
  <a href="/portfolioo/year4">4 курс</a>
</div>

<div class="hero">

<p>Студент IT-направления</p>
<p>Портфолио учебных и проектных работ</p>

</div>

---

## Мои работы

<div class="cards">

<a href="/portfolioo/year1" class="card">
<h3>1 курс</h3>
<p>1 и 2 семестр</p>
</a>

<a href="/portfolioo/year2" class="card">
<h3>2 курс</h3>
<p>3 и 4 семестр</p>
</a>

<a href="/portfolioo/year3" class="card">
<h3>3 курс</h3>
<p>5 и 6 семестр</p>
</a>

<a href="/portfolioo/year4" class="card">
<h3>4 курс</h3>
<p>7 и 8 семестр</p>
</a>

</div>
