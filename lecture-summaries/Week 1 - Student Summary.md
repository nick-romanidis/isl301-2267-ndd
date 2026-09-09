# ISL301 Week 1 Summary: Identity, Intersectionality and Computer Science

Class of Wednesday, September 9, 2026. This recap complements the Week 1 slides and what was said in class. It is not a replacement for either. Use it to check your understanding, to prepare for Lab 1, and later to study for Test 1.

## The one question this course keeps asking

**Who does this system work for, and who does it exclude or harm?**

Write it at the top of every lab. Every framework, case study and principle in this course is a way of answering it more carefully.

This is a design-quality course, not a compliance course. Meeting a standard is required. It is also the minimum. A product can pass every checklist and still shut people out.

## What we covered

1. Introductions and the icebreaker: one piece of technology that was not built for you
2. Ground rules for how we talk in this room
3. The myth of neutrality in computing
4. Identity at two levels, and intersectionality
5. Systemic bias, with this year's news story on hiring algorithms
6. The wall of exclusion and the persona spectrum
7. The build-the-wall activity (an ungraded rehearsal for Lab 1). Skipped for time; see below for what it would have been.
8. Breaking down the wall: solve for one, extend to many
9. The Canadian context: multiculturalism, bilingualism, rights and accessibility law
10. Reconciliation, Call to Action 92, and Indigenous data sovereignty

We did not reach the second deck (DEIA in Computer Applications). It moves to September 16.

## Ground rules

These were agreed on the board and apply all term.

1. Speak from your own experience. Use "I" statements, not "people like you".
2. Nobody speaks for a whole group, and nobody is asked to. If you are the only person in the room from a group, you are not its spokesperson.
3. Critique the design, not the person. Assume good intent, take impact seriously.
4. Stories stay in the room; lessons leave.
5. It is fine to change your mind mid-sentence. That is what learning looks like out loud.

Nobody is ever required to disclose anything about themselves. You can always talk about a design, a persona or an example instead of yourself.

## The icebreaker, and why it mattered

Everyone named one piece of technology that clearly was not designed with them in mind, and each answer went into a brick on the whiteboard. The instructor's example was The Weather Network Android app, which ignores the phone's text-size setting. Somebody chose a fixed font size once, and nobody turned the accessibility setting on to check.

The point, revealed once we reached the wall of exclusion: every one of those bricks is a design decision somebody made. Each looked reasonable on its own. Together they build a wall. That wall is the reference point for every case study this term.

Two products the instructor builds were also used as honest examples. A digital signage product, where the customer is the business that buys the screen and the user is whoever walks past it, and those two people were never the same. And syndii, a smart home alert system designed for older people who are not comfortable with technology. Designing for that group was the right instinct, and the product still excludes people: alerts must be heard, setup needs a smartphone and internet, the interface is English only, and it costs money. Building for people who are usually excluded does not mean you have stopped excluding anyone. The skill this course teaches is noticing, early, on purpose.

## Key definitions

**Diversity, equity, inclusion and accessibility (DEIA).** The four words in the course title, and each one becomes a question about who your software works for.
- Diversity is who is present: on the team, in the user research, in the training data.
- Equity is different from equality. Equality gives everyone the same thing. Equity gives each person what they need to reach the same outcome.
- Inclusion is whether the people who are present can actually participate fully.
- Accessibility is the measurable part: can people with disabilities use the thing. In Canada, disability is defined broadly and includes invisible, temporary and episodic conditions.

**The myth of neutrality.** The common assumption is that technology is objective: logic and mathematics that do not care who you are. The reality is that a product is a long chain of human decisions before the code and after it, and every decision is made by people with a background, values and blind spots. The mathematics is neutral. Every place it touches a person is a decision.

**Bias, as this course uses the word.** A systematic skew that disadvantages a group. The test is outcomes, not intent. "I did not mean to" is never the end of the conversation.

