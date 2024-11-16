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

**The M Extension, for Multiplication**

The RV32M extension implements 8 instructions to perform multiplication and division on integers (RV64M adds 5 instructions to those 8).

Chapter 7 of the unprivileged specification describes how integer multiplication and division should be accomplished. It describes how each of the multiplication instructions will behave, which registers are used for the multiplier and multiplicand, and where the result will be stored. It does the same for division since functionally one can view division as simply the inverse of multiplication.

It may seem odd that this extension is not required. However, for many embedded processors, multiplication can be done in software if it is not required very often or even at all. Removing this logic from a processor saves money on development, keeping the end product cost lower. It also reduces the area required inside the chip, and energy consumption in the final application.

**The F and D Extensions, for 'float' and 'double'**

**F is for float**

The F extension adds support for single-precision floating-point arithmetic operations. Single-precision floating-point numbers are typically represented using 32 bits, conforming to the IEEE 754 standard.

This extension introduces single-precision floating-point registers (f0 to f31) and a set of single-precision floating-point instructions for operations such as addition, subtraction, multiplication, division, and conversions between integer and single-precision floating-point values.

The F extension also includes instructions for handling special values, like NaN (Not-a-Number) and infinities, and for comparing and rounding single-precision values.

**D is for double**

The D extension extends the floating-point capabilities of RISC-V to include double-precision floating-point arithmetic operations. Double-precision numbers use 64 bits for representation and also follow the IEEE 754 standard for double-precision arithmetic.

With the D extension, double-precision floating-point registers f0 to f31 are now 64-bit wide, and it supports instructions for double-precision arithmetic operations, conversions between integer and double-precision values, and handling special values.

Double-precision arithmetic is particularly important for scientific and engineering applications that require higher precision than single-precision arithmetic can provide.

Again, many embedded applications do not require floating point logic, and hence these extensions are not part of the Base ISAs.

**The C Extension, for Compressed Instructions**

The compressed instruction set extension is a clever addition to the RISC-V ISA, which provides an alternative 16-bit encoding for a special subset of existing instructions, reducing static and dynamic code size.

After analyzing countless lines of code generated by modern optimizing compilers, the creators of RISC-V identified the most popular instructions, and created 34 16-bit versions of those popular instructions, giving up some of the functionality of their full 32-bit versions (which are still available in the RV32I base ISA anyway).

Typically, 50%–60% of the RISC-V instructions in a program can be replaced with RVC instructions, resulting in a 25%–30% code-size reduction. The C extension is compatible with all other standard instruction extensions. These 16-bit instructions may be freely intermixed with 32-bit instructions. This means that any instruction can start on any 16-bit boundary. As such, with the addition of the C extension to any system, no instructions can raise instruction-address-misaligned exceptions.

This compression is possible because for these special instructions:

Some registers are more popular than others (as per the ABI).
One operand is usually overwritten.
There are some preferred immediate values.
This allows encoding the instructions for a limited number of registers as operands, specifying only 2 registers instead of 3, using small immediate values, all of this in 16 bits.

By compressing the most frequently used instructions, you have a better chance of compressing your programs significantly.

In the following picture (which you have seen before), compare the green block (RV32I) with the orange block (RV32C). Consider that RV32I instructions are 32 bits wide, while RV32C are 16 bits wide.

