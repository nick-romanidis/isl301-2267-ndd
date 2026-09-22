# ISL301 Week 2 Summary: DEIA in Computer Applications

Class of Wednesday, September 16, 2026. This recap complements the Week 2 slides and what was said in class. It is not a replacement for either. Use it to check your understanding, to look back at Lab 1, and later to study for Test 1.

## The one question this course keeps asking

**Who does this system work for, and who does it exclude or harm?**

Week 1 asked it about people: who gets excluded, and why. Week 2 asked it about products: where in the process we excluded them, and what to do instead.

## What we covered

1. A review of week 1: the ground rules, and the seven principles
2. The BlackBerry case: one object, three roles
3. DEIA is technical quality, not a social add-on
4. Which app did you give up on, and why people give up
5. The default user does not exist
6. The four pillars, one at a time: diversity, equity, inclusion, accessibility
7. Who works in Canadian tech, and who is caught by a filter
8. Equity versus equality, the same-form scenario, equity as a feature list, and CanCode
9. The pothole app, in small groups
10. The standard (WCAG), the law (two acts), and six quick tests you can run today
11. DEIA across the product lifecycle: research, design, development, testing
12. Two Canadian products: CBC Gem and the TD mobile app
13. The cost of exclusion, and exclusion as a design choice
14. Lab 1: Spot the Bias, Canadian App Edition, started in class, with the deadline extended to Friday September 18

Two pieces on the agenda were not reached: the avatars case study (representation in games) and this week's news story, the iPhone Duo. Both move to the start of class on September 23, about fifteen minutes. The exit question was not asked; it is in the check-yourself list below instead.

## Ground rules

Unchanged from week 1 and in force all term. The one that mattered most this week: nobody speaks for a whole group, and nobody is asked to. Several slides invite people to speak about groups they belong to; you can always talk about a design or an example instead of yourself.

## The BlackBerry case

Research In Motion was founded in Waterloo in 1984. In 1998 its two-way pager was sold to the Deaf community as the WyndTell service, with email and teletypewriter relay built in. A year later the same pager was renamed BlackBerry. Then: BlackBerry Messenger in 2005, free but only between BlackBerry users; the iPhone in January 2007, which BlackBerry's leadership did not believe people would type on; the BlackBerry Storm in November 2008, a touchscreen that clicked, of which nearly all of about one million units came back; VoiceOver on the iPhone 3GS in June 2009, a screen reader built into the phone and driven entirely by touch; and the old operating system switched off in January 2022.

The question was: what changed, the object or the default user? The object did not change. The same keyboard was accessibility technology for the Deaf community in 1998, a status symbol for executives from 2005 to 2009, and a barrier from 2009 on for everyone the touchscreen could serve. The person it was for changed three times. The lesson: familiarity is an accessibility strategy, and worth keeping. The push: the strengths are the same list as the exclusions. Audit your strengths, not just your bugs.

## Key definitions

**DEIA is technical quality.** DEIA is the course's term for diversity, equity, inclusion and accessibility. A product can look polished and have great code, and if a lot of people cannot access it, understand it, afford it, or use it in their real-life context, it is not a high-quality product. The failure is measured in outcomes, not in intentions and not in crashes. Air Canada's chatbot never crashed and threw no errors; it told a grieving customer something false, and the cost sat with that customer for more than a year until a tribunal made the airline pay. That case is not about exclusion; it is about what counts as broken. Exclusion is the same kind of defect: invisible in the logs, visible in who gets hurt.

**Why people give up on an app.** Three groups: confusing or slow (you could not find the thing, or it never loaded on your connection); hard to read or not in your language (tiny text, low contrast, jargon, English only); needed something you did not have (a newer phone, a credit card, a Canadian address, a fast connection, an account you did not want). And a fourth that is quieter: it simply felt like it was not made for you. Every one of those is a design decision somebody made, and almost nobody who made them meant to exclude you. That is the principle of structure over intent.

