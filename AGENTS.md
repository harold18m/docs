# Instrucciones del proyecto de documentación

## Sobre este proyecto

- Documentación pública de **ReallyQuickEmails** (API de email para desarrolladores), construida sobre [Mintlify](https://mintlify.com).
- Las páginas son archivos MDX con frontmatter YAML (`title`, `description`).
- La configuración (tema, colores, navegación) vive en `docs.json`.
- El contenido se escribe en **español** (copy para desarrolladores).
- La fuente de verdad del comportamiento de la API es el código de `reallyquickemails-node-api`, no suposiciones.

## Terminología

- Usa "proyecto" (no "workspace"), "API key" / "Secret Key", "sender" / "remitente".
- Modos: **Live** (`sk_proj_*` / `sk_live_*`) y **Test** (`sk_test_*`).

## Preferencias de estilo

- Voz activa y segunda persona ("tú"), español neutro (sin voseo).
- Frases concisas — una idea por frase.
- Negrita para elementos de UI: Haz clic en **Integraciones → API Keys**.
- Formato de código para nombres de archivo, comandos, rutas y referencias de código.

## Componentes

Componentes globales de Mintlify usados en estas docs: `<Info>`, `<Warning>`, `<Note>`, `<Tip>`,
`<Steps>`/`<Step>`, `<Tabs>`/`<Tab>`, `<AccordionGroup>`/`<Accordion>`, `<Columns>`/`<Card>`.
Los iconos de `<Card>` usan la librería **lucide** (configurada en `docs.json`).
