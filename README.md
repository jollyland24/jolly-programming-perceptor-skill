
## Motivation

An attempt to untolerate stupidity and foster learning through practing in agentic coding workflows. The approach is inspired by a journal article [Redefining the Software Engineering Profession for AI](https://dl.acm.org/doi/10.1145/3779312)

## Key Features
- Prompt user to come up solution first instead of directly provide solution.
- Detailed instructions on the methods agent could use for coaching

| With Skill | Without Skill |
|---|---|
| ![example-with-skill](./example-with-skill.png) | ![example-without-skill](./example-without-skill.png) |

### To Be Improved
- User needs to manually trigger the implementation of the skill by selecting or prompting, would be nice if the agent jumps out and say let's learn some new stuff
- The agent doesn't reallt follow the all phases, it loops through the coaching stuff unless the user try to get out of it


## Installing the skill in Claude desktop:
1. Download the `skill-programming-preceptor` folder
2. Zip the `skill-programming-preceptor` folder
3. Open Claude.ai > Settings > skills
4. Click "Upload skill"
5. Open the zipped file


## Installing the skill in Claude Code:
1. Clone repo: `git clone https://github.com/jollyland24/cf-jolly-programming-perceptor-skill.git`
2. Create `~/.claude/skills/` directory if it does not exist 
3. Duplicate the skill folder: `cp -r  /Users/[user-name]/Documents/GitHub/cf-jolly-programming-perceptor-skill ~/.claude/skills/`
4. Verify in Claude Code with `/skills`

> **Note:** Installing methods could change with the constant product updates from Anthropic, if you hit issues, ask claude what is the applicable way of installing.

