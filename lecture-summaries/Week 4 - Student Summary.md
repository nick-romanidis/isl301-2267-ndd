# ISL301 Week 4 Summary: Best Practices in Inclusive Design

Class of Wednesday, September 30, 2026, the National Day for Truth and Reconciliation. This recap complements the Week 4 slides and what was said in class. It is not a replacement for either. Use it to check your understanding, to get ready for Lab 3, and later to study for Test 1 on October 21.

## The one question this course keeps asking

**Who does this system work for, and who does it exclude or harm?**

This week turned that one question into three you can ask on every project: **Who isn't here? Who can't use this? How might we design it differently?**

Week 4 was mostly review, put to work. Most of what we used you already knew under our own names. The new part was applying it to real products: a government app, a streaming gadget, a game controller, and the software that decides whether your name can be registered.

## What we covered

1. The National Day for Truth and Reconciliation, and the story behind the orange shirt
2. Microsoft's inclusive design framework: three principles you already know
3. From principle to practice: four steps, matched to week 2's lifecycle
4. Inclusive design as a method, not a moral claim, and the business case
5. Case study: ArriveCAN, what happened, who could not use it, the route nobody heard about, and the lessons
6. This week's example: the Stream Deck, and the blind developer who fixed it
7. The other way to do it: the Xbox Adaptive Controller, and Microsoft's "We All Win" ad
8. Reflecting Indigenous realities in design: a name the system would not take, five realities, and what Canada has actually committed to
9. Practical tools for the rest of the course
10. A direction, not a finish line: three questions to ask every time
11. Before we break: one app, one person, one second route
12. After the break: Fair Trade, an activity in four groups

## Ground rules

Unchanged from week 1 and in force all term. Today, on this date in particular: speak from your own experience, and nobody speaks for a whole group.

## The National Day for Truth and Reconciliation

September 30 is a federal statutory holiday, created in 2021 in answer to Call to Action 80 of the Truth and Reconciliation Commission. It is not a public holiday in Ontario, which is why we had class. It is a day to honour the more than 150,000 First Nations, Inuit and Métis children who were sent to residential schools. The last federally run school closed in 1996, and many survivors are alive today.

The orange shirt comes from Phyllis Webstad. In 1973, at six years old, Phyllis wore a bright new orange shirt from a grandmother to the first day at St. Joseph Mission Residential School, near Williams Lake, British Columbia. On that first day, the shirt was taken away. Forty years later, in 2013, Phyllis told that story in public, and the first Orange Shirt Day was held on September 30 that year. September, because that is when children were taken from their families and sent to the schools. The shirt stood for feeling loved and excited to belong; taking it away was what the schools did to identity and culture. The orange shirt says one thing: **every child matters.**

We came back to what this means for designers in part three.

## Key definitions

**Microsoft's three inclusive design principles.** From Microsoft's research with disability communities. You already know all three under our names:
- **Recognise exclusion:** find the barriers your design choices create; exclusion can be permanent, temporary or situational. Ours: the wall, and the persona spectrum.
- **Learn from diversity:** work directly with the people who are excluded; they are the experts on the barrier. Ours: design with, not for.
- **Solve for one, extend to many:** a fix built for one excluded group usually helps everyone. Curb cuts were built for wheelchair users and are used by every stroller and suitcase. "The curb-cut effect" is Angela Glover Blackwell's term (2017); the curb cuts themselves came from disability activists.

**From principle to practice.** Four steps, each lining up with a stage of the lifecycle from week 2: recognise barriers (research), engage communities (design), design solutions with more than one way to finish the task (development), and iterate continuously (testing, and after launch). It is a cycle, not a checklist. You are never done, because the people using it keep changing.

**A method, not a moral claim.** Values matter, but most teams adopt inclusive design because it works. 27 percent of Canadians aged 15 and over have a disability, 8.0 million people (the 22 percent you may see quoted is the 2017 survey). Accessibility law and human rights codes add risk, and fixing it early costs less than a retrofit or a lawsuit. So if you want your boss to pay for accessibility, do not open with "it is the right thing to do". Open with 8 million more customers and less chance of being sued. Clear navigation and readable text also help everyone in bright sunlight and in a noisy room.

