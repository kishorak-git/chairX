# ChairIQ

Seat-pressure posture monitoring: dashboard simulation (sensor hardware not yet built)

ChairIQ is an HTML/CSS/JavaScript dashboard that demonstrates seat-pressure and posture monitoring with simulated input.

## Live demo

https://chairx-mu.vercel.app/

## Screenshot

> Screenshot placeholder: add a real ChairIQ dashboard screenshot here.

## What the simulation does

- Displays four simulated seat-pressure zones: front, back, left, and right.
- Calculates a posture score from the four zone values.
- Tracks simulated sitting time.
- Shows alerts for poor posture and extended sitting time.
- Supports simulated postures including good posture, hunch, lean left, lean right, slouch, and stand up.
- Displays the current posture, score history, sitting statistics, and a simulation log.

## Planned

- ESP32-based hardware input
- Physical pressure sensors
- WebSocket data transfer

The planned hardware and WebSocket integration are not implemented in this repository.

## How to run locally

This project is a static HTML application.

```powershell
git clone https://github.com/kishorak-git/chairX.git
cd chairX
python -m http.server 8000
```

Open `http://localhost:8000/intex.html` in a browser.
