# Patrones de diseño · Pet Survivors

Presentación web sobre **Factory**, **Observer** y **Command**, y sus patrones
afines, aplicados al proyecto final Pet Survivors del curso Tecnología de
Objetos (UNSA, 1703240).

**En vivo:** https://pet-survivors-patrones.vercel.app

**Presentación general:** https://pet-survivors-presentacion.vercel.app

**Código del juego:** https://github.com/sandra-aliaga/veterinaria-apocaliptica-to

## Contenido

| Bloque | Temas |
|---|---|
| Factory | Problema, UML, `FabricaMascotasBase`, `FabricaEnemigosBase` con Strategy y la familia creacional (Simple Factory, Factory Method, Abstract Factory, Builder, Prototype, Singleton) |
| Observer | `MisionBase` y `ReceptorEventosMision`, secuencia de notificación, push contra pull, Publish/Subscribe, MVC y Mediator |
| Command | `Comando` y `AccionesControlador`, roles del patrón, flujo de entrada y comparación con Strategy, Memento, Chain of Responsibility y Template Method |
| Integración | Los patrones en un mismo cuadro de juego y los principios SOLID que aportan |

El código que se muestra viene del repositorio del juego. Cuando algo aún no
está integrado (los comandos concretos y la suscripción de la vista), la
presentación lo indica.

## Uso

- Flechas, espacio o Re Pág / Av Pág para cambiar de diapositiva.
- Clic en un diagrama para ampliarlo; Esc para cerrarlo.
- `patrones_pet_survivors.html` es la versión de un solo archivo para usar sin
  conexión. Los diagramas UML se dibujan con [Mermaid](https://mermaid.js.org/)
  y necesitan internet.

## Desarrollo

Sitio estático sin compilación:

```bash
python -m http.server 4174
```

## Créditos

- Equipo: Dai, Mariana Yucra, Edson Subia y Sandra Aliaga.
- Arte pixel: Camila Alarico y Sandra Aliaga.
- Fuentes Pixelify Sans y Handjet bajo licencia SIL Open Font License.
