---
slug: the-next-step-towards-a-bug-bounty-program-for-the-technology-transformation-service
date: 2017-05-18 2:00:07 -0400
title: The Next Step Towards a Bug Bounty Program for the Technology Transformation Service
summary: 'We took a big step toward creating a bug bounty program for our agency by issuing an award to HackerOne for a Software-as-a-Service bug-reporting platform.'
authors:
  - eric-mill
  - omid-ghaffari-tabrizi
  - waldo-jaquith
topics:
  - product-and-project-management
  - content-strategy
  - security
expirydate: 2025-01-01
---

On May 9, we took a big step toward creating a bug bounty program for our agency by issuing an award to HackerOne for a Software-as-a-Service bug-reporting platform. The TTS Bug Bounty will be a security initiative to pay people for identifying bugs and security holes in software operated by the General Service Administration’s Technology Transformation Service (TTS), which includes 18F. This will be the first public bug bounty program run by a civilian agency, and follows in the footsteps of the [Hack the Pentagon](https://www.defense.gov/News/News-Releases/News-Release-View/Article/802929/defense-secretary-ash-carter-releases-hack-the-pentagon-results) and [Hack the Army](https://www.army.mil/article/178473/army_secretary_issues_challenge_with_hack_the_army_program) bug bounty programs run by the Department of Defense.

Before launching the TTS Bug Bounty program, we issued the [TTS vulnerability disclosure policy](https://18f.gsa.gov/vulnerability-disclosure-policy/) in November. This policy outlines how researchers can report system vulnerabilities, while keeping personal and financial information safe. Bug bounties, which offer payouts for such reports, provide incentives for security researchers and other interested users to report security issues directly to the system owner through the use of financial rewards. {{< legacy-img src="2017/05/600-x-400-2-72-dpi-Software-development-and-debugging-concept.-Bug-found-in-binary-code-vchal-iStock-Thinkstock-504819900.jpg" alt="Software development and debugging concept. Bug found in binary code with magnifying glass." caption="" >}}

## What is a “bug bounty” program? {#what-is-a-bug-bounty-program}

Bug bounty programs have been operated by private companies since as early as 1983, with technology companies recognizing the enthusiasm of people who were fixing bugs and developing workarounds on their own. From the very beginning, these programs had a simple concept, and one that has stood the test of time: reward independent researchers for software bugs they discover, giving the owners time to fix them before they’re made public.

For a number of years, few companies operated bug bounties, but the idea has come into its own since 2010, when the most well-known tech giants began to adopt it and launch bug bounty programs of their own. Today, hundreds of companies have requirements similar to ours, with most using one of the major commercial bug bounty providers, and a handful running their own bounty programs.

## How will the TTS Bug Bounty be structured? {#how-will-the-tts-bug-bounty-be-structured}

Draft solicitation documents to hire a private vendor to operate the bug bounty program were posted for review and comment on January 23. We used these drafts to gather input from experts from the private sector, as well as within government, and used the feedback to develop our final [solicitation documents](https://github.com/18F/tts-buy-bug-bounty). Now that we’ve issued an award, HackerOne will work with us to set up bug bounties for several TTS public-facing web applications.

Upon receipt of a bug report, HackerOne will triage submissions first, determining both the validity and severity of the reported bug. Valid bugs will be sent to TTS and the appropriate team in charge of the web application will correct the issue. Anyone from a high school student with an interest in coding to a major security research firm with hundreds of employees can look for bugs and, if successful in their hunt, obtain a payout ranging from $300 to $5,000.

## What comes next? {#what-comes-next}

Security bug bounties provide many benefits to organizations that offer them:

  * Provide an officially-sanctioned channel for users to report security issues
  * Incentivize independent researchers to use their expertise to improve the organization’s security posture
  * Bring a broader base of expertise into play by opening up research to experts outside the organization
  * Complement traditional security reviews and penetration tests by making security review an ongoing, iterative process

With bug bounties becoming an established industry-wide best practice, it’s important for us to establish our own. With the results we receive from the TTS Bug Bounty, we look forward to establishing a permanent program that involves most — if not all — TTS-owned websites and web applications.

_This post was originally published on the [18F blog](https://18f.gsa.gov/2017/05/11/the-next-steps-towards-bug-bounty-program-for-technology-transformation-service/)._