**Inclusive innovation.** Building systems that widen who can take part, instead of quietly adding barriers. This is our working definition, not a quotation.

**Free, prior and informed consent.** You ask the community before you decide, you tell them everything, and you do not pressure them. Their answer should be able to change the plan.

**OCAP®.** The First Nations principles of ownership, control, access and possession: First Nations own, control, access and possess data about themselves. Ask who owns the data, and where it is stored, before you collect any. (From week 2.)

## Case study: ArriveCAN

In April 2020, the Canada Border Services Agency launched ArriveCAN to collect travellers' health and contact information at the border, replacing paper forms. It became mandatory for air travellers in November 2020 and for land travellers in February 2021, with a possible fine of $5,000. While it was mandatory:
- In July 2021, a blind board member of the Canadian National Institute for the Blind could not finish setting up an account with a screen reader without help from a sighted person.
- In June and July 2022, an update wrongly told about 10,200 fully vaccinated iPhone users to quarantine. It took three weeks to find and fix.

It stopped being mandatory on October 1, 2022. In February 2024, the Auditor General could not say exactly what it cost (about $59.5 million) and found 177 releases, many with little or no documented testing. Built fast, made mandatory, changed often, tested little: every one of those is a decision about who it has to work for.

**What worked.** The phone app came in English, French and Spanish. It meant less face-to-face contact during a pandemic, and information sent ahead usually meant faster crossings.

**Who was left out.** People with no smartphone, or no data plan while abroad. Older travellers and anyone not comfortable with apps. Screen reader users at account setup. Travellers caught by the glitch. And, as I said in class, in a lot of families the traveller is not the one using the app: when my dad flies back from Greece, I fill it in for him over WhatsApp the night before.

**The route nobody heard about.** The case study page said there was no paper fallback. That is wrong. A traveller who could not use the app because of a disability, no internet, or an outage could give the information by voice to a border officer, or on a paper form. Almost nobody knew. **A second route that nobody knows about does not help anyone.** Same lesson as the 911 outage in week 3.

**Lessons, through the three principles.**
- Recognise exclusion: before making it mandatory, ask who is in the line without a phone, a data plan, or the ability to read the screen.
- Learn from diversity: test with the travellers most likely to fail, not only the team's own phones.
- Solve for one, extend to many: a well-announced paper and voice route, built for the traveller with no phone, also helps anyone whose phone dies or whose app stops working at the border.

Speed and scale matter. Inclusive design still cannot be an afterthought, even in a crisis.

## This week's example: the Stream Deck

A Stream Deck is a small keypad from Elgato, popular with streamers and YouTubers, where every key is a tiny screen. You program each key to do one thing, such as mute your microphone or switch scenes. You set the keys up in Elgato's app by dragging icons onto a picture of the pad.

**Who cannot set it up?** A blind user. The setup app is drag and drop and cannot be used with a screen reader, so a blind user can press the buttons but cannot set them up alone. A blind developer from the Netherlands, ViewpointUnseen, added keyboard and screen reader support to OpenDeck, a free, open-source replacement for Elgato's app. Two principles on one example: learn from diversity (the excluded user knew exactly what was wrong) and solve for one, extend to many (keyboard setup also helps anyone who finds dragging slow).

**The other way to do it: the Xbox Adaptive Controller.** Same world, the opposite choice. Microsoft designed a game controller for gamers with limited mobility, working with disability organisations (SpecialEffect, AbleGamers and Warfighter Engaged) from the start. It has two large buttons and 19 ports, so each player plugs in the switches, pedals or buttons that work for their own body. Its one-minute Super Bowl ad in 2019, "We All Win", ends: when everybody plays, we all win. Elgato left the excluded user to fix it; Microsoft built with them from the start.

## Reflecting Indigenous realities in design

First Nations, Inuit and Métis people are not one user group. They are many nations, languages and places, and software keeps getting them wrong in specific, fixable ways.

### A name the system would not take

