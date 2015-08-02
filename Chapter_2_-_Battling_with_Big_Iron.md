---
title: Chapter 2 - Battling with Big Iron
permalink: /Chapter_2_-_Battling_with_Big_Iron/
---

<div style="float:right; margin-left:1em;">
__TOC__

</div>
Unscrambling the code
---------------------

> *These modern accounting methods are a far cry from those employed in the days of King Henry 1, when the King’s finances were controlled by a small group of administrators selected from the baronage and the clergy. This body constituted the Exchequer, so called from the chequered tablecloth used to facilitate the counting of money.*
> New Zealand’s controller and auditor general, commenting on computer introduction in 1960.[1]

New Zealand was rapidly evolving from its rural roots and increasingly leveraging its industrial and commercial strengths, all of which required efficient communications. Many government departments, universities, and businesses were now on to their second and third generation of computing power and looking seriously at connecting them into networks.

The methods available were, however, highly proprietary, allowing only an IBM or Burroughs mainframe, for example, to connect to their own terminals and perhaps an identical machine across town over the telephone lines. If you had another brand of computer you were out of luck, unless you had some very resourceful technical types on staff. The government had several large computers processing the payroll of public servants, and for doing the public accounts and those of various trading departments.

By the early 1960s firms could communicate between head office and branches or with other businesses by leased telegraph circuits. Telegraph switching had been introduced in 1964 with automatic switching possible at the three main centres, with a special code for each station. By 1966 there were 441 telex subscribers and a public telex booth system launched in 1971. A faster automatic service of switching telegraphs on larger circuits was also possible.[2] In April 1970 the NZPO began offering its Datel (data/telephony) service, sending computer and telex data over dedicated lines at 2400bit/sec (bits per second).

The number of inland telegrams had declined markedly since the war, displaced by other forms of telephony. By 1950 there were 5.7 million telegrams sent, by 1970 it had dropped away to 1.95 million. Intensive development of telecommunications in the 1950s and early 1960s had created a network valued at £100 million, with the third-highest telephone density in the world behind the United States and Sweden but ahead of Canada.[3] Between 1950 and 1970 the number of telephone subscribers had grown from 250,000 to 800,000 and staff numbers at the NZPO had doubled to more than 32,000.[4] By 1971 the number of telephone users had passed the million mark.

The nation’s phone network came under increasing pressure – the so-called ‘broadband’ network was now carrying thousands of circuits. The first satellite station opened at Warkworth, north of Auckland, in 1971, hugely speeding up the delivery of television programmes and news from around the world. That gave TVNZ less reason to repeat content, and gave the Post Office an important alternative for reducing congestion with international phone calls. It also opened up new possibilities for computers to gain access to international databases.

In 1972 there were 200 business computers in the country, mainly unwieldy mainframes that needed huge, air-conditioned rooms to operate. They were fed punch cards and spat out their data on huge plan printers in plain Ascii-type characters. By 1969 nine government divisions had computers, with Treasury, the Department of Education and DSIR acting as bureaus for other departments including Social Security, the Post Office, and Railways. In 1970 two bureau operations were centralised, along with Statistics Department data processing staff, into the Government Computer Centre (GCS) as an independent unit within the Department of Internal Affairs. By 1972, it became the Computer Services Division (CSD), of the State Services Commission (SSC).[5]

By the mid-1970s the CSD had become a highly centralised operation, running four large computer centres and four data-preparation centres. The Vogel Computer Centre was operated by the Ministry of Works and Development as a science and engineering service for all government departments, under contract to the SSC, and used by a range of agencies including the Electricity Department, Forestry, and Broadcasting. The Wanganui Computer Centre was operated on behalf of the Police, Justice, and Transport ministries. The Trentham Computer Centre in Hutt Valley had been intended for the DSIR but didn’t become operational until 1978, and when it proved unsuitable for the task was relegated to handling the needs of Customs. In Wellington the Cumberland Centre housed the accounting functions for State Insurance, Government Life, the public service, and teachers in the education system. The Pipitea Computer Centre handled data for the Social Welfare, Inland Revenue, Valuation, and Housing departments.

All the CSD centres had data communications networks extending from Kaitaia in the north to Invercargill in the south. The Ministry of Defence, Post Office, Department of Health, and New Zealand Railways Corporation also retained their own equipment and computing organisations, including data communications networks. Most local authorities had their data processing needs met by computer bureaus.6

### Beggaring with the Burroughs

Across the universities the main communication between the key information science people was face to face, typically when two or three from each campus would meet with a government committee to discuss issues. The Department of Education had made computing a priority for all university campuses. The first breakthrough came in 1971 when the government, through the Vice Chancellor’s Grants Committee, arranged to buy five brand-new Burroughs 6700 (later Unisys) mainframes with a view to networking them.

