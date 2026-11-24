# Ploto Brand & Loader Assets

Minimal monochrome brand assets and animated loading icon for **Ploto** (background multi-threaded AutoCAD / CAD LT batch plotter).

## Files (`brand/`)

| File | Purpose |
| --- | --- |
| `brand/ploto-logo.svg` | Static monochrome black vector logo (`64×64`, Roll Spiral mark) |
| `brand/ploto-app-icon.svg` | App icon — white circle with optically centered black Ploto mark |
| `brand/ploto-loader.svg` | Standalone animated loading SVG (no JS required; works directly in `<img>`) |
| `brand/ploto-brand-component.html` | Interactive HTML/JS reference component toggling between static logo and 60/120fps clockwise rolling loader |

## Quick Usage

### 1. Zero-JS Loading Icon
```html
<img src="./brand/ploto-loader.svg" alt="Loading..." width="48" height="48" />
```

### 2. Static Logo / App Icon
```html
<img src="./brand/ploto-logo.svg" alt="Ploto" width="32" height="32" />
<img src="./brand/ploto-app-icon.svg" alt="Ploto App" width="48" height="48" />
```
