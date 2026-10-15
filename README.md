# Zindua Hackathon Dashboard

> One place for every hackathon update, so the whole team works from the same information at the same time.

The Hackathon Dashboard is Zindua School's central hub for communication during hackathons. It gives participants, mentors, judges and organisers one shared place for announcements, schedules, deadlines and progress. Nobody has to dig through chat threads or wait for updates to be passed along by word of mouth.

---



## Why This Dashboard Exists

Hackathons move fast. When updates are scattered across WhatsApp groups, emails, Slack channels and verbal announcements, several things go wrong:

- **Information gets lost.** Teams miss deadline changes, room changes or rule clarifications.
- **Updates arrive late.** By the time news reaches everyone, it can be too late to act on it.
- **Access is uneven.** Some people end up in the loop and others don't, which is unfair to participants.
- **Nobody knows what's true.** Conflicting messages from different channels cause confusion.

The dashboard fixes this with a **single source of truth**. If it's official, it's on the dashboard.






#### Installation

```bash
git clone https://github.com/soniah13/hackathon_dashboard.git
cd hackathon_dashboard
npm install
```

#### Environment variables

Create a `.env` file in the project root:

```env
# Example; replace with the real keys
DATABASE_URL=
AUTH_SECRET=
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

Never commit `.env` files. Use `.env.example` to document the required keys.

#### Run locally

```bash
npm run dev
```

Then open `http://localhost:3000`.

### Build & deploy

```bash
npm run build
npm start
```



### Contributing

1. Create a branch from `main`: `git checkout -b feature/short-description`
2. Make your changes, keeping commits small and clear.
3. Open a Pull Request that describes **what** changed and **why**.
4. Get at least **one review** before merging.
5. Note any user-facing changes in the PR, so organisers can announce them.

**Branch naming:** `feature/…`, `fix/…`, `docs/…`



### Support & Contact

- **Organising team:** edu@zinduaschool.com
- **Report a bug:** open an issue in this repository
- **During the event:** use the **Help & Blockers** section of the dashboard


### License

*[Specify license, e.g. MIT, or "Proprietary – Zindua School"]*



<p align="center">Built with care by the Zindua School team 💙</p>
