<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1> Pedido de Receita Médica </h1>
    <form method="post" action="Pedido.jsp">
        
        
         Nome Completo:
         <br>
         <input  type="text" name="nome"> 
         <br>
         Email: <input type="email" name="email"><br>
         
         Insira a data de hoje:<input type="date" name="diadehoje">
         <br>       
        
         Quantos meses?
         <br>
         <input type="radio" name="mês"> 1 Mês
         <input type="radio" name="mês"> 2 Mêses
         <input type="radio" name="mês"> 3 Mêses
         <br>
         Qual remédio?
         <br>
         <select name="nome do remédio">
         <option>Tandrilax</option>
         <option>Neovalgina</option>
         <option>Dipirona</option>
         <option>Rivotril</option>
         <option>Lipomax</option>
         </select>
         <br>
         Qual melhor dia da semana para você pegar seu remédio?
         <br>
         <input type="checkbox" name="Segunda Feira" value="sim"> Segunda Feira
         <input type="checkbox" name="Terça Feira" value="sim"> Terça Feira
         <input type="checkbox" name="Quarta Feira" value="sim"> Quarta Feira
         <input type="checkbox" name="Quinta Feira" value="sim"> Quinta Feira
         <input type="checkbox" name="Sexta Feira" value="sim"> Sexta Feira
         <br>
         Deixe no campo abaixo suas observações: <br>
         <textarea name="obs" rows="10" cols="10"></textarea>
          <br>
         <input type="submit">
    </form>
</body>
</html>
