
<!DOCTYPE html>
<html>
<head>
<title>My Video Site</title>

<style>
body{
font-family: Arial;
background:#f1f1f1;
margin:0;
}

.header{
background:red;
color:white;
padding:15px;
font-size:20px;
}

.container{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:10px;
padding:10px;
}

.video-card{
background:white;
padding:5px;
border-radius:6px;
}

video{
width:100%;
border-radius:6px;
}

.title{
font-size:14px;
margin-top:5px;
}
</style>

</head>

<body>

<div class="header">
My Video Tube
</div>

<div class="container">

<div class="video-card">
<video controls>
<source src="video1.mp4" type="video/mp4">
</video>
<div class="title">আমার প্রথম ভিডিও</div>
</div>

<div class="video-card">
<video controls>
<source src="video2.mp4" type="video/mp4">
</video>
<div class="title">নতুন ভিডিও</div>
</div>

<div class="video-card">
<video controls>
<source src="video3.mp4" type="video/mp4">
</video>
<div class="title">ভালো একটি ভিডিও</div>
</div>

<div class="video-card">
<video controls>
<source src="video4.mp4" type="video/mp4">
</video>
<div class="title">দেখতে ভুলবেন না</div>
</div>

</div>

</body>
</html>