The B6700 machines were an upgrade to the Burroughs 6500; large systems with integrated circuits that could handle up to four processors for symmetrical multiprocessing (although their new owners could only ever afford to use the single processor version). The machines were valued at about a million dollars each and the terminals that connected to them were $9000. They featured a stack architecture[6] with instruction sets designed for easier running of software than the traditional hardware-based approach. They had specific support for high-level languages such as Fortran and Cobol as opposed to assembly language. All systems software was written in an extended version of ALGOrithmic Language (ALGOL). The Burroughs could compile as quickly as they could read the source code from punched cards, and were reputed to have the fastest card readers in the industry.[7]

Auckland University just scraped in to take delivery of the first of the B6700 machines in March 1971. “We couldn’t have a computer because we didn’t have a building to put one in, we couldn’t have a building because we didn’t have a computer centre director, and we couldn’t have a director until we’d decided which computer we were likely to buy,” recalled former IT director and computer science associate professor, Nevil Brownlee. Neil Mowbray, who was professor of civil engineering at the time, somehow succeeded in getting all three just in time to qualify for the Vice Chancellor’s Grants Committee funds for the Burroughs acquisition. “For a brief spell of about three months we had the most powerful computer in New Zealand,” Brownlee said.

However, as the deal was being signed off, it became apparent that Lincoln College and Waikato University were not included. Waikato was expected to make do with its existing IBM 1130 and a link to Auckland University’s machine. Neither Auckland nor Waikato had a faculty directly related to computing, so it was felt their needs could be met by one system. It was clear Waikato, which had relied on a small group of academics to administer computing on campus, needed to formalise the position of computer department director if it was to attract any future computing investment.

Meanwhile, it stubbornly refused to sign off on the deal, which saw it sidelined as a poor cousin to Auckland. By early 1974 the contract for the Burroughs B6700 in Auckland and the terminals at Waikato were still unsigned. The plan had shown four terminals connected to a DC1200 terminal unit linked to Auckland via a modem connection. However the terminals never worked as specified and would only operate a card punch, card reader, and line-printer and needed to be re-configured. Auckland University was still quite disorganised in the computing field and had no formally organised Computer Science Department, which meant Waikato got very little service. Burroughs’ reputation was on the line as long as Waikato refused to sign off. Eventually it conceded under ministerial pressure.[8]

“The DC1200 was a bottleneck from day one. Enrolments crept towards 800 students. Two key punch operators working full time were snowed under. COBOL programs took three to four days to get punched and verified before being sent up the line to Auckland to be compiled and run. Then there was the two-day delay before the results were received. The error rate was high, even though the programs were punched twice to check the input, they would invariably come back with compiler errors; weeks might pass before a single program would successfully compile and run,” claims the university’s computing history site.[9]

John Houlker had been studying physics and mathematics at Waikato University when an interest in computers intruded. Sidelining his original aspirations, he hung out in the CSD and began working there part-time. His first experience was with the Burroughs machines. “They were kind of elegant, really. I still have a soft spot for those machines. They were a fairly advanced architecture for their time. The promise was that having a remote link through a leased line to Auckland University’s Burroughs machine would be just as good as having our own machine. I think we got short changed. Let’s just say as a student operator, I noticed features meant to ensure we had equal share were missing in the control system at the Waikato end, so I reprogrammed the interface. Initially we didn’t notify Auckland what we had done but after a while I think they were surprised to learn what had been going on. Certainly for the Waikato Computer Department it was an improvement.”

Lincoln College had also missed out on the computing spend-up and was forced to share with Canterbury University in Christchurch. Canterbury had built an internal network based on the Burroughs equipment but it could only communicate with its own terminals. When Robin Harrington[10] joined the CSD in 1972 he was told the researchers wanted equipment they couldn’t buy off the shelf connected to the computer. “My brief was to source the pieces and connect them together.” One major challenge was linking the Burroughs mainframe to Lincoln College but as Waikato University had found out, the equipment provided by Burroughs to achieve this was less than satisfactory.

One of the development tasks was to replace an IBM 1620 operating a plotter, with a Digital Equipment Co (DEC) PDP-11[11] version and get that to work with the Burroughs. “We displaced the Burroughs DC1200 unit and developed our own protocols. Then the engineers had the idea of using the same technology as a remote job entry system, to provide a link to the engineering school 1km away. It was more reliable than the equipment Burroughs supplied. So Waikato used our technology to replace their Burroughs box; we put a larger one into Lincoln and sold one to the Reserve Bank in Wellington as well.”

The Digital protocols, needed a more advanced operating system so Canterbury built its own. CSIROnet in Australia were doing a similar thing and the Department of Scientific and Industrial Research (DSIR) mimicked that.

### Pushing the boundaries

