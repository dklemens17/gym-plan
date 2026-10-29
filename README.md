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

## Why each exercise matters

Every exercise shows a blue **On the pitch** box. It has a headline payoff and a one-line explanation of how the exercise helps in a game. A few examples:

- Countermovement jumps: "Explosive legs".
- Hex bar deadlift: "Harder to knock off the ball".
- Pullovers: "Longer throw-ins".
- Shuttles: "Cut and go".

Knee armor exercises show a green box naming the muscle they strengthen and how it protects the knee. Warm-up items carry a one-line reason too, plus a **How to do it** dropdown with step-by-step cues and an animated demo. The payoff also shows on the PR Challenge splash and in the "Next" line on rest screens.

## Knee armor

Every session ends with deliberate work for the muscles that protect the knee ligaments. Each exercise in the app says which muscle it targets and why.

| Muscle | Why it matters | Exercises (rotate by block) |
| --- | --- | --- |
| Hamstrings | Keep the shin from sliding forward, the same job the ACL does | Nordic hamstring lower, single-leg RDL, hamstring bridge, sliding leg curl |
| Hips and glutes | Stop the knee caving inward on landings and cuts | Side-lying hip abduction, side plank with leg raise, single-leg glute bridge |
| Inner thigh | Steadies the inside of the knee on cuts and kicks | Copenhagen plank |
| Quads and control | Knee tracks over the toes under load | Single-leg sit to bench, forward step-down, split-squat hold |
| Calves and soleus | Absorb landings; soleus helps pull the shin back | Single-leg calf raise, seated soleus raise |

## Built-in timers

- **Rest timer.** Starts on its own when a set is logged, with a suggested time and the reason on screen. Adjust it 15 seconds at a time.
  - **By kind of work and stage**, following youth strength guidelines: about 1 minute for beginners, 1 to 2 minutes for intermediate, 2 to 3 minutes for heavy or power work.
    - Heavy lifts: 1:15, then 1:45, then 2:30.
    - Strength sets: 1:00, then 1:30, then 2:00.
    - Stick jumps: 45 to 75 sec. In young soccer players, 30, 60 and 120 sec between jump sets gave the same gains.
    - Reactive and depth jumps: 1:00 to 1:30.
    - Sprints: 1:30 or more. Shuttles: 2:00.
    - Throws: 45 to 60 sec. Knee armor: 45 to 60 sec. Nordics: 1:00 to 1:30. Core: 30 to 45 sec.
  - **By step in the workout:**
    - Paired exercises switch after 15 seconds and rest after the pair.
    - Moving to a new exercise adds 30 seconds to set up.
    - A set that falls short of its target reps adds 30 seconds.
  - Rests are shorter than an adult plan because kids recover from hard efforts faster than adults.
- **Hold timer** for timed exercises such as the Copenhagen plank, hollow hold and split-squat hold. It counts down "get set", the hold, "switch sides" and the second side, then logs the set.
- **Session clock** in Run workout, plus timers on the timed warm-up items.
- Beeps on the last 3 seconds (sound can be turned off). The phone vibrates where supported, and the screen stays awake during a workout.

## PRs and PR Challenges

- **PRs are logged automatically** from real numbers, and each one gets a celebration with confetti and a sound:
  - A heavier weight than ever.
  - A stronger set: more reps at a given weight, compared using estimated strength.
  - More push-up or inverted-row reps.
  - A longer Copenhagen, hollow or split-squat hold.
  - A better broad jump, sprint or throw-in test.
- The first session of an exercise sets the baseline.
- **One PR Challenge per session**, rotating through each block:

  | Week of block | Day A | Day B |
  | --- | --- | --- |
  | 1 | Copenhagen longest hold | Push weight or max reps |
  | 2 | Hex bar weight PR | Squat weight PR |
  | 3 | Single-leg lift weight PR | Push weight or max reps |
  | 4 (test week) | Hex bar rep max | Squat rep max |

  - When Run workout reaches the challenge exercise, a full-screen flash calls it out with the record to beat.
  - The challenge is the last set. Weight challenges suggest 5 lb more on bars and 2.5 lb more on dumbbells, and only if every rep so far looked clean.
  - Rep max challenges stop at 12 reps, or as soon as form slips.
  - In test week, the three tests are PR challenges too.
- **The Progress tab has a PR board:** total PRs, challenges won, records for every exercise, and recent PRs.

## Where the data lives

Logs are saved in the phone's browser (localStorage). Nothing is sent anywhere. Use **Progress > Export backup** now and then, and **Import backup** to move the log to another device.

## Hosting

Served with GitHub Pages from the `main` branch root. To add it to a phone's home screen, open the page in Safari or Chrome and choose "Add to Home Screen".
