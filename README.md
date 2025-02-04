

---

# Connect Four – KI mit Minimax & Alpha-Beta-Pruning

Dieses Repository enthält eine **künstliche Intelligenz (KI)** für das Spiel **Connect Four**, die den **Minimax-Algorithmus mit Alpha-Beta-Pruning** verwendet, um optimale Spielzüge zu berechnen.

---

## Projektstruktur

```
├── ex4.ipynb        # Jupyter Notebook mit der Minimax-Implementierung für Connect Four
├── README.md        # Projektdokumentation
```

---

## Beschreibung

Das Notebook **ex4.ipynb** implementiert **Connect Four** mit einer intelligenten Spielstrategie.

### Funktionen:
- **Spielmechanik**: 6x7 Spielbrett mit zwei Spielern (`1` und `-1`).
- **Minimax-Algorithmus**: Berechnet optimale Spielzüge für die KI.
- **Alpha-Beta-Pruning**: Verbessert die Effizienz des Minimax-Algorithmus, indem unnötige Berechnungen vermieden werden.
- **Bewertungsfunktion**: Schätzt die Stärke eines Spielzugs basierend auf Gewinnmöglichkeiten.

---

## Installation & Nutzung

1. Notwendige Bibliotheken installieren:
   ```sh
   pip install numpy notebook
   ```

2. Jupyter Notebook starten:
   ```sh
   jupyter notebook
   ```

3. Das Notebook `ex4.ipynb` öffnen und ausführen.

---

## Lizenz

Dieses Projekt ist lizenzfrei