In 1973 discussions began on how to connect the Burroughs B6700 mainframe at Victoria University to Aloha University in Hawaii using the Post Office’s X.25 packet network. The pioneering Alohanet, developed at the University of Hawaii and deployed from 1970, used ham radiolike shared transmission systems to create a computer network across dispersed campuses.

Initially it used two frequencies, with a hub machine broadcasting packets on an outbound channel and client machines sending data to the hub on the inbound channel. All nodes would communicate on the same frequency with communications sent via a teletype so the data rate usually didn’t exceed 80 characters per second. However two stations couldn’t talk at the same time or the messages would be garbled. Any machine noticing corrupt data would wait a short time and then re-send the packet. This required a system to control who could talk at any time, resulting in the development of contention management systems that later assisted Bob Metcalf and others at Xerox PARC in Palo Alto, California, in producing the Ethernet protocol.

Alohanet had connected to the experimental ARPANET from 1972.[12] “We had the opportunity to connect to Alohanet but the nearest dish was Wellington Polytechnic. We wanted to put one up at the university, it was a research project that required only a small amount of money but no one thought it was worth doing so it didn’t get done,” recalled Mike Newbery, who was working at the computing services centre at Victoria University.

At this stage the only activity that might have been considered networking consisted of a few Burroughs TD800 terminals linked back to the mainframe data communications processors, even though some of them were on fairly long lines. The first real attempt at linking university computers took place in 1975 when Victoria University and Massey University began experimenting with their Burroughs machines, using a pair of synchronous modems operating at 4800bit/sec. The plan to share resources on-line was optimistically dubbed KiwiNet but the link was down more than it was up.

Meanwhile Victoria University’s Burroughs 6700 was connected to a Hewlett-Packard HP2100 mini computer at the Applied Mathematics Division of the DSIR, which was on the university campus, and out to a B6700 at the Reserve Bank. This still didn’t qualify in any real sense as networking. While staff at the DSIR made use of Victoria’s B6700, they were not able to connect to Massey. Neil James was in the computer centre at Massey University at the time. “We proved the connectivity and that’s about as far as it went. In concept we were looking at possibilities of load sharing, to even out demand on the Burroughs machines at both universities, which in hindsight I don’t think we had much show of achieving,” said James.

The first example of anything that even approached successful networking, was when he took one of the Burroughs terminals and an acoustic modem,[13] which the department had acquired from the United Kingdom, to his home. “You would clamp the phone hand piece into the box and dial up so the tones of the phone connected to the computer at the other end. It worked at 30 baud (bits per second) but there was never any practical use.”

This was early experimentation, largely to gain experience in networking. By the end of the 1970s when he left to head the Computer Science Department at Otago University, there was still precious little in the way of networking happening at Massey, said James.

### DSIR breaks ranks

The DSIR, which had locations around the country including Massey University and Victoria University campuses, had an important role to play in the ultimate development of the university networks. The Applied Maths Division (AMD) of the DSIR had an Elliot 503 computer, which had been perhaps the second computer in the country,[14] and the scientists wanted to understand their options for the future.

Frank March was at Canterbury University when he noticed the DSIR was advertising for someone with a research background. “It didn’t particularly matter what field of science but they wanted someone who could advise scientists on the use of computing.” March had a PhD in chemistry from Canterbury University and had done postdoctoral studies in Canada and the United Kingdom. While overseas in 1974 he’d had access to remote computing resources at Sussex University as part of his work as a chemical crystallographer, one of the disciplines that was a great consumer of computer power. That network would a decade later become the Joint Academic Network (Janet).

The DSIR had been assigned the ICL mainframe which was going in at Trentham; however there were delays getting it installed, so from 1975, as a stop-gap measure it was given access to the Cumberland centre. Cumberland was using an older IBM batch command language networking system to connect devices and terminals, while the Vogel Computing Centre had migrated up to systems network architecture (SNA) networking, creating major incompatibilities.

March, who joined the Cumberland Computing Centre looking after DSIR interests, wasn’t happy that they’d had been sidelined to use computers not designed for scientific use, but the plan was that the DSIR would go to tender in 1975 for a sophisticated network of its own. IBM was the only vendor to respond and pitched its $6 million system around the new SNA. However the Muldoon government intervened, decreeing that all government work would be done on three centralised bureau computers in Wellington.

The foundations for the DSIR network were established from about April 1976 when the organisation’s Physics and Engineering Laboratory (PEL) created the Computer Research Section (CRS) at Gracefield campus in Lower Hutt. PEL also built its first wide area network (WAN) based around the DEC PDP-11 mini computers and communications controllers. The basic software and protocols were developed by John Paine at Australia’s Commonwealth Scientific and Research Organisation (CSIRO). Paine had developed a system called NodeCode, which ran on any of the PDP machines, and offered it for free, as long as there was a reciprocal arrangement when the DSIR had interfaces with the IBM computers.

