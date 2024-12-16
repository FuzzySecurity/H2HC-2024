## The Kernel Hacker's Guide to the Galaxy: Automated Exploit Engineering

#### Speakers

[Ruben Boonen](https://twitter.com/FuzzySec) & [Valentina Palmiotti](https://twitter.com/chompie1337)

#### Presentation Recording

YouTube: N/A (yet)

#### Abstract

Agenda: [here](https://www.h2hc.com.br/en/pages/agenda.html)

As systems evolve and modern mitigations advance, exploit development becomes more intricate and labor-intensive. Consequently, the cost of exploiting vulnerabilities has risen. Patch gaps can be leveraged to exploit machines that have not yet received necessary updates. The brief window of opportunity before mature clients apply patches puts pressure on the research period for developing N-Day exploits making it demanding and highly time sensitive. To address this, we have implemented many ancillary automation workflows to ease and expedite our exploit development efforts. We will show tradecraft that allows us to programmatically find suitable drop-in exploit objects for specific kernel pools, discover heap spray primitives, identify control flow call targets, perform race condition window analysis, and more, within closed source binaries. These various primitives can be filtered based on the requirements of the vulnerability exploited. Manual root cause analysis allows us to leverage semantic binary search to automatically identify potential vulnerability variants across all Windows kernel subsystems. We illustrate these concepts by showing practical examples using recent vulnerabilities.