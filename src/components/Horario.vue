<template>

    <div class="container">
        <h3 class="mt-4">Horatio de clases de Sistemas</h3>
        <table class="table">
            <thead>
                <tr>
                    <th scope="col">Horario</th>
                    <th scope="col">Lunes</th>
                    <th scope="col">Martes</th>
                    <th scope="col">Miercoles</th>
                    <th scope="col">Jueves</th>
                    <th scope="col">Viernes</th>
                </tr>
            </thead>
            <tbody>
                <tr v-for="(h, index) in horario" :key="index">
                <td>{{ h.hora }}</td>
            </tr>



            </tbody>
        </table>
    </div>

</template>
<script setup>

const Horario = ref([
    { hora: '07:00 - 09:00', lunes: 'Inteligencia Artificial (ACS - Vasquez Martínez Josué)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '09:00 - 11:00', lunes: 'Administracion De Redes (RDS - Garcia Llamandez Astrid)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '11:00 - 13:00', lunes: 'Desarrollo En La Nube (RDS - Perez García Auriel)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '13:00 - 15:00', lunes: 'Desarrollo Con Realidad Aumentada (LC3 - Deman)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '15:00 - 17:00', lunes: 'Desarrollo Con Realidad Aumentada (LDS - Deman)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '17:00 - 19:00', lunes: 'Desarrollo Agil (ACS - Vasquez Martínez Josué Israel / Grunov)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '19:00 - 21:00', lunes: 'Administracion De Redes (RDS - Garcia Llamandez Astrid)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '21:00 - 23:00', lunes: 'Inteligencia Artificial (MAGS - Vasquez Martínez Josué)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '23:00 - 01:00', lunes: 'Desarrollo Con Realidad Aumentada (ACS - Deman)', martes: '', miercoles: '', jueves: '', viernes: '' },
    { hora: '10:00 - 11:00', lunes: '', martes: 'Desarrollo Agil (ACS - Vasquez Martínez Josué Israel / Grunov)', miercoles: '', jueves: '', viernes: '' },
    { hora: '11:00 - 12:00', lunes: '', martes: 'Desarrollo En La Nube (4 - Perez García Auriel Delande)', miercoles: '', jueves: '', viernes: '' },
    { hora: '14:00 - 16:00', lunes: '', martes: 'Taller De Investigacion II (9 - Antonio Jimenez Saltea / Grunov)', miercoles: '', jueves: '', viernes: '' }
]);


</script>