**The five choice points.** The five places where the makers' backgrounds and blind spots enter a product, even when the code is neutral:
1. Which problem gets picked and funded. A problem nobody in the room can see does not get picked.
2. What data gets collected. A system only knows what it was fed.
3. What the defaults are. Language, name fields, gender options, date format, units. Defaults are the designer's guess at the typical user, and most users never change them.
4. Who tests it. A team that shares a background shares blind spots.
5. Who bears the errors. Every system fails sometimes, and the cost of failure is not spread evenly.

**Individual identity.** Your own background, abilities, how you learn, your values and motivations. It shapes how you approach a problem, what you notice, and how you work with people. It is why you and your lab partner debug differently.

**Collective identity.** Shared experience as a member of a cultural, gendered, racial, linguistic or socioeconomic group. Socioeconomic means class: family income, parents' work, whether there was a computer at home. Collective identity is partly assigned by other people; you are read as something before you say anything. It shapes who enters computing, who stays, and who leads. It is why the room looks the way it does.

**Intersectionality.** Coined by law professor Kimberlé Crenshaw in 1989. Overlapping identities produce experiences that cannot be understood by looking at one identity at a time. The key phrase is "not additive". It is not "the disadvantage of being a woman plus the disadvantage of being Black". The combination creates a distinct experience that single-category thinking cannot see. It is about power and about people who fall through systems built around single categories. It is not a ranking of who is most oppressed.

The Canadian list of overlapping identities from the slides: race and ethnicity; gender identity and expression; Indigeneity and treaty status; disability and accessibility needs; language (English, French, Indigenous languages); immigration and citizenship status; socioeconomic class. Two of these, Indigeneity and treaty status and official languages, do not appear in the American version of this list at all.

**The three compounding stages.** Education (who gets early exposure and is told they belong), employment (hiring bias and networks), and leadership (glass ceilings and representation gaps). Each stage is a filter, and the filters compound. Part of a designer's job is to find where the filter is tightest, because that is where a small change does the most good.

**Systemic bias.** Bias built into structures, policies, practices and data rather than living in any individual's prejudice. It produces unequal outcomes regardless of what anyone in the system believes. No villain required. The picture to keep: a building with stairs at the entrance. Nobody who built it hated wheelchair users. The stairs still exclude, and the fix is a ramp, not a sensitivity workshop for the builders.

Why this course focuses on the systemic kind: engineers and designers control structures. You cannot retrain everyone's head. You can change a default, a requirement, a dataset or a process.

**Four places bias lives in computing** (slide 9): educational pathways, hiring pipelines, workplace norms, and technological systems.

**Mismatch.** Kat Holmes' word for the gap between a person and a design's assumptions. Exclusion is what the mismatch produces.

**The wall.** In Holmes' book *Mismatch*, a gamer who plays by voice control shows his "wall of exclusion": dozens of game controllers, every one needing two hands. (The slide calls it the Wall of Inclusion; same idea.) Each brick is one small design decision. On its own each looks reasonable. Together they make a wall nobody can get over. Exclusion is not rare and not an edge case. It is the normal result of designing for a narrow picture of who the user is.

**The three kinds of brick.** Almost every exclusion you find is one of these:
- A requirement: "requires a phone number to sign up".
- An assumption: "assumes a stable internet connection".
- A default: "language is English unless you change it".

**Accessibility thinking, traditional and inclusive.** The traditional view says accessibility is for a small minority of "special needs" users and gets added at the end. The inclusive view says exclusion happens to everyone at some point, so you design for it from the start. "Edge case" is a statement about who you imagined, not about the world.

**The persona spectrum.** From Microsoft's inclusive design toolkit. Take one need and list who has it permanently, temporarily and situationally. One-handed use: someone with one arm; someone with a broken arm; someone holding a baby. Bigger text: someone with low vision; tired eyes at the end of the day; a phone in bright sunlight. Solve it once for the permanent column and you serve all three. The permanent group is small and the other two are enormous. This is why accessibility features keep going mainstream: captions, voice control, keyboard navigation, larger text, dark mode.

**Solve for one, extend to many; the curb-cut effect.** Design for the person facing the sharpest version of a problem and the solution usually improves things for everyone facing milder versions. The first curb cuts were in Kalamazoo in 1945 and Berkeley in the early 1970s, pushed for by wheelchair users. Now every stroller, delivery cart, cyclist and suitcase uses them. Angela Glover Blackwell named this the curb-cut effect in 2017. It is an argument about where to start, not a promise that everything generalises.

