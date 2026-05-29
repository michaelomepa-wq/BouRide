# BouRide Project Structure Plan

This document outlines the planned code structure for BouRide.
We will build these files one by one.

## 1. Core for AROB
- `docs/ussd-flow.md` - USSD menus for *777# on Digicel/Bmobile
- `docs/driver-survey.md` - Questions for PMV drivers in Arawa/Buka

## 2. Future Backend (Node.js)
- `config/` - database.js, maps.js
- `controllers/` - rideController.js, driverController.js

## 3. Future Frontend
- `passenger-app/` - For booking rides
- `driver-app/` - For PMV owners

## Immediate Next Step
Create `docs/ussd-flow.md` because 80% of Bougainville uses 2G phones.
Backend code comes AFTER we talk to drivers + ABG.
