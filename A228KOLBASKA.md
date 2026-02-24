### ⚔️ `Battles` (Сражения)
| Поле | Тип | Описание |
|------|-----|----------|
| `id` | `INTEGER` 🏷️ | **PRIMARY KEY** |
| `winner_id` | `INTEGER` 🥇 | **FOREIGN KEY** → `Players.id` |
| `loser_id` | `INTEGER` 😢 | **FOREIGN KEY** → `Players.id` |
| `battle_date` | `DATETIME` 📅 | **DEFAULT CURRENT_TIMESTAMP** |
| `duration_seconds` | `INTEGER` ⏱️ | Длительность боя |
