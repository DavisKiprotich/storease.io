# Storease

Storease is an Expo React Native point-of-sale and inventory management app for small businesses. It combines product management, checkout, customer tracking, reporting, multilingual support, Supabase-backed data, and subscription gating.

## Features

- POS checkout flow with cart and payment handling
- Inventory and stock intake management
- Customer and supplier management
- Dashboard and reporting views
- Multi-store support
- Multi-language UI
- Supabase authentication and data storage
- RevenueCat subscription/paywall integration

## Tech Stack

- Expo
- React Native
- TypeScript
- React Navigation
- Supabase
- RevenueCat
- i18next

## Project Structure

```text
src/
  components/
  constants/
  contexts/
  i18n/
  lib/
  navigation/
  screens/
  services/
```

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Create a `.env` file with the required Expo public variables:

```env
EXPO_PUBLIC_SUPABASE_URL=
EXPO_PUBLIC_SUPABASE_ANON_KEY=
EXPO_PUBLIC_REVENUECAT_APPLE_KEY=
EXPO_PUBLIC_REVENUECAT_GOOGLE_KEY=
```

3. Start the Expo app:

```bash
npm start
```

## Useful Scripts

- `npm start`
- `npm run android`
- `npm run ios`
- `npm run web`

## Database

The repository includes Supabase schema and migration-style SQL files such as:

- `supabase_schema.sql`
- `phase1_migration.sql`
- `fix_rls_policies.sql`
- `secure_data_isolation.sql`

## Notes

- App configuration lives in `app.json`.
- Main entry point is `App.tsx`.
- Supabase client setup is in `src/lib/supabase.ts`.
