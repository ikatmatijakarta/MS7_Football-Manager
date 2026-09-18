# MS7 Football Manager Mini Online — PRESEASON ACCESS V1

Based on PURE FINAL V3.

## New production flow

Register → Admin approval → Create Club → **Preseason Lobby** → Founding Draw → Full Gameplay.

Managers no longer get stuck outside the app while the founding quota is still incomplete.

## Available before Founding Draw
- Home / Preseason Lobby
- Squad status (0/22; no fake players)
- Club identity
- Inbox / server notifications

## Locked before Founding Draw
- Tactics
- Training
- Transfers
- League
- Match Centre
- Season gameplay

The minimum founding target is NOT bypassed. No squad is allocated early.
When the server changes `founding_draw_status` to `COMPLETED`, Refresh World Status switches the manager into the normal production game and loads the real squad.

## Safety
- No MockDB
- No dummy managers
- No dummy players
- Supabase production stays the source of truth
- PWA/mobile support retained