**Design with, not for.** People with lived experience of exclusion are experts in spotting barriers and in solutions. Bring them into the design process at the start. The people not using your product will not show up in your analytics, so you have to go and ask.

**Compliance is the floor, not the goal.** Meeting the standard is required, and a product can meet it and still exclude people. Alt text on every image does not make a form usable for a newcomer.

**Indigenous data sovereignty and OCAP.** Sovereignty means the right to govern yourself; here, a community decides what happens to data about its own people. OCAP stands for Ownership, Control, Access, Possession and comes from the First Nations Information Governance Centre.
- Ownership: a First Nation collectively owns information about its people.
- Control: the community controls how that information is collected, used and shared.
- Access: the community can get at its own data.
- Possession: the community physically holds the data, or decides who does. Where the server sits matters.

OCAP is a First Nations framework; Inuit and Métis organisations have their own. The instructor relayed the Centre's framework and does not speak for it. A free course is at fnigc.ca.

## The seven principles (you will cite these in Lab 1)

Lab 1 gives marks for naming the principle behind each problem you find. These were on the board and will be repeated next week.

1. **Technology is not neutral.** Check the five choice points: problem, data, defaults, testers, who bears the errors.
2. **Intersectionality.** When you find an exclusion, ask who is hit twice.
3. **Structure over intent.** No villain required. Look for the structure, not the person to blame.
4. **The wall.** Every exclusion is a requirement, an assumption, or a default.
5. **The persona spectrum.** Permanent, temporary, situational.
6. **Solve for one, extend to many; design with, not for.**
7. **Compliance is the floor, not the goal.**

And under all of them: who does this work for, and who does it exclude or harm?

## Case studies and examples from class

### Google search and "Black girls" (choice point 1)

Safiya Noble's book *Algorithms of Oppression* opens with a 2011 Google search for "Black girls" that returned pornography on the first page. Nobody wrote code to do that. Ad revenue shaped ranking, and nobody at the company was checking that query. The people who decide what gets engineering time were not the people being harmed, so they never saw it. A problem nobody in the room can see does not get picked.

### Air Canada's chatbot (choice point 5)

In 2022 a passenger booking a flight after his grandmother died asked Air Canada's website chatbot about bereavement fares. The chatbot said he could apply for the discount after flying. That was false; the real policy said the opposite elsewhere on the same site. Air Canada refused the refund. In February 2024 the British Columbia Civil Resolution Tribunal ordered Air Canada to pay. Air Canada had argued the chatbot was a separate legal entity responsible for its own words; the tribunal called that remarkable and rejected it.

The lesson: probably no line of that chatbot's code was biased. The decisions around it were: ship without verifying its answers, put nobody in charge of its mistakes, then argue the mistake belonged to the software. For more than a year the cost sat with the person with the least power to do anything about it.

### DeGraffenreid versus General Motors, 1976 (intersectionality)

Five Black women sued General Motors over layoffs that went by seniority. General Motors had hired white women for office jobs for decades and Black men for factory jobs for decades, but only started hiring Black women in 1964. So Black women were last in and first out. The court threw the case out: General Motors hires women (look at the offices), it hires Black people (look at the factory floor), and there is no such thing as suing as Black women. Crenshaw's insight: the law had no category for the intersection, so the discrimination was invisible to it. It was real, and the system literally could not see it.

The engineering version: ship an update that quietly breaks only for Black women. Split your analytics by gender, women look fine. Split by ethnicity, Black users look fine. Each group is mostly unaffected people who pull the average up. You only see it by splitting by both at once, and nothing told you to. That is the General Motors court, in a dashboard.

### This year's news story: hiring algorithms (systemic bias)

**The study.** On May 26, 2026, Stanford researchers published the largest study of an artificial intelligence hiring tool to date: four million applications from 3.4 million people, across 1,700 job postings at 150 employers in 11 industries, all screened by one vendor's tool. Twenty-six percent of Black applicants and 15 percent of Asian applicants had applied to positions where the tool discriminated against their racial group. At equal recommendation rates, about 40,000 more of their applications would have advanced.

