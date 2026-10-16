# Blazor Basic Component Logo Sample

[![Blazor](https://img.shields.io/badge/Blazor-.NET-512BD4?logo=blazor&logoColor=white)](https://dotnet.microsoft.com/apps/asp.net/blazor)
[![C%23](https://img.shields.io/badge/C%23-Language-239120?logo=c-sharp&logoColor=white)](https://learn.microsoft.com/dotnet/csharp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

Este repositorio contiene un ejemplo pr谩ctico para aprender a crear y reutilizar componentes personalizados en **Blazor**. Muestra c贸mo encapsular marcado HTML y estilos dentro de un componente independiente (`LogoComponent.razor`) e integrarlo en distintas p谩ginas de la aplicaci贸n (`/`, `/counter`, `/weather`).

---

## 馃搶 驴Qu茅 incluye este proyecto?

1. **`LogoComponent.razor`**:
   * Componente Blazor que encapsula un contenedor estilizado con marco decorativo (`border`, `border-radius`, `padding`).
   * Renderiza el texto descriptivo *"SUPER Escuela gratuita."* junto a la imagen del logotipo (`LogoSinMicro.png`).

2. **Reutilizaci贸n en vistas principales**:
   * **`Home.razor` (`/`)**: Integraci贸n del logo al inicio de la p谩gina principal.
   * **`Counter.razor` (`/counter`)**: Inclusi贸n del logo en la vista del contador interactivo.
   * **`Weather.razor` (`/weather`)**: Inclusi贸n del logo en la vista de consumo de datos (`HttpClient`).

---

## 馃洜锔?Requisitos Previos

* [.NET SDK](https://dotnet.microsoft.com/download) (.NET 8.0 o superior recomendado).
* IDE o editor de c贸digo: Visual Studio, VS Code o JetBrains Rider.

---

## 馃殌 C贸mo Ejecutar el Proyecto

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/HoracioAldoTore/BlazorBasicComponentLogoSample.git
   ```

2. Ingresar al directorio del proyecto:
   ```bash
   cd BlazorBasicComponentLogoSample
   ```

3. Restaurar dependencias y ejecutar:
   ```bash
   dotnet run
   ```

4. Abre tu navegador e ingresa a la direcci贸n indicada en la consola (por ejemplo, `https://localhost:7000` o `http://localhost:5000`).

---

## 馃捇 Ejemplo de Uso del Componente

Para reutilizar el logotipo en cualquier otra p谩gina o componente `.razor`:

```razor
@page "/mi-pagina"

<LogoComponent />

<h1>Mi nueva p谩gina</h1>
```

---

## 馃搫 Licencia

Este proyecto est谩 disponible bajo la licencia **MIT**.