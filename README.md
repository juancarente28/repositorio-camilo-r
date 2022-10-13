# repositorio-camilo-r
mi primer repositorio
autor: Camilo Rentería
fecha: 12/10/2022
<!DOCTYPE html>
<html lang="es">
<head>
   <meta charset="utf-8" />
    <meta http-equiv="x-UA-compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Primer pagina web</title>
</head>
<body>
   <h2>titulos y subtitulos</h2>
    <h1>tamaño 1</h1>
    <h2>tamaño 2</h2>
    <h3>tamaño 3</h3>
    <h4>tamaño 4</h4>
    <h5>tamaño 5</h5>
    <h6>tamaño 6</h6><br>

    <h2>Parrafo</h2>
    <p>Este es mi primer parrafo en html, este es mi primer parrafo en html,
    este es mi primer parrafo en html, este es mi primer parrafo html,
    este es mi primer parrafo html,<br> este es mi primer parrafo en html,
    este es mi primer parrafo en de html, este es mi primer parrafo en html,</p>

    <p>Este es mi segundo parrafo en html, este es mi segundo parrafo en html
     este es mi segundo parrafo en html, este es mi segundo parrafo en html
     este es mi segundo parrafo en html,</p>
     
    <h2>imagen</h2>
     <img src="imagenes/estadio.jpg" alt="estadio mexicano" width="350px" height="250px"><br>
     
    <h2>Links</h2>
    <a href="https://twitter.com/InfoDIM?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" target="_blank">link a dim</a><br>
                    
    <p>imagen como link</p>
    <a href="https://twitter.com/InfoDIM?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor" target="_blank"><img src="imagenes/logo.png" alt="logo del rojo"           width="350px" height="250px"></a>               

    <h2>TABLAS</h2>
    <table>
        <tr>
            <th>nombre</th>
            <th>partidos</th>
            <th>goles</th>
        </tr>
        <tr>
            <td>cambindo</td>
            <td>15</td>
            <td>nueve</td>
        </tr>
        <tr>
            <td>luciano</td>
            <td>doce</td>
            <td>4</td>
        </tr>
        <tr>
            <td>blacho</td>
            <td>13</td>
            <td>6</td>
        </tr>
    </table><br>  

    <h2>listas</h2>
    <p>listas desordenada</p>
    <ul>
        <li>yulian</li>
        <li>cadavid</li>
        <li>mosquera</li>
        <li>arboled</li>                  
    </ul>

    <p>lista ordenada</p>
    <ol>
       <li>yulian</li>
       <li>cadavid</li>
       <li>mosquera</li>
       <li>arboled</li> 
    </ol>

    <p>descripción</p> 
    <dl>
        <dt>Cadavid</dl>
        <dd>bueno por arriba y en pelota parada</dd>
        <br>
        <dt>mosquera</dl>
            <dd>bueno por arriba y veloz</dd>
    </dl>
    <br><br>
    
     <h2>imput de selección multiple</h2>
    <input type="checkbox" id="topping1" name="topping1" value="chispas">
    <label for="topping1">chispas de chocolate</label><br>
    <input type="checkbox" id="topping2" name="topping2" value="nuez">
    <label for="topping2">nuez</label><br>
    <input type="checkbox" id="topping3" name="topping3" value="fresas">
    <label for="topping3">fresas</label>
    <br><br>
    
     <h2>imput de selección única</h2>
    <input type="radio" id="roja" name="salsas" value="roja">
    <label for="roja">roja</label><br>
    <input type="radio" id="maiz" name="salsas" value="maiz">
    <label for="maiz">maiz</label><br>
    <input type="radio" id="humo" name="salsas" value="humo">
    <label for="humo">humo</label><br>
    <input type="radio" id="bbq" name="salsas" value="bbq">
    <label for="bbq">bbq</label>
    <br><br>
    
     <h2>select</h2>
    <label for="hamburguesas">Disponibles</label>
    <select id="hamburguesas" name="hamburguesas">
        <option value="queso">queso</option>
        <option value="doble queso">doble queso</option>
        <option value="ranchera">ranchera</option>
        <option value="grande">grande</option>
        <option value="grande doble queso">grande doblequeso</option>
    </select> 
    <br><br>
    
     <h2>select con Imput</h2>
    <label for="bebidas">Elige tu bebida</label><br>
    <Input list="bebidas">
    <datalist id="bebidas">
        <option value="uva">
        <option value="cuatro">    
        <option value="coca-cola">
        <option value="manzana">
        <option value="naranja">
        <option value="lionada">
        <option value="uva">        
    </datalist>    
    <br><br>
    
    <h2>Input de Fecha</h2><br>
    <input type="date" id="fecha1" name="fecha1"><br>
    <input type="datetime-local" id="fecha2" name="fecha2"><br>
    <input type="week" id="fecha3" name="fecha3"><br>
    <input type="time" name="fecha4" id="fecha4"><br>
    <input type="month" id="fecha5" name="fecha5"><br><br>

    <hr>
     <h2>Input de archivo</h2><br>
    <input type="file" id="archivo1" name="archivo" multiple><br><br>

    <input type="file" id="archivo1" name="archivo" multiple size="6mb"><br><br>

    <h2>Input de color</h2><br>
    <input type="color" id="color1" name="color1"><br><br>

    <h2>Input de Rango</h2><br>
    <label for="vol">volumen (entre 0 y 50):</label><br>
    <input type="range" id="vol" name="vol" min="0" max="50"><br>

    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
   
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
