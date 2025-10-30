# Fonctionnalités principales et cas d’utilisation


## 1. Brainstorm ALL features

### Possible features

- See workout list
- Start a workout
- See timer
- Track calories
- Save favorite workouts
- Download for offline
- Create custom workout
- Login


## 2. Prioritized Features (MoSCoW)

| Feature | Description | Priority |
|----------|--------------|-----------|
| Display 3 workout routines (15 min each) | Home screen with 3 ready-to-start options | **Must** |
| Start a workout | “Start” button → timer + calories tracking | **Must** |
| Live calorie tracking | Real-time display of calories burned | **Must** |
| Offline mode | Download once, use anywhere | **Should** |
| Save a workout | Mark as favorite | **Could** |
| User login | Login / profile | **Won’t** (MVP) |

---

## 3. Use Cases (UC)

| ID | Actor | As **Ahmed**, I want to… so that I can… | Priority |
|----|--------|------------------------------------------|-----------|
| UC1 | Busy employee | see 3 ready-to-use 15-minute workouts **so I can choose in less than 5 seconds** | Must |
| UC2 | Busy employee | start a workout with one click **so I don’t waste time** | Must |
| UC3 | Busy employee | see calories burned in real time **so I can track my progress** | Must |
| UC4 | Busy employee | use the app without Wi-Fi **so I can work out in the basement** | Should |
| UC5 | Busy employee | save a workout **so I can repeat it tomorrow** | Could |

---

## 4. Use Case Diagram (Text Version)
```
          +-------------------+
          |     Fitness App   |
          +-------------------+
             /       |        \
            /        |         \
   +---------------+ +---------------+ +---------------+
   | Start Workout | | Track Calories| | Offline Mode  |
   +---------------+ +---------------+ +---------------+
          |                  |                  |
        [Ahmed]            [Ahmed]            [Ahmed]

```