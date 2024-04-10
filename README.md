<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
<style>
*{padding: 0;margin: 0;box-sizing: border-box;}
.container{
height: 100%;
display: grid;
justify-content: center;
background-color: whitesmoke;
flex-wrap: wrap;
text-align: center;
}
.box{
margin-top: 30px;
padding: 20px ;
width: 350px;
height: 380px;
text-align: center;
border: 1px solid rgb(216, 211, 211);
background-color: white;
}
.box.a{
margin-top: 10px;
height: 80px;
}
#hedding{
font-size: 40px;
font-weight: 400;
font-family: Harlow Solid Italic;
margin-bottom: 10px;
}
#int{
width: 250px;
height: 30px;
margin: 20px 30px 10px 30px;
background-color: whitesmoke;
padding: 10px;
border: 1px solid rgb(216, 211, 211);
}
#a{
width: 250px;
height: 30px;
margin: 20px 30px 10px 30px;
background-color: rgb(85, 85, 223);
padding-bottom: 0px;
border: 1px solid rgb(216, 211, 211);
border-radius: 5px;
color: white;
cursor: pointer;
}
#pho{
border-radius: 10px;
cursor: pointer;
}
 hr {
      width: 100%;
      margin: 10px 0;
    }
</style>
</head>
<body>
<div class="container">
<div class="box">
<h2 id="hedding">Instagram</h2>
<input id="int" type="text" placeholder="Telefono, usuario o correo electronico" required>
<input id="int" type="password" placeholder="Contraseña" required>
<input id="a" type="submit" value="Entrar"><br>
<hr><br>
<a href="https://www.facebook.com">
  <img src="f.jpg" alt="Imagen de Facebook" height="20" width="20" />
  Iniciar sesion con Facebook
</a><br><br>
<p>¿Has olvidado tu contraseña?</p>
</div>
<div class="box a">
<p style="font-size: 19px;color: rgb(83, 77, 77);">¿No tienes una cuenta?<span
style="color: blue;cursor: pointer;">Registrate</span></p>
</div>
<p style="padding: 20px;font-size: 20px;"> Descarga la Aplicacion</p>
<center><span><img id="pho"src="cc.png"width="250px" height="60px"></span></center>
<br><br><br><br><br><br><br>
</div>

</body>
</html>
