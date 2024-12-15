# Somini: A Candy Crush-Inspired Match-Three Game

Somini is a fun and engaging match-three puzzle game inspired by Candy Crush. Built with Python, it features a colorful game board, intuitive gameplay, and integration with Google Cloud Storage for saving player progress.

---

## **Features**

### Core Gameplay:
- Match three or more tiles to score points.
- Dynamic game board with randomly generated tiles.
- Simple and addictive mechanics.

### Storage Integration:
- Save and load game progress using Google Cloud Storage.

### Future Additions:
- Power-ups and boosters.
- Monetization through in-app purchases and ads.
- Social features to connect with friends.

---

## **Installation**

### Prerequisites:
- Python 3.8 or higher
- Google Cloud account (if using progress saving)

### Steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd somini
   ```

2. Create a virtual environment:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Set up Google Cloud credentials (optional):
   - Create a service account and download the JSON key file.
   - Set the `GOOGLE_APPLICATION_CREDENTIALS` environment variable:
     ```bash
     export GOOGLE_APPLICATION_CREDENTIALS="path/to/key.json"
     ```

5. Run the game:
   ```bash
   python frontend/main.py
   ```

---

## **Project Structure**
```
├── backend/        # Backend logic
│   ├── game_logic.py  # Core game logic
│   ├── storage.py     # Google Storage integration
├── frontend/       # Frontend UI and game loop
│   ├── main.py        # Game interface
├── tests/          # Unit tests
├── requirements.txt # Python dependencies
└── README.md       # Project documentation
```

---

## **Gameplay Instructions**
1. Launch the game.
2. Swap adjacent tiles to match three or more of the same color.
3. Score points and progress through levels.
4. Save progress (requires Google Cloud setup).

---

## **Dependencies**
- `google-cloud-storage`: For saving/loading progress.
- `pygame`: For the game interface.

Install them with:
```bash
pip install -r requirements.txt
```

---

## **Future Plans**
- Add animations for tile matching.
- Implement power-ups like bombs and extra moves.
- Create a scoring system and leaderboards.
- Monetize with in-app purchases and ads.

---

## **Contributing**
Contributions are welcome! Fork the repository, make your changes, and submit a pull request.

---

## **License**
This project is licensed under the MIT License.
