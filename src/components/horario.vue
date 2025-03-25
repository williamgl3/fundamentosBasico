<template>
    <div class="container mt-4">
      <h3 class="text-center bg-primary text-white py-3 rounded shadow">📅 Horario de Clases</h3>
      <table class="table table-bordered table-striped table-hover mt-3 text-center shadow-sm">
        <thead class="table-dark text-white">
          <tr>
            <th>🕒 Hora</th>
            <th>📖 Lunes</th>
            <th>📖 Martes</th>
            <th>📖 Miércoles</th>
            <th>📖 Jueves</th>
            <th>📖 Viernes</th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="horario in horarios" :key="horario.hora">
            <td class="fw-bold">{{ horario.hora }}</td>
            <td><i class="fas fa-book-open"></i> {{ horario.lunes }}</td>
            <td><i class="fas fa-book-open"></i> {{ horario.martes }}</td>
            <td><i class="fas fa-book-open"></i> {{ horario.miercoles }}</td>
            <td><i class="fas fa-book-open"></i> {{ horario.jueves }}</td>
            <td><i class="fas fa-book-open"></i> {{ horario.viernes }}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        horarios: [
          { hora: '08:00 - 09:00', lunes: 'Matemáticas', martes: 'Historia', miercoles: 'Física', jueves: 'Química', viernes: 'Inglés' },
          { hora: '09:00 - 10:00', lunes: 'Español', martes: 'Biología', miercoles: 'Arte', jueves: 'Geografía', viernes: 'Deporte' },
          { hora: '10:00 - 11:00', lunes: 'Inglés', martes: 'Matemáticas', miercoles: 'Historia', jueves: 'Física', viernes: 'Química' },
          { hora: '11:00 - 12:00', lunes: 'Computación', martes: 'Filosofía', miercoles: 'Español', jueves: 'Música', viernes: 'Educación Física' }
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
  
  th, td {
    padding: 12px;
  }
  </style>
  