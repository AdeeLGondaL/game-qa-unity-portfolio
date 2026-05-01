# Game QA & Unity Development Portfolio

## About Me

I am a Unity/C# game developer and QA-oriented software engineer with 2+ years of experience building, testing, debugging, and releasing mobile, VR, and interactive game projects.

My experience covers gameplay coding, UI implementation, bug fixing, initial testing, analytics integration, optimization, level design, publishing support, and structured QA documentation.

This portfolio highlights selected game projects, QA documentation samples, bug-reporting formats, regression checklists, and testing workflows relevant to manual game QA and game development quality assurance.

---

## Core QA & Game Development Skills

- Manual game testing
- Gameplay flow testing
- Exploratory testing
- Regression testing
- Bug reproduction
- Defect documentation
- Test-case writing
- Release validation
- UI and input testing
- Player experience evaluation
- Unity/C# gameplay debugging
- Performance profiling and optimization
- Firebase / ByteBrew analytics-based issue investigation
- Jira storyboards, GitHub Issues, Asana, Google Sheets, and Notion for task/bug tracking

---

# Published / Released Game Projects

## FINZ Games

### Mr. Sneaky / Rob People Prank

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.ws.rob.people.prank.game

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Level design support
- Analytics integration
- Optimization
- iOS publishing support

**QA Focus:**
- Tested player interactions and level flow
- Checked fail/retry behavior
- Verified UI states and button responses
- Reproduced gameplay bugs before release
- Supported release quality through repeated playtesting

---

### Break the Giant / Push the Giant

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.ws.push.the.giant.game

**Responsibilities:**
- Gameplay coding
- Physics/gameplay interaction tuning
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Level design support

**QA Focus:**
- Tested core gameplay loop
- Checked object interaction and player feedback
- Reproduced physics/collision-related issues
- Verified level progression and restart behavior
- Supported bug documentation and fix verification

---

### Horn Havoc / Bull Havoc Ragdoll

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.ws.bull.havoc.ragdoll.game

**Responsibilities:**
- Gameplay coding
- Ragdoll/physics-based interaction support
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Level design

**QA Focus:**
- Tested collision behavior and ragdoll responses
- Checked gameplay stability during repeated interactions
- Reproduced inconsistent object behavior
- Verified fail/retry and level-completion states
- Supported performance and stability improvements

---

### Scary Makeover / Haunted Scary Wash

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.haunted.scarywash

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Level design support
- Analytics integration
- Optimization

**QA Focus:**
- Tested UI navigation and player interaction flows
- Checked visual feedback and gameplay clarity
- Verified level progression
- Reproduced UI and interaction bugs
- Supported release preparation and fix verification

---

### Smash Its Legs

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.smash.its.legs.game

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Level design support

**QA Focus:**
- Tested gameplay responsiveness
- Verified player input and object interactions
- Checked fail/retry behavior
- Reproduced gameplay and UI issues
- Supported release quality through repeated manual testing

---

### Smash the Balloon / Pop Fury

**Platform:** Mobile  
**Role:** Unity/C# Developer, Game QA Support  
**Link:** https://play.google.com/store/apps/details?id=com.tb.smash.the.balloon.game

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Level design support

**QA Focus:**
- Tested core gameplay loop
- Verified input response and level progression
- Checked reward/fail states
- Reproduced interaction bugs
- Supported performance and release testing

---

## RipeSeed Projects

### SpookySphere

**Platform:** Mobile  
**Role:** Unity Developer, QA Support, Publishing Support  
**Link:** https://play.google.com/store/apps/details?id=com.redpetalgames.spookysphere

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Publishing support
- Level design

**QA Focus:**
- Tested gameplay flow and UI navigation
- Verified input response and progression
- Reproduced interaction and level-flow issues
- Created sample manual test cases and bug reports
- Built a regression checklist for release validation

---

### Gaze Maze

**Platform:** Mobile  
**Role:** Unity Developer, QA Support, Publishing Support  
**Link:** https://play.google.com/store/apps/details?id=com.ripeseed.gaze_maze

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Optimization
- Publishing support

**QA Focus:**
- Tested interaction logic and gameplay progression
- Checked UI behavior and user flow
- Reproduced bugs related to input and level states
- Supported optimization and release preparation

---

### Heroes_Alghamdi

**Platform:** Unity / GitHub Project  
**Role:** Unity Developer, QA Support  
**Link:** https://github.com/Raibatsu/Heroes_Alghamdi

