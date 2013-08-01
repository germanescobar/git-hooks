<h2>git-hooks</h2>
=========

Estos dos script evitan que acidentalmente se hagan commit o push directamente sobre el master.


<h4>Requerimientos</h4>

  - github 1.8

<h4>¿Cómo usarlos?</h4>

  -Guarde los scripts dentro del repositorio, en el directorio .git/hooks<br/>
  -Asegurese de que los scripts tengan permisos de ejecución (chmod +x pre-push & chmod +x pre-commit)<br/>
  -Ejecute el commando "git init" en el directorio principal del repositorio<br/>