![Screenshot 2024-11-12 224652](https://github.com/user-attachments/assets/986dca7c-2f67-49b9-9167-1a420e5616f4)

So, instructions from the C extension are pseudoinstructions, right?
Wrong!

Pseudoinstructions are special instructions added to the assembly language to make programming less cumbersome. Pseudoinstructions have a direct translation to machine code, and are supported by assemblers and compiler toolchains.

The C extension provides hardware support for specific versions of existing base ISA instructions.

Thus, one difference is that pseudoinstructions are a logical addition (software), whereas instructions from the c extension represent a logical and a physical addition (software and hardware).

**More Extensions**

The open nature of RISC-V allows for a rich proliferation of other extensions that we will not cover. Here we have some examples:

The A extension, for Atomic Memory Operations

The Q extension, for quad-precision floating-point operation, introducing 128-bit wide floating point registers

The B extension, for bit manipulation

The S extension, for supervisor operation

The H extension, for hypervisor operation

The L extension, for decimal floating-point operation

The P extension, for Packed-SIMD instructions

The V extension, for vector operations

The Zicsr extension, for manipulating CSR registers

The Zifencei extension, for instruction memory synchronization

Once again, this list is not exhaustive.

Almost all of the above extensions are ratified, and only the L and P extensions are still under discussion, and thus open.

**Fun Fact! Unsupported Instructions**

You may be wondering:

What happens when a RISC-V processor is executing a program that contains instructions it does not implement?

For example:

Suppose an RV32IAC processor fetches a multiplication instruction for execution. What is the processor supposed to do with that instruction if it does not implement the M extension?

Well, compilers are informed of the extensions included in the target CPU so that they can generate the best possible code. If the code contains an instruction from extensions that are missing in the physical CPU, the decoding of that instruction will trigger an illegal instruction exception. The software running on the CPU will have to handle this exception and take appropriate action, such as emulating the instruction or providing an alternative implementation, possibly from the standard library.

So, next time you see assembly code in a disassembly view, pay attention to the RISC-V assembly instructions that may not be supported by the target CPU. You may even want to check the execution of these instructions to get a better appreciation of what is going on.

**The RISC-V Instruction Set**

**Instruction Encoding**

The RV32I ISA specifies the following elements:

1 32-bit wide Program Counter Register

32 32-bit wide Registers named x0 to x31

40 Unique 32-bit wide unprivileged Instructions in six different formats (R, I, S, B, U, J) but with some recurring fields:

A major opcode in the 7 least significant bits of the instruction, identifying the instruction.

Source registers (rs1 always in bits 15 to 19, rs2 in bits 20 to 24).

Destination register (rd in bits 7 to 11) fields.

Function fields, or minor opcodes, named funct7 or funct3 depending on their bit width. Funct7 occupies the last 7 bits of the R type instruction and funct3 always occupies bits 12 to 14.

Immediate fields, which always tend to be towards the end (left side) of the instruction and are encoded differently depending on the instruction type.

24 additional unique 32-bit wide privileged instructions in two formats (R and I).

Among these elements, we are now interested in the encoding of instructions. The following table shows just that:

![Screenshot 2024-11-12 230534](https://github.com/user-attachments/assets/f00d4ede-7423-42cb-8840-2280e3260b15)

A key principle of RISC-V that stands out in this table is the fixed instruction length:

All instructions are encoded in 32 bits. No exceptions.

These instruction encodings are part of the RISC-V ISA's design and provide a structured way to classify and execute various types of instructions. They help make the RISC-V architecture efficient and suitable for a wide range of applications.

Immediates and Addresses

Other than opcodes and registers, any instruction encoding other than R-Type may contain immediates, that is a piece of data encoded directly in the instruction, rather than in memory or in a register. This data can represent either constants, to be used for example in arithmetic operations, or as memory addresses or offsets.

Different handling of immediates is the exact characteristic that defines the instruction types, but all of them tend to encode the immediates in similar positions in order to simplify the implementation of the hardware immediate decoder. All immediates decode to 32-bit wide values, but encoding varies by instruction.

**Instructions in Assembly Language**

Instruction mnemonics are used in RISC-V assembly language to represent specific instructions in a more human-readable form. A mnemonic is a short string of letters that represents a specific instruction. 

For example, in the instruction "add x1, x2, x3", "add" is the mnemonic that represents the add instruction. Functionally, that instruction means “add the contents of x2 with the contents of x3, and store the result in x1”.

When an assembler encounters a mnemonic in the source code, it will use that mnemonic to translate the instruction into the corresponding machine code representation of the instruction, along with the encoding of the operands.

For example, the instruction "add x1, x2, x3" is translated by the assembler into the machine code instruction 0x003100B3. This long hexadecimal number can be extended to binary as follows:

0000 0000 0011 0001 0000 0000 1011 0011

Which in turn can be separated as an R-Type instruction with the following fields:

![Screenshot 2024-11-12 231430](https://github.com/user-attachments/assets/b44f26e2-444f-42e2-a8b4-38df4f38bed9)

As shown above, these are the meanings of the bit fields in the encoded instruction:

funct7: 0000000

rs2: 00011, which means x3

rs1: 00010, which means x2

funct3: 000

rd: 00001, which means x1

opcode: 0110011, which means add

Keep in mind that mnemonics are used for both instructions and pseudoinstructions, which the assembler converts to machine instructions.
**
The RISC-V Instruction Set Reference Documents**

Now is a good time for you to review the (not so) many instructions in the RISC-V Instruction Set, especially because you have some understanding of the encoding of instructions.

As we have established by now, the instruction set is divided throughout the RISC-V base ISAs and extensions. Therefore, it is a good idea to have The RISC-V Instruction Set Manual Volume I: Unprivileged ISA handy in case you need to review some of the instructions in detail.

However, this document is very thorough and specific, so a simpler alternative like a quick reference document may be more convenient for you. We recommend the following:

A RISC-V Reference Card, by James Zhu. Skim through this short document to get familiar with the instructions in RV32I and many extensions.

The RISC-V Reference Card included in the previously mentioned book titled The RISC-V Reader, by David Patterson and Andrew Waterman (or the dedicated Appendix A: RISC-V Instruction Listings therein). You may want to get a copy of the book, but the reference card is free to download.

Please take the time to obtain one of these reference cards before moving on to the next page.

**Exercise: Using the RISC-V Reference Card**

Try the following exercise using either one of the RISC-V Reference Cards provided on the previous page.

Based on either of these reference cards, try to answer the following questions. Now, don’t dedicate more than 10 minutes to this exercise, and don’t worry if you cannot answer one (or any) of these questions. Some may require computer architecture savvy, which is not a requirement of this course. Either way, just give it a try.

1.Which bitwise logical operations are available?

2.Which conditional branches are available?

3.Which instructions use immediate values?

4.Are there any traditional instructions missing?

Once you have given this exercise a try, check your answers on the following page.

**Exercise Answers**

Here are the answers to the questions on the previous page.

Which bitwise logical operations are available?
AND

OR

XOR

Which conditional branches are available?
Branch if equal

Branch if not equal

Branch if less than (signed and unsigned)

Branch if greater or equal (signed and unsigned)

Which instructions use immediate values?

All except register operations and environment calls.

Are there any traditional instructions missing? Yes, quite a few!

Bitwise not

Branch if less or equal

Branch if greater than

Load immediate

No Operation (nop)

Unconditional jump

Subroutine call

Subtract immediate

Register Move/Copy

**A Few Peculiar RISC-V Design Decisions**

RISC-V has a few rather peculiar design decisions that may prove intriguing. You may have noticed some of the following curious design decisions, and may be wondering what the designers of RISC-V were thinking when they came up with them.

These design decisions reflect the RISC-V philosophy of providing a minimal, extensible base architecture, while leaving certain aspects like stack management, call conventions, and some basic operations to be defined by the ABI or the specific implementation. This approach promotes flexibility and adaptability for a wide range of applications and use cases.

**Introduction to the Privileged Specification**

The unprivileged instruction set architecture presented so far is not enough to run modern execution environments. As its name suggests, the privileged specification contains descriptions of the RISC-V ISA which operate in Machine Mode (M-mode) or Supervisor Mode (S-mode). These modes have elevated privileges and are therefore described in a completely separate document from the base ISA and standard extensions. This specification also contains additional functionality required for running rich operating systems like Linux.

In fact, the RISC-V privileged specification was designed to support virtualized systems implementing the typical software stack shown below:

![Screenshot 2024-11-12 233823](https://github.com/user-attachments/assets/434f3c70-8376-45d0-98df-02645d61b461)

The diagram shows a virtual machine monitor configuration where multiple multiprogrammed operating systems are supported by a single hypervisor. Each OS communicates via a supervisor binary interface (SBI) with the hypervisor, which provides the supervisor execution environment (SEE). The hypervisor communicates with the hypervisor execution environment (HEE) using a hypervisor binary interface (HBI), to isolate the hypervisor from details of the hardware platform.

This is the level of complexity expected in today’s computational systems, and RISC-V must be able to deliver the required capabilities.

**Machine-Level (M-Mode) ISA, Version 1.12**

This chapter describes the machine-level features available in machine-mode (M-mode). M-mode is used for low-level access to a hardware platform and is the first mode entered at reset, when the processor finishes initializing and is ready to execute code. M-mode can also be used to implement features that are too difficult or expensive to implement in hardware directly. A good example of this would be a watchdog timer implemented in low level software (firmware) which helps the system recover from faults. 

**Important Features of M-Mode**

Non-maskable interrupts

Non-maskable interrupts (NMIs) are only used for hardware error conditions. When fired, they cause an immediate jump to an NMI handler running in M-mode, regardless of how that hardware thread has its interrupt-enable bit set. In other words, that interrupt will be serviced without a way to block the service in configuration. Each NMI will have a “mcause” register associated with it. This allows implementations to decide how they wish to handle these interrupts and allows them to define many possible causes. NMIs do not reset processor state which enables diagnosis, reporting, and possible containment of the hardware error.

Physical Memory Attributes (PMA)

The physical memory map for a system includes address ranges like memory regions, memory-mapped control registers, and empty holes in the address space. Some memory regions might not support reads, writes, or execution; some might not support subword or subblock accesses; some might not support atomic operations; and some might not support cache coherence or might have different memory models. In RISC-V systems, these properties and capabilities of each region of the machine’s physical address space are termed physical memory attributes (PMAs).

The PMAs of some memory regions are fixed at chip design time — for example, for an on-chip ROM. Others are fixed at board design time, depending, for example, on which other chips are connected to off-chip buses. Some devices might be configurable at run time to support different uses that imply different PMAs — for example, an on-chip scratchpad RAM might be cached privately by one core in one end-application, or accessed as a shared non-cached memory in another end-application. Most systems will require that at least some PMAs are dynamically checked in hardware later in the execution pipeline after the physical address is known, as some operations will not be supported at all physical memory addresses, and some operations require knowing the current setting of a configurable PMA attribute.

For RISC-V, we separate out specification and checking of PMAs into a separate hardware structure, the “PMA checker”. In many cases, the attributes are known at system design time for each physical address region, and can be hardwired into the PMA checker. Where the attributes are run-time configurable, platform-specific memory-mapped control registers can be provided to specify these attributes at a granularity appropriate to each region on the platform (e.g., for an on-chip static random-access memory (SRAM) that can be flexibly divided between cacheable and uncacheable uses).

The details of PMAs could easily take up an entire chapter of this course. We will not cover memory-ordering PMAs, idempotency PMAs, coherence PMAs, or cacheability PMAs. The details of PMAs are described in detail in section 3.5 of the privileged specification. Advanced users may want to review this section.

Physical Memory Protection (PMP)

A common feature of most modern processors is some way of performing secure remote computation or a “trusted execution environment”. Examples of this technology include Intel Software Guard Extensions (SGX), AMD Secure Encrypted Virtualization (SEV), and Arm TrustZone. While the RISC-V ISA does not provide an end-to-end solution for Trusted Execution Environments, the Physical Memory Protection (PMP) capabilities are a solid foundation on which one might construct such a system.

RISC-V PMP limits the physical addresses accessible by software running on a hart (hardware thread). An optional PMP unit provides per-hart machine-mode control registers to allow physical memory access privileges (read, write, execute) to be specified for each physical memory region. The PMP values are checked in parallel with the PMA checks we covered in the last section. The granularity of PMP access control settings are platform-specific and within a platform may vary by physical memory region, but the standard PMP encoding supports regions as small as four bytes. The privileges of certain regions can be hardwired — for example, some regions might only ever be visible in machine mode but in no lower-privilege layers.

**Supervisor-Level (S-Mode) ISA, Version 1.12**

This chapter describes the RISC-V supervisor-level architecture, which contains a common core that is used with various supervisor-level address translation and protection schemes. Supervisor mode is deliberately restricted in terms of interactions with underlying physical hardware, such as physical memory and device interrupts, to support clean virtualization. In this spirit, certain supervisor-level facilities, including requests for timer and inter-processor interrupts, are provided by implementation-specific mechanisms. In some systems, a supervisor execution environment (SEE) provides these facilities in a manner specified by a supervisor binary interface (SBI). Other systems supply these facilities directly, through some other implementation-defined mechanism.

RISC-V supports Page-Based 32-bit, 39-bit, and 48-bit virtual memory addressing. The supervisor (S-Mode) memory-management fence instruction (SFENCE.VMA) is used to synchronize updates to in-memory memory-management data structures with current execution. Executing this instruction guarantees that any previous stores already visible to the current RISC-V hart (hardware thread) are ordered before all subsequent implicit references from that hart to the memory-management data structures.

Virtual Memory is a concept which takes several months of graduate level education to grasp and is beyond the scope of this course. It is enough for this course that you understand that RISC-V supports Page-Based virtual memory of several widths, and that there is a special S-Mode instruction used for synchronizing updates between hardware threads.

Chapter 3 Summary
Let us recap on what we covered in this chapter:

We explored the fundamental design principles and basic technical features of the RISC-V instruction set.

We saw the structure of the different RISC-V instruction types, and the functions of the instructions within each type.

We covered the concept of modularity applied to an instruction set and how RISC-V achieves it.

We discussed some common RISC-V extensions and the functionality they add to the basic instruction set.

Lastly, we briefly described the privilege modes and the memory model.

Feel free to come back to this material if you need a refresher in the future.

**HANDS-ON RISC-V ASSEMBLY LANGUAGE**

**Introduction**

**Chapter Overview and Objectives**

This chapter is all about RISC-V Assembly Language: The nuts and bolts behind making RISC-V systems work. We will dig into the language that connects what we understand with what the machine can execute. It is like learning the behind-the-scenes script that powers your favorite show. We will get acquainted with the RISC-V Assembly Language documentation, its features, and some assembly programming. We will also learn about the many elements in an assembly language program. Among these elements, we have directives, labels, mnemonics, operands, immediates, instructions, and pseudo instructions.

This course is intended for the general public, so our expectations are very basic and there are no hard requirements. You are welcome to try the coding examples in the simulator we will use (or any other of your choice), but you are certainly not required to do so. You may just sit back and enjoy the show.

By the end of this chapter, you should be able to:

Describe the RISC-V assembly language syntax and features.

Identify the many elements of a RISC-V assembly program, like directives, labels, mnemonics, and operands.

Identify the pseudoinstructions in a RISC-V assembly program.

Explain how Control and Status Registers are managed in the RISC-V assembly code.

Use immediate values properly in a RISC-V assembly program.

Get ready to dive into the core of how RISC-V really works!

About Assembly Language

You are about to become acquainted with the RISC-V assembly language syntax. Computers execute programs stored as binary data in memory. This data is encoded as machine code, which the CPU understands. Some examples of RISC-V machine code instructions are 0x000012B7, 0x00028313, 0x00500393, and 0x00000E13. Understandably, machine code is not very human-friendly.

Assembly language is distinct from machine language in that it is a human-readable representation of machine language. All assembly language instructions and pseudoinstructions have an exact translation to their corresponding machine language instructions.

In terms of levels of abstraction, assembly language has the lowest abstraction from a programmer’s perspective. Even lower levels are found in machine code, logic states stored in memory, and electrical signals traversing the hardware. Nevertheless, programmers usually start at assembly language as the lowest level of abstraction in computer programming. 

Assembly code is at a lower level of abstraction with respect to high level programming languages like C or Python. Although most of the code is usually written in a high level language, sometimes one has no choice but to code directly in assembly language.

**Features**

The RISC-V assembly language has a number of features that go hand in hand with the features of the RISC-V ISA. Among other features, we have the following:

1.The language was designed with simplicity in mind.

2.In general, binary operations like addition, AND, XOR, multiplication, and so on, specify 3 operands: 2 source registers with read access, and 1 result register with write access.

3.Support of pseudoinstructions to ease the task of writing assembly code.

4.Direct translation between assembly language and machine language.

**How the RISC-V Assembly Language Works**

The syntax of the RISC-V assembly language can vary depending on the specific variant or extension of the architecture and the assembler being used (the program that reads a text file with assembly code, and produces machine code).

**RISC-V Assembly Language Elements**

**Instructions**

A set of basic operations, such as arithmetic, load/store, and control flow, that are executed by the processor. In general, instructions consist of a mnemonic (a short but descriptive instruction name) and a series of operands (the registers or data to operate upon).

**Registers**

Processor-internal memory locations used to store intermediate results and control information.

**Labels**

Symbolic names for memory locations that can be used as targets for branch and jump instructions.

**Directives**

Special commands used to control the behavior of the assembler, such as setting memory regions or defining constants.

**Macros**

User-defined sequences of instructions that can be invoked with a single macro call.

**Pseudoinstructions**

Synthetic instructions that are translated by the assembler into one or more real instructions, allowing for a higher-level, more concise representation of the code.

These elements are combined to create RISC-V assembly programs, which are then assembled into machine code and executed by the processor.

**Assembly Language Syntax**

The RISC-V assembly language syntax follows the typical assembly language rules of other processors, supporting basic elements like instructions and labels, as well as directives and means to specify storage requirements.

In general, an assembly source file consists of a series of blocks of code, each specifying its memory section and storage requirements.

Up ahead, we will see what all the parts of an assembly program mean. For now, let’s skim through a Hello World example featured in the book The RISC-V Reader. It contains a block of executable code in the text section and a block of data with two strings in the read-only data section.

  .text                     # Directive: enter text section
  .align 2                  # Directive: align code to 2^2 bytes
  .globl main               # Directive: declare global symbol main

main:                       # label for start of main
  addi sp,sp,-16            # allocate stack frame
  sw ra,12(sp)              # save return address
  lui a0,%hi(string1)       # compute address of
  addi a0,a0,%lo(string1)   # string1
  lui a1,%hi(string2)       # compute address of
  addi a1,a1,%lo(string2)   # string2
  call printf               # call function printf
  lw ra,12(sp)              # restore return address
  addi sp,sp,16             # deallocate stack frame
  li a0,0                   # load return value 0
  ret                       # return

  .section .rodata          # Directive: enter read-only data section
  .balign 4                 # Directive: align data section to 4 bytes

string1:                    # label for first string
  .string "Hello, %s!\n"    # Directive: null-terminated string

string2:                    # label for second string
  .string "world"           # Directive: null-terminated string

**Assembler Directives**

RISC-V assembler directives are non-CPU instructions that provide information to the assembler (the program that produces machine code from a text file), but are not executed as machine instructions. They control the assembly process, specify data locations and provide information to linkers. 

**Common RISC-V Assembler Directives**

.align
Aligns the location counter to a specified power of 2 boundary.

.section
Specifies the section of the output file where the following data should be placed.

.byte
Defines an array of 8-bit values.

.half
Defines an array of 16-bit values.

.word
Defines an array of 32-bit values.

.data
Specifies the start of the data section where initialized data is stored.

.text
Specifies the start of the code section where instructions are stored.

.globl
Declares a symbol as global and accessible from other files.

.equ
Assigns a value to a symbol, useful for constants.

.string
Defines a string of ASCII characters with a null terminator.

These are some of the most popular RISC-V assembler directives, but there are many more. Consult the RISC-V ISA manual or the specific assembler documentation for a complete list.

**Reminder: The RISC-V Instruction Set**

This is a good time for a reminder:

Since we are about to see a few coding examples, it’s a good idea to have “The RISC-V Instruction Set Manual Volume I: Unprivileged ISA” handy in case you need to review some of the instructions in the code.

Also remember to have a quick reference document handy. Here are the links to the documents we recommended earlier:

A RISC-V Reference Card, by James Zhu
The RISC-V reference card included in The RISC-V Reader

**A Quick Review of the RISC-V Assembly Instruction Set**

Please have your RISC-V quick reference document handy to read more about some instructions we have selected and detailed in the following list. The list is not exhaustive, but attempts to represent most types of instructions, and it provides some important details we think you should know. 

The purpose of this exercise is to get you acquainted with the instruction set from an assembly language programmer’s standpoint, so that you may go back to your quick reference document whenever you need to learn more about a specific instruction. Keep in mind that your quick reference document may or may not have organized the instructions by their base ISA or ISA extension.

All of the following assembly language instructions have a corresponding RISC-V machine language instruction. In other words, these are not pseudoinstructions.

![Screenshot 2024-11-16 160838](https://github.com/user-attachments/assets/8600850d-7eee-49b5-8319-5fdb03ecb1e5)

**A Quick Review of RISC-V Pseudoinstructions**

Once again, have your RISC-V quick reference document handy to read more about some pseudoinstructions we have selected and detailed in the following list. 

A pseudoinstruction is a valid instruction in assembly language, which does not have a machine encoding but translates to one or more RISC-V machine instructions that end up performing its function.

In the following list we will showcase some pseudoinstructions and their usual implementation.

![Screenshot 2024-11-16 161002](https://github.com/user-attachments/assets/d94fe641-adbe-4f93-afa8-a88d79813c71)




 
