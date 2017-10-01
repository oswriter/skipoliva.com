+++
title = "Does a Software Vendor's Promise to Provide Upgrades Create a 'Perpetual' Contract?"
date = 2017-10-01
draft = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ['contract law', 'false advertising']
categories = ['Blog']

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

Software runs many of our critical business systems. But what happens when the vendor responsible for the software decides to exit the market? Do customers have any legal recourse if they were led to believe product support would continue indefinitely? A state appeals court in Wisconsin recently addressed these questions, and found the customer's options for relief were limited by its own decision not to purchase extended service contracts.

## Vendor May Be Liable Under Wisconsin Law for Misrepresenting Business Plans

The plaintiff in this case operates assisted living facilities. It needs computer systems to monitor its residents. Between 2009 and 2011, the plaintiff purchased six such monitoring systems, including hardware and proprietary software, from the defendant. In late 2011, the defendant was acquired by a larger company.

Subsequently, in 2012 the defendant sent the plaintiff a sales proposal to purchase a seventh monitoring system. The proposal said that despite the recent change in ownership, the defendant planned to remain "in business for the long term" and would continue to support its products. Such support was especially critical given the proprietary software required to control the monitoring systems, which meant only the defendant could provide any necessary security upgrades.

But despite the defendant's assurances, the company decided to exit the resident monitoring business in June 2012, just three months after sending its sales proposal to the plaintiff. The defendant formally ceased all technical support for its products at the end of 2013. This forced the plaintiff to purchase seven new monitoring systems at a cost of over $400,000. The plaintiff then sued the defendant, alleging breach of contract, breach of "good faith and fair dealing," and violation of Wisconsin's law banning "fraudulent representations" in business solicitations.

A trial judge in Milwaukee rejected all of the plaintiff's claims and granted the defendant's motion for summary judgment. But in a [September 26 opinion](https://scholar.google.com/scholar_case?case=12685763702261426536), the Wisconsin Court of Appeals for District I partially reinstated the plaintiff's case, specifically the fraudulent representation allegation, and returned that issue to the circuit court for trial.

With respect to the contract-related claims, the Court of Appeals agreed with the trial judge that the terms of the plaintiff's original purchase agreements with the defendant did not obligate the latter to provide indefinite support for its software. In fact, the plaintiff declined to purchase extended service contracts beyond the monitoring systems' one-year warranty period, opting instead to pay for such maintenance on a "time and materials" basis as needed. And although the defendant agreed to provide "software updates to the system at no charge," the appeals court said this did not create a "perpetual contract" for support.

Similarly, the plaintiff could not sustain a claim for breach of "good faith and fair dealing," since that too must be based in the terms of the contract. Since "there was no contract for lifetime provision of services [including] software updates and support," the defendant was never under any obligation to support its products beyond the warranty period. Therefore there was no "no good faith duty" to breach.

But as noted above, the Court of Appeals did find the plaintiff may have a case with regard to Wisconsin's fraudulent representations law. Under [Section 100.18 of the Wisconsin Statutes](https://docs.legis.wisconsin.gov/statutes/statutes/100/18), a business cannot make an "untrue, deceptive or misleading" statement with the intent to "induce the public in any manner to enter into a contract" for goods and services. Essentially, this is a law that bans false advertising.

In this case, the plaintiff said it was "induced" to purchase the seventh and final monitoring system based on the defendant's express statement it would remain in business "for the long term." The trial judge rejected this argument on the grounds the plaintiff had a preexisting business relationship with the defendant and was no longer a member of the "public" for purposes of Section 100.18.

But the Court of Appeals said that conclusion was premature. A jury could find that given the defendant "had no obligation to make any further purchases" from the defendant, the sales proposal was effectively a new "public" solicitation covered by the statute. Furthermore, a jury could find the defendant's misrepresentations about its intentions was a "significant factor" in the plaintiff's decision to purchase the seventh system. In turn, this caused the plaintiff to suffer a "pecuniary loss" when that system had to be replaced once the defendant exited the market.

## Is "Open Source" the Solution to Vendor Lock In?

You might think the lesson of this case is, "Always buy the extended service agreement." But it's not clear if that would have helped the plaintiff here. As the Court of Appeals explained, "Wisconsin courts do not favor perpetual contracts," unless expressly intended by the parties. So unless the service contract said it was perpetual, the plaintiff might still have been unable to obtain all of the relief it asked for.

Perhaps the real lesson--and this goes beyond the realm of contract or false advertising law--is that businesses need to do their due diligence before purchasing proprietary software that can only be serviced by a single vendor. In recent years there has been a growing movement towards "open source" software solutions where the underlying source code is made public, and thus accessible to other developers who can provide support if the original vendor decides to abruptly end support. Indeed, the plaintiff here complained that the defendant "refused to give its proprietary software code to a company that could otherwise have provided a permanent tech support solution" for abandoned customers like itself. Had the code been open source from the outset, this would not have been a problem.
