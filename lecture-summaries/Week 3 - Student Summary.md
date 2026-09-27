# ISL301 Week 3 Summary: Bias in Algorithms, Terminology and Privilege in Design

Class of Wednesday, September 23, 2026. This recap complements the Week 3 slides and what was said in class. It is not a replacement for either. Use it to check your understanding, to look back at Lab 2, and later to study for Test 1.

## The one question this course keeps asking

**Who does this system work for, and who does it exclude or harm?**

Week 2 was what good looks like: what we should do. Week 3 was where the barriers actually are: in the algorithms that decide, in the words we write into code, and in the assumptions designers carry in without noticing.

## What we covered

1. Finishing week 2: the avatars case study, with The Sims 4 as the example
2. Finishing week 2: the iPhone Duo, who benefits and who is left out, and three changes before launch in pairs
3. A review of the eight principles and of week 2
4. Systemic inequities, and where bias gets into an algorithm
5. Credit scoring: the Canadian example
6. Case study: facial recognition in Canada, what was claimed and what was measured
7. What Canada has already done with facial recognition, who pays for a false match, and six checks before going live
8. Bias in hiring algorithms, a callback to week 1
9. The power of terminology: which words made you stop, and who changed the words
10. Privilege in design: three Canadian apps, and the consequences
11. This week's story: the 911 outage of September 17
12. The online exam, in pairs
13. Three questions to take with you, what you do with this, and the key takeaways
14. One assumption you will now look for, asked aloud after the break
15. Lab 2: Figma Personas, Meet Real Canadians, started in class and due on Blackboard Friday, September 25, at 11:59 PM

Everything on the agenda was covered, including the question we missed in week 2.

## Ground rules

Unchanged from week 1 and in force all term. The one that mattered most this week: critique the design, not the person. In the terminology part, nobody is shamed for a word they were taught. The goal is to notice the impact and choose the clearer word.

## Finishing week 2

### Avatars and female characters in games

A 2016 study coded 571 games with playable female characters, released from 1983 to 2014. Coded means the researchers went through each game and recorded what the characters looked like and did. Sexualisation of female characters peaked in the 1990s and has fallen since. Fighting games remain far more sexualised than role-playing games, so it depends on genre, not just on year. Secondary female characters (the sidekick, the reward, the one you rescue) were far more sexualised than leads.

The case study asks three questions, and they are not the same question:
- **Can people see themselves?** The character creator: skin tone, hair, body type, gender presentation, pronouns, age, disability, mobility aids, facial features. Leaving an option out is a decision too.
- **Can they use it?** Representation is not enough if the game has tiny text, clues that depend on colour, no captions, controls that need two fast hands, or hardware that costs a month's rent. A player who sees themselves on the character screen and cannot read the subtitles has been invited in and then locked out.
- **Do they feel welcome?** Voice-chat pressure, harassment and moderation that does nothing push out people the character creator invited in. The report button, the mute default and the moderation budget are design decisions, and they decide who stays.

The Sims 4 was the worked example. Over a hundred skin tones were added in 2020, after players had asked for years; custom pronouns in 2022; a textured hairstyle made with the hair care brand Dark and Lovely in 2024. Players made their own wheelchairs for their Sims as add-ons, which raises the question of why they had to. Every option added later is someone who was left out before. And the first avatar on the screen is the designer's guess at who is playing; most players never change it.

### The iPhone Duo

Apple announced its first folding iPhone on September 9: a 7.6-inch display open, a 5.4-inch display closed, pre-orders October 16, on sale October 23, starting at 1,999 American dollars. We were not there to decide whether Apple is good or bad. It is the newest product in the world to ask the course question of.

Does a bigger screen automatically mean better accessibility? No. The screen is the hardware; accessibility is mostly software. Layout, focus order, controls and text scaling decide it. If an app stretches its layout, the text is the same size in a bigger box. If a screen reader loses its place when the display changes from outer to inner, the user is back at the top of the page every time.

