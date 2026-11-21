# Build Your First App with AI — Starter Kit

**Draft: the full setup has not yet been tested with learners.** This template prepares a Python workspace; it is not a finished app. You'll create your own copy, open it in GitHub Codespaces, and use an AI coding agent to help you build.

## What you'll need

- A computer, internet access, and an eligible [GitHub account](https://github.com/).
- GitHub Codespaces. Personal accounts include a monthly allowance; check [current limits and billing](https://docs.github.com/en/billing/concepts/product-billing/github-codespaces) before enabling paid usage.
- Your own eligible account for **Codex** or **Claude Code**, with access to the IDE extension. Check current plan costs, limits, and terms.

**Age and account rules:** GitHub requires users to be at least 13, or the applicable local minimum. [OpenAI's individual terms](https://openai.com/policies/terms-of-use) require users to be at least 13 or the applicable local minimum, with a parent or guardian's permission under 18; Codex IDE availability for teen accounts remains to be verified. [Anthropic's consumer terms](https://www.anthropic.com/legal/consumer-terms) require users to be at least 18, or older where local law requires. Do not share accounts or credentials to work around these rules. Check current terms before registering.

## 1. Create your own repository

The starter is the course's source template. Your copy is a **separate project under your account**; your changes do not change the original.

1. Open the [starter template](https://github.com/lemonadeliteracy/app-firstapp-starterkit).
2. Select **Use this template → Create a new repository**.
3. Choose your own account as owner and give the repository a name, such as `my-first-app`.
4. Select **Private**, then **Create repository**.
5. Confirm that the new repository belongs to your account and contains the starter files.

A private repository is not a secret vault. Never put passwords, tokens, API keys, personal information, confidential information, or client details in project files or prompts.

## 2. Open your repository in Codespaces

1. On **your new repository**, select **Code → Codespaces**.
2. Select **Create codespace on main**, or the equivalent create button.
3. Wait for the browser-based editor to open and the environment build and dependency installation to finish.
4. Open **Explorer** and check that you can see your project files.

The configuration uses Python 3.12 and installs [Streamlit](https://streamlit.io/) for the app interface and [Requests](https://requests.readthedocs.io/) for public data connections. It forwards port 8501 for an app you build later. There is no app in the starter yet.

If you need to return later, open [your Codespaces](https://github.com/codespaces) and reopen the existing one. Stop it there when you're finished; closing the browser tab may not stop it immediately. Files in a Codespace are **not automatically committed and pushed** to GitHub—review and save changes using Source Control during the course.

## 3. Connect an AI coding agent

Choose one option. The extension and its account are separate: installing an extension doesn't create or pay for an account.

1. In the Codespace editor, open **Extensions**.
2. Find and install one of these official extensions in the Codespace:
   - **Codex**, published by OpenAI — identifier `openai.chatgpt`. See the [Codex IDE guide](https://learn.chatgpt.com/docs/codex/ide) and [pricing](https://developers.openai.com/codex/pricing).
   - **Claude Code**, published by Anthropic — identifier `anthropic.claude-code`. See the [Claude Code VS Code guide](https://code.claude.com/docs/en/vs-code). Anthropic documents an eligible paid Claude subscription or Claude Console account for the extension.
3. Open the agent's panel and follow its sign-in instructions using your **own eligible account**. If an icon isn't visible, open the Command Palette and search for the agent.

**Not yet verified:** installation, sign-in and operation of either extension in this starter's browser-based Codespace. If an extension doesn't install or start, ask the organizer for help. Do not enable privileged containers, disable security controls, or share credentials to bypass the problem.

## 4. Ask your first question

Once your agent is open in your project, try:

> I'm learning to build my first app. Explain only the tracked starter files `README.md`, `requirements.txt`, `.gitignore`, and `.devcontainer/devcontainer.json` in beginner-friendly language. Do not read secrets, credentials, environment files, or untracked files. Do not change or run anything.

Compare the answer with the files in Explorer. If the agent asks to change files or run commands, decline for this exercise. Its answer may be incomplete or wrong; check what it says.

## Ready for Saturday?

- [ ] I created my own private repository from the starter.
- [ ] I can open that repository in a Codespace and see its files.
- [ ] I checked account eligibility, age rules, and costs for my chosen agent.
- [ ] My agent can describe the starter files without changing them.
- [ ] I know how to stop and reopen my Codespace.
- [ ] I know not to put personal or confidential information, passwords, tokens, or keys in prompts or files.

If you get stuck, note the step and ask the course organizer for help. Don't send sign-in codes, credentials, personal details, or screenshots containing them.

## Later: run your app

When the course has helped you create an `app.py` file, run `python -m streamlit run app.py` in the Codespace terminal. Before opening or sharing a preview, check that its port is marked **Private** in the Ports tab.

`.gitignore` excludes some common secret files, but it cannot catch every credential and does not stop an agent from reading files. Review what you share and commit.

## References

- [Create a repository from a template](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
- [Create a Codespace for a repository](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository)
- [GitHub Terms of Service](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service)
