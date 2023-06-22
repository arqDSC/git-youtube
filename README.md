# Comandos útiles de Git

1.  git init                     ` INICIALIZA NUEVO REPOSITORIO `

2.  git add .                    ` AGREGA TODO A "STAGING AREA" `
3.  git reset .                  ` REVIERTE EL git add SACANDO TODO DEL "STAGING AREA" `

4.  git commit "[desc]"          ` SUBE TODO LO QUE HAY EN "STAGING AREA" A REPOSITORIO LOCAL [descripcion del commit]`

5.  git checkout -- .            ` REVIERTE ARCHIVOS AL ESTADO DEL ULTIMO commit `

6.  git log                      ` MUESTRA DETALLE DE commits EFECTUADOS `

7.  git commit --amend           ` PERMITE MODIFICAR EL ULTIMO commit EFECTUADO ` 
                                ` abre archivo git > modificar, cerrar y listo `

8.  git checkout -b rama-heroes  ` TRASLADA A NUEVA RAMA !!IMPORTANTE: NO TRABAJAR EN RAMA "main" / "master" `
8.  git branch                   ` MUESTRA LAS RAMAS `

9.  git checkout master          ` PASA A LA RAMA "master" o "main" `
9.  git checkout main            ` PASA A LA RAMA "master" o "main" `

9.  git merge rama-heroes        ` UNE DOS RAMAS `
10. git branch -d rama-heroes    ` ELIMINAR UNA RAMA `

11. git push                     ` ENVIA A REPOSITORIO REMOTO `
12. git commit -am "[desc]"      ` EJECUTA SIMULTANEAMENTE COMANDOS DE "git add ." Y "git commit" // [descripcion del commit] `

13. rama villanos creada