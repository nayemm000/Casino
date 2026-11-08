# ELITE CLUB — Social Games Starter

A responsive React/Vite starter for a virtual-coin social games experience.

## Run locally
1. Install Node.js 20 or newer.
2. Extract this folder.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite.

## Build
`npm run build`

## Important limitations
This is a front-end starter/demo. Game outcomes are illustrative client-side demo logic; balances are stored in this browser's localStorage. The Admin Preview is not a secured admin system. Do not use it for real users or real value.

Before inviting users, implement Firebase Authentication, Firestore, Cloud Functions, server-authoritative game logic, custom admin claims, Firestore Security Rules, and immutable audit logs. Keep all coins strictly virtual with no cash value. No payment or cash withdrawal functions are included.

## Firebase
The provided Firebase config can be added in a future `src/services/firebase.ts` module using environment variables. Do not put service-account credentials in frontend code. Enable Firebase Authentication providers and create Firestore. Deploy and test restrictive security rules and Cloud Functions before production.
