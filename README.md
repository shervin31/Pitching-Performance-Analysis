# Rays Pitching Analysis: MLB Pitch-Level Performance Insights

📖 **Project Overview**  
This project focuses on analyzing Tampa Bay Rays pitching data (40k+ pitch records) to understand pitcher performance, pitch selection patterns, and game outcomes. Using detailed pitch-by-pitch and player statistics, the goal is to provide actionable insights that can inform scouting, strategy, and performance evaluation in Major League Baseball.

🎯 **Business Objective**  
Pitchers and coaching staff often need data-driven insights to optimize performance. This analysis identifies trends in pitch frequency, pitch types, situational outcomes, and home run tendencies. By uncovering these patterns, the project helps teams make informed decisions about pitcher usage, pitch strategies, and batter matchups.

📊 **Dataset**  
- **Source:** RaysPitching Database (LastPitchRays & RaysPitchingStats tables)  
- **Records:** 40k+ pitch-level records from Tampa Bay Rays games  
- **Features:** Pitch type, pitch count, pitch speed, spin rate, game location, batter handedness, pitch outcome, home runs, strikeouts, runner positions, and more  
- **Target Analysis:** Patterns in pitch selection, pitch outcomes, home run risk, and player-specific insights  

🛠️ **Technical Approach**  
The analysis follows a structured data-driven workflow:

**Data Preprocessing & EDA:**  
- Cleaned pitch-level and player data, handled missing values, and standardized metrics  
- Explored trends in pitches per at-bat, pitch sequences, home/away splits, and handedness  

**Comparative Analysis:**  
- AVG pitches per at-bat by game location, batter handedness, and pitcher role  
- Top 3 most common pitches by pitch sequence  

**Home Run & Launch Analysis:**  
- Identified pitch types, zones, and counts most associated with home runs  
- Evaluated launch speed and spin rates for pitch effectiveness  

**Player-Specific Analysis:**  
- Focused on Shane McClanahan: release speed, spin rate, strikeout patterns, pitch distribution by infield positions, and pitch outcomes with runners on base  

📈 **Key Results & Insights**  
- AVG pitches per at-bat vary by location, batter handedness, and pitcher role  
- Fastballs dominate last-pitch counts; offspeed pitches follow  
- Home run-prone pitches and zones highlighted for strategic adjustments  
- Shane McClanahan’s pitch tendencies quantified for advanced scouting  
- Top pitch sequences and situational patterns identified for strategic planning  

💡 **Impact & Recommendations**  
- Use pitch-level insights to optimize pitcher strategy and game planning  
- Inform coaching staff and analysts for batter matchups and pitch selection  
- Evaluate player-specific strengths and situational effectiveness for targeted performance improvement  

📁 **Repository Structure**  
- `SQL/`: Queries for pitch analysis, home runs, and player-specific insights  
- `Data/`: Source tables (LastPitchRays, RaysPitchingStats)  
- `Analysis/`: Summary tables and aggregated results  
