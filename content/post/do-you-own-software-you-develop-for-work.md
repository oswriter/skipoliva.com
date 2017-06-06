+++
date = "2016-09-07"
title = "Do You Own Software You Develop for Work?"
categories = ["Sample Posts"]
tags = ["copyright", "employment law"]

+++


Computer code is a work of authorship subject to U.S. and international copyright laws. This is easy to forget in the open source community where software is freely licensed and re-distributed. But “license” implies the existence of a valid copyright. And software authors who fail to properly establish their copyrights will have a hard time enforcing any purported licenses in court.

## Employee Assumes He Has Ownership of Code

A <a href="https://scholar.google.com/scholar_case?case=5651988263964571306&amp;hl=en&amp;as_sdt=6,47">recent decision</a> by a federal judge in Alabama illustrates the problems that a software developer can face in enforcing copyright against their employer--or in this case, a former employer.

The plaintiff in this case is a U.S. Army veteran. Following a combat tour and an honorable discharge, the plaintiff entered the private sector as an airplane mechanic for a defense contractor in Texas. The contractor assisted Boeing in recycling parts from decommissioned Apache helicopters, a process known as depopulation. The plaintiff was one of several mechanics assigned to remove and catalog parts from the helicopters.

During this depopulation process, the plaintiff took it upon himself to develop several computer programs to track the removal of parts. The first such program was “a series of Excel spreadsheets,” according to court records, but later the plaintiff and a co-worker used <a href="http://www.asp.net/">ASP.net</a>, an open source web application platform, to create a more detailed parts-tracking program. They named this program AMIP.

More than a year later, another defense contractor working on Apache depopulation approached the plaintiff and offered him a job. The plaintiff ultimately accepted a position with this second contractor in Alabama. He also brought his AMIP program with him to the new employer.

Shortly after changing jobs, the plaintiff formally registered his copyright in AMIP with the <a href="http://copyright.gov/">U.S. Copyright Office</a>, listing himself and his former co-worker as the authors. The plaintiff then licensed AMIP to his new employer under terms that allowed the company to use the software “for an unlimited period of time” without paying a licensing fee, even in the event of the plaintiff's “voluntary separation” from the company.

## Falling Out Leads to Copyright Infringement Charges

AMIP proved quite popular at the plaintiff's new employer, and he was eventually responsible for administering an AMIP-based database with more than 200 users. Later, at the employer's direction, the plaintiff created derivative programs based on AMIP to manage the depopulation of Apache Delta and Blackhawk helicopters.

After about three years, the plaintiff became disillusioned with his employer. His attorney informed the company that it had “exceeded the scope of the license provided” for AMIP. The plaintiff then unsuccessfully attempted to negotiate a sale of the AMIP copyright to the employer. Shortly thereafter, the attorney informed the employer that his client was submitting his “involuntary resignation” and demanded the company cease using AMIP and all derivative programs immediately.

The plaintiff sued his now-former employer for copyright infringement and violations of Alabama state law. On August 31, U.S. District Judge <a href="http://www.alnd.uscourts.gov/content/judge-madeline-h-haikala">Madeline Hughes Haikala</a> granted summary judgment to the employer and dismissed the plaintiff's lawsuit.

## Plaintiff's Code Was a “Work-for-Hire”

The main defect in the plaintiff's case, Judge Haikala said, was that he failed to establish legal ownership of the AMIP copyright. The judge agreed with the defendant, who argued the plaintiff's first employer–the contractor who originally hired him as a mechanic–legally owned the AMIP code since it was developed in the course of his employment there. Under <a href="http://www.copyright.gov/title17/92chap2.html">federal law</a>, copyright vests in the original author, unless it is a “work made for hire,” in which case “the employer or other person for whom the work was prepared is considered the author.”

Although the plaintiff's 2010 registration of the AMIP copyright established a legal presumption he was the owner of said copyright, Judge Haikala said that presumption was rebutted by evidence the software was developed “within the scope of his employment” with the first defense contractor. Indeed, Judge Haikala noted that during a deposition, the plaintiff admitted “one of the things he did for [the first contractor] was work on the AMIP program.” And while the plaintiff did perform some of the work on AMIP at home, he nonetheless “used servers and other equipment” located at his employer's facility and collaborated with his co-author exclusively at work. Finally, the plaintiff's employment agreement with the first contractor expressly said that any “inventions, developments or improvements” he produced in the course of employment belonged to the company. Given all this, Judge Haikala said it was clear AMIP was a work-for-hire and the plaintiff could not assert any copyright.

## Plaintiff Failed to Produce “Complete Source Code”

Judge Haikala went on to explain that even if the defendant <em>did</em> hold a valid copyright, his lawsuit would still fail because he could not prove there was infringement by the defendant. The problem, the judge explained, was that the plaintiff “cannot produce a copy of AMIP's source code as it existed when he registered the 2010 AMIP program with the U.S. Copyright Office.”

<a href="http://www.copyright.gov/eco/help-deposit.html#source">U.S. Copyright Office rules</a> requires anyone registering a copyright in a computer program submit an electronic copy of “the first 25 and last 25 pages or equivalent units of the source code.” Source code in this context means the “code as actually written by the author in a particular programming language.” In this case, the plaintiff deposited 50 separate computer files with the Copyright Office as part of his purported 2010 registration of AMIP.

As the deposited files only constituted a portion of the total program, the plaintiff also submitted to Judge Haikala a program called AMIP-ONE, which he claimed provided a “clear roadmap to decipher” the entire AMIP source code. But the judge said AMIP-ONE was “not up to the task.” She found that 16 of the 50 files deposited with the Copyright Office did not match either the plaintiff's AMIP-ONE or the source code of the defendant's AMIP implementation.

## Appeal, State Lawsuit May Follow

Judge Haikala's decision does not necessarily signal the end of this litigation. The plaintiff may appeal the judge's decision to the U.S. <a href="http://www.ca11.uscourts.gov/">11th Circuit Court of Appeals</a> in Atlanta. The plaintiff also raised a number of claims under Alabama state law against his former employer. Judge Haikala declined to exercise jurisdiction over those claims, noting he is free to pursue them in Alabama state court.

### Did You Find This Post Useful?

Would you like content such as this on your own blog or website? [Contact me](https://skipoliva.com/#contact) today to discuss a custom blog ghostwriting package for your law firm or business.