**Systemic rejection.** When many employers rent the same screening algorithm, rejection by one predicts rejection by the others, because it is the same judgement being run again. One in ten people who submitted four applications was rejected by every one. This is the compounding filter from slide 7, except here the filters line up because 150 companies bought the same software.

**The lawsuit.** Mobley versus Workday, in a federal court in California. Workday sells screening software used by thousands of employers. A job seeker alleged its tools screened him out on age, race and disability. In February 2026 the court let anyone in the United States aged 40 or over who applied through Workday since 2020 join the age claim. On June 22, 2026 the court refused to dismiss the race, sex, age and disability claims and held that a screening tool can be treated as the employer's agent. Same argument as Air Canada's chatbot, same result.

**Ontario.** Since January 1, 2026, every Ontario employer with 25 or more employees must state in a public job posting whether artificial intelligence is used to screen, assess or select applicants. The same rule bans "Canadian experience required" from postings. What it does not require: any audit before the tool is used, any test of whether it rejects some groups more than others, or any way for a rejected applicant to challenge the result.

**Why it matters to you.** When you apply for co-op or a first job, read the postings. A line like "we use automated tools, including artificial intelligence, to review applications" means your resume goes to an algorithm before a person reads it, and it may be the same algorithm the next five companies use. Nobody at that employer has to dislike you for the structure to filter you.

### Facial recognition, and checking the source

Slide 10 says facial recognition systems have higher error rates for Indigenous and racialised people, with no citation. The best-known study, Gender Shades (Buolamwini and Gebru, 2018), found commercial gender classifiers erred up to about 35 percent on darker-skinned women and under 1 percent on lighter-skinned men. It did not test Indigenous faces. A 2019 United States government report did find elevated false positives for several groups including American Indian. So the slide points the right way, but its exact claim about Indigenous people does not have a study behind it.

This is a habit to build for the whole course: before you repeat a claim, find the source and check what it actually measured. The same slide's representation figures (women around 20 to 25 percent of Canadian undergraduate computer science students; Indigenous peoples about 5 percent of the population and under 2 percent of computer science graduates) come with no source, so treat them as rough. Facial recognition gets its own case study later in the term.

### The build-the-wall activity (skipped)

This activity was planned as an ungraded rehearsal for Lab 1 and was skipped for time. Here is what it would have been, so you can try it on your own before next week.

Groups would take one domain from slide 9 (educational pathways, hiring pipelines, workplace norms, technological systems) and write bricks on sticky notes, three lines each: the brick in five words or fewer, who it excludes, and the principle number from the list above. Each group would then star the brick that looked most reasonable at the time it was laid.

The lesson the finished wall teaches: every brick had a reason. Cost, time, security, simplicity, a deadline. The wall is the sum of reasons, not the sum of malice. That is why "just be less biased" does not work. Nobody lays these bricks out of bias. Structures need redesign.

Lab 1 is exactly this exercise, on a real Canadian digital service, with screenshots. If you want a warm-up, pick one app you use daily and write three bricks for it, one of each kind: a requirement, an assumption, a default.

### Accessibility that went mainstream (slide 15, with a correction)

The slide says email and text messaging were developed for deaf users. More precisely: the teletypewriter was, in 1964. Email (1971) and text messaging (1992) were not built for deaf users, but the Deaf community adopted and championed them, because text is the channel that works. Voice assistants were built for people with mobility and vision impairments and are now used by drivers and anyone with their hands full. Captions were built for deaf users and are now used by language learners and anyone in a noisy room. Text size and dark mode were built for people with vision needs and are now ordinary preferences.

One more example from the same pattern: in 1998 a company called Wynd Communications sold a two-way pager to the Deaf community, with email and teletypewriter relay built in. The pager was made by Research In Motion of Waterloo, Ontario. A year later it was rebranded as the BlackBerry. The BlackBerry was accessibility technology before any executive had one.

## The Canadian context

Three things make the Canadian context specific.

