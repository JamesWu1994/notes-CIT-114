1. Summarize a few key points made in the readings or videos.

# Chapter 1 The Big Picture
* Devops is a way of thinking and a way of working
* It is part of the cultural weave that shapes how we work and why
* An equally important part of our culture is our values, norms, and knowledge
* What makes tools “devops” is the manner of their use, not fundamental characteristics of the tools themselves.
* Devops is not just another software development methodology. Although it is related to and even influenced by software development methodologies like Agile or XP, and its practices can include software development methods, or features like infrastructure automation and continuous delivery, it is much more than just the sum of these parts. While these concepts are related and may be frequently seen in devops environments, focusing solely on them misses the bigger picture—the cultural and interpersonal aspects that give devops its power.

## A Snapshot of Devops Culture
* A new engineer at Etsy starts her first day with a laptop and a development virtual machine (VM) already set up with the appropriate accounts for access and authorization, the most common GitHub repositories cloned, aliases and shortcuts to relevant tools precreated, and a guide with new hire information and links to other company resources on her desktop.
* A current employee will pair with the new employee to walk through what testing and development processes she will use in her day-to-day work. She starts by writing code on her local development VM, which is set up with configuration management to be nearly identical to the live production environment.
* In Etsy’s high-trust, blameless environment, people are given the trust and authority to decide whether a code review is necessary.

## The Evolution of Culture
* This story of Etsy today is in stark contrast to how things were several years ago with a less transparent and more error-prone deployment process that took close to four hours.
* Developers had their own blade servers to work on, rather than virtual machines, but the blade servers weren’t powerful enough to run the automated test suites to completion.
* Tests that were run in the staging environment took a couple of hours to complete, and even then they were flaky enough to make their results less than useful.
* Developers had their own blade servers to work on, rather than virtual machines, but the blade servers weren’t powerful enough to run the automated test suites to completion.

## The Value of The Story
* Effective DevOps contains case studies and stories from both teams and individuals.

# Chapter 2. What Is Devops?
* Devops is a cultural movement that changes how individuals think about their work, values the diversity of work done, supports intentional processes that accelerate the rate by which businesses realize value, and measures the effect of social and technical change.
* It is a way of thinking and a way of working that enables individuals and organizations to develop and maintain sustainable work practices.

## A Prescription for Culture
* Devops is about finding ways to adapt and innovate social structure, culture, and technology together in order to work more effectively.

## The DevOps Equation
* While the term devops itself is a portmanteau of “development” and “operations,” the core concepts of devops can and should be applied throughout the entire organization.
* A sustainable, successful business is more than the development and operations teams.

## DevOps as Folk Model
* In many ways, devops has become a folk model, a term used with different intent that leads to miscommunication and misunderstanding.
* Folk models are not necessarily bad and become problematic when different groups use the same term with different intent.
* Situational awareness

## The Old View and the New View
* Old: In an environment where humans are blamed and punished for errors, a culture of fear can build up walls that prevent clear communication and transparency.
* “human error as the cause of trouble.”
* New: Contrast this with a blameless environment, where issues are addressed cooperatively and viewed as learning opportunities for individuals and the organization.
* “human error as a symptom of trouble deeper in the system.”

## The Devops Compact
* The heart of devops starts with people working not only as groups but as teams with a desire for mutual understanding.

# Chapter 3. A History of Devops
* Examining the history of the industry and the recurring patterns and ideas within it helps us to understand what shaped the devops movement.

## Developer as Operator
* In the beginning, the developer was the operator.
* When World War II broke out, the United States government put out a call for math majors to become “computers,” a job in which they were responsible for calculating ballistics firing tables for the war effort.

## The Advent of Software Engineering
* In 1961, President John F. Kennedy set the challenge that within the decade the United States would land a person on the moon, and return them safely to Earth.
* NASA enlisted Margaret Hamilton, a mathematician at the Massachusetts Institute of Technology (MIT) to write the onboard flight software.
* In her pursuit of writing this complex software, Hamilton is credited with coining the term software engineering.
* She also created the concept of priority displays, software that alerts astronauts to information that requires their attention in real time.
* She instituted a set of requirement gathering that added quality assurance to the list of software engineering concerns, which included:
  * debugging all individual components;
  * testing individual components prior to assembly; and
  * integration testing.
* In 1969, during the Apollo 11 mission, the lunar module guidance computer software was tasked with too many calculations for its limited capacity.
* Hamilton’s team had programmed the software such that it could be manually overridden, allowing Neil Armstrong to step in and pilot the lunar module using manual controls.
* The freedom and trust that the management team afforded the team of engineers working on the onboard flight software, as well as the mutual respect between team members, led to software that facilitated one of humankind’s great leaps in technology as Neil Armstrong stepped on the moon.

