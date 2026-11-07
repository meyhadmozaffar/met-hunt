# Met Scavenger Hunt

Team scavenger hunts at The Met. Players sign in with Google or an email link,
join a team, and their profile keeps every hunt they've played.

- `public/index.html`: the app (served by Firebase Hosting)
- `firestore.rules`: database security rules
- `.github/workflows/deploy.yml`: deploys both on every push to `main`

The web API key is not stored in this repository. The deploy workflow adds it
from the `FIREBASE_WEB_API_KEY` secret.
