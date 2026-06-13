# Documentación Técnica - Módulo de Contabilidad Personal

## Información General

**Aplicación:** Módulo de Contabilidad Personal
**Funcionalidades:** Registro de ingresos y gastos, visualización de balance total, filtros por fecha
**Stack Tecnológico:** HTML + JavaScript
**Repositorio:** https://github.com/luisernestosalas/contabilidad-personal
**URL de Producción:** https://contabilidad-personal-3y5kbv0zp-luisernestosalas-2775s-projects.vercel.app

## Características Principales

### Funcionalidades Core
- **Registro de Transacciones**: Permite registrar ingresos y gastos con descripción, monto y fecha
- **Balance Total**: Calcula y muestra el balance actual (ingresos - gastos)
- **Filtrado por Fecha**: Permite filtrar las transacciones por rangos de fechas específicos
- **Persistencia Local**: Los datos se almacenan localmente en el navegador

### Arquitectura Técnica

**Frontend:**
- HTML5 para estructura
- JavaScript vanilla para lógica de negocio
- CSS para presentación (implícito)

**Almacenamiento:**
- LocalStorage para persistencia de datos

**Despliegue:**
- Plataforma: Vercel
- Tipo: Aplicación estática

## Estructura del Proyecto


contabilidad-personal/
├── index.html          # Página principal
├── script.js          # Lógica de la aplicación
├── style.css          # Estilos (probable)
└