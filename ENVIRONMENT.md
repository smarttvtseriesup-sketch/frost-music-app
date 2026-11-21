# Environment Variables

The demo build requires no environment variables.

For production, place provider credentials in a backend environment such as Supabase Edge Functions or Firebase Functions. The mobile app should call a backend endpoint, never embed provider secrets.

Recommended variables:

- `MUSIC_API_BASE_URL`
- `LICENSED_PROVIDER_TOKEN` (backend-only)
- `LYRICS_API_TOKEN` (backend-only)
