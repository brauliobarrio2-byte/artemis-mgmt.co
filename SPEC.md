# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** Artemis Management Co. — a workplace app for scheduling, payroll, records, attendance, and communication. Today's preview covers the manager's schedule-approval screen.
- **Audience:** A department manager who needs to check a simulated schedule suggestion by department/role and approve it (or send it back) before employees see it.
- **Requirements:** One working primary interaction — viewing a sample weekly schedule with a simulated coverage suggestion and clicking Approve or Send back for edits; selected states and results are understandable; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping. This preview only shows the manager view (no employee/HR access, no live Wi-Fi or payroll integration yet). The schedule and coverage suggestion are pre-scripted sample logic, clearly labeled as a simulation — no runtime AI call, no external service.
- **Experience:** Dark grayscale base, blue accent color, structured card-based layout in the spirit of Monday.com — schedule grid plus coverage-suggestion panel, clear Approve/Send-back actions.
- **Test:** I can complete the main action (approve or send back the schedule), check one boundary (a schedule cannot show as "published" without a manager clicking Approve), and point to my standing rule's effect in the actual preview (marking an employee "out sick" visibly surfaces a suggested-coverage prompt, and the sample/simulated nature of the schedule and suggestion is visibly labeled). After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
