# INTRODUCTION-TO-RISC-V
Learn the basics of the RISC-V ISA and the community ecosystem


**Introduction:**

Chapter Overview and Objectives

In this chapter, we will embark on a journey to discover the world of RISC-V – a technology, an organization, and a community. As you read through these pages, you will grasp the fundamental essence of RISC-V.

This chapter also explores everything there is to know about the RISC-V organization – RISC-V International. We will go over the history of RISC-V from its origins as an academic program through its current incarnation as a global non-profit organization, as well as the organizations within RISC-V – technical and non-technical.

By the end of this chapter, you should be able to:

Describe the philosophy of RISC-V.

List the goals of RISC-V International as a community-driven organization.

Describe the organization around the RISC-V community.

Understand how member organizations work together to develop an open source community.

Know how to contribute and make a difference within the RISC-V community.

So, relax, sit back, and allow the layers of RISC-V to unfold before you, revealing an organized ecosystem that is shaping the future of computing.

**Exploring RISC-V:**

**About RISC-V**

RISC processors – short for Reduced Instruction Set Computer - were first designed in the 1980s as an evolution of earlier designs.

In practice, the term RISC-V can refer to several different things depending on context:

The Instruction Set Architecture (ISA)

The community of users and developers of the ISA

RISC-V International, the organization that owns and maintains the ISA intellectual property

The hardware and IP products that are built on the ISA.

As you can see, each of these things revolves around the ISA as the central component, but all of these things are RISC-V. In general, we use RISC-V in conversation to refer to the technology components – the ISA and its various specifications – while the other contexts are the RISC-V community, RISC-V International, and RISC-V hardware, respectively.

**The RISC-V ISA and Community**

ISA refers to the Instruction Set Architecture, an abstract model of a computer — in this case, a Reduced Instruction Set Computer (or RISC). The specification for this set of instructions is the 5th generation of RISC processors, which have been in development since the 1980s, thus we call it RISC-V.

Unlike technology developed by a privately owned company or consortium, RISC-V is developed by a community, a group of individuals and organizations who all contribute to the development of these specifications. Members of the community come from all walks of life — industry professionals, students, trainers, and anyone else with an interest in open technology and a willingness to learn more about it.

While all members have their own reason for participating, they all share a common interest in developing an openly available instruction set architecture specification and the ecosystem around it. This ecosystem is composed of a wide variety of elements:

Physical hardware: Processors, development boards, System-on-Chips (SoCs), System-on-Modules (SoMs), and other physical systems.

“Soft” IP processor cores that can be loaded into emulators, field-programmable gate arrays (FPGAs), or implemented in silicon.

The entire software stack, from bootloaders and firmware, up to full operating systems and applications.

Educational material including courseware, curricula, lesson plans, online courses like this one, tutorials, podcasts, lab assignments, and even books.
Services including verification, custom board design, and many more.
All of this community output is recognized on the RISC-V Exchange, an organized section on the RISC-V website that describes the ecosystem in terms of available hardware and software, services, learning materials, and discussion points.

The website also lists much more information about the community, with links to member working groups as well as public mailing lists, organized information on the wiki, and of course the specifications themselves — both the completed, approved versions and the latest specs being developed.

So why do we refer to this as a community rather than a marketplace? The true reason is that we think a community is by far the best way to approach an effort as complex as building a new architecture from scratch, using proven open source development methods. RISC-V at its heart is a community of highly motivated people focused on the same goals and harnessing the power of working together with many hands to lift a heavy load.

**The Importance of Open Source & Open Standards**

RISC-V’s story begins at the UC Berkeley Parallel Computing Lab. To set the stage, we first discuss the importance of open source and open standards, as these directly apply to the development process and open licensing of the RISC-V ISA.

Technology does not persist in isolation, unless we are talking about exceptionally simple unconnected devices like a flashlight — and even there, we rely on international standards to connect the battery to the bulb. As our technical world has become more complex and more connected, global standards ensure that society may realize the profound benefits of interoperability from the inventor to the consumer.

Standards drive innovation at a base platform level from the standard threads on a machine screw to threads connecting silicon on a microprocessor. The setting of voluntary standards in engineering dates back more than a century. In the late 1980s through the 1990s, Tim Berners-Lee led a revolution to standardize the protocols we use on the internet (URL, HTML, HTTP, W3C), easily the biggest advance of technology utility in modern history. There are numerous examples that underpin the technology we rely on every day.

Advances in software and hardware standardization through global collaboration and consensus, as well as open source development and delivery of software and hardware design, has accelerated technical progress at an unprecedented global scale. The release of RISC-V to the open community, both for standardization and for ongoing improvement through open collaboration is at the core of RISC-V International. Without collaboration and open access to the RISC-V ISA and open extensions, the community risks fragmentation, forking, and the establishment of multiple standards.

As an Instruction Set Architecture, RISC-V itself is not “open source” in the same way that software is open, as an ISA is not made of source code. It is, however, an open specification, and it is released under a Creative Commons license. Other artifacts within RISC-V, such as software and compliance tests, use appropriate licenses (e.g. BSD and MIT) that retain the permissive original intent for RISC-V to be available to everyone.

