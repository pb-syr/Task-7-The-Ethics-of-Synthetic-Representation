# Task 07: The Ethics of Synthetic Representation

## Task Description

This repository contains my Phase A ethical analysis and Phase B policy document for Research Task 7. The task asked me to reason systematically about the ethical implications of the synthetic media capability I exercised in Task 6, and then to produce a governance document that a real organization could adopt to use or refuse that capability responsibly.

Phase A is the reasoning. Phase B is the artifact. Both are required, and both are grounded in what I actually built in Task 6 rather than in a survey of news stories.

## Task 6 Work This Builds On

My Task 7 analysis is grounded in two repositories from Task 6:

- [Task_06_Deep_Fake](https://github.com/pb-syr/Task_06_Deep_Fake) contains the final artifact, Storyboard_1.mp4, a thirty second silent vertical synthetic sports video generated with CapCut AI Video Generator.
- [Task_06_Descriptive-Statistics-LLM](https://github.com/pb-syr/Task_06_Descriptive-Statistics-LLM) contains the project concept, prompt engineering, and script used to produce the artifact.

Both repositories document the construction of a synthetic sports interview representing Syracuse Women's Lacrosse, using an AI generated coach and real season statistics.

## Organizational Context Chosen

I chose a university athletics communications office as the setting for my policy. The choice is deliberate. My Task 6 artifact used a real university's brand, real player names, and real season statistics, all rendered through an AI generated coach that the university did not authorize. That specific ethical feature, institutional brand representation without institutional consent, becomes an operational question inside an athletics communications office rather than a thought experiment. The office has real employees, real audiences, real reputational stakes, and a real temptation to use tools like CapCut for rapid content production. A policy written for this setting can be concrete, specific, and adoptable on a Monday morning.

## Repository Map

- [phase_a_analysis.md](phase_a_analysis.md) contains the Phase A ethical analysis. It opens with a fresh look at my Task 6 artifact, reasons outward across five axes of ethical concern, and surveys the mitigation landscape with honest notes on what I did and did not test.
- [phase_b_policy.md](phase_b_policy.md) contains the actual policy document, written for a university athletics communications office. It takes positions on permitted uses, prohibited uses, consent workflow, disclosure standards, provenance requirements, review and approval, incident response, and conditions for refusal.
- [limitations.md](limitations.md) contains an honest account of where the policy fails, what residual risk remains, and where the policy depends on good faith.

## What Surprised Me

Two things surprised me while writing this task.

The first was how easily I had misdescribed my own Task 6 artifact. I wrote in the Task 6 README that the video contained AI generated voice narration, before I had actually confirmed the audio was present. When I watched the artifact again for Task 7, it was silent. That small documentation failure, on a project where nothing was at stake, taught me more about the scale of the synthetic media problem than any article I could have read. If I can misdescribe my own work in my own README, the capacity for misdescription at scale by actors with incentives is not hypothetical.

The second was how much of the ethical weight sits in the institutional brand rather than the individual likeness. My Task 6 artifact used a generic AI coach, so no person's likeness was misused. But Syracuse University is real, and its colors, its team, and its players' statistics were used to lend credibility to a synthetic production the university did not authorize. I did not see that as a consent problem until I tried to reason outward from my own artifact. Institutional identity turns out to be a distinct consent surface, and it is not governed by the same norms as individual likeness rights.
