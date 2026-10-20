# Thomas BARASCUD
**Développeur Informatique Graphique & Moteur 3D | Master IMAGINE**

Profil spécialisé dans la programmation bas niveau, l'architecture logicielle et le rendu temps réel. Un intérêt fort est porté à la compréhension interne des systèmes, que ce soit par l'écriture de moteurs 3D en C++ ou par la fabrication artisanale d'instruments de musique (lutherie). 

Tous les projets présentés ci-dessous sont le fruit d'un travail collaboratif et de co-développement en équipe.

---

### 🛠️ Stack Technique & Compétences
* **Langages :** C++, Python, Java, GLSL
* **Graphisme & GPU :** OpenGL, Compute Shaders, Pipeline PBR
* **Architecture :** Entity Component System (ECS), Graphe de scène
* **Domaines :** Moteurs physiques (CCD), Génération Procédurale (PCG), Intelligence Artificielle

---

### 🚀 Projets Collaboratifs & Contributions

#### 🧊 Voxel Game Engine (C++ / OpenGL)
*Co-développement d'un moteur de jeu optimisé de type Minecraft.*
* Conception d'une architecture ECS par Sparse Sets pour maximiser la localité en cache.
* Réduction drastique de la charge polygonale via l'algorithme de **Greedy Meshing**.
* Implémentation d'un pipeline de rendu Physically Based Rendering (PBR) avec ombrage de Cook-Torrance, occlusion ambiante (Vertex AO) et Normal Mapping.

#### 🌊 Simulation d'Érosion Fluide (C++ / OpenGL)
*Réalisation en équipe d'une simulation hydraulique et thermique.*
* Implémentation des *Shallow Water Equations* pour simuler l'écoulement des fluides et l'érosion des terrains.
* Parallélisation massive des calculs sur GPU via **Compute Shaders**, permettant d'atteindre un rendu temps réel à plus de 960 FPS.

#### 🌀 Moteur Portal & Solveur Physique (C++ / OpenGL)
*Création en binôme d'un moteur 3D intégrant une mécanique spatiale non euclidienne.*
* Développement d'un moteur physique "from scratch" avec détection continue des collisions (CCD) pour éviter le *tunneling*.
* Gestion de l'espace continu (Stencil Buffer, clonage visuel) et illumination globale mise en cache par Sondes Harmoniques (SH Probes).

#### 🍳 OvercookMini & IA Multi-Agents (Python)
*Développement en équipe d'un environnement de simulation coopératif.*
* Programmation d'un moteur 2D asynchrone et d'un algorithme de génération procédurale de cartes topologiques validées.
* Modélisation d'intelligences artificielles autonomes avec pathfinding dynamique, évitement d'obstacles en temps réel et résolution algorithmique des conflits de répartition des tâches.

#### 🌍 Application Mobile : Réseau Social & Générateur d'Itinéraires (Java)
*Co-création d'une plateforme mobile combinant réseau social photographique et planification de voyage.*
* Développement d'un algorithme de recommandation et de génération de parcours touristiques sur mesure.
* Filtrage dynamique des itinéraires croisant de multiples variables : budget, durée du séjour, sensibilités météorologiques et affinités personnelles (restaurants, sites culturels, bars, parcs, musées).

---

### 🔗 Liens & Contact
* **Portfolio & Analyses Techniques :** https://thomasbrcd.github.io
* **LinkedIn :** https://www.linkedin.com/in/thomas-barascud-7b33b3419
