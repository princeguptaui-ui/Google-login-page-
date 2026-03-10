
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Google Sign In</title>

<style>
body{
    font-family: Arial, sans-serif;
    background:#f1f3f4;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.login-box{
    background:white;
    width:380px;
    padding:40px;
    border-radius:8px;
    box-shadow:0 2px 10px rgba(0,0,0,0.1);
    text-align:center;
}

.logo{
    width:75px;
    margin-bottom:10px;
}

h2{
    font-weight:500;
    margin:10px 0;
}

p{
    color:#5f6368;
    font-size:14px;
}

input{
    width:100%;
    padding:12px;
    margin-top:20px;
    border:1px solid #dadce0;
    border-radius:4px;
    font-size:16px;
}

input:focus{
    outline:none;
    border:1px solid #1a73e8;
}

.links{
    text-align:left;
    margin-top:10px;
}

.links a{
    color:#1a73e8;
    text-decoration:none;
    font-size:14px;
}

.buttons{
    margin-top:30px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.create{
    color:#1a73e8;
    text-decoration:none;
    font-size:14px;
}

.next{
    background:#1a73e8;
    color:white;
    border:none;
    padding:10px 22px;
    border-radius:4px;
    font-size:14px;
    cursor:pointer;
}

.next:hover{
    background:#1669c1;
}
</style>

</head>

<body>

<div class="login-box">

<img class="logo" src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png">

<h2>Sign in</h2>
<p>Use your Google Account</p>

<input type="email" placeholder="Email or phone">

<div class="links">
<a href="#">Forgot email?</a>
</div>

<p style="font-size:12px;margin-top:25px;">

</p>

<div class="buttons">
<a class="create" href="#">Create account</a>
<button class="next">Next</button>
</div>

</div>

</body>
</html>
