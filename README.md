<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>votação</title>
</head>
<body>

    <h1>Eleição</h1>
    candidato A 
   
    <input id="Votos candidato A" type="number"><br>

    candidato B 
   
    <input id="votos candidato B" type="number"><br>

    votos em Branco
  
    <input id="votos em branco" type="number"><br>
    
    votos nulos
 <input id="votos nulos" type="number"><br>

 <button onclick="calcular()">Resultado da Eleição:

    <div id="resultado_da_eleição">

    </div>


</body>
</html>
<script>

function calcular(){ resultado_da_eleição.innerHTML = 'Votos candidato A' + ('+votos_candidato_A.value+') + (Number(votos_candidato_A.value) + 80)


}

</script>