In 2014, in the Northwest Territories, Shene Catholique-Valpy named her daughter Sahaiʔa, a Chipewyan (Dene) name. The ʔ is a glottal stop, a letter in Chipewyan. The territory required the Roman alphabet, and the name was registered with a hyphen instead. In 2016 the territory's health minister promised to allow Dene, Inuvialuit and Cree characters; in 2022 the family was still waiting. In February 2026 a bill to update the law passed second reading: it allows a single traditional name, but still leaves out non-Roman characters, because passports and other provinces' health systems might not accept them. Federal passports print only Roman letters, because of the international machine-readable standard.

**A character set is a default somebody chose.** Once one system cannot hold a name, every system after it becomes the excuse. The glottal stop has been part of Unicode, the standard computers use for text, since the 1990s. It is not a technical limit. It is a choice not to update. That is the wall: a default, which means it can be changed.

### Five realities, and what the design has to do

| Reality | What is true | What the design has to do |
|---|---|---|
| Names | Glottal stops, other characters, syllabics, and names reclaimed from residential schools | Accept every character in a name field. Never "correct" a name |
| Languages | More than 70 Indigenous languages; 237,420 people can hold a conversation in one | Support the keyboards that exist (FirstVoices Keyboards covers every First Nations language in Canada; Inuktitut has its own). Do not let software guess or invent a language: in March 2026, CBC reported artificial intelligence tools inventing words and mixing up nations. Ask the nation |
| Connectivity | 65.7 percent of households on First Nations reserves can get fast internet, against 96.4 percent overall | Low-bandwidth and offline modes, and a phone or in-person route (week 2) |
| Data | OCAP: First Nations own, control, access and possess data about themselves | Ask who owns the data and where it is stored before you collect any (week 2) |
| Consent | Family and kinship that do not fit a standard form (week 3); the right to free, prior and informed consent (new) | Co-design with the community early enough that their answer can change the design |

Not one user group. Name the nation, ask early, and let the answer change the design.

### Canada's commitments, checked

- **Truth and Reconciliation Commission, 2015.** 94 Calls to Action. None of them is about digital technology, though that is often claimed. The one that applies to a company you might work for is 92: consult meaningfully and get free, prior and informed consent, give equitable access to jobs and training, and educate staff.
- **United Nations Declaration on the Rights of Indigenous Peoples Act, 2021.** Canada's law to bring its laws in line with the Declaration, with an action plan of 181 measures in 2023. Its key idea is free, prior and informed consent.
- **The Digital Charter, 2019.** Often said to protect people from discrimination by algorithms. None of its ten principles mentions discrimination, bias or algorithms; the first is universal access. The artificial intelligence law that would have covered algorithms died in January 2025. Accessibility law is the two acts from week 2.

The commitments exist. None of them designs the screen. That part is yours, and compliance is the floor, not the goal.

## Practical tools

A map of the tools for the rest of the course:

| Tool | What it is | Where you use it |
|---|---|---|
| Web Content Accessibility Guidelines | Testable rules for digital accessibility | Week 2 |
| Persona spectrum | Permanent, temporary, situational | Week 2, and Lab 2 |
| Accessibility audits | Automated and manual testing of what already exists | Next week, and Lab 3 |
| Co-design workshops | Structured sessions where excluded users shape the decisions | The group project |
| Impact metrics | Measuring who benefits and who is still excluded | The group project |

Five tools, one question: who is missing?

## A direction, not a finish line

Inclusive design is not something a product has or does not have. Every choice either widens or narrows who can take part. The question is not whether you have reached perfect inclusion, but whether each version moves toward it. Every week I have asked you one question: who does this work for, and who does it exclude or harm? Here it is as three questions for every project:

- **Who isn't here?**
- **Who can't use this?**
- **How might we design it differently?**

## Before we break

Asked aloud, a quick round: think of one app or website you used this week. Who can't use it, and what second route would you give them? One app, one person, one route.

## The eight principles

No new principle this week; Microsoft's three are ours under other names. Cite them by name; the number is a shorthand, not a substitute.