### THE PROBLEMS OF SOFTWARE
* Space flight was not the only area in which software was becoming critical in the 1960s.
* As hardware became more readily available, people became more concerned about the impending complexity of software that did not follow standards across other engineering disciplines.
* The growth rate of systems and the emerging dependence upon them were alarming.
* In 1967, the NATO Science Committee, comprising scientists across countries and industries, held discussions to assess the state of software engineering.
* A Study Group on Computer Science was formed in the fall of 1967, whose goal was to focus attention on the problems of software.
* NATO Software Engineering Conference of 1968, key problems with software engineering were identified, including:
  * defining and measuring success;
  * building complex systems requiring large investment and unknown feasibility;
  * producing systems on schedule and to specification, and;
  * putting economic pressures on manufacturers to build specific products.

## The Advent of Proprietary Software and Standardization
* Until 1964, the practice was to build computers that were specific and targeted to customer requirements.
* In 1964, International Business Machines (IBM) announced a family of computers known as the System/360—computers designed to support a wide range of utility from small to large and for commercial and scientific purposes.
* The System/360 became the dominant mainframe computer, providing customers the flexibility to start small and grow computing resources as needed.
* Up until the late 1960s, computers were leased rather than bought outright.
* In 1969, faced with a US antitrust lawsuit, IBM again impacted the industry by decoupling the software and hardware of their product, charging separately for the software associated with their mainframe hardware.
* This changed how software was viewed; software had suddenly acquired significant monetary value in and of itself and was not provided openly.

## The Age of the Network
* In 1979, a worldwide distributed discussion platform called Usenet was started by Tom Truscott and Jim Ellis, then students at Duke University.
* Usenet started out as a simple shell script that would automatically call different computers, search for changes in files on those computers, and copy changes from one computer to another using UUCP (Unix-to-Unix copy, a suite of programs allowing for file transfer and remote command execution between computers).
* Ellis gave a talk on the “Invitation to a General Access UNIX Network”3 at a Unix users group known as USENIX.
* This was one of the first ways to communicate and share knowledge across organizations with computers, and its use grew rapidly.
* While this tool started to facilitate the sharing of knowledge across universities and corporations, this was also a time when the details of how companies were run were considered part of their “secret sauce.”
* Talking about solving problems outside of the company was not done, because such knowledge was viewed as a competitive advantage.
* This stymied a great deal of collaboration and limited the effectiveness of the communication channels that were available.
* Increasingly complex systems in turn led to the need for specialization of skills and role proliferation.
* This situation created the institutional Tower of Babel, with the different silos all speaking different languages due to differing concerns.
* System administrators borrowed the idea of “root cause analysis” from total quality management (TQM).
* This led in part to additional attention and effort toward minimizing risk. 

## The Beginnings of a Global Community
* As interconnected networks allowed programmers and IT practitioners to share their ideas online, people began looking for ways to share their ideas in person as well. 
* One of the biggest worldwide user groups was DECUS, the Digital Equipment Computer Users’ Society, which was founded in 1961 with members consisting mostly of programmers who wrote code for or maintained DEC computer equipment.
* Employees were strongly discouraged or even explicitly forbidden from sharing knowledge at industry conferences to try to maintain this sort of competitive advantage.
* This is in stark contrast to more recent developments, where communities and conferences are growing around knowledge sharing and cross-collaboration between companies.

### TRADE SECRETS AND PROPRIETARY INFORMATION
* Information that is not generally known to the public that is sufficiently secret to confer economic or business advantage is considered a trade secret.
* Information a company possesses, owns, or holds exclusive rights to is considered proprietary. 
* Ex: software, processes, methods, salary structure, organizational structure and customer lists.
* All trade secrets are proprietary; not all proprietary information is secret.

## The Age of Applications and the Web
* An early example of successful cooperation across organizational boundaries, the very popular Apache HTTP Server was released in 1995.
* Based on the public domain NCSA HTTP daemon developed by Robert McCool, an undergraduate at the University of Illinois at Urbana-Champaign, the modular Apache software enabled anyone to quickly deploy a web server with minimal configuration.
* This marked the beginning of a trend toward this and other open source solutions.
* Open source software, with licenses that allow users to read, modify, and distribute its source code, began to compete with proprietary, closed source solution.
* Combined with the availability of various distributions of the Linux operating system and the growth in popularity of scripting languages such as PHP and Perl, the open source movement led to the proliferation of the LAMP stack (most commonly Linux, Apache, MySQL, and PHP) as a solution for building web applications.
* It was a time of angst and frustration for both system administrators and computer programmers.
* In 1992, Simon Travaglia started posting a series on Usenet called The Bastard Operator From Hell (BOFH) that described a rogue sysadmin who would take out his frustration and anger on the users of the system.
* Toxic operations environments led some individuals in this field to view that rogue sysadmin as a hero and emulate his behaviors, often to the detriment of others around them.
* In development, there was a culture of “it’s critical to get these changes out” and “I don’t want to know how to do that because I’ll get stuck doing it.” 

