<!DOCTYPE html>
<html lang="pt">
<head>
<meta charset="UTF-8">
<title>PRO Logistics - Prestação de Contas Mensal</title>
<style>
body{
font-family:Arial;
margin:40px;
background:#f4f6f8;
}

.container{
max-width:1000px;
margin:auto;
background:white;
padding:30px;
border-radius:12px;
box-shadow:0 0 12px rgba(0,0,0,0.08);
}

.header{
display:flex;
justify-content:space-between;
align-items:center;
border-bottom:2px solid #ddd;
padding-bottom:20px;
margin-bottom:25px;
}

.logo{
font-size:26px;
font-weight:bold;
}

h2{
margin-top:30px;
border-bottom:1px solid #ddd;
padding-bottom:8px;
}

table{
width:100%;
border-collapse:collapse;
margin-top:15px;
}

th, td{
border:1px solid #ccc;
padding:10px;
text-align:left;
}

input{
width:100%;
border:none;
padding:6px;
font-size:14px;
}

.total{
font-weight:bold;
font-size:18px;
margin-top:20px;
}

textarea{
width:100%;
height:100px;
padding:10px;
}

button{
margin-top:25px;
padding:12px 25px;
background:black;
color:white;
border:none;
cursor:pointer;
border-radius:6px;
}
</style>
</head>

<body>

<div class="container">

<div class="header">
<div>
<h1>PRESTAÇÃO DE CONTAS MENSAL</h1>
<p>Competência:
<input type="text" placeholder="Ex: Maio 2026"></p>

<p>Período:
<input type="text" placeholder="01/05 a 31/05"></p>

<p>Emissão:
<input type="date"></p>
</div>

<div class="logo">
PRO Logistics
</div>
</div>


<h2>1. Resumo Financeiro</h2>

<table>
<tr>
<th>Descrição</th>
<th>Valor (€)</th>
</tr>

<tr>
<td>Receitas do período</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Despesas Administrativas</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Despesas Operacionais</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Seguros</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Infraestrutura</td>
<td><input type="number"></td>
</tr>
</table>


<h2>2. Demonstrativo de Despesas</h2>

<table>
<tr>
<th>Código</th>
<th>Categoria</th>
<th>Descrição</th>
<th>Valor (€)</th>
</tr>

<tr>
<td><input value="001"></td>
<td><input></td>
<td><input></td>
<td><input type="number"></td>
</tr>

<tr>
<td><input value="002"></td>
<td><input></td>
<td><input></td>
<td><input type="number"></td>
</tr>

<tr>
<td><input value="003"></td>
<td><input></td>
<td><input></td>
<td><input type="number"></td>
</tr>

</table>


<h2>3. Obrigações Futuras</h2>

<table>
<tr>
<th>Compromisso</th>
<th>Próximo Ciclo (€)</th>
<th>Vencimento</th>
</tr>

<tr>
<td><input></td>
<td><input type="number"></td>
<td><input type="date"></td>
</tr>

</table>


<h2>4. Movimento de Caixa</h2>

<table>
<tr>
<th>Item</th>
<th>Valor (€)</th>
</tr>

<tr>
<td>Saldo Inicial</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Entradas</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Saídas</td>
<td><input type="number"></td>
</tr>

<tr>
<td>Saldo Final</td>
<td><input type="number"></td>
</tr>

</table>


<h2>5. Indicadores de Gestão</h2>

<table>
<tr>
<th>Indicador</th>
<th>Percentual</th>
</tr>

<tr>
<td>Despesas sobre faturamento</td>
<td><input></td>
</tr>

<tr>
<td>Custo operacional</td>
<td><input></td>
</tr>

<tr>
<td>Margem líquida</td>
<td><input></td>
</tr>

</table>


<h2>6. Observações</h2>

<textarea></textarea>

<div class="total">
Responsável:
<input type="text">
</div>

<button onclick="window.print()">
Gerar PDF / Imprimir
</button>

</div>

</body>
</html>
