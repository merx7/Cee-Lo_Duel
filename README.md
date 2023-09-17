# Cee-lo Mobile Game (Java, 2017)

A classic two-player dice game inspired by Cee-lo, this mobile app is designed with eight distinct activities: Login, Register, Main Menu, Statistics, Gameplay, Game Rules, Leaderboard, and Account Modification. It integrates with SQLite Database for account management and game statistics.

## Features:

- **User Management**: Register or login to access the game. User data managed through SQLite.
- **Game Mechanics**: Players swipe to roll dice, with unique dice combinations determining game outcomes like instant wins, rerolls, or head-to-head die value comparisons.
- **Statistics & Leaderboards**: Track your wins, losses, and scores. View leaderboards to see top players.
- **Game Knowledge**: Access in-game rules for a comprehensive understanding of Cee-lo.
- **Customization**: Modify account details including username, email, and password.

## Tech Stack & Requirements:

- Developed in Java (2017).
- Minimum SDK: API 17 (Android 4.2, Jelly Bean).
- Target SDK: API 26 (Android 8.0, Oreo).

## Rules of Cee-lo:

1. **Three-of-a-Kind**: Rolling three of the same number is an automatic win.
2. **4-5-6 Combination**: Rolling a 4, 5, and 6 in any order is an automatic win.
3. **1-2-3 Combination**: Rolling a 1, 2, and 3 in any order is an automatic loss.
4. **Point Setting**: If a player rolls a "two-of-a-kind", the third die becomes their point. To win, they must get a higher point than their opponent or a winning dice combination.
5. **Rerolls**: Players must reroll if they don't set a point or roll a winning or losing combination.

## Future Plans:

- **Kotlin Recreation**: Transforming the Java-based game into a modern Kotlin app.
- **Multiplayer Support**: Enable users to compete with friends and players worldwide.
- **Crypto Integration**: Integrate with cryptocurrency features for in-game rewards or transactions.
- **Cross-Platform Compatibility**: Extend the game's reach to iOS users using Kotlin Multiplatform.
- **Web3 Technologies**: Explore the possibilities of decentralized gaming through Web3.