Some of the DSIR’s AMD staff moved out to PEL at Lower Hutt to set up the CRS and develop the interface between NodeCode and whatever computer the DSIR was going to use. When March joined them in September 1976 they had nearly completed the connection with the Cumberland Computer Centre. He recognised later that Paine, working entirely on his own, had come up with a networking code remarkably like transmission control protocol (TCP), which was under construction at Berkeley University. “He’d obviously been reading the Berkeley papers, knew what was going on and incorporated it to the best of his abilities.”

The DSIR network itself had no computing power. It functioned as a message-switching network, connecting teletype machines or ‘dumb’ terminals to a selection of host computers. “I recall the day we exchanged the first complete message. There was a collective celebration and everyone went to the pub. It was a wonderful occasion,” said March.

When the ICL 2980 at Trentham finally became operational in 1978 it was quickly discovered to be a clunker, and a decision was made to use it mainly for Customs. The DSIR stayed with the Cumberland centre where it now linked to the IBM system 370/168 because it was able to emulate the IBM binary synchronous code (BSC) protocol, the predecessor to SNA. CRS staff wrote gateway software to link the mainframe hosts and the DSIR’s communications nodes.

DSIR Gracefield staff also had access to the Ministry of Works and Development IBM system 370 via a single IBM 3270 terminal from late 1980. The Ministry of Works was one of the few organisations with an IBM SNA network. It was used for design and engineering, including building bridges and roads, and had connections to line printers and card readers across the country. The big mainframes could handle interactive time-share computing, using stand-alone IBM 3270 terminals. They transmitted in batches of up to 1024 characters at a time in each direction – about 2000 characters would fill the screen, March said. The trouble was the Vogel and Cumberland centres couldn’t talk to each other.

March ended up writing SNA gateway emulation between the DSIR and Cumberland’s IBM well before other third-party systems were commercially available. “One of the key programmers had left about three or four weeks after I arrived and they said, ‘Well look, you’d better do this job.’ I suddenly found myself programming PDP-11 assembler on a protocol I had never even heard of before. It was a wonderful experience. It really got me hooked. I lived and breathed it and was totally absorbed for about 12 months.” Now the DSIR team could emulate their way into the Cumberland network, which mainly looked after government payroll and administration. They could make use of the scarce resources allocated to them for scientific use and began writing sophisticated programs using a Fortran Compiler.

March recalls Victoria University computer staff, who had been working on the KiwiNet link between Auckland and Wellington, coming to Gracefield PEL to advise on the use of X.25 for communications. “We asked them how they were getting on and they admitted they were still playing around with it and couldn’t really get it working. I think they were a little shocked when we told them we had a working network that was about to go into production.”

The DSIR network went live in April 1977 with a BSC gateway converting the protocols from a teletype machine which was keying characters to the IBM in one direction and reversing the process at the other end. “It simulated an IBM network to an IBM computer. From there we collectively developed it to become more sophisticated, and by 1978 we had an SNA network connecting with Cumberland long before such products were commercially available,”[15] said March.

Eventually the DSIR managed to convince the authorities that the centralised IBM computers in Wellington were not well suited for scientific computing. “They were not fast or responsive enough; we needed interactive computing. We had many meetings to try and convince them. It was a hell of a fight but we managed to get new machines funded.” So over a three-year period the DSIR in Wellington acquired three DEC VAX 11/780 machines and two VAX 11/750s. These mid-range machines were capable of ‘interactive computing’ with up to 40 people simultaneously. “The little DEC terminals were quite sophisticated machines for their day; probably the best of what was available,” said March. The move to the DEC environment meant the relationship between the DSIR’s Applied Mathematics Division and the Computer Sciences Department and Computing Centre at Victoria University became even more productive.[16]

### KiwiNet resurrected

By October 1976 some of the technology and many of the lessons learned from KiwiNet provided a foundation for what was to become VicNet, a general purpose network that linked the machines on the Victoria campus to Massey University’s B6700. It was achieved using the Post Offices X.25 packet switching network. The project received extensive coverage at the Sixth New Zealand Computer Conference, and while it achieved modest success on the Victoria campus, Massey University missed out on funding for the leased line and never successfully linked.[17]

Meanwhile the Computer Science Department at Waikato, now formalised with its own director but still smarting after being forced to share sparse resources with Auckland, didn’t like its chances of getting funding for a separate machine after the prolonged protest of ‘the Burroughs incident.’ It conspired with a group of lawyers to get approval for its preferred machine, a brand-new DEC PD-1170 at a cost of $548,000. The deal was done at 11 a.m. and at 11.01 a.m. the machine was sold for exactly the same amount to a merchant bank. At 11.02 a.m. it was signed back to the university on a rent-to-buy contract. The Ministry of Education, believing it had been cheated, was furious. The university had purchased the machine, avoided sales tax, sold it to pay the vendor, and established a low rental rate for full access to a state-of-the art machine, all within a matter of minutes.

