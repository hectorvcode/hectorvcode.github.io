# Instrucciones

Antes que nada vamos a crear una nueva branch para trabajar.

- En la terminal o CMD, escribe el comando `git checkout -b feature/yourgithubname`

Esto crea una nueva rama y te cambia a ella automáticamente.

Cuando termines tu diseño de mobile, esperamos recibir tu primer PR (pull request).

¿Cómo lo haces?

Una vez estés listo para enviar tu PR entonces deberás hacer lo de siempre.

- `git add .` (para guardar todos los cambios)
- `git commit -m 'nombre para tus cambios'` Puedes usar mobile design, luego tablet design como sugerencias. Si envías un commit en español, perderás -10 puntos de experiencia.
- `git push origin feature/yourgithubname` (nombre de la rama según se indicó arriba)
- Luego de esto, tus cambios ya estarán en GitHub y deberás crear el PR. [**Mira este video**](https://youtu.be/0g4YZCdiOfg) que te muestra como hacerlo.

1. Como trabajaremos con git y GitHub, debes realizar al menos 3 pull request al repo original, uno con el diseño finalizado de mobile, otro con tablet y otro con desktop.
2. Visita **[Lorem Picsum](https://picsum.photos/)**, este será el diseño a copiar.
3. No debes implementar los espacios que allí se mencionan con urls, solo queremos el texto título y un párrafo debajo.
4. Las imágenes deben ir en el mismo orden que el diseño presenta.
5. Se debe omitir la sección de List Images e Images Details.
6. En el `footer` podemos dejar solo texto o bien usar el icono de preferencia omitiendo las brands del diseño.
7. Empieza con la regla mobile first. Luego tablet y por último desktop. Esta página es responsiva por lo que si activas tus herramientas de desarrollo podrás ver como se adapta a diferentes tamaños.

Nota: si los compiladores fallan usa sass desde la terminal.
```sass --watch assets/styles/styles.scss:assets/styles/styles.css```
