# RepairHub — Interactive Customer Journey

An interactive, scene-by-scene customer journey for the RepairHub smartphone repair concept.
Built for the Operations Management Capstone Project at Católica Lisbon (2025/2026).

## 🎮 Live Experience

→ Deploy via Vercel to get your live URL

## 📖 What it covers

9 interactive scenes walking through the full customer journey:
1. Broken phone
2. Arriving at the store (Arrival Queue buffer)
3. Counter registration (Camera + Tablet)
4. AI Diagnosis + Inventory Check (ROP + VUT queueing)
5. Quote presented → **single customer decision point**
6. Repair in progress (Technician + QC)
7. Pickup — Satisfied Demand
8. Alt path: Scheduled Repair (replenishment triggered on confirmation)
9. Alt path: Customer declines (lost demand)

## 🖼️ Adding Gemini scene images

Place your generated images in the `/images` folder:
- `images/scene1.jpg` through `images/scene9.jpg`

The app automatically uses them as backgrounds. Falls back to gradients if images are not present.

## 🚀 Deploy on Vercel

1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this repo: `mrtn25/repairhub-customer-journey`
3. Framework Preset: **Other**
4. Click Deploy

## 📐 OM Concepts covered

- Arrival Queue (Buffer)
- Activity (Counter, Technician, QC)
- AI Diagnosis + Inventory Check (ROP)
- VUT Queueing Model (W_q calculation)
- Single Decision Point (customer approval)
- Scheduled Repair path
- Pickup Buffer → Satisfied Demand
