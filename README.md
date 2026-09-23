# Práctica 4 — Sabores en red

Código de arranque de la Práctica 4 de TC2007B.

Es la app de la Práctica 2 terminada: tres pantallas, navegación y ViewModel
compartido, con los datos todavía en memoria. Durante la práctica vas a cambiar
de dónde salen esos datos.

## Cómo empezar

1. Clona el repositorio y ábrelo en Android Studio.
2. Espera a que Gradle sincronice y corre la app: debes ver los cinco restaurantes.
3. Sigue la guía: https://startdroid.com/practicas/sabores-en-red.html

## Cómo trabajar

Haz un commit en cada checkpoint de la guía:

    git add -A ; git commit -m "checkpoint a1"

Si algo se rompe sin remedio, `git restore .` te regresa al último checkpoint bueno.

Los experimentos que rompen el código a propósito van en una rama:

    git switch -c experimento-c2                  # antes de romper nada
    git add -A ; git commit -m "experimento-c2"   # al terminar: guárdalo EN la rama
    git switch main                               # el código bueno vuelve intacto

Sin el commit en la rama, `git switch main` se lleva tus cambios contigo y
el código roto aparece en `main`.

## Uso de IA

Todo commit con código generado por IA debe declararlo con un trailer
`Co-Authored-By`. Ver la política completa en la guía.

## Entrega

Ver la rúbrica en la guía. Al subir tu repositorio, sube también la rama del
experimento: `gh repo create … --push` solo sube la rama actual.

    git push origin --all
