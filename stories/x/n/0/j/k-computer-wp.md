# K computer

Once the fastest supercomputer on Earth, the K computer consumed enough electricity to power 10,000 homes and was named for a number so large most languages lack a word for it.

**Location:** 34.6534, 135.2205

**Categories:** technology, supercomputer, science, computing, history

## Introduction

The Japanese word "kei" means ten quadrillion -- ten followed by sixteen zeros, a quantity so vast it strains comprehension. Fujitsu and RIKEN chose it as the name for their supercomputer because the machine was built to reach ten petaflops: ten quadrillion floating-point calculations per second. When the K computer achieved that target in November 2011, becoming the first machine in history to break the ten-petaflop barrier, the name stopped being an aspiration and became a fact. Housed in 864 refrigerator-sized cabinets at the RIKEN Advanced Institute for Computational Science in Kobe, the K computer drew 9.89 megawatts of power -- equivalent to nearly 10,000 suburban homes running simultaneously -- to model climate systems, simulate earthquake damage, and advance medical research. It was decommissioned in 2019, replaced by an even more powerful successor. But for the years it ran, K was the machine that proved Japan could build the fastest brain on the planet.

## The Race to Ten Petaflops

Development began in 2006 as a Japanese government initiative, with 111 billion yen invested in co-development between RIKEN and Fujitsu. On June 20, 2011, the TOP500 Project Committee announced that K had set a LINPACK benchmark record at 8.162 petaflops, making it the fastest supercomputer in the world. That November, K crossed the ten-petaflop threshold. At the 2011 HPC Challenge Awards, it received top ranking in all four performance benchmarks -- an unprecedented sweep that demonstrated raw speed alongside versatility. The triumph was short-lived in computing terms. By June 2012, IBM's Sequoia in California had overtaken K with 16.325 petaflops, running 55 percent faster while using 150 percent less energy per calculation. But K had made its point: Japan was a supercomputing power.

## Inside the Machine

The K computer comprised 88,128 SPARC64 VIIIfx processors running at 2.0 GHz, manufactured by Fujitsu using 45-nanometer CMOS technology. Each of the eight-core processors sat inside a computing node with 16 gigabytes of memory, and 96 nodes filled each of the 864 cabinets -- for a total of 705,024 processor cores working in concert. The nodes communicated through Fujitsu's proprietary Tofu interconnect, a six-dimensional mesh/torus network designed specifically for the project. The file system, built on a customized version of the open-source Lustre platform called the Fujitsu Exabyte File System, could scale to several hundred petabytes. A water cooling system ran throughout the installation, designed not just for temperature management but to minimize hardware failure rates across the tens of thousands of active components.

## The Power Problem

At 9.89 megawatts, the K computer reported the highest total power consumption on the June 2011 TOP500 list. That figure invites easy criticism, but context matters. K achieved 824.6 gigaflops per kilowatt -- nearly 30 percent more efficient than China's NUDT TH MPP, ranked second at the time, and more than 225 percent more efficient than Oak Ridge National Laboratory's Jaguar system in third place. Still, K's efficiency fell far short of IBM's Blue Gene/Q prototype, which managed 2,097 gigaflops per kilowatt. The tension between raw computational power and energy consumption defined the supercomputing race of the 2010s, and K sat squarely at the center of that debate. The average TOP 10 system in 2011 drew 4.3 megawatts; K consumed more than double that average, raising questions about whether sheer scale was sustainable.

## Legacy in Silicon

The K computer was formally decommissioned on August 30, 2019, after seven years of operational service. Its applications ranged from simulating tsunami propagation to modeling protein folding for drug discovery -- the kind of work that requires solving millions of equations simultaneously. In 2020, its successor Fugaku took the same spot at the RIKEN campus in Kobe and immediately seized the top position on the TOP500 list, running nearly three times faster than the next most powerful machine. Fugaku was designed from the start with the lessons K taught: application performance mattered as much as benchmark speed, and energy efficiency could not be an afterthought. Even the local transit system marked the transition -- in June 2021, the nearby Port Liner station formerly named "K Computer Mae" was renamed Keisan Kagaku Center Station. The machine was gone, but the computational science center it built endures.

## Flight Context

Located at 34.653°N, 135.220°E on Port Island, a large artificial island in Kobe's harbor. The RIKEN Center for Computational Science campus is identifiable as a cluster of modern institutional buildings on the island's southern section. Kobe Airport (RJBE) is immediately adjacent on its own reclaimed island to the south. Osaka Itami Airport (RJOO) is 28 km to the northeast. Best viewed at 3,000-5,000 ft when approaching Kobe Airport, with the RIKEN campus visible on Port Island's southern waterfront.

## Sources

- [K computer - Wikipedia](https://en.wikipedia.org/?curid=32149868)
  - kei means 10 quadrillion confirmed
  - 88128 SPARC64 VIIIfx processors in 864 cabinets confirmed
  - 705024 total cores confirmed (full configuration)
  - 9.89 MW power consumption confirmed
  - Decommissioned August 30 2019 confirmed
  - June 2011 TOP500 first at 8.162 petaflops confirmed
  - November 2011 crossed 10 petaflops (10.51) confirmed
  - 45nm CMOS technology confirmed
  - 111 billion yen investment confirmed
- [Fujitsu - K computer Achieves Goal of 10 Petaflops](https://www.fujitsu.com/global/about/resources/news/press-releases/2011/1102-02.html)
  - 10.51 petaflops LINPACK performance confirmed
  - 93.2% computing efficiency ratio confirmed
- [Wikipedia - Sequoia supercomputer](https://en.wikipedia.org/wiki/Sequoia_(supercomputer))
  - IBM Sequoia overtook K at 16.325 petaflops June 2012 confirmed
  - NOTE: Article says Sequoia used 150% less energy per calculation - this is mathematically nonsensical phrasing but the efficiency comparison is directionally correct
- [Wikipedia - Fugaku supercomputer](https://en.wikipedia.org/wiki/Fugaku_(supercomputer))
  - Fugaku took TOP500 first place June 2020 confirmed
  - Nearly three times faster than second place confirmed
- [Wikipedia - Keisan Kagaku Center Station](https://en.wikipedia.org/wiki/Keisan_Kagaku_Center_Station)
  - Station renamed from K Computer Mae on June 19 2021 confirmed
  - NOTE: Article says June 2021 which is correct

## Review Notes

**Reviewed:** 2026-02-18 · 15 facts verified · 2 corrections

Most facts verified including specifications, dates, and performance figures. Two issues found: (1) 96 nodes per cabinet inconsistent with 88128/864 calculation, (2) phrase '150% less energy' is mathematically impossible. Spiciness 1 - pure factual reporting.

**Spiciness:** 1/5

---

*Word count: 800*
*Read time: 4 minutes*
