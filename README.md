# GAM305-Project

## Module Two Project Log

### Chosen Scenario

Our team selected the First-Person Simulation scenario. The game will place the player inside a biological environment where they must eliminate viruses while navigating interconnected rooms and traversal systems. The team selected this scenario because it provides flexibility in gameplay design while allowing for creative environmental storytelling, combat mechanics, and exploration systems.

### Selected Additional Elements

1. Pick-Ups: 9 total pickups with at least 3 unique item types including health, ammo, and armor boosts
2. Jump Pads
3. Teleporters
4. Virus Reproduction System

These elements were selected because they support exploration, combat progression, environmental traversal, and replayability while remaining achievable within the project timeline.

### Brainstorming and Project Design Discussion

The team discussed creating a science-fiction themed first-person simulation where the player is miniaturized and inserted into a biological environment infected by dangerous viruses. The player’s objective will be to travel through multiple infected chambers while eliminating viruses and surviving environmental hazards throughout the level.

The level will contain at least five connected rooms with varying layouts and traversal mechanics. Each room will feature a distinct visual identity while maintaining a cohesive biological theme throughout the environment. The team discussed using lighting, textures, particle effects, and environmental assets to create the appearance of organic tunnels, infected chambers, bloodstream-inspired pathways, and laboratory-inspired areas.

Gameplay systems discussed during brainstorming include:

- Three unique virus enemy types with different visual designs and AI behaviors that patrol and attack the player
- Health, ammo, and armor pickups placed throughout the level
- Jump pads used for vertical movement and traversal between areas
- Teleporters connecting sections of the map and creating alternate navigation paths
- Virus reproduction mechanics that allow enemies to spawn over time and increase difficulty
- A progression system where players eliminate viruses while exploring the level to reach the final objective

The team also discussed maintaining a manageable project scope by focusing on polished core mechanics and stable gameplay systems instead of attempting overly complex features that could negatively impact development progress.

The team agreed that creating a traceability matrix and test plan would help us better track functionality, implementation descriptions, current progress, final phases, task assignments, and testing status. The test plan will also help us monitor bugs, issues, and pass/fail results throughout the game development process to ensure features are working as intended. (Alice)

### Development Schedule and Timeline

#### Module 2

- Finalize scenario selection
- Establish communication methods
- Create repository structure
- Assign initial development responsibilities
- Brainstorm gameplay systems and level structure

#### Module 3

- Develop graybox/blockout level
- Create room layouts and player navigation flow
- Implement first-person player movement
- Begin environmental asset collection

#### Module 4

- Implement virus enemy AI systems
- Create pickup systems
- Add jump pads and teleporters
- Begin initial texture and lighting passes

#### Alpha Stage

Development goals for the Alpha Stage include:

- Fully explorable level layout
- Functional first-person movement
- Core virus enemy AI implementation
- Functional pickup systems
- Working jump pads and teleporters
- Initial gameplay loop established
- Basic environmental textures and lighting in place
- Initial testing for gameplay functionality and collision issues

Project progress during Alpha will be tracked using:

- GitHub commits and branches
- Weekly progress updates
- Team communication logs
- Internal gameplay testing sessions

#### Module 5-6

- Improve environmental detail and level polish
- Implement virus reproduction system
- Balance gameplay difficulty
- Refine lighting and atmosphere
- Continue bug fixing and testing

#### Beta Stage

Development goals for the Beta Stage include:

- Fully playable level with complete gameplay loop
- Stable enemy functionality and AI behavior
- Completed environmental art and textures
- Refined traversal systems
- Functional UI elements and gameplay feedback
- Reduced gameplay, collision, and AI bugs
- Finalized level progression and balancing

Project progress during Beta will be tracked using:

- Bug tracking lists
- Team testing feedback
- GitHub issue tracking
- Gameplay milestone completion

#### Final Release

- Final optimization and polish
- Additional bug fixes
- Final gameplay balancing
- Repository cleanup
- Preparation of postmortem documentation

### Communication Methods

