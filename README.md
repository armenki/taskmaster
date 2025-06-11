¿Qué aprendiste sobre el ciclo de vida de Maven?
Los perfiles deben activarse antes de invocar una fase para que sus propiedades estén disponibles durante el ciclo de vida.
Las propiedades definidas en perfiles o vía -D deben estar accesibles para la configuración de plugins para que tengan efecto durante la ejecución.
El orden en el que se pasa -P, -D y los goals importa para que Maven ejecute el ciclo de vida con los perfiles y configuraciones esperadas.

¿Cómo facilita Maven el trabajo en equipo y la reproducibilidad?
Asegura que todos los miembros del equipo usen las mismas versiones de las bibliotecas.
Utiliza un archivo pom.xml compartido para definir las configuraciones del proyecto.
Permite construir el proyecto en cualquier máquina con el mismo resultado.

¿Cuál fue el mayor reto al trabajar con dependencias?
Cuando dos o más dependencias traen diferentes versiones de una misma librería, puede causar errores en tiempo de compilación o ejecución.
Maven resuelve automáticamente las dependencias de tus dependencias, pero a veces no son las versiones que necesitas o causan incompatibilidades.

¿Por qué crees que Maven es tan usado en entornos empresariales?
Asegura que todos usen las mismas versiones de las bibliotecas.
Permite construir el proyecto en cualquier máquina con el mismo resultado.
Automatiza construcción, prueba y despliegue.
Abundante documentación y ayuda disponible.

¿Qué harías diferente si tuvieras que automatizar otro proyecto?
Definir perfiles (dev, prod, etc.) con propiedades bien diferenciadas y nombradas consistentemente para facilitar la activación y el uso correcto en los comandos.
Asegurar que cada plugin o dependencia esté declarado una sola vez, evitando duplicados que puedan causar warnings o fallos.
