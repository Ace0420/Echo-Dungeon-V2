# Echo Dungeon Enhanced

A fully voice-controlled dungeon crawler RPG designed for accessibility, specifically for blind and visually impaired players.

## 🎮 Game Overview

Echo Dungeon Enhanced is a text-based RPG that uses voice commands for all interactions. Navigate through procedurally generated dungeons, fight monsters, collect treasure, and level up your character—all through voice alone.

## 🌟 Features

- **100% Voice Controlled**: Every action is controlled by voice commands
- **Three Character Classes**: Warrior, Mage, and Rogue, each with unique abilities
- **Procedurally Generated Dungeons**: Each level is randomly created with 10x10 grid
- **Combat System**: Turn-based combat with attack, defend, and special abilities
- **Magic Rings**: Equip up to 5 different ring types for stat bonuses
- **Save/Load System**: Save your progress with a shareable code
- **Progressive Difficulty**: Descend through multiple dungeon levels
- **Screen Reader Friendly**: Accessible text display for assistive technology

## 📋 Requirements

- **Browser**: Chrome or Edge (for speech recognition)
- **Connection**: HTTPS or localhost
- **Microphone**: Required for voice input
- **Speakers/Headphones**: Required for audio feedback

## 🚀 Getting Started

1. Open the game in Chrome or Edge browser
2. Allow microphone permissions when prompted
3. Tap anywhere on the screen to start
4. Choose your class: "warrior", "mage", or "rogue"
5. Start exploring!

## 🎯 Character Classes

### Warrior
- **Health**: 120
- **Mana**: 30
- **Gold**: 50
- **Special**: Power Strike (40 damage, 15 mana)
- **Starting Items**: Iron Sword, Leather Armor, 2 Health Potions

### Mage
- **Health**: 80
- **Mana**: 100
- **Gold**: 75
- **Special**: Fireball (30 damage, 20 mana)
- **Starting Items**: Magic Staff, Cloth Robes, Health Potion, Mana Potion

### Rogue
- **Health**: 100
- **Mana**: 60
- **Gold**: 100
- **Special**: Backstab (35 damage, 25 mana)
- **Starting Items**: Steel Dagger, Studded Leather, Lockpicks, Health Potion

## 🗣️ Voice Commands

### Movement
- "north" / "forward" - Move north
- "south" / "back" - Move south
- "east" / "right" - Move east
- "west" / "left" - Move west
- "go down stairs" - Descend to next level

### Actions
- "look around" - Describe current room
- "search" - Search the room for hidden items
- "open chest" - Open a treasure chest
- "drink fountain" - Use a magical fountain (full heal)
- "meditate" - Restore 15 mana
- "wear ring" - Equip a ring (specify type: health, mana, protection, strength, wisdom)

### Combat
- "attack" / "fight" - Basic attack
- "defend" / "block" - Reduce incoming damage by 50%
- "special" / "ability" - Use your class special ability
- "use potion" / "drink potion" - Use health or mana potion
- "flee" / "run" - Attempt to escape combat

### Information
- "status" / "stats" - Check character status
- "inventory" / "items" - List your items
- "hint" - Get a helpful hint
- "help" - List available commands
- "commands" - Detailed command list

### System
- "save game" - Generate a save code
- "load game" - Prepare to load a save
- "code [your-save-code]" - Load saved game

## 🏰 Room Types

- **Entrance**: Safe starting area (center of map)
- **Empty Rooms**: Abandoned areas with possible loot
- **Treasure Rooms**: Contain valuable chests
- **Enemy Lairs**: Monsters guard these chambers
- **Trap Rooms**: Dangerous traps (15 damage first visit)
- **Fountains**: Magical healing fountains (one-time use)
- **Crypts**: Ancient burial chambers
- **Boss Room**: Contains the level dragon (southeast corner at 9,9)
- **Stairs**: Portal to next dungeon level

## ⚔️ Combat System

Combat is turn-based. Each turn you can:

