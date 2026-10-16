# Blazor Basic Component Logo Sample

Este repositorio contiene un ejemplo practico para aprender a crear y reutilizar componentes personalizados en **Blazor**. Muestra como encapsular marcado HTML y estilos dentro de un componente independiente (`LogoComponent.razor`) e integrarlo en distintas paginas de la aplicacion (`/`, `/counter`, `/weather`).

---

## Que incluye este proyecto?

1. **`LogoComponent.razor`**:
   * Componente Blazor que encapsula un contenedor estilizado con marco decorativo (`border`, `border-radius`, `padding`).
   * Renderiza el texto descriptivo *"SUPER Escuela gratuita."* junto a la imagen del logotipo (`LogoSinMicro.png`).

2. **Reutilizacion en vistas principales**:
   * **`Home.razor` (`/`)**: Integracion del logo al inicio de la pagina principal.
   * **`Counter.razor` (`/counter`)**: Inclusion del logo en la vista del contador interactivo.
   * **`Weather.razor` (`/weather`)**: Inclusion del logo en la vista de consumo de datos (`HttpClient`).

---

## Requisitos Previos

* [.NET SDK](https://dotnet.microsoft.com/download) (.NET 8.0 o superior recomendado).
* IDE o editor de c贸digo: Visual Studio, VS Code o JetBrains Rider.

---

## 馃殌 Como Ejecutar el Proyecto

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

4. Abre tu navegador e ingresa a la direccion indicada en la consola (por ejemplo, `https://localhost:7000` o `http://localhost:5000`).

---

## Ejemplo de Uso del Componente

Para reutilizar el logotipo en cualquier otra pagina o componente `.razor`:

```razor
@page "/mi-pagina"

<LogoComponent />

<h1>Mi nueva pagina</h1>
```

---

## Licencia

Este proyecto est谩 disponible bajo la licencia **MIT**.