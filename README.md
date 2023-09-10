# Not-Spotify
### A Spotify Clone to learn about TypeScript, Nextjs, Supabase and more!

Guided around a video made by [Code With Antonio](https://www.youtube.com/@codewithantonio)
Its going to be uploaded to Vercel later, for now im thinking of following up with stripe integration, but i doubt it.

Features:
- Song upload
- Stripe integration
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices
- Credential authentication with Supabase
- Github authentication integration
- File and image upload using Supabase storage
- Client form validation and handling using react-hook-form
- Server error handling with react-toast
- Play song audio
- Favorites system
- Playlists / Liked songs system
- Advanced Player component
- Stripe recurring payment integration
- How to write POST, GET, and DELETE routes in route handlers (app/api)
- How to fetch data in server React components by directly accessing the database
- Handling relations between Server and Child components in a real-time environment
- Cancelling Stripe subscriptions

You can run it with:
```shell
npm i
npm run dev
```

You can setup your .env with:
```js
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
SUPABASE_SERVICE_ROLE_KEY=

NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
```

