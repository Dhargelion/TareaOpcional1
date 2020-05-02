# Git Flow
>Nombre: Diego Corrales Vega
## ¿Que es git flow?
>Es un flujo de trabajo que se basa en el uso de git con el fin de brindar mayor control y organizacion en el proceso de integracion continua de un proyecto.
### ¿Porque implementar git flow?
Implemnetando git flow se puede aumentar la velocidad de entrega de codigo, ya que con el uso de git flow se puede reducir los errores humanos al momento de mezclar ramas.
Se recominda el uso de git flow cuando el equipo tiene una mas de 2 personas, ya que es en estos casos cuando se presentan problemas o complicaciones.
#### Implementacion de git flow
Para la implementacion de git flow se debe tener 2 ramas principales que son:
- master
- develop

Ademas de estas 2 ramas, se crea ramas auxiliares como:
- Feature
- Release
- Hotfix  
Las ramas de feature se originan a partir de la rama develop y se deben incorporar a la misma, y las ramas de releases se originan a partir de develop y deben incorporarse a la ramas develop y master, las ramas para correcciones (hoyfixes) se originan de master y deben incorporarse a la rama develop y master. 

Para iniciar un trabajo e implementar git flow en cada maquina y directorio donde tengamos el repositorio, la primera vez se debe ejecutar el comando git flow init.


