# iOS.Games.Cards.TarneebMaster
A sophisticated iOS Tarneeb card game with AI opponents powered by machine learning.

# TarneebMaster

A sophisticated iOS Tarneeb card game with AI opponents powered by machine learning.

## Overview

TarneebMaster is a complete implementation of the popular Middle Eastern trick-taking card game Tarneeb (also known as "Tarnibe" or "Hakam"). The game features advanced AI opponents that use both heuristic strategies and machine learning models trained through reinforcement learning.

# How to Play TarneebMaster

Welcome to TarneebMaster! This guide will teach you everything you need to know to play and enjoy the classic Middle Eastern card game Tarneeb.

## What is Tarneeb?

Tarneeb (طرنيب) is a popular trick-taking card game played throughout the Middle East. It's a partnership game where two teams of two players compete to win tricks and reach the target score.

---

## Game Setup

### Players & Teams
- **4 players** seated in compass positions: North, East, South, West
- **Team 1**: North & South (partners)
- **Team 2**: East & West (partners)
- You play as **South**, with AI controlling the other three players

### The Deck
- Standard 52-card deck
- **Ranking** (high to low): A, K, Q, J, 10, 9, 8, 7, 6, 5, 4, 3, 2
- Each player receives **13 cards**

---

## Game Flow

### Phase 1: Bidding

Before playing, teams bid on how many tricks they believe they can win.

| Bid | Meaning |
|-----|---------|
| **7-12** | Number of tricks you promise to win |
| **13 (Kaboot)** | All 13 tricks - high risk, high reward! |
| **Pass** | Skip bidding this round |

**Bidding Rules:**
- Bidding starts with the dealer and goes clockwise
- Each bid must be higher than the previous bid
- You can **Pass** if you don't want to bid higher
- If everyone passes, cards are redealt
- The highest bidder wins and chooses the **trump suit**

### Phase 2: Trump Selection

The winning bidder selects a trump suit (♠ ♥ ♦ ♣).

**Tips for choosing trump:**
- Pick a suit where you have many cards
- Strong cards (A, K, Q) in the suit help
- Consider your partner's potential cards

### Phase 3: Playing Tricks

A trick consists of each player playing one card.

**Playing Rules:**
1. The winning bidder leads the first trick
2. Play proceeds clockwise
3. **You must follow suit** if you have a card of the led suit
4. If you can't follow suit, you may play **any card** (including trump)
5. The winner of each trick leads the next one

**Who Wins the Trick?**
- If trump was played: **Highest trump** wins
- If no trump: **Highest card of the led suit** wins

---

## Scoring

### Bidding Team
| Result | Score |
|--------|-------|
| **Win bid or more tricks** | + tricks won |
| **Fail to make bid** | - bid amount |
| **Kaboot Success (13/13)** | +26 points |
| **Kaboot Failure** | -16 points |

### Non-Bidding Team
| Result | Score |
|--------|-------|
| **Opponents succeed** | 0 points |
| **Opponents fail** | + tricks won |
| **Unbid Kaboot (13/13)** | +16 bonus |

### Winning the Game
- First team to reach the **target score** wins
- Target options: **31**, **41**, or **61** points

---

## Game Controls

### Your Turn
- **Tap a card** to play it
- **Use arrows** (◀ ▶) to scroll through your hand
- Valid cards are highlighted

### Other Features
- **Last Trick**: View the previous trick
- **Score Panel**: Track both teams' scores
- **Trump Indicator**: Shows the current trump suit

---

## Strategy Tips

### Bidding Strategy
- 🎯 Count your high cards (Aces, Kings, Queens)
- 🎯 Long suits (5+ cards) are valuable
- 🎯 Bid conservatively until you learn the game
- 🎯 Trust your partner's bidding signals

### Playing Strategy
- ♠ **Lead with Aces** when you have them
- ♠ **Save trump cards** for when you need them
- ♠ **Follow your partner's lead** - they're on your team!
- ♠ **Trump when void** to win important tricks
- ♠ **Count cards** - track what's been played

### Partnership Play
- 🤝 Support your partner's suit
- 🤝 Don't trump your partner's winning card
- 🤝 Signal strength by playing high cards

---

## Glossary

| Term | Definition |
|------|------------|
| **Tarneeb** | Arabic for "trump" - gives the game its name |
| **Trick** | One round where each player plays a card |
| **Trump** | The powerful suit that beats all others |
| **Kaboot** | Bidding 13 - the ultimate challenge |
| **Void** | Having no cards of a particular suit |
| **Ruff** | Playing trump when you can't follow suit |
| **Lead** | Playing the first card of a trick |

---

## Quick Reference Card

```
┌─────────────────────────────────────────┐
│           TARNEEB QUICK GUIDE           │
├─────────────────────────────────────────┤
│  CARD RANK: A K Q J 10 9 8 7 6 5 4 3 2  │
│  BIDS: 7-13 (13 = Kaboot)               │
│  TEAMS: North+South vs East+West        │
├─────────────────────────────────────────┤
│  MUST follow suit if possible           │
│  TRUMP beats all other suits            │
│  HIGHEST card of led suit wins          │
│  (unless trumped)                       │
├─────────────────────────────────────────┤
│  WIN BID → Score tricks won             │
│  FAIL BID → Lose bid amount             │
│  FIRST TO TARGET SCORE WINS!            │
└─────────────────────────────────────────┘
```

---

## Need More Help?

- **[tarneeb_rules.md](tarneeb_rules.md)** - Complete official rules
- **[README.md](README.md)** - App features and overview

---

**Good luck and have fun! 🃏**
