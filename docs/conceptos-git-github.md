¿Qué puede hacer Git aunque GitHub no exista?
Respuesta:
Git permite llevar el control de versiones de un proyecto desde un computador, con el que podamos guardar cambios, recuperar versiones anteriores y ver que modificaciones se hicieron sin que subamos el proyecto a internet.

¿Por qué una rama reduce el riesgo de dañar main?
Respuesta:
Porque al crear la rama permite hacer cambios en una copai del proyect sin afectar la version principal, asi se pueden probar ideas o corregir errores y ya cuando todo funciona poder unir los cambios a la rama principal. 

¿Qué diferencia existe entre guardar un archivo y crear un commit?
Respuesta:
Guardar un archivo solo almacena los cambios en l computador, en cambios un commit registra esos cambios en el historil de Git con un mensaje que explica que se hizo.

¿Por qué un pull request no es lo mismo que un merge?
Respuesta:
El pull request es como la solicitud para que otra persona revise los cambios antes de unirlos, en cambio merge es la accion de integrar esos cambiosen la rama principal.

¿Qué evidencia permite saber quién cambió algo y por qué?
Respuesta:
El historial de commits, aqui aparece quien realizo el cambio, cuando lo hizo y el mensaje que explia el motivo de lo que se cambio.

Secuencias de trabajo:
1. Crear el repositorio: Se crea el espacio donde se almacenar el proyecto RIESGO QUE EVITA: que los archivos queden desorganizados
2. Crear una rama: Se crea para trabajar sin modificar la version principal RIESGO QUE EVITA: dañar el contenido de la rama MAIN
3. Hacer commits: se registran los cambios con mensajes claros RIEGO QUE EVITA: perder informacion o no saber que se modifico
4. Abrir un Pull request: Se solicita revisar los cambios antes de integrarlos RIESGO QUE EVITA: incorporar errores directamente al proyecto
5. Revisar: Otro integrante analiza los cambios y propone mejoras RIESGO QUE EVITA: deja pasar errores de estructura, ortografia o calidad
6. Corregir observaciones: Se realizan las modificaciones solicitadas durante la revision RIESGO QUE EVITA: fusionar cambios con problemas detectados
7. Fusionar: Despues de la aprobacion los cambios pasan a la rama principal RIESGO QUE EVITA: integrar trabajos sin revision previa

3 COMMITS
Docs: 
