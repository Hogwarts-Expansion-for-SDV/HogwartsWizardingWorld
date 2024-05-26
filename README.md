# The Hogwarts Wizarding World Expansion

This is a hub for team members current and prospective mod-users and mod-makers to offer support for features, report bugs, and request new features or ideas for the Hogwarts Expansion mod for Stardew Valley. A description of the latest release's features can be found in its [Nexus page](https://www.nexusmods.com/stardewvalley/mods/14858).

The lack of a license is not an oversight. No one may reproduce, distribute, or create derivative works from the contents of this repository.

## For Non-Team Members
If you would like to offer an one-time contribution or join the team, [message Sexynes on Nexus Mods](https://www.nexusmods.com/stardewvalley/users/85287593) and state one's intention. See the Contribution Guidelines at the end of this file before you start your work.

### The Issues Tab
The [Issues tab](https://github.com/Hogwarts-Expansion-for-SDV/HogwartsWizardingWorld/issues) is located at the top of the page on the tab bar, the second from the left between Code and Pull Requests. Anyone can use it to report bug, request features, and see activity and updates regarding existing issues.

To **navigate existing issues**, search keywords or use the filter bar for specific filter suggestions. You can also view all issues of a particular type such as bugs, feature requests, and questions by choosing a label from the page linked next to the search bar.

To **report a bug**, press the green button that says _New Issue_ on the top right of the Issues page. Navigate to the green _Get Started_ button to the right of the _Bug Report_ option, and fill it out to the best of your ability.

To **request a feature**, press the green button that says _New Issue_ on the top right of the Issues page. Navigate to the green _Get Started_ button to the right of the _Feature Request_ option, and fill it out to the best of your ability.

## For Team Members
Head over to our wiki for [guides on how to use GitHub](https://github.com/Hogwarts-Expansion-for-SDV/HogwartsWizardingWorld/wiki/GitHub-Guide-for-Team-Members).

## Contribution Guidelines

### Development Strategy
At the moment, we are applying trunk-based development, committing straight to the trunk. Team members are expected to commit directly to the main branch (after testing to ensure their commit doesn't break the mod). Any pull requests are subject to approval. Only admins can create branches. Committing to any branches other than main should only be done under request of an admin. A team member's first commit after our migration to GitHub, however, should be done to their personal initial-* branch.

### Open a Discussion Before:
- Using third-party content. Include proof that you have explicit permission to use those assets (copy of their license, message from the author, etc.).
- Replacing an existing graphical asset. Include your alternative design in the discussion and @mention the original asset’s author. You must discuss which design should be in the final version; if you can’t reach a consensus or the original author isn’t responding, the community will vote on your designs.
- Starting work on a new C# feature. The C# part of this mod is designed to be superfluous and expendable; any game-changing features will be rejected.
- Adding content with new dependencies. Each new dependency is a liability once their author stops updating it.
- Adding narrative content. All storylines must be approved before being added to the mod.
All above discussions should be opened in the Ideas category.

### Do Not:
- Include any sort of sexual or discriminatory content
- Push your commits to main before testing the mod. If you get a SMAPI error, do not push until the error is resolved.

### Do:
- Make atomic commits. That means one change = one commit.
  - No commit should have two changes ("Added cowbane to Honeydukes and created a new wand")
  - A single change shouldn’t have multiple commits ("Added Distiller to Data/BigCraftables" and "Added Distiller to Data/Machines" are the same change: created Distiller).
- Write informative and succinct commit messages.
- Create new issues whenever you see a bug.