**History of RISC and Open ISAs**

RISC stands for Reduced Instruction Set Computer, a computer architecture proposed in the early 1980s based on simplicity, as opposed to current microprocessors at the time, dubbed Complex Instruction Set Computers, or CISC. The RISC architecture was born in an academic environment, so the design strives for simplicity and efficiency, proposing a series of features that dramatically opposed the CISC philosophy, which was motivated by commercial interests at the time. RISC is the opposite of CISC in many ways. Usually, CISC CPUs have a few registers and lots of instructions, most of which have access to memory, whereas RISC CPUs have lots of registers and a very modest instruction set, with memory access restricted to a few Load and Store instructions.

Now, the distinction between a complex and a reduced instruction set is in the numbers: CISC instruction sets usually support lots of instructions, many performing complicated calculations for specific tasks, whereas RISC instruction sets have a modest number of simple, general-purpose instructions. As an example: Intel’s 80386 (the first 32-bit microprocessor) was launched in 1985 and supported over 150 instructions, whereas the RISC-V Base Integer ISA was released in 2010 and has only 40 instructions!

The RISC acronym was coined around 1980 by Prof. David Patterson at the University of California, Berkeley, whose work with Prof. John Hennessy at Stanford University yielded their celebrated books “Computer Organization and Design” and “Computer Architecture: A Quantitative Approach." Thanks to their work on the RISC architecture, they received the ACM A. M. Turing Award in 2017.

In many ways, the history of RISC is bound up with the history of MIPS processors. Both processor architectures have had great commercial success in different ways, although RISC architectures are arguably more likely to be recognized through some very popular designs, including Sun Microsystems’ SPARC line, DEC’s Alpha line, Intel’s i860 and i960 processors, and the ubiquitous ARM processors that inhabit billions of devices today from many silicon manufacturers. RISC-V is the latest iteration of this instruction set architecture.

Many RISC, MIPS, and other designs have been “open” to varying degrees. In 2005, Sun Microsystems opened the SPARC architecture, creating the OpenSPARC project under the GNU Public License (GPL). The OpenRISC project provides 32-bit and 64-bit cores through the OpenCores community under the Lesser GNU Public License (LGPL), which is somewhat less restrictive than the GPL. The MIPS architecture, owned by Wave Computing, was provided under an “open use” license in a pilot program that closed down in 2019. Even ARM, which previously showed its architecture only to paying licensees, has now partly opened its architecture to changes by its partners. All of these efforts work to balance the needs and aspirations of partners and stakeholders with the realities of the marketplace, international laws around intellectual property, and the historic momentum in the industry that keeps leading toward open source, open specifications, and open standards.

The takeaway is that opening up an Instruction Set Architecture is both a highly valuable effort and a very difficult task. It requires collaboration among many stakeholders, protection from patent trolls and other lawsuits, and a clear path toward ownership for anyone basing their livelihood on the outcome. RISC-V is succeeding wildly because of its dedication to a fully open architecture, the protection provided and agreed to by all members, and its full commitment to community.

**RISC-V Origins: UC Berkeley Architecture Research**

Prof. Krste Asanović and graduate students Yunsup Lee and Andrew Waterman started the RISC-V instruction set in May 2010 as part of the Parallel Computing Laboratory (Par Lab) at UC Berkeley, of which Prof. David Patterson was Director. The Par Lab was a five-year project to advance parallel computing funded by Intel and Microsoft for $10M over 5 years, from 2008 to 2013. It also received funding from several other companies and the State of California. The Chisel hardware construction language that was used to design many RISC-V processors was also developed in the Par Lab.

All the projects in the Par Lab were open source using the Berkeley Software Distribution (BSD) license, including RISC-V and Chisel.

The ISA specification itself, i.e., the encoding of the instruction set, was released with a permissive license (similar to the language of the BSD license) when the ISA tech reports were published., though the The actual tech report text (an expression of the specification) was later put under a Creative Commons license to allow it to be improved by external contributors, including the RISC-V Foundation.

No patents were filed related to RISC-V in any of these projects, as the RISC-V ISA itself does not represent any new technology. The RISC-V ISA is based on computer architecture ideas that date back at least 40 years. RISC processor implementations – including some based on other open ISA standards – are widely available from various vendors worldwide.

The worldwide interest in RISC-V is not because it is a great new chip technology. The interest is because it is a common free and open standard to which software can be ported, and which allows anyone to freely develop their own hardware to run the software. RISC-V International does not manage or make available any open source RISC-V implementations, only the standard specifications. RISC-V software is managed by the respective open source software projects.

Suggested reading: The original history article titled "RISC-V Genealogy".

**DARPA Influence**

After the invention of RISC-V, it was used by numerous companies, in many places. Countless projects used it, including research programs funded by the Defense Advanced Research Projects Agency (DARPA).

