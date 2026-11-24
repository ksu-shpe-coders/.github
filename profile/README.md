SHPE Coders @ KSU

The software team of the Society of Hispanic Professional Engineers (SHPE) chapter at Kennesaw State University. We build apps for our chapter and learn real-world engineering by shipping them.

What we're building
📱 shpe-mobile

The SHPE KSU member app, built with React Native, Expo, and TypeScript. Members sign up with their KSU email and can:

browse events and RSVP
read chapter announcements and the member spotlight
find other members in the member directory
track their points on a monthly leaderboard
manage their profile and account, and report issues to officers

Officers also have a pilot chat room for the e-board.

⚙️ shpe-api

The backend for the app: an ASP.NET Core (.NET 10) API with 33 REST endpoints, PostgreSQL, and Entity Framework Core. It runs on Render, deploys automatically on every merge to main, and sends email through Brevo.

🌐 shpe-web (planned)

A web dashboard where officers will post events and announcements and manage points. Not started yet.

Both app repositories are private for now. Members get access when they join the team.

Status (November 2026)
The API and database are live on Render, currently with test accounts only.
The first Android test build is done. Store releases are waiting on the chapter's Apple and Google developer accounts.
Decided but not built yet: QR check-in for events and a photo gallery.
Tech stack
Backend: ASP.NET Core (.NET 10), PostgreSQL, Entity Framework Core
Mobile: React Native, Expo, TypeScript
Hosting and delivery: Render, Docker, GitHub Actions, EAS Build
Email: Brevo
How we work

Members work in small feature teams. Every change goes through a pull request that CI checks, and contributors walk the team through their code before it's approved. We use AI coding agents, and each repo's AGENTS.md sets the rules they follow.

Want to contribute?

No prior experience required, just enthusiasm to learn. Reach out to the current software chair:

Jorge "Coki" Arriaga jarriag1@students.kennesaw.edu