The team selected Discord and GitHub as the primary methods of communication and collaboration. Discord will be used for team discussions, progress updates, and meetings, while GitHub will be used for repository management, version control, feature branching, and progress tracking.

### Communication Frequency

The team will conduct at least one scheduled check-in each week to review progress, discuss issues, and assign new development tasks. Additional communication will occur throughout the week as needed during active development stages.

### Task Assignment and Reporting

The team will use GitHub Issues and repository branches to assign and track development tasks. Individual responsibilities will be documented through commit history, branch updates, and weekly progress reports. Team members will provide status updates during scheduled meetings and through Discord communication channels.


## Module Three Project Log - Team Development

# Quality Assurance and Testing Plan

## Communication and Collaboration

The team will use Discord and GitHub as the primary methods of communication and collaboration. Discord will be used for team discussions, meetings, progress updates, and problem solving. GitHub will be used for repository management, version control, feature branching, and issue tracking.

The team will conduct at least one scheduled team check-in each week to review progress, discuss issues, and assign new development tasks. Additional communication will occur throughout development as needed.

---

## Team Documentation

The team will maintain shared documentation through Microsoft 365 to allow real-time collaboration and updates throughout development.

Shared documents include:

- Traceability Matrix
- Test Plan
- Bug Tracker

These documents will be continuously updated to reflect feature implementation progress, testing results, bug reports, and project changes. Microsoft 365 allows all team members to access and update documentation while maintaining version history.

---

## Testing Schedule

### Preproduction Play Test

Testing during early development will focus on validating basic mechanics and gameplay flow before major systems are fully implemented.

Testing objectives:

- First-person movement
- Collision and player navigation
- Initial room layouts
- Basic player interaction
- Navigation and progression through the graybox/blockout level
- Basic environmental traversal

---

### Demo Testing

Before project demonstrations and milestone reviews, the team will conduct internal testing sessions to verify completed features and identify gameplay issues.

Testing objectives:

- Virus enemy behavior
- Pickup functionality
- Jump pads
- Teleporters
- Environmental interaction
- Gameplay progression
- Difficulty balancing
- Visual and gameplay feedback

---

### Code Release Testing

Before major feature releases or merges into the main branch, testing will validate functionality against the established test plan.

Testing objectives:

- Regression testing
- Feature integration testing
- Bug verification
- Performance testing
- Collision testing
- Complete gameplay loop verification

---

## Test Checklist

| Feature                   | Expected Result                              | Status  | Assigned Tester | Notes |
| ------------------------- | -------------------------------------------- | ------- | --------------- | ----- |
| First-person movement     | Player moves correctly in all directions     | Pass | Ruben           |       |
| Room navigation           | Player can travel between rooms correctly    | Pending | Grace           |       |
| Virus AI                  | Enemies patrol and attack correctly          | Working on it | Alice           |Currently cannot place nav mesh. Working on finding the error|
| Health pickups            | Health increases properly                    | Pending | David           |       |
| Ammo pickups              | Ammo increases properly                      | Pending | David           |       |
| Armor pickups             | Armor increases properly                     | Pending | David           |       |
| Jump pads                 | Player launches correctly                    | Pass | Ruben           |       |
| Teleporters               | Player teleports to intended location        | Pass | Ruben           |       |
| Virus reproduction system | New enemies spawn correctly                  | Pending | Alice           |       |
| Final progression         | Player reaches the final objective correctly | Pending | Ruben           |       |

Status options:

- Pending
- Testing
- Pass
- Fail

---

## Updating the Test Plan

The test plan will be updated whenever changes are made to the game design document or gameplay systems.

The team will maintain a traceability matrix to track:

- Feature descriptions
- Assigned team members
- Current implementation status
- Expected functionality
- Testing status
- Final implementation goals

Whenever a feature changes, the corresponding testing requirements and documentation will also be updated.

---

## Bug Reporting

Bugs will be reported through GitHub Issues and documented within the testing documentation.

Each reported bug will include:

- Bug ID
- Description
- Steps to reproduce
- Assigned team member
- Priority level
- Current status

---

## Bug Tracking and Change History

The team will track bug progression using the following categories:

