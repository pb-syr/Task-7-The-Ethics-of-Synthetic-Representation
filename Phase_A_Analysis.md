# Phase A: Ethical Analysis

**Task 7: The Ethics of Synthetic Representation**

Grounded in Task 6: Task_06_Deep_Fake and Task_06_Descriptive-Statistics-LLM

---

## 1. Return to What You Built

### Watching Storyboard_1.mp4 Again

I open the repository, download Storyboard_1.mp4, and watch it for the first time since I uploaded it. It runs about thirty seconds. Vertical. Silent. A cinematic sports montage with AI generated visuals of a female coach in orange and navy, a Syracuse themed athletic environment, gameplay sequences, animated captions, and broadcast style transitions. It looks like a highlight reel. It is not the interview I asked for.

That is the first thing that strikes me now, watching it from outside the making of it. The artifact is not what my prompt requested, and I did not fully register that at the time. My prompt asked for a TV style interview with an AI generated female Syracuse coach in a trophy room, delivering a specific script with real season statistics. Eighteen games, twelve wins, Megan Carney's forty five goals, eight goals allowed per game, the North Carolina comeback, Emma Ward as the potential game changer. CapCut returned something adjacent but different. A broadcast styled montage with no speaking coach, no interview structure, and no voice narration. I described AI generated voice narration in the output section of the second repo before I had actually confirmed the audio was present. When I watched it again just now, there was none.

I need to sit with that. I nearly published a description of an artifact that did not exist, because I trusted the tool's framing of its own output more than my own observation. That is not a small thing. It is the exact failure mode Task 7 asks me to reason about, except it happened to me, at the documentation layer, on a project where nothing was at stake. If I can misdescribe my own artifact in my own README, the capacity for misdescription at scale, by actors with incentives, audiences with less context, and distribution channels with no memory, is not hypothetical.

### What the Process Log Does Not Capture

The process log records the prompt, the script, the tools, the concept, and the observation that CapCut creatively reinterpreted the prompt. What it does not record is the moment I stopped paying attention. There was a point where I had a rendered video that looked professional, and I moved to writing the README. The README was written from the prompt and the intent, not from a careful second viewing of the output. The log says the AI generated a cinematic sports highlight video with realistic visuals. It does not say I noticed the audio was missing and decided to describe it anyway, because I did not notice. That gap between what I thought I had and what I actually had is the material Task 7 rests on, and it is not in the log.

The dominant feeling while building was relief. The tool produced something usable quickly, and the output looked better than I expected. That relief is the same affect that drives adoption of these tools across every professional context. It is also the affect that suppresses scrutiny. The smoother the output, the less likely I am to check whether it says what I asked it to say.

Where the tool refused or degraded is also worth noticing. CapCut did not refuse. It substituted. My prompt specified a two person interview format and the tool produced a solo cinematic montage. It specified a trophy room and the tool produced a mix of trophy room and gameplay footage. It specified audio that I did not clarify, and the tool defaulted to silent. Each of these is a degradation relative to intent, and none of them was surfaced to me as a limitation. The shape of these substitutions tells me something about what the vendor thinks is safe. A silent, non speaking montage cannot be accused of putting words in a real person's mouth. The tool's guardrails are not ethical commitments. They are liability minimizations, and they are invisible to the user unless the user is looking.

### Ethical Questions the Artifact Raises Even Though It Is Honest

The coach is AI generated and generic, so no individual's likeness is misused. But Syracuse University is a real institution. Its colors, its team, its athletic brand, and its conference identity are all rendered in this video without the university's knowledge or consent. The script attributes to a fictional Syracuse coach a set of real claims about the team's season and its future. The university did not agree to be represented by an AI coach, and the fact that the coach is fictional does not erase the fact that the brand is real. This is a distinct category of harm from individual likeness misappropriation, and I did not think about it once during Task 6.

The content is true. I verified the statistics in Task 5. But the artifact does not show that verification. A viewer who encounters the video without the repository README has no way to know whether the numbers are real, fabricated, or somewhere in between. The broadcast format, the confident captions, the professional transitions, the authoritative visual language, borrows the credibility of sports journalism without carrying its verification obligations. The medium asserts authority it cannot justify on its own.

Disclosure lives in the README, not in the artifact. The video itself carries no on screen label. If the file were re uploaded without the repository context, the disclosure would vanish. I treated disclosure as a property of the submission, not of the artifact, and those are not the same thing.

I also did not run a detection tool on Storyboard_1.mp4. I did not test whether any provenance metadata survived the export. I did not attempt to verify whether the file was signed, watermarked, or traceable. I did not test what happens to the artifact when it is re encoded by a platform. My Task 6 process log touches detection and provenance only nominally, and the nominal touch does not constitute a test. That gap is itself an ethical datum. I produced a synthetic artifact without doing anything to establish whether the mitigations the field relies on would have worked on it. I cannot now claim they would.

