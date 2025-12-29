**Objective**

Identify the zoo where the provided webcam image was taken.

**Tools Used**

Google Images — reverse image searching

Google Search — official webcam verification

Google Maps / Street View — terrain and environment validation

**Image:**

<img width="386" height="221" alt="Screenshot 2025-12-24 143210" src="https://github.com/user-attachments/assets/f6d98803-00bc-470d-a933-0164ac6a8f96" />


**Initial Assessment**

At first glance, the image provides very limited direct indicators:

No visible signage

No identifiable buildings

Only animals, terrain, fencing, and vegetation

This type of image presents a common OSINT risk: jumping to conclusions based on surface-level cues.

**Step 1: Reverse Image Search**


Upload the image to images.google.com.

Key Observation

The top results are heavily influenced by AI-generated descriptions, repeatedly identifying the animal as an Indian Rhinoceros.

This introduces an important OSINT caution:

Animal identification does not equal location identification

Many zoos house the same species

Species alone is insufficient evidence

At this stage, no reliable location data has been confirmed.

**Step 2: Ignore the Animal, Analyze the Environment**

<img width="1522" height="856" alt="Screenshot 2025-12-24 143536" src="https://github.com/user-attachments/assets/93772555-434f-4f41-933c-60e60c5e5735" />


Rather than focusing on the rhinoceros, shift attention to environmental features:

<img width="1175" height="666" alt="Screenshot 2025-12-24 143817" src="https://github.com/user-attachments/assets/8a155137-f99c-434e-a5df-3ba6f95f0d7e" />


Rolling hills and elevation changes

Vegetation type (trees, shrubs, density)

Enclosure layout and fencing style

Background terrain silhouettes

Scrolling further through image results reveals repeated references to:

<img width="1040" height="691" alt="Screenshot 2025-12-24 143855" src="https://github.com/user-attachments/assets/abced663-cfd1-4c18-98b6-df3fd792ab5b" />


San Diego Zoo

This is the first location-based lead derived from environmental context rather than object recognition.

**Step 3: Pivot to Official Zoo Webcams**

To validate the hypothesis, search directly for official zoo webcams.

Reviewing the San Diego Zoo website reveals:

<img width="1441" height="878" alt="Screenshot 2025-12-25 081830" src="https://github.com/user-attachments/assets/8de47684-a21f-4473-aa1c-aec80656b453" />



No direct rhinoceros-specific webcam

References to older enclosure areas (e.g., “Urban Jungle”)

However, terrain and enclosure details from these pages do not fully match the challenge image, suggesting the need to pivot further.

**Step 4: Unexpected Pivot — Giraffe Webcam**

<img width="1044" height="897" alt="Screenshot 2025-12-25 085009" src="https://github.com/user-attachments/assets/97bccedb-b34a-48d7-94ff-92850d6a6b49" />

While reviewing available webcams, the giraffe cam becomes a critical breakthrough.

<img width="1351" height="895" alt="Screenshot 2025-12-25 085128" src="https://github.com/user-attachments/assets/c39ee281-9f9b-4500-ab41-21d6584edfe7" />


Key observations:

Identical rolling hills in the background

Matching vegetation density and shrub placement

Similar fencing style and enclosure orientation

The same rhinoceroses visible within the broader enclosure area

This confirms that the rhinoceros habitat is part of a larger shared terrain rather than an isolated exhibit.

**Step 5: Terrain Verification with Google Maps**

To ensure high confidence, pivot to Google Maps.

Using satellite imagery and nearby viewpoints:

<img width="1173" height="609" alt="Screenshot 2025-12-25 082316" src="https://github.com/user-attachments/assets/59caf1e8-63ba-4896-a097-32866cdf7fa6" />


Hill silhouettes match the webcam background

Enclosure orientation aligns with satellite view

Tree placement and spacing are consistent

Using Street View, additional terrain confirmation is achieved:

<img width="1814" height="771" alt="Screenshot 2025-12-25 085652" src="https://github.com/user-attachments/assets/f11dde3c-c9d4-4ea9-9687-71cc656dea01" />


Similar hilltops

Matching vegetation patterns

Consistent environmental layout

At this point, the location can be confidently verified.

**Final Answer: San Diego Zoo, California, United States**
