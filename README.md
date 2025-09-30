# 🐷 Piggy Bank Slots

![Status](https://img.shields.io/badge/status-in%20development-yellow)
![License](https://img.shields.io/badge/license-MIT-blue)

**Piggy Bank Slots** es un juego de tragaperras educativo/recreativo desarrollado como proyecto de portfolio. El juego presenta una mecánica única de "hucha progresiva" con sistema de bonus Hold & Win.

> ⚠️ **Nota importante**: Este es un proyecto educativo. No involucra dinero real ni apuestas reales. Todos los créditos son virtuales.

## 🎮 Concepto del Juego

Una slot machine moderna con temática de ahorro y dinero. El jugador llena una hucha virtual mediante símbolos scatter especiales (monedas) que aparecen aleatoriamente. Cuando la hucha se llena completamente, se activa un bonus tipo "Hold & Win" con respins y premios acumulativos.

## ✨ Características Principales

- 🎰 **5 rodillos × 3 filas** con 10 líneas de pago
- 🐷 **Sistema de hucha progresiva** con llenado aleatorio
- 💰 **4 tipos de monedas scatter**: Bronce, Plata, Oro y Diamante
- 🎁 **Bonus Hold & Win** con mecánica de respins
- 💎 **4 niveles de Jackpot**: Mini, Minor, Major y Grand
- 📊 **Sistema de apuestas escalable** (0.10€ - 10.00€)
- 🎨 **Diseño cartoon minimalista** moderno y limpio

## 🎨 Diseño Visual

### Estilo
- **Tipo**: Cartoon minimalista
- **Inspiración**: Diseño limpio tipo Duolingo/Crossy Road

### Paleta de Colores
- **Fondo**: Morado oscuro con degradados
- **Hucha**: Rosa neón con detalles dorados
- **Acentos**: Dorado para premios, verde neón para acciones positivas
- **Monedas**: Bronce, plata, oro y diamante con efectos brillantes

## 🎰 Mecánicas de Juego

### Símbolos Regulares (de menor a mayor valor)
1. 💶 Billete 5€
2. 💶 Billete 10€
3. 💶 Billete 20€
4. 💶 Billete 50€
5. 💳 Tarjeta de crédito
6. 💰 Bolsa de dinero
7. 🪙 Lingote de oro

### Símbolos Especiales
- **Wild**: 🐷 Hucha dorada (sustituye símbolos regulares)
- **Scatter**: 🪙 Monedas (Bronce/Plata/Oro/Diamante) - llenan la hucha

### Sistema de Hucha
La hucha se llena mediante un sistema de puntos oculto (0-100%):
- **Moneda Bronce**: +8% (40% probabilidad)
- **Moneda Plata**: +20% (30% probabilidad)
- **Moneda Oro**: +35% (20% probabilidad)
- **Moneda Diamante**: +50% (10% probabilidad)

Cuando alcanza el 100%, la hucha explota y activa el **Bonus Hold & Win**.

## 🎁 Bonus: Hold & Win

### ¿Cómo funciona?
1. La hucha explota y se activa el modo bonus
2. Comienzas con **3 respins**
3. Solo aparecen monedas con valores multiplicadores
4. Cada moneda que cae:
   - Se queda fija en su posición
   - Resetea los respins a 3
5. El bonus termina cuando se acaban los respins
6. Se suman todos los valores de las monedas

### Monedas en el Bonus (Multiplicadores × BET)
- 🥉 **Bronce**: x1, x2
- 🥈 **Plata**: x5, x10
- 🥇 **Oro**: x25, x50
- 💎 **Diamante**: x100

### Jackpots Especiales
- ⭐ **MINI**: x15
- ⭐ **MINOR**: x30
- ⭐ **MAJOR**: x100
- ⭐ **GRAND**: x1000

> 🎊 **Bonus especial**: Si llenas TODA la pantalla (15 posiciones) → Premio adicional

## 💰 Sistema de Apuestas

### Configuración
- **Créditos iniciales**: 1,000.00€ (virtuales)
- **Apuesta por defecto**: 1.00€
- **Rango de apuestas**: 0.10€ - 10.00€
- **Incrementos**: 0.10€, 0.25€, 0.50€, 1.00€, 2.00€, 5.00€, 10.00€

### Cálculo de Premios
Todos los premios son **multiplicadores del BET**:

**Ejemplo con BET de 1.00€:**
- Moneda Oro x25 en bonus = 25.00€
- GRAND Jackpot x1000 = 1,000.00€

**Ejemplo con BET de 10.00€:**
- Moneda Oro x25 en bonus = 250.00€
- GRAND Jackpot x1000 = 10,000.00€

## 🛠️ Stack Tecnológico

- **Frontend**: Vue.js 3 + TypeScript
- **Styling**: Tailwind CSS
- **Animaciones**: CSS Animations + GSAP/Anime.js
- **Estado**: Pinia
- **Hosting**: Firebase Hosting
- **CI/CD**: GitHub Actions
- **Control de versiones**: Git + GitHub

## 📂 Estructura del Proyecto
<img width="498" height="318" alt="image" src="https://github.com/user-attachments/assets/6f0790d6-f341-4cc0-a8b8-1af8ed7b39a9" />

## 🗓️ Roadmap de Desarrollo

### Fase 1: MVP - Juego Base ✅ (Planeado)
- [ ] Setup del proyecto (Vue 3 + Tailwind)
- [ ] Diseño de la UI básica
- [ ] Sistema de rodillos (spin básico)
- [ ] Símbolos y líneas de pago
- [ ] Sistema de apuestas y balance
- [ ] Detección de combinaciones ganadoras

### Fase 2: Sistema de Hucha 🔄
- [ ] Implementar hucha visual
- [ ] Sistema de puntos oculto (0-100%)
- [ ] Animación de monedas volando a la hucha
- [ ] Efectos visuales (vibración, brillo)
- [ ] Animación de explosión

### Fase 3: Bonus Hold & Win 🎁
- [ ] Transición a modo bonus
- [ ] Sistema de respins
- [ ] Monedas con valores fijos
- [ ] Reset de respins al caer moneda
- [ ] Suma final de premios
- [ ] Jackpots especiales

### Fase 4: Polish & UX ✨
- [ ] Sonidos y música
- [ ] Animaciones mejoradas
- [ ] Efectos de partículas
- [ ] Feedback visual completo
- [ ] Modo responsive (móvil)
- [ ] Tutorial/ayuda integrada

### Fase 5: Optimización & Deploy 🚀
- [ ] Optimización de rendimiento
- [ ] Testing completo
- [ ] Deploy a Firebase Hosting
- [ ] Configurar dominio personalizado
- [ ] Analytics (opcional)

## 🎯 Objetivos del Proyecto

Este proyecto tiene como finalidad:
- ✅ Practicar Vue.js 3 y TypeScript
- ✅ Implementar animaciones complejas
- ✅ Gestión de estado con Pinia
- ✅ Arquitectura escalable de componentes
- ✅ Deploy y CI/CD con GitHub Actions
- ✅ Crear un proyecto destacado para portfolio

## 📝 Documentación Adicional

- [Game Design Document](./docs/GAME_DESIGN.md) - Diseño detallado del juego
- [Technical Specs](./docs/TECHNICAL_SPECS.md) - Arquitectura y especificaciones técnicas
- [Roadmap](./docs/ROADMAP.md) - Plan de desarrollo detallado

## 🤝 Contribuciones

Este es un proyecto personal de aprendizaje. Si tienes sugerencias o mejoras, siéntete libre de abrir un issue.

## 📄 Licencia

MIT License - Este proyecto es de código abierto y puede ser usado como referencia educativa.

## 👤 Autor

**Tu Nombre**
- GitHub: [@AlvaroS19](https://github.com/AlvaroS19)
- LinkedIn: [Alvaro Delgado](https://www.linkedin.com/in/alvarodelgado-dev/)

---