The UC Berkeley ASPIRE Lab succeeded the Par Lab, and was led by Krste Asanović. It lasted from 2013 to 2018 and led to the building of several RISC-V compatible microprocessors. It had funding from DARPA as well as from many companies.

Basic research funding to universities is largely for unrestricted research with permission to publicly disseminate the results. This contract is the standard model for U.S. federal grants to universities, and allows for results from the funded work to be published in the open literature and made accessible worldwide to the public at large. The government retains rights to use any technology developed in the research, but unless explicitly stated, does not restrict the technology.

A related DARPA photonics program predates RISC-V, and funded research at MIT in 2006. The research supported the development of integrated silicon photonics. Later stages of funding at MIT and Berkeley were used to build prototype chips, which included RISC-V cores as infrastructure to demonstrate the photonic links.

The ASPIRE Lab was funded by the DARPA Power Efficiency Revolution for Embedded Computing Technologies (PERFECT) program. The goal of the program was to develop revolutionary approaches as well as the technologies and techniques to provide the power efficiency required to enable embedded computing systems. Researchers used RISC-V based systems to demonstrate the ideas in that program.

In all of these funded projects, the RISC-V ISA specification and RISC-V open source cores were not contract deliverables. RISC-V was just the infrastructure separately developed to support the funded research.

While DARPA did not fund the original RISC-V ISA definition, DARPA funding played a significant role in its later development. The linked articles on the SSITH Voting Machine and DOD presentation by Linton Salmon detail some of the areas where DARPA research continues to support RISC-V.

DARPA funds a large set of programs around open-source hardware technology. However, RISC-V International (the current owner of RISC-V) has never had DARPA funding, nor pursued or received funding from any government.

**Fun Fact: The RISC-V Name**

How did RISC-V get its name? The RISC portion is fairly obvious, but why is it number 5, and why is this represented with a Roman numeral?

The answer lies in a footnote in the introduction of the ISA spec itself:

The name RISC-V was chosen to represent the fifth major RISC ISA design from UC Berkeley (RISC-I [15], RISC-II [8], SOAR [21], and SPUR [11] were the first four). We also pun on the use of the Roman numeral “V” to signify “variations” and “vectors”, as support for a range of architecture research, including various data-parallel accelerators, is an explicit goal of the ISA design.

**RISC-V International**


**Introduction to RISC-V International**
So RISC-V is indeed a community. In fact, it is a global community spanning more than 40 countries and thousands of people. At the heart of this community is its home and guiding force — the RISC-V International Association.

RISC-V International, a Swiss non-profit organization, was formed in order to organize the activity around development of the ISA as well as other artifacts including software, non-ISA specifications, testing and compliance frameworks, and much more. RISC-V is organized by and for its members, which include over 200 large and small organizations as well as many hundreds of individual members who participate on their own, apart from companies or universities. The board of directors includes voting representatives from every membership level, so RISC-V is truly an egalitarian, community-based organization.

RISC-V International provides all of the management activities that are required by a global organization — executive management, promotion and marketing, member support, operations support, technical program management, and creative services. It also provides legal support for RISC-V intellectual property, which includes the specifications as well as RISC-V trademarks and imagery.

RISC-V International employs a small staff to assist and guide the community in organizing itself, and it maintains a contract with the Linux Foundation to provide management services, including human resources, IT and tools support, financial support, and more. The Linux Foundation brings many years of experience in running open source foundations and projects, which benefits the RISC-V community directly in helping to achieve its mission.

RISC-V International does not produce hardware. Instead, it provides the basis for all of its member organizations to create new technology based on the foundational support of the RISC-V ISA. As an open specifications project, RISC-V mainly produces documentation in the form of specifications like the Instruction Set Architecture, testing and debugging specifications, a trace specification, and other related artifacts. These are produced through a collaborative process among thousands of people, with rigorous feedback and oversight. RISC-V International was founded to shepherd this process, curate the specifications using the best practices of both standards organizations and the open source process, and to provide value for both members and the wider community.                                                                                                   

**Evolution of RISC-V International**

The RISC-V Foundation was founded in 2015 to build an open, collaborative community of software and hardware innovators based on the RISC-V ISA. The Foundation, a non-profit corporation controlled by its members, directed the development to drive the initial adoption of the RISC-V ISA.

Across 2018-2019, the RISC-V community reflected on the geo-political landscape and heard concerns from around the world that investment in RISC-V must come with IP access continuity to ensure a long-term strategic investment.

Incorporation in Switzerland has the effect of calming concerns of political disruption to the open collaboration model. As a non-profit, membership-based organization, RISC-V International does not maintain any commercial interest in products or services. There have not been any export restrictions on RISC-V in the US. The move does not circumvent any existing restrictions, but rather alleviates uncertainty going forward.

In March 2020, the RISC-V International Association was incorporated in Switzerland. Along with this, it shifted to a new, more inclusive membership structure. Members of RISC-V International not only have access to the RISC-V ISA specification, extensions, and related hardware and software, but also are eligible to participate in the development of these components.

