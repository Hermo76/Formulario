# Formulario
<!Doctype html>
<html lang="en" <head>
<meta charset="utf-8>" <meta http-equiv="x-ua-compatible" content="ie=edge">
<meta nome="viewport" content="width=device-widh,initial<-scale=1.0">
<title>FORMULARIO /Hermo</title>
</head>
<style>
    body {
        font-family: Arial, Helvetica, sans-serif;
        background-image: linear-gradient(to right, rgb(20, 147, 220), rgb(17, 54, 71));
    }
    
    .box {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        background-color: rgb(20, 147, 220) padding: 15px;
        border-radius: 50px;
        width: 50%;
    }
    
    fieldset {
        border: 3px solid darkblue;
    }
</style>

<body>
    <div class="box">
        <form action="">
            <fieldset>
                <legend><b>FORMULARIO </b></legend>
                <BR>
                <div class="imputbox">
                    <input type="text" nome="nome" id="nome" class="inputUser" required><br>
                    <label for="nome">NOME COMPLETO</label>
                </div>
                <br><br>
                <div class="imputbox">
                    <input type="email" name="email" id="email" class="imputUser" required><br>
                    <label for="EMAIL">EMAIL</label>
                </div>
                <br><br>
                <div class="imputbox">
                    <input type="tel" name="telefone" id="telefone" class="imputUser" required><br>
                    <label for="TELEFONE">TELEFONE</label>
                </div>
                <br><br>
                <p> SEXO: </p>
                <input type="radio" id="Feminino" nome="genero" value="Feminino" required>
                <label for="Feminino">feminino</label>
                <input type="radio" id="Masculino" nome="genero" value="Masculino" required>
                <label for="Masculino">Masculino</label>
                <input type="radio" id="Criança/Adolescente" nome="genero" value="Criança/Adolescente" required>
                <label for="Criança/Adolescente">Criança/Adolescente</label>
                <br><br>
                <div class="imputbox">
                    <label for="data_nascimento"><br>Data de Nascimento:</br></label>
                    <input type="date" nome="data_nascimento" id="data_nascimento" class="inputUser" required>
                </div><br>
                <br><br>
                <div class="imputbox">
                    <input type="text" nome="Cidade" id="Cidade" class="inputUser" required><br>
                    <label for="Cidade">Cidade</label>
                </div>
                <br><br>
                <div class="imputbox">
                    <input type="Estado" name="Estado id=" Estado " class="imputuser " required><br>
                    <label for="Estado ">Estado</label>
                </div>
                <br><br>
                <div class="imputbox ">
                    <input type="Endereço " name="Endereço " id="telefone " class="imputuser " required><br>
                    <label for="Endereço ">Endereço</label>
                </div>
                <br><br>
   <button>Enviar</button><samp></samp>
<a href="https://api.whatsapp.com/send?phone=5519999999999&text=Texto%20aqui"
    target="_blank"
    style="position:fixed;bottom:20px;right:30px;">
    <svg enable-background="new 0 0 512 512" width="50" height="50" version="1.1" viewBox="0 0 512 512" xml:space="preserve" xmlns="http://www.w3.org/2000/svg"><path d="M256.064,0h-0.128l0,0C114.784,0,0,114.816,0,256c0,56,18.048,107.904,48.736,150.048l-31.904,95.104  l98.4-31.456C155.712,496.512,204,512,256.064,512C397.216,512,512,397.152,512,256S397.216,0,256.064,0z" fill="#4CAF50"/><path d="m405.02 361.5c-6.176 17.44-30.688 31.904-50.24 36.128-13.376 2.848-30.848 5.12-89.664-19.264-75.232-31.168-123.68-107.62-127.46-112.58-3.616-4.96-30.4-40.48-30.4-77.216s18.656-54.624 26.176-62.304c6.176-6.304 16.384-9.184 26.176-9.184 3.168 0 6.016 0.16 8.576 0.288 7.52 0.32 11.296 0.768 16.256 12.64 6.176 14.88 21.216 51.616 23.008 55.392 1.824 3.776 3.648 8.896 1.088 13.856-2.4 5.12-4.512 7.392-8.288 11.744s-7.36 7.68-11.136 12.352c-3.456 4.064-7.36 8.416-3.008 15.936 4.352 7.36 19.392 31.904 41.536 51.616 28.576 25.44 51.744 33.568 60.032 37.024 6.176 2.56 13.536 1.952 18.048-2.848 5.728-6.176 12.8-16.416 20-26.496 5.12-7.232 11.584-8.128 18.368-5.568 6.912 2.4 43.488 20.48 51.008 24.224 7.52 3.776 12.48 5.568 14.304 8.736 1.792 3.168 1.792 18.048-4.384 35.52z" fill="#FAFAFA"/></svg>
</a>

    </div>
    </fieldset>
    </form>
    </div>
</body>l
