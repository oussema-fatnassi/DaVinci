# Da Vinci — Futurama Space Scene · Blender 3D

> **🇫🇷 Français** · [🇬🇧 English below](#-english)

---

## 🇫🇷 Français

### À propos du projet

Projet de modélisation et de rendu 3D réalisé avec **Blender**, inspiré de l'univers de *Futurama*.
L'objectif était de concevoir plusieurs assets 3D de zéro — personnages, véhicules, environnements — puis de les assembler dans une composition spatiale finale cohérente et immersive.

---

### Composition finale

![Composition finale](Renders/FinalComposition.png)

*Bender et Fry flottent dans l'espace autour du vaisseau Planet Express, encerclés d'astéroïdes, d'une planète rose et de galaxies spiralées.*

---

### Composition (draft)

![Composition](Renders/Composition.png)

---

### Assets — Personnages

| Bender | Fry |
|--------|-----|
| ![Bender](Renders/Bender.png) | ![Fry](Renders/Frey.png) |
| Robot iconique de Futurama, modélisé avec matériaux métal et éclairage néon. | Fry en combinaison spatiale orange, avec accessoires et casque détaillés. |

---

### Assets — Véhicule

![Planet Express Ship](Renders/SpaceShip.png)

*Le vaisseau Planet Express — carrosserie turquoise, logo emblématique, propulseur lumineux.*

---

### Assets — Environnement spatial

| Planète | Galaxie | Astéroïdes |
|---------|---------|------------|
| ![Planet](Renders/Planet.png) | ![Galaxy](Renders/Galaxy.png) | ![Asteroids](Renders/Asteroids.png) |
| Surface rocheuse texturée avec maps PBR haute résolution. | Galaxie spirale générée procéduralement avec systèmes de particules. | Champ d'astéroïdes avec displacement maps pour le relief. |

---

### Assets — Armes

| Laser Gun | Laser Saber |
|-----------|-------------|
| ![LaserGun](Renders/LaserGun.png) | ![LaserSaber](Renders/LaserSaber.png) |
| Pistolet laser rétro-futuriste, style cartoon. | Sabre laser rouge avec émission lumineuse et bloom. |

---

### Structure du projet

```
DaVinci/
├── Blender/
│   ├── Asteroid.blend       — Champ d'astéroïdes
│   ├── Composition.blend    — Scène finale assemblée
│   ├── Fry.blend            — Personnage Fry
│   ├── Galaxy.blend         — Galaxie spirale
│   ├── LaserGun.blend       — Pistolet laser
│   ├── Planet.blend         — Planète réaliste
│   ├── SpaceShip.blend      — Vaisseau Planet Express
│   └── bender.blend         — Personnage Bender
├── Renders/                 — Tous les rendus PNG finaux
├── Textures/                — Textures PBR utilisées
└── MoodBoard.pur            — Moodboard du projet
```

---

### Technologies

| Outil | Usage |
|-------|-------|
| **Blender 4.x** | Modélisation, shading, rendu |
| **Cycles** | Moteur de rendu physique |
| **Geometry Nodes** | Génération procédurale (galaxie, astéroïdes) |
| **PBR Textures** | Surfaces réalistes (planète, astéroïdes) |
| **Shader Editor** | Matériaux métal, émission, subsurface |

---

---

## 🇬🇧 English

### About the project

A **Blender** 3D modeling and rendering project, inspired by the *Futurama* universe.
The goal was to design multiple 3D assets from scratch — characters, vehicles, environments — then assemble them into a cohesive, immersive final space composition.

---

### Final Composition

![Final Composition](Renders/FinalComposition.png)

*Bender and Fry float through space around the Planet Express ship, surrounded by asteroids, a pink planet and spiral galaxies in the background.*

---

### Draft Composition

![Composition](Renders/Composition.png)

---

### Assets — Characters

| Bender | Fry |
|--------|-----|
| ![Bender](Renders/Bender.png) | ![Fry](Renders/Frey.png) |
| Futurama's iconic robot, modeled with metallic materials and neon lighting. | Fry in his orange spacesuit, with detailed accessories and helmet. |

---

### Assets — Vehicle

![Planet Express Ship](Renders/SpaceShip.png)

*The Planet Express ship — turquoise hull, iconic logo, glowing thruster.*

---

### Assets — Space Environment

| Planet | Galaxy | Asteroids |
|--------|--------|-----------|
| ![Planet](Renders/Planet.png) | ![Galaxy](Renders/Galaxy.png) | ![Asteroids](Renders/Asteroids.png) |
| Rocky surface textured with high-res PBR maps. | Procedurally generated spiral galaxy using particle systems. | Asteroid field with displacement maps for surface detail. |

---

### Assets — Weapons

| Laser Gun | Laser Saber |
|-----------|-------------|
| ![LaserGun](Renders/LaserGun.png) | ![LaserSaber](Renders/LaserSaber.png) |
| Retro-futuristic cartoon-style ray gun. | Red laser saber with emissive glow and bloom effect. |

---

### Project Structure

```
DaVinci/
├── Blender/
│   ├── Asteroid.blend       — Asteroid field
│   ├── Composition.blend    — Final assembled scene
│   ├── Fry.blend            — Fry character
│   ├── Galaxy.blend         — Spiral galaxy
│   ├── LaserGun.blend       — Laser gun
│   ├── Planet.blend         — Realistic planet
│   ├── SpaceShip.blend      — Planet Express ship
│   └── bender.blend         — Bender character
├── Renders/                 — All final PNG renders
├── Textures/                — PBR textures used
└── MoodBoard.pur            — Project moodboard
```

---

### Tech Stack

| Tool | Usage |
|------|-------|
| **Blender 4.x** | Modeling, shading, rendering |
| **Cycles** | Physical render engine |
| **Geometry Nodes** | Procedural generation (galaxy, asteroids) |
| **PBR Textures** | Realistic surfaces (planet, asteroids) |
| **Shader Editor** | Metal, emission, subsurface materials |

---

*Oussema Fatnassi & Oroitz Lago Ramos — La Plateforme · 2025*