**The default user.** When a team says "the user" without naming anyone, it is imagining someone with a recent phone and strong, unlimited internet, lots of free time and a quiet room, high English fluency and a Canadian address, no disability today, a credit card, and no worry about sharing their location or their data. Nobody writes that list down, which is why it is powerful. One assumption on the list is measured: 96.4 percent of all Canadian households can sign up for fast home internet (50 megabits per second down, 10 up, unlimited data), but only 65.7 percent of households on First Nations reserves can. About one in three cannot get it at all, whatever they are willing to pay. Design for an unnamed default and everyone else becomes an edge case. Edge case is a statement about who you imagined, not about the world.

**The four pillars, as engineering questions.**
- Diversity: who is present? On the team, in the user research, in the training data. Different people notice different edge cases. It is a headcount question, not a participation one, and it is not a spokesperson: one person should never be expected to represent a whole group.
- Equity: what support does fair access need? Equal treatment does not produce equal outcomes, because people start with different barriers. The support has to be connected to a real barrier.
- Inclusion: can they actually participate? Presence is not participation. People can contribute, be heard, influence decisions, and belong. For a product: the person can finish the task, not only start it. Inclusion is measured at the finish line, not the door.
- Accessibility: can the thing actually be used? Across physical, sensory, cognitive, technological and situational conditions. That includes an old phone on a slow connection and a phone held in one hand on a moving bus. In Canada, disability is defined broadly and includes invisible, temporary and episodic conditions. 27 percent of Canadians aged 15 and over live with a disability, 8 million people, up from 22 percent in 2017; part of the rise is that mental-health disabilities among young people are now counted.

**Barrier.** The course's word for anything that stops someone using a product. Principle four, the wall, says every barrier is one of three things: a requirement (you must have X to proceed: a credit card, a Canadian phone number), an assumption (the design takes something for granted: a fast connection, office Wi-Fi), or a default (a setting chosen once that most people never change: the font size, the language). The test: can the user change it (default), did the team just not think of it (assumption), or must the user have it to proceed (requirement)? English and French only is a requirement, not a default, because there is no switch to find.

**Equity versus equality.** Equality is the same resources, the same rules, the same treatment: same interface, same instructions, same font size, same deadline. It sounds fair, and often it is, but people start with different barriers and different access to resources, so the same thing keeps the gap exactly where it was. Equity starts from the barrier each person faces, gives the support that barrier calls for, and holds the goal constant. Different inputs, comparable results. Equity does not lower the bar, and it is not "give everyone whatever they want": the support has to answer a real barrier. Read the professor's quadrant as two columns: under equality, the person with high need and the person with low need get the same thing, and only one of them gets through; under equity, the person with high need gets more support, the person with low need loses nothing, and both end up in a comparable place.

**Equity is a feature list.** In software, equity is something you build: plain language, accessible controls, flexible formats and a low-bandwidth option, extra time where it addresses a real barrier, a second language, clear examples, adjustable text, an offline mode, a phone number accepted where an email was required. Each one is a different input that gets a stuck person to the same place, and each one is a feature somebody has to decide to build. The Weather Network app is the equality version: one font size for everyone. Honouring the phone's text-size setting would have been the equity version.

**The same-form scenario.** Everybody gets the same timed online form, the same device requirement, the same deadline, the same text-heavy instructions. The screen-reader user runs out of time; the person on a shared device cannot finish in one sitting; the person new to the language reads slower than the clock. Equal treatment can still create unequal results. The fix is support connected to the barrier, not a different goal.

**The standard: Web Content Accessibility Guidelines (WCAG).** Published by the World Wide Web Consortium: version 2.0 in 2008, 2.1 in 2018, 2.2 in 2023. Three levels: A is the minimum, without which some people cannot use the page at all; AA is what the law asks for; AAA is the highest, and even the standard says not to expect a whole site to meet it. Every rule sits under one of four principles, which spell POUR: perceivable (can users receive the information: captions, text alternatives, contrast, resizable text), operable (can they operate it: keyboard use, visible focus, enough time, no mouse-only tasks), understandable (plain language, clear labels, useful error messages, predictable navigation), robust (does it work with present and future technologies, including assistive ones: semantic HTML, sensible structure, careful use of ARIA). What a rule looks like: contrast of at least 4.5 to 1 at level AA; every meaningful image has a text alternative; nothing depends on colour alone; every function works from a keyboard; text resizes to 200 percent without losing content.

