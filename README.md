# GigPass Passport

Build a full-stack web application called GigPass.

GigPass is a worker-owned portable reputation passport for gig workers.

The core concept is:

A gig worker can connect multiple gig platforms, give consent to share their performance data, and generate a portable reputation credential containing verified performance metrics.

The credential should be cryptographically signed so that another platform can verify that the credential is authentic and has not been modified.

For this first version, use simulated gig platforms and synthetic data. Do NOT claim that the platforms are real integrations.

Tech requirements:

- React

- TypeScript

- Tailwind CSS

- Modern responsive web design

- Supabase-ready architecture

- Reusable components

- Clean component structure

Create these pages:

1. Landing page

2. Worker dashboard

3. Connect platform page

4. Reputation passport page

5. Credential verification page

Design style:

- futuristic but professional

- dark background

- purple/cyan accents

- clean dashboard

- subtle animations

- excellent desktop layout

- responsive mobile layout

Landing page headline:

"Your reputation. Your passport."

Subtitle:

"Build a portable, verifiable professional reputation across gig platforms."

Main buttons:

- Create Your Passport

- Verify a Passport

Worker dashboard should display:

- overall rating

- total jobs completed

- completion rate

- number of connected platforms

- connected platform cards

- recent reputation activity

Use fictional platforms:

- QuickRide

- TaskGo

- FlexiFleet

Create realistic synthetic demo data.

Important:

Do not implement blockchain.

Do not use AI for cryptographic verification.

Do not create fake real-world API integrations.

Keep the code modular so real APIs can be connected later.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/d7145cdd-f5d3-471d-ae5e-3eb45ffb968a).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
