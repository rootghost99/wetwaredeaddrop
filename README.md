# WETWARE DEADDROP

```
 █░█░█ █▀▀ ▀█▀ █░█░█ ▄▀█ █▀█ █▀▀
 ▀▄▀▄▀ ██▄ ░█░ ▀▄▀▄▀ █▀█ █▀▄ ██▄
 █▀▄ █▀▀ ▄▀█ █▀▄ █▀▄ █▀█ █▀█ █▀█
 █▄▀ ██▄ █▀█ █▄▀ █▄▀ █▀▄ █▄█ █▀▀
```

A cyberpunk trading game where you hustle goods across neon-lit sectors, dodge loan sharks, and try to survive the streets.

**[Play Now](https://rootghost99.github.io/wetwaredeaddrop/)** | **[Report Bug](https://github.com/rootghost99/wetwaredeaddrop/issues)**

---

## Overview

You're a runner in a dystopian megacity. You start with cash, debt to a loan shark, and 30 days to turn your life around. Buy low, sell high, and try not to get killed.

- **Buy goods** cheap in one sector
- **Sell them** for profit in another
- **Pay off your debt** before the shark finds you
- **Survive** random events, thugs, and corporate security
- **Upgrade** your gear and hideout
- **Complete missions** for extra cash

---

## How to Play

### Goal
Survive until the end of the game with a **positive net worth** (Cash + Inventory Value - Debt ≥ 0).

### Basic Loop
1. **Travel** to a new sector (costs 1 day, adds 10% debt interest)
2. **Buy** goods that are cheap in the current sector
3. **Travel** to a sector where those goods sell high
4. **Sell** for profit
5. **Pay down debt** when you can
6. **Repeat** until you win or die

### Game Over Conditions
- Health reaches 0%
- Time runs out with negative net worth
- Complete bankruptcy (no cash, net worth below -$10,000)

---

## Sectors

Each sector has **specialties** - one item is cheap there, another is expensive.

| Sector | Description | Cheap | Expensive |
|--------|-------------|-------|-----------|
| **Sector 7** | Water district | Nano-Water | AI Cores |
| **Neon Bay** | Party zone | Neuro-Stims | Mech-Parts |
| **The Stack** | Industrial hub | Mech-Parts | Neuro-Stims |
| **Void** | Black market | AI Cores | Nano-Water |
| **High City** | Tech elite | Memory | Nano-Water |

### Sector Traits
- **Sector 7**: Low danger, high police presence
- **Neon Bay**: Moderate danger, corrupt cops
- **The Stack**: Corporate security active
- **Void**: High danger, no law enforcement
- **High City**: Low danger, strict enforcement

---

## Trade Goods

| Item | Base Price Range | Notes |
|------|------------------|-------|
| Nano-Water | $5 - $25 | Cheap, low margins |
| Memory | $20 - $80 | Stable mid-tier |
| Neuro-Stims | $100 - $400 | Good profit potential |
| Mech-Parts | $500 - $1,500 | High value |
| AI Cores | $2,000 - $8,000 | Highest risk/reward |

### Price Dynamics
- Prices fluctuate each day
- **Bubbles** can form (prices spike then crash)
- **Trends** indicate price direction (▲ up, ▼ down)
- Buy the **Price Scanner** to see predictions

---

## The Loan Shark

You start in debt. Every day, your debt grows by **10%**.

- If debt exceeds $5,000, the shark may find you
- Higher debt = higher encounter chance
- You can **pay** what he demands, **pay all** your cash, or **refuse**
- Refusing means a beating (health damage) and +15% debt penalty

**Pro tip**: Pay down debt early to avoid the compound interest death spiral.

---

## Random Events

When traveling, there's a 40% chance of a random event.

### Good Events (30%)
- Lucky Find (free cash)
- Market Tip (price spike)
- Medical Supply (health restore)
- Debt Forgiveness (debt reduction)
- Underground Auction (free goods)
- Reputation Boost
- Abandoned Cargo
- Security Bribe (avoid next police raid)

### Bad Events (50%)
- Mugged (lose cash + health)
- Police Raid (lose inventory)
- Hacker Attack (lose cash)
- Rival Sabotage (destroy cargo)
- Protection Racket (pay or get hurt)
- Toxic Exposure (health damage)
- Market Crash (price collapse)
- Ambush
- Sector Blackout

### Neutral Events (20%)
- Rumors and hints
- Drone surveillance
- Graffiti messages (sometimes hide loot)

---

## NPCs

You may encounter helpful (or dangerous) characters while traveling.

### Doc Chrome (👨‍⚕️)
*"Need patching up, runner?"*
- Appears in: Sector 7, The Stack, High City
- Offers healing for $300-500
- Restores 30-50% health

### Whisper (🕵️)
*"Information is the real currency..."*
- Appears in: Neon Bay, Void
- Sells market intel for $500-800
- Reveals which sectors have best prices
- May trigger price spikes

### The Fence (🦊)
*"Hot merchandise? I know buyers..."*
- Appears in: Void, Neon Bay
- Buys your goods at 30-60% premium
- Great for offloading inventory fast

### Razor (😎)
*"Let's settle this like professionals."*
- Appears in: All sectors
- Challenges you to a negotiation duel
- Win = double your stake
- Lose = lose your stake

---

## Shop Upgrades

Access the shop from the stats panel.

| Upgrade | Cost | Effect |
|---------|------|--------|
| **Cargo Expander** | $1,000+ | +25 inventory capacity (max 5) |
| **Med-Kit** | $500 | Restore 35% health |
| **Body Armor** | $2,500 | Reduce event damage by 30% |
| **Price Scanner** | $1,500 | See price predictions |

---

## Hideout System

Your hideout provides passive bonuses. Access via the 🏠 button.

### Security System
Reduces losses from theft events.
- Level 1: Basic Locks ($1,000) - 10% protection
- Level 2: Cameras ($3,000) - 20% protection
- Level 3: Armed Drones ($8,000) - 35% protection

### Medical Bay
Passive health regeneration each day.
- Level 1: First Aid Kit ($1,500) - +2% health/day
- Level 2: Auto-Doc ($4,000) - +5% health/day
- Level 3: Trauma Center ($10,000) - +10% health/day

### Intel Network
Improves price predictions accuracy.
- Level 1: Street Contacts ($2,000)
- Level 2: Informant Ring ($5,000)
- Level 3: Spy Satellite ($12,000)

### Hidden Storage
Bonus cargo capacity.
- Level 1: False Floor ($1,000) - +10 capacity
- Level 2: Hidden Room ($2,500) - +25 capacity
- Level 3: Warehouse ($6,000) - +50 capacity

---

## Mission System

Accept contracts for bonus rewards. Access via the 📋 button.

### Mission Types
- **Delivery**: Bring specific items to a sector
- **Collection**: Gather a certain amount of goods
- **Profit**: Make X amount of profit from trades
- **Grand Tour**: Visit all sectors
- **Survival**: Go X days without taking damage
- **Hacking**: Complete hack mini-games
- **Wealth**: Reach a net worth target

### Rewards
- Cash bonuses ($1,000 - $5,000)
- Reputation boosts
- Achievement progress

---

## Mini-Games

### Hacking (Breach Protocol)
Match hex codes in sequence before time runs out.
- 4x4 grid of hex values
- Click codes that match the sequence
- Wrong click = instant fail
- Rewards cash on success

### Negotiation
Stop the moving marker in the green zone.
- Marker bounces back and forth
- Green zone = success (double your stake)
- Miss = lose your stake
- Tests timing and nerve

---

## Reputation System

Each sector tracks your reputation (0-100).

| Level | Range | Effect |
|-------|-------|--------|
| Hostile | 0-19 | +15% prices, more bad events |
| Suspicious | 20-39 | +5% prices |
| Neutral | 40-59 | Normal |
| Known | 60-79 | -5% prices |
| Respected | 80-100 | -10% prices, can avoid fines |

### Building Reputation
- Complete missions
- Fair trading over time
- Random events
- NPC interactions

---

## Achievements

Unlock 18 achievements by playing. Access via the 🏆 button.

| Achievement | Requirement |
|-------------|-------------|
| First Steps | Complete your first trade |
| Getting Started | Complete 10 trades |
| Professional | Complete 100 trades |
| Millionaire | Have $1,000,000 cash |
| Freedom | Pay off all debt |
| Survivor | Win with <10% health |
| Hoarder | Fill inventory completely |
| Big Score | $10,000 profit on one sale |
| Explorer | Visit all 5 sectors |
| Shark Dodger | Survive 5 shark encounters |
| Speed Runner | Win in under 15 days |
| Pacifist | Win without buying armor |
| Operator | Complete first mission |
| Fixer | Complete 5 missions |
| Netrunner | Complete 5 hacks |
| Silver Tongue | Win 5 negotiations |
| Home Owner | Fully upgrade hideout |
| Legend | Max reputation in any sector |

---

## Difficulty Settings

Choose your starting conditions:

| Difficulty | Starting Cash | Starting Debt |
|------------|---------------|---------------|
| Easy | $10,000 | $3,000 |
| Medium | $5,000 | $5,000 |
| Hard | $3,000 | $5,000 |

### Game Length
- 30 Days (Quick)
- 60 Days (Standard)
- 90 Days (Extended)
- 180 Days (Marathon)

---

## Controls

| Action | How |
|--------|-----|
| Travel | Click sector buttons |
| Buy/Sell | Click BUY/SELL on item rows |
| Open Shop | Click SHOP button |
| Pay Debt | Click PAY DEBT button |
| Save/Load | Click SAVE/LOAD buttons |
| Hideout | Click 🏠 button |
| Missions | Click 📋 button |
| Achievements | Click 🏆 button |
| Toggle Sound | Click 🔊 button (bottom-right) |

---

## Tips & Strategy

1. **Pay debt early** - 10% daily interest compounds fast
2. **Learn sector specialties** - Buy where it's cheap, sell where it's expensive
3. **Watch for bubbles** - Get out before they pop
4. **Upgrade cargo first** - More capacity = more profit per trip
5. **Keep some cash reserve** - For emergencies and opportunities
6. **High City is safest** - Good for recovering health
7. **Void is most profitable** - But also most dangerous
8. **The Fence is your friend** - 30-60% bonus on sales
9. **Accept missions** - Free money on top of trading
10. **Build hideout security** - Protects high-value cargo

---

## Tech Stack

- Pure HTML/CSS/JavaScript
- No frameworks or dependencies
- Web Audio API for sound
- LocalStorage for saves
- Mobile responsive

---

## Contributing

Pull requests welcome! Please open an issue first to discuss major changes.

---

## License

MIT License - do whatever you want with it.

---

*Buy low. Sell high. Pay the shark. Survive the streets.*