**ARIA.** Accessible Rich Internet Applications: attributes that tell a screen reader what the HTML does not. Semantic HTML first (a real button, real headings, real labels); ARIA when it adds information the HTML cannot; never as a substitute. Example: HTML has no way to say whether a menu is open or closed, so a screen reader hears "button, Menu"; add `aria-expanded`, and it hears "button, Menu, expanded". A div with `role="button"` bolted on is ARIA doing HTML's job badly; a real button gets keyboard focus and the Enter key for free.

**The law: two acts, one standard.** The Accessible Canada Act (2019) is federal: the Government of Canada and what it regulates, including banks, airlines, telecoms and interprovincial transport, with a goal of a barrier-free Canada by 2040. Federal digital services must meet WCAG 2.0 level AA as a minimum, with the public sector moving to 2.1; regulations published in December 2025 add digital requirements for federal bodies and larger federally regulated companies, starting December 2027. The Accessibility for Ontarians with Disabilities Act (2005) is provincial: the public sector and organisations with fifty or more employees, including Seneca and ServiceOntario; websites have had to meet WCAG 2.0 level AA since 2021; its headline goal, an accessible Ontario by 2025, was missed. Neither act invents its own rules; both point at the standard. Passing a checklist does not mean a real person can complete the task comfortably, independently, and with dignity. Compliance is the floor, not the goal.

**Six quick tests you can run today.** Use only the keyboard: can you reach everything and see where you are? Turn the text up to 200 percent: does anything overlap, clip or vanish? Turn on a screen reader (VoiceOver on Apple, TalkBack on Android, Narrator on Windows): does every control have a name? Check the contrast: grey on white and light text on a photo are the common failures. Break a form on purpose: does the error tell you what to do? Slow it down on mobile data or an old device: does it still finish the task? None needs a tool you do not already have. Automated scans catch the rest, and only the rest.

**DEIA across the product lifecycle.** Do not wait until right before launch to "add accessibility". Four stages, four questions, and each is a place where exclusion gets decided:
- Research: who did you talk to, and who did you miss? Are the methods themselves accessible? Are you paying participants? "We interviewed twelve users, all of them people like us" optimises the product for those twelve, and every later stage inherits that choice. Good looks like recruiting for the edges on purpose, paying participants, and offering more than one way to take part.
- Design: are the personas built from real diversity or from a stereotype? "Sarah, 28, downtown, new iPhone, fluent English" sounds reasonable, and every default that follows fits Sarah. Good looks like personas from the research, at least one on a screen reader and one on a slow connection; text written to be translated; defaults chosen for the person most likely to be excluded, not the person most like the designer.
- Development: semantic HTML first, keyboard navigation and a visible focus indicator, contrast that meets the standard, layouts that respond, performance on slow devices and networks, and support for other languages from day one. "The button is a div with a click handler" looks like a button, a mouse can click it, and a screen reader cannot find it. Every string in one place from the start means a second language is a file, not a rewrite.
- Testing: automated scans matter and will not catch everything. Test with a keyboard, a screen reader, zoom, voice input, a slow network, an old device, and real people with relevant lived experience. "Tested on the latest phone, on office Wi-Fi, by the team that built it" makes every blind spot of the team a blind spot of the test plan. Measure outcomes after launch, by group: who completes the task, who gives up, where they get stuck, and which groups have the worse experience. A failure that only hits one group disappears into the average.

This is the same list as week 1's five choice points, laid out in time. Retrofitting is expensive and usually incomplete, because the exclusion was decided before the code existed.