Who could face barriers: price first, because a product can be innovative and still be out of reach for most people (add financing, regional availability, repair cost, warranty and battery life); physical handling (the hinge, the grip and strength needed to open it, the weight, one-handed use, reaching across a bigger screen); and apps, which have to work folded and unfolded, and which Apple mostly does not write. A launch announcement does not tell us how a screen reader, magnification, captions, voice control or hearing devices behave across the fold. Every one of those is a question for the testing stage.

In pairs you chose three changes or tests before launch. "Make it more accessible" is not a change. "Test screen-reader focus across the fold with three blind users before launch" is: it has a person, a barrier, and a way to know it worked. Inclusive design does not say do not innovate. It says be honest about who can use the product, who faces barriers, and what choices the team is making.

## Key definitions

**Systemic inequity.** Patterns of disadvantage built into the structures and processes of institutions and systems. Unlike individual bias, they live in the policies, the procedures and the technologies themselves. Nobody has to hold the bias for the system to produce it. That is structure over intent, principle three, applied to code. The three Canadian examples on the slide (employment platforms that filter out Indigenous names, educational software only in English, health apps that ignore cultural differences in health practices) are often cited without sources, so treat them as directions to look in, not as measured findings.

**Algorithmic bias.** A computer system that reflects or amplifies human bias and produces unfair outcomes for certain groups. It looks objective; it was built by people and trained on the past. An algorithm has no opinion about anyone, so if the output is unfair, the bias got in somewhere other than the arithmetic. The four places it gets in are week 1's choice points:
- Built by people with unconscious biases: which problem gets solved, and for whom.
- Trained on historical data that reflects past discrimination: whose data. For a model, the past is the only room it is ever in.
- Designed with limited perspectives: the defaults, set by whoever was in the room.
- Optimised for a metric that can disadvantage minorities: who bears the errors. A model tuned for the average is wrong most often at the edges.

"The algorithm is just math" is true, and the math is the smallest part. The data, the target it optimises, the threshold, and who checks the output are all decisions.

**Credit invisibility.** Having no credit file at all. A model that reads "no history" as "risk" is not judging whether you pay your bills; it is judging whether you have a history in its database. That is a default (the wall, principle four), and the person it excludes did nothing wrong.

**Proxy signals.** A hiring tool never has to ask about race, gender or language to produce unequal results. It uses signals tied to them: a name, a school, a club, a postal code, a gap in the dates, the wording of a degree from abroad. A system with no race field can still produce a race gap, which is why "we removed the protected attributes" is not an audit.

**Two kinds of language barrier.** One is a word with a history: "master" and "slave", "blacklist" and "whitelist", "grandfathered" (from the grandfather clauses of the 1890s in several southern American states, which exempted men from literacy tests if their grandfathers could vote, so white men could vote and Black men could not). The other is a word nobody explained: jargon and insider language that shuts out newcomers to Canada, women entering tech, and first-generation students who did not grow up immersed in computing culture. The first is fixed by choosing another word ("primary" and "replica", "allowlist" and "blocklist", "legacy"), which is usually the better engineering word too. The second is fixed by the person who already knows the word explaining it.

**Design privilege.** When creators unconsciously design for people like themselves, making assumptions about users' abilities, experiences and contexts that exclude others. The tells: assuming high-speed internet, designing only for the latest devices, using cultural references from dominant groups, putting convenience ahead of accessibility, building in only one language. It is last week's default user, seen from the designer's chair. Nobody decided to exclude these people. Nobody decided not to. That is the difference between an accident and a default.

**A second route.** A fallback that works for the person least able to find it. A second route the caller has to discover during the failure is not a second route. Diverse service routes are an equity feature, and they have to exist before the night they are needed.

**A requirement about the task, or about your house.** The online exam test: a requirement is fair when it is about what the task checks. A requirement that is really about the student's living situation is a barrier (the wall, principle four).

## Case studies and examples from class

### Credit scoring in Canada

