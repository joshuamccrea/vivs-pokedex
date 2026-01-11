# Viv's Pokedex

A colorful, interactive Pokedex featuring all 151 original Pokemon with a classic 1980s design aesthetic.

## Features

- 🎨 Classic Pokedex red theme with retro styling
- 🔍 Search by Pokemon name or type
- ⭐ Mark Pokemon as favorites (gold border)
- ✅ Track seen Pokemon (green border)
- 📖 Detailed Pokemon information including descriptions, types, and evolution chains
- 💾 Progress saved automatically in browser localStorage
- 📱 Responsive design for mobile and desktop

## How to Use

1. **Browse Pokemon**: Scroll through all 151 original Pokemon
2. **Search**: Use the search box to filter by name or type (e.g., "fire", "pikachu")
3. **View Details**: Click any Pokemon to see full details
4. **Mark as Favorite**: Click the yellow star ⭐ in the detail view to favorite (appears first in list with gold border)
5. **Mark as Seen**: Click "Mark as Seen" checkbox in detail view (green border and checkmark)
6. **Navigate Evolutions**: Click on evolution images to jump to that Pokemon's details

## Installation

### GitHub Pages (Online) - Recommended
1. Create a new GitHub repository (e.g., "vivs-pokedex")
2. Upload only the `index.html` file
3. Enable GitHub Pages in repository Settings > Pages
4. Select the main branch and save
5. Your Pokedex will be live at: `https://[your-username].github.io/[repository-name]/`

**Note:** Pokemon images are loaded automatically from PokeAPI's online sprite repository, so you don't need to upload any image files!

### Option 2: Use with Local Images (Optional)
If you want to use custom/higher quality images:
1. Download the index.html file
2. Place your Pokemon images (1.png through 151.png) in the same folder
3. Modify the image source URLs in the HTML to use local files
4. Open index.html in your web browser

## File Structure

```
vivs-pokedex/
├── index.html          # Main Pokedex application (all you need!)
└── README.md           # This file (optional)
```

Pokemon images are automatically loaded from: `https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/`

## Technologies Used

- HTML5
- CSS3 (with animations and gradients)
- Vanilla JavaScript
- LocalStorage API for data persistence (uses unique keys: `vivSeenPokemon`, `vivFavoritePokemon`)
- Google Fonts (Press Start 2P, Orbitron)

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Mobile browsers

## Credits

Created for Viv's Pokemon collection tracking.

Pokemon sprites and data are property of Nintendo/Game Freak/The Pokemon Company.