**Exclusion is a design choice.** Exclusion in applications is not accidental. It results from specific design decisions, usually made by default without anyone choosing on purpose, when a team does not consider the full range of users. Four moves: recognise that normal users do not exist; make inclusion decisions explicit and early; include diverse voices in design and testing, and build with the people the product is for, not just for them; measure and iterate on inclusion outcomes, split by group. Sometimes exclusion is intentional, usually it is not, and either way it results from decisions about who the team considered and whose needs were treated as important.

## Case studies and examples from class

### Gender Shades (diversity)

Buolamwini and Gebru, 2018, tested three commercial face-analysis products on a set of faces balanced by gender and skin tone. The systems failed darker-skinned women up to about 35 percent of the time and lighter-skinned men under 1 percent of the time. The training data was almost all light-skinned men, so the models had barely seen the faces they got wrong. For a model, the training data is the only room it is ever in. A diversity failure, not a code failure.

### Who works in Canadian tech (the filters)

Women are underrepresented in technical roles, and the gap widens at every level up. Indigenous peoples face barriers getting in, then more barriers moving up. Newcomers hit credential recognition, no local network, unwritten cultural expectations, language, visa complexity, and the vague demand for "Canadian experience", which Ontario postings may no longer make. Outside Toronto, Vancouver and Montreal the jobs thin out. None of this needs anyone to decide to exclude: office-first work, hiring through personal networks and job postings full of jargon each quietly filter people out. Groups like Women in AI and Women in Cyber exist to push back on who gets in, who gets heard, who gets hired, who stays and who gets credit. The original slide gives no figures for these groups, so treat them as directions to verify, not measurements.

### CanCode and the Charter (equity as policy)

CanCode is a federal program, since 2017, that pays for coding and digital-skills classes for kids. It does not pay for everyone equally: money goes first to girls, Indigenous students, and youth in rural and remote communities, through organisations that already serve them, because a program open to everyone tends to reach the kids who were already going to find it. The objection, "why should girls and Indigenous kids get money that other kids do not?", has a constitutional answer: section 15 of the Charter guarantees equality, and section 15(2) says in the same breath that programs to improve the conditions of disadvantaged groups do not break that guarantee. Canada chose both. The aim is to level the playing field, not to create an unfair advantage. Beyond the money, what has to change: internet connectivity, local delivery, culturally relevant material, community partnerships, who the instructors are, trust, and equipment.

### The pothole app (small groups)

A city launches an app for reporting potholes. To use it you need a recent smartphone, unlimited data, strong English or French, a credit card to verify your account, and no concern about sharing your location. Who gets left out, what assumptions are built in, and what alternative paths could the city offer? Every assumption is a barrier; every alternative path (a web form, a phone line, help at the library, a way to verify without a credit card, save now and upload later) is equity. Lab 1 was this exercise on a real service.

### Google Photos, 2015 (testing)

Google shipped an image labeller that tagged Black people as gorillas. The code did what it was trained to do; nobody who would have caught it was in the test. Google's fix in production was to stop the model labelling gorillas at all, which tells you how late testing found it and how little could be fixed by then.

### CBC Gem and the TD app (built for the one, used by the many)

CBC Gem is federally funded, so it is covered by the Accessible Canada Act. Read each feature as who it was built for and who ends up using it: captions, built for deaf and hard-of-hearing viewers, used by language learners and anyone in a noisy room; described video, built for blind and low-vision viewers, used by anyone listening while cooking or driving; English and French interfaces with Indigenous-language content growing; a low-bandwidth mode built for rural and remote communities, used by everyone on transit. Every row is the persona spectrum: built for the permanent case, used by the temporary and situational cases, and the second group is far bigger. That is why accessibility features are not "special features", and it is also the business case: most of the audience uses captions, so they pay for themselves.

The TD mobile app: screen reader support (VoiceOver, TalkBack, magnifiers), adjustable text that scales with the phone's setting, and a bilingual interface. The fourth row on the slide, a simplified-language mode, comes from the original course slide, and I could not find it in TD's published accessibility plan, so it is labelled as unverified. That is the habit: a claim you cannot source is a claim you label. You do not delete it and you do not repeat it as fact.

### The cost of exclusion, and Jodhan v. Canada

