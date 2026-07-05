\# Ludo Game — with AI Opponents 🎲



A complete browser-based Ludo game built with pure HTML, CSS, and JavaScript. Play against 3 AI opponents or with up to 4 friends on one device (AI course project).



\## Game Modes

\- \*\*🤖 Play vs AI\*\* — you (red) against 3 computer players

\- \*\*👥 Play with Friends\*\* — 2, 3, or 4 players, pass-and-play



\## Full Ludo Rules Implemented

\- Roll 6 to release a token from base (+ extra turn on every 6)

\- Capture opponent tokens by landing on them — captured tokens return to base

\- Safe star cells where tokens cannot be captured

\- Colored home columns requiring exact rolls to finish

\- First player to bring all 4 tokens home wins



\## AI Design (Heuristic Scoring)

Each AI evaluates all possible moves and picks the highest-scoring one:

\- Capture an opponent: +100

\- Finish a token: +80

\- Escape base on a 6: +50

\- Enter home column: +30

\- Land on a safe cell: +20

\- Small preference for advancing the lead token, plus slight randomness



\## Tech Stack

\- HTML, CSS (Grid layout), JavaScript — no frameworks, no server needed



\## How to Run

Just open `index.html` in any browser!



\## Author

Naymur Rahman — CSE, Notre Dame University Bangladesh