“The PDP 1170 was a marvel. It had a superior time-sharing mechanism, making it ideal for a large user-based environment like the university. Of course there were those that felt the machine was lacking in many areas, compared to other time-sharing systems, but these were usually number-crunchers,” states the Waikato University computer history web site. The upshot was that computer science at Waikato University was now a popular subject, offering 14 computer science papers.[18]

John Hine, originally from upstate New York, had met his New Zealand wife Paula while she was on her ‘big OE[19].’ He’d been studying computer science, specialising in operating systems and some early networking, at the University of Newcastle on Tyne in England. After gaining his PhD in computer science he was lecturing at the University of Connecticut when in 1977 he and his new wife decided to head to New Zealand to visit her family. He took a job at Victoria University, lecturing in what was then known as the Information Science Department. He was the only person there with a PhD in computer science. New Zealand universities were at various stages of developing computer-related disciplines and WAN was still something of a dream.

In Newcastle Hine had been working on an IBM 360/67,[20] which was designed for time-sharing, so arriving at Victoria was like taking a step back in time. The universities were still struggling with the Burroughs B6700 machines. Very little networking had resulted but it had benefited computer science departments, giving them an entry into the revolution now gaining momentum around the world. “From a networking perspective there was some initial toying around, because that’s the only way to describe it, between Massey and Victoria University campuses, the Computer Services Centre at Victoria which had a DEC PDP-5[21] machine, and the Applied Mathematics Division of the DSIR.”

He had to suffer a year with the old Burroughs B6700 punch card-operated mainframe before the arrival of ‘interactive computing’ on a new Digital Vax. “The only real connectivity was a group of us within the Computer Services Centre at Victoria emailing around the building using the Unix-to Unix copy protocol (UUCP) connectivity tools that came with the Unix operating system, and some connectivity with the DSIR AMD and the campus library.”

Meanwhile the telephone network was undergoing major upgrades with users given increasing autonomy in the shift from the old party-line, operator-based system, to subscriber trunk or toll dialling (STD), which was available in most centres by 1976.

STD was common in the United States, Britain, and Australia by the early 1970s, but its arrival in New Zealand was delayed because the Post Office had to meet the demands of extending free calling areas and obtaining the full coverage needed for automatic telephony, which was a precondition of a nationwide STD system. A ban on tariff increases in 1972–1975 had also cut revenues available for the conversion. By early 1977 more than a third of the network – 357,000 subscribers – had access to STD. The roll-out to the rest of the country was painfully slow and lasted until the end of the decade.[22] A substantial upgrade of the national telecommunications network had taken place on 5 March 1976. Enhanced crossbar equipment was cut over at four central exchanges in Auckland, Hamilton, Wellington, and Christchurch.

From December 1979 a link through the Intelsat IV satellite, in conjunction with new NEC 820 crossbar equipment in Auckland, enabled international subscriber trunk (ISD) dialling from New Zealand. Intelsat circuits leased to the International Maritime Satellite Organisation (Inmarsat), which New Zealand had joined in July 1979, meant instant access for local users to Tymnet and Telenet, two North American data networks that were part of Oasis (Overseas Access Service for Information Services). The service proved popular with New Zealand libraries, as they could access the Dialog database with its then 18 million bibliographic entries.[23]

### A decade of change

During the early 1970s New Zealand began to catch up with the world. You could hear it in the music and see it in the pace of technology and the move away from post-war mindsets. There was rebellion in the air, a strong interest in what was happening in the rest of the world, and a deep desire to connect into those growing databases being compiled by scientists offshore. It was a time of political and social challenge. The country had gone from having one television channel to two colour channels and radio transmission was slipping away from government control. Home video recorders had been introduced.

By 1974 more than a million New Zealanders now had telephones and the New Zealand Broadcasting Corporation (NZBC) was restructured, with Radio New Zealand and two TV channels operating under the Broadcasting Corporation of New Zealand. It was announced the Wanganui Computer Centre would store information on individuals from the Justice, Police, and Transport departments.[24]

In 1976 the Tasman 1 cable between Auckland and Sydney came into service in a joint venture between the NZPO and Australia’s Overseas Telecommunications Commission (OTC). Cable manufactured by Standard Telephones and Cables stretched 1258 nautical miles, with 155 repeaters replacing the COMPAC cable between Australia, New Zealand, and Canada, which had been laid in the 1960s.[25]

