# Cliente01
<?php


$nomeCliente = $_GET["nome"];

?>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salvar Cliente</title>
</head>
<body>
    <table border="1">
        <tr>
            <td>Nome Completo</td>
            <td><?php echo $nomeCliente; ?></td>
            <td>cpf</td>
            <td><?php echo &cpf; ?></td>
            <td>rg</td>
            <td><?php echo &indentidade; ?></td>
            <td>fone</td>
            <td><?php echo &telefone; ?></td>
            <td>Gmail</td>
            <td><?php echo &Gmail; ?></td>  
        </tr>
    </table>
</body>
</html>