### Is There Anything I Would Not Build Again

Yes. I would not build a synthetic representation of a real institution's athletic program, even with true statistics, even with a fictional coach, without that institution's knowledge and consent. The distinction between a fictional individual and a real institution turns out to be less protective than I assumed when I started. The university's brand is a form of identity, and using it to lend credibility to a synthetic production is a form of representation that the university did not authorize. I would also not submit an artifact without rewatching it carefully against my own prompt before writing the documentation, because the misdescription I caught this time was accidental and could have been published as fact.

---

## 2. Reasoning Across the Axes

The axes below are anchored in what I actually built. A CapCut generated, AI coach, Syracuse branded, silent, thirty second vertical video, disclosed in the repository but not in the artifact, with real statistics but no verification, produced once over the course of a task with no detection or provenance testing.

---

### Truth Axis: Same Delivery, False Content

A regional sports blog wants to drive engagement during a slow news week. The blog's editor uses CapCut to produce a thirty second highlight reel in the same visual style as my Task 6 artifact. AI generated coach in team colors, broadcast captions, cinematic transitions, for a mid major program the blog covers. The script, like mine, is written to sound like a coach's season recap. But one number is fabricated. The editor inflates the team's win total from fourteen to nineteen, because a nineteen win season makes a better story. The blog posts the video with a two word caption, Season recap. No disclosure. No verification. The visual language is identical to my artifact. A rival program's fan account shares it. A local reporter cites the win total in a column. The number enters the discourse and does not come out.

The delivery mechanism is the same as mine. The difference is the payload, but the payload is not the point. The point is that the format carries no signal about the payload's truth. My artifact's broadcast style made true numbers feel authoritative. The same style makes false numbers feel authoritative. The tool did not distinguish between the two, and the visual conventions that signal sports journalism do not carry any actual verification. This is where I understand something my Task 6 process log did not register. The harm is not that the video is fake. The harm is that the register of professional sports media has been borrowed without the verification infrastructure that makes professional sports media trustworthy. The tool makes the register free. It does not make the verification free.

---

### Consent Axis: Same Delivery, Someone Else's Likeness

A recruiting analytics startup wants to sell its service to high school athletes and their families. To demonstrate reach, the startup produces a series of synthetic commitment videos, thirty seconds each, in my artifact's exact visual style, in which AI generated versions of real high school athletes announce their verbal commitments to particular universities. The athletes are public figures in the recruiting world. Their photos and stats are widely available. The startup uses those photos to condition CapCut's character generation. The videos are labeled AI generated demonstration in small text at the bottom. They are sent directly to families as examples of what the startup can produce for them. One of the athletes is a rising junior whose recruitment is still open. Her photo appears in a video committing her to a school she has not chosen. Her actual coaches see it. Her family spends a week correcting the record.

The disclosure is present, and it does not matter. The harm is not that viewers were deceived. The harm is that the athlete's identity was used to produce a claim about her future without her consent. The disclosure does not transfer consent. It transfers information, and information is not the same as authorization. This is where the technology moves from tool to weapon, and the movement is not in the tool. The tool did not decide to use her face. The movement is in the decision to use her face. My Task 6 artifact used a generic AI coach, so this decision was never made. But CapCut did not prevent it, and my artifact's visual style, the one that made my fictional coach look credible, is the same style that would make a synthetic commitment video look credible to a family. The consent boundary is where the capability's ethical weight actually lives, and it lives entirely in the human decision to cross it.

---

### Context Axis: The Label Stripped

My Storyboard_1.mp4 is disclosed in the repo README. A Syracuse fan account with forty thousand followers downloads it, crops the vertical frame slightly, re encodes it through a mobile video editor to remove any lingering metadata, and posts it to X with the caption New coach intro video. The account does not disclose that the video is synthetic. It does not know that it is synthetic. The account admin found it in a group chat where someone had reposted it from elsewhere. A mid tier sports newsletter picks it up. A beat reporter for a competing outlet emails Syracuse athletics to ask whether the coach in the video is real. The university's communications office has to respond. The artifact has traveled two hops from its repository, and the disclosure has traveled zero.

The label was never in the artifact. It was in the submission. The README, the repository, the context I controlled. Once the artifact leaves that context, the label is gone. My Task 6 process log treated the README disclosure as sufficient. It was sufficient for a reader of the repository. It was not sufficient for the artifact. This is the context axis, and it is not a hypothetical for my particular artifact. It is the most likely path my artifact would take if it circulated at all. The governance lesson is structural. Disclosure at the production end is a property of the channel, not the file, and the channel is not yours to control once the file is out. The university in the scenario did nothing wrong. It was collateral. That is what context stripping produces.

