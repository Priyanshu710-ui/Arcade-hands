# 🕹️ Arcade Hands

> A browser-based interactive arcade experience built around hand-driven interaction.

![Web](https://img.shields.io/badge/Web-Interactive-2563eb?style=for-the-badge)
![Vision](https://img.shields.io/badge/Hand-Driven-8b5cf6?style=for-the-badge)

## ✋ Interaction Pipeline
```mermaid
flowchart LR
    A[📷 Camera / Input] --> B[✋ Hand Detection]
    B --> C[🧠 Gesture Interpretation]
    C --> D[🕹️ Game Controls]
    D --> E[🎮 Arcade Experience]
```

## 🔄 Gameplay Loop
```mermaid
sequenceDiagram
    participant U as Player
    participant C as Camera/Input
    participant G as Game
    U->>C: Perform gesture
    C->>G: Send interpreted action
    G->>G: Update game state
    G-->>U: Render next frame
```

## 🗺️ Game Map
```mermaid
mindmap
  root((Arcade Hands))
    Hand Input
    Gesture Logic
    Controls
    Game State
    Visual Feedback
```

## 📂 Structure
```text
├── index.html
└── README.md
```

---

### 👨‍💻 Created by **Priyanshu**
