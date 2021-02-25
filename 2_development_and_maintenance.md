
# 2. Development and Maintenance

[← Back to Contents](README.md)

###  How do we handle growth and management?

**Key themes that emerged in discussion included:**

* [Version Support](#version-support)
* [Preservation](#preservation)
* [Communication](#communication)
* [Automation](#automation)
* [Management](#management)
* [Recognizing Individual Contribution](#recognizing-individual-contribution)
* [Leadership Transition](#leadership-transition)
* [Documentation and Education](#documentation-and-education)


## Version Support

A key issue when it comes to development and operations is versioning. Most OSSTAs create regular releases of new versions of the tool with updated features. Some OSSTAs put out new releases on specific dates to create a regularity of schedule. Others work on a milestone basis, waiting until particular features and bug fixes are complete before putting out a new release. The second approach generally works better with the volunteer nature of these projects; contributors can work when they are able, without worrying about a deadline. This can result in releases becoming delayed because of one or two features. To address this, some OSSTAs support two versions at a time, one “stable” version for the large user base, and a beta version that contains all the latest code for users to test an upcoming release.

OSSTAs are software that runs on browsers, operating systems, and hardware created by others, so there is a constant need to respond to changes in those platforms. This may conflict with the timeline of releases, requiring quick patch releases to address functionality that has broken due to changes to the underlying platforms OSSTAs are running on.

The experience for users dealing with changes to versions, browsers, and operating systems, and hardware is a concern for OSSTAs. As new versions are created, it becomes difficult for OSSTAs to maintain support for all of the past versions, even though users may continue to use them. Various user projects rely on external libraries written by community members rather than the core project maintainers, and if those libraries are not well maintained the project may stop working. This raises questions around preservation of individual artworks, which is beyond the scope of this report, but of concern to OSSTA contributors and users.


## Preservation

The preservation of the OSSTA tools themselves is a separate but related issue to artwork preservation. It can be difficult to document OSSTAs due to the distributed nature of development, and the limited time contributors have available. However, without documentation, the history of OSSTA and media arts is in danger of losing relevant content that is both educational and of artistic value. It is important to document and preserve not only the code and artistic outputs, but also the history of the communities and collaborative working models around them, which are extremely unique in the space of OSS.


## Communication

There are many different types of people that interact with OSSTAs, including contributors, students, educators, and artists. As the size of the community grows, the time and resources required to manage communication also increases. How can OSSTAs ensure that this diversity of knowledge and learning is understood by the leadership? How can strategies of communication bridge different experiences and contexts? Having regular discussions that allow community members to share their different perspectives is essential. It is also necessary to be intentional with the design of communication structures and guidelines, such as a code of conduct, to ensure they support inclusive and accessible discussions.

The OSSTA community uses a multiplicity of channels, applications, and modes of communication to interact internally and externally. One of the most common channels used is GitHub, which offers distributed version control and source code management as well as collaborative communication tools. However, a significant amount of technical experience is required to use GitHub and this is identified as a barrier for new people. Projects that centralize all communication on GitHub, even those related to non-coding aspects of the project, may severely limit participation and prevent growth. One participant said, “If we only communicate through something like GitHub, then our communication is going to be purely centered around development and lines of code.” It is important to deploy approachable ways in which newcomers and people interested in contributing can be introduced to GitHub. This may include introductory tutorials or 1-on-1 mentoring. It is also necessary to teach and recognize less technically difficult modes of contribution such as documenting issues, labeling issues, and editing the wiki.

Other channels used by the OSSTA community are email, social media, Slack, Discord, Gitter, Discourse, Stack Overflow, online forums, and IRC channels. Some of these channels offer the possibility of real-time conversation, but not everyone who is part of the community is equipped to engage in a real-time conversation or debate. This is a result of the range of technical expertise or familiarity with the project. It is important for OSSTA’s leadership to keep in mind the multiplicity of participants and their backgrounds when engaging in communication and involving the members into the decision-making process.

For some OSSTAs, having many different channels creates different access points. However, this might inundate or confuse new community members. Additionally, as the number of communication tools increases, communication and project organization can become isolated and scattered into various channels. The welcoming and introductory steps may not be clear depending on the entry channel.

There is also a need for an intentional and thoughtful approach to communication within these channels. This includes recognizing different communication styles, experience levels, native languages, and disabilities. The participants acknowledged that often they find themselves working against exclusionary communication patterns that are prevalent in open-source.

Even though OSSTAs exist in a digital environment, OSSTA contributors find in-person interaction a central element to advancing these tools. One of the participants said, “Having those personal connections is really important.” Participants find meetings to advance the tools, projects, and communities extremely valuable. Gatherings, convenings, and conferences are places where energy is aggregated and large amounts of work and maintenance are achieved, but as the participants go back to their regular schedules, it is difficult to maintain this energy. There have been previous efforts to establish regular meeting schedules but this is difficult to sustain over time, and hard to figure out equitable approaches when contributors live all around the world.


## Automation

Automated tools can facilitate welcoming new contributors and reduce the time involved in management. GitHub features such as welcoming bots, issue templates, pull request templates, and issue labels are helpful tools. However, there’s a concern that automated processes can feel cold, and participants note the value of human interaction during the onboarding process.


## Management

Management of development and community is a key concern among OSSTA contributors. Currently, some of the OSSTAs have no clear guidelines and run primarily on implicit knowledge and workflows. A lack of written documentation can cause disconnects between the primary contributors and other members of the community. Someone may solve an issue or create an addition to the tool in a way that does not align with the expectations of the primary contributors, causing their contribution to be denied.

There is a need for documentation in two main areas. First, in documenting the core values of the tool and community in forms such as a contributor covenant, mission statement, community statement, or code of conduct. Second, a set of guidelines for leadership, contribution, communication, documentation, and pull requests enables project leaders and contributors to have shared expectations and know how to work together.

OSSTAs host these documents in different places, including Google Drive, GitHub, Dropbox, and Etherpads. This creates some risk as OSSTAs rely on other platforms to store and host the projects. Often knowledge is distributed across different locations, and it can be difficult to piece the full picture together.

Every community has its own dynamics and management strategies. Many of the projects effectively use a “do-ocracy” model, where those that do the most work make decisions, or a “founder-leader” or “benevolent dictator” model, where the founder(s) of the project oversee decision making and community leadership. Many of these models emerged organically as the projects grew. A robust community is defined by a participant as a community able to self-organize and manage themselves. Thus, the community needs little permission from the leadership to manage specific areas of the tool.

One of the participants commented, “When you are building these projects, you put your own politics behind them, and the open-source ethos sometimes is: We don’t care about having decentralized management systems, we are going to let it be free form.”

However, decision making is fundamental to promote space for growth in any project. It is sometimes unclear how to make a decision or arrive at consensus when contributors are distributed. The idea that anyone can theoretically participate in decision making does not always mean that it is accessible for everyone or that it is equal. Decision-making processes may be centralized within the leadership and primary contributors, and it can be difficult to find a way in. When volunteer-based projects function on a “do-ocracy” model, it privileges those that can afford to donate their time. To address management issues, one of the participants emphasized the need for contributors with specific management skills to participate in leadership.


## Recognizing Individual Contributions

There is a need for understanding maintenance (both code development and non-code tasks such as documentation) as necessary, and to acknowledge that the people doing these tasks are an essential part of the growth and development of the tool. Recognition is a key way in which OSSTA leadership can engage people in the process of maintaining and documenting the tools. Some participants noted that recognition isn’t always enough, and that some contributors need monetary compensation to be able to allocate time.

Many OSSTA contributors are also artists, designers, academics, or sole proprietors whose career success depends on individual recognition. Ownership is a controversial topic. The intrinsic ethos of open-source relies on collaboration, thus in most projects there is no individual ownership in the sense of a sole inventor that exists in more traditional, proprietary models. Rather than ownership, participants feel public and private recognition of their contributions and that their involvement with the project is essential. The concept of ownership concerns not only who is acknowledged when a new tool or a version for a tool is released, but it is also connected to how the community perceives a tool. As a tool becomes more relevant to a group of people, they will take care of it and contribute in different ways.


## Leadership Transition

As OSSTAs become multi-year projects, many project leaders start to experience burnout. The community grows older, as there is less energy put into maintaining pathways to welcome and involve newcomers.

Processing and openFrameworks are defined as relatively mature tools that have gone through the process of transitioning from  single authorship to a community of contributors, and are widely used within the community. But these projects still struggle to organize and manage contributors, volunteers, and cultivate potential young leadership.

Leadership transition offers a way to lift the burden off project founders and also open more space for new and diverse voices. However, OSSTAs need to budget and plan the time, space, and resources necessary to develop opportunities for mentorship and transition. They must also address questions about how the new leader is chosen and what their responsibilities are.


## Documentation and Education

Several of the participants articulated that documentation is essential to the growth of the tools. One of the participants said, “The main reason I open-sourced stuff I made is because it is about saying it is more valuable to people than if I keep it closed, it is more valuable if somebody can fork it, if they want to do something different with it, if they want to look to how I built something and take that and incorporate that somewhere else, that is valuable.” Documentation is central to the ethos of OSSTAs, making them accessible and encouraging learning and experimentation.

While documentation is recognized as necessary, there are often gaps in coverage, especially when users get beyond the beginner level. There is a constant need for more tutorials, resources, and documentation, clearer guidelines for documentation, and support for translating these materials into other languages.

One prevalent idea is to approach documentation as a wiki that many  people can edit, sharing the work and allowing more people to contribute. Quality control and editorial control are issues with this method. Other projects place the documentation directly into the source code, and require documentation updates to be paired with code submissions to keep the code and documentation tightly linked. However, this raises the barrier for contributors by adding more work for a single pull request.

There has been some success involving students in documentation creation, which contributes to available materials as well as serving to recruit and onboard new community members. This type of education is discussed in depth in the section *Community: Training and Mentorship for Users and Contributors*.