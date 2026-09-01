# ☕ Calculadora de Propina Inteligente - GastroTech

Este proyecto es una aplicación web interactiva desarrollada para el sector de la restauracíon en España. Esta diseñada para que los camareros de una cafeteria o restaurante puedan calcular de forma instantánea y transpatente la propina estándar (10%) y el total general a pagar por una mesa directamente desde una tableta o dispositivo móvel.

## 📸 Vista Previa del Proyecto

Interfaz fluida con tarjeta centralizada de forma absoluta y resultados dinámicos:

![Captura de la calculadora de propina](preview-2.png)

## 🚀 Tecnología Utilizadas

- **HTML5:** Estruturacíon semática con inputs numéricos de control de dados.
- **CSS3 Moderno:** Centralización absoluta con Flexbox y unidades relativas a la pantalla (`min-height: 100vh`), sombras suaves de profundidad (`box-shadow`), y pseudo-clases dinámicas (`:focus`, `:hover`).

## 💡 Soluciones de Ingeniería Aplicadas

- **Alineación Adaptable Nivel UI:** Uso de `min-height: 100vh` para garantizar que la aplicación se mantenga perfectamente centrada en la vertical sin importar las dimensiones físicas del dispositivo del camarero.
- **Formateo Financiero Nativo:** Integración con la API oficial `Intl.NumberFormat` configurada para España (`es-ES`, `EUR`) para mostrar los importes con los puntos de millares y el símbolo del euro colocados de forma correcta según el estándar de la eurozona.
- **Inyección Limpia de Componentes:** Uso de plantillas literales con el carácter de la acentuación grave ( ` ) para inyectar bloques HTML completos en el DOM, optimizando la legibilidad del código.