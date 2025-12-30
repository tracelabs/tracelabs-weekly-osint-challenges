Objective

Given a single image of a vessel at sea, identify:

Vessel name

Flag state

Last reported port

---

Tools Used

Google Reverse Image Search — initial discovery and pivoting

VesselFinder — authoritative vessel data and imagery

---

Image:

![1](https://github.com/user-attachments/assets/4a07b78b-df42-460c-9db8-3e86baa6c7cb)

---

Step 1: Reverse Image Search

Upload the vessel image to images.google.com.

<img width="1384" height="916" alt="Screenshot 2025-12-30 055339" src="https://github.com/user-attachments/assets/47bd8c13-9bda-4278-afd0-0549642c7713" />

Initial results include:

AI-generated summaries

News articles

Visual matches

A promising result from VesselFinder

***OSINT Reminder:
AI summaries are not evidence. They are entry points that must be independently verified.***

The VesselFinder result provides structured maritime data and is the most reliable pivot.

---

Step 2: Pivot to VesselFinder

Open the VesselFinder result to review:

<img width="984" height="688" alt="Screenshot 2025-12-30 055518" src="https://github.com/user-attachments/assets/2a971ed6-e086-4e02-8d7b-7758e35434ba" />

<img width="979" height="732" alt="Screenshot 2025-12-30 055552" src="https://github.com/user-attachments/assets/297899ea-7a0b-4485-9d38-94b92988d27a" />

Vessel profile

Historical tracking data

Image galleries

Port call history

At first glance, the information appears consistent—until closer inspection of the vessel name introduces a critical risk.

---

Step 3: Identify the Deception (Name Confusion)

Examining the image closely, the side of the vessel appears to read:

![1-1-1](https://github.com/user-attachments/assets/715a12ec-f95d-4e11-ab27-c02b7c52622b)


“Ever Gifted”

This is a serious red flag.

Why This Matters

Ever Gifted and Ever Given are different ships.

Confusing the two can lead to:

False attribution

Incorrect reporting

Compromised OSINT conclusions

This is a classic maritime OSINT trap: similar vessel names + reused imagery.

---

Step 4: Visual Verification (Stern Over Hull)

<img width="1135" height="868" alt="Screenshot 2025-12-30 055758" src="https://github.com/user-attachments/assets/ef8bebec-d9f4-42fe-aa13-cd1ef2040039" />

In maritime identification, the stern (rear of the vessel) is the most reliable location for confirming a ship’s name.

Within VesselFinder’s image gallery:

Multiple images are available

Hull-side markings vary or are partially obscured

The stern clearly displays the vessel name

Result:
The stern unmistakably shows EVER GIVEN — not Ever Gifted.

<img width="1195" height="713" alt="Screenshot 2025-12-30 055846" src="https://github.com/user-attachments/assets/7813113b-5a2d-434a-aab8-a63016a17c45" />

This confirms the vessel’s true identity.

---

Why a Comparison Is Necessary

This vessel:

<img width="1147" height="836" alt="Screenshot 2025-12-30 055944" src="https://github.com/user-attachments/assets/a14ed752-0e7f-498c-8bf1-ac5fab710c62" />


Have similar naming conventions

<img width="1150" height="851" alt="Screenshot 2025-12-30 060042" src="https://github.com/user-attachments/assets/4d56d4c7-830b-449d-adcc-31a9487858e9" />


Belong to the same shipping line

Are sometimes mislabeled or reused in image search results

Without stern verification, misidentification is very easy.

---

Step 5: Confirm Vessel Details

With the vessel identity verified, confirm remaining attributes directly in VesselFinder (not via secondary articles).

Verified information:

<img width="984" height="688" alt="Screenshot-2025-12-30-055518-1" src="https://github.com/user-attachments/assets/e434f525-1760-4189-b323-fb1240a92d03" />


Vessel Name: Ever Given

Flag State: Panama

Last Reported Port: Port of Singapore

All data points align across:

Tracking records

Port history

Verified imagery

---

Final Answer: Ever Given, Panama, Singapore
