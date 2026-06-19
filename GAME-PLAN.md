# Coin Pusher 🪙 — v12

## Overview
An addictive 3D coin pusher arcade game built with Three.js + Rapier physics engine. Two-tier cabinet with compound pusher, special coins, particles, jackpot system, and arcade neon aesthetics.

## Features (v12)
- ✅ Two-tier shelf + compound kinematic pusher
- ✅ Gold/silver coins with physics (Rapier 3D v0.14)
- ✅ **Special coins**: Bomb (explosion push), Magnet (attract nearby), Heavy (3x mass), Multiplier (3x score)
- ✅ **Particle system**: Sparkles on coin collisions, collect effects, bomb blasts, shake effect
- ✅ **Jackpot meter**: Fill bar → 25th coin triggers 20-coin cascade
- ✅ **Shake mechanic**: ⚡ Shake button (4s cooldown, S key), impulse on all coins
- ✅ **Combo variety**: Cascade (3-5x), Tower Drop (6-9x), JACKPOT (10x+)
- ✅ **Neon lights**: Purple/blue top strips, red bottom glow, pulse on combos
- ✅ **Score popups**: Type-specific (+1, x3!✨, 💥, 🧲)
- ✅ Screen shake + varied sound effects per coin type
- ✅ Cabinet with glass walls, gold trim, felt playfield

## Special Coin Types
| Type | Color | Effect | Rarity |
|------|-------|--------|--------|
| Normal | Gold/Silver | +1 score | 60% |
| Bomb | Red glow | Explosion pushes nearby coins on collect | 10% |
| Magnet | Cyan glow | Attracts coins within 2.2 radius | 10% |
| Heavy | Dark iron | 3x mass, pushes more coins | 10% |
| Multiplier | Pink glow | 3x score on collect | 10% |

## Controls
- **Mouse click / Space / Enter**: Drop coin
- **S key**: Shake machine
- **⚡ Shake button**: Nudge all coins (4s cooldown)

## Tech Stack
| Layer | Tech |
|-------|------|
| Rendering | Three.js r170 (CDN importmap) |
| Physics | Rapier 3D v0.14 (WASM via CDN) |
| UI | HTML/CSS overlay |

## Phases
- **v1** ✅ — Core mechanics: platform, pusher, coins, score, basic cabinet
- **v2** ✅ — Visual polish: particles, neon lights, combo variety, shake mechanic
- **v3** ✅ — Special coins: bomb, magnet, heavy, multiplier + jackpot meter

## Future Ideas
- Stage goals (collect X coins, survive N drops)
- Lucky wheel board event
- Prize lanes / side gutters
- More special coin types (splitter, ghost)
- Coin shop / progression unlocks