**Multiculturalism.** Official policy since 1971 and law since 1988. A system built in Toronto cannot assume a single culture, name format, calendar or family structure.

**Bilingualism.** The Official Languages Act (1969) requires federal institutions to serve in English and French. It says nothing about the more than 70 Indigenous languages spoken in Canada. In Lab 1, if the service you audit offers English and French only, that is a brick. Write it down as one.

**The rights framework.**
- The Canadian Charter of Rights and Freedoms, section 15: equality before the law without discrimination. Section 15(2) explicitly allows programs that improve conditions for disadvantaged groups, which is the constitutional basis for equity measures.
- The Accessibility for Ontarians with Disabilities Act (2005) set a target of a fully accessible Ontario by 2025. That target has passed unmet. Seneca and ServiceOntario are both covered by it.
- The Accessible Canada Act (2019) sets 2040 for federally regulated organisations: the federal government, banks, telecoms, airlines, interprovincial transport.
- The Truth and Reconciliation Commission's Calls to Action (below).

**Six responsibilities of Canadian technologists** (slide 17): respect Indigenous data sovereignty; design for linguistic diversity; address digital divides (not everyone has a phone, home internet, or a laptop that runs your app); build accessible systems; challenge discriminatory algorithms; include marginalised voices.

## Reconciliation and Call to Action 92

From 2008 to 2015 the Truth and Reconciliation Commission documented the residential school system, in which about 150,000 Indigenous children were taken from their families. Its final report made 94 Calls to Action addressed to governments, churches, schools and businesses. Number 92 is the one for business, and it has three parts. The slide quotes only the second.

1. Adopt the United Nations Declaration on the Rights of Indigenous Peoples as the framework for how the company deals with Indigenous peoples and their lands, and obtain consent before starting projects on Indigenous land. Canada made the Declaration part of federal law in 2021.
2. Ensure Indigenous peoples have equitable access to jobs, training and education, and that Indigenous communities gain long-term benefits from projects near them.
3. Educate managers and staff on Indigenous history, residential schools, treaties and Indigenous law.

For a technology company all three apply: who you hire, who you buy from, what you teach staff, and how you handle data about Indigenous communities. The data part is OCAP (see the definitions above). Design with, not for, is the same move as learn from diversity, applied to communities that have been studied without their consent for a very long time.

A question to try: under OCAP, if a health app built with a First Nation stores its data in a United States cloud region, which of the four letters is broken? (Possession, and probably control.)

## Where this is going

The course moves through four stages: build awareness, develop skills, take action, create change. Week 1 was build awareness. Lab 1 next week is take action in miniature.

**Week 1 takeaways from the slides.**
- Computing is shaped by identity. Technology is not neutral; it reflects the identities, values and assumptions of its creators.
- Systemic bias operates through structure. Exclusion results from structural design rather than individual intent, so addressing it means redesigning systems, not just changing attitudes.
- Intersectionality reveals complexity. Multiple identity dimensions combine to create experiences that cannot be understood in isolation.
- Inclusive design benefits everyone. Exclusion is a design failure, not an edge case.

## Next week (September 16)

- The DEIA in Computer Applications deck (carried over from this week), followed by bias in algorithms, terminology and privilege in design.
- Case study: BlackBerry and the QWERTY keypad. A Canadian phone whose greatest strength, a familiar physical keyboard, was also what it could not outgrow.
- **Lab 1: Spot the Bias, Canadian App Edition.** Done in class and submitted on Blackboard at the end of class. It is already posted. Before class, read it and pick a public-facing Canadian digital service to audit. You will find two or three examples of systemic bias, annotate screenshots, and link each example to a principle from the list above. There are no make-ups for labs.

## Check yourself

Try these without looking back.

1. A sorting algorithm is neutral. Name the five places where a product built around it can stop being neutral.
2. Explain intersectionality using the General Motors case, then explain why a fairness check that tests gender and race separately can miss it.
3. What is the difference between individual bias, unconscious bias and systemic bias? Why does this course focus on the third?
4. Name the three kinds of brick, and give one example of each from an app you use.
5. Run "must be able to hear an alert" through the persona spectrum.
6. What is the curb-cut effect, and what is it not an argument for?
7. What did Air Canada and Workday both argue, and what did the courts say?
8. Ontario now requires employers to disclose artificial intelligence screening in job postings. What does that rule not require?
9. What does each letter of OCAP stand for, and why does the location of a server matter?

