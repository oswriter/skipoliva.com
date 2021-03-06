+++
date = "2016-03-02"
title = "Is There a Constitutional Right to Audit Source Code?"
tags = ["criminal defense", "dui"]
authors = ["skipoliva"]

+++


Many people in the tech community have sounded the red alert klaxon over the FBI's recent demand for Apple's assistance in rewriting its proprietary iOS software to disable certain security features. In some corners, Apple is portrayed as a champion of individual liberty against the growing police state. But suppose we change the parameters of the legal scenario. Instead of the FBI demanding a backdoor to access an accused criminal's iPhone, let's say a defendant charged with murder has reason to believe that the victim's locked device might contain exculpatory evidence. Would it then be reasonable for the judge to order Apple's assistance in order to ensure the defendant received a fair trial?

I'm fairly confidant Apple's position would not change. At the end of the day, Apple's prime directive is protecting its proprietary software from outside interference. If that happens to coincide with taking a stance in favor of individual rights, then that's great for marketing, but it's not essential to protecting shareholder interests.

## 

I've actually been thinking about this subject since the death of U.S. Supreme Court Justice Antonin Scalia last month. Although the late justice is often characterized as an unfeeling defender of right-wing authoritarianism, Justice Scalia's actual record on criminal defense issues was far more complex. Of special concern to him was the Confrontation Clause of the <a href="https://www.law.cornell.edu/constitution/sixth_amendment">Sixth Amendment</a>, which states that in all criminal trials, the accused has the right “to be confronted with the witnesses against him.”

In 2009, Justice Scalia wrote his <i>magnum opus </i>on the Confrontation Clause in the Supreme Court's <a href="https://scholar.google.com/scholar_case?case=7136706767059629384&amp;hl=en&amp;as_sdt=6,47">majority opinion</a> in <i>Melendez-Diaz v. Massachusetts.</i> Aside from the decision itself, this case was notable in that Justice Scalia (and his conservative colleague, Justice Clarence Thomas) joined three of the Court's more traditionally liberal members in standing up for a criminal defendant's rights. Specifically, the majority held that a defendant in a drug case had the right to cross-examine the state crime lab analysts who performed forensic tests on evidence seized during the arrest process. The analysts did not testify at trial. Instead, prosecutors presented sworn affidavits wherein the analysts stated the evidence they tested was in fact illegal narcotics.

Justice Scalia, writing for the Court, said this violated the defendant's rights under the Confrontation Clause. The affidavits were a form of testimony, and as such the defense was entitled to cross-examination. Justice Scalia fervently rejected the prosecution's argument that the Confrontation Clause should only apply to “testimony recounting historical events,” and not “neutral, scientific testing,” such as crime lab reports. Noting that the latter is not always “as neutral or reliable” as the prosecution suggests,
<blockquote>Forensic evidence is not uniquely immune from the risk of manipulation. According to a recent study conducted under the auspices of the National Academy of Sciences, “[t]he majority of [laboratories producing forensic evidence] are administered by law enforcement agencies, such as police departments, where the laboratory administrator reports to the head of the agency.” And “[b]ecause forensic scientists often are driven in their work by a need to answer a particular question related to the issues of a particular case, they sometimes face pressure to sacrifice appropriate methodology for the sake of expediency.” A forensic analyst responding to a request from a law enforcement official may feel pressure—or have an incentive—to alter the evidence in a manner favorable to the prosecution. (citations omitted)</blockquote>
Ultimately, Justice Scalia concluded, “Confrontation is one means of assuring accurate forensic analysis.”

## State Courts Disagree on Right to Access Code

But what if the forensic analysis relies on proprietary source code? Prosecutors and law enforcement often use proprietary software to analyze and assess evidence. Judges and juries, in turn, rely on such evidence in convicting defendants. Does that mean a defendant has right to audit--i.e., cross-examine--any source code used to build the case against them?

State courts are divided on this question. In a recent <a href="https://scholar.google.com/scholar_case?case=11961414350036583037">Massachusetts case</a>, a state judge ordered the owner of a proprietary breath-alcohol analyzer program to disclose its source code to two defense experts (under a non-disclosure agreement), who in turn discovered “thousands of errors, some of which could produce unreliable results.” The Massachusetts Supreme Judicial Court ruled the expert's findings could be used to exclude a drunk driving defendant's breath test that relied on said code.

