# Roadmap

What has shipped, what is being built and what comes next — the features a player sees and the fixes that matter.
Plans can change; the order and the content of a release may move.

## Shipped

- **0.4.2 — A correctness and security pass over every service.** Nothing answers without a sign-in unless it is meant
  to; someone else's game, chat, invitation or profile answers "not found", so a stranger learns nothing about it; a
  request's size is bounded; a game refuses a move its rules do not know; a board or a profile is never shown out of
  date.
- **0.4.1 — The platform as a release.** The whole platform starts with one command from its released images, each
  pinned; every release is played through end to end — players registering, chatting and playing — before it ships.
- **0.4.0 — The foundation.** Registration with email confirmation and sign-in on the platform's own pages, protected
  against password guessing; one error format the apps can translate; lists that page through any amount of data;
  avatars; bans and account deactivation; the owner appoints the admins.
- **0.3.0 — Server-authoritative games.** Tic-tac-toe, battleship and reversi: the server owns every rule, each player
  sees the board through their own eyes, every move is pushed to the players in real time.

## Now — 0.4.3

- **Player names:** a unique @nickname, and an optional display name in any language.
- **A ban takes effect at once:** the player's sessions and live connections end the moment it is issued, and the player
  is told.

## Next

- **0.4.4 — Account security:** signing out really signs out; change or reset a forgotten password; change the email
  address; passkeys for every account; the admin panel only by passkey.
- **0.4.5 — A complete description of the API** the apps are built on, every response typed.
- **0.4.6 — The player app, first slice:** sign up, sign in and chat one on one in the browser.
- **0.5.0 — Games and statuses:** a catalog of games with their options; looking back through a game move by move;
  online, busy and invisible; playing from several devices at once.
- **0.6.0 — Chats:** group chats, a feed of your chats with unread counts, message search, messages encrypted at rest,
  blocking a player, browser notifications for your turn and new messages.
- **0.7.0 — Lobbies:** a game opens as a lobby in a chat — players join, the host starts; looking for a game; a time
  limit per turn.
- **0.8.0 — The admin panel:** players, chats and games in one place, moderation within set bounds, calling an admin
  from a chat, a journal of every admin action.
- **0.9.0 — Reports:** dashboards of how the platform is used.
- **0.10.0 — Progression:** statistics, levels and achievements.