- Open
- In Progress
- Testing
- Fixed
- Closed

For each bug, changes and solutions will be documented to create a history of how issues were resolved throughout development.

Maintaining bug history will help the team identify recurring issues, monitor completed fixes, and maintain stable progress throughout the project lifecycle.

Alice Iuliano, Ruben Rodriguez, David Bryan, Grace Provencher


## Module Four Project Log - Team Reflection

### QA and Testing Process: What Went Well?

The testing process was effective in identifying gameplay and functionality issues early in development. Team members were able to verify core systems including first-person movement, room navigation, pickups, jump pads, and teleporters against the testing plan established in Module Three.

Regular testing sessions helped ensure that newly implemented features functioned as intended before additional systems were added. The use of the traceability matrix and test plan allowed the team to track feature completion and testing progress throughout development. Communication through Discord also helped team members quickly report issues and share testing results.

---

### Bugs: Identifying and Correcting Issues

Most bugs were identified through internal playtesting and feature-specific testing sessions. Team members tested implemented systems against expected functionality listed in the test checklist.

Examples of issues identified included:

- Collision and navigation problems within level geometry
- Teleporter destination and placement issues
- Jump pad launch inconsistencies
- Pickup interaction and trigger detection problems
- Enemy behavior adjustments during testing

When bugs were identified, they were documented through team communication and GitHub updates. Team members reproduced the issues, isolated the cause, implemented fixes, and then retested the affected systems to verify that the problem had been resolved without introducing additional issues.

---

### What Would We Do Differently?

If the team were to repeat this phase of development, we would begin structured testing earlier and conduct more frequent testing sessions throughout implementation.

Several features were tested after major portions of development were completed. Conducting smaller testing sessions immediately after each feature implementation would have allowed issues to be identified sooner and reduced the amount of rework required later.

The team would also benefit from maintaining a more detailed bug tracking log from the beginning of development to better monitor issue status and resolution history.

---

### Helpful Tools and Techniques

The most successful tools used during development were Discord, GitHub, feature branching, and the QA documentation created during Module Three.

**Discord** provided an efficient platform for communication, progress updates, problem solving, and coordination between team members.

**GitHub** allowed the team to manage source control, maintain project backups, and safely develop features through separate branches before merging changes into the main project.

**Feature branching** helped prevent conflicts between team members while allowing multiple systems to be developed simultaneously.

**The traceability matrix and testing plan** provided a structured approach to monitoring project progress, feature completion, and testing status.

---

### Tools and Techniques That Were Less Helpful

Although all selected tools contributed to development, the team found that maintaining documentation required consistent updates and could become time-consuming during active development periods.

At times, information within testing documents and development progress reports required manual updates after implementation changes. While the documentation remained valuable, maintaining it alongside active development occasionally slowed workflow.

The team also found that informal testing discussions sometimes occurred before updates were recorded in official documentation, creating temporary gaps between development progress and recorded testing status.

---

### Team Approach and Tool Selection

The team's initial analysis of the game design document played a significant role in determining which tools and techniques would be used throughout development.

Because the project involved multiple gameplay systems, environmental mechanics, and team members working on separate tasks, the team recognized the need for strong communication and version control early in development. This led to the selection of Discord for communication and GitHub for repository management.

The complexity of the project also influenced the decision to create a traceability matrix, testing plan, and bug tracking process. These tools helped ensure that planned features remained aligned with project requirements while providing a method for tracking implementation and testing progress.

---

### Alpha Stage Status Assessment

The project has successfully reached the Alpha stage with the majority of planned core gameplay systems implemented and functioning.

Completed Alpha features include:

- First-person player movement
- Multi-room level layout
- Virus enemy implementation
- Pickup systems
- Jump pads
- Teleporters
- Initial environmental design and traversal systems
- Core gameplay loop functionality

Current development efforts are focused on continued testing, bug fixes, gameplay balancing, and feature refinement.

To prepare for Beta development, the team plans to:

- Continue refining enemy behavior
- Implement and test the virus reproduction system
- Improve environmental polish and visual quality
- Perform additional gameplay balancing
- Conduct expanded testing sessions
- Resolve remaining gameplay and collision issues

