# Pokedex - React Application

A modern, responsive Pokedex application built with React and Vite, powered by the [PokeAPI](https://pokeapi.co/).

## 🚀 Features

- **Pokemon Overview**: Browse a list of Pokemon with their names and images.
- **Detailed View**: View specific details for each Pokemon, including height, weight, and types.
- **Debounced Search**: Efficiently search for Pokemon by name using a custom `useDebounce` hook to optimize API interactions.
- **Client-Side Routing**: Fast and seamless navigation using React Router.
- **Dynamic Data**: Fetches real-time data from the PokeAPI.
- **Pagination**: Navigate through the extensive collection of Pokemon using 'Next' and 'Prev' controls.
- **Responsive Design**: Clean and functional interface (custom CSS).


## 🛠️ Tech Stack

- **Framework**: [React 19](https://react.dev/)
- **Routing**: [React Router](https://reactrouter.com/)
- **Build Tool**: [Vite](https://vitejs.dev/)
- **Data Fetching**: [Axios](https://axios-http.com/)
- **API**: [PokeAPI](https://pokeapi.co/)
- **Styling**: Vanilla CSS

## 📦 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/arjunpjaiswal/pokedex.git
   cd pokedex
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

## 🏗️ Project Structure

- `src/Components`: Re-usable components (`Pokedex`, `PokemonList`, `Pokemon`, `PokemonDetails`, `Search`).
- `src/hooks`: Custom hooks like `useDebounce` for optimized performance.
- `src/routes`: Routing configuration using React Router.
- `src/App.jsx`: Main application container with shared layout.
- `src/main.jsx`: Entry point for React, wrapped in `BrowserRouter`.

---
Built by [Arjun](https://github.com/arjunpjaiswal)