1. **Attack**: Deal 15-30 damage (+ ring bonuses)
2. **Defend**: Reduce next attack by 50%
3. **Special**: Use class ability (consumes mana)
4. **Potion**: Restore health (40 HP) or mana (30 MP)
5. **Flee**: Chance to escape (depends on enemy)

## 💍 Magic Rings

Find and equip rings for permanent bonuses:

- **Ring of Minor Health**: +10 Max Health
- **Ring of Minor Mana**: +10 Max Mana
- **Ring of Protection**: +5 Max Health
- **Ring of Strength**: +2 Attack Damage
- **Ring of Wisdom**: +5 Max Mana

## 🎲 Enemies

### Common Enemies
- **Goblin**: 30 HP, 8 damage (Easy to flee)
- **Skeleton**: 40 HP, 10 damage
- **Orc**: 60 HP, 15 damage
- **Wraith**: 50 HP, 18 damage
- **Troll**: 80 HP, 20 damage

### Special Enemies
- **Dragon** (Boss): 150 HP, 30 damage (Very hard to flee)
- **Mimic** (Trap): 45 HP, 12 damage (Disguised as chest)

## 📈 Progression

- **Experience**: Gain XP from defeating enemies
- **Level Up**: Automatic when XP threshold reached
  - +20 Max Health
  - +10 Max Mana
  - Full heal and mana restore
  - XP requirement increases by 1.5x
- **Gold**: Collect from enemies, chests, and treasures

## 💾 Save System

To save your game:
1. Say "save game"
2. A save code will be ready to you
3. Copy the code

To load:
1. Say "load game"
2. Say "code" followed by your save code (no spaces)

**Example**: "code 1234"

## 🗺️ Map Layout

The dungeon is a 10x10 grid:
- **Center (5,5)**: Entrance
- **Southeast (9,9)**: Boss Room
- **Near Boss (9,8)**: Stairs (unlocked after defeating boss)
- **Random**: All other rooms

## 🎯 Tips for Success

1. **Search Everything**: Many rooms contain hidden loot
2. **Use Fountains Wisely**: They only work once per fountain
3. **Manage Mana**: Meditate regularly to keep mana high
4. **Equip Rings Early**: Stat bonuses help throughout the game
5. **Save Before Boss**: Always save before challenging the dragon
6. **Flee When Low**: Don't be afraid to retreat and heal
7. **Explore Thoroughly**: Check every room for treasure chests

## ♿ Accessibility Features

- **Full Voice Control**: No keyboard or mouse needed
- **Clear Audio Feedback**: All game information is spoken
- **Screen Reader Support**: Hidden text display for assistive tech
- **Simple Commands**: Natural language processing
- **No Time Pressure**: Take as long as you need
- **Save Anytime**: Save and resume whenever needed

## 🐛 Troubleshooting

### Voice Not Working
- Ensure you're using Chrome or Edge
- Check microphone permissions
- Verify HTTPS connection (or localhost)
- Try refreshing the page

### Audio Not Playing
- Check system volume
- Verify browser audio permissions
- Try a different browser

### Game Not Responding
- Tap the screen again
- Refresh the page
- Clear browser cache

## 📱 Mobile Support

The game works on mobile devices with:
- Chrome or Edge browser
- Microphone access
- Stable internet connection

Note: Voice recognition may be less accurate on mobile.

## 🏆 Game Objectives

1. **Short Term**: Defeat the dragon on each level
2. **Medium Term**: Descend through multiple dungeon levels
3. **Long Term**: Reach the highest level possible
4. **Mastery**: Complete a level without using potions

## 🔄 Version History

**Version 1.0** (Current)
- Initial release
- Three character classes
- Full voice control
- Save/load system
- Ring equipment system
- Multiple room types
- Progressive difficulty

## 👥 Credits

Designed for accessibility and created with love for the blind gaming community.

## 📄 License

Free to play and share. Enjoy your adventure!

---

**Have fun exploring the Echo Dungeon!** 🎮🔊