1. **Technology is not neutral.** Check the five choice points: problem, data, defaults, testers, who bears the errors.
2. **Intersectionality.** When you find an exclusion, ask who is hit twice.
3. **Structure over intent.** No villain required. Look for the structure, not the person to blame.
4. **The wall.** Every barrier is a requirement, an assumption, or a default.
5. **The persona spectrum.** Permanent, temporary, situational.
6. **Solve for one, extend to many; design with, not for.**
7. **Compliance is the floor, not the goal.**
8. **Equity is differentiated support, built in at every stage.**

## After the break: Fair Trade

Four groups, four 100-piece puzzles. Nine of each group's pieces were at the other groups' tables, three at each, and each group held nine pieces that were not its own. To get a piece back, you visited another group and answered a question from their sheet, drawn from weeks 1 to 4: a right answer won one piece, a wrong one won nothing. One visitor out at a time, one piece per visit, and no second visit to a group until everyone in your group had been. The rules could change if all four groups agreed.

Then the cards were read out. Groups A and B had a second route nobody else was told about: request slips that worked without a question. Group C could bring a helper, with a pass to prove it was allowed. Group D had the rules everyone was given, and nothing more.

What it was about:
- **A second route nobody knows about is not a second route.** Groups C and D did not know A and B had one. That is ArriveCAN's paper form, and week 3's 911 outage.
- **Structure over intent.** You held pieces you had no use for, and you did not just give them back. The rules said the pieces stay on your table, and winning said you should not. Nobody was a villain.
- **Fix the structure.** One rule change, a middle table for every piece, would have beaten thirty-six negotiations. It needed all four groups to agree, and competing works against that. Solve for one, extend to many: when everybody plays, we all win.
- **Support networks, and the default user.** Group C's helper is the support network from the Lab 2 personas, and they needed a pass to be believed even though it was allowed. Group D is the default user: the standard rules, and nothing else.

The barriers today were rules, not people. That is what we have been looking for for four weeks.

## Next week (October 7)

- Evaluating products for diversity, equity, inclusion and accessibility: how to check whether a product actually delivers on inclusion.
- Lab 3, an accessibility audit of a government website, starts in class. Bring your laptop.
- Test 1 is on Wednesday, October 21.

## Check yourself

Try these without looking back.

1. Name Microsoft's three inclusive design principles, and the course principle each one matches.
2. Why do most teams adopt inclusive design? Make the case to a manager in two sentences without saying "it is the right thing to do".
3. Name two people ArriveCAN left out, and say why the paper and voice route did not help them.
4. What makes a second route real? Name the lesson ArriveCAN shares with the 911 outage.
5. Apply each of Microsoft's three principles to ArriveCAN in one sentence.
6. Who could not set up a Stream Deck, and why? What does the Xbox Adaptive Controller do differently?
7. Why could the Northwest Territories not register Sahaiʔa's name? Is that a requirement, an assumption or a default?
8. Name the five Indigenous realities on the slide, and what the design has to do for each.
9. What does free, prior and informed consent mean in practice for a design team?
10. What does Call to Action 92 ask of companies? What does the Digital Charter not say?
11. Name the five practical tools, and which one you use in Lab 3.
12. In Fair Trade, what one rule change would have helped every group? Why was it hard to agree on?
13. Think of one app or website you used this week. Who can't use it, and what second route would you give them?

## Sources mentioned in class