More than 2.5 million adults in Canada are credit invisible, with no file at all, and about seven million more have a thin file of two accounts or fewer (Equifax Canada figures, reported September 2, 2026). Statistics Canada found 14.8 percent of immigrant families in Canada under two years are credit invisible, against 7.5 percent of Canadian-born families. A British Columbia man found his score reset to zero in 2025 after a few years without borrowing. The gap closes after two to four years in Canada, and those are exactly the years a newcomer rents an apartment, gets a phone plan and buys a car. The original slide also names Indigenous people and rural communities; the study measured immigrants, so that part is a direction, not a finding. A lender does need some history, and the question is what counts: rent, phone bills and utility payments exist and are usually ignored. That is a default.

### Facial recognition in Canada: claimed versus measured

The case-study page says facial recognition misidentifies Indigenous and racialised Canadians at rates "up to 10 times higher" than white individuals. I could not find the study behind that figure, so it is labelled, not repeated as fact. What was measured:
- **Gender Shades, 2018.** Three commercial gender classifiers, tested on faces balanced by gender and skin tone. Error up to about 35 percent on darker-skinned women, under 1 percent on lighter-skinned men. It did not test Indigenous faces, and it tested gender labelling, not identification.
- **The United States National Institute of Standards and Technology test, 2019.** 189 algorithms from 99 developers on 18 million images. False-positive rates differed across demographic groups by factors of 10 to more than 100. On police mugshots, false positives were highest for American Indian faces and elevated for Black and Asian faces; two to five times higher for women than men; higher for the elderly and children. The most accurate algorithms showed much smaller differences.

Hold three things at once: the direction of the claim is supported, the ten-times figure has no study behind it, and neither study measured Indigenous faces in Canada. Say what was measured, not what you heard.

**What Canada has already done with it.** In May 2019 the Canadian Civil Liberties Association asked Toronto's police board to stop using facial recognition until there were rules for it, calling it "carding by algorithm". From October 2019 to February 2020 some Toronto police officers used Clearview AI, a tool built on three billion photos scraped from the web, in 84 investigations, before the chief learned of it and ordered a stop. On February 3, 2021 the Privacy Commissioner of Canada and three provincial commissioners found Clearview's collection was mass surveillance and illegal under Canadian law. On June 10, 2021 the Royal Canadian Mounted Police's use of Clearview was found to violate the Privacy Act. Since January 2026 Montreal's transit agency has run artificial-intelligence cameras at two Metro stations to flag people lingering before closing; it says no facial recognition is used. On April 20, 2026 Metrolinx started body-worn cameras on its officers at Union Station. The case study says Metrolinx has "explored" artificial-intelligence camera monitoring; nothing beyond the body-worn cameras could be verified, so say explored, not deployed.

**Who pays for a false match?** Suppose the software matched you at Union Station, and it was wrong. In the next ten minutes you are stopped and questioned by someone deciding whether to believe you or the screen; you miss your train, which is the smallest cost; and nobody can tell you whether the flag is deleted afterwards. "A human checks" is a good answer, until you ask how long a human takes to overrule a machine that is usually right. The communities with the highest error rates are often the ones that already trust the police least: hit twice, which is intersectionality, principle two.

**Six checks before letting it go live.** Every one is a testing-stage question from week 2's lifecycle:
1. Test accuracy on the people who will be in front of it, by group and by sex within group, not the vendor's benchmark.
2. Check the training data: who is in it, who is not, and where it came from.
3. Audit false positives and false negatives separately. A false positive stops an innocent person; a false negative misses a real one. They fall on different people.
4. Involve the affected communities before deployment, with the power to say no. Design with, not for.
5. Limit high-stakes use. A match is a lead for a human to check, never a decision on its own.
6. Give people a way to challenge a match: who to call, what they see, how fast it is fixed, and whether the record is deleted.

An error rate is not just a technical number. The harm depends on who is more likely to be misidentified, and on what happens after the system is wrong.

### Bias in hiring algorithms

