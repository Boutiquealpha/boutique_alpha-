خوش آمدید
<html lang="fa">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>بوتیک آلفا</title>

<style>

body{
margin:0;
padding:0;
font-family:tahoma;
direction:rtl;
background:#f7f3f0;
text-align:center;
}

/* بک‌گراند لوگو */
body::before{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background-image:url("https://i.ibb.co/gZxQrVRx/IMG-20260703-001703-903.jpg");
background-repeat:no-repeat;
background-position:center;
background-size:cover;
opacity:0.10;
pointer-events:none;
z-index:-1;
}

/* هدر */
header{
background:#3b2f2f;
color:white;
padding:15px;
font-size:22px;
font-weight:bold;
}

/* محصولات */
.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:20px;
}

.product{
width:260px;
background:white;
padding:15px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.product img{
width:100%;
border-radius:10px;
}

/* دکمه */
button{
background:#6b4f4f;
color:white;
padding:10px 15px;
border:none;
border-radius:10px;
cursor:pointer;
margin-top:10px;
}

button:hover{
background:#4a3636;
}

/* سبد خرید */
.cart{
position:fixed;
top:15px;
right:15px;
background:#3b2f2f;
color:white;
padding:10px 15px;
border-radius:50px;
cursor:pointer;
z-index:999;
}

/* فوتر */
.footer{
background:#3b2f2f;
color:white;
padding:20px;
margin-top:30px;
}

.footer a{
color:#ffddc1;
text-decoration:none;
font-weight:bold;
}

</style>
</head>

<body>

<header>
🛍 بوتیک آلفا
</header>

<!-- سبد خرید -->
<div class="cart" onclick="showCart()">
🛒 <span id="cartCount">0</span>
</div>
<!-- محصولات -->
<div class="products">

<!-- 1 -->
<div class="product">
<h3>شومیز طرح خرس</h3>
<img src="https://i.ibb.co/jZ5R2JPM/filename.jpg">
<p>🎨 رنگ بندی: 9 رنگ</p>
<p>👗 سایز فری (38/46)</p>
<p>🧶 جنس: لینن پفکی</p>
<p>💵 قیمت: 1,288,000 تومان</p>
<button onclick="addToCart('شومیز طرح خرس',1288000)">➕ افزودن به سبد</button>
</div>

<!-- 2 -->
<div class="product">
<h3>تیشرت فلفلی</h3>
<img src="https://i.ibb.co/kst7qBTR/filename.jpg">
<p>جنس نخ پنبه سوپر</p>
<p>فری سایز تا 48</p>
<p>💯 محدود</p>
<p>💵 قیمت: 988000 تومان</p>
<button onclick="addToCart('تیشرت فلفلی',988000)">➕ افزودن به سبد</button>
</div>

<!-- 3 -->
<div class="product">
<h3>شومیز باکسی شیما</h3>
<img src="https://i.ibb.co/1JQrNPRs/filename.jpg">
<p>جنس مکس</p>
<p>قد 55 سانت</p>
<p>رنگ بندی متنوع</p>
<p>سایز تا 46</p>
<p>💵 قیمت: 1,398,000 تومان</p>
<button onclick="addToCart('شومیز باکسی شیما',1398000)">➕ افزودن به سبد</button>
</div>

<!-- 4 -->
<div class="product">
<h3>شلوار بگ کرپ مورگان</h3>
<img src="https://i.ibb.co/CKNQ0wcv/filename.jpg">
<p>کرپ درجه 1</p>
<p>سایز 42 تا 48</p>
<p>قد 103/105</p>
<p>💵 قیمت: 1,680,000 تومان</p>
<button onclick="addToCart('شلوار بگ کرپ مورگان',1680000)">➕ افزودن به سبد</button>
</div>

<!-- 5 -->
<div class="product">
<h3>شومیز پشت پیله</h3>
<img src="https://i.ibb.co/CK6sjHXK/filename.jpg">
<p>سایز فری 38/44</p>
<p>جنس اطلس</p>
<p>💵 قیمت: 1,298,000 تومان</p>
<button onclick="addToCart('شومیز پشت پیله',1298000)">➕ افزودن به سبد</button>
</div>

<!-- 6 -->
<div class="product">
<h3>تیشرت باکسی Home</h3>
<img src="https://i.ibb.co/Wp7cPxZL/filename.jpg">
<p>نخ پنبه سوپر</p>
<p>اورسایز 46/48</p>
<p>💵 قیمت: 588000 تومان</p>
<button onclick="addToCart('تیشرت باکسی Home',588000)">➕ افزودن به سبد</button>
</div>

<!-- 7-->
<div class="product">
<h3>شومیز شیشه‌ای</h3>
<img src="https://i.ibb.co/chP3frX9/filename.jpg" width="300">
<P>رنگ بندی:4رنگ</p>
<P>سایز فری(38/44)</p>
<p>قیمت: 1750000 تومان</p>
<button onclick="addToCart('شومیزشیشه ای',175000)">➕ افزودن به سبد</button>
</div>


<!-- فوتر -->
<div class="footer">

<p>📞 09375294372</p>
<p>📍 ماهشهر، ایران</p>

<p>📸 
<a href="https://instagram.com/boutique.alphaa_" target="_blank">
@boutique.alphaa_
</a>
</p>

<p>💳 شماره کارت: 6219861963961338</p>
<p>به نام: سارا مقدم سریمه</p>

</div>

<script>

let cart = [];

function addToCart(name, price){

let item = cart.find(p => p.name === name);

if(item){
item.qty += 1;
}else{
cart.push({name:name, price:price, qty:1});
}

updateCartCount();
alert(name + " اضافه شد 🛒");
}

function updateCartCount(){
let count = 0;
cart.forEach(i => count += i.qty);
document.getElementById("cartCount").innerText = count;
}

function removeItem(name){
cart = cart.filter(i => i.name !== name);
updateCartCount();
renderCart();
}

function changeQty(name, type){
let item = cart.find(i => i.name === name);
if(!item) return;

if(type === "plus") item.qty++;
if(type === "minus" && item.qty > 1) item.qty--;

renderCart();
updateCartCount();
}

function showCart(){

if(cart.length === 0){
alert("سبد خرید خالیه");
return;
}

renderCart();
document.getElementById("cartModal").style.display = "block";
}

function renderCart(){

let box = document.getElementById("cartItems");
box.innerHTML = "";

cart.forEach(item => {

box.innerHTML += 
<div style="background:#fff;margin:10px;padding:10px;border-radius:10px">
<h4>${item.name}</h4>
<p>${item.price} تومان</p>

<button onclick="changeQty('${item.name}','minus')">-</button>
${item.qty}
<button onclick="changeQty('${item.name}','plus')">+</button>

<button onclick="removeItem('${item.name}')">❌ حذف</button>
</div>
;

});
}

function checkout(){

let name = document.getElementById("cusName").value;
let phone = document.getElementById("cusPhone").value;
let address = document.getElementById("cusAddress").value;

if(!name || !phone){
alert("مشخصات کامل نیست ❌");
return;
}

let msg = "🛒 سفارش جدید:%0A";
let total = 0;

cart.forEach(i=>{
msg += i.name + " x" + i.qty + "%0A";
total += i.price * i.qty;
});

msg += "%0A💰 مجموع: " + total;
msg += "%0A👤 نام: " + name;
msg += "%0A📞 تلفن: " + phone;
msg += "%0A🏠 آدرس: " + address;

window.open("https://wa.me/989375294372?text="+encodeURIComponent(msg), "_blank");
}

</script>
</script>

</body>
