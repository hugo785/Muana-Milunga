// Definindo variáveis
$primary-color: #0062cc;
$secondary-color: #5a6268;
$font-family: 'Roboto', sans-serif;

// Aplicando variáveis em estilos
body {
  font-family: $font-family;
  background-color: #f4f4f4;
}

header {
  background-color: $primary-color;
  padding: 20px;
  color: white;

  h1 {
    font-size: 2rem;
  }
}

button {
  background-color: $secondary-color;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;

  &:hover {
    background-color: darken($secondary-color, 10%);
  }
}
