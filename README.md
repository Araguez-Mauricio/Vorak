# Vorax

Shooter de zombis en primera persona que corre en el navegador (Three.js r128), todo en un solo archivo: `index.html`.

## Cómo jugar

Abre `index.html` en un navegador moderno (Chrome, Edge o Firefox). Necesita conexión a internet la primera vez para cargar Three.js y las fuentes.

## Modos

- **Supervivencia:** rondas cada vez más difíciles, con desafíos y un descanso entre rondas.
- **Misión: Extracción:** junta combustible, enciende el generador, resiste y escapa en helicóptero.

## Controles

| Tecla | Acción |
|---|---|
| W A S D | Moverse |
| Shift | Correr (baja el arma) |
| Clic | Disparar / golpear |
| Clic derecho / V | Golpe rápido |
| R | Recargar |
| E | Usar / recoger |
| 1–6 / rueda | Cambiar de arma |
| F | Linterna |
| B / Enter | Armería / empezar ronda (entre rondas) |
| P | Pausa |

## Sistemas

- Armería con monedas: armas de fuego, armas cuerpo a cuerpo, 5 mejoras por arma y mejoras del personaje.
- Munición por cargadores: al recargar se pierden las balas que quedaban en el cargador. La escopeta carga cartucho por cartucho.
- Zombis con vida por zona: crítico a la cabeza, cojean con una pierna rota y se arrastran sin piernas.
- Armas generadas por código con materiales PBR, manos articuladas y animaciones de recarga, bombeo y cerrojo.
- El progreso se guarda en el navegador (localStorage).