On the flip side, the <a href="https://scholar.google.com/scholar_case?case=6886254601549378856&amp;hl=en&amp;as_sdt=6,47">California Court of Appeal</a> ruled last year that a defendant in a murder trial could not even access the source code of a proprietary software program used to connect his DNA profile to material collected from the victim's body. (It's also worth noting that the murder took place in 1977, some 34 years before the DNA test was conducted.) Although a trial judge ordered the source code's disclosure during pretrial discovery, the Court of Appeal reversed at the urging of prosecutors, holding it was a privileged “trade secret.” The appeals court said the software company's need to protect its standing in a “highly competitive commercial environment” outweighed the defendant's need to test the reliability of the source code. The defendant expressly raised a Confrontation Clause argument, but the Court of Appeal held the right of cross examination did not apply to pretrial discovery, only witnesses produced at trial.

## Star Trek Predicts the (Legal) Future

But at what point does the source code become a “witness”? Interestingly enough, this issue has been contemplated, at least in science fiction, going back at least 50 years. An episode of the original <i>Star Trek </i>series highlighted the confrontation—pun intended—between man and source code in the courtroom.

In the first-season episode “Court Martial,” Captain James T. Kirk is accused of negligence in the death of one of his officers. A computer log shows Kirk failed to give sufficient warning before jettisoning a research pod containing the officer into space. Kirk maintains his innocence, insisting that somehow the computer log is incorrect.

Much of the episode is spent establishing the purported infallibility of the computer records. Both the presiding officer of the trial court and Kirk's own attorney insist, “Computers don't lie!” Of course, it turned out the computer did “lie.” Commander Spock, Kirk's first officer and close friend, “tested the program bank” and discovered someone had reprogrammed the computer, rendering its log entry establishing the captain's negligence unreliable. (It turned out the supposed victim had faked his death and tampered with the computer in order to frame Kirk.)

After Spock informs Kirk's attorney, Samuel Cogley, of this tampering, he delivers an impassioned plea to the court to allow him the chance to cross examine the “most devastating witness against my client,” i.e. the computer:
<blockquote>I speak of rights. A machine has none. A man must. My client has the right to face his accuser. And if you do not grant him that right, you have brought us down to the level of the machine. Indeed, you have elevated that machine above us.</blockquote>
But as Ken Ray, who co-hosts the popular Star Trek podcast <i>Mission Log </i>(and coincidentally produces a daily <a href="http://macosken.squarespace.com/">Apple news podcast</a>), pointed out in his <a href="http://www.missionlogpodcast.com/court-martial/">review</a> of “Court Martial,”
<blockquote>Cogley only finds the stones to [make his argument] once he knows that there's something wrong with the computer. He only makes his argument for humanity and 'he's got to be able to face his accuser' only when he knows that his accuser is mistaken. It doesn't even occur to him to question the validity of the computer evidence until he is presented with evidence himself that the computer evidence is wrong.</blockquote>
Put another way, if Spock had not been able to audit the computer's source code, then Cogley would have simply accepted the evidence against his client as irrefutable. The right of cross examination in this context therefore required nothing less than unrestricted access to the source code.

Yet, returning to the non-fiction world, if we accept the California Court of Appeal's reasoning in the case discussed above, source code is not essential to “test the reliability” of a computer program used to establish a defendant's guilt. Instead, the proprietary software's owner need only disclose the “methodology and underlying assumptions” to a defendant while still protecting the sanctity of its “trade secrets.” This view might not sit well with folks like <a href="http://twitter.com/dvdgeeks">John Champion</a>, Ray's <i>Mission Log </i>co-host, who said in his own comments about “Court Martial”:

>We can't be cavalier with evidence, and we can't treat people who are on trial as the pieces on a chessboard. So Cogley is making a plea for human dignity and the sanctity of the lives of the people who are the subjects here, as opposed to just holding the court procedural above everything else.

Or, as it turns out, the court procedural <i>and </i>the intellectual property portfolios of proprietary software companies.

## The Government Won't Change Until the Public Does

At some point in the not-too-distant future, the Supreme Court may have to answer the question, “Does the Confrontation Clause entitle a defendant to audit the source code of any computer program used to produce evidence against him?” But as Justice Scalia would caution if he were still with us, it's not exclusively the judiciary's responsibility to protect the rights of criminal defendants. The use of proprietary software by law enforcement is a decision made by the executive branch of government (with the tacit approval of the legislative branch.) If legislators and officials made a concerted effort to require the disclosure of source code in criminal cases, judicial intervention would not be necessary.

Such a change will not occur spontaneously. Proprietary software vendors like Apple would aggressively lobby against such a move. Legislators, regardless of political party, are also not in the business of supporting policies that make life more difficult for prosecutors and law enforcement. And let's be honest: When a large majority of the general public continue to support proprietary software themselves, there's little incentive for their elected representatives to challenge the <i>status quo</i>.

### Did You Find This Post Useful?

Would you like content such as this on your own blog or website? [Contact me](https://skipoliva.com/#contact) today to discuss a custom blog ghostwriting package for your law firm or business.
