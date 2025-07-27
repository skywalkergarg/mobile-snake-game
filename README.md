# Snake Game - Nova Benefits (Mobile)

A fun HR-themed Snake game where you advance from HR Intern to CHRO while minimizing employee attrition!

## 🎮 Game Overview
This is a 2-minute Snake game where you play as an HR professional trying to minimize employee attrition while advancing your career from HR Intern to CHRO (Chief Human Resources Officer).

## 🕹️ Controls

### Desktop
- **Arrow Keys**: Control snake movement
- **Keys 1-3**: Adjust game speed (Low/Medium/High)
- **Spacebar**: Restart game when game over

### Mobile
- **Tap Screen**: Tap relative to the snake's head position to change direction
- **Speed Dropdown**: Use the dropdown menu to adjust speed
- **Tap Game Over Message**: Restart the game

## 🎯 Core Game Mechanics

### 👥 Employees (Blue Characters 👨‍💼👩‍💼)
- Employees spawn randomly on the game board
- They move around independently in random directions
- After 10 seconds, employees become "at-risk" and turn red 🦸‍♂️🦸‍♀️
- At-risk employees will exit the company after another 10 seconds if not saved
- When employees exit, it increases your attrition rate

### 🎁 Powerups (Gift Boxes)
- Gift boxes appear randomly with different HR benefits:
  - Insurance, Training, Recognition, Onboarding, Feedback
  - Flexibility, Engagement, Culture Book, Timely Payroll
  - Offsite, Growth Plan, Inclusivity, Mentorship, Appraisal
  - Doctor, Therapist, Health Checkup, Gym Subscription, OPD

**Collecting a powerup:**
- Increases your HR experience level by 1
- Grows the snake by one segment  
- Activates **Supernova Mode** for 5 seconds

### ⭐ Supernova Mode
- Snake turns golden yellow during this 5-second period
- You can save at-risk (red) employees by touching them
- **Saving employees:**
  - Gives +10 points
  - Counts as employee retention
  - Permanently saves that employee (they won't become at-risk again)
  - Spawns a new employee to maintain workforce

## 🏆 Career Progression
Your HR level determines your title:

| Level | Title |
|-------|-------|
| 0-5 | HR Intern |
| 6-10 | HR Associate |
| 11-15 | HR Manager |
| 16-19 | HR Lead |
| 20-25 | Head HR |
| 26+ | CHRO |

## 🎲 Game Rules

### Movement Rules
- Snake cannot reverse direction (can't go directly opposite to current direction)
- Hitting walls or the snake's own body results in game over
- Speed affects how fast the snake moves

### Win/Lose Conditions
- **Time Limit**: 2 minutes to play
- **Game Over Triggers**: 
  - Snake hits walls
  - Snake hits itself
  - Time runs out

### Success Metrics
- **Minimize attrition percentage** (exited employees ÷ total employees)
- **Achieve highest possible HR title**
- **Maximize employee retention**

## 📊 Scoring & Metrics

The game tracks these key performance indicators:
- **HR Level & Title**: Increases with powerup collection
- **Total Employees**: All employees hired during the game
- **Exited Employees**: Employees who left the company
- **Present Headcount**: Current active employees
- **Attrition %**: Key performance metric (exited ÷ total × 100)

## 🎯 Strategy Tips

1. **Collect powerups quickly** to enter Supernova mode
2. **Save at-risk employees** during Supernova to minimize attrition
3. **Plan your route** to efficiently reach red employees
4. **Balance growth and retention** - longer snake means higher speed but harder control
5. **Time management** - prioritize saving employees over collecting powerups when time is running low

## 🚀 Getting Started

1. Open `index.html` in a web browser
2. Choose your preferred speed setting
3. Use appropriate controls for your device
4. Try to achieve CHRO level with minimal attrition!

## 🎖️ Challenge Goals

- **Beginner**: Reach HR Associate level
- **Intermediate**: Reach HR Manager with <20% attrition
- **Advanced**: Reach CHRO with <10% attrition
- **Expert**: Reach CHRO with 0% attrition

Good luck on your journey from HR Intern to CHRO! 🎉 