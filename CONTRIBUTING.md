# Contributing
 
Thank you for helping with AgenTrust Develop for Good. This page explains how to get your work into the repo. You do not need to be an expert in Git to follow it.
 
## Before you start
 
- You need a GitHub account, and the project owner must have added you to this repo. If you cannot push to it, ask in the team channel.
- Read the [README](README.md) so you know what we are building.
- Install AgenTrust and try it. Write down anything that confused you. Those notes help us improve the volunteer docs.
## Pick a task
 
1. Open the **Issues** tab, or the project board.
2. Choose an issue with your name on it. If nobody has been assigned, comment "I'll take this" and wait for a reply.
3. Read the issue. It says what the finished work looks like ("Done when").
If you are stuck, ask in the team channel, so other people can see the answer.
 
## Make your changes
 
Do not edit `main` directly. Work on your own branch.
 
1. Create a branch from `main`. Use a short, clear name:
   - `guide/iso-42001`
   - `demo/gdpr`
   - `docs/getting-started`
2. Make your changes. Keep each commit small and give it a clear message, for example `Add ISO 42001 table rows 1 to 10`.
3. Commit often. Small commits are easier to review than one large one.
## Send your work for review
 
1. Open a pull request from your branch into `main`.
2. Fill in the pull request template.
3. Link the issue, for example `Closes #12`.
4. Ask your **review partner** to check it. Reviews are done in pairs:
   | Author | Reviewed by |
   |---|---|
   | ISO 42001 | NIST |
   | EU AI Act | GDPR |
   | GDPR | EU AI Act |
   | NIST | ISO 42001 |
   | Getting-started guide | Project setup |
   | Project setup | Getting-started guide |
5. Answer every review comment, then mark the conversation as resolved.
6. When you have the required approval, the pull request can be merged.
## When you review someone's work
 
- Read it as a newcomer would. Is anything unclear?
- Check that it follows the guide format below.
- Check that every claim about a law or standard points to the source.
- Be kind and specific. Say what to change and why.
## How a guide looks
 
Every guide is built around one table with one row per rule:
 
| Rule | How AgenTrust helps | Proof it leaves | Covered? |
|---|---|---|---|
| The rule, with its article or clause number | The AgenTrust feature that handles it | The record or evidence it produces | Yes, partly or no |
 
After the table, add:
 
1. Short setup steps.
2. A list of what AgenTrust does **not** cover.
A template is available in the `guides/` folder.
 
## Writing style
 
- Use plain words and short sentences.
- Explain any acronym the first time it appears.
- Cite the exact article or clause when you mention a rule.
- Be honest about gaps. "Partly" or "no" in the Covered column is useful information.
- Do not copy text from paid standards (for example the full ISO 42001). Summarize in your own words and link to the public overview.
## Demos
 
- Each demo goes in its own subfolder inside `demos/`.
- Include a `README.md` with the steps to run it. Someone new should be able to start it from your steps alone.
- Use fake data only. Never include real personal data, passwords or API keys.
## Weekly rhythm
 
- **Tuesday, 1 pm PT:** team meeting. Say what you did, what is next and whether you are stuck.
- **Friday:** post your progress in Slack.
- **Running behind?** Tell the team lead by Friday. Asking early is always fine.
## Code of Conduct
 
Everyone taking part must follow the [Code of Conduct](CODE_OF_CONDUCT.md).
 
## License
 
By contributing, you agree that your work is released under the [Apache License 2.0](LICENSE).
 
