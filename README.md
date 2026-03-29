# Formulario-de-Cadastro
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
</head>
<body>
  <form method="POST">
  
        <h1>Cadastro</h1>

        <fieldset>
            <h3>Dados Pessoais</h3>

            <label for="nome">Nome completo:</label>
            <input type="text" id="nome" name="nome" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="senha">Senha:</label>
            <input type="password" id="senha" name="senha" required min="6">

            <label for="data">Data de nascimento:</label>
            <input type="date" id="data" name="data">

            <label for="foto">Foto de perfil:</label>
            <input type="file" id="foto" name="foto">
        </fieldset>

        <fieldset>
            <h3>Seu Gênero</h3>

            <label>
                <input type="radio" name="genero" value="masculino"> Masculino
            </label>

            <label>
                <input type="radio" name="genero" value="feminino"> Feminino
            </label>

            <label>
                <input type="radio" name="genero" value="outro"> Outro
            </label>
        </fieldset>

        <fieldset>
            <h3>Interesses</h3>

            <label><input type="checkbox" name="interesses" value="tecnologia"> Tecnologia</label>
            <label><input type="checkbox" name="interesses" value="esportes"> Esportes</label>
            <label><input type="checkbox" name="interesses" value="musica"> Música</label>
            <label><input type="checkbox" name="interesses" value="jogos"> Jogos</label>
        </fieldset>

        <fieldset>
            <h3>Infomações</h3>

            <label for="pais">País:</label>
            <select id="pais" name="pais">
                <option value="Argentina">Argentina</option>
                <option value="EUA">Estados Unidos</option>
                 <option value="Espanha">Espanha</option>
                  <option value="França">França</option>
                   <option value="Brasil">Brasil</option>
            </select>

            <label for="cor">Cor favorita:</label>
            <input type="color" id="cor" name="cor">

            <label for="satisfacao">Nível de satisfação (0 a 10):</label>
            <input type="range" id="satisfacao" name="satisfacao" min="0" max="10" >
        </fieldset>

        
        <fieldset>
            <h3>De sua opinião sobre o formulário</h3>

            <label for="mensagem">Digite sua mensagem:</label>
            <textarea id="mensagem" name="mensagem"></textarea>
        </fieldset>

        <fieldset>
            <h3>Ações</h3>

            <button type="submit">Enviar</button>
            <button type="reset">Limpar</button>
        </fieldset>

    </form>
</body>
</html>
