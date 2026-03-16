# tamagotchi-pet
🐣 Browser-based Tamagotchi virtual pet game with pixel art - Relive the 90s handheld pet craze!# 🥚 Virtual Pet - Tamagotchi Revival

![Virtual Pet Banner](https://img.shields.io/badge/Tamagotchi-Revival-purple?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> **Relive the 90s nostalgia!** Take care of your own virtual pet in this browser-based Tamagotchi-style game with pixel art animations, retro gameplay mechanics, and modern web features.

## 🎮 About

Remember the joy of caring for your Tamagotchi in the 90s? This project brings back that nostalgic experience with a modern twist! Watch your pet grow from an egg to a fully mature adult while managing its happiness, hunger, energy, and cleanliness.

## ✨ Features

### 🐣 Pet Evolution System
- **5 Growth Stages**: Egg → Baby → Child → Teen → Adult
- Each stage has unique emoji representation
- Evolution triggered by age milestones
- Special evolution notification animations

### 📊 Stat Management System
- **Happiness** 💚 - Keep your pet entertained and loved
- **Hunger** 🍔 - Feed regularly to maintain health
- **Energy** 💤 - Rest is essential for growth
- **Cleanliness** ✨ - Keep your pet's environment clean

### 🎯 Interactive Actions
- **🍔 Feed** - Satisfy hunger and boost happiness
- **🎮 Play** - Increase happiness but consume energy
- **🧼 Clean** - Restore cleanliness to 100%
- **💤 Sleep** - Fully restore energy levels
- **💊 Medicine** - General health boost for all stats
- **💡 Light Toggle** - Day/night mode for your pet

### 💾 Save System
- **Automatic Save** - Game state saved every 30 seconds
- **Persistent Storage** - Uses localStorage for data persistence
- **Time Decay** - Stats naturally decrease even when you're away
- **Realistic Simulation** - Time passes while you're offline

### 🎨 Retro Design
- **90s LCD Screen** - Authentic Tamagotchi green screen aesthetic
- **Scanline Effect** - Retro CRT monitor simulation
- **Pixel Art Animations** - Smooth floating and bouncing effects
- **Colorful Device Shell** - Purple gradient plastic shell design
- **Responsive Layout** - Works perfectly on mobile and desktop

### 🔊 8-bit Sound Effects
- Different beeps for each action
- Web Audio API for authentic retro sounds
- Play, Feed, Clean, Sleep, Heal, and Evolution sounds
- Non-intrusive audio feedback

### 📈 Statistics Tracking
- Total feedings counter
- Total plays counter
- Total cleanings counter
- Age tracking in days
- Current stage information

### 🎭 Dynamic Mood System
- **Happy** - Bouncing animation when stats are high
- **Sad** - Shaking animation when attention needed
- **Sleeping** - Dimmed appearance during sleep
- **Status Messages** - Real-time feedback on pet's condition

## 🚀 Quick Start

### Option 1: Direct Download
1. Download `index.html` from this repository
2. Open the file in any modern web browser
3. Start caring for your virtual pet!

### Option 2: Clone Repository
```bash
git clone https://github.com/tharev/tamagotchi-pet.git
cd tamagotchi-pet
# Open index.html in your browser
```

### Option 3: GitHub Pages
Visit the live demo: [Tamagotchi Virtual Pet](https://tharev.github.io/tamagotchi-pet/)

## 🎯 How to Play

1. **Starting Out**: Your pet begins as an egg 🥚
2. **First Evolution**: After 1 day, it hatches into a baby 🐣
3. **Daily Care**: 
   - Feed when hunger is low
      - Play to keep happiness high
         - Clean when environment gets dirty
            - Let it sleep when energy is depleted
            4. **Watch it Grow**: Your pet evolves through 5 stages over 14 days
            5. **Keep it Alive**: Don't let any stat reach 0, or your pet will die 💀

            ## 📱 Compatibility

            - ✅ Chrome/Edge (recommended)
            - ✅ Firefox
            - ✅ Safari
            - ✅ Mobile browsers (iOS/Android)
            - ✅ Works offline after first load

            ## 🛠️ Technical Details

            ### Technologies Used
            - **HTML5** - Semantic structure
            - **CSS3** - Animations, gradients, flexbox/grid
            - **Vanilla JavaScript** - No dependencies!
            - **Web Audio API** - Sound effects
            - **localStorage API** - Save game data

            ### File Structure
            ```
            tamagotchi-pet/
            ├── index.html          # Complete single-file application
            └── README.md          # This file
            ```

            ### Key Features Implementation
            - **Game Loop**: Updates every 5 seconds for gradual stat decay
            - **Age System**: Checks evolution every minute
            - **Auto-save**: Saves progress every 30 seconds
            - **Time Tracking**: Calculates time passed when returning
            - **Responsive Design**: Mobile-first CSS approach

            ## 🎨 Customization

            The entire game is in a single HTML file, making it easy to customize:

            ### Change Pet Emojis
            ```javascript
            const stages = [
                { emoji: '🥚', name: 'Egg', minAge: 0 },
                    { emoji: '🐣', name: 'Baby', minAge: 1 },
                        // Modify these to change pet appearance
                        ];
                        ```

                        ### Adjust Difficulty
                        ```javascript
                        // Make stats decay faster or slower
                        pet.hunger = Math.max(0, pet.hunger - 0.5); // Change 0.5
                        pet.happiness = Math.max(0, pet.happiness - 0.3); // Change 0.3
                        ```

                        ### Modify Evolution Times
                        ```javascript
                        const stages = [
                            { emoji: '🥚', name: 'Egg', minAge: 0 },
                                { emoji: '🐣', name: 'Baby', minAge: 1 }, // Change age here
                                    // Adjust minAge values for faster/slower evolution
                                    ];
                                    ```

                                    ## 📸 Screenshots

                                    ### Main Game Screen
                                    ![Main Screen](https://via.placeholder.com/500x400/9ccc65/333?text=Virtual+Pet+Screen)

                                    ### Pet Evolution Stages
                                    | Egg 🥚 | Baby 🐣 | Child 🐥 | Teen 🐦 | Adult 🦜 |
                                    |--------|---------|----------|---------|----------|
                                    | Day 0  | Day 1   | Day 3    | Day 7   | Day 14   |

                                    ## 🤝 Contributing

                                    Contributions are welcome! Here are some ideas:
                                    - Add more pet evolution paths
                                    - Create different pet species
                                    - Add mini-games
                                    - Implement achievement system
                                    - Add sound toggle option
                                    - Create pet accessories/customization
                                    - Multi-pet support

                                    ### How to Contribute
                                    1. Fork the repository
                                    2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
                                    3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
                                    4. Push to the branch (`git push origin feature/AmazingFeature`)
                                    5. Open a Pull Request

                                    ## 📝 License

                                    This project is open source and available under the [MIT License](LICENSE).

                                    ## 🙏 Acknowledgments

                                    - Inspired by the original Tamagotchi virtual pets from Bandai (1996)
                                    - Built with nostalgia and love for retro gaming
                                    - Emoji graphics from system default emoji sets
                                    - No external libraries or dependencies used!

                                    ## 🐛 Known Issues

                                    - Sound may not play on first interaction (browser autoplay policy)
                                    - Time decay continues even when browser is closed
                                    - Pet cannot be revived after death (must reset)

                                    ## 🔮 Future Enhancements

                                    - [ ] Multiple save slots
                                    - [ ] Pet breeding system
                                    - [ ] Achievement badges
                                    - [ ] Social features (share your pet)
                                    - [ ] Custom themes/skins
                                    - [ ] Sound volume control
                                    - [ ] Rare evolution branches
                                    - [ ] Special events/holidays

                                    ## 📞 Support

                                    Having issues or questions? 
                                    - Open an [Issue](https://github.com/tharev/tamagotchi-pet/issues)
                                    - Check existing issues for solutions
                                    - Contribute fixes via Pull Requests

                                    ## 🌟 Show Your Support

                                    If you enjoyed this project, please:
                                    - ⭐ Star this repository
                                    - 🐛 Report bugs
                                    - 💡 Suggest new features
                                    - 🔄 Share with friends
                                    - 🤝 Contribute code

                                    ---

                                    **Made with 💜 by [tharev](https://github.com/tharev)**

                                    *Bringing 90s nostalgia to the modern web, one pixel at a time!*

                                    🎮 **Play now and relive your childhood memories!** 🎮