## The Growth of Software Development Methodologies
* In 2001, an invitation to discuss software development went out to people interested and active in the Extreme Programming (XP) community and others within the field. XP was a form of Agile development that was designed to be more responsive to changing requirements than previous development software methodologies, known for short release cycles, extensive testing, and pair programming. In response to this invitation, 17 software engineers got together in Snowbird, Utah.
* They summarized their shared common values to capture the adaptiveness and response to change that they wanted to see in development with an explicit emphasis on human factors. This Agile Manifesto was the rallying cry that started the Agile movement.
* In 2004, Alistair Cockburn, a software developer who was one of the coauthors of the Agile Manifesto, described Crystal Clear,5 a software development methodology for small teams based on his 10 years of research with successful teams. It described three common properties:
 * frequent delivery of usable code, moving toward smaller, more frequent deployments rather than large, infrequent ones;
 * reflective improvement, or using reflections on what worked well and what worked poorly in previous work to help guide future work; and
 * osmotic communication between developers—the idea that if developers are in the same room, information will drift through the background to be picked up informally, as by osmosis.

## Open Source Software, Proprietary Services
* Instead of being restricted to one hardware vendor and whatever operating system and proprietary software would run on that hardware, developers were now able to pick and choose which tools and technologies they wanted to use.
* As software, especially web software, became more commoditized, it became at once both more and less valuable, being less exclusive and more commonplace, but with software developers being highly paid and widely sought after.
* In 2006, Amazon.com, Inc., an ecommerce company that until then had mostly been known as a website selling books and other goods to consumers, launched two services, Amazon Elastic Compute Cloud (EC2) and Amazon Simple Storage Service (S3), a first foray into providing virtualized compute instances and storage through a proprietary service.
* This allowed individuals to spin up compute resources quickly without a large upfront expenditure of hardware, and request more as needed.
* As with the introduction of the System/360, the service was quickly adopted, becoming the de facto standard due to its ease of use, low entry cost, and flexibility.
* Twitter, an online social networking service, was introduced to the world in 2006.
* At first it seemed very much like a tool for people wanting to share information in an abbreviated format, for short attention spans or for celebrities to reach out to fans.
* In 2007, however, its usage skyrocketed thanks to the South by Southwest Interactive (SXSW) conference streaming live tweets about the conference on screens in the hallways.

## Agile Infrastructure
* At the Agile 2008 conference in Toronto, system administrator and IT consultant Patrick Debois spoke about incorporating Scrum into operations with his talk, “Agile Operations and Infrastructure: How Infra-gile are You?” Patrick worked with development and operations teams on a project to test data center migration. In his work he might be doing development one day and fighting fires with the operations team the next; this context switching began to take a toll on him. Indeed, switching between even two tasks instead of focusing on just one can cause a nearly 20 percent drop in productivity due to the overhead of context switching.

## The Beginning of devopsdays
* Pris Nasrat, at the time a lead systems integrator at the Guardian, tweeted in reply, “Why not organize your own Velocity event in Belgium?” Inspired, Patrick did almost exactly that, creating a local conference that would allow for developers, system administrators, toolsmiths, and other people working in those fields to come together. In October of that year, the first devopsdays conference took place in Ghent. 
* The conference grew and spread as individuals started up new local devopsdays events across the world. With the real-time communication made available by Twitter, the hallway track never ended and #devops took on a life of its own.

## The Current State of Devops
* The 2015 State of Devops Report, published by Puppet, found that companies that are doing devops are outperforming those that aren’t.

# Chapter 6. The Four Pillars of Effective Devops

## The Four Pillars of Effective Devops
* Collaboration
* Affinity
* Tools
* Scaling

3. Identify two quotes that were made, that you found interesting.
* "A key takeaway from this event for me was the value of failure."
* "It is one thing to talk about how something should work in theory, but there is often a great deal of difference between how something should work in theory and how things turn out in practice."

5. What new facts did you learn from this section?
* This chapter opened my eyes to the effectiveness of DevOps.
