<html>
<head>
  <title>Formulário Simples</title>
</head>
<body>

  <h2>Cadastro de Usuário</h2>

  <form method="post" action="#">
    <label>Nome:</label><br>
    <input type="text" name="nome"><br><br>

    <label>Email:</label><br>
    <input type="email" name="email"><br><br>

    <label>Idade:</label><br>
    <input type="number" name="idade"><br><br>

    <label>Gênero:</label><br>
    <select name="genero">
      <option value="">Selecione</option>
      <option value="masculino">Masculino</option>
      <option value="feminino">Feminino</option>
      <option value="outro">Outro</option>
    </select><br><br>

    <label>Observações:</label><br>
    <textarea name="observacoes" rows="4" cols="30"></textarea><br><br>

    <input type="submit" value="Enviar">
    <input type="reset" value="Limpar">
  </form>

</body>
</html>
