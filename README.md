# Carpintería Zajo

Sistema de gestión y documentación oficial para **Carpintería Zajo**, negocio de carpintería artesanal ubicado en Yanga, Veracruz, México.

---

## Descripción

Este repositorio contiene la aplicación web desarrollada en **Angular** para la gestión de recursos digitales de Carpintería Zajo, incluyendo generación de documentos oficiales, políticas y materiales de operación del negocio.

---

## Requisitos

- Node.js 18 o superior
- npm 9 o superior
- Angular CLI 17 o superior

---

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/usuario/carpinteria-zajo.git
cd carpinteria-zajo

# Instalar dependencias
npm install
```

---

## Uso

### Servidor de desarrollo

```bash
ng serve
```

La aplicación estará disponible en `http://localhost:4200`.

### Compilar para producción

```bash
ng build --configuration production
```

Los archivos generados se ubican en la carpeta `dist/`.

---

## Estructura del proyecto

```
carpinteria-zajo/
├── src/
│   ├── app/                  # Módulos y componentes de Angular
│   ├── assets/               # Recursos estáticos (imágenes, fuentes)
│   └── environments/         # Configuración por entorno
├── docs/                     # Documentos oficiales generados
│   └── politica_privacidad.pdf
├── angular.json
├── package.json
└── README.md
```

---

## Dependencias principales

| Paquete         | Versión  | Uso                        |
|-----------------|----------|----------------------------|
| `@angular/core` | ^17.x    | Framework principal        |
| `@angular/cli`  | ^17.x    | Herramientas de desarrollo |

---

## Documentos incluidos

- **Política de Privacidad** — Documento oficial conforme a la legislación mexicana (LFPDPPP).

---

## Información del negocio

| Campo      | Detalle                  |
|------------|--------------------------|
| Nombre     | Carpintería Zajo         |
| Ubicación  | Yanga, Veracruz, México  |
| Giro       | Carpintería artesanal    |

---

## Licencia

Uso privado — © Carpintería Zajo. Todos los derechos reservados.
