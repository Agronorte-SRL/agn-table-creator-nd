# agn-table-creator-nd — Documentación técnica

## Resumen
- **Qué es:** app Angular para generar tablas, formularios y definiciones de API contra un backend propio (componentes `api-creator`, `formulario`, `general-form`; servicio `api.service.ts` que hace `POST` a `http://localhost:8000`). Herramienta interna de desarrollo para el backend genérico de Agronorte.
- **Estado:** legado / sin uso (julio 2024).
- **Autor principal:** AugustoAgronorte (17 commits).
- **Último commit:** 2024-07-02 — "Add table creator". Rama por defecto: `master`.

## Stack
Angular 18 + TypeScript.

## Sistemas conectados
- Backend local en `http://localhost:8000` (probablemente el backend Django de `agn-backendpyext-nd`; No determinado con certeza). Header `Authorization` con valor de prueba fijo.

## Cómo se corría
`npm install` y `ng serve`, con el backend corriendo en el puerto 8000.

## Recomendación
**Archivar**: herramienta de desarrollo de 2024 sin cambios ni uso posterior.