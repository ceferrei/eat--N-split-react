# Eat-'N-Split

A simple and interactive React application designed to help you easily split bills with friends and keep track of who owes whom.

## Demo

<div align="center">
  <video src="https://github.com/user-attachments/assets/bf7aa0de-59f7-4419-91ae-d527136d3a4e" controls width="600">
    Seu navegador não suporta o elemento de vídeo.
  </video>
</div>

## Features

- **Manage Friends:** Add new friends to your list with their name and an optional image URL.
- **Track Balances:** Clearly see who owes money or who is owed money within the friend group.
- **Select & Split:** Choose a friend from the list to split a bill with.
- **Easy Bill Splitting:**
  - Enter the total bill amount.
  - Specify your portion of the expense.
  - The friend's expense is automatically calculated.
  - Select who paid the bill (you or the friend).
- **Automatic Balance Updates:** Balances are automatically recalculated and updated after each bill split.
- **Interactive UI:** Clean user interface built with React components and state management (`useState`).
- **Persistent State (Conceptual):** Uses React state to manage data during the session (Note: data resets on page refresh in this version).

## Installation

1.  Clone the repository (replace the URL with your actual repository link):
    ```bash
    git clone https://github.com/ceferrei/eat--N-split-react.git
    cd eat--N-split-react
    ```
2.  Install dependencies:
    ```bash
    npm install
    ```

## Running the Application

1.  Start the development server:
    ```bash
    npm start
    ```
2.  Open your browser and navigate to: `http://localhost:3000` (or the port specified in your console if 3000 is busy).

## How It Works

The application uses React functional components and the `useState` hook to manage the list of friends, the currently selected friend, and the visibility of the 'Add Friend' form. When a bill is split, the relevant state is updated, causing the UI to re-render with the new balances.