In 1977 the New Zealand national anthem was changed from “God Save the Queen” to “God Defend New Zealand”, the 200-mile economic limit was imposed and the Beehive was officially opened. On 5 January the longest and most controversial Maori land occupation began after the government announced plans to sell Bastion Point.[26] After 506 days Muldoon ordered the eviction of the protestors, and the burning of their makeshift homes. There were 222 arrests there. That year New Zealand’s first feature-length film since 1962 was made: Sleeping Dogs, the movie adaptation by Roger Donaldson of C.K. Stead’s novel Smith’s Dream. The political thriller about right-wing dictatorship ruling New Zealand and imposing martial law after industrial disputes got out of hand was another measure of the mood of the nation.

In 1978 the first arcade and console games began appearing here, including Pac-Man, Space Invaders, Star Trek, Pong, and the original role-playing game, Dungeons and Dragons. About 95 percent of New Zealand homes had television by then.

The economy was suffering through rampant inflation in the aftermath of the 1973 energy crises and the loss of New Zealand’s biggest export market after Britain entered the European Economic Community (EEC). The Muldoon government maintained a high level of state intervention, borrowing heavily to support its ‘Think Big’ strategies, which included large-scale industrial projects designed to create more jobs. The government also had to borrow to support the welfare state and cover agricultural subsidies. Under pressure to pay back national debt and control wages, which were spiralling out of control, Muldoon did a deal with the Trade Union movement to reduce taxes if they stopped pressuring for wage increases. In 1982, when his tactic appeared to have little effect, Muldoon imposed a total freeze on wages, prices, interest rates, and dividend payouts, which lasted for two years.

Meanwhile the technology that would transform the nation continued to evolve. The United Nations declared 1983 World Communications Year, with the idea that computers and communications technology were about to come together. The aim was “to stimulate accelerated worldwide development of communications infrastructures and to provide an opportunity for all countries to undertake an in-depth review and analysis of their policies on communications development.”

By 1980 the Post Office was supporting about 800 leased lines and 1800 modems.[27] In 1983 it took the plunge and invested in a 14km fibre cable system between Wellington and Lower Hutt. The 10Mbit/sec pilot, capable of carrying several hundred telephone circuits, was the first use of fibre-optic technology in the country. While clearly exploring new options to ease congestion, the Post Office mail and phone monopoly was still way behind the capacity curve.

There was strong interest in the new Post Office satellite-based X.25 packet switching[28] data service (Pacnet) which had been in trial mode since early 1983. It was the only nationwide public network with a uniform cost structure. Cabinet had approved its introduction in September 1979, and $2 million in equipment was ordered from the French firm SESA. Pacnet was designed specifically for business customers with a number of dispersed terminals or teleprinters linked to a central computer, operating at different transmission speeds, anywhere from 2400bits to 48kbit/sec. Its use was mainly for data, although digital speech was not excluded. The packetised data service became commercially available from August 1984 and considerably expanded the Post Office digital data network (DDN).[29]

AWA (NZ) won the contract to upgrade the DDN, including the installation of a videotext information service. Videotext was similar to the UK-based Prestel system, which allowed text to be displayed on screens with the aid of primitive modems on the telephone line. It began to be commercially available from February 1984 and expanded to include data from Valuation New Zealand, Databank, and serviced special-information networks, including Farmnet and Teledata. Its biggest challenge was the arrival of TVNZ’s Teletext service, which delivered on-screen TV programme data plus basic services and news items useful to the investment and farming community.[30]

Another major use for the phone lines made its debut in 1984 as electronic funds transfer at point-of-sale (Eftpos) appeared on the retail scene, only five years after the country’s first bank ATM was installed. The first system operated from a service station and a supermarket attached to a bank computer.[31] Expanded use of the Post Office network had grown to include the use of facsimile machines for offices and homes. The number of private fax machines grew from 200 in 1984 to 800 by 1986, and soon took off as a major communications tool. In 1986 the Post Office began commercial operation of its Starnet electronic mail service, enabling messages to be left for business subscribers, government departments, and universities in ‘electronic mailboxes’ on computers.[32] Users would log in to the remote database to download or send messages, which were delivered via the Pacnet network.

Amidst pockets of innovation, politics kept the Post Office lumbering along to its own tune, and it was often hijacked for partisan purposes. Decisions about which exchanges would be upgraded from manual to automatic often tended to be influenced by other factors than business necessity. Post Office staff were frequently forced to comply with the whim of particular politicians and resented the diversion when there were clearly more pressing problems to be attended to. According to Vivienne Smith in her book on the history of the Post Office, Reining in the Dinosaur, one classic case was the automation of the Te Kuiti telephone exchange shortly before the 1984 general election.

Digital switching and transmission took a giant leap forward on 16 November 1984 when the first Wellington-Auckland link using digital microwave and co-axial cable technology went live after two years of planning. The $24 million system had delivered a 640km digital link that could transmit voice and data at 140Mbit/sec per circuit. At the same time new computerised stored program controlled (SPC) exchanges were cut into the network. A thousand new circuits were added to the digital link within two years, as the system was expanded to the main South Island centres. A major SPC upgrade was installed in the Auckland area from 1984 after a massive 20 percent upsurge in toll traffic in and out of the city – caused by an election year boom and rising business confidence. Regardless, subscribers continued to face delays and overloading.[33]

