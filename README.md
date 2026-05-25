### Key Features

- Prompt user to come up solution first instead of directly provide solution.
- Detailed instructions on using Socratic dialogue and guided reasoning in coaching.

### For Claude Desktop users:

1. Download and Zip `skill-programming-preceptor` folder
2. Go to "Claude.ai > Settings > skills"
3. Click "Upload skill"
4. Upload the zipped skill file
5. Verify in the "Add" button - available plugins


### For Claude code CLI users:

1. Clone repo: 
   ```
   git clone https://github.com/jollyland24/cf-jolly-programming-perceptor-skill.git
   ```
2. Check if the skills directory exists; create it if not

   ```
   [ -d ~/.claude/skills ] || mkdir -p ~/.claude/skills
  ```
   
4. Move the skill to the skill directory:
   ```
   cp -r  /Users/[user-name]/Documents/GitHub/cf-jolly-programming-perceptor-skill/skill-programming-preceptor ~/.claude/skills/
   ```
5. Verify in Claude Code from `/skills`

> **Note:** Installing methods could change with the constant product updates from Anthropic
