🍪 Cookie Cats AB Test Analysis
🎯 Problem Definition

Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. It's a "connect three"-style puzzle game where players match tiles of the same color to clear the board and win levels.

As players progress, they encounter gates that either make them wait ⏳ or encourage in-app purchases 💰. These gates also help give players a break, potentially enhancing long-term enjoyment 🎮.

The first gate was originally at level 30, and the AB test moved it to level 40. This analysis focuses on the impact of this change on player retention and game sessions.

🗂 Dataset Description

The dataset contains information about players of Cookie Cats:

user_id 🆔: Unique player identifier

game_version 🎮: Gate version (control: Gate30, treatment: Gate40)

total_rounds_played 🔢: Total number of game sessions played by the player

retention_1 📅: Player retention on the first day (boolean/proportion)

retention_7 📆: Player retention after seven days (boolean/proportion)

❓ Key Questions

Has the average number of game sessions increased by 5 sessions? 🎯

Has player retention increased by 2% after 1 day? 📈

Has player retention increased by 5% after 7 days? 📊

🔬 Hypothesis Testing
1️⃣ Game Sessions

Null Hypothesis (H0): The mean number of sessions for Gate30 (control) ≤ Gate40 (treatment)

Alternative Hypothesis (H1): The mean number of sessions for Gate30 > Gate40

Decision Rule: Reject H0 if p-value < alpha

2️⃣ Day-1 Retention

H0: The proportion of players returning on day 1 is the same for Gate30 and Gate40

H1: The proportions are different

Decision Rule: Reject H0 if p-value < alpha

3️⃣ Day-7 Retention

H0: Retention rate after 7 days has not increased by 5%

H1: Retention rate after 7 days has increased by at least 5%

Decision Rule: Reject H0 if p-value < alpha

📊 Analysis Goals

Determine whether moving the gate from level 30 to 40 affects average game sessions 🎮.

Assess whether short-term (1 day) and long-term (7 days) retention improves 📈.

Support data-driven decisions about optimal gate placement to balance player engagement and monetization 💰.