### Dragging the chain

By 1984 the State occupied a huge place and a stifling role in the New Zealand economy. Government spending accounted for over 40 percent of New Zealand’s GDP, and it employed 31 percent of the nation’s workforce.[34] New Zealand’s economy was one of the worst performers in the OECD. GDP per capita had declined from fifth in the world in the 1950s to 20th in the 1980s.[35]

The newly elected Labour Government, due to take office after the July 1984 elections, was in for a shock. The projected $5 billion deficit was the biggest in the country’s history and far larger than the Muldoon government had acknowledged. The country also faced a constitutional crisis played out in the media, as Muldoon refused to agree to the measures the incoming government wanted to put in place to manage the crisis, including an immediate 20 percent devaluation of the New Zealand dollar. “We changed New Zealand in our first 13 days and we weren’t even Ministers of the Crown. Before we were even sworn in we had taken away the huge range of restrictions and strange prohibitions and all those Polish shipyard rules that we laboured under and we had become inexorably committed to a totally new economy,” recalled Prime Minister David Lange, in Vivienne Smith’s book, of those tumultuous first days of the Labour Government.

Roger Douglas, the minister of finance, spent the first three months in office concentrating on the big items, getting rid of subsidies and tax breaks, and looking at the reform of State-Owned Enterprises (SOEs) to make them more efficient and accountable. This also meant a review of their role in the production of goods and services, and their contribution to the country’s economic well-being. “We started seeing the government organisation as being an institution with a huge impact on the efficiency and transformation of resources into useful products and stopped assuming, as the classic bureaucratic model does, that a bureaucracy is a black box that does what its told – the politicians give it instructions, and it immediately carries them out. We started thinking…it’s nothing like that at all. The bureaucracy itself is a huge potential distortion in the transformation of political will into the delivery of public services and government interventions,” said Douglas.

Vivienne Smith, in Reining in the Dinosaur, said Treasury was concerned at the inability of the SOEs to draw the line between social and commercial demands. They didn’t have to pay the going rate for government finance. Many of them didn’t pay tax and what they did with their funding did not reflect its true cost encouraging them to use more of it. That had led to excessive expansion of activity or artificially low prices for goods and services. Many SOEs were engaged in conflicting roles, acting as policy adviser and regulator in the areas of business where they derived their greatest revenue. Such protections and regulations had worked against effective competition and needed to be eliminated.[36]

The Post Office was the country’s biggest employer, with about 40,000 staff. It had 1262 post offices and agencies across the country, total assets of $4.5 billion, and only ten accountants. According to chairman Michael Morris, who co-authored the 1986 ‘Mason-Morris Report,’ it was an old-fashioned organisation that had developed from the 19th century postal operation into a head office and district structure through the ad hoc addition of functions dictated by communications technology and economic factors. The working environment was “characterised by inertia and frustration.”[37]

The union’s motto was: ‘Post Office work for Post Office people’ and that resulted in many jobs that could have been contracted out, being done in house. “You name it they did it: electrical work, plumbing work they had painters, carpenters, motor mechanics, all sorts of minor repair work to telephones was being done in their workshops,” Morris said. Personnel policies bore a strong resemblance to the game of snakes and ladders. Inflexible practices meant anyone rejoining the Post Office after a period of employment elsewhere could not come back on the grade they left at. Instead they had to go to the bottom of the grading scale and start again, despite critical shortages of people with particular skills.[38]

By 1985 New Zealand was divided into 22 districts for postal services, each under control of a chief postmaster and 17 telecommunications districts, each under the control of a district or regional engineer. This in itself caused major administration and co-ordination problems. On the telecommunications side there had been rapid growth in the demand for high-quality telephone services as well as an explosion in the use of computers for communication purposes in the public and private sectors. The organisation was dominated by the telecommunications engineers, who were interested only in the technical aspects of the operation, not the business side. But they had their own problems trying to get access to the latest equipment.

Former post office senior engineer Laurence Zwimpfer recalled the days when Post Office requests for new technology were controlled by Treasury, which ultimately stifled progress because of its accounting procedures. “We’d do our best to try and put a new telephone exchange in and try and meet future demand but by the time we had ordered and installed the thing, it was out of capacity. That was because we were using historic three-year projections, which was the way Treasury allocated funds. You had to prove your case and they weren’t prepared to take any risks beyond your last three years of projection. So we as engineers always felt as though we had our hands tied behind our backs. We could never even keep pace with basic demand because we didn’t have the funding support,” said Zwimpfer.

