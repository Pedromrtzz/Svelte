<script>

</script>


<link rel="stylesheet" href="css/formularioAcceso.css">

<div class="contenedor-formulario">

    <div class="titulo-formulario">
        <h1>Formulario Acceso</h1>
    </div>

    <div class="formulario">
        <form>
            <!-- Nombre -->
            <label for="name">Nombre</label>
            <input type="text" id="nombre" placeholder="Ingresa tu nombre">
    
            <!-- Apellidos -->
            <label for="subname">Apellidos</label>
            <input type="text" id="apellido" placeholder="Ingresa tus apellidos">
    
            <!-- Correo -->
            <label for="email">Correo</label>
            <input type="email" id="correo" placeholder="Ingresa tu correo">
    
            <!-- Productos -->
            <label for="curso">Curso</label>
            <select name="curso" id="curso" >
                <option value="DAM">Desarrollo de Aplicaciones Multiplataforma</option>
                <option value="DAW">Desarrollo de Aplicaciones Web</option>
                <option value="ASIR">Sistemas MicroInformáticos</option>
                <option value="Marketing">Marketing</option>
                <option value="AFI">Administración y Finanzas</option>
            </select>

            <label for="genero">Género</label>
            <select name="genero" id="genero" >
                <option value="masc">Masculino</option>
                <option value="fem">Femenino</option>
                <option value="otro">Otro</option>

            </select>
    
            <!-- Botón de envío -->
            <button type="submit">Enviar Formulario</button>
        </form>
    </div>
    


</div>