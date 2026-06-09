# Gym Starter Repository (Adi + Partner)

Single HTML page with:
- today's split day auto-calculated for IST
- warm-up list
- 5-day routine cards
- one primary + one backup YouTube for key exercises
- simple daily logging form
- log history + CSV export

## Open
- Permanent public link (works from anywhere):
  - `https://clawbot-adi.github.io/adi-gym-trainer-hub/`
- Local LAN fallback:
```bash
python3 -m http.server 8080 --directory /root/gym_trainer_hub
```
then open `http://localhost:8080`

## Daily logging flow (no login)
The page now asks the same quick flow for both of you:
- Did you do this today?
- What you did
- What you couldn't do
- Pain/stiffness score + notes

Use it 2 lines, save, and optionally press **Copy today's report** to paste directly in Telegram.

## Share with partner
- Send her the public link above and she can update logs from her phone/browser directly.
- Both of you can also log by texting this pattern in Telegram and I can also keep a copy for us: `Did you do today's session?` etc.

## Update plan
Edit `/root/gym_trainer_hub/index.html` to change exercises, timings, or video links.