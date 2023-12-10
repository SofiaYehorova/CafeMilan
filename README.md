<!DOCTYPE html>
<html lang="uk" >
<head>
<meta charset="UTF-8">
<title>Кяв'ярня- "Мілан"</title>
<style type="text/css">
a{
color: #brown;
text-decoration: none;
}
html{
background: #black;
min-height: 100%;
font-family: Helvetica;
display: flex;
flex-direction: column;
}
body{
margin: 0;
padding: 0 15px;
display: flex;
flex-direction: column;
flex: auto;
}
h1{
margin-top: 0;
}
h1, p{
color: #white;
}
img{
border: 0;
}
.header{
width: 100%;
min-width: 360px;
max-width: 1060px;
margin: 0 auto 15px;
padding: 15px 0 10px;
display: flex;
flex-wrap: wrap;
justify-content: space-between;
box-sizing: border-box;
}
.logo{
font-size: 1.5rem;
color: #brown;
text-decoration: none;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
display: flex;
flex: none;
align-items: center;
background: #black;
width: 130px;
height: 50px;
}
.nav{
margin: -5px 0 0 -5px;
display: flex;
flex-wrap: wrap;
}
.nav-item{
background: #black;
width: 130px;
height: 50px;
font-size: 1.5rem;
color: #brown;
text-decoration: none;
display: flex;
margin: 5px 0 0 5px;
justify-content: center;
align-items: center;
}
.sqr{
height: 300px;
width: 300px;
background: #white;
}

.main{
width: 100%;
min-width: 360px;
max-width: 1060px;
margin: auto;
flex: auto;
box-sizing: border-box;
}
.box{
font-size: 1.25rem;
line-height: 1.5;
margin: 0 0 40px -50px;
display: flex;
flex-wrap: wrap;
justify-content: center;
}
.box-base{
margin-left: 50px;
flex: 1 0 430px;
}
.box-side{
margin-left: 50px;
font: none;
}
.box-img{
max-width: 100%;
height: auto;
}
.content{
margin-bottom: 30px;
display: flex;
flex-wrap: wrap;
}
.banners{
flex: 1 1 200px;
}
.banner{
background: #brown;
width: 100%;
min-width: 100px;
min-height: 200px;
font-size: 3rem;
color: #brown;
margin: 0 0 30px 0;
display: flex;
justify-content: center;
align-items: center;
}
.posts{
margin: 0 0 30px 30px;
flex: 1 1 200px;
}
.comments{
margin: 0 0 30px 30px;
flex: 1 1 200px;
}
.comment{
display: flex;
}
.comment-side{
padding-right: 20px;
flex: none;
}
.comment-base{
flex: auto;
}
.comment-avatar{
background: #brown;
width: 50px;
height: 50px;
}
.footer{
background: #white;
width: 100%;
max-width: 960px;
min-width: 460px;
color: #black;
margin: auto;
padding: 15px;
box-sizing: border-box;
}

@media screen and  (max-width: 800px) {
.banners{
margin-left: -30px;
display: flex;
flex-basis: 100%;
}
.banner{
margin-left: 30px;
}
.posts{
margin-left: 0;
}
}
@media screen and  (max-width: 600px) {
.content{
display: block;
}
.banners{
margin: 0;
display: block;
}
.banner{
margin-left: 0;
}
.posts{
margin: 0;
}
}
</style>
</head>
<body>
<header class="header">
<a class="logo">
LOGO
</a>
<nav class="nav">
<a href="#posts" class="nav-item">Головна</a>
<a href="#comments" class="nav-item">Коментарі</a>
<a href="#posts" class="nav-item">Спілкування</a>
</nav>

</header>
<main class="main">
<div class="box">
<div class="box-base">
<h1>Мета нащої кав'ярні</h1>
<p>Головна мета нашої кав'ярні "Мілан"- подарувати незабутні враження від вищуканої кави зробленної з відбврних сортів кавових зерен. Вибираючи нас Ви маєте змогу відпдчити в "Міланській кав'ярні". Долучайтеся до нас, ми не підведимо Вас!</p>
</div>
<div class="box-side">
<div class="sqr">

