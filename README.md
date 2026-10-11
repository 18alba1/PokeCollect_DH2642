# PokeCollect

**PokeCollect** is a Pokémon collection web app that combines a searchable Pokédex with a virtual pack-opening experience. Users can explore Pokémon, purchase virtual packs with in-app currency, open packs, and build a personal collection that persists between sessions.

**Live demo:** [Try PokeCollect](https://pokecollect-pied.vercel.app/)

**Video demo:**

https://github.com/user-attachments/assets/cfcd44b8-b69c-4cc3-9946-35b8e97c1492



## Overview

The project brings together data from the [PokéAPI](https://pokeapi.co/) and user-specific data stored with Firebase. It was built collaboratively, with a focus on interactive UI, client-side state management, authentication, persistent user data, and responsive design.

## Features

- **Pokédex search:** Search for Pokémon and view detailed information.
- **Filtering:** Browse Pokémon by type and generation.
- **Virtual store:** Browse packs, review pack details, and manage a shopping cart with adjustable quantities.
- **In-app currency:** Purchase packs using virtual currency, with a timed balance replenishment system.
- **Interactive pack opening:** Open purchased packs and reveal Pokémon with a card-flip animation.
- **Personal collection:** Save collected Pokémon, revisit them later, and track collection progress by generation.
- **Authentication and persistence:** Sign in with Google and save user-specific collection and application data.
- **Protected routes:** Restrict authenticated features and redirect users appropriately when they sign out.
- **Responsive interface:** Adapt the experience for desktop and mobile screens.

## Screenshots

_Add screenshots or a short GIF here to show the Pokédex, store, pack-opening animation, and personal collection._

For example, place images in a `screenshots/` directory and embed them like this:

```markdown
![Pokédex view](screenshots/pokedex.png)
```

## Technical Highlights

- Integrated an external REST API to retrieve Pokémon data.
- Connected Google sign-in and Firebase-backed persistence for user-specific data.
- Built interactive React components for search, filtering, cart management, and pack opening.
- Managed application state and reactive UI updates with MobX.
- Implemented route navigation and protected views with React Router.
- Improved usability through responsive CSS, clear cart feedback, collection-progress indicators, and fixes informed by user evaluations.

## Technology Stack

| Area | Technologies |
|---|---|
| Frontend | React, JavaScript, CSS |
| Build tooling | Vite, npm |
| State management | MobX, mobx-react-lite |
| Routing | React Router |
| Authentication and persistence | Firebase |
| External data | PokéAPI |
| UI components | React Card Flip, ReactJS Popup, React Rating, Font Awesome |
| Deployment | Vercel |

## Run Locally

### Prerequisites

- Node.js and npm
- Access to the Firebase project configuration required by the application

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/18alba1/PokeCollect_DH2642.git
   cd PokeCollect_DH2642
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure Firebase using the project's expected configuration in `src/firebaseConfig.js`. Do not commit private credentials or secrets.

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed by Vite in your terminal (typically `http://localhost:5173`).

To create a production build:

```bash
npm run build
```

## Team

Built collaboratively by:

- [Alexander Barhado](https://github.com/18alba1)
- [Elias Amani](https://github.com/Eliasamani)
- [Razan Yakoub](https://github.com/RazanYakoub01)
- [Seema Bashir](https://github.com/Seemamian)