The IP contributed and produced by RISC-V International is held under industry and global standard licenses that are already open to leverage by any company regardless of jurisdiction. This licensing is a common open source approach to foster collaboration that is not tied to any geographic regulation. Open Source IP has not been subject to export control.

We encourage organizations, individuals, and enthusiasts to join our ecosystem and together enable a new era of processor innovation through open standard and open source collaboration.

**RISC-V International Membership**

RISC-V is a non-profit membership-based organization that is driven by its members through representative governance on a board of directors, a technical steering committee, and many other working committees.

Membership is offered at various levels, and members receive a wealth of benefits. Most importantly, the membership process provides intellectual property projection for all members as well as provenance and IP security for the RISC-V ISA itself, which is RISC-V International’s top priority. All members are able to participate fully in the technical development process as well as in project administration through various working groups and committees. Members are also able to participate in a number of annual events and workshops and to stay on the leading edge of RISC-V development. All benefits are outlined on the RISC-V membership page.

So, why does RISC-V insist on membership rather than opening contribution and participation to the general public in the manner of the Linux kernel and many other open source software projects?

The primary reason for this is the IP protection just mentioned. The RISC-V membership agreement and the Articles of Association provide solid protection, but their scope is limited to members who actually sign the agreement.

While active participation is limited to members for this reason, RISC-V does make the entire technical process transparent (in read-only fashion) to non-members, and provides a wealth of learning opportunities as well as a set of public discussion lists where experienced RISC-V developers often contribute.

Membership in RISC-V is free for individual people, academic institutions, and non-profit organizations. For-profit companies have three membership levels available with annual dues, which support the ongoing collective support, facilitation, and advocacy of RISC-V as well as the following programs to foster the technical development, academic inclusion, market adoption, and industry visibility of our RISC-V community and members.

All Organizational members — Premier, Strategic, and Community Organization — have access to the RISC-V Trademark, which includes the RISC-V name and logo.

**RISC-V International Governance**

RISC-V International is governed by its Board of Directors. The Board is composed of Directors elected to represent all classes of membership to ensure the offering of a strategic voice at all levels. In addition, the Technical Steering Committee (TSC) provides leadership to the organization’s technical initiatives in setting long-term strategy, forming tactical committees and work groups, and approving technical deliverables for ratification or release.

RISC-V International also supports and drives ad hoc and standing groups to pursue specific industry, geographic, and strategic interests through a variety of constructs. The aim of RISC-V International is to guide and facilitate the broadest and most effective collaboration for the benefit of their member community.

**The RISC-V Community**


**RISC-V Community Working Model**

Community development is core to RISC-V International – there is no single company behind the scenes, and without the active community of architects and developers, there would be no RISC-V.

Specification development teams – whom we call the “tech” community – are composed of RISC-V International members, including both individuals and organizations. Although each member participates at their own level, we welcome everyone’s voice in the development process. Working groups and committees are chaired by member organizations, but it is possible for sufficiently enthusiastic and skilled individual members to help lead a working group if they earn support from the community and the Technical Steering Committee (TSC).

All members are welcome to participate and contribute in technical groups through mailing lists, meetings and workshops, webinars and conferences, and in many other ways. The technical working groups are publicly visible so that non-members can also follow discussions and progress.

In addition, there are three public forums where anyone may participate:

The RISC-V public mailing lists, particularly ISA-Dev and SW-Dev, which date back to the earliest days of RISC-V
The Exchange forums which provide a focused discussion point for items that appear on the RISC-V Exchange
The RISC-V Slack channel for live chat

**RISC-V’s Relationship with the Linux Foundation**

In November 2018, the RISC-V Foundation announced a joint collaboration with the Linux Foundation. As part of this collaboration, the Linux Foundation provides operational, technical, and strategic support for RISC-V International, including member management, accounting, training programs, infrastructure tools, community outreach, marketing, legal, and other open source services and expertise.

**The RISC-V Ecosystem**

As previously mentioned, RISC-V relies on its members to operate. The body of members across many different technical and application areas is known as the RISC-V Ecosystem. You can look at a comprehensive view by visiting the RISC-V Landscape website. 

There you’ll find an interactive view of key RISC-V contributors with clickable links to learn more about them. These contributors are organized by the type of product or service they provide, both in software and hardware. There are categories like applications, libraries, operating systems, implementations, and so on.

The RISC-V Ecosystem shows some of the numerous areas of application where you may contribute.

