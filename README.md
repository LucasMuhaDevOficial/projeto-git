<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadastro</title>
    <link rel="stylesheet" type="text/CSS" href="Document.css" media="Screen">
</head>
<body>
    
    <div class="campo">
      <h1 id="titulo">Cadastro De DEVs</h1>
      <p id="subtitulo">Complete Suas Informações</p>
      <br>
    </div class="campo">

    <fieldset class="Grupo">
        <div class="campo">
            <label for="Nome"><strong>Nome</strong></label>
            <input type="text" name="nome" id="nome" required>
        </div class="campo">

        <div class="campo">
            <label for="Sobrenome"><strong>Sobrenome</strong></label>
            <input type="text" name="Sobrenome" id="Sobrenome" required>
        </div class="campo">

        <div class="campo">
            <label for="Email"><strong>Email</strong></label>
            <input type="email" name="email" id="email" required>
        </div class="campo">
    </fieldset class="Grupo">

    <div class="campo">
        <label><strong>De Qual Lado Da aplicação Você Desenvolve</strong></label>
        <label>
            <input type="radio" name="devweb" value="Front-End">Front-End
            <input type="radio" name="devweb" value="Back-End">Back-End
            <input type="radio" name="devweb" value="FullStack">FullStack
    </div class="campo">

    <div class="campo">
        <label for="Senioridade"><strong>Senioridade</strong></label>
        <select id="senioridade">
            <option selected disabled value="">Escolha</option>
            <option>Junior</option>
            <option>Pleno</option>
            <option>Sênior</option>
        </select>
    </div class="campo">

<fieldset class="Grupo">
    <div id="check">
        <label><strong>De Qual Lado Da aplicação Você Desenvolve</strong></label><br><br>
        <input type="checkbox" name="tecnologia1" id="tecnologia1" value="HTML">
        <label for="tecnologia1">HTML</label>
        <input type="checkbox" name="tecnologia2" id="tecnologia2" value="CSS">
        <label for="tecnologia2">CSS</label>
        <input type="checkbox" name="tecnologia3" id="tecnologia3" value="Javascript">
        <label for="tecnologia3">Javascript</label>
        <input type="checkbox" name="tecnologia4" id="tecnologia4" value="PHP">
        <label for="tecnologia4">PHP</label>
        <input type="checkbox" name="tecnologia5" id="tecnologia5" value="C#">
        <label for="tecnologia5">C#</label>
        <input type="checkbox" name="tecnologia6" id="tecnologia6" value="Python">
        <label for="tecnologia6">Python</label>
        <input type="checkbox" name="tecnologia7" id="tecnologia7" value="Java">
        <label for="tecnologia7">Java</label>
    </div class="campo">
</fieldset class="Grupo">

<div class="campo">
    <br>
    </label><strong>Conte Um Pouco Da Sua Experiência</strong><label>
    <textarea placeholdr row="6" style="width:26em"></textarea>
</div class="campo">

<button class="Botão">Concluido</button>
<head>
<body>

*{
    margin:0;
    padding:0;
}

#titulo{
   font-family: sans-serif;
   color:#59429d;
   margin-left: 7%;
}

#subtitulo{
    font-family: sans-serif;
   color:#59429d;
   margin-left: 10%;
}

fieldset{
    border:0;
}

body{
    background-color: #F0F8FF;
    font-family: sans-serif;
    font-size: 1em;
    color:#59429d;
    margin-left: 36%;
    margin-top: 2%;
    justify-content: center;
}

input, select, textarea, button{
    border-radius: 5px;
}

.campo{
    margin-bottom: 1em;
}

.campo label{
    margin-bottom: 0.2em;
    color:#59429d;
    display:block;
}

fieldset.grupo.campo{
    float:left;
    margin-right: 1em;
}

.campo input [type="text"], .campo input [type="email"], .campo select, .campo textarea{
    padding:0.2em;
    border:1px solid #59429d;
    box-shadow: 2px, 2px, 2px rgb(0,0,0.2);
    Display:block;
}

.campo select, option{
    padding-right: 1em;
}

.campo input:focus, .campo select:focus, .campo textarea:focus{
    background: #E0E0F8;
}

.botão{
    font-size: 1.2em;
    background:#59429d;
    border:0;
    margin-bottom: 1em;
    color:#ffff;
    padding:0.2em, 0.6em;
    box-shadow: 2px, 2px, 2px rgba(0,0,0,0.2);
    text-shadow: 1px, 1px, 1px rgba(0,0,0,0.5);
    position:absolute;
    top:90%;
    left:50%;
    margin-right: -50%;
    transform: translate(-50%,-50%);
}

.botão:hover{
    background:#ccbbff;
    box-shadow: inset 2px 2px 2px rgba(0,0,0,0.2);
    text-shadow: none;
}

#check{
    display: inline-block;
}
