# Ddostesstinggg
Advanced browser-based network stress testing tool.

## Features
- Pure browser-based DDoS (no botnet)
- Multiple attack methods
- Real-time statistics
- No installation required
- Cross-platform compatible

## Deployment

### GitHub Pages (Free):
1. Create new repository
2. Upload `index.html`
3. Go to Settings → Pages
4. Select main branch → Save
5. Access via `https://[username].github.io/[repo]`

### Vercel (Recommended):
1. Drag & drop `index.html` to vercel.com
2. Automatic deployment
3. Custom domain available

### Netlify:
1. Drag `index.html` to netlify.com
2. Instant deployment
3. HTTPS by default

## Usage
1. Open deployed website
2. Enter target URL
3. Click "START ATTACK"
4. Monitor statistics

## Attack Methods
- **HTTP Flood**: Rapid GET requests
- **Slowloris**: Partial requests keeping connections open
- **WebSocket Flood**: Persistent connections

## Technical Details
- Uses Service Workers for parallel processing
- Implements Fetch API with no-cors mode
- WebSocket connections for slow attacks
- Local storage for statistics

## Legal activity
- for legal activity and educational purpose only 