## Sources mentioned in class

- Bano and Zowghi (Commonwealth Scientific and Industrial Research Organisation), "AI bias isn't just an error in the algorithm, it's a chain of human decisions", Tech Xplore, August 20, 2026. https://techxplore.com/news/2026-08-ai-bias-isnt-error-algorithm.html
- Safiya Umoja Noble, *Algorithms of Oppression*, New York University Press, 2018. https://nyupress.org/9781479837243/algorithms-of-oppression/
- *Moffatt v. Air Canada*, 2024 BCCRT 149; CBC News report, February 2024. https://www.cbc.ca/news/canada/british-columbia/air-canada-chatbot-lawsuit-1.7116416
- Kimberlé Crenshaw, "Demarginalizing the Intersection of Race and Sex", *University of Chicago Legal Forum*, 1989. https://chicagounbound.uchicago.edu/uclf/vol1989/iss1/8/
- Stanford Institute for Human-Centered Artificial Intelligence, "AI Hiring Tools Can Yield Racial Bias and Systemic Rejection", May 26, 2026. https://hai.stanford.edu/news/ai-hiring-tools-can-yield-racial-bias-and-systemic-rejection
- *Mobley v. Workday, Inc.*, United States District Court, Northern District of California; summary by RPJ Law. https://rpjlaw.com/recent-developments-in-mobley-v-workday-california-court-allows-key-ai-hiring-bias-claims-to-move-forward/
- Ontario job-posting disclosure rule, in force January 1, 2026: Osler summary. https://www.osler.com/en/insights/blogs/employment-and-labour-law-blog/ai-in-hiring-ontario-employers-grappling-with-new-job-posting-disclosure-requirement/
- Joy Buolamwini and Timnit Gebru, "Gender Shades", Proceedings of Machine Learning Research, 2018. https://proceedings.mlr.press/v81/buolamwini18a.html
- National Institute of Standards and Technology, *Face Recognition Vendor Test Part 3: Demographic Effects*, December 2019. https://nvlpubs.nist.gov/nistpubs/ir/2019/NIST.IR.8280.pdf
- Kat Holmes, *Mismatch: How Inclusion Shapes Design*, Massachusetts Institute of Technology Press, 2018. https://mitpress.mit.edu/9780262539487/mismatch/
- Microsoft Inclusive Design toolkit (persona spectrum). https://inclusive.microsoft.design/
- Angela Glover Blackwell, "The Curb-Cut Effect", *Stanford Social Innovation Review*, 2017. https://ssir.org/articles/entry/the_curb_cut_effect
- RCR Wireless News on the WyndTell service, 1998 and 1999. https://www.rcrwireless.com/19990816/archived-articles/company-hopes-to-reach-deaf-community-with-wireless-messaging
- *Canadian Multiculturalism Act*. https://laws-lois.justice.gc.ca/eng/acts/c-18.7/
- *Official Languages Act*. https://laws-lois.justice.gc.ca/eng/acts/o-3.01/
- *Canadian Charter of Rights and Freedoms*, section 15. https://laws-lois.justice.gc.ca/eng/const/page-12.html
- *Accessibility for Ontarians with Disabilities Act*, 2005. https://www.ontario.ca/laws/statute/05a11
- *Accessible Canada Act*, 2019. https://laws-lois.justice.gc.ca/eng/acts/A-0.6/
- Truth and Reconciliation Commission of Canada, *Calls to Action*, 2015. https://www2.gov.bc.ca/assets/gov/british-columbians-our-governments/indigenous-people/aboriginal-peoples-documents/calls_to_action_english2.pdf
- First Nations Information Governance Centre, OCAP training. https://fnigc.ca/ocap-training/

Optional viewing before the facial recognition case study: *Coded Bias* (documentary, 2020), about the Gender Shades study. https://www.youtube.com/watch?v=_-XaaTqOICU
