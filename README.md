# Myfirstrepo
Your weight in the Solar System

<!DOCTYPE html>
<html>
  <head>
    <title> Your weight in the System Solar</title>
    <style type="text/css">
    body
        {
            background-color: #AAAAFF;
            color: black;
            font-family: Helvetica;
        }
        strong
        {
            background-color: #FFAAAA;
        }
      </style>
  </head>
<body>
  <h1>Your weight in Other planet</h1>
  <p>In the earth your weight is different than other Planets</p>
  <script>
    var usuario = prompt("Cual es tu peso?");
    var planet = parseInt(prompt("Choose your planet\n 1. Mars\n 2.Jupiter\n 3. Venus\n 4. Saturno\n 5. Urano\n 6. Neptuno\n 7. Mercurio "));
    var peso = parseFloat(usuario);
    var g_earth = 9.8;
    var g_mars = 3.7;
    var g_jupiter = 24.7;
    var g_venus = 8.8;
    var g_saturno = 10.4;
    var g_urano = 8.8;
    var g_neptuno = 11.1;
    var g_mercurio = 3.7;
    var peso_final;
    var name = "";
    if (planet == 1)
    {
      peso_final = peso * g_mars / g_earth;
      name = "mars";
    }
    else if (planet == 2)
    {
      peso_final = peso * g_jupiter / g_earth;
      name = "Jupiter";
    }
    else if (planet == 3)
    {
      peso_final = peso * g_venus / g_earth;
      name = "Venus";
    }
    else if (planet == 4)
    {
      peso_final = peso * g_saturno / g_earth;
      name = "Saturno";
    }
    else if (planet == 5)
    {
      peso_final = peso * g_urano / g_earth;
      name = "Urano";
    }
    else if (planet == 6)
    {
      peso_final = peso * g_neptuno / g_earth;
      name = "Neptuno";
    }
    else if (planet == 7)
    {
      peso_final = peso * g_mercurio / g_earth;
      name = "Mercurio";
    }
    else
    {
      peso_final = 1000000
      name = "Kripton"
    }
    peso_final = parseInt(peso_final);
    document.write("Tu peso en " + name + " es <strong> " + peso_final + " kilos</strong>");
  </script>
</body>
</html>
