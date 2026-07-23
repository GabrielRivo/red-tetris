# red-tetris

> Advanced project from 42 School. A full-stack, real-time multiplayer implementation of the classic Tetris game built as a Single Page Application (SPA).

![Status](https://img.shields.io/badge/Status-Completed-success)
&emsp;
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=000)
![Redux Toolkit](https://img.shields.io/badge/Redux_Toolkit-764ABC?logo=redux&logoColor=fff)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=fff)
![Express](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?logo=socketdotio&logoColor=fff)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=fff)

## Introduction

This project consists of an online **multiplayer Tetris web application** adhering to strict functional and technical constraints. Players can create or join lobbies, play in real-time against competitors, and experience classic or custom gameplay mechanics.

The game uses WebSockets for low-latency synchronization between the server and all connected clients, backed by a comprehensive unit and component testing suite to ensure state integrity and UI stability.

<div align="center">
  <img src="https://github.com/user-attachments/assets/f14c496f-aa86-4d9b-8359-ec1142f4d613" alt="Red Tetris Gameplay" width="600">
</div>

## Features

#### Core Features
- **Real-Time Multiplayer:** Instant synchronization of game states across multiple players using WebSockets.
- **Lobby & Room System:** Create, join, and list active game lobbies with live player counts and host management.
- **State & Data Management:** Built with Redux Toolkit for reliable data handling and real-time state synchronization.
- **Enhanced Multiplayer Experience:** Features real-time line penalties sent to opponents, dynamic difficulty scaling, score tracking, and custom pieces.
- **Touch & Keyboard Controls:** Gesture controls for mobile users along with full keyboard bindings for desktop players.
- **Full Unit & Component Test Suite:** Built with **Vitest** and **React Testing Library** achieving high test coverage across components, custom hooks, and Redux slices.

## My work

My main tasks were focused on the frontend architecture, state management, and real-time interaction logic:

- Designed and built responsive UI components using **React** and **Tailwind CSS**.
- Implemented **Redux Toolkit** store and custom socket middleware to centralize data management and state synchronization across the application.
- Wrote extensive unit and integration test suites using **Vitest** and **React Testing Library** to validate UI rendering, user actions, and edge cases.

## Install project

```bash
git clone [https://github.com/GabrielRivo/red-tetris.git](https://github.com/GabrielRivo/red-tetris.git)
cd red-tetris