</div>
</div>
</div>
<div class="content">
<div class="banners">
<div class="banner">Баннер 1</div>
<div class="banner">Баннер 2</div>
<div class="banner">Баннер 3</div>
</div>
<div class="posts"  id="posts">
<div class="post">
<h1>Coffee</h1>
<p>Coffee is one of the most stable products on the consumer goods market. Its consumption is characterized by a high level of brand loyalty: only in the last resort will a product lover betray his favorite brand and switch to a cheaper option. Even during the crisis, the share of consumers who changed their favorite coffee to a cheaper one was insignificant. Every year, the coffee market is replenished with new capital, the size of which reaches 200-300 million dollars. And it's not because coffee is getting more expensive or cheaper: it's just that more and more people are drinking it. The "Milan" coffee shop is presented in such a way that the visitor is offered several types of coffee, which are prepared quickly and qualitatively. The coffee shop will deal with the sale of coffee-rich drinks. Drinks will be of high quality and brewed according to the original recipe.</p>
</div>
<div class="post">
<h1>Our history</h1>
<p>The history of the development of the "Milan" enterprise: "Milan" began its activity in 2023 as a small coffee shop with signature coffee and Italian desserts. We offer residents and guests of the city a completely new style of coffee shop. This is a unique coffee shop that allows you to enjoy exclusive desserts with high-quality drinks in a comfortable and high-class place, where you can socialize, relax and work. Growth prospects: Plans to expand the brand include opening new branches, expanding the menu and introducing concept innovations. Cafe "Milan" is aimed at constant improvement and response to the changing needs of customers.</p>
</div>
<div class="post">
<h1>Menue "Milan"</h1>
<p>Menu of our cafe: Espresso, Ristretto, Doppio, Lungo, Americano, Latte, Cappuccino Macchiato, Flat white, Viennese coffee, Ruff coffee, Frappe, Glasse, Affogato, Irish or Irish coffee, Green, black and herbal tea, Carbonated and non-carbonated water, Signature drinks, Hot chocolate, Cocoa. And other delicacies.</p>
</div>
</div>
<div class="comments"  id="comments">
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">Коментарі</h1>
<p>Вам потрыбно змынити назву) Дякуэмо за гарний настрій, смачна кава та пртьмна атмосфера.</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">The additional menu</h1>
<p>White tea (Chinese: bai cha) is rare and expensive, consists exclusively of tea buds (tips). Yellow tea (Chinese - huan cha) is almost like green tea, but before drying, it goes through a closed "swelling" procedure. Green tea (English green, Chinese Lui cha) in its dry form has a green color (from light green to dark green, depending on the production features), the infusion is a dull yellowish or greenish color, the aroma clearly has a "herbal" note. Red tea (English oolong, Chinese Oolong), this name is found in Russia, in China it is sometimes called "turquoise" or "blue-green". Black tea (English black, Chinese Hong cha, also known as red in China) is the most famous and popular. Puerh (Chinese Hei cha, "black tea"). It is made from tips, and from mature leaves, from old trees. Flavored tea. Fruit teas. The basis of these drinks is tea, but at the same time there are significant additions of fruit and other inclusions. Herbal teas (tiza). Tiza - from the French word "Tisane", means any herbal infusion. Instant teas. These teas in the form of granules can be diluted with both hot and cold water. Tea extracts that come from tea juice are a very expensive and exotic pleasure. Karkade is one of the most famous non-tea teas in Ukraine, it is the dried flowers of the Sudan rose (hibiscus flower). Mate - sometimes "Paraguayan tea" or "Brazilian tea" - this Latin American version of tea is gaining more and more popularity these days. Rooibos is tea from a red shrub, sometimes called Bushman tea.</p>
</div>
</div>
<div class="comment">
<div class="comment-side">
<div class="comment-avatar">

</div>
</div>
<div class="comment-base">
<h1 class="comment-title">"Milan"</h1>
<p>We always inspire you, and we will support you wherever you are: work, rest or difficulties. You will be served by our professional baristas, waiters and specialized confectioners. If you want to share your breakfast or dinner with us, we will give you a real taste of "Milan style". The environmental assessment of the "Milan" coffee shop includes: 1. Load on the environment: production emissions and waste, as well as disposal costs are taken into account. 2. Procedures for environmental protection: procedures have been developed and implemented to reduce the impact on nature, in particular, efficient use of resources and limitation of emissions. 3. Environmental quotas: submission of requests for ecological quotas meets the standards and requirements determined during the environmental impact assessment.</p>
</div>
</div>
</div>
</div>
</main>
<footer class="footer"  id="footer">
</footer>
</body>
</html>
