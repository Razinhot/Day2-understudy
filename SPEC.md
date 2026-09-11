# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page daily-learning planner that suggests one personalized 30–90 minute lesson and displays it as a daily task list.
- **Audience:** Curious students and learners who want to build knowledge around their interests, current classes, and career goals.
- **Requirements:** Visitors enter interests, classes, career goals, and a pasted weekly schedule; choose a 30–90 minute duration with a slider; then generate a clear daily lesson/task. Selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code only. No required external service, keys, accounts, runtime AI, private data, or real calendar connection. Treat schedule entries and lesson suggestions as sample planning content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Visually playful and interactive, with a friendly planner-like layout, colorful duration scale, and animated-but-reduced-motion-safe result cards.
- **Test:** I can enter sample learner details, choose 30 minutes and 90 minutes, generate a daily task each time, and see that the result respects my standing rule in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
