# Taller Semana 6 de Programación IV

Pokédex en C# con ASP.NET MVC 5, .NET Framework 4.8 y PokéAPI.

## Descargar y ejecutar el proyecto completo

1. Descarga [S6P4_proyecto.zip](S6P4_proyecto.zip) y extrae su contenido en una ruta corta.
2. Instala en Visual Studio la carga **ASP.NET y desarrollo web** y el targeting pack de **.NET Framework 4.8**.
3. Abre `S6P4/S6P4/S6P4.csproj` (o la solución `.slnx` en una versión compatible).
4. Restaura los paquetes NuGet, recompila y ejecuta con F5 usando IIS Express.
5. Se abrirá la Pokédex; prueba `pikachu`, `25`, Siguiente, Anterior y una búsqueda inexistente.

El ZIP contiene el proyecto completo con sus recursos originales. Se excluyeron únicamente cachés de Visual Studio, binarios, archivos de usuario y paquetes restaurables de NuGet. La carpeta `codigo/` permite revisar los archivos principales sin extraer el ZIP; para ejecutar utiliza el ZIP completo, que incluye también todos los recursos CSS y JavaScript.

## Funcionamiento

- Listado de 20 Pokémon por página y detalles consultados en paralelo.
- Búsqueda por nombre o número.
- Ficha con imagen, tipo, descripción en español, altura, peso, estadísticas y habilidades.
- Mensaje de Pokémon no encontrado.
- API pública: https://pokeapi.co/api/v2/ (sin claves).

## Evidencias

El informe PDF y las capturas están disponibles en este repositorio. Las capturas se obtuvieron ejecutando los controladores y vistas Razor originales mediante System.Web y una pasarela HTTP local de verificación; no representan un despliegue en GitHub Pages. La ejecución habitual del proyecto es con Visual Studio e IIS Express.

## Referencia académica

Guía **Instrucciones Taller Semana 6 - 5463**, Programación IV, Universidad de Las Américas. Docente: Luis Fernando Aguas Bucheli.
