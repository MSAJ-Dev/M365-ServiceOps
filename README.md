# M365 ServiceOps

Triage a simulated Microsoft 365 incident and see how priority affects response and resolution targets.

## Try the browser demo

Download [demo.html](demo.html) and open it locally. The thresholds mirror the project’s SLA policy. The walkthrough uses simulated data and does not contact Microsoft Graph.

## Run the full application

Download [M365-ServiceOps-source.zip](M365-ServiceOps-source.zip). Extract the source package, copy `.env.example` to `.env`, then run `docker compose up --build` and open `http://localhost:3000`. The app uses a simulated Microsoft Graph adapter. The archive includes the original project documentation and the new demo.
