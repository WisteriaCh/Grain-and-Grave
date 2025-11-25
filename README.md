## Persephone's Two Kingdoms: Grain-and-Garin

Persephone’s Two Kingdoms: Grain-and-Garin is a short narrative management game built in Godot.
You play as Persephone, moving between the sunlit fields of Demeter and the shadows of Hades, trying to keep both the mortal world and the underworld from falling apart.

Each in-game month, mortals consume grain and the order of the dead decays.
In the overworld, Demeter farms while you dance at the altar to boost the harvest and prevent famine.
In the underworld, you work at Hades’ desk, judging myth-inspired souls in a mini-game to restore order before the dead riot.

Talk with Demeter and Hades, travel between realms, and try to survive the year without starving the living or collapsing the realm of the dead.

## Play the Game

Web version (GitHub Pages):  
https://wisteriach.github.io/Grain-and-Grave/

## How to Play

You play as **Persephone**, moving between the world of the living and the underworld, trying to keep both realms stable.

### Goal

Keep **both** of these above zero for as long as you can:

- **Grain** – food for mortals in the overworld  
- **Order** – stability in the underworld  

If either runs out, the game ends:

- Grain ≤ 0 → **famine ending** (mortals starve)  
- Order ≤ 0 → **underworld collapse ending** (the dead riot)

You can restart from the Game Over screen.

---

### Controls

- **Move**: Arrow keys or **W A S D**  
- **Interact / Talk / Use**: **E**
  - Use portals, talk to Demeter or Hades, use the altar, sit at the desk, etc.
- **Mini-game (judging souls)**:  
  - **↑** (Up arrow) – send soul to **Asphodel / peaceful afterlife**  
  - **↓** (Down arrow) – send soul to **Tartarus / punishment**

---

### Overworld (Demeter’s fields)

This is where you grow grain for mortals.

- While you are in the **overworld**, Demeter **automatically farms**, slowly increasing **Grain** over time.
- Stand on the **altar** and hold **E** to make Persephone **dance**:
  - Demeter’s farming is **boosted**, speeding up grain growth.
- Talk to **Demeter** with **E** to get flavour dialogue and hints.

Every in-game month, mortals consume a fixed amount of grain.  
If you ignore the fields for too long, Grain will eventually run out → famine.

---

### Underworld (Hades’ realm)

This is where you repair the order of the dead.

- While you are in the **underworld**, there is **no farming**:
  - Grain only goes **down** each month (mortals keep eating).
- Interact with **Hades** using **E** to hear his perspective on the state of the dead.
- Interact with the **desk** using **E** to start a **soul-sorting mini-game**:

  - You’ll see short descriptions of souls inspired by Greek myths  
    (kings, heroes, oath-breakers, self-sacrificing spouses, etc.).
  - For each case, choose:
    - **↑** – peaceful afterlife (Asphodel / Elysium)  
    - **↓** – punishment (Tartarus)
  - Correct judgments **increase Underworld Order**.  
    Wrong judgments **slightly decrease** it.

If you spend too long below without tending the fields, Grain will run low.  
If you ignore the desk and Hades, Order will decay until the underworld collapses.

---

### Time and Months

- The game advances in **months** (each month is ~1 minute of real time).
- At the end of every month:
  - **Grain decreases** (mortals eat).
  - **Order decreases** (the underworld naturally drifts toward chaos).
- Your actions between month ticks (farming and judging souls) are what keep those two bars from hitting zero.

Balance your time between **Demeter** and **Hades** and see how long you can keep both worlds alive.
```
