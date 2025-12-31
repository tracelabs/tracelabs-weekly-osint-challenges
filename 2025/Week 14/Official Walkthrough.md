Objective

Suspicious network traffic was observed during routine monitoring.
A screenshot from the same session may help identify the source.

One HTTP header appears out of place.

Goal:
Identify the real-world location associated with this traffic.

---

Tools Used

Google — contextual research

Google Images — reverse image analysis

Google Maps / Street View — visual and spatial verification

Base64 Decoder — encoded data analysis

---

Image: 

<img width="1136" height="838" alt="Screenshot 2025-12-16 151958" src="https://github.com/user-attachments/assets/f93aa62f-1614-4e4d-92a2-1ccf8cd531cc" />


Provided Artifacts
```HTTP Headers
HTTP/1.1 200 OK
Server: Apache/2.4.57 (Ubuntu)
Content-Type: text/html; charset=UTF-8
X-Powered-By: PHP/8.2.0
X-Clue: U2FuZHMgTGlmZXN0eWxlIENvdW50ZXIgKEhvdGVsIExvYmJ5KQ==
Cache-Control: no-cache
Connection: close
```

---

Step 1: Identify the Anomaly

Most of the HTTP headers are standard and unremarkable.
One header immediately stands out:

X-Clue

Why this matters:

Non-standard header

Contains encoded content

Clearly intentional

Custom headers with encoded values are rarely accidental.
This becomes the primary investigative entry point.

---

Step 2: Decode the X-Clue Header

The value of X-Clue appears to follow a Base64 encoding pattern:

U2FuZHMgTGlmZXN0eWxlIENvdW50ZXIgKEhvdGVsIExvYmJ5KQ==

<img width="1000" height="671" alt="Screenshot 2025-12-31 070024" src="https://github.com/user-attachments/assets/bc886ef3-312f-4e0c-80f2-4faeff392852" />

Decode the string using a Base64 decoder.

Decoded Result
“Sands Lifestyle Counter (Hotel Lobby)”


This is not random data—it is a semantic location clue.

Key indicators:

“Sands”

“Hotel Lobby”

At this point, we have a conceptual location, not coordinates.

---

Step 3: Reverse Image Search the Screenshot

<img width="1184" height="901" alt="Screenshot 2025-12-31 070546" src="https://github.com/user-attachments/assets/732ed9a9-5bad-4bc4-ab2a-792bf49bc9e2" />

Next, pivot to the screenshot associated with the traffic.

Upload the screenshot to Google Images.

Results consistently reference:

Marina Bay Sands

Singapore skyline

Interior hotel lobby imagery

Retail and concierge-style counters inside the Sands complex

This visual evidence aligns directly with the decoded header.

We now have two independent corroborating signals:

Encoded technical metadata

Visual confirmation from image analysis

This is strong OSINT validation.

---

Step 4: Ground-Truth Verification with Maps

Open Google Maps and search for:

Sands Lifestyle Counter Singapore

<img width="1391" height="748" alt="Screenshot 2025-12-31 071446" src="https://github.com/user-attachments/assets/e8a94154-1247-4926-99ac-a3a4b37ec9cd" />

Using Street View and indoor imagery:

<img width="1893" height="874" alt="Screenshot 2025-12-31 071635" src="https://github.com/user-attachments/assets/c636e562-13f2-4b8d-9083-b8164e2cd28c" />


Scan hotel lobby interiors

Compare counter layout, lighting, and materials

Match architectural features seen in the screenshot

Counter placement and lighting are strong identifiers

The interior visuals match the screenshot precisely.

---
Verification Tips:

<img width="1366" height="710" alt="Screenshot 2025-12-31 071527" src="https://github.com/user-attachments/assets/3c73cd9b-3019-4ec5-8585-c356e9a70e7a" />

Hovering Pegman over indoor-accessible areas often reveals interior previews

Hotel lobbies frequently have Street View coverage

---

Final Answer

Marina Bay Sands Hotel Lobby, Singapore