---

### Scale Axis: One to Thousands

A conference rival's creative team decides to compete for attention during recruiting season. Over one weekend, two staffers with CapCut subscriptions produce four hundred thirty second synthetic highlight reels, one for each recruit on their board, calibrated to the recruit's position, home state, and the program's pitch. Each video uses AI generated coaches and players in the program's colors, with captions drawn from the recruit's own public stats. Each is disclosed in the tool's default watermark, which is small, low contrast, and easily cropped. The staffers send them via direct message. The cost is roughly zero per video. The following week, a rival conference's compliance office tries to investigate, and discovers that the videos were produced on free accounts, the watermarks were cropped before sending, and there is no metadata to trace. The investigation cannot establish which videos were produced by the same actor, whether the actor was affiliated with a member institution, or whether any of the content is synthetic at all.

My Task 6 artifact took one prompt and one render. At scale, the render cost drops to zero, and the verification cost rises catastrophically. The scale axis is not just about volume. It is about the ratio of production cost to verification cost. Every mitigation I surveyed in Task 6, disclosure, provenance, detection, assumes a world where production is expensive enough that verification can keep pace. At four hundred videos per weekend, produced on free accounts, cropped before distribution, the verification assumption fails entirely. The scale axis is where the governance problem becomes structural rather than procedural. It is not that any single mitigation is weak. It is that the entire class of mitigations depends on a production to verification cost ratio that the technology has inverted.

---

### Fifth Axis: Institutional Identity

An athletic department's marketing office decides to celebrate a retiring coach with a tribute video. The coach is unavailable for filming. The office uses CapCut to generate a synthetic version of the coach, in the university's colors, delivering a farewell message written by the marketing team. The coach has verbally approved the idea of a tribute but has not reviewed the script. The video is disclosed as synthetic on the university's social channels. It goes viral. A rival fan base circulates it as evidence that the university cannot even get its own coach to show up. The coach, who has not seen the script, is asked in a press conference whether the sentiment reflects his actual views. He has to either endorse a script he did not write or publicly distance himself from his own tribute. Either way, the university's brand and the coach's identity have been used in ways neither authorized in detail.

My Task 6 artifact used a generic AI coach and a real university brand. I did not think of this as a consent problem because the coach was fictional. But the university is not fictional, and the brand is not a neutral visual input. It is an identity with stakeholders, reputational interests, and, in the case of a public institution, a relationship to the public it serves. Institutional identity is a distinct consent surface from individual likeness, and it is not governed by the same norms. Individuals have likeness rights. Institutions have brand and trademark interests, but those interests are commercial, not dignitary, and they do not map cleanly onto the ethical questions synthetic representation raises. The institutional identity axis is where my own Task 6 artifact's most distinctive ethical feature lives, and I did not see it until I tried to reason outward from the artifact to what it enables.

---

## 3. Survey of the Mitigation Landscape

Before proposing a policy, I have to be honest about what mitigations exist, what they promise, and where they break. I will also be honest about the limits of my own testing. In Task 6, I did not run a detection tool on Storyboard_1.mp4, and I did not test whether provenance metadata survived export or re encoding. I cannot report results I did not produce. What follows is what I can reason from my experience plus what I know of the field, with those gaps flagged.

---

### Disclosure Norms

Disclosure norms promise that labeling, watermarks, and on screen acknowledgments will tell the audience that what they are seeing is synthetic. The promise is that an informed viewer will adjust their interpretation, treat the artifact as representation rather than record, and discount its evidentiary weight accordingly.

In my own Task 6 work, disclosure was a property of the README, not the artifact. The video itself carried no on screen label beyond CapCut's small default watermark, which is easily cropped. The disclosure reached a reader of the repository and no one else. The context axis above shows what happens next. The artifact travels, the label does not, and the audience that matters is the audience that never saw the repo. Beyond the distribution problem, disclosure faces a comprehension problem. A viewer who sees a label that says AI generated may not know what that means for the content. Is the image synthetic but the claims true. Are the claims synthetic but the image real. Is any of it real. Disclosure is a necessary condition for ethical production, but it is not a sufficient condition for ethical reception, and it does not survive downstream re encoding.

---

### Provenance and Content Credentials (C2PA)

Provenance and content credentials promise that cryptographic signing and chain of custody metadata will let a viewer verify that an artifact was produced by a specific tool, at a specific time, by a specific actor, independently of the artifact's content. The promise is that provenance is verifiable even when content is not.