![Screenshot 2024-11-10 202757](https://github.com/user-attachments/assets/743b633b-441b-4ceb-9ca3-68a715e3c420)

The RISC-V ecosystem is constantly growing, as more and more areas of application continue to emerge. The RISC-V ecosystem is also organized separately in certain segments. For example, you can learn about the RISC-V Software Ecosystem by visiting the Rise project website. This is an effort led by industry leaders to promote the development of open software for RISC-V .

Just by looking at the main member logos, you may get an idea of how serious the software industry is about RISC-V, and the type of investment that is being put into the future of computing with this architecture.

**Communication Channels**

Communication is the most critical part of community-based development, whether in open source software, open specifications, open standards or any other type of shared resource development. RISC-V uses best practices drawn from decades of experience in open source and academia.

The technical organization operates on a group of policies which are often updated to include best practices. These policies form the basis for the development processes within RISC-V and enable more than 2,000 developers to work together.

**The RISC-V Exchange**

The RISC-V Exchange is a special resource that provides a window into work that people have accomplished around the world in the RISC-V community, including educational material, physical hardware, IP cores, and a great deal of software. This section of our website is growing as hardware and software continue to be created.

**Contribute to RISC-V**

There are as many ways to contribute to RISC-V as there are components in an instruction set architecture’s ecosystem.

Here are some ways you may contribute to the RISC-V community:

Build RISC-V knowledge through the Learn resources.

Become a RISC-V Ambassador technical expert.

Post RISC-V technical position openings on RISC-V Careers.

Become a mentor and guide a RISC-V Mentorship project.

Help maintain the technical specifications.

Write and share your own RISC-V projects.

For a detailed list of ways you may contribute, be sure to read the RISC-V Member Benefits and Welcome presentation.

**Types of Contributions**

Technical Contributions

To learn about the process of contributing to RISC-V on a technical level, please read the Developer Getting Started Guide in the RISC-V Technical Wiki.

To contribute to a specification or a technical area, you may look for the most relevant group in Groups.IO, join it, follow the discussions on the mailing list, attend the meetings, and volunteer to help.

To propose a new group, specification, or topic, send an email to help@riscv.org for guidance on where to start.

Proposing New Instructions

RISC-V was designed to allow anyone to add new instructions to the base ISA and any of its extensions. You can do this freely on your own implementations, but you may also contribute to the official ISA specifications. For the latter, you must become an active member of the RISC-V community in charge of maintaining the documents you intend to contribute to. These communities are specified in the RISC-V Technical Wiki.

Identifying and Resolving Issues in GitHub

The RISC-V instruction set architecture (ISA) and related specifications are developed, ratified and maintained by RISC-V International contributing members within the RISC-V International Technical Working Groups. Work on the specification is performed on GitHub, and the GitHub issue mechanism can be used to provide input into the specification.

**Summary**

Let us recap on what we covered in this chapter:

We went through the philosophy of RISC-V.

We learned about the goals of RISC-V International as a community-driven organization.

We described the organization around the RISC-V community.

We reflected on how member organizations work together to develop an open source community.

We also gave you a primer on how to contribute and make a difference within the RISC-V community.

Feel free to come back to this material if you need a refresher in the future.

**EXPLORING THE RISC-V INSTRUCTION SET ARCHITECTURE**

**Introduction**

**Chapter Overview and Objectives**

It’s time to get technical!

In this chapter, we will go through the heart of RISC-V — the Instruction Set Architecture (ISA). We will unravel the world of RISC-V instruction formats: From R-type to J-type, we will explore these diverse formats that define how instructions are structured. You will gain a basic understanding of how data is processed within the RISC-V architecture.

Going deeper, we will explore the modular nature of RISC-V to learn about its base ISAs and the many options for ISA extensions designed to allow RISC-V to meet the computational demands of the whole spectrum of today’s applications.

Our journey would not be complete without an exploration of the RISC-V register file. These registers serve as the guinea pigs of the architecture, storing data and witnessing its manipulation during program execution. We will decipher the purpose of different registers, shedding light on their roles in the assembly language.

Furthermore, inside the ISA you will discover the core principles that underpin RISC-V. From fixed instruction length to the load/store architecture, these principles are the embodiment of simplicity, efficiency, and compatibility that make RISC-V a groundbreaking technology.

By the end of this chapter, you should be able to:

Recognize the fundamental design principles and basic technical features of the RISC-V instruction set.

Recognize the structure of the different RISC-V instruction types, and the functions of the instructions within each type.

Describe the concept of modularity applied to an instruction set and how RISC-V in particular achieves it.

Identify some common RISC-V extensions and what functionality they add to the basic instruction set.

Discuss privilege modes and the memory model.

Let’s demystify the world of the RISC-V Instruction Set Architecture.

**RISC-V Specification**

**The RISC-V ISA Specification Documents**

The RISC-V ISA was defined while avoiding implementation details as much as possible. It should be read as the software-visible interface to a wide variety of implementations rather than as the design of a particular hardware artifact. However, multiple design decisions were influenced by hardware implementations in the spirit of simplifying the ISA, for example separating the multiplication extension from the base integer ISA.

The RISC-V manual is structured in two volumes: 

The first volume covers the design of the base unprivileged instructions, including optional unprivileged ISA extensions. Unprivileged instructions are those that are generally usable in all privilege modes in all privileged architectures, though behavior might vary depending on privilege mode and privilege architecture. 
The second volume provides the design of the first privileged architecture.

**RISC-V: A Modular ISA**

Being the fifth generation of a research project that started in 1980, RISC-V is a seasoned architecture designed to succeed where others have failed in the past, learning from their mistakes. For this reason, RISC-V was designed as a modular ISA, as opposed to the traditional incremental ISAs in commercial processors like the ARM Cortex family.

This modularity means that a RISC-V implementation is composed of a mandatory base ISA and a number of ISA extensions so that custom CPUs may be tailored to the needs of the application. Any extension can be used or left out for a specific implementation.

Conversely, an incremental architecture requires an ISA to contain all the ISAs contained in the ISA it extends. For example, the ARM Cortex-M4 instruction set contains all the instructions in the Cortex-M3 instruction set, and in turn, all those in the Cortex-M0+ instruction set. There is no way an ARM Cortex-M4 processor would only contain instructions from the M4 and M0+ instruction sets, skipping the instructions of the M3 instruction set in the middle.

A popular RISC-V core for a number of embedded microcontrollers available today implements the RV32IMAC ISA. Let us discuss what this nomenclature means.

The naming convention for custom RISC-V ISAs consists of the letters RV (for RISC-V) followed by the bit-width, and then a series of 1-letter identifiers for the base ISA and its extensions.

With this in mind, RV32IMAC means:

RV32I: A 32-bit CPU with the Base Integer ISA. This includes the absolutely necessary instructions for basic operation.

M: The Integer Multiplication and Division extension.

A: The Atomic Instruction extension.

C: The Compressed Instruction extension. This extension provides an alternative 16-bit encoding for a special subset of existing RV321 instructions, which are encoded in 32 bits.

In the image below, we have a graphical representation of the unprivileged RV32IMAC instruction set. Notice that the instruction set is showing the modular (not incremental) nature of RISC-V. A mandatory Base ISA is combined with a set of extensions.

![Screenshot 2024-11-10 211717](https://github.com/user-attachments/assets/50327a85-b201-41f0-ada0-af8431ae6cf0)

RV32IMAC Instruction Set
Retrieved from RISC-V, Wikipedia (author Eduardo Corpeño)
 
Another popular ISA is the RV32IMAFD, often abbreviated as RV32G. The letter G does not represent an ISA extension, but it stands for General.

To learn more about the RISC-V ISA, consider reading the book titled The RISC-V Reader, by David Patterson and Andrew Waterman. The English version is very inexpensive, and the Spanish, Portuguese, Chinese, and Korean translations are free to download.

**RISC-V Instruction Set Architecture Primer**

**Defining an Instruction Set Architecture (ISA)**

An instruction set architecture (ISA) is an abstract model of a computer. It is also referred to as architecture or computer architecture. A realization of an ISA, such as a central processing unit (CPU), is called an implementation. Some ISAs you may have heard of include x86, ARM, MIPS, PowerPC, or SPARC. All of these ISAs require a license to implement them. On the other hand, the RISC-V ISA is provided under open source licenses that do not require fees to use.

**How the RISC-V ISA Is Different**

The most notable difference between RISC-V and other ISAs is that RISC-V is developed by a member organization that is completely free to join and licenses its ISA with permissive open source licenses. This means that anyone can contribute to the specifications, and no one company or group of companies can drive the direction of the standards. The Technical Steering Committee (TSC) provides leadership to our technical initiatives and approves technical deliverables for ratification or release. 

**Collaborative Development Model**

A RISC-V Specification starts its life as a Task Group approved by the Technical Steering Committee (TSC). Once a Task Group has an approved charter, they begin work publicly on GitHub by writing their documents in AsciiDoc format. These repositories on GitHub can only receive pull requests from RISC-V International members, however the work is done publicly and transparently. For groups who choose to take minutes, those minutes from the Task Group meetings are published publicly as well. The public is free to submit issues to the GitHub repository in order to give early feedback on any specification. 

Non-ISA specifications and standards (e.g., processor trace, architectural tests, software overlay) are developed in a similar fashion. RISC-V Specifications live on GitHub and are housed alongside dozens of software projects. A list of ratified specifications and the links to their GitHub repositories can be found on the RISC-V Specifications website. 

**RISC-V Extensions Lifecycle**

Every modular specification of RISC-V goes through a design process, where the maturity of the design is indicated by its status, which may be Open, Frozen, or Ratified.

RISC-V International specifies a procedure to propose an ISA extension that anyone, in principle, can follow. The main steps are summarized as follows:

An extension being developed by its proponent and/or the community at large is referred to as in "Open" status.
When all the main features of the extension have been developed to the point that no substantial modifications are deemed possible, except for very minimal updates, the extension is referred to as in "Frozen" status.
A frozen extension is subject to a period of public review for further refinement and to a final ratification-by-vote, after which the extension is referred to as in "Ratified" status.
To learn about the lifecycle of a RISC-V Specification, you may read the RISC-V Lifecycle Guide.

Each RISC-V extension goes through several stages on its way to ratification. In this section we will briefly review each stage known as a “milestone”. The RISC-V Lifecycle guide defines these milestones as follows.

 ![Screenshot 2024-11-10 214855](https://github.com/user-attachments/assets/b30d7940-5182-4472-87b7-d94b45acb13e)

The Plan Milestone creates two key documents for use throughout the whole lifecycle, the Ratification Plan and the Status Checklist.

The Development Milestone creates the early versions of the specification and declares them reasonably stable.

The Stable Milestone continues specification development until it is self-consistent and stable.

The Freeze Milestone brings the document to feature complete, declares that no substantive changes are planned, and prepares the document for Public Review.

The Ratification-Ready Milestone holds the Public Review, addresses any issues, and performs final activities before asking for TSC Approval and Board of Directors Ratification.

The Ecosystem Development Milestone manages on-going open source software community work across the multitudes of projects which can be impacted by a specification in a continued effort to achieve upstream community support.

Once an extension has been ratified, it is added to either the Unprivileged or Privileged Specification. Occasionally a specification is created as part of a separate document, with the debug specification being the most common example. However, this is a rare case and usually indicates that the extension is not part of the ISA, but rather a “standard” or “non-ISA specification”. We will now review the Unprivileged and Privileged Specification in greater detail.

For full details on this process, refer to the following documents:

The RISC-V Lifecycle Guide details the full traditional procedure to ratify an extension;
The Fast Track Architecture Extension Process presents a reduced faster version of the procedure for small extensions; and
The Ratification Policy presents the criteria with which the proposed extension proceeds through the various steps of the ratification process leading to the vote by the Technical Steering Committee (TSC).

**Organizing the Specifications**

The RISC-V ISA is broken up into two parts:

Volume 1, Unprivileged Specification
Volume 2, Privileged Specification

To understand why the specification is broken up into two different parts, we must first understand a bit about computer architecture and security. Historically, processors used hierarchical protection domains, often called privilege rings, to protect data and code from malicious actors. For illustration purposes, the following picture shows the privilege rings for the x86 processor, by Intel, along with their common uses.

![Screenshot 2024-11-10 215410](https://github.com/user-attachments/assets/c4e788e6-0f4d-4b38-bf79-8a5fbf83a440)

The most privileged code runs in “Ring 0” and has access to the entire system. The processor will decide which privileges to grant executing code based on the privilege level. As an example, accessing memory by physical address may be restricted to “Ring 0” such that other rings must reference the virtual address space. Typically the processor can run in only one of the privilege modes at a time and there are special instructions to move between modes. All of these details can change from system to system, however they must follow the rules set out in the specification documents of a given architecture.

RISC-V has three privilege levels: User Mode (U-mode), Supervisor Mode (S-mode), and Machine Mode (M-mode). One can think of these as “Ring 2”, “Ring 1”, and “Ring 0” respectively. Other modes like a hypervisor mode (H-Mode) are available as variations of these 3 basic modes.

Much like in the figure above, U-mode is for user processes, S-mode is for kernel and/or device drivers, and M-mode is used for bootloader and/or firmware. Each privilege level has access to specific Control and Status Registers (CSRs), which are special registers that report the state of the system, or control its behavior. Higher privilege levels can access the CSRs of less privileged levels.

**Unprivileged Specification**

**Inside the Unprivileged Specification**

Simply put, the unprivileged specification details items that are not related to machine mode (M-Mode) or to Supervisor Mode (S-Mode). The unprivileged specification includes the base Integer (I) ISA as well as extensions to that base, like float (F), double (D), compressed instructions (C), and many more.

The base instruction sets describe the instruction format, basic integer instructions, load & store instructions, and other fundamental details of the ISA. We break the base ISAs into several variants:

RV32I - Integer 32-bit

RV32E - A version of RV32I with fewer registers for embedded applications

RV64I - Integer 64-bit

RV128I - Integer 128-bit

All these Base ISAs either reduce or extend off the RV32I base instruction set. As an example, RV64I widens the integer registers and the supported user address space to 64 bits. This means that the LOAD and STORE instructions work a bit differently than in RV32I and the unprivileged specification contains the chapter explaining these differences.

**The RV32I Base Integer ISA**

With only 40 instructions, the RV32I base integer ISA implements the absolutely necessary operations to achieve basic functionality with 32-bit integers (its 64-bit variant is RV64I). This ISA, encoded in 32-bits, includes instructions for:

Addition

Subtraction

Bitwise logical operations

Load and store

Jumps

Branches

The Base Integer ISA also specifies the 32 CPU registers, which are all 32-bits wide, plus the program counter. The only special register is x0, which always reads 0, as implemented in many previous RISC ISAs.

Although all registers are available for general purpose, the application binary interface (ABI) specifies a purpose for each of them, according to its calling convention. This means that some registers are expected to hold temporary or saved data, pointers, return addresses, and so on.

The RV32I register file, showing the hardware register names and their assigned functionality as specified in the RISC-V application binary interface, is presented in the table below. 

![Screenshot 2024-11-10 223040](https://github.com/user-attachments/assets/5b0c3325-c167-4dd5-a56c-9fa1b38227ef)

**Control and Status Registers (CSRs)**

Control and Status Registers (or CSRs for short), are a separate bank of registers with a separate 12-bit address space, limiting their number to 4096. They usually contain various CPU information, like timers, counters, flags, manufacturer information and other data. 

CSRs are special registers designed to control and monitor the processor's operation. They serve as the mechanism through which software interacts with hardware to adjust settings, manage exceptions, and acquire information about the processor's status. Understanding CSRs is essential for any RISC-V programmer, as they allow precise control over the processor's behavior and enable efficient system programming.

The Zicsr extension contains instructions intended for manipulation of CSRs, such as CSRRW (CSR read and write), CSRRS (CSR read and set), and CSRRC (CSR read and clear). These instructions allow software to read and modify the values in the control and status registers. The CSR instructions are covered in chapter 2.8 of the Unprivileged Specification document.

There are several important Control and Status Registers (CSRs) in the RISC-V architecture, each serving a specific function. Here are a few of the most important CSRs:

1.mstatus (Machine Status Register): This CSR is arguably the most critical one as it controls and monitors the machine's operating mode and privilege level. It contains fields for controlling interrupt enable/disable status, setting the privilege level (M-mode, S-mode, U-mode), and various flags that influence the processor's behavior. It is fundamental for privilege level transitions and interrupt management.

2.mepc (Machine Exception Program Counter): Stores the program counter value of the instruction that caused an exception or interrupt in machine mode. It determines where the program should resume execution after handling the exception.

3.mtvec (Machine Trap-Vector Base Address): Specifies the base address of the trap handler for machine mode, determining where the processor should jump to when an exception occurs.

4.mcause (Machine Cause Register): This CSR provides information about the reason for the most recent exception or interrupt. It distinguishes between exceptions and interrupts and gives a code indicating the specific cause, such as a page fault or a software interrupt.

5.misa (Machine ISA Register): Specifies the supported instruction set extensions for the processor, allowing software to determine the capabilities of the RISC-V processor. It also encodes the bit width of the base ISA (RV32, RV64, or RV128).

These CSRs are fundamental for the operation of a RISC-V processor, enabling privilege mode control, exception handling, and providing information about the processor's capabilities and recent events. There are many more CSRs that serve important functions, these five are among the most critical for basic processor operation and software development.

**Control and Status Registers (CSRs)**

Control and Status Registers (or CSRs for short), are a separate bank of registers with a separate 12-bit address space, limiting their number to 4096. They usually contain various CPU information, like timers, counters, flags, manufacturer information and other data. 

CSRs are special registers designed to control and monitor the processor's operation. They serve as the mechanism through which software interacts with hardware to adjust settings, manage exceptions, and acquire information about the processor's status. Understanding CSRs is essential for any RISC-V programmer, as they allow precise control over the processor's behavior and enable efficient system programming.

The Zicsr extension contains instructions intended for manipulation of CSRs, such as CSRRW (CSR read and write), CSRRS (CSR read and set), and CSRRC (CSR read and clear). These instructions allow software to read and modify the values in the control and status registers. The CSR instructions are covered in chapter 2.8 of the Unprivileged Specification document.

There are several important Control and Status Registers (CSRs) in the RISC-V architecture, each serving a specific function. Here are a few of the most important CSRs:

1.mstatus (Machine Status Register): This CSR is arguably the most critical one as it controls and monitors the machine's operating mode and privilege level. It contains fields for controlling interrupt enable/disable status, setting the privilege level (M-mode, S-mode, U-mode), and various flags that influence the processor's behavior. It is fundamental for privilege level transitions and interrupt management.

2.mepc (Machine Exception Program Counter): Stores the program counter value of the instruction that caused an exception or interrupt in machine mode. It determines where the program should resume execution after handling the exception.

3.mtvec (Machine Trap-Vector Base Address): Specifies the base address of the trap handler for machine mode, determining where the processor should jump to when an exception occurs.

4.mcause (Machine Cause Register): This CSR provides information about the reason for the most recent exception or interrupt. It distinguishes between exceptions and interrupts and gives a code indicating the specific cause, such as a page fault or a software interrupt.

5.misa (Machine ISA Register): Specifies the supported instruction set extensions for the processor, allowing software to determine the capabilities of the RISC-V processor. It also encodes the bit width of the base ISA (RV32, RV64, or RV128).

These CSRs are fundamental for the operation of a RISC-V processor, enabling privilege mode control, exception handling, and providing information about the processor's capabilities and recent events. There are many more CSRs that serve important functions, these five are among the most critical for basic processor operation and software development.

**ISA Extensions**

The unprivileged specification also contains the descriptions of the extensions to these base ISA’s. Again, any extension that does not require M-mode to operate can be described in the unprivileged specification.

Each extension to the base ISA is developed and maintained by a task group.

Once ratified, these extensions are added to the unprivileged specification. Up ahead we will go through a few of the most popular RISC-V ISA extensions.

