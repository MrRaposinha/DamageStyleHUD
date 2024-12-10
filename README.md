### **DamageStyleHUD - Track Your Total Damage in Real-Time**

**DamageStyleHUD** is a mod for ULTRAKILL that enhances the StyleHUD by adding a real-time damage counter. Keep track of your total damage directly on the style bar, making it easier than ever to measure your performance during intense combat.

---

## 🌟 Features

- **Real-Time Damage Counter**:
  - Displays the total damage dealt in real-time on the first line of the StyleHUD.
  - Updates dynamically as you deal damage to enemies.

- **Clear and Permanent Formatting**:
  - The damage text is prominently formatted in orange and displayed consistently above existing style metrics.

---

## 🎮 Why Use This Mod?

- **Measure Efficiency**:
  - Easily gauge the effectiveness of different weapons and strategies.

- **Improve Gameplay**:
  - Fine-tune your combat techniques by monitoring damage output.

- **Track Performance**:
  - Satisfyingly watch your damage numbers climb during intense battles.

---

## 🚀 How It Works

- **Harmony Integration**:
  - The mod patches key methods in the StyleHUD class:
    - **AddPoints**: Captures the style points (equivalent to damage) and adds them to a running total.
    - **UpdateItems**: Ensures the damage counter always appears as the first line on the StyleHUD.

- **Dynamic Updates**:
  - The damage counter updates seamlessly alongside existing style metrics for a fluid and immersive experience.

---

## 📥 Installation

### Requirements
- **BepInEx**: Ensure BepInEx is installed in your ULTRAKILL directory.

### Steps to Install
1. Download the latest release of **DamageStyleHUD** from the [Releases](https://github.com/MrRaposinha/DamageStyleHUD/releases) page.
2. Place the `DamageStyleHUD.dll` file in your `BepInEx/plugins` folder.
   - If the `plugins` folder doesn’t exist, create it manually.
3. Launch ULTRAKILL and enjoy tracking your damage in real-time!

---

## 🔧 Technical Details

- **Text Format**:
  - The damage counter appears as `+ <color=orange>DAMAGE: [value]</color>`, where `[value]` is the total damage dealt.

- **Lightweight Design**:
  - Optimized for minimal performance impact, ensuring smooth gameplay.

---

## 📜 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

Thank you for trying **DamageStyleHUD**! Take control of your combat stats and make every hit count. 🎮🔥