**Responsibilities:**
- Gameplay coding
- UI implementation
- Bug fixing
- Initial testing
- Optimization

**QA Focus:**
- Tested gameplay mechanics
- Checked UI flow and player interaction
- Reproduced bugs during development
- Improved game stability through debugging and repeated testing

---

### VR Table Tennis

**Platform:** Unity VR  
**Role:** Unity Developer, Manual Game QA  
**Technologies:** Unity, C#, XR Toolkit

**Responsibilities:**
- Built physics-based VR gameplay
- Implemented racket interaction
- Developed ball trajectory and collision behavior
- Added AI opponent logic
- Tested real-time interaction reliability

**QA Focus:**
- Tested ball physics and collision detection
- Debugged inconsistent XR interactions
- Checked timing issues and gameplay responsiveness
- Validated edge cases through repeated manual testing
- Improved gameplay feel through testing and tuning

---

# QA Documentation Samples

## Sample Bug Report 1

### Bug Title

Player can get stuck after restarting level immediately after failure

### Type

Bug

### Environment

- Platform: Android
- Device: Samsung Galaxy A52
- OS: Android 13
- Build Version: Sample Build v1.0.4

### Severity

High

### Priority

Medium

### Preconditions

- Game is installed successfully
- Player has reached Level 3
- Player fails the level and the fail screen is visible

### Steps to Reproduce

1. Launch the game.
2. Start Level 3.
3. Let the player fail the level.
4. On the fail screen, tap the Restart button repeatedly.
5. Observe the game behavior.

### Expected Result

The level should restart once and load correctly with normal player controls.

### Actual Result

The game sometimes freezes on the fail screen and the player cannot continue without restarting the app.

### Reproduction Rate

Reproduced 4 out of 5 attempts.

### Evidence

Screen recording or screenshot can be attached.

### Retest Status

Open / Pending fix verification

---

## Sample Bug Report 2

### Bug Title

Reward button remains clickable after reward has already been claimed

### Type

Bug

### Environment

- Platform: Android
- Device: Xiaomi Redmi Note 10
- OS: Android 12
- Build Version: Sample Build v1.0.2

### Severity

Medium

### Priority

High

### Preconditions

- Player completes a level
- Reward screen is displayed

### Steps to Reproduce

1. Complete a level.
2. Wait for the reward screen.
3. Tap the reward button.
4. Quickly tap the reward button again.
5. Observe the reward state.

### Expected Result

The reward button should become disabled after the reward is claimed once.

### Actual Result

The reward button remains active and can trigger the reward flow again.

### Reproduction Rate

Reproduced 3 out of 5 attempts.

### Evidence

Screenshot or short recording can be attached.

### Retest Status

Open / Needs verification after fix

---

## Sample Bug Report 3

### Bug Title

Player character clips through obstacle during fast movement

### Type

Bug

### Environment

- Platform: Android
- Device: Samsung Galaxy S21
- OS: Android 14
- Build Version: Sample Build v1.0.5

### Severity

Medium

### Priority

Medium

### Preconditions

- Player is in a level with moving obstacles
- Player movement speed is at maximum

### Steps to Reproduce

1. Launch the game.
2. Start the obstacle level.
3. Move the player toward the obstacle at maximum speed.
4. Trigger collision at the edge of the obstacle.
5. Observe player behavior.

### Expected Result

The player should collide with the obstacle and stop or trigger the correct fail response.

### Actual Result

The player sometimes clips through the obstacle and continues moving.

### Reproduction Rate

Reproduced 2 out of 5 attempts.

### Evidence

Screen recording can be attached.

### Retest Status

Open

---

# Sample Test Cases

| Test Case ID | Feature | Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|---|
| TC-001 | Launch Flow | Verify that the game launches successfully | Open the game from the device home screen | Game opens without crash and main menu appears | Not Run |
| TC-002 | Main Menu | Verify Play button functionality | Launch game > Tap Play | First level loads correctly | Not Run |
| TC-003 | Gameplay Input | Verify player input response | Start level > Perform movement/input action | Player responds correctly to input | Not Run |
| TC-004 | Level Progression | Verify level completion flow | Complete level objective | Success screen appears and next level becomes available | Not Run |
| TC-005 | Fail Flow | Verify fail state behavior | Trigger fail condition during gameplay | Fail screen appears with retry option | Not Run |
| TC-006 | Retry Flow | Verify retry button functionality | Fail level > Tap Retry | Same level restarts correctly | Not Run |
| TC-007 | Reward Flow | Verify reward claim behavior | Complete level > Tap reward button | Reward is granted once and UI updates correctly | Not Run |
| TC-008 | UI Navigation | Verify settings/menu navigation | Open settings/menu and return | UI opens and closes correctly without broken states | Not Run |
| TC-009 | Performance | Check for major FPS drops or freezes | Play for 5 minutes continuously | No major freeze, crash, or severe performance drop occurs | Not Run |
| TC-010 | Audio/Visual Feedback | Verify feedback after interaction | Perform gameplay action | Correct sound, animation, or visual feedback appears | Not Run |
| TC-011 | Edge Case | Tap buttons repeatedly during transition | Rapidly tap UI buttons during loading or fail flow | No duplicate actions, freeze, or broken UI state occurs | Not Run |
| TC-012 | Progress Save | Verify level progress is saved | Complete level > Close game > Reopen game | Correct progress is restored | Not Run |

