Last login: Thu May  5 16:44:41 on ttys000
candelaccrespi@MacBook-Air-de-Candela ~ % pwd 
/Users/candelaccrespi
candelaccrespi@MacBook-Air-de-Candela ~ % cd Desktop    
candelaccrespi@MacBook-Air-de-Candela Desktop % cd Universidad
candelaccrespi@MacBook-Air-de-Candela Universidad % cd 5º\ de\ carrera/periodismo-de-datos/Trabajo\ final/candelaccrespi 
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % git status
rebase interactivo en progreso; sobre 0f67572
Last command done (1 command done):
   pick fb99b9f api
No quedan más comandos.
Estás aplicando un rebase de la rama 'main' sobre '0f67572.
  (corrige los conflictos y ejecuta "git rebase --continue")
  (usa "git rebase --skip" para omitir este parche)
  (usa "git rebase --abort" para volver a tu rama original)

Cambios a ser confirmados:
  (usa "git restore --staged <archivo>..." para sacar del área de stage)
	nuevos archivos: .DS_Store

Rutas no fusionadas:
  (usa "git restore --staged <archivo>..." para sacar del área de stage)
  (usa "git add/rm <archivo>..." como sea apropiado para marcar la resolución)
	borrados por nosotros:  API-Pandas-Folium.ipynb

Cambios no rastreados para el commit:
  (usa "git add <archivo>..." para actualizar lo que será confirmado)
  (usa "git restore <archivo>..." para descartar los cambios en el directorio de trabajo)
	modificados:     .DS_Store

candelaccrespi@MacBook-Air-de-Candela candelaccrespi % git rebase --continue
API-Pandas-Folium.ipynb: needs merge
Tienes que editar todos los conflictos de fusión y luego
marcarlos como resueltos usando git add
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % git rebase --skip
error: no se puede realizar rebase: Tienes cambios fuera del área de stage.
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % it restore --staged <archivo>...
zsh: no such file or directory: archivo
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % git restore --staged <archivo>...
zsh: no such file or directory: archivo
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % pwd  
/Users/candelaccrespi/Desktop/Universidad/5º de carrera/periodismo-de-datos/Trabajo final/candelaccrespi
candelaccrespi@MacBook-Air-de-Candela candelaccrespi % cd ..
candelaccrespi@MacBook-Air-de-Candela Trabajo final % cd candelaccrespi2 
candelaccrespi@MacBook-Air-de-Candela candelaccrespi2 % git clone https://github.com/Pontedatos/candelaccrespi.git
Clonando en 'candelaccrespi'...
remote: Enumerating objects: 66, done.
remote: Counting objects: 100% (66/66), done.
remote: Compressing objects: 100% (60/60), done.
remote: Total 66 (delta 31), reused 11 (delta 4), pack-reused 0
Recibiendo objetos: 100% (66/66), 595.66 KiB | 487.00 KiB/s, listo.
Resolviendo deltas: 100% (31/31), listo.
candelaccrespi@MacBook-Air-de-Candela candelaccrespi2 % nano 

  GNU nano 6.3                     Búfer nuevo                      Modificado  
# **Metodología de la Práctica Final**

## **Crear el repositorio**∑

















¿Guardar el búfer modificado?                                                   
 S Sí
 N No           ^C Cancelar
