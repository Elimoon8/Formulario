<html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, inicial-scale=1.0">
    <meta http-equiv="X-UA-compatible" content="ie=edge">
    <link href="https://fonts.googleapis.com/css?family=lato:400,900">
    <link rel="stylesheet" href="CSS/main.css">
    <title>Formulario Control Asistencia</title>
  </head>
  <body>
    <nav>
      <div class="logo_imagen">
        <img src="imagen/Soldeaquino1.PNG" alt="">
        </div>
        </nav>
    <center>
    <form action="mailto:" method="post" enctype="text/plain">
      <table border="1" width="70%">
        <tbody>
          <tr>
            <td>Facultad</td>
            <td>
              <input Facultad="facultad" size="100" maxlength="100" type="text"> </td>
          </tr>
          <tr>
            <td>Espacio Académico</td>
            <td>
              <input name="Asignatura" size="50" maxlength="80" type="text"> </td>
          </tr>

          <tr>
            <td>Sede</td>
            <td>
              <select name="Sede">
            <option value="Seleccione">Seleccione</option>
            <option value="aquinate">Aquinate</option>
            <option value="Total">Edificio_total</option>
            <option value="angelico">DR_Angelico</option>
            <option value="Gregorio">Gegorio_XIII</option>
            <option value="santodomingo">Santo_Domingo</option>
            <option value="campus">Campus</option>
            <option value="Labotatorios">Laboratorios_ETM</option>
            <option value="Paltaforma">Plataforma</option>
          </select> </td>
          </tr>
          <tr>
            <td>Tipo de clase</td>
            <td>
              <select name="Tipo de Clase">
            <option value="Seleccione">Seleccione</option>
            <option value="personalizada">Tutoria_personalizada</option>
            <option value="magistral">Tutoria_Magistral</option>
            <option value="virtual">Tutoria_Virtual</option>
            <option value="Clase">No_hubo_Clase</option>

          </select> </td>
          </tr>
          <tr>
            <td>Horario</td>
            <td>
              <select name="Horario">
            <option value="Seleccione">Seleccione</option>
            <option value="uno">6:00_8:00p.m.</option>
            <option value="Dos">7:00_9:00p.m.</option>
            <option value="otro">Otro</option>

          </select> </td>
          </tr>
        </tbody>
      </table>
      <p>
        <input name="enviar" value="Enviar" type="submit">
        <input name="borrar" value="Borrar" type="reset">
      </p>
    </form>
  </body>
</html>