These objectives remain consistent with the development schedule established during Module Two and position the project to successfully reach Beta milestones.

---

### Alpha Prototype Repository Branch

The Alpha prototype has been prepared using the repository branch:

**FinalAlpha**

---

### Team Members

- Alice Iuliano
- Ruben Rodriguez
- David Bryan
- Grace Provencher

---


## Module Five Project Log - Team Reflection

### What Parts of the Plan Went Well in Relation to the Last Stage Evaluation

During the last stage evaluation, we perceived that several important issues from earlier development had been resolved. One of the biggest improvements was with the AI navigation system. Previously, we were having issues with the Nav Mesh, which prevented the enemy from moving properly. After troubleshooting and rebuilding the navigation setup, the enemy was able to patrol the area successfully. This was an important step because enemy movement is a core part of the gameplay experience.

We also made progress with the level layout. The layout became more cohesive and walkable, and each room now feels more connected to the overall game structure. This made the project easier to evaluate because the player can move through the space more naturally, and the rooms feel like they are part of one connected environment rather than separate unfinished areas.

---

### What Parts of the Plan Went Wrong in Relation to the Last Stage Evaluation

Some of the more complicated gameplay functionality took longer than initially expected. For example, the enemy splitting into two when hit by the player is a more advanced feature that still requires additional work and testing. This showed us that certain mechanics may need more development time than originally planned, especially when they depend on other systems being fully functional first.

Another challenge was that not every part of the project was at the same level of completion during the evaluation. Some systems were working and ready to be tested, while others still needed more implementation or polish. This made it harder to evaluate the full Beta experience as one complete build.

---

### How Previous Evaluations Were Integrated Into This Latest Stage

Previous evaluations were integrated by using earlier feedback and technical issues to guide the next stage of development. Instead of only adding new features, we focused on solving problems that affected the core gameplay. The Nav Mesh issue is one example of this because it directly affected whether the enemy could function correctly.

The previous evaluations also helped us better understand what needed to be prioritized. Core systems such as enemy movement, level navigation, room layout, jump pads, teleporters, and overall playability became the main focus. This helped move the project closer to a playable Beta stage.

---

### What We Would Do Differently to Improve Collaboration or Development

To improve the collaboration and development process, we would focus on stronger communication and more consistent follow-ups. Regular check-ins would help the team confirm what has been completed, what still needs work, and whether anyone needs support. This would reduce confusion and make it easier to identify problems earlier in the development process.

We would also make sure tasks are documented more clearly, including who is responsible for each task and when it should be completed. This would help the team stay organized and avoid last-minute uncertainty about which features are complete and which still need attention.

---

### Tools or Techniques That Were Not Helpful

We do not think any tool was completely unhelpful to the success of the project. However, some tools and techniques are only useful if the team uses them consistently. Communication tools, planning documents, and test plans can support development, but they become less effective if they are not updated regularly or followed up on.

The main issue was not necessarily the tools themselves, but the consistency of how they were used. A schedule, task list, or test plan only helps the project if everyone uses it to track progress and communicate updates.

---

### Completed Stage of Development and Project Schedule

The project is currently in the intended Beta stage of development. At this stage, the main systems are beginning to come together, and the project is playable enough to evaluate core gameplay elements. The enemy AI can now patrol, the level layout is more cohesive and walkable, and systems such as the jump pad and teleporter have been developed.

To meet the Final Release deadline, the team should focus on completing unfinished core features first. This includes finalizing more complex mechanics, such as enemy splitting, and making sure all major gameplay systems work together. After that, the focus should shift to QA testing, bug fixing, retesting, and polishing the level, gameplay flow, and player experience.

The final schedule should prioritize stability over adding too many new features. At this stage, it is more important to make sure the current systems work correctly than to expand the scope too much before the Final Release deadline.

---
### Team Members

- Alice Iuliano
- Ruben Rodriguez
- David Bryan
- Grace Provencher

  ## Module Six Project Log - Team Reflection