Vivienne Smith also wrote about the appalling state of the accounting and financial management systems, and the lack of control the Post Office had over capital expenditure and the growth in inventory. Morris during his review asked for an update on the inventory it was carrying. It took a week to come through and when it did, it had nearly doubled in a six-month period (and “nobody knew!” according to Morris). From March to October 1985 it went from $285 million to $403 million. Most of the millions were tied up in telecommunications equipment – telephones, PABXs, and cable – waiting to be installed. Worse still, because of the long wait, when the time came to install some of this equipment, the technology had passed it by. “They took it to the tip and dumped it. I thought the whole thing was a real indictment, partly of management and partly of the government, its owner,” said Morris.The Mason-Morris review began in September 1985[39] The ‘Mason-Morris Review’ recommended splitting the Post Office into three separately managed businesses. The government agreed to implement this within a year.

Sidebars
--------

Footnotes
---------

<references />

[1] Looking Back to Tomorrow, New Zealand Computer Society, 1985, pp39

[2] A.C. Wilson, p165

[3] Ibid p152

[4] Ibid, p144

[5] Ibid p41

[6] Where most program data is kept on the stack and queued for greater efficiency rather than having to be called from the software register each time

[7] <http://en.wikipedia.org/wiki/Burroughs_large_systems>

[8] <http://en.wikipedia.org/wiki/Burroughs_large_systems>

[9] Ibid

[10] After 15 years development, engineer Harrington became director of the Canterbury Computer Services Department in the mid-1980s

[11] The DEC PDP (programmed data processor) was a series of highly successful computers made by DEC

[12] <http://en.wikipedia.org/wiki/ALOHAnet>

[13] Also known as acoustically coupled modems that were mechanically connected to the phone, fitting over the handset to send and receive signals coming down the phone line and convert them into the zeroes and ones of data streams that could be understood by computers. A primitive device that preceded electrically connected modems

[14] The Elliot was a British machine. The company was taken over by General Electric and later became ITL

[15] By 1977 the DSIR had developed a gateway with IBM 3270 emulation, which was extended to handle SNA in 1980, long before such products were available from vendors. J.H. Hine, ‘Research Networks in New Zealand,’ Department of Computer Science, Victoria University of Wellington. Technical Report CSD-87-021, 1987

[16] Frank March moved from the DSIR to spend a decade as director of Computing Services at Victoria University from 1985

[17] J.H. Hine, chapter 6

[18] <http://www.cs.waikato.ac.nz/department/history.html>

[19] Overseas experience: the semi-obligatory working holiday young people take before settling in to the workforce

[20] The IBM System/360 mainframe computer system family announced by IBM on 17 April 1964 were the first to make a clear distinction between architecture and implementation, allowing compatibility across its range of models. Customers could purchase a smaller system with an upgrade path. The 360-67, first shipped in August 1966, came with the CP/CMS operating system, the original virtual machine system developed at IBM’s Cambridge Scientific Center, in co-operation with MIT researchers. Ref: <http://en.wikipedia.org/wiki/IBM_360>

[21] The predecessor to DEC’s highly successful PDP-8 aimed it at a market that couldn’t afford larger mainframe computers

[22] Wilson, p152

[23] Ibid, p162–163

[24] A young punk anarchist was killed on 18 November 1982, apparently blown up by his own gelignite bomb while trying to breach security at the computer centre. The bomber, 22-year-old Neil Roberts, had the words “This Punk won’t see 23. No Future” tattooed across his chest

[25] <http://www.atlantic-cable.com/CableCos/NewZealand/index.htm>

[26] Development was prevented but ten years later Bastion Point land was returned to Ngati Whatua

[27] Colin Beardon, Computer Culture, Reed Methuen, 1985

[28] The first international standard packet switching network was developed in the early 1970s and published in 1976 by the CCITT (now ITU). X.25 was designed to become a worldwide public data network similar to the global telephone system for voice, but it never came to pass due to incompatibilities and the lack of interest within the US. It has been used primarily outside the United States for low-speed applications (up to 56kbit/sec) such as credit card verifications, automatic teller machine (ATM) and other financial transactions. X.25 provides a connection-oriented technology for transmission over highly error-prone facilities, which were more common when it was first introduced. Error checking is performed at each node, which can slow overall throughput and renders X.25 incapable of handling real-time voice and video. Source: <http://www.pcmag.com/encyclopedia>

[29] Wilson, p173

[30] Wilson, p174

[31] <http://www.paymark.co.nz>

[32] Wilson, p175

[33] Wilson, p174

[34] Ian Duncan and Alan Bollard, Corporatisation and Privatisation: Lessons from New Zealand, Oxford University Press, Auckland, 1992, p7

[35] ‘Economic management,’ The Treasury, Wellington, 14 July 1984, p275, p279.

[36] Smith, pp43–45

[37] The Mason-Morris review began in September 1985

[38] Smith, p44

[39] Ibid, pp45–46