<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>namora cmg?</title>
</head>



<body>
  <div id="conteudo">
   
    <h2>ACEITA NAMORAR CMG??</h2>
<button onclick="sim()">SIM</button>
<button onclick = "desvia(this)" onmouseover="desvia(this)">NÃO</button>
</div>
</body>
 

<style>
 #conteudo
 {background: #fc0ac0;
  width: 100%;
  height: 100%;
  position: fixed;
  top: 0;
  left: 0;
  padding: 25px;
  text-align: center;
}

  </style>


<script> function sim() {
 alert("Ótimo agr estamos namorando hehehe, te encontro no intervalo")
} 


function desvia(t){
    var btn = t;
    btn.style.position='absolute';
    btn.style.bottom=geraposition(10,90);
   btn.style.left=geraposition(10,90);
    console.log("opaaa, desviei hehehe...");
} 


function geraposition (min, max) {
      return Math. random() * (max - min) + min + "%";
}




</script>

</html>
