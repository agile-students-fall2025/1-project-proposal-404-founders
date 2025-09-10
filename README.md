# NutriSmart: Meal & Nutrition Planner

## Team Members
- [Ahmmed Razee](https://github.com/ErazeerHead04)  
- [Amy Liao](https://github.com/Amyliao0)  
- [Sejona Sujit Das](https://github.com/sejonasdas)  
- [Amal Faisal](https://github.com/amal-faisal)  
- [Sihyun Kim](https://github.com/sihyunlkim)  


## What and Why?
We propose a mobile web application that creates personalized meal plans for health-conscious users and patients with specific dietary needs (such as cancer, diabetes, or kidney disease). The system adapts to individual goals, weight loss, recovery, or balanced nutrition, and helps reduce food waste by planning meals around ingredients already available at home.

This is important because many people struggle to manage diet, health conditions, and grocery budgets at the same time. Patients often require symptom-friendly foods, fitness-minded users want to track macros, and busy families or students need quick, affordable meals. Current solutions are fragmented, and none provide a simple, accessible way to meet all these needs in one place.

## For Whom?
- Patients with chronic illness who need symptom-friendly dietary suggestions.  
- Health-conscious individuals managing fitness, recovery, or weight goals.  
- Busy families and students looking for affordable, healthy, low-waste meal plans.  

## How?
From an end-user perspective, NutriSmart will provide the following core functionality:

### User Profiles
- Register/login to account.  
- Set dietary goals (weight loss, balanced nutrition, recovery, etc.).  
- Add allergies, dietary restrictions, and health conditions.  

### Nutrition & Meal Data
- Pull nutrition information from USDA FoodData Central.  
- Access recipes from TheMealDB and combine with USDA data to calculate calories and macros.  

### Pantry & Barcode Scanning
- Add and manage pantry items.  
- Scan barcodes with the phone camera (using ZXing/Quagga).  
- Fetch product details from Open Food Facts to populate the pantry automatically.  

### Meal Planning
- Generate personalized 7-day meal plans based on dietary goals.  
- Prioritize pantry ingredients first to minimize food waste.  
- Adjust meals according to user restrictions and preferences.  

### Symptom-Based Suggestions
- Log symptoms such as nausea, fatigue, or loss of appetite.  
- Receive rule-based food recommendations with clear disclaimers (educational, not medical advice).  

### Exports & Sharing
- Export meal plans and logs as PDF/CSV.  
- Share with dietitians, doctors, or caregivers for external guidance.  

 

### Additional features (stretch goals):
- **Receipt OCR:** Use Tesseract.js to add pantry items directly from receipts.  
- **Chatbot:** Provide simple Q&A through a rule-based system, with the option to later upgrade to a free chatbot framework.  
- **Caregiver/Shared accounts:** Let caregivers or family members view meal plans.  

*(Note: The APIs listed above are some suggested free options; the team may explore alternatives as needed.)*

## Scope
We believe this project is appropriately scoped for a semester-long effort by a team of 4-6 developers.  

- **Phase 1** focuses on the core: ingredient tracking, meal planning, and nutrition database integration. These features are substantial but achievable within the timeframe.  
- **Phase 2** introduces stretch goals such as symptom-aware suggestions and healthcare provider integration if time permits.  

The technical work, API integration, database management, and mobile-responsive design, seems moderately complex but manageable, without requiring advanced AI or full medical system integration.  

In our view, the project balances feasibility with innovation by leveraging established nutrition APIs while adding a novel symptom-awareness layer that differentiates it from existing apps.  
