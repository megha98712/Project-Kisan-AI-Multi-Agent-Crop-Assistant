🌾 Project Kisan – AI-Powered Crop Assistance System

Smart Guidance • Farmer Journal • Gov Scheme Info • Expert Recommendation

📌 Overview

Project Kisan is an AI-powered agricultural support system designed to help farmers with real-time crop guidance, expert recommendations, government scheme info, and daily farm logging. This notebook integrates multiple AI agents to deliver fast, safe, and beginner-friendly crop support—without making medical-grade decisions or pesticide dosage recommendations.

🚀 Key Features 1️⃣ Crop Issue Analysis (Safe, Non-Diagnostic)

Uses CropDiagnosisAgent + CropCareAgent to provide:

✔ General reason for crop stress

✔ Risk level (Low / Medium / High)

✔ Red-flag symptoms

✔ Safe first-aid crop steps

❌ No harmful suggestions, no chemicals

2️⃣ Daily Farm Log System

Your DailyFarmLogAgent can store and retrieve:

Date & time

Crop name

Symptoms observed

Field condition

Watering details

Notes from the farmer

All logs can be fetched using:

memory_bank.get_logs()

3️⃣ Smart Crop Care Guidance

Delivered by CropCareAgent:

Irrigation schedule

Sunlight requirements

Soil moisture guidance

Organic, natural remedies

What to avoid (overwatering, excess fertilizer)

4️⃣ Agriculture Expert Recommendation

Provided by FarmExpertAgent, suggesting the right expert:

Soil Expert

Irrigation Specialist

Plant Pathologist

Pest Management Officer

KVK Officer

Agriculture Extension Officer

5️⃣ Government Schemes & Farmer FAQs

Handled by KrishiFAQAgent:

PM-Kisan

PMFBY Crop Insurance

Soil Health Card

Fertilizer Subsidies

Organic Farming Info

Crops & Varieties (Simple Wikipedia summary)

6️⃣ Parallel AI Processing (Fast Output)

Function:

parallel_crop_analysis()

Returns:

Crop Care Guidance

Expert Recommendation At the same time (async parallel tasks)

7️⃣ General Crop Information

Auto-fetched Wikipedia summary:

What the crop is

Where it grows

Common uses

Simple background

8️⃣ Farmer Memory / Journal

Your MemoryBank keeps:

All past issues

Logs

Patterns

Crop history

Field health timeline

Used for improved guidance over time.

9️⃣ Final Orchestrator Output

When you run:

output = await orch.run(crop_name, issue)


Output Key Meaning crop_care_guidance Full AI crop care steps recommended_agriculture_expert Best expert to meet general_crop_information Clean summary of crop farmer_journal Saved logs / memory

🧪 Example Output Format 🌾 Crop Care Summary: Your plant may be experiencing mild water stress. Ensure proper soil moisture.

👨‍🌾 Recommended Agriculture Expert: Plant Pathologist

📘 General Crop Information: Tomato is a widely grown vegetable crop known for its nutritional value…

📝 Farmer Journal:

2025-11-25: Tomato field had yellow leaves and low soil moisture.

**** Conclusion****

Project Kisan is a complete AI-powered agriculture help system with:

Multi-agent intelligence

Safe guidance 

Government scheme awareness

Farmer history tracking

Expert recommendation

Rapid parallel analysis