Business cost: users you never see in your analytics, because they never got in; retrofitting accessibility late, which is expensive and never complete; legal risk; and reputation, in a country where the case gets reported. Human cost: when a bank, a health service or a government form excludes someone, they lose access to essential services, economic opportunity, social connection or civic participation. In those settings exclusion is not an inconvenience; it is material.

Donna Jodhan is an accessibility consultant in Toronto, and she is blind. She could not apply for a federal government job online or complete the census online, because the sites did not work with her screen reader. In 2010 the Federal Court found this was a system-wide failure to meet the government's own accessibility standard and ruled it violated section 15 of the Charter; the government got fifteen months to fix it, and the Federal Court of Appeal upheld the finding in 2012. In Canada, exclusion is measurable, it is expensive, and it has already been ruled unconstitutional once.

## The eight principles (you cited these in Lab 1)

The seven from week 1, plus one added this week. Cite them by name; the number is a shorthand, not a substitute.

1. **Technology is not neutral.** Check the five choice points: problem, data, defaults, testers, who bears the errors.
2. **Intersectionality.** When you find an exclusion, ask who is hit twice.
3. **Structure over intent.** No villain required. Look for the structure, not the person to blame.
4. **The wall.** Every barrier is a requirement, an assumption, or a default.
5. **The persona spectrum.** Permanent, temporary, situational.
6. **Solve for one, extend to many; design with, not for.**
7. **Compliance is the floor, not the goal.**
8. **Equity is differentiated support, built in at every stage.** Different help for different barriers, decided at every stage of the product, not at the end.

And under all of them: who does this work for, and who does it exclude or harm?

## Lab 1: Spot the Bias, Canadian App Edition

Started in class, with the deadline extended to Friday, September 18, on Blackboard. One page: two or three examples of systemic bias or exclusion in one public-facing Canadian digital service, an annotated screenshot for each, each example tied to a principle, and links to the pages used. Each example had four parts: what I saw (the barrier in one sentence, as a requirement, an assumption or a default, not "this is slow"); who it excludes, and how (the persona spectrum, and who is hit twice); which principle; what a fix would look like (one sentence: solve for one, extend to many). The worked example was a ServiceOntario renewal page: renewing online requires the trillium number from the back of the card and a Visa or Mastercard, and the page is in English and French only, so it excludes anyone who pays by debit and anyone whose language is neither. Principles: the wall, and compliance is the floor. Fix: accept debit; add the languages the census says this city speaks. Marks: 30 percent for the examples, 25 percent for the connection to the principles (where most marks are lost), 20 percent for screenshots and links, 15 percent for the analysis, 10 percent for completeness.

## Not covered this week

Two agenda items were not reached and move to the start of class on September 23:
- **Case study: avatars and the evolution of female characters.** A 2016 study of 571 games, and three questions that are not the same question: can people see themselves, can they use it, do they feel welcome?
- **This week's story: the iPhone Duo.** Apple's first folding phone, announced September 9, as the newest product in the world to ask the course question of: who benefits, who faces barriers, and what a launch announcement does not tell us.

## Next week (September 23)

- About fifteen minutes to finish the two pieces above.
- The bias deck: bias in algorithms, terminology, and privilege in design, the second half of systemic inequities. Case study: facial recognition in Canada.
- **Lab 2: personas in Figma.** Started in class, due on Blackboard by Friday, September 25, at 11:59 PM. Bring the same laptop. The design-stage slide from this week (personas from the research, at least one on a screen reader and one on a slow connection, defaults chosen for the person most likely to be excluded) is the brief.

## Check yourself

Try these without looking back.

