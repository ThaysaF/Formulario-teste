Teste de um formulário em HTML e CSS

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" type="text/css" href="Formulario.css" media="screem">

    <title>Cadastro</title>
</head>
<body>

    <div>
        <h1 id="titulo">Cadastro dos Artistas</h1>
        <p1 id="subtitulo">Complete suas Informações</p1>
        <br>
    </div>

<form>
    <fieldset class="grupo">
        <div>
            <label for="nome"><strong>Nome</strong></label>
            <input type="text" name="nome" id="nome" required>
        </div>

        <div class="campo">
            <label for="sobrenome"><strong>Sobrenome</strong></label>
            <input type="text" name="sobrenome" id="sobrenome" required>
        </div>
    </fieldset>

    <div class="campo">
        <label for="email"><strong>Email</strong></label>
        <input type="email" name="email" id="email" requied>
    </div>

    <div class="campo">
        <label><strong>Qual área você exerce:</strong></label>
        <label>
            <input type="radio" name="designer" value="Design gráfico" checked>Design Gráfico
        </label>
        <label>
            <input type="radio" name="designer" value="Publicidade">Publicidade
        </label>
        <label>
            <input type="radio" name="designer" value="Marketing">Marketing
        </label>
    </div>

    <div class="campo">
        <label for="nivel de conhecimento"><strong>Nível de Conhecimento</strong></label>
        <select id="nivel de conhecimento">
            <option selected disabled value="">Selecione</option>
            <option>Básico</option>
            <option>Intermediario</option>
            <option>Avançado</option>
        </select>
    </div>

    <fieldset class="grupo">
        <div id="check">
            <label><strong>Selecione os aplicativos de edição que utiliza</strong></label><br>
            <input type="checkbox" id="edição1" name="edição1" value="Photoshop">
            <label for="edição1">Photoshop</label>
            <input type="checkbox" id="edição2" name="edição2" value="Canva">
            <label for="edição2">Canva</label>
            <input type="checkbox" id="edição3" name="edição3" value="Illustrator">
            <label for="edição3">Illustrator</label>
            <input type="checkbox" id="edição4" name="edição4" value="Lightroom">
            <label for="edição4">Lightroom</label>
            <input type="checkbox" id="edição5" name="edição5" value="CorelDraw">
            <label for="edição5">CorelDraw</label>
        </div>
    </fieldset>

    <div class="campo">
        <br>
        <label><strong>Conte um pouco sobre sua experiência</strong></label>
        <textarea row="6" style="width: 26em" id="experiência" name="experiência"></textarea>
    </div>

    <button class="botao" type="submit">Concluído</button>

</form>

</body>
</html>