I did not test this in Task 6, and I should say so plainly rather than infer from the general literature. Based on what I know of the field, C2PA credentials are only as strong as the distribution chain that preserves them, and that chain is not under the producer's control. Platform re encoding, screenshotting, format conversion, and mobile editing apps all strip embedded metadata as a matter of course. CapCut's free tier does not sign outputs with C2PA credentials as far as I can determine. And critically, provenance is a voluntary standard. A bad faith actor does not need to defeat credentials. They only need to use a tool that does not add them. My artifact's provenance, if any existed, would not survive the first hop in the context axis scenario above. The provenance gap is not a technical problem awaiting a technical solution. It is an incentive problem, and the incentives currently favor the actor who strips.

---

### Detection

Detection promises that automated detectors and forensic techniques can identify synthetic media with high accuracy, allowing verification to be scaled and automated.

I did not run a detector on Storyboard_1.mp4. This is a real gap in my Task 6 work, and I flag it as a limitation of this survey. What I can say from the field is that detection is an arms race between generators and detectors, and the generators are currently winning. More fundamentally, detection answers the wrong question. It answers whether this was made by a machine, not whether I should believe this. A detected synthetic artifact may still be true. An undetected synthetic artifact may still be false. And detection is binary output on a probabilistic problem. A detector that is ninety five percent accurate produces five percent false negatives and five percent false positives, and at the scale described in the scale axis above, five percent is a catastrophe. Detection is useful for post hoc forensics. It is not useful for real time audience verification, and it does not address the truth axis at all.

---

### Legal and Regulatory Regimes

Legal and regulatory regimes promise that disclosure requirements, election adjacent restrictions, non consensual imagery statutes, and platform obligations will create legal liability for harmful uses, deterring bad actors and providing recourse for victims.

No law currently governs the production of an AI generated sports interview of a fictional coach representing a real university. If the coach had been real, non consensual likeness statutes might apply, but they are jurisdiction bound, unevenly enforced, and generally written for intimate imagery rather than the broader category of synthetic representation. Election adjacent restrictions are time bound and event specific. Platform obligations are only as strong as the platforms' enforcement appetite. The law is reactive, fragmented, and slow, and it addresses harms after they occur. My Task 6 artifact would not have been illegal under any proposed regime because it was honest and disclosed. The same mechanism, deployed differently, falls into a regulatory gap that the law has not yet closed. Legal regimes are necessary, but they are not sufficient, and they are not fast.

---

### Platform Policy

Platform policy promises that social platforms will label synthetic media, remove harmful content, and cooperate with researchers. The promise is that the distribution channel will police itself.

Platform policy is inconsistent across platforms, opaque in enforcement, and subject to commercial pressure. In my Task 6 experience, CapCut's own content policies constrained what it would generate. The tool substituted a montage for the interview I requested, which reads more like liability minimization than ethical commitment, but the constraints were invisible to me as a user. I could not audit them, and I could not predict them. On the distribution side, the platforms where my artifact might circulate have disclosure toggles that are easy to miss and enforcement that is inconsistent. The gap between commitment and enforcement is not a bug in platform governance. It is a feature of platforms whose business model rewards engagement over verification.

---

### Professional and Organizational Norms

Professional and organizational norms promise that journalism, entertainment, advertising, education, and political consulting will articulate their own standards for synthetic media use, filling the gap where law and platform policy fail.

Professional norms are voluntary, unevenly adopted, and weakly enforced. They depend on professional communities with shared values and mutual accountability. My Task 6 work was produced in an academic context with no professional norm governing it. No disclosure standard, no consent workflow, no review process. The norms that exist in journalism and advertising are aspirational rather than operational, and they do not extend to the actors most likely to cause harm at scale. Professional norms are a useful starting point, and they are what a policy for a real organization will operationalize. But they are not a substitute for governance, because they do not bind anyone who has not chosen to be bound.

---

## Summary of Phase A

The artifact I built in Task 6 was honest, disclosed in its repository context, and used a generic AI coach rather than a real person's likeness. It was also built without detection testing, without provenance testing, without a clear understanding of where the disclosure actually lived, without institutional consent from the university whose brand it used, and without any recognition that CapCut had silently substituted a different artifact than the one I asked for. Each of those omissions is a small thing in a class project. Each of them scales, when the same mechanism is deployed by an actor with different intentions, into a category of harm that no single mitigation on the landscape above can contain.

The policy in Phase B is written for a specific organizational context, one whose constraints I can describe concretely, and one whose operations are close enough to my own Task 6 work that the analysis above translates directly into governance. The context I have chosen is a university athletics communications office, because it is where my artifact's distinctive ethical feature, institutional brand representation without institutional consent, becomes an operational question rather than a thought experiment.