- Canadian Heritage, "National Day for Truth and Reconciliation", updated September 23, 2026. https://www.canada.ca/en/canadian-heritage/campaigns/national-day-truth-reconciliation.html
- National Centre for Truth and Reconciliation, "Residential School History". https://nctr.ca/education/residential-school-history/
- Orange Shirt Society, "Orange Shirt Day". https://orangeshirtday.org/about/orange-shirt-day/
- Government of Ontario, "Your guide to the Employment Standards Act: Public holidays". https://www.ontario.ca/document/your-guide-employment-standards-act-0/public-holidays
- Microsoft, Inclusive Design. https://inclusive.microsoft.design/
- Angela Glover Blackwell, "The Curb-Cut Effect", *Stanford Social Innovation Review*, Winter 2017. https://ssir.org/articles/entry/the_curb_cut_effect
- Statistics Canada, "Canadian Survey on Disability, 2017 to 2022", *The Daily*, December 1, 2023. https://www150.statcan.gc.ca/n1/daily-quotidien/231201/dq231201b-eng.htm
- Canada Border Services Agency, issue notes, study on the ArriveCAN application, November 14, 2022. https://www.cbsa-asfc.gc.ca/transparency-transparence/pd-dp/bbp-rpp/oggo/2022-11-14/issue-enjeux-eng.html
- Transport Canada, "ArriveCAN application glitch". https://tc.canada.ca/en/binder/10-arrivecan-application-glitch
- Office of the Auditor General of Canada, "Report 1: ArriveCAN", February 12, 2024. https://www.oag-bvg.gc.ca/internet/English/parl_oag_202402_01_e_44417.html
- Government of Canada, ArriveCAN. https://www.canada.ca/en/mobile/arrivecan.html
- Double Tap, AMI-audio, "Open Deck Update Brings Full Accessibility to Elgato Stream Decks", April 24, 2026. https://doubletaponair.com/open-deck-update-brings-full-accessibility-to-elgato-stream-decks/
- OpenDeck, on GitHub. https://github.com/nekename/OpenDeck
- Stream Deck photo: RacoonyRE, Wikimedia Commons, Creative Commons Attribution-ShareAlike 4.0. https://commons.wikimedia.org/wiki/File:Huggle_Buttons_on_Stream_Deck.jpg
- Xbox Adaptive Controller, released September 4, 2018. https://en.wikipedia.org/wiki/Xbox_Adaptive_Controller
- Microsoft, "We All Win", Super Bowl LIII, February 3, 2019 (copy on YouTube). https://www.youtube.com/watch?v=kW46iX_2tFo
- CBC North, Chipewyan baby name not allowed on Northwest Territories birth certificate, 2015. https://www.cbc.ca/news/canada/north/chipewyan-baby-name-not-allowed-on-n-w-t-birth-certificate-1.2984173
- CBC North, Shene Catholique-Valpy and traditional names, 2022. https://www.cbc.ca/news/canada/north/shene-catholique-valpy-traditional-names-1.6601460
- CBC North, inclusive changes proposed to the Northwest Territories Vital Statistics Act, 2026. https://www.cbc.ca/news/canada/north/vital-statistics-act-changes-nwt-9.7180325
- Legislative Assembly of the Northwest Territories, Bill 40, An Act to Amend the Vital Statistics Act. https://www.ntlegislativeassembly.ca/documents-proceedings/bills/act-amend-vital-statistics-act
- Statistics Canada, "Indigenous languages in Canada, 2021", March 29, 2023. https://www150.statcan.gc.ca/n1/pub/11-627-m/11-627-m2023029-eng.htm
- Canadian Radio-television and Telecommunications Commission, making it easier to connect Indigenous communities, March 18, 2026 (2024 data). https://www.canada.ca/en/radio-television-telecommunications/news/2026/03/crtc-making-it-easier-to-connect-indigenous-communities-to-high-speed-internet-and-cellphone-services.html
- First Nations Information Governance Centre, "The First Nations Principles of OCAP®", September 2022. https://fnigc.ca/wp-content/uploads/2022/10/OCAP_Brochure_20220927_web.pdf
- FirstVoices Keyboards, App Store listing. https://apps.apple.com/ca/app/firstvoices-keyboards/id1066651145
- CBC News, "Be wary of AI-generated content on Indigenous cultures, say experts", March 16, 2026. https://www.cbc.ca/news/indigenous/ai-indigenous-language-culture-9.7126508
- Truth and Reconciliation Commission of Canada, Calls to Action, 2015. https://nctr.ca/about/truth-and-reconciliation-commission-of-canada-calls-to-action/
- Justice Canada, United Nations Declaration on the Rights of Indigenous Peoples Act. https://www.justice.gc.ca/eng/declaration/about-apropos.html
- Innovation, Science and Economic Development Canada, "Canada's Digital Charter". https://ised-isde.canada.ca/site/innovation-better-canada/en/canadas-digital-charter-trust-digital-world