### What Parts of the Plan Went Well in Relation to the Last Stage Evaluation

One area that went well during this stage was our ability to improve the overall playability of the project despite development challenges. Building on the previous evaluation, the team focused on creating a more complete gameplay experience rather than continuing to add new features. Health bars were successfully implemented, health pickups were integrated into gameplay, and a small playable level was created to allow testing of the systems that had been completed. We also developed a functional main menu and game over menu, which helped provide a more complete gameplay loop than what existed during the previous stage.

Another positive outcome was the continued refinement of systems that had been causing issues earlier in development. Several gameplay and technical problems were addressed, allowing the project to become more stable and easier to test. While the game remained limited in scope, the systems that were completed worked together more effectively than in previous builds.

---

### What Parts of the Plan Went Wrong in Relation to the Last Stage Evaluation

The biggest challenge during this stage was maintaining development momentum while working with limited participation across the team. As development progressed, much of the implementation work fell to a smaller group of contributors, with Alice Iuliano and Ruben Rodriguez taking on the majority of the remaining development tasks in an effort to assemble a playable final build. This reduced the amount of time available for advanced features, testing, and polish.

Several planned systems also proved more difficult to implement than originally expected. One example was the enemy splitting mechanic, which required additional design, programming, and testing effort that became difficult to prioritize while other gameplay systems still needed attention. We also spent significant time troubleshooting the player health UI to ensure it updated dynamically when health pickups were collected. In addition, camera-related issues required further adjustments before the player experience felt acceptable.

Because of these challenges, some planned functionality was simplified or left unfinished so that development efforts could focus on creating a stable and playable build for the final release.

---

### How Previous Evaluations Were Integrated Into This Latest Stage

Feedback from previous evaluations directly influenced the priorities for this stage of development. Earlier reviews highlighted the importance of creating a cohesive gameplay experience rather than focusing exclusively on adding new mechanics. As a result, development efforts shifted toward improving stability, usability, and player feedback systems.

The work completed on health pickups, health bar functionality, menu systems, and level playability reflected lessons learned from previous evaluations. Earlier concerns regarding gameplay flow, system integration, and overall playability guided decision-making throughout the final development stage. Rather than expanding the project's scope, the focus became making existing systems work together more effectively and ensuring players could experience a functional gameplay loop.

---

### What We Would Do Differently to Improve Collaboration or Development

If we were to repeat this project, we would establish more structured accountability and milestone tracking earlier in development. While communication tools were available, stronger follow-up procedures and clearer expectations regarding task completion would have helped maintain progress throughout the project lifecycle.

We would also prioritize creating a playable vertical slice much earlier in development. Having a stable test build available sooner would have allowed the team to identify integration issues earlier and spend more time refining gameplay systems. Earlier testing of UI functionality, player camera behavior, and enemy mechanics would likely have reduced the amount of troubleshooting required during the final stages of development.

---

### Were There Any Tools or Techniques That Were Not Helpful?

The primary challenge was not the tools themselves but how consistently they were used. GitHub, Discord, and project documentation all provided value throughout development. However, planning documents and task tracking systems are only effective when they are updated regularly and supported by consistent participation from all team members.

As development progressed, documentation occasionally became less reflective of the current state of the project because implementation priorities changed rapidly. More frequent updates to project tracking materials would have helped ensure that development goals, testing status, and feature progress remained aligned throughout the final stages of the project.

---

### Final Release Status

Although not all originally planned features were completed, the team successfully assembled a functional and playable build. The final project includes a playable map, enemy encounters, health systems, health pickups, a dynamically updating health bar, a main menu, and a game over screen. Alice Iuliano and Ruben Rodriguez worked to bring together the completed systems and resolve as many issues as possible within the remaining development time.

While some features such as the enemy splitting system were not completed to the level originally envisioned, significant progress was made toward improving stability, usability, and overall playability. Despite development setbacks and limited participation during the final stages of the project, the final build demonstrates the core gameplay concepts established during planning and represents the team's best effort to deliver a functional game experience.

---

### Team Members

- Alice Iuliano
- Ruben Rodriguez