Screening tools learn from historical hiring data. If the people hired before were chosen through biased processes, the tool learns to prefer people like them, at every employer that buys it. A Stanford study published May 26, 2026 looked at four million applications to 150 employers: 26 percent of Black applicants, and 15 percent of Asian applicants, applied to positions where one vendor's tool discriminated against their group, and about 40,000 more of their applications would have advanced at equal recommendation rates. Amazon's tool, built from 2014, was trained on ten years of mostly male resumes, penalised the word "women's" (as in "women's chess club captain"), and was scrapped by 2017. In Canada the groups often named are newcomers, Indigenous candidates, francophone applicants and women, without figures. Since January 1, 2026, an Ontario job posting must say if artificial intelligence is used to screen applicants. A "2023 study of Canadian tech companies, 23 percent" is also often cited; I could not find it, so it is not presented as a fact.

### Which words made you stop, and who changed them

Most of you have typed `git push origin master` without thinking about it. The word is invisible until it is not. What has changed, and when: Python removed "master" and "slave" from its documentation and code in 2018; the Linux kernel's coding-style guide asked for "primary/secondary" and "allowlist/denylist" in new code in July 2020; GitHub made "main" the default branch name for new repositories on October 1, 2020. Shopify, Cohere, the University of Toronto, the University of British Columbia and McGill are often named as adopters, and Canadian banks, telecommunications companies and government agencies are often said to have inclusive language policies; I could not confirm any of them, so they are labelled as unverified. A word change costs almost nothing, and it is not the same as removing a barrier. Do it, and then do the harder thing too: compliance is the floor, not the goal, principle seven.

### Three Canadian apps, and the consequences

A provincial health app, a food delivery app, a banking app: who was each built for, and who is standing outside? "Old people" is a category; "my grandmother, who has a flip phone and reads Greek" is a person.
- **Language-centric apps.** Many government and health apps are designed in English first, with French and other languages as afterthoughts. Outside: Quebec residents, newcomers, speakers of Indigenous languages.
- **Urban-focused services.** Food delivery, transit and ride-sharing apps optimise for dense cities and serve rural and remote communities poorly, including many reserves. Outside: the one in three households on First Nations reserves that cannot get fast home internet at all.
- **Banking apps.** Digital banking assumes traditional employment, a credit history and documentation. Outside: newcomers, gig workers, people without a bank account. The credit-invisible example, from the other side of the counter.

The consequences, as two lists of assumptions. Provincial health apps often assume a permanent address, a traditional family structure, familiarity with medical terms and reliable internet, which excludes people without housing, Indigenous communities with different kinship systems, and rural people with limited connectivity. Online learning built during COVID-19 assumed a dedicated study space, high-speed internet, a personal device and a quiet room, which excluded students in crowded housing, students sharing a device with siblings, and families with limited resources. Many of you lived the second list in 2020. When we do not design inclusively, we do not just miss users; we actively exclude them from participating in digital society. Both lists are often cited without figures.

### This week's story: the 911 outage

On Thursday, September 17, at 3:13 in the morning, Bell's next-generation 9-1-1 network failed. Bell runs 9-1-1 for Ontario, Quebec, Manitoba and Atlantic Canada, so six provinces were affected: Ontario, Quebec, Manitoba, Nova Scotia, New Brunswick and Prince Edward Island. Service was restored at 4:40, one hour and 27 minutes later. Bell says it was not a cyber attack, and it has 14 days to report the cause to the Canadian Radio-television and Telecommunications Commission. A backup system rerouted most calls from Bell customers automatically, so most people never knew. No death or injury has been reported.

Police told everyone else to call a non-emergency line, use a landline, use Wi-Fi calling, or try a phone on another carrier. Who could not follow those instructions at three in the morning?
- A landline: many households, especially younger ones, do not have one.
- Wi-Fi calling: needs Wi-Fi at three in the morning, a phone that supports it, and knowing it exists.
- A phone on another carrier: most households are on one carrier, and most people are alone at that hour.
- A ten-digit non-emergency number: a newcomer who has never heard of the Ontario Provincial Police; anyone in crisis who cannot look up a number; a child taught to dial three digits.
- Text with 9-1-1: the route Deaf, hard-of-hearing and speech-impaired callers register for. It runs on the same 9-1-1 network, and nobody has said how it behaved that night.

