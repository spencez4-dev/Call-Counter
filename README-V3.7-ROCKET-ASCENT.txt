LOAD RUSH V3.7 — DAILY ROCKET ASCENT

ADDED
- A new Mission to 100 rocket card directly above the Hourly Quest.
- The rocket begins at altitude 0 each day.
- Each + load/check call increases altitude by 1.
- Each minute causes a very small 0.02 altitude drift downward.
- The call total itself never decreases from time decay.
- Milestones run from Mercury at 10 through Heaven at 100.
- The entire day's path remains visible.
- The trail is rendered as a smooth cubic Bezier curve instead of rigid straight segments.
- The rocket coasts to its new position with a 0.78-second easing animation.
- The rocket rotates to follow the newest curve direction and briefly boosts its flame after a call.

SAFETY / ISOLATION
- Existing Hourly Quest code was not replaced.
- Reminder, Freight Fate, XP, garage, charts, recap, and countdown systems remain intact.
- Rocket data uses its own localStorage key: loadRushRocketV37.
- Rocket CSS uses rocket-* class names to avoid collisions.
- Existing main app state format was not changed.

UPLOAD
Upload/replace the included files in the repository and commit.
Open once with:
?v=rocket-ascent-v37

Confirm the build badge says:
LOAD RUSH · V3.7
