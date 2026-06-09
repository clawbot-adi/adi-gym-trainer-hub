# Gym Starter Repository (Adi + Partner)

Single HTML page with:
- today's split day auto-calculated for IST
- warm-up list
- 5-day routine cards
- primary + backup video links
- zero-friction daily logging flow
- log history + CSV export

## Open
- Permanent public link (works anywhere):
  - `https://clawbot-adi.github.io/adi-gym-trainer-hub/`
- Logging entry point:
  - `https://clawbot-adi.github.io/adi-gym-trainer-hub/#log`
- Local LAN fallback:
```bash
python3 -m http.server 8080 --directory /root/gym_trainer_hub
```
then open `http://localhost:8080`

## Daily logging flow (designed to be used)
Goal: **< 30 seconds**.

1. Open the shared link.
2. Pick name (Adi/Partner).
3. Tap **Did you train today?**
4. If Yes: tick completed moves (default on), add skipped/notes if any.
5. Set pain score + feel, Save.
6. Tap **Copy Telegram format** to paste directly.

## Share with partner
- Send this single link to her. She can open and log directly from her browser.
- There is no login required and no extra setup.

## Update plan
Edit `/root/gym_trainer_hub/index.html` to change exercises, timings, or video links.