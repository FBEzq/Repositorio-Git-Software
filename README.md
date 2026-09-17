# Proyecto Grupal

Pequeño sitio web hecho en equipo para practicar Git y GitHub: control de versiones, ramas, commits individuales y merge.

## Integrantes

- Nombre 1 — sección de la que se encargó
- Nombre 2 — sección de la que se encargó
- Nombre 3 — sección de la que se encargó

## Estructura

```
proyecto-grupal/
├── index.html
├── estilos.css
└── README.md
```

## Cómo verlo

Clonar el repositorio y abrir `index.html` en el navegador. No necesita servidor ni instalación.

```
git clone URL_DEL_REPOSITORIO
```

## Flujo de trabajo usado

Cada integrante trabajó en su propia rama y fusionó sus cambios a `main` una vez terminados:

1. `git clone` del repositorio remoto.
2. Cada integrante creó su rama: `git switch -c nombre-rama`.
3. Modificaciones y commits propios en esa rama.
4. `git push -u origin nombre-rama` para subir la rama.
5. Vuelta a `main` (`git switch main`) y `git merge nombre-rama` para integrar los cambios.
6. Resolución de conflictos cuando dos ramas tocaron las mismas líneas.
7. `git push origin main` con el proyecto ya integrado.

## Historial de commits

Ver con:

```
git log --oneline --graph --all
```
