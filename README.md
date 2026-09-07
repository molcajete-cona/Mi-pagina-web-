/* Estilos generales de la página */
body {
  font-family: Arial, sans-serif;
  color: #333;
  background-color: #298A43;
  background-image: url('fondo.jpg');
  background-size: cover;
  background-position: center;
  margin: 0;
  padding: 20px;
}

header h1 {
  text-align: center;
  color: #fff;
  text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.5);
}

/* Grilla para ordenar las tarjetas */
.contenedor {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  max-width: 1000px;
  margin: 0 auto;
}

/* Tarjetas tipo bloc de notas */
.bloc-de-notas {
  background-color: #ffffff;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  width: 280px;
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.bloc-de-notas h2 {
  margin: 0;
  font-size: 1.2rem;
  color: #298A43;
}

textarea {
  width: 100%;
  height: 100px;
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 8px;
  resize: vertical;
  box-sizing: border-box;
}

/* Botón de guardar */
.btn-guardar {
  background-color: #298A43;
  color: white;
  border: none;
  padding: 10px;
  border-radius: 4px;
  cursor: pointer;
  font-weight: bold;
  transition: background-color 0.2s ease;
}

.btn-guardar:hover {
  background-color: #1f6832;
}