The landline and single-carrier points are a reading of the room, not statistics. Most people were given a second route automatically. The people least able to find one were told to find it themselves. The question is not what broke; it is who had a second route, and who did not.

### The online exam (pairs)

A course makes you write its final exam online, and you need four things: a webcam on the whole time, fast and stable internet, a quiet room with nobody else in it, and a laptop of your own. The exam exists to check two things: that you did the work yourself, and what you know. Which of the four are about the exam, and which are about your house?

All four are about your house. The webcam stands in for trust, and only works if you have a private room to point it at. The exam does not need fast internet; the delivery method does. Nothing about the exam needs silence. The exam needs a screen, not ownership. Each one stops someone: anyone without a room of their own, one in three households on a reserve, anyone caring for someone at home, the family with one computer. A fairer version keeps the same exam and the same standard: a longer window and flexible timing, a booked quiet room and a machine on campus, a low-bandwidth option or an in-person sitting, privacy information in plain words, another format where the format is the barrier. Same exam, same standard, different inputs: last week's same-form scenario, on a case you have all lived.

## Three questions to take with you

Not for class; for the bus home, and for the next time you build something.
- **Personal bias detection.** An app or tool you use every day: have you noticed a feature that would work differently for someone with a different background, ability or circumstance than yours?
- **Canadian platform analysis.** A Canadian platform you have used (a government service, a banking app, the college's systems): how might privilege show up in its design, and who might face extra barriers?
- **Language impact.** A term from your computing courses: has it made you, or someone near you, feel excluded? What would be a better word?

Ask them of someone from a different background than yours. Their answer might reveal a bias you had not noticed. That is diversity as an engineering method.

**What you do with this.** Three habits for your projects and your career. Recognise systemic inequities: the eye for bias in algorithms, exclusionary design patterns and harmful terminology. Audit for bias: test with diverse users, examine your data for representation, use bias-detection tools, and know that a tool does not replace judgement, context, lived experience, or listening to the people affected; make bias testing a standard part of development, not a launch-week panic. Design inclusively: inclusive terminology, diverse abilities and contexts, and the communities affected in the design process from the start. The goal is not to eliminate all bias. It is to be aware of our biases and actively work to create more equitable systems.

## Key takeaways

- **Algorithmic bias affects real people,** through hiring, recognition and service systems. The arithmetic is neutral; the data, the defaults and the metric are decisions.
- **Language choices include or exclude.** A word with a history, or a word nobody explained. Both are fixed by the person who already knows, and neither fix removes the harder barrier.
- **Design privilege excludes users unlike the creators.** Health apps, online learning, banking, transit: nobody decided to exclude, and nobody decided not to.
- **Canadian institutions have made changes.** Four privacy commissioners ruled Clearview's face database illegal. Toronto police stopped using it. Ontario now requires job postings to say when software screens applicants. Real, recent and verifiable.

Eight principles, three places to look: the algorithm, the words, and the designer's chair.

## The eight principles

No new principle this week. Cite them by name; the number is a shorthand, not a substitute.

1. **Technology is not neutral.** Check the five choice points: problem, data, defaults, testers, who bears the errors.
2. **Intersectionality.** When you find an exclusion, ask who is hit twice.
3. **Structure over intent.** No villain required. Look for the structure, not the person to blame.
4. **The wall.** Every barrier is a requirement, an assumption, or a default.
5. **The persona spectrum.** Permanent, temporary, situational.
6. **Solve for one, extend to many; design with, not for.**
7. **Compliance is the floor, not the goal.**
8. **Equity is differentiated support, built in at every stage.**

And under all of them: who does this work for, and who does it exclude or harm?

## One assumption

The question we missed in week 2 was asked aloud after the break: what is one assumption you will now look for when you use, critique or build a digital product? Mine, after the 911 story: what happens to a product the night its one connection fails. The lab was about the person your assumption stops.

## Lab 2: Figma Personas, Meet Real Canadians

Started in class, due on Blackboard Friday, September 25, at 11:59 PM, as a PDF (portable document format) export. Worth 2 percent. Two personas, built in Figma: a Punjabi grandmother trying to use the Ontario Health Insurance Plan (OHIP) online health portal, and a trans teen applying to a university in Saskatchewan. For each: digital habits, access barriers, support networks, preferred tools, accessibility needs and cultural nuances.

This is the persona you audited for in Lab 1. Last week you found the barrier and guessed at the person on the other side of it; this week you built that person, in enough detail that a designer could not ignore them. Week 2's design-stage slide was the brief: personas come from research, not from imagination, and where you have no research, write what you would need to find out. The persona spectrum (principle five) is the tool; intersectionality (principle two) is the check.

What a persona holds: who, and the task today, and why today; digital habits (which device, how old, who set it up); access barriers, each one a requirement, an assumption or a default, and permanent, temporary or situational; support networks (who helps, and what happens when that person is not there); preferred tools (what they reach for first, and what they avoid); accessibility needs, so they can finish and not just start; cultural nuances (what a designer from outside this person's life would get wrong); and one line in their own voice. The worked example was my own test user: Greek-Canadian, in his seventies, came to Canada at eighteen, a phone his children set up, reads English but not fast, calls a family member before tapping anything unfamiliar, hears an alert only if it is loud. A designer can build for "calls his son first". Nobody can build for "older people struggle with technology". A persona is not a stereotype: "elderly immigrant" is a category; a named person with a phone, a language, a helper and a task is a persona.

Marks: 25 percent for persona depth and realism (where stereotypes cost you), 20 percent for digital habits and access barriers, 20 percent for accessibility needs and cultural nuances, 20 percent for support networks and preferred tools, 15 percent for Figma design quality and presentation.

## Next week (September 30)

- Best practices in inclusive design: Microsoft's inclusive design framework, and the case study ArriveCAN.
- Bring the same laptop.

## Check yourself

Try these without looking back.

1. Name the three questions from the avatars case study. Give an example of a game that passes one and fails another.
2. Does a bigger screen automatically mean better accessibility? What decides it?
3. What is the difference between systemic inequity and individual bias? Why does it matter that nobody has to hold the bias?
4. An algorithm is arithmetic. Name the four places bias gets in, and match each to one of week 1's choice points.
5. Why is "no credit history reads as risk" a default, and who does it stop? Why does the timing of the gap make it worse?
6. The case study says "up to 10 times higher". What did Gender Shades measure, what did the 2019 United States test measure, and what did neither measure?
7. Name four of the six checks before a facial recognition system goes live. Why audit false positives and false negatives separately?
8. What is a proxy signal? Why is "we removed the protected attributes" not an audit?
9. Name the two kinds of language barrier, and how each is fixed. Why is renaming a branch the floor and not the goal?
10. Pick one of the three Canadian apps. Name a person, not a category, and the assumption that shuts them out.
11. In the 911 outage, who had a second route and who did not? What makes a second route real?
12. Sort the four online exam requirements: exam, or house? What does a fairer version change, and what does it keep the same?
13. What is one assumption you will now look for when you use, critique or build a digital product?

## Sources mentioned in class

- Lynch, Tompkins, van Driel and Fritz, "Sexy, Strong, and Secondary", *Journal of Communication*, volume 66, issue 4, 2016. https://academic.oup.com/joc/article-abstract/66/4/564/4082387
- Electronic Arts, "How New CAS Starter Sims Expand Cultural Expression in The Sims 4", July 30, 2026, and "How The Sims and its partners are expanding diversity and representation in gaming", March 25, 2024.
- Apple newsroom, "Apple unveils iPhone Duo", September 9, 2026. https://www.apple.com/newsroom/2026/09/apple-unveils-iphone-duo/
- MacRumors, "Apple Announces Foldable iPhone Duo", September 9, 2026 (starting price). https://www.macrumors.com/2026/09/09/apple-announces-foldable-iphone-duo/
- Jane Douglas, "Meet the Canadians without a credit score", Lakeland Connect, September 2, 2026 (Equifax Canada figures). https://lakelandconnect.net/2026/09/02/meet-the-canadians-without-a-credit-score/
- Statistics Canada, "Immigrant credit visibility", Economic and Social Reports, September 27, 2023. https://www150.statcan.gc.ca/n1/pub/36-28-0001/2023009/article/00001-eng.htm
- Joy Buolamwini and Timnit Gebru, "Gender Shades", Proceedings of Machine Learning Research, volume 81, 2018. https://proceedings.mlr.press/v81/buolamwini18a.html
- Grother, Ngan and Hanaoka, *Face Recognition Vendor Test Part 3: Demographic Effects*, National Institute of Standards and Technology, December 2019. https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf
- CBC News, Toronto police use of facial recognition, May 2019. https://www.cbc.ca/news/canada/toronto/privacy-civil-rights-concern-about-toronto-police-use-of-facial-recognition-1.5156581
- CBC News, Toronto police used Clearview AI in 84 investigations, December 2021. https://www.cbc.ca/news/canada/toronto/toronto-police-report-clearview-ai-1.6295295
- Office of the Privacy Commissioner of Canada, Clearview AI findings, February 3, 2021. https://www.priv.gc.ca/en/opc-news/news-and-announcements/2021/nr-c_210203/
- Office of the Privacy Commissioner of Canada, the Royal Canadian Mounted Police's use of Clearview AI, June 10, 2021. https://www.priv.gc.ca/en/opc-news/news-and-announcements/2021/nr-c_210610/
- CBC News, Montreal transit agency using artificial intelligence to detect loitering, September 4, 2026. https://www.cbc.ca/news/canada/montreal/ai-stm-montreal-metro-surveillance-loitering-9.7332212
- CP24, Metrolinx introducing body-worn cameras, March 27, 2026. https://www.cp24.com/local/toronto/2026/03/27/metrolinx-introducing-body-worn-cameras-on-go-transit-up-express/
- Stanford Institute for Human-Centered Artificial Intelligence, artificial-intelligence hiring tools and racial bias, May 26, 2026. https://hai.stanford.edu/news/ai-hiring-tools-can-yield-racial-bias-and-systemic-rejection
- Jeffrey Dastin, Reuters, Amazon scraps recruiting tool that showed bias against women, October 10, 2018. https://www.reuters.com/article/us-amazon-com-jobs-automation-insight-idUSKCN1MK08G
- Ontario *Employment Standards Act, 2000*, job posting requirements in force January 1, 2026. https://www.ontario.ca/laws/statute/00e41
- Python issue 34605, 2018. https://github.com/python/cpython/issues/78786
- Linux kernel documentation, coding style, naming. https://www.kernel.org/doc/html/latest/process/coding-style.html#naming
- GitHub changelog, the default branch for new repositories is now main, October 1, 2020. https://github.blog/changelog/2020-10-01-the-default-branch-for-newly-created-repositories-is-now-main/
- Canadian Radio-television and Telecommunications Commission, Canadian Telecommunications Market Report 2025 (reserves internet figure, from week 2). https://crtc.gc.ca/eng/publications/reports/policymonitoring/2025/ctmr.htm
- The Canadian Press, 911 restored across Canada after Bell outage, September 17, 2026. https://ca.finance.yahoo.com/news/911-restored-across-canada-bell-160604867.html
- CP24, 911 lines back up after widespread outages, September 17, 2026. https://www.cp24.com/local/toronto/2026/09/17/911-lines-back-up-and-running-in-gta-after-widespread-outages-across-ontario-quebec-and-nova-scotia/
- NOW Toronto, 911 outage hits six Canadian provinces, September 17, 2026. https://nowtoronto.com/news/911-outage-six-canadian-provinces-service-restored/
- Text with 9-1-1, what you need to know. https://www.textwith911.ca/en/what-you-need-to-know-about-text-with-9-1-1/
