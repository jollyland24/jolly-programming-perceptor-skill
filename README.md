# cf-jolly-programming-perceptor-skill

## v1.0.0 Feedback
- it doesnt stop quizzing me about git and drift away from what i was learning

❯ /skill-programming-preceptor

⏺ Switching into preceptor mode — I'll guide rather than just answer
  from here on.

  You've been working through some solid git concepts today. Let me
  check your understanding:

  You deleted topic/fix-footer-label from remote, and your local branch
   was based on it. What do you think "based on" actually means in git
  terms — what happened when you first created your feature branch?

✻ Churned for 5s

❯ i think it has the same code and it tracks the changes from the
  first branch i created,

⏺ Good instinct! You're close. Let me sharpen it a bit.

  When you create a branch, git takes a snapshot of the code at that
  exact moment — it doesn't keep tracking changes from the original
  branch going forward.

  So if someone pushed new commits to topic/fix-footer-label after you
  branched off, your branch would not automatically get those.

  Does that change how you think about what "based on" means?

✻ Baked for 3s

❯ yeah

⏺ Can you put it in your own words now — what does "based on" mean?

✻ Cooked for 4s

❯ when create a local/remote branch, you take a screenshot of the code
   at that moment (with the past commits) and then from there it
  tracks the upstream code as well to compare your add on, and if it
  is local noones sees it but you and if it is remote your
  collaboraters see too

⏺ Really good! The "screenshot" analogy is spot on — that's exactly
  what a git commit is.

  One small thing to clarify: it doesn't automatically track the
  upstream branch. You have to explicitly set it (like you did today
  with --set-upstream-to).

  So why do you think it's useful to set an upstream? What does git use
   it for?

✻ Brewed for 3s

❯ it is good when your project has a branch that is the golden rule?

⏺ Interesting — say more about "golden rule" branch. What do you mean
  by that?


❯ it is the final

⏺ Yes! That's usually called the main or development branch — the
  source of truth everyone works from.

  So knowing that, why would you want your feature branch to track
  development as upstream specifically?

✻ Sautéed for 2s

❯ so i dont miss others' commits

⏺ Exactly! So when you run git pull, you get everyone else's latest
  changes from development into your branch — keeping you in sync.

  Now here's a question: what do you think could go wrong if two people
   edited the same line of code on their separate branches?

✻ Baked for 2s

❯ conflict

⏺ Yes! And what do you think git does when it hits a conflict — does it
   just pick one version, or something else?

✻ Brewed for 2s

❯ show u conflict and ask you to resolve

⏺ Exactly right. Git stops and asks you to decide which version to
  keep.

  Have you ever resolved a conflict before, or is that something you
  haven't run into yet?

✻ Churned for 2s

❯ no

⏺ That's fine — it'll happen eventually and it's not as scary as it
  sounds.

  When it does, one last question to prepare you: if you and a
  colleague both edited the same line, whose version should you keep?

✻ Brewed for 3s
