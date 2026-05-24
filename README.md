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
| First-person movement     | Player moves correctly in all directions     | Pending | Ruben           |       |
| Room navigation           | Player can travel between rooms correctly    | Pending | Grace           |       |
| Virus AI                  | Enemies patrol and attack correctly          | Pending | Alice           |       |
| Health pickups            | Health increases properly                    | Pending | David           |       |
| Ammo pickups              | Ammo increases properly                      | Pending | David           |       |
| Armor pickups             | Armor increases properly                     | Pending | David           |       |
| Jump pads                 | Player launches correctly                    | Pending | Ruben           |       |
| Teleporters               | Player teleports to intended location        | Pending | Ruben           |       |
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
