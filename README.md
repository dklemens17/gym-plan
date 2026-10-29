# Gym Plan

A 36-week, twice-a-week gym logbook for a 12-year-old soccer player: explosiveness, speed, throw-in power, and deliberate strength work for the muscles that protect the knee ligaments.

Open it on a phone, pick the week and Day A or Day B, then tap **Run workout** to go set by set with an animated demo of each exercise, or log sets directly in the list.

## How the program is built

- **3 stages of 12 weeks:** Foundation (technique, landings, base strength), Strength (heavier lifts, linked jumps), Power (fast, reactive jumps and cuts).
- **Each stage has 3 blocks of 4 weeks.** Exercises rotate every block so the work stays varied:
  - Week 1: new exercises, start light.
  - Week 2: add weight where reps looked clean.
  - Week 3: strength lifts get an extra set.
  - Week 4: lighter test week (2 sets) plus broad jump, 10 m sprint and throw-in tests.
- **Day A:** jumps, hex bar deadlift, a rotating single-leg lift and pull, then Knee armor.
- **Day B:** sprints or shuttles, lateral bounds and hops, throw-in power, squat (goblet or back squat), push and pullover, Knee armor, core.

## Knee armor

Every session ends with deliberate work for the muscles that protect the knee ligaments. Each exercise in the app says which muscle it targets and why.

| Muscle | Why it matters | Exercises (rotate by block) |
| --- | --- | --- |
| Hamstrings | Keep the shin from sliding forward, the same job the ACL does | Nordic hamstring lower, single-leg RDL, hamstring bridge, sliding leg curl |
| Hips and glutes | Stop the knee caving inward on landings and cuts | Side-lying hip abduction, side plank with leg raise, single-leg glute bridge |
| Inner thigh | Steadies the inside of the knee on cuts and kicks | Copenhagen plank |
| Quads and control | Knee tracks over the toes under load | Single-leg sit to bench, forward step-down, split-squat hold |
| Calves and soleus | Absorb landings; soleus helps pull the shin back | Single-leg calf raise, seated soleus raise |

## Where the data lives

Logs are saved in the phone's browser (localStorage). Nothing is sent anywhere. Use **Progress > Export backup** now and then, and **Import backup** to move the log to another device.

## Hosting

Served with GitHub Pages from the `main` branch root. To add it to a phone's home screen, open the page in Safari or Chrome and choose "Add to Home Screen".
