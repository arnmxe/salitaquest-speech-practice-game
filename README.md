# SalitaQuest – Speech Practice Adventure

**Say it. Play it. Grow with Kiko!**

SalitaQuest is an interactive speech practice game designed to make Filipino speech exercises more engaging and enjoyable for children ages 4–8. Through themed worlds, word pronunciation activities, encouraging feedback, and collectible rewards, children can practice speaking while exploring the game with their companion, Kiko.

## Features

- **Bilingual Interface** – Switch between English and Filipino.
- **Explorer Profiles** – Create a player profile using a nickname and avatar.
- **Interactive Worlds** – Explore five themed worlds: Jungle, Beach, Farm, Space, and Market.
- **Speech Practice** – Listen to word pronunciations and practice saying them aloud.
- **Audio Support** – Uses browser speech synthesis to pronounce words.
- **Microphone Permission** – Requests microphone access before starting a practice attempt.
- **Encouraging Feedback** – Choose how well the word was pronounced and receive positive feedback.
- **Rewards System** – Earn stars and collectible stickers after completing levels.
- **Growing Companion** – Unlock new appearances and accessories for Kiko as levels are completed.
- **Daily Practice Goal** – Encourages five minutes of daily practice.
- **Parent Area** – Provides access to practice summaries, settings, and progress reset.
- **Child-Friendly Design** – Features colorful illustrations, simple navigation, and positive reinforcement.

## Game Worlds

| World | Filipino Name | Target Sound |
|---|---|---|
| Jungle | Gubat | /l/ |
| Beach | Tabing-Dagat | /r/ |
| Farm | Bukid | /k/ |
| Space | Kalawakan | /s/ |
| Market | Palengke | /m/ |

Each world contains selected Filipino words that children can practice.

## Technologies Used

- **React 19** – User interface development
- **TypeScript** – Application logic and type safety
- **Vite** – Development server and build tool
- **Tailwind CSS 4** – Styling and responsive interface
- **Web Speech API** – Text-to-speech pronunciation
- **Web Audio API** – Sound effects

## Getting Started

Follow these instructions to run the project locally.

### Prerequisites

Make sure you have installed:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- A modern web browser

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/salitaquest-speech-practice-game.git
   ```

2. Navigate to the project folder:

   ```bash
   cd salitaquest-speech-practice-game
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL displayed in your terminal, usually:

   ```text
   http://localhost:5173
   ```

## Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Starts the local development server |
| `npm run build` | Builds the application for production |
| `npm run preview` | Previews the production build locally |

## Project Structure

```text
salitaquest-speech-practice-game/
│
├── public/
│
├── src/
│   ├── components/
│   │   └── Art.tsx
│   │
│   ├── utils/
│   │   └── cn.ts
│   │
│   ├── App.tsx
│   ├── audio.ts
│   ├── data.ts
│   ├── index.css
│   └── main.tsx
│
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
└── vite.config.ts
```

**Note:** The `public/` folder shown above is a conventional project directory and may be added if needed. It is not included in the current project files.

### Editable Game Data

The `src/data.ts` file contains the main game content, including:

- Word lists and syllable breakdowns
- Target speech sounds
- Game worlds and themes
- Assigned practice words
- Collectible stickers
- Kiko's companion stages
- English and Filipino interface text

Developers can modify the game content in this file when adding or updating words and worlds.

## Privacy and Safety

SalitaQuest is designed with a child-friendly experience in mind.

- Audio is not uploaded or saved.
- Microphone access is requested through the browser.
- The current implementation checks microphone permission but does not record or analyze the child's speech.
- Pronunciation feedback is based on the player's selected rating.
- Player progress is currently maintained in application memory and is not permanently stored.

**Important:** The current project is a prototype. The "Send to Therapist" feature displays a confirmation within the application but does not actually transmit a report to a therapist.

## Project Status

**Development Stage:** Prototype

SalitaQuest currently demonstrates the main gameplay experience, bilingual interface, themed practice worlds, rewards, and parent-facing screens. Persistent progress storage, automated speech assessment, and actual therapist reporting are not yet implemented.

## License

No license has been specified for this project yet.

---

**SalitaQuest**  
*Say it. Play it. Grow with Kiko!*
