# Design and architecture

DoneZone is designed around a simple promise: give every task a clear place without burying it under unnecessary controls. A white and cool slate canvas, restrained indigo accents, and Plus Jakarta Sans make the board feel calm and easy to scan. Dark mode carries the same hierarchy into a lower-light workspace.

Lovable provides the frontend development and publishing workflow. A private GitHub repository stores the complete React and TanStack Start implementation. Authentication and persistent storage use Supabase with user-level access controls. The public showcase is a separate documentation-only repository.

The rebuild retains the original app's complete board, list, card, label, and backup workflows. Its browser demo has no account requirement and does not write demo data to the backend. Automatic backups are checked while a board is open. The app is published on Lovable at [DoneZone](https://donezone-by-khiz.lovable.app).

No application source or deployment configuration is distributed in this public showcase.
