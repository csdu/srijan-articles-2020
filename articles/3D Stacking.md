# 3D Stacking

---

| Question   | Answer                                                            |
| ---------- | ----------------------------------------------------------------- |
| Writer     | Abhinav Kumar - Msc II year                                      |
| Editor     | Diksha Gupta                                                       |
| Status     | Edited |
| Plagiarism | None. [Report](./plag-reports/plag-3d-stacking.pdf)|

---

Microprocessor companies are investing billions of dollars in R&D to create innovative and revolutionary technologies that could bring Moore's law to its saturation point. As more and more devices are going handheld, companies have to decide whether to provide mobile phones with a slightly bigger headphone jack at the cost of miniaturizing internal components of the battery.

To tackle this problem of blockage, major microprocessor giants are coming up with a new form of circuit fabrication packaging which does not require discrete removable auxiliary components such as RAM. For instance, in 2019, AMD and Intel unveiled chipsets based on this paradigm. AMD called it their chipset design and Intel named it FOVEROS, with the code name 'LakeField'. These kinds of CPUs are more likely to come in HPC(High Performance Computing) and server parts than in the mainstream consumer market.

Last year, Microsoft confirmed that their revolutionary two screen folding android smart-phone - 'Surface Duos' would come equipped with chipsets of the same design. It probably was more of a marketing move to lower the market share that Qualcomm has with their ARM based chips(like 8cx) which are specifically designed for these devices. Intel’s implementation had one flaw. Instead of having a direct interaction between the processors and memory, stacked like floors of a building, the memory addresses and content had to be passed by lift like pillars in the 3D packaging. This was being achieved with one logic box layer storing content from memory in a manner similar to buffer cache in UNIX systems. But, it hardly differed from Intel’s previously announced 2.5D technology which had video memory instead of main memory.

Nevertheless, they managed to motivate others in the industry to come up with their own implementation, the kind of research that would eventually help the consumer. We should be excited for the day that would bring an ecosystem where we can have a set processor from different vendors that we would be able to stack on to one another. This stack would have better combined performance instead of getting bottle-necked by the caches provided by a single processor which is fixed for its lifecycle. This would probably seem to be a bit limiting to a company since they might lose monopoly on their product. But, as past is evident, this was the main selling point for ARM processors because manufacturers had the flexibility in creation. This is why you can never spot anybody holding a phone that has Intel CPU. Tt might have Intel’s modem (iPhones for instance) but not Intel's CPU. Intel has remembered the lesson that this mistake taught indeed. They have played a great gamble on foldable devices to perhaps create the next gen that people could switch to after phones.

In conclusion, System on chip(SOC) design needs to have different subsystems for encryption, modems, and so on. A space efficient technique is required to contain cost that would otherwise blow the roof. 3D stacking could minimize the cost and help Intel gain a much-needed market share in portable devices which would help the consumer get a better product!
