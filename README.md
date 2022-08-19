# Tic-Tac-Toe Tutorial Follow Up

The offical React website provides a **learning by doing** tutorial on how to build an interactive tic-tac-toe game with React ([https://reactjs.org/tutorial/tutorial.html](https://reactjs.org/tutorial/tutorial.html)). The example provided in the tutorial uses React class components for state management. At the end of the tutorial, 6 follow-up tasks are suggested for readers to practice and develop their React skills.

This React App provides an example on how to use React function components to develop the tic-tac-toe game and use the `useState` and `useRef` hooks for state management. This example also shows how to fulfil the 6 follow-up tasks similar to the ones suggested in the React tutorial:

1. Display the location (using the square number) for each move in the move history.
2. Highlight the current selected item in the move list.
3. Use loops to make the squares instead of hardcoding them.
4. The move list is implemented for users to inspect and replay their completed games, by going to any numbered step, or by pressing Forward or Backward buttons. This provides a standard game replay, which differs from the [implementation provided in the React tutorial](https://codepen.io/gaearon/pen/gWWZgR?editors=0010), where users can go back to a previous step, and then to continue playing as a new game from that step.
5. When someone wins, the three squares that caused the win are highlighted using color.
6. When no one wins, a **Draw** message is provided.

In addition, the position of the last step during the game is highlighted; and a warning message is provided in case a move is atempted on an occupied position. Replay is only presented and enabled aften a game is completed. A _New Game_ button is provided for readers to play the game again. You are welcome to try [the improved game](https://wadehonda.github.io/tictactoe).
