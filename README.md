# LEGO SPIKE FLL Common Blocks Library

Welcome to the **LEGO SPIKE™ Common Blocks Library** for **FIRST® LEGO League (FLL)** teams!

This project provides a curated set of reusable **My Blocks** and example programs designed to accelerate robot programming and ensure consistency across missions. Each block is named and numbered for easy reference and use.

---

## 🚀 How to Use This Library

1. **Download the `.ll3` file** from the [Releases](./releases) or this repository.
2. **Open the LEGO SPIKE app** (version 3.x or later).
3. **Import the `.ll3` project** into the SPIKE app.
4. Use or copy the blocks into your own FLL mission projects.

---

## 📦 Block Naming Convention

Each block is named with a two-digit prefix for easy sorting and reference.  
**Format:** `##.BlockName`  
Example: `01.Turn`

- `01–09`: Basic movement
- `10–19`: Sensor-based logic
- `20–29`: Advanced maneuvers or helper functions
- `30–99`: Custom team strategies, mission-specific routines

---

## 📚 Block List

| Block Name     | Description |
|----------------|-------------|
| `01.Turn`      | Turns the robot by a specific number of degrees using a gyro sensor. |
| `02.Forward`   | Drives forward for a given distance or time, with speed control. |
| `03.Stop`      | Stops all motors immediately. |
| `10.WaitForLine` | Waits until the color sensor detects a black line. |
| `11.AlignToLine` | Aligns the robot squarely to a line using two color sensors. |
| `20.NavigateToZone` | Drives to a predefined zone using sensor feedback and PID-style control. |
| `21.PushMissionModel` | Executes a push routine to interact with a mission model. |
| `30.Strategy_Run1` | Combines blocks to perform a full Run 1 sequence. |
| `31.Strategy_ScoreComboA` | Optimized combo for multiple mission scoring in one run. |

> More blocks coming soon! Contributions welcome.

---

## 🧩 Compatibility

- ✅ LEGO SPIKE App v3.x or newer
- ❌ Not compatible with `.llsp` files (SPIKE Legacy apps)

---

## 🙌 Contributions

FLL teams are encouraged to:
- Add their own blocks
- Submit pull requests with improvements
- Follow the naming conventions to keep the library clean

---

## 📄 License

This project is open-source under the [MIT License](./LICENSE).

---

## 💬 Feedback & Support

If you find bugs or want to suggest improvements, open an [Issue](./issues) or reach out via GitHub Discussions.

Happy building and good luck in your FLL season! 🤖🏆
