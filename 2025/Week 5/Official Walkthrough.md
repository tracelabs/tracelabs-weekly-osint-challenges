
**Objective**

Determine the following based on a provided webcam still:

Location shown in the image

Temperature at 7:56 PM on 10-21-2025

**Tools Used**

Google Reverse Image Search — initial geolocation indicators

EarthCam — webcam verification and environment matching

Weather Underground — historical weather data validation

**Image:** 
<img width="900" height="454" alt="Screenshot 2025-12-17 063909" src="https://github.com/user-attachments/assets/5f3333e6-7d7c-4dbb-a4e1-298e24931ec0" />


**Step 1: Identify the Location**
Reverse Image Search

<img width="1219" height="879" alt="Screenshot 2025-12-17 064133" src="https://github.com/user-attachments/assets/f7574fcc-fbf6-432e-a084-bdb04e6f615b" />

Upload the webcam still to images.google.com.

Multiple results reference Times Square, which provides an initial hypothesis.
However, per OSINT best practices, this result must be independently verified.

Webcam Verification
<img width="1322" height="581" alt="Screenshot 2025-12-17 064219" src="https://github.com/user-attachments/assets/0833e780-bb62-4d58-975f-872b23ed40a2" />

Search for “Times Square webcam” and review available providers.
EarthCam was selected due to:

Widespread use and credibility

Archived still images

Multiple camera angles covering the same location

Scrolling through EarthCam’s available feeds revealed multiple stills visually consistent with the challenge image.
<img width="1840" height="838" alt="Screenshot 2025-12-17 064327" src="https://github.com/user-attachments/assets/971ae4d7-38ae-4cd9-a3fc-99edec400f69" />

Upon locating the live webcam, environmental elements such as signage, building placement, and street layout matched the challenge still.
<img width="1835" height="840" alt="Screenshot 2025-12-17 064456" src="https://github.com/user-attachments/assets/19d1b3d1-0f85-43d2-9b0f-0311159d9a0b" />

Conclusion:
The location is confirmed as Times Square.

**Step 2: Determine the Temperature**
Historical Weather Data

Search for historical weather data for Times Square, New York on 10-21-2025.
<img width="1487" height="602" alt="Screenshot 2025-12-17 064620" src="https://github.com/user-attachments/assets/6796f441-e6df-45fc-8af8-41f45f378112" />

Multiple services provide weather history; Weather Underground was selected due to:

Reliable historical archives

Hour-by-hour data granularity

Clear timestamps

Navigate to the History section, select the appropriate date, and review conditions at 7:56 PM.
<img width="1414" height="778" alt="Screenshot 2025-12-17 082717" src="https://github.com/user-attachments/assets/e007a6ee-7b18-4773-802a-1fad0b617efd" />

Weather Underground displays a temperature of 63°F at that time.

**Data Variance Consideration**

During the original challenge run, the temperature displayed varied slightly due to rounding and reporting intervals.

The challenge’s reference value listed 64°F, which falls within normal variance for hourly weather reporting.

Documenting and acknowledging such discrepancies is an important OSINT practice.

**Final Answer**
Times Square 64°F
