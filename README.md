<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>العقيق باك | Link in Bio</title><!-- SEO --><meta name="description" content="العقيق باك - جميع روابط التواصل الاجتماعي في مكان واحد">
<meta property="og:title" content="العقيق باك">
<meta property="og:description" content="تابع جميع حساباتنا وروابط التواصل"><style>
@import url('https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;700&display=swap');

body{
margin:0;
font-family:'Cairo',sans-serif;
background: radial-gradient(circle at top,#0b1220,#05070f);
color:white;
display:flex;
justify-content:center;
align-items:center;
min-height:100vh;
overflow-x:hidden;
}

/* خلفية احترافية */
.glow{
position:fixed;
width:400px;
height:400px;
background:#6366f1;
filter:blur(140px);
opacity:0.25;
top:-100px;
left:-100px;
animation:float 10s infinite alternate;
z-index:-1;
}

@keyframes float{
from{transform:translate(0,0);}
to{transform:translate(250px,200px);}
}

.container{
width:92%;
max-width:420px;
background: rgba(255,255,255,0.06);
backdrop-filter: blur(20px);
border-radius:30px;
padding:28px;
box-shadow:0 25px 60px rgba(0,0,0,0.7);
text-align:center;
border:1px solid rgba(255,255,255,0.1);
}

.avatar{
width:100px;
height:100px;
border-radius:50%;
overflow:hidden;
margin:auto;
border:3px solid rgba(255,255,255,0.2);
box-shadow:0 10px 25px rgba(0,0,0,0.5);
}

.avatar img{
width:100%;
height:100%;
object-fit:cover;
}

h1{
margin:12px 0 5px;
font-size:24px;
font-weight:700;
}

p{
margin-bottom:20px;
font-size:13px;
opacity:0.8;
}

.section{
text-align:right;
font-size:12px;
opacity:0.6;
margin-top:18px;
margin-bottom:8px;
}

.link{
display:flex;
align-items:center;
justify-content:center;
gap:10px;
margin:10px 0;
padding:14px;
border-radius:16px;
text-decoration:none;
color:white;
font-weight:600;
background: linear-gradient(135deg, rgba(99,102,241,0.4), rgba(236,72,153,0.4));
border:1px solid rgba(255,255,255,0.1);
transition:0.25s;
}

.link:hover{
transform:scale(1.05);
background: linear-gradient(135deg, rgba(99,102,241,0.7), rgba(236,72,153,0.7));
}

.footer{
margin-top:20px;
font-size:11px;
opacity:0.5;
}

button{
margin-top:10px;
padding:10px;
border:none;
border-radius:12px;
width:100%;
cursor:pointer;
font-weight:600;
background:white;
color:#0b1220;
transition:0.3s;
}

button:hover{
transform:scale(1.03);
}

.toast{
position:fixed;
bottom:20px;
background:#22c55e;
color:white;
padding:10px 15px;
border-radius:10px;
display:none;
}

</style></head>
<body><div class="glow"></div><div class="container"><div class="avatar">
<img src="https://via.placeholder.com/150" alt="logo">
</div><h1>العقيق باك</h1>
<p>كل روابطنا الرسمية في مكان واحد</p><button onclick="copyLink()">نسخ رابط الصفحة</button>

<div class="section">حسابات التواصل</div><a class="link" href="https://instagram.com" target="_blank">📸 إنستغرام</a> <a class="link" href="https://tiktok.com" target="_blank">🎵 تيك توك</a> <a class="link" href="https://facebook.com" target="_blank">📘 فيسبوك</a> <a class="link" href="https://youtube.com" target="_blank">▶️ يوتيوب</a>

<div class="section">تواصل مباشر</div><a class="link" href="https://wa.me/0000000000?text=مرحبا%20أريد%20التواصل" target="_blank">💬 واتساب</a> <a class="link" href="mailto:example@email.com">✉️ البريد الإلكتروني</a>

<div class="footer">© 2026 العقيق باك - جميع الحقوق محفوظة</div></div><div class="toast" id="toast">تم النسخ 👍</div><script>
function copyLink(){
navigator.clipboard.writeText(window.location.href);
document.getElementById('toast').style.display='block';
setTimeout(()=>{
document.getElementById('toast').style.display='none';
},2000);
}
</script></body>
</html>
