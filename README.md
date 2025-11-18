# MindfulTask  
A seamless blend of **productivity** and **well-being**, designed for busy individuals who want to manage tasks while staying mindful of their health — without switching between multiple apps.

---

## 📌 Introduction

In today’s fast-paced world, many people prioritize work, deadlines, and daily commitments, often forgetting their own well-being. **MindfulTask** was created for individuals who stay busy and rarely check their health stats — yet still value balance.

This app is not just another productivity tool; it's a **mindful digital companion** that supports task management while monitoring **step count and activity patterns** through Apple Health.

With its **Wellness Insights** feature, MindfulTask analyzes daily movements and offers personalized task recommendations aligned with your energy level — helping users stay productive **and** healthy.

---

## 🎯 Target Audience

MindfulTask is ideal for:
- Students & professionals constantly on the move  
- Remote workers  
- Anyone who wants to stay productive while maintaining wellness  
- Users who don’t want to open multiple apps to track health and tasks  

---

## 🧩 User Experience Flow

1. **Onboarding** – Requests HealthKit & notification permissions  
2. **Home Screen** – Shows daily step count & proactive suggestion  
3. **Proactive Suggester** – Suggests tasks based on energy & step data  
4. **Task Manager** – Add, complete, and delete tasks  
5. **Smart Notifications** – Sends reminders based on activity levels  

---

## 🛠 Technical Summary

MindfulTask was developed using **SwiftUI** and the **MVVM architecture**.

### Core Components
- **Models:** Task properties (title, energyLevel, dueDate, etc.)
- **ViewModels:** Logic, data persistence, HealthKit queries
- **Managers:** JSON persistence & notification management  

### Development Highlights
- `NavigationStack` for seamless flow  
- `PersistenceManager` using JSON  
- `HealthKitViewModel` to connect with Apple Health  
- `SuggestedTaskView` custom animated UI component  

---

## 🚧 Development Challenges & Fixes

| Issue | Fix |
|-------|-----|
| HealthKit permission crash | Added correct Info.plist privacy keys |
| Entitlement issue | Enabled HealthKit capability |
| Data decoding error | Cleared outdated saved JSON |

---

## 🧪 Testing (iPhone 15 Pro)

| Feature | Result |
|---------|---------|
| Wellness Insights | ✅ |
| Add / Delete Task | ✅ |
| Notifications | ✅ |
| HealthKit Integration | ✅ |
| Proactive Suggestions | ✅ |

Performance: **Smooth, real-time updates with no lag**.

---

## 🔮 Future Enhancements

- Migrate from JSON to **SwiftData**
- Add **gamified reward animations**

---

## 🤖 AI Collaboration

AI tools such as **Google Gemini** were used for idea support, planning, and debugging.  
All generated code was **reviewed, customized, and tested manually**.

---

## 🏁 Conclusion

MindfulTask demonstrates how technology can support **both achievement and well-being**.  
It transforms ordinary task management into a **mindful lifestyle**, proving that true success is meaningful only when it’s **balanced and healthy**.

---

