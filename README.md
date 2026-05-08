# Tic Tac Toe Game

A classic Tic Tac Toe game implemented as a web application using **ReactJS** for the UI and **Redux** for state management. This project demonstrates fundamental front-end development concepts, including component-based architecture, state management, and basic AI logic.

## Features

-   **Single Player Mode:** Play against an AI with adjustable difficulty levels:
    -   **Easy:** The AI makes random moves.
    -   **Medium:** The AI attempts to block your winning moves and win itself, but can be outsmarted.
    -   **Impossible:** The AI plays optimally and is unbeatable.
-   **Two Player Mode:** Challenge a friend on the same device.
-   **Score Tracking:** Keeps track of wins for both players.
-   **Dynamic Animations:** Smooth transitions and visual feedback powered by Anime.js.
-   **Responsive Design:** Playable on various screen sizes.

## Technologies Used

-   **Frontend:**
    -   [ReactJS](https://reactjs.org/)
    -   [Redux](https://redux.js.org/)
    -   [React Router DOM](https://reactrouter.com/web/guides/quick-start) (for potential future routing, though not heavily used in a single-page game)
-   **Build Tool:**
    -   [Webpack](https://webpack.js.org/)
-   **Animations:**
    -   [Anime.js](https://animejs.com/)
-   **Utilities:**
    -   [Classnames](https://github.com/JedWatson/classnames)
    -   [Prop-types](https://www.npmjs.com/package/prop-types)
    -   [Lodash](https://lodash.com/)

## Building and Running Locally

To set up and run the project on your local machine, follow these steps:

**Prerequisites:**
-   Node.js
-   npm (Node Package Manager)

```bash
$ git clone https://github.com/imsacid/tictactoe.git
$ cd tictactoe
$ npm install
$ npm run dev
```

This will start the development server, and you can access the game in your browser, usually at `http://localhost:8080`.

## Play Online

You can play the live version of the game here.

---

*This project was originally created by saed and is used here as a portfolio piece.*
