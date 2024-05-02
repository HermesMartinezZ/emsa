# Guía de Uso - Instalación de Energía EMSA

Este repositorio contiene el código fuente y los archivos necesarios para la implementación del servicio de instalación de energía del EMSA. El servicio está modelado con Camunda BPM y se implementa con Spring Boot.

## Requisitos Previos

- Java 17 o una versión superior debe estar instalada en su sistema.
- Camunda BPM Run 7 debe estar configurado y ejecutándose en su entorno de desarrollo.

## Pasos de Instalación

1. **Descarga del Proyecto:**
   - Clone o descargue el proyecto desde el repositorio.

2. **Descompresión del Archivo:**
   - Descomprima el archivo descargado en el directorio deseado.

3. **Apertura en el Editor:**
   - Abra el proyecto en su IDE preferido. Se recomienda IntelliJ IDEA para una mejor experiencia de desarrollo.

4. **Ejecución del Programa:**
   - Ejecute el programa desde su IDE. Asegúrese de que Camunda BPM Run esté en ejecución.

5. **Inicio del Servicio:**
   - Vaya al directorio de Camunda BPM Run y ejecute el archivo `start.bat`.

6. **Acceso al Servicio:**
   - Una vez que el servicio esté en funcionamiento, se abrirá automáticamente en su navegador predeterminado.
   - Si no se abre automáticamente, acceda al servicio mediante la siguiente dirección: [http://localhost:8080/camunda/app/tasklist/default/#/login](http://localhost:8080/camunda/app/tasklist/default/#/login).
   
7. **Inicio de Sesión:**
   - Ingrese al servicio utilizando las siguientes credenciales:
     - Usuario: admin
     - Contraseña: admin

## Uso del Servicio

Una vez dentro del programa, siga estos pasos:

1. **Inicio del Proceso:**
   - En la pestaña superior derecha, seleccione "Start Process" y elija el proceso "EMSA" en la ventana desplegable.
   - Ingrese los datos solicitados y haga clic en "Start".

2. **Verificación de Documentación:**
   - Recargue la página y seleccione la opción "All Tasks" en el lateral derecho.
   - Seleccione el proceso "Verificar Documentación - EMSA" y reclámelo.
   - Complete el formulario según sea necesario.

3. **Recibir Respuesta del Cliente:**
   - Repita el proceso anterior para la tarea "Recibir Respuesta del Cliente".

4. **Mostrar Términos y Condiciones:**
   - Repita el proceso para la tarea "Mostrar Términos y Condiciones".

5. **Firmar el Contrato:**
   - Repita el proceso para la tarea "Firmar el Contrato".

6. **Asignar Fecha Tentativa:**
   - Ingrese una fecha y hora tentativa y complete la tarea.

7. **Verificar Disponibilidad del Técnico:**
   - Repita el proceso para las tareas "Verificar Disponibilidad del Técnico" y "Verificar si el Cliente Acepta la Fecha".

8. **Verificar Materiales:**
   - Repita el proceso para la tarea "Verificar Materiales".

9. **Asignar Técnico Eléctrico:**
   - Ingrese el nombre del técnico asignado y complete la tarea.
   - 
Una vez completado el proceso, la instalación del servicio comenzará automáticamente. Espere hasta que en la consola de IntelliJ IDEA vea el mensaje indicando que el servicio se está instalando. Luego, vuelva al navegador, recargue la página y seleccione la tarea

10. **Registrar en el Sistema lo Realizado y Complicaciones:**
    - Después de completar todas las tareas anteriores, seleccione la nueva tarea "Registrar en el Sistema lo Realizado y Complicaciones" y complete el formulario.

11. **Determinar Costo de la Factura:**
    - Ingrese los valores para determinar el costo de la factura y complete la tarea.

 para completar el proceso.
