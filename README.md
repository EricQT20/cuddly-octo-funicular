# reniec_pnp
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Plataforma de Consultas Institucionales</title>
  <link rel="stylesheet" href="css/style.css"/>
</head>
<body class="dark-mode">
  <header>
    <img src="assets/logos/logo_pnp.png" alt="PNP" class="logo"/>
    <img src="assets/logos/logo_reniec.png" alt="Reniec" class="logo"/>
    <img src="assets/logos/logo_minedu.png" alt="Minedu" class="logo"/>
    <h1>Plataforma Informática de Identidad Confidencial</h1>
  </header>

  <main>
    <h2>Seleccione una consulta</h2>
    <ul id="consulta-lista">
      <li>FICHA RENIEC</li>
      <li>DNI VIRTUAL</li>
      <li>ARBOL GENEALÓGICO</li>
      <li>TITULARES DE LÍNEA</li>
      <li>CERTIFICADO DE NACIDO VIVO</li>
      <li>ANTECEDENTES POLICIALES</li>
      <li>ANTECEDENTES JUDICIALES</li>
      <li>ANTECEDENTES PENALES</li>
      <li>ACTA DE NACIMIENTO</li>
      <li>ACTA DE DEFUNCIÓN</li>
      <li>REPORTE INFOCORP</li>
      <li>COPIA LITERAL SUNARP</li>
      <li>OPSITEL LÍNEAS TITULARES</li>
      <li>MIGRACIONES HISTORIAL</li>
      <li>FISCALÍA - PROCESOS</li>
      <li>POLICÍA NACIONAL DEL PERÚ</li>
      <li>RENADESPPLE - SENTENCIAS</li>
      <li>DENUNCIAS Y ACTAS</li>
      <li>REQUISITORIAS - DETENCIONES</li>
      <li>DIRECCIONES</li>
      <li>EMPRESAS Y CARGOS</li>
      <li>CÓNYUGES Y PAREJAS</li>
      <li>DÓNDE TRABAJA</li>
      <li>SUELDO / CUÁNTO GANA</li>
      <li>PROPIEDADES SUNARP</li>
      <li>DÓNDE ESTUDIA</li>
      <li>CONSULTA MTC</li>
      <li>BÚSQUEDA POR FOTO</li>
      <li>CONSULTA SUNAT</li>
      <li>CONSULTA VEHICULAR</li>
      <li>SISFOH INTEGRANTES</li>
      <li>MULTAS ELECTORALES</li>
      <li>NÚMEROS DE TELÉFONO</li>
      <li>CORREOS ELECTRÓNICOS</li>
      <li>INFORMACIÓN FINANCIERA</li>
      <li>CONSULTA SUNEDU / MINEDU</li>
      <li>CONSULTA SUCAMEC</li>
      <li>CONSULTA PAPELETAS</li>
    </ul>
  </main>

  <footer>
    <p>Atendido por la Policía Nacional del Perú - Plataforma 2025</p>
  </footer>
</body>
</html>

body.dark-mode {
  background-color: #121212;
  color: #ffffff;
  font-family: Arial, sans-serif;
}

header {
  text-align: center;
  padding: 20px;
}

.logo {
  width: 80px;
  margin: 5px;
}

main {
  padding: 20px;
}

ul#consulta-lista {
  list-style: none;
  padding: 0;
}

ul#consulta-lista li {
  padding: 10px;
  background-color: #1f1f1f;
  margin: 8px 0;
  border-radius: 8px;
  border-left: 5px solid #00acc1;
}

footer {
  text-align: center;
  padding: 10px;
  background-color: #1a1a1a;
  position: fixed;
  bottom: 0;
  width: 100%;
}
