# 🌐 Quantiva Portal

> SPA moderna y modular desarrollada con Blazor WebAssembly, orientada a presentar la propuesta tecnológica, visión y soluciones de **Quantiva**.

---

## 🚀 Tecnologías principales

- **Blazor WebAssembly** — Frontend interactivo con C#
- **Bootstrap 5** — Estilo responsivo y moderno
- **.NET 8** — Framework subyacente
- **GitHub Actions** — CI/CD automatizado
- **Soomee** — Previsualización visual del portal y métricas del despliegue
- **ASP.NET Core Web API** — Backend para contenido dinámico
- **Clean Architecture** — Separación de responsabilidades y escalabilidad

---

## 📂 Estructura del proyecto

QuantivaPortal/ 
├── QuantivaPortal.Client/ # SPA Blazor WASM 
├── QuantivaPortal.Server/ # API REST para contenido dinámico 
├── QuantivaPortal.Shared/ # Modelos, constantes, extensiones compartidas 
└── .github/workflows/ # Flujo CI/CD con GitHub Actions


---

## 🧱 Componentes reutilizables

- `SectionHeader.razor`
- `FeatureCard.razor`
- `PostPreview.razor`
- `TeamMember.razor`
- `TechBadge.razor`
- `ThemeToggle.razor`
- `ContactForm.razor`

> Todos diseñados con Bootstrap y CSS aislado para modularidad.

---

## ⚙️ Despliegue Automático

Cada `push` a la rama `main`:
- Ejecuta el build en GitHub Actions
- Publica automáticamente en Soomee usando `soomee-io/github-action`
- Genera una nueva vista previa del portal con estadísticas

Consulta el workflow en `.github/workflows/build-and-deploy.yml`

---

## 🎯 Objetivo del proyecto

**Quantiva** nace con la misión de crear soluciones modulares, escalables y elegantes en el mundo del desarrollo de software, integrando principios sólidos de arquitectura como Clean Architecture y una fuerte identidad visual.

---

## 🤝 Contribuciones

¡Las ideas, sugerencias y mejoras son bienvenidas! Abrir un issue o pull request para aportar.

---

## 📸 Vista previa

![Quantiva Portal Preview](SoomeePreview.png)

---

## 📬 Contacto

Para más información o colaboraciones:

- ✉️ [ligiapuertas@gmail.com](mailto:ligiapuertas@gmail.com)
- 🌐 [quantiva.soomee.io](https://quantiva.soomee.io) *(demo del portal)*

---
