# 🎵 **User Interfaces Project**

## 🌟 Project Title: **EURODLE**

**Team: Grupo P**

### 👥 **Team Members & Roles**

| 🏆 **Name**                                                                                                              | 🔍 **Role** |
| ------------------------------------------------------------------------------------------------------------------------ | ----------- |
| [Eduardo García Rivas](https://www.linkedin.com/in/eduardo-garcia-rivas-ab147b289/)                                      | CTO         |
| [Eloy González Castillo](https://www.linkedin.com/in/eloy-gonz%C3%A1lez-castillo/)                                       | CEO         |
| [Francisco Javier Jordá Garay](https://www.linkedin.com/in/fjjordagaray/)                                                | CIO         |
| [María Paulina Ordóñez Walkowiak](https://www.linkedin.com/in/mar%C3%ADa-paulina-ord%C3%B3%C3%B1ez-walkowiak-ab575232a/) | COO         |
| [Javier Toledo Delgado](https://www.linkedin.com/in/javier-toledo-delgado-85b75032a/)                                    | CXO         |

---

## 📖 **Descripción del proyecto (Español)**

Nuestro juego se inspira en minijuegos derivados de Wordle, como [Gamedle](https://www.gamedle.wtf/) o [Pokédle](https://pokedle.net/). Aprovechando la proximidad de la próxima edición de Eurovisión, hemos decidido basar el juego en este evento.

El objetivo es adivinar una canción de Eurovisión con la ayuda de pistas, que se van volviendo progresivamente más claras a medida que el jugador falla. Si al final de las pistas el jugador no adivina, pierde la partida.

Las canciones provienen de las siguientes bases de datos (filtradas para incluir solo finalistas y datos hasta 2025):

* [Eurovision Song Contest Data from Kaggle](https://www.kaggle.com/datasets/diamondsnake/eurovision-song-contest-data)
* [Spijkervet/eurovision-dataset](https://github.com/Spijkervet/eurovision-dataset?tab=readme-ov-file)

**Tecnologías utilizadas:** React (frontend puro), CSS + Bootstrap para los estilos, y R para procesamiento de datos.

---

## 📖 **Project Description (English)**

Our game is inspired by Wordle spin-offs like [Gamedle](https://www.gamedle.wtf/) or [Pokédle](https://pokedle.net/). Taking advantage of the upcoming Eurovision Song Contest, we decided to base the game on this event.

The goal is to guess a Eurovision song with the help of clues, which become progressively clearer as the player makes mistakes. If the player fails to guess after all the clues are revealed, they lose the game.

Songs are sourced from the following databases (filtered to include only finalists and data up to 2025):

* [Eurovision Song Contest Data from Kaggle](https://www.kaggle.com/datasets/diamondsnake/eurovision-song-contest-data)
* [Spijkervet/eurovision-dataset](https://github.com/Spijkervet/eurovision-dataset?tab=readme-ov-file)

**Technologies used:** React (frontend only), CSS + Bootstrap for styling, and R for data processing.

---

## 🌐 **Demo**

We deployed a live demo on Netlify.
👉 [Try EURODLE here](https://endearing-stroopwafel-7c8d92.netlify.app)

---

## 🚀 **Guía de instalación y uso (Español)**

### **Prerrequisitos**

* Tener instalado [Docker Desktop](https://www.docker.com/products/docker-desktop/).

---

### 🧩 **Paso 1:** Clonar el repositorio

```bash
git clone <URL-del-repositorio>
```

---

### 🐳 **Paso 2:** Construir y arrancar el contenedor

Desde la carpeta raíz del proyecto:

```bash
docker compose up --build
```

---

### 🌐 **Paso 3:** Probar en el navegador

Abrir:

```
http://localhost:3000/
```

---

Para detener el contenedor:

```bash
docker compose down
```

---

## 🚀 **Installation & Usage Guide (English)**

### **Prerequisites**

* Install [Docker Desktop](https://www.docker.com/products/docker-desktop/).

---

### 🧩 **Step 1:** Clone the repository

```bash
git clone <repository-URL>
```

---

### 🐳 **Step 2:** Build and start the container

From the project root folder:

```bash
docker compose up --build
```

---

### 🌐 **Step 3:** Open in your browser

Go to:

```
http://localhost:3000/
```

---

To stop the container:

```bash
docker compose down
```