---

# Regression Checklist

Use this checklist before release or after major gameplay changes.

## Launch & Basic Flow

- [ ] Game launches successfully
- [ ] No crash on startup
- [ ] Main menu loads correctly
- [ ] Play button works
- [ ] First level loads correctly
- [ ] Loading transitions work correctly

## Gameplay

- [ ] Player input responds correctly
- [ ] Core gameplay loop works
- [ ] Level objective is clear
- [ ] Level completion works
- [ ] Fail condition works
- [ ] Retry button works
- [ ] Next level unlocks correctly

## UI / UX

- [ ] Buttons are clickable
- [ ] UI text is readable
- [ ] No overlapping UI elements
- [ ] Settings/menu navigation works
- [ ] Reward screen displays correctly
- [ ] Player receives clear feedback after actions

## Bug-Prone Areas

- [ ] Repeated button tapping does not break flow
- [ ] Player cannot get stuck in transition screens
- [ ] Reward cannot be claimed multiple times incorrectly
- [ ] Player cannot skip required progression steps
- [ ] Collision behavior works correctly
- [ ] No major physics instability appears

## Performance / Stability

- [ ] No major FPS drops during normal gameplay
- [ ] No freeze after repeated retries
- [ ] No crash after extended play session
- [ ] No major input delay
- [ ] Game remains responsive after level restart

## Release Validation

- [ ] No blocker bugs remain
- [ ] Critical gameplay flow works
- [ ] Core UI works
- [ ] Progression works
- [ ] Reward/fail/retry flow works
- [ ] Build is ready for final review

---

# QA Workflow Example

## 1. Find Issue During Playtesting

While testing gameplay flow, I observe unexpected behavior such as a freeze, broken UI state, collision issue, or reward-flow problem.

## 2. Reproduce the Issue

I repeat the same action multiple times to confirm whether the issue happens consistently or only under certain conditions.

## 3. Document the Bug

I write a clear bug report with:

- Title
- Environment
- Preconditions
- Steps to reproduce
- Expected result
- Actual result
- Severity
- Priority
- Evidence
- Reproduction rate

## 4. Track the Bug

The issue can be tracked using tools such as Jira storyboards, GitHub Issues, Asana, Google Sheets, or Notion.

## 5. Verify the Fix

After the bug is fixed, I retest the same steps and check related gameplay areas to make sure the fix did not break another part of the game.

---

# Tools & Technologies

## Game Development

- Unity
- C#
- XR Toolkit
- Android Studio
- Git
- GitHub

## QA & Documentation

- Jira storyboards
- GitHub Issues
- Asana
- Google Sheets
- Notion
- Test cases
- Bug reports
- Regression checklists

## Analytics & Debugging

- Firebase
- ByteBrew
- Unity Profiler
- Debug logs
- Player behavior analysis

## Technical QA

- Selenium WebDriver
- Python unittest
- Postman
- REST APIs
- JSON
- MySQL basics
- MongoDB

---

# Gaming Interest

I regularly play and analyze multiplayer, action, fighting, sports, co-op, and mobile games, including:

- Rainbow Six Siege
- Tekken 8
- Spider-Man
- FIFA 23
- Call of Duty 4
- Backrooms: Escape Together
- Clash of Clans
- League of Legends

When playing, I pay attention to gameplay feel, input responsiveness, UI clarity, progression systems, balancing, bugs, and overall player experience from a QA perspective.

---

# Contact

**Name:** Adeel Ahmed  
**Location:** Karlsruhe, Germany  
**GitHub:** https://github.com/AdeeLGondaL  
**Email:** ahmedadeel783@gmail.com
