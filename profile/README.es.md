# Revive360

**Software nuevo y abierto para una consola de veinte años.** Creamos aplicaciones reales para la Xbox 360 de hoy, desde cero y en abierto, apoyándonos en el ecosistema homebrew existente.

[English](README.md) · [Português](README.pt-BR.md)

## Catálogo y tres niveles

- **Revive360 Project** — repo dentro de [revive360](https://github.com/revive360), reglas/seguridad de la org, PR revisada y releases del CI firmadas/atestadas; validez continua mientras cumpla las reglas. Sello verde con mascota, el más fuerte.
- **Reviewed · vX.Y.Z** — repo del autor, solo versión/hash/fecha revisados. Binario nuevo o sustituido vuelve a la cola manual de menor prioridad por llegada (objetivo 14 días); **versión actual no revisada** hasta la aceptación. Autor compila, org comprueba hash y vínculo al código; sin canal de actualización de la org. Si el autor desaparece, el sello caduca.
- **Community list** — descubrimiento sin sello: **No verificado por Revive360; no es una recomendación; úsalo bajo tu responsabilidad.** Puede retirarse en cualquier momento.

El [catálogo](https://github.com/revive360/catalog) es la fuente de verdad; los sellos enlazan a las fichas y muestran válido, versión actual no revisada, caducado o revocado. Ser miembro no es certificación. La org asume responsabilidad operativa por sus repos y las versiones externas revisadas dentro del alcance documentado; un repo de miembro fuera del catálogo es solo del autor. Usar nombre/sello sin ficha es uso indebido. Revisión no es auditoría completa; software **tal cual**, sin garantía del sello.

**Tube360** — app nativa de YouTube, MIT, responsable [Pedro](https://github.com/PedroHenrique0713). El [repo real](https://github.com/PedroHenrique0713/tube360) sigue en la cuenta del autor. El registro Project local es una **demostración de un estado futuro dentro de la org**, sin transferencia ni certificación real. No se lista otra app real.

Seguridad en cualquier nivel: respuesta en **48 h**, revocación inmediata si es grave. Releases Project: CI automático tras revisión y prueba del binario exacto en consola real; revisiones externas FIFO, objetivo **14 días**; Community según capacidad. Nadie revisa su app **excepto el fundador Pedro**, incluso al máximo nivel. [Checklist y límites](../REVIEW.md).

## Reglas

1. Solo código abierto creado por miembros, o bibliotecas abiertas con licencias compatibles.
2. Nada de piratería, juegos, claves, SDK filtrado de Microsoft ni exploits distribuidos. BadUpdate/RGH son requisitos del usuario, fuera de la organización.
3. Cada proyecto tiene responsable y licencia propia. MIT, GPL y otras licencias abiertas conviven; trasladar código exige respetar su licencia.
4. Todo lanzamiento se prueba en una consola real.
5. Se permite la IA como herramienta; quien firma responde por el código.
6. Comunidad en portugués, español e inglés.

## Proponer una aplicación o unirse

Abre una issue **App proposal** o **Join Revive360** en este repositorio. Describe la aplicación, su responsable, licencia y procedencia de dependencias. Un proyecto existente entra solo con el consentimiento de su responsable. No hace falta ser miembro para contribuir. Lee [CONTRIBUTING](../CONTRIBUTING.md), [GOVERNANCE](../GOVERNANCE.md) y el [Código de Conducta](../CODE_OF_CONDUCT.md). Aceptamos los tres idiomas.

Gracias a [xenosworks](https://github.com/xenosworks), por [xsdk](https://github.com/xenosworks/xsdk), [vulkan4xenon](https://github.com/xenosworks/vulkan4xenon) y [SDL-xenon](https://github.com/xenosworks/SDL-xenon), y a [Free60/libxenon](https://github.com/Free60Project/libxenon). Revive360 complementa este trabajo y conserva sus créditos.

## Personas, riesgo y contacto

Hoy solo el fundador Pedro es dueño de la org. Miembros entran con acceso mínimo y avanzan por contribuciones; no hay promoción automática a dueño. DCO obligatorio. El fundador decide cambios con 14 días de aviso público; restricciones urgentes de seguridad son inmediatas. El autor puede recuperar su proyecto; archivar tras 12 meses sin mantenimiento o por infracciones. La org no recibe ni reparte donaciones por ahora.

**El homebrew puede causar bloqueos en Xbox Live, pérdida de datos y daños a la consola; úsalo bajo tu responsabilidad.** Ninguna recopilación sin opt-in; login/tokens permanecen en la consola. Términos de terceros a cargo del autor; prohibido romper DRM/paywall.

Hasta diciembre, seguridad por private vulnerability reporting y contacto público por issues/Discussions. `CONTACT_DECEMBER_2026_TODO`: añadir email/dominio confirmados después.

Xbox y Xbox 360 son marcas de Microsoft. Revive360 es independiente y no está afiliada ni avalada por Microsoft, Google o los proyectos mencionados.
