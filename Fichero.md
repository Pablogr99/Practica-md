  ## Comandos basicos V
 
   Deshacer múltiples cambios en el respositorio:
  
  `git reset --soft <id_commit>`
  `git reset --mixed <id_commit>`
  `git reset --hard <id_commit>`
  
  Listar archivos que git no controla:
  
  `git clean -n`
  
  Eliminar archivos que git no controla:
  
  `git clean -f`
  
  Ignorar archivos en el repositorio: .gitignore
  ## Comandos basicos VI
 
   Listar el contenido del respositorio de git:
  
  `git ls-tree master`
  `git ls-tree master^^^`
  `git ls-tree master~3`
  
  Log en una línea:
  
  `git log --oneline`
  
  Log con los tres últimos commits en una línea:
  
  `git log --oneline -3`
  
  Para más opciones consultar documentación de git.

  
