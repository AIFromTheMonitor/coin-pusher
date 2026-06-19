# 🪙 Coin Pusher — Feature Ideas

Researched from Coin Dozer, Raccoin, real arcade machines, and mobile coin pusher games.

---

## 🥇 Tier 1 — Quick Wins (high fun, low effort)

### 🪙 Special Coins (different token values)
- **Gold Coin** — worth 3 tokens when collected (costs 2 to drop)
- **Silver Coin** — worth 2 tokens (costs 1)
- **Bronze Coin** — worth 1 token (costs 1, current default)
- Visual: different materials/colors already exist (goldCoin, silverCoin)
- Strategy: risk premium coins for higher return

### 💥 Giant Coin
- 3x size, 5x weight — causes massive splash when dropped
- Costs 5 tokens to drop
- Pushes everything in its path, triggers cascades
- Visual: oversized glowing gold coin
- Great "big play" moment

### 🌧️ Coin Rain
- Drops 5-8 coins simultaneously in a spread pattern
- Costs 3 tokens
- Creates instant pile-up pressure
- Visual: coins fall from above like rain

### 🧱 Coin Wall (power-up)
- Temporary walls appear on both sides for 15 seconds
- Prevents coins from falling off the sides
- Earned randomly when collecting coins (5% chance)
- Visual: glowing blue energy walls

### 🔥 Streak Multiplier
- Consecutive rapid collects multiply token gain
- 2x at 3 streak, 3x at 5 streak, 5x at 8 streak
- Already have the combo system — just attach token multiplier
- Visual: combo text already exists, add multiplier number

---

## 🥈 Tier 2 — Depth Builders

### 🎁 Mystery Box
- A cube/chest drops onto the field (physics object like a coin)
- Gets pushed like a coin — when it falls off, reveals random reward:
  - Token bonus (5-20 tokens)
  - Free Giant Coin drop
  - Coin Rain activation
  - Coin Wall activation
  - Nothing (dud — adds tension)
- Appears every 15-20 drops randomly
- Visual: glowing purple/gold cube

### 🎰 Lucky Wheel
- Every 25 coins collected → wheel spins automatically
- Prizes: token jackpot (10-50), Giant Coin, Coin Rain, Mystery Box, Coin Wall
- Simple slot-machine style overlay
- Gives regular dopamine hits beyond just collecting

### 📈 Milestone Rewards
- At 50 total collects: unlock Silver Coins
- At 100: unlock Coin Rain
- At 200: unlock Giant Coin
- At 500: unlock Gold Coins
- Gives progression feeling — not everything available at start
- Display milestone progress bar

### 🎯 Target Zones
- Occasionally a glowing zone appears on the shelf
- Drop a coin into the zone for bonus tokens (2x-5x)
- The zone moves/changes every few drops
- Adds skill element to aiming

---

## 🥉 Tier 3 — Polish & Magic

### ✨ Particle Effects
- Coin sparks on collision (Three.js particles)
- Golden burst when Giant Coin hits
- Trail behind falling coins
- Glow pulse on combo streaks

### 🎵 Sound Design
- Different drop sounds for different coin types
- Escalating pitch on combo streaks
- Jackpot sound for big cascades
- Ambient arcade background hum

### 🏆 Daily Challenge
- "Push 50 coins today" → bonus tokens
- "Trigger 3 Giant Coin cascades" → free Giant Coin
- Resets daily, gives reason to come back

### 🎨 Machine Skins
- Unlockable visual themes: Neon, Retro, Gold, Crystal
- Changes background, trim colors, platform material
- Earned through milestones or daily challenges

### 👻 Boss Coin
- Rare, massive coin (5x size) appears randomly
- Takes multiple pushes to move
- Worth 20 tokens when finally collected
- Whole field shakes when it falls
- Creates epic memorable moments

---

## 🎯 Recommendation: Start with Tier 1

The core loop is: drop coins → watch them push → collect rewards. Tier 1 enhances this without breaking the simple fun:

1. **Gold/Silver coins** — instant strategy layer
2. **Giant Coin** — big satisfying moments
3. **Streak multiplier** — already have combo system, just add token multiplier
4. **Coin Wall** — simple, dramatic, saves coins

These 4 add depth while keeping the core relaxing coin-dropping vibe intact.