1. The BlackBerry keyboard was the same object in 1998, 2005 and 2009. What changed, and why does that matter for a product you would build?
2. Name the three kinds of barrier, and give one example of each from an app you use. Is "English and French only" a requirement or a default, and why?
3. Explain equity versus equality using the timed-form scenario. What would an equitable version look like without lowering what the form is for?
4. Why is it constitutional for CanCode to fund girls and Indigenous students first?
5. What do the letters in POUR stand for, and what is the difference between levels A, AA and AAA?
6. When is ARIA the right tool, and when is it the wrong one? Give one example of each.
7. Name the two accessibility acts, who each one covers, and which standard both point at.
8. Which of the six quick tests could you run on your phone right now, and what would it catch?
9. Why does "tested by the team that built it" fail, and what does "measure by group" add after launch?
10. Read the CBC Gem captions row as "built for the one, used by the many". Why is that also the business case?
11. What did the Federal Court decide in Jodhan v. Canada, and under which section of the Charter?
12. The exit question we did not get to: what is one assumption you will now look for when you use, critique or build a digital product?

## Sources mentioned in class

- RCR Wireless News on the WyndTell service, 1998 and 1999. https://www.rcrwireless.com/19990816/archived-articles/company-hopes-to-reach-deaf-community-with-wireless-messaging
- Apple newsroom, iPhone 3GS with VoiceOver, June 8, 2009. https://www.apple.com/newsroom/2009/06/08Apple-Announces-the-New-iPhone-3GS-The-Fastest-Most-Powerful-iPhone-Yet/
- BlackBerry end-of-life notice, January 4, 2022. https://www.blackberry.com/us/en/support/devices/end-of-life
- *Moffatt v. Air Canada*, 2024 BCCRT 149; CBC News report, February 2024. https://www.cbc.ca/news/canada/british-columbia/air-canada-chatbot-lawsuit-1.7116416
- Canadian Radio-television and Telecommunications Commission, Canadian Telecommunications Market Report 2025. https://crtc.gc.ca/eng/publications/reports/policymonitoring/2025/ctmr.htm
- Joy Buolamwini and Timnit Gebru, "Gender Shades", Proceedings of Machine Learning Research, volume 81, 2018. https://proceedings.mlr.press/v81/buolamwini18a.html
- Statistics Canada, Canadian Survey on Disability 2022, The Daily, December 1, 2023. https://www150.statcan.gc.ca/n1/daily-quotidien/231201/dq231201b-eng.htm
- Innovation, Science and Economic Development Canada, CanCode. https://ised-isde.canada.ca/site/cancode/en
- *Canadian Charter of Rights and Freedoms*, section 15. https://laws-lois.justice.gc.ca/eng/const/page-12.html
- World Wide Web Consortium, Web Content Accessibility Guidelines 2.1 and 2.2. https://www.w3.org/TR/WCAG21/ and https://www.w3.org/TR/WCAG22/
- *Accessible Canada Act*, S.C. 2019, c. 10. https://laws-lois.justice.gc.ca/eng/acts/A-0.6/
- Regulations Amending the Accessible Canada Regulations, SOR/2025-255, Canada Gazette, December 17, 2025. https://gazette.gc.ca/rp-pr/p2/2025/2025-12-17/html/sor-dors255-eng.html
- *Accessibility for Ontarians with Disabilities Act*, 2005. https://www.ontario.ca/laws/statute/05a11
- BBC News, Google Photos labelled Black people as gorillas, July 1, 2015. https://www.bbc.com/news/technology-33347866
- CBC Help Centre, Content Accessibility, and described video on Gem. https://cbchelp.cbc.ca/hc/en-ca/articles/31690987020701-Content-Accessibility and https://cbchelp.cbc.ca/hc/en-ca/articles/360041873913-How-to-enable-or-disable-described-video-on-Gem
- TD Accessibility Plan 2023 to 2026. https://www.td.com/content/dam/tdcom/canada/about-td/pdf/td-accessibility-plan-web-en-may-31-lp-final.pdf
- *Jodhan v. Canada (Attorney General)*, 2010 FC 1197; upheld in *Canada (Attorney General) v. Jodhan*, 2012 FCA 161. https://www.canlii.org/en/ca/fct/doc/2010/2010fc1197/2010fc1197.html
- Government of Ontario, "Renew a driver's licence" (the Lab 1 worked example). https://www.ontario.ca/page/renew-drivers-licence
