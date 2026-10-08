# Lucky 777 Cartoon Slots — Source Code

A responsive HTML5-style slot game built with Next.js and React. This package uses virtual coins only and contains no payment, deposit, withdrawal, account, or real-money system.

## Included

- 5 reels × 3 rows
- 10 or 20 selectable paylines
- Vertical reel animation with staggered stops
- Spin and Auto Spin
- Virtual coins, bet selection, and local browser saving
- Animated winning lines, confetti, and jackpot effects
- Original cartoon symbol artwork
- Original synthesized background music and sound effects
- Responsive desktop and mobile layout
- Paytable and fullscreen mode

## Run locally

1. Install Node.js 20 or newer.
2. Open a terminal in this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open `http://localhost:3000`.

For a production build, run `npm run build`, followed by `npm run start`.

## Quick reskin

Replace the six PNG files inside `public/symbols/` while keeping the same filenames:

- `seven.png`
- `bar.png`
- `bell.png`
- `diamond.png`
- `cherry.png`
- `lemon.png`

The main game settings are near the top of `app/page.tsx`:

- `DATA`: symbol names, image paths, and payouts
- `START`: opening symbol layout
- `LINES`: the 20 payline patterns
- `COLORS`: animated payline colors
- Starting coins, default bet, reel duration, and music notes can also be edited in this file.

Visual styling and animation settings are in `app/globals.css`.

## Support boundary

The included source is supplied as shown. Custom reskins, extra paylines, advertisements, leaderboards, daily bonuses, mobile packaging, backend accounts, and deployment are separate services.

## License

See `LICENSE.txt`. The artwork and code may be used in one end product per purchased license. The source package itself may not be redistributed or resold.
