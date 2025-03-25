<template>
    <div class="container mt-4">
      <h3 class="text-center bg-primary text-white py-2 rounded">Lista de Alumnos</h3>
      <table class="table table-bordered table-striped mt-3">
        <thead class="table-primary text-center">
          <tr>
            <th>Control</th>
            <th>Nombre</th>
            <th>Carrera</th>
            <th>Gusto</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="alumno in alumnos" :key="alumno.id">
            <td>{{ alumno.id }}</td>
            <td>{{ alumno.nombre }}</td>
            <td>{{ alumno.carrera }}</td>
            <td>{{ alumno.gusto }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        alumnos: [
          { id: 12345, nombre: 'Juan', carrera: 'ISC', gusto: 'Fútbol' },
          { id: 12346, nombre: 'Antonio', carrera: 'TICS', gusto: 'Videojuegos' },
          { id: 12347, nombre: 'Nicolas', carrera: 'ISC', gusto: 'Música' },
          { id: 12348, nombre: 'Perez', carrera: 'ISC', gusto: 'Cine' },
          { id: 12349, nombre: 'Maria', carrera: 'TICS', gusto: 'Baile' },
          { id: 12350, nombre: 'Luis', carrera: 'IM', gusto: 'Lectura' },
          { id: 12351, nombre: 'Fernanda', carrera: 'IM', gusto: 'Fotografía' },
          { id: 12352, nombre: 'Carlos', carrera: 'ISC', gusto: 'Cocina' },
          { id: 12353, nombre: 'Elena', carrera: 'TICS', gusto: 'Teatro' },
          { id: 12354, nombre: 'Roberto', carrera: 'IMA', gusto: 'Natación' },
          { id: 12355, nombre: 'Gabriela', carrera: 'IM', gusto: 'Pintura' },
          { id: 12356, nombre: 'Daniel', carrera: 'ISC', gusto: 'Ajedrez' },
          { id: 12357, nombre: 'Sofía', carrera: 'TICS', gusto: 'Senderismo' }
        ]
      };
    }
  };
  </script>
  
  <style>
  .container {
    max-width: 900px;
    margin: auto;
  }
  </style>
  