# SnapClone

A complete Snapchat clone built with Flutter, Next.js, and Supabase.

## Features

- **Authentication**: Supabase Auth (Email/Password)
- **Camera**: Take photos and videos with filters
- **Stories**: 24-hour ephemeral stories with progress indicators
- **Chat**: Real-time messaging and ephemeral snaps
- **Snap Map**: Real-time location sharing with friends
- **Discover**: Public feed of posts

## Tech Stack

- **Mobile**: Flutter (iOS + Android)
- **Web**: Next.js 14 (App Router, Tailwind CSS)
- **Backend**: Supabase (PostgreSQL, Realtime, Storage, Auth)

## Prerequisites

- Node.js 18+
- Flutter SDK 3.19+
- Supabase CLI
- Docker (for local Supabase)

## Setup

1. Start Supabase locally:
   ```bash
   cd supabase
   supabase start
   ```

2. Setup Web:
   ```bash
   cd web
   npm install
   cp .env.local.example .env.local
   # Update env vars
   npm run dev
   ```

3. Setup Mobile:
   ```bash
   cd mobile
   flutter pub get
   flutter run --dart-define=SUPABASE_URL=YOUR_URL --dart-define=SUPABASE_ANON_KEY=YOUR_KEY
   ```
Just a personal project inspired  by Snapchat.

You can download the files from the "snapclone.zip" file in the uploaded files.
