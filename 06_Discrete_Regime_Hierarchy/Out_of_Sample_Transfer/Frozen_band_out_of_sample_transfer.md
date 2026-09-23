# Frozen-band out-of-sample transfer

**Canvas source:** `step5-hierarchy-inventory.canvas.tsx` · **Rows:** 12

| Duration | Train→test | AI test NMI | LE test NMI | AI / LE hold |
| --- | --- | --- | --- | --- |
| 30 | 2022–23→2024–25 | 0.0844 | 0.0767 | Yes / Yes |
| 30 | 2022–24→2025 | 0.0409 | 0.0662 | Yes / Yes |
| 30 | 2022→2023 | 0.0055 | 0.0144 | No / No |
| 30 | 2022–23→2024 | 0.0528 | 0.0381 | Yes / Yes |
| 45 | 2022–23→2024–25 | 0.1144 | 0.1072 | Yes / Yes |
| 45 | 2022–24→2025 | 0.0618 | 0.0734 | Yes / Yes |
| 45 | 2022→2023 | 0.0147 | 0.0231 | No / No |
| 45 | 2022–23→2024 | 0.0747 | 0.0666 | Yes / Yes |
| 60 | 2022–23→2024–25 | 0.1340 | 0.1144 | Yes / Yes |
| 60 | 2022–24→2025 | 0.0717 | 0.0759 | Yes / Yes |
| 60 | 2022→2023 | 0.0238 | 0.0297 | No / No |
| 60 | 2022–23→2024 | 0.0899 | 0.0765 | Yes / Yes |

> **Note.** Hold requires test/train NMI ≥ 0.60.
