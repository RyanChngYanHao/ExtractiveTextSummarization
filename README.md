# ExtractiveTextSummarization - Python 3 script (beautifulsoup4 + nltk)

## 0. Perface & Load Packages
## 1. Create Word Frequency Table
## 2. Tokenize Sentence
## 3. Score the Sentences against Word Frequency
## 4. Create a Threshold
## 5. Generate Summary
## 6. Comparing the Orginal Text versus Summary

'''
<<Title>>
Transgender student shares distressing experience of MOE allegedly blocking her HRT treatment - The Online Citizen Asia

<<Original text>>
Using a throwaway account on reddit/r/SGExams, one transgender student recalled her difficult experience in school, specifically with the Ministry of Education (MOE) allegedly interfering her hormone replacement therapy (HRT) treatment that was prescribed by her doctor after she was diagnosed with gender dysphoria.
The student recalled her experience in an all-boys-primary school, describing it as “the worse period of my life”.
She wrote, “I couldn’t fit in and constantly got bullied because I was ‘too soft’ and ‘needed to man up to the bullies’.
Things started looking up when she started attending a co-ed secondary school where she made more friends and started better understand her identity.
It was then that she was taken to the gender clinic at the Institute of Mental Health (IMH). There, she was diagnosed with gender dysphoria.
When she informed the MOE of her diagnosis via her junior college (JC), the MOE replied was: “This is a new issue and we would like to work with you to learn more about it”, as she quoted in the post.
However, after several months when she was due to begin hormone therapy, there was a snag as the MOE intervened.
She wrote, “Then, as I was about to undergo hormone therapy (a treatment explicitly stated in the ICD-10, again, and recommended by the multiple doctors attending to trans patients in Singapore) the request was suddenly blocked as the MOE had intervened, apparently for the reason ‘students in MOE schools are under our control, and we have every right and say over their treatment’.”
As such, she said her doctor “had to call off the referral” and causing her further mental trauma as it affected her ability to present and pass as a female.
On top of that, she was also instructed to cut off her hair to fit into the approved boys’ hairstyle in the school’s handbook. She had to wear a uniform designed for male students.
If she proceeded with hormone therapy and is unable to fit into the male uniform, she was threatened with expulsion, instead of the school allowing her to wear the female uniform.
“The principal’s explanation for this was that ‘due to your presentation, you would be disruptive to the school environment as a student with severe autism’,” she recalled.
About the issues with the school dress code, she said: “That could probably have slipped under the radar but it seems unlikely as all these troubles started in the same month.”
She ended her post by asking, “What right does the MOE have over the MOH? Why is the MOE interfering with my medical care, and the irony of MOE advocating for mental health issues. I cannot speak for others, but in my experience, these are outright lies and just a farce to gain support from the younger generations of students.”
In a comment replying to another Redditor on the thread who suggested that the MOE would not intervene with her treatment without parental consent,  she said that she was informed that the doctor has a meeting with higher-ups in the MOE.
She wrote, “I understand that MOE essentially reprimanded my doctor and told him not to write letter to schools or referrals for hormone therapy/treatment.”

Another person alleged that it was definitely the MOE’s fault, citing a similar case where both parents consented to their child undergoing HRT but the school did not allow it.

Worryingly, several replies to the thread shared similar incidents of LGBT students facing discrimination in schools.
Another transgender student said another transgender girl in her JC wasn’t allowed to start HRT because she did not “pass” enough—meaning she did not ‘pass’ as a girl—and the school would expel her for ruining its reputation and image if she started transitioning.

One Redditor who identified themselves as “one of the people running TransgenderSG” said that there have been much worse cases of schools and the MOE allegedly preventing students from transitioning and prohibiting doctors from giving them HRT which resulted in suicide.

Stories from other Redditors are just as harrowing.
From a girl’s exam results being withheld over allegations that she is a lesbian to a “gay witch-hunt” of LGBT students in a school and even “surprise conversion therapy”.



Together with Sayoni, TransgenderSG has collaborated with the Asia Pacific Transgender Networl (APTN) on a joint stakeholder report to the United Nations, in preparation for Singapore’s third Universal Periodic Review (UPR) this year.
The report, which was released in October 2020, references data from the first nationwide survey of the country’s transgender community.
One of the six areas of concern highlighted in the report includes the discrimination, abuse and restrictions faced by transgender students.
Specifically, 77.6 per cent of transgender students surveyed by TransgenderSG reported negative experiences in school ranging from bullying to sexual abuse. Less than 30 per cent agreed or strongly agreed that they felt safe in school and only 24 per cent said they had a staff member they could reach out to for support.
In a statement on the report, TransgenderSG said, “School administrators have implemented unreasonable demands that pressure even high-performing transgender students to drop out of school, or sought to prevent them from transitioning or pursuing HRT, sometimes by contacting their healthcare providers without the student’s or their parents’ knowledge or consent.”
“This joint report on transgender rights is the most important document ever produced to understand the impact of violence and discrimination against transgender persons in Singapore,” said Jean Chong of Sayoni.
She said that while “state and non-state actors have sometimes paid lip service to the inclusion of trans persons, it is nonetheless difficult to square this with the systemic failure in their policies which leads to the lack of protection for transgender persons”.
Citing Article 1 of the Universal Declaration of Human Rights, which states that “All human beings are born free and equal in dignity and rights”, Ms Chong said: “Trans rights are human rights. Nothing more and nothing less.”
A spokesperson for Transgender SG said: “For a long time, the challenges and struggles facing the transgender community in Singapore have long gone unheard.”
“With this report, we want to shed some light on these issues and how even small policy actions can go a long way in enabling trans people here to live safe, fulfilling lives that will benefit not just them but the rest of Singapore,” the spokesperson stressed.
 © 2006 - 2021 The Online Citizen
© 2006 - 2021 The Online Citizen


<<Summary>>
 The student recalled her experience in an all-boys-primary school, describing it as “the worse period of my life”. There, she was diagnosed with gender dysphoria. Worryingly, several replies to the thread shared similar incidents of LGBT students facing discrimination in schools. Specifically, 77.6 per cent of transgender students surveyed by TransgenderSG reported negative experiences in school ranging from bullying to sexual abuse.

<<Title>>
S'porean youth detained under ISA over alleged plans to attack Muslims at two mosques; netizens call for rehabilitation instead of retributive punishment - The Online Citizen Asia

<<Original text>>
A 16-year-old Singaporean was detained in December last year under the Internal Security Act (ISA) for allegedly drawing up “detailed plans and preparations” to attack Muslims at two mosques in Singapore using a machete, said the Internal Security Department (ISD) on Wednesday (27 January).
According to the ISD in a statement today, the youth, who is a Protestant Christian of Indian ethnicity, “is the first detainee to be inspired by far-right extremist ideology” and the youngest individual so far to be detained under the ISA for terrorism-related activities.
Brenton Tarrant, the Australian gunman singlehandedly responsible for the Christchurch mosque massacre that took 51 lives in March 2019, had purportedly influenced the youth’s views.
The ISD said that the youth had watched the live-stream of the attack and read Tarrant’s manifesto.
“He had also watched Islamic State in Iraq and Syria (ISIS) propaganda videos, and came to the erroneous conclusion that ISIS represented Islam, and that Islam called on its followers to kill non-believers,” the ISD explaiined, in highlighting the youth’s “strong antipathy towards Islam”.
The youth, said ISD, had planned to carry out his attacks on 15 March this year, on the anniversary of the Christchurch attacks.
“He chose Assyafaah Mosque and Yusof Ishak Mosque as his targets, because they were near his home. He conducted online reconnaissance and research on both mosques to prepare for the attack,” the ISD added.
The youth had also allegedly planned to drive between the two attack sites and created a plan to obtain a vehicle for that purpose.
He had also reportedly “bought a tactical vest from an online platform, and intended to adorn the vest with right-wing extremist symbols, and modify it so that he could strap on his mobile device to livestream the attack”, in a bid to replicate Tarrant’s Christchurch attack, said the ISD.
Prior to settling on the machete, the youth had considered using a rifle similar to that used by Tarrant, the ISD noted.
“He managed to find a prospective seller via a private chat platform, but did not follow through with the purchase when he suspected it was a scam.
“He nevertheless persisted to search for firearms online, and only gave up the idea when he realised that it would be difficult to get his hands on one, given Singapore’s strict gun-control laws,” said the ISD.
The youth had also experimented with making a Triacetone Triperoxide (TATP) bomb and “mimicking Tarrant’s plan of setting fire to the mosques with gasoline”.
“He eventually dropped both ideas due to logistical and personal safety concerns,” according to the ISD.
In the process of preparing himself for the machete attacks he was planning to carry out, the youth had apparently watched YouTube videos on how to do so, said the ISD.
The ISD said that the youth “was confident that he would be able to hit the arteries of his targets by randomly slashing at the neck and chest areas”.
“At the point of his arrest by ISD, the youth had found his choice machete on Carousell but had not purchased it yet,” the ISD added.
Further following the footsteps of Tarrant, said the ISD, the youth had prepared two documents which he intended to disseminate before carrying out his planned attacks.
The first was a message to the people of France — drafted after the attack against Christians in a church in the city of Nice on 29 October last year.
“In the message, he called on the French people to “stand up for what is right”, claiming that “we cannot let them [i.e. Muslims] lurk in our bushes and wait for them to attack”.
“He referred to his intended attacks as a “massacre”, an “act of vengeance” and a “call for war” against Islam. He also referred to readers as a “great audience”, in reference to his intention to livestream his attacks,” according to the ISD.
The second document, yet to be completed at the time of the youth’s arrest, was “a manifesto detailing his hatred for Islam and his belief that “violence should never be solved with peace”, because peace, while “moral”, is “nowhere near effective” as violence”, said the ISD.
The ISD added: “He also expressed hope that “my act of extremism or some would call ‘a justifiable act of violence.’ … would cause a change in those who believe that Islamic extremism is right”. The draft borrowed heavily from Tarrant’s manifesto and referred to Tarrant as a “saint” and the Christchurch attacks as a “justifiable killing of Muslims”.
According to the ISD, the youth had allegedly confessed during investigations that he was only able to see two outcomes to his plan: either risking an arrest prior to even carrying out the attacks, or being “killed by the Police” when he carries out his plan.
Highlighting the isolated nature of the youth’s actions, the ISD said that its investigation did not reveal any attempt at influencing others with his extreme outlook or to involve others in his attack plans.
“His immediate family and others in his social circles were not aware of his attack plans and the depth of his hatred for Islam,” said the ISD.
The youth’s case, said the ISD, “demonstrates yet again that extreme ideas can find resonance among and radicalise Singaporeans, regardless of race or religion”.
ISD urged the public to stay alert to suspicious items and individuals and to inform the authorities by calling 999, sending an SMS to 71999 or using the “Report” function in the SGSecure application. 
Members of the public are also encouraged to familiarise themselves with SGSecure advisories such as “Run, Hide, Tell” and “Press, Tie, Tell”. These advisories provide important information on what to do in the event of a terror attack, and how to render first aid to others in their immediate surroundings.
Commenting on The Straits Times’ Facebook post on the issue, one Muslim netizen hopes that the authorities would still take into account the youth’s age in dealing with him.
“Im muslim and i don’t wanna see he (sic) get punishment he should be educated,” they said.

A couple of other commenters held the same view, preferring rehabilitation over retribution against the youth.

One commenter, however, praised the ISD for “preventing such a vile act from happening”, adding that it is due to state surveillance that the authorities are “able to prevent” such acts from recurring.

One commenter urged the authorities to investigate which church the youth attends to see if it is imparting “extreme views” or “have influenced him”.

A couple of commenters called for greater security measures to be implemented in places of worship, including prohibiting big bags and enforcing mandatory deployment of armed security forces in such places.


 © 2006 - 2021 The Online Citizen
© 2006 - 2021 The Online Citizen


<<Summary>>
 He conducted online reconnaissance and research on both mosques to prepare for the attack,” the ISD added. “He eventually dropped both ideas due to logistical and personal safety concerns,” according to the ISD.

<<Title>>
Netizens suggest students should be afforded choice to opt out from high-element activities in school camps - The Online Citizen Asia

<<Original text>>
Source: TODAY
All schools have suspended outdoor activities involving heights such as rock climbing and rope obstacles with immediate effect, following the death of a student who fell during a high-element activity at Safra Yishun last week, The Straits Times reported.
The boy, aged 15 from Anglo-Chinese School (Independent) was taken to Khoo Teck Puat Hospital (KTPH) after the incident at about 2 pm on 3 February and was pronounced dead the next morning.
The police said in a statement on 4 Feb that the victim had “allegedly lost his footing while participating in a high-element course, but was suspended by the safety harness and subsequently lost consciousness when he was lowered to the ground”.
Camp programmes were first offered by the Ministry of Education (MOE) in April 2016 as part of Singapore’s National Outdoor Adventure Education Masterplan, including a new five-day multi-school Secondary 3 cohort camp.
Students participate in about two or three school cohort camps at upper primary and secondary levels, which provide them with the authentic outdoor environments — including high-element activities involving students clearing an obstacle course at a height — to apply their learning.
These experiences obtained during these camps are believed able to instil resilience, ruggedness, tenacity and ability to work well in teams in students so that they will be confident to seize future opportunities and tackle challenges together to build a better nation.
Following this incident, netizens on Facebook opined that high-element activities should not be made compulsory for students to join, especially those with “phobias”, as these activities can be “a mental torture” and pose pressure to them to do well among peers.
Several others also suggested many other options should be made available for students to participate in order to build their characters, saying that forcing them to join high-element activities could be “traumatising” for the students.

Meanwhile, many others said that these activities are necessary, provided that safety procedures are enhanced, as accidents can happen at all times.
Safety protocols should be “reviewed and reassessed” to avoid accidents from repeating in the future, they said, with one netizen stressing that people should “be prepared, not scared”.
Many users also suggested that these activities should be continued.
One commenter said that students do not deserve to get the learning benefits gained from these camps to be stripped away from them.
      
 © 2006 - 2021 The Online Citizen
© 2006 - 2021 The Online Citizen


<<Summary>>
 Students participate in about two or three school cohort camps at upper primary and secondary levels, which provide them with the authentic outdoor environments — including high-element activities involving students clearing an obstacle course at a height — to apply their learning. Several others also suggested many other options should be made available for students to participate in order to build their characters, saying that forcing them to join high-element activities could be “traumatising” for the students. Meanwhile, many others said that these activities are necessary, provided that safety procedures are enhanced, as accidents can happen at all times. Many users also suggested that these activities should be continued.
'''

