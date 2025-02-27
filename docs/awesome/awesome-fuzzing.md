<div class="github-widget" data-repo="cpuu/awesome-fuzzing"></div>
## Awesome Fuzzing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> [Fuzzing](https://en.wikipedia.org/wiki/Fuzzing)  或模糊测试是一种自动软件测试技术，涉及提供无效，意外或随机数据作为计算机程序的输入.  然后监视程序是否存在异常，例如崩溃，内置代码断言失败或潜在的内存泄漏.  通常，模糊器用于测试采用结构化输入的程序. 

 一系列精选的Fuzzing安全测试参考列表.  此外，还有一系列免费提供的学术论文，工具等.

 您最喜欢的工具或自己的纸张未列出？  fork并创建一个Pull Request来添加它！





## Books
- [Fuzzing for Software Security Testing and Quality Assurance, 2nd Edition](https://www.amazon.com/Fuzzing-Software-Security-Testing-Assurance/dp/1608078507/) (2018)
- [Fuzzing: Brute Force Vulnerability Discovery, 1st Edition](https://www.amazon.com/Fuzzing-Brute-Force-Vulnerability-Discovery/dp/0321446119/) (2007)
- [Open Source Fuzzing Tools, 1st Edition](https://www.amazon.com/Open-Source-Fuzzing-Tools-Rathaus/dp/1597491950/) (2007)


## Papers
为了达到明确的范围，我选择在最后的4个程序中包括关于模糊测试的出版物
从2008年1月到2019年2月，顶级主要安全会议和其他会议.按字母顺序，
它包括（i）ACM计算机和通信安全会议（CCS），（ii）IEEE Symposium on
安全和隐私（S＆P），（iii）网络和分布式系统安全研讨会（NDSS），以及（iv）USENIX安全研讨会（USEC）.

### ACM Conference on Computer and Communications Security (ACM CCS)
- [Evaluating Fuzz Testing, 2018](http://www.cs.umd.edu/~mwh/papers/fuzzeval.pdf)
- [Hawkeye: Towards a Desired Directed Grey-box Fuzzer, 2018](https://chenbihuan.github.io/paper/ccs18-chen-hawkeye.pdf)
- [IMF: Inferred Model-based Fuzzer, 2017](http://daramg.gift/paper/han-ccs2017.pdf)
- [SemFuzz: Semantics-based Automatic Generation of Proof-of-Concept Exploits, 2017](https://www.informatics.indiana.edu/xw7/papers/p2139-you.pdf)
- [AFL-based Fuzzing for Java with Kelinci, 2017](https://dl.acm.org/citation.cfm?id=3138820)
- [Designing New Operating Primitives to Improve Fuzzing Performance, 2017](http://iisp.gatech.edu/sites/default/files/images/designing_new_operating_primitives_to_improve_fuzzing_performance_vt.pdf)
- [Directed Greybox Fuzzing, 2017](https://dl.acm.org/citation.cfm?id=3134020)
- [SlowFuzz: Automated Domain-Independent Detection of Algorithmic Complexity Vulnerabilities, 2017](https://arxiv.org/pdf/1708.08437.pdf)
- [DIFUZE: Interface Aware Fuzzing for Kernel Drivers, 2017](https://acmccs.github.io/papers/p2123-corinaA.pdf)
- [Systematic Fuzzing and Testing of TLS Libraries, 2016](https://www.nds.rub.de/media/nds/veroeffentlichungen/2016/10/19/tls-attacker-ccs16.pdf)
- [Coverage-based Greybox Fuzzing as Markov Chain, 2016](https://ieeexplore.ieee.org/abstract/document/8233151)
- [eFuzz: A Fuzzer for DLMS/COSEM Electricity Meters, 2016](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.817.5616&rep=rep1&type=pdf)
- [Scheduling Black-box Mutational Fuzzing, 2013](https://softsec.kaist.ac.kr/~sangkilc/papers/woo-ccs13.pdf)
- [Taming compiler fuzzers, 2013](https://www.cs.utah.edu/~regehr/papers/pldi13.pdf)
- [SAGE: whitebox fuzzing for security testing, 2012](https://dl.acm.org/citation.cfm?id=2094081)
- [Grammar-based whitebox fuzzing, 2008](https://dl.acm.org/citation.cfm?id=1375607)
- [Taint-based directed whitebox fuzzing, 2009](https://dl.acm.org/citation.cfm?id=1555061)

### IEEE Symposium on Security and Privacy (IEEE S&P)
- [Full-speed Fuzzing: Reducing Fuzzing Overhead through Coverage-guided Tracing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000b122/19skgbGVFEQ)
- [Fuzzing File Systems via Two-Dimensional Input Space Exploration, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a594/19skfLYOpaw)
- [NEUZZ: Efficient Fuzzing with Neural Program Smoothing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a900/19skg5XghG0)
- [Razzer: Finding Kernel Race Bugs through Fuzzing, 2019](https://www.computer.org/csdl/proceedings-article/sp/2019/666000a296/19skfwZLirm)
- [Angora: Efficient Fuzzing by Principled Search, 2018](http://web.cs.ucdavis.edu/~hchen/paper/chen2018angora.pdf)
- [CollAFL: Path Sensitive Fuzzing, 2018](http://chao.100871.net/papers/oakland18.pdf)
- [T-Fuzz: fuzzing by program transformation, 2018](https://nebelwelt.net/publications/files/18Oakland.pdf)
- [Skyfire: Data-Driven Seed Generation for Fuzzing, 2017](https://www.ieee-security.org/TC/SP2017/papers/42.pdf)
- [Program-Adaptive Mutational Fuzzing, 2015](https://softsec.kaist.ac.kr/~sangkilc/papers/cha-oakland15.pdf)
- [TaintScope: A checksum-aware directed fuzzing tool for automatic software vulnerability detection, 2010](https://ieeexplore.ieee.org/abstract/document/5504701)

### The Network and Distributed System Security Symposium (NDSS)
- [CodeAlchemist: Semantics-Aware Code Generation to Find Vulnerabilities in JavaScript Engines, 2019](https://daramg.gift/paper/han-ndss2019.pdf)
- [PeriScope: An Effective Probing and Fuzzing Framework for the Hardware-OS Boundary, 2019](https://people.cs.kuleuven.be/~stijn.volckaert/papers/2019_NDSS_PeriScope.pdf)
- [REDQUEEN: Fuzzing with Input-to-State Correspondence, 2019](https://www.syssec.ruhr-uni-bochum.de/media/emma/veroeffentlichungen/2018/12/17/NDSS19-Redqueen.pdf)
- [Send Hardest Problems My Way: Probabilistic Path Prioritization for Hybrid Fuzzing, 2019](https://www.cs.ucr.edu/~heng/pubs/digfuzz_ndss19.pdf)
- [Life after Speech Recognition: Fuzzing Semantic Misinterpretation for Voice Assistant Applications, 2019](https://www.ndss-symposium.org/wp-content/uploads/2019/02/ndss2019_08-4_Zhang_paper.pdf)
- [INSTRIM: Lightweight Instrumentation for Coverage-guided Fuzzing, 2018](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_14_Hsu_paper.pdf)
- [IoTFuzzer: Discovering Memory Corruptions in IoT Through App-based Fuzzing, 2018](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_01A-1_Chen_paper.pdf)
- [What You Corrupt Is Not What You Crash: Challenges in Fuzzing Embedded Devices, 2018](http://s3.eurecom.fr/docs/ndss18_muench.pdf)
- [Enhancing Memory Error Detection for Large-Scale Applications and Fuzz Testing, 2018](https://lifeasageek.github.io/papers/han:meds.pdf)
- [Vuzzer: Application-aware evolutionary fuzzing, 2017](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/vuzzer-application-aware-evolutionary-fuzzing/)
- [DELTA: A Security Assessment Framework for Software-Defined Networks, 2017](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2017/09/ndss201702A-1LeePaper.pdf)
- [Driller: Augmenting Fuzzing Through Selective Symbolic Execution, 2016](https://cancer.shtech.org/wiki/uploads/2016---NDSS---driller-augmenting-fuzzing-through-selective-symbolic-execution.pdf)
- [Automated Whitebox Fuzz Testing, 2008](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2017/09/Automated-Whitebox-Fuzz-Testing-paper-Patrice-Godefroid.pdf)


### USENIX Security
- [Charm: Facilitating Dynamic Analysis of Device Drivers of Mobile Systems, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/talebi)
- [MoonShine: Optimizing OS Fuzzer Seed Selection with Trace Distillation, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/pailoor)
- [QSYM : A Practical Concolic Execution Engine Tailored for Hybrid Fuzzing, 2018](https://www.usenix.org/conference/usenixsecurity18/presentation/yun)
- [OSS-Fuzz - Google's continuous fuzzing service for open source software, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/serebryany)
- [kAFL: Hardware-Assisted Feedback Fuzzing for OS Kernels, 2017](https://www.usenix.org/conference/usenixsecurity17/technical-sessions/presentation/schumilo)
- [Protocol State Fuzzing of TLS Implementations, 2015](https://www.usenix.org/conference/usenixsecurity15/technical-sessions/presentation/de-ruiter)
- [Optimizing Seed Selection for Fuzzing, 2014](https://softsec.kaist.ac.kr/~sangkilc/papers/rebert-usenixsec14.pdf)
- [Dowsing for overflows: a guided fuzzer to find buffer boundary violations, 2013](http://enigma.usenix.org/sites/default/files/sec13_proceedings_interior.pdf#page=57)
- [Fuzzing with Code Fragments, 2012](https://www.usenix.org/system/files/conference/usenixsecurity12/sec12-final73.pdf)


### ArXiv (Fuzzing with Artificial Intelligence & Machine Learning)
- [MoonLight: Effective Fuzzing with Near-Optimal Corpus Distillation, 2019](https://arxiv.org/abs/1905.13055)
- [Coverage-Guided Fuzzing for Deep Neural Networks, 2018](https://arxiv.org/abs/1809.01266)
- [DLFuzz: Differential Fuzzing Testing of Deep Learning Systems, 2018](https://arxiv.org/abs/1808.09413)
- [TensorFuzz: Debugging Neural Networks with Coverage-Guided Fuzzing, 2018](https://arxiv.org/abs/1807.10875)
- [NEUZZ: Efficient Fuzzing with Neural Program Learning, 2018](https://arxiv.org/abs/1807.05620)
- [EnFuzz: From Ensemble Learning to Ensemble Fuzzing, 2018](https://arxiv.org/abs/1807.00182)
- [REST-ler: Automatic Intelligent REST API Fuzzing, 2018](https://arxiv.org/abs/1806.09739)
- [Deep Reinforcement Fuzzing, 2018](https://arxiv.org/abs/1801.04589)
- [Not all bytes are equal: Neural byte sieve for fuzzing, 2017](https://arxiv.org/abs/1711.04596)
- [Faster Fuzzing: Reinitialization with Deep Neural Models, 2017](https://arxiv.org/abs/1711.02807)
- [Learn&Fuzz: Machine Learning for Input Fuzzing, 2017](https://arxiv.org/abs/1701.07232)
- [Complementing Model Learning with Mutation-Based Fuzzing, 2016](https://arxiv.org/abs/1611.02429)
### The others
- [Ifuzzer: An evolutionary interpreter fuzzer using genetic programming, 2016](https://www.cs.vu.nl/~herbertb/download/papers/ifuzzer-esorics16.pdf)
- [Hybrid fuzz testing: Discovering software bugs via fuzzing and symbolic execution, 2012](https://pdfs.semanticscholar.org/488a/b1e313f5109153f2c74e3b5d86d41e9b4b71.pdf)
- [Call-Flow Aware API Fuzz Testing for Security of Windows Systems, 2008](https://www.computer.org/csdl/proceedings/iccsa/2008/3243/00/3243a019-abs.html)
- [Feedback-directed random test generation, 2007](https://dl.acm.org/citation.cfm?id=1248841)



## Tools
有关可用于利用模糊测试的各种开源工具的信息.
### General-purpose
- [radamsa](https://gitlab.com/akihe/radamsa) - 通用型模糊器.
- [zzuf](https://github.com/samhocevar/zzuf) - 透明的应用程序输入模糊器.
### Binary
- [American fuzzy lop](http://lcamtuf.coredump.cx/afl/) - 一种面向安全的模糊器，它采用一种新型的编译时工具和遗传算法来自动发现触发目标二进制文件中新内部状态的干净，有趣的测试用例. 
- [WinAFL](https://github.com/googleprojectzero/winafl) - 用于模糊Windows二进制文件的AFL分支.
- [libFuzzer](http://llvm.org/docs/LibFuzzer.html) - 用于覆盖引导的模糊测试的库. [Tutorial from Google.](https://github.com/google/fuzzer-test-suite/blob/master/tutorial/libFuzzerTutorial.md)
- [Driller](https://github.com/shellphish/driller) - 执行 [driller paper](https://www.cs.ucsb.edu/~vigna/publications/2016_NDSS_Driller.pdf) .  该实现建立在AFL之上，其中angr被用作符号跟踪器.
- [shellphish fuzzer](https://github.com/shellphish/fuzzer) -  AFL的Python接口，可以轻松注入测试用例和其他功能.
- [Eclipser](https://github.com/SoftSec-KAIST/Eclipser) - 基于二进制的模糊测试工具，通过利用称为灰盒模拟测试的新技术改进经典的基于覆盖的模糊测试.
### Web, JavaScript
- [jsfunfuzz](https://github.com/MozillaSecurity/funfuzz) -  JavaScript引擎模糊器.
- [IFuzzer](https://github.com/vspandan/IFuzzer) - 使用遗传编程的进化解释器模糊器.
- [domato](https://github.com/googleprojectzero/domato) - 来自DOM的模糊器 [Google Project Zero](https://github.com/googleprojectzero). [Blog Post.](https://googleprojectzero.blogspot.com/2017/09/the-great-dom-fuzz-off-of-2017.html)
- [fuzzilli](https://github.com/googleprojectzero/fuzzilli) - 由SamuelGroß编写的（覆盖）指导的Javascript引擎模糊器.
- [CodeAlchemist](https://github.com/SoftSec-KAIST/CodeAlchemist) -  JavaScript引擎模糊器，由KAIST SoftSec Lab编写.
### Network protocol
- [TLS-Attacker](https://github.com/RUB-NDS/TLS-Attacker) - 用于分析TLS库的基于Java的框架.
- [DELTA](https://github.com/nss-lab/DELTA) -  SDN安全评估框架.
- [boofuzz](https://github.com/jtpereyda/boofuzz)   - 人类的网络协议模糊测试.  有关文档，请访问http://boofuzz.readthedocs.io/，其中包括漂亮的快速入门指南.
- [LL-Fuzzer](https://github.com/mit-ll/LL-Fuzzer) - 适用于Android设备的自动NFC模糊测试框架.
- [tlsfuzzer](https://github.com/tomato42/tlsfuzzer) -  SSL和TLS协议测试套件和模糊器.
- [TumbleRF](https://github.com/riverloopsec/tumblerf) - 一种框架，用于协调模糊技术在RF系统中的应用. 
- [PULSAR](https://github.com/hgascon/pulsar) - 用于专有网络协议的有状态黑盒模糊测试的方法.
- [SPIKE](https://github.com/guilhermeferreira/spikepp/tree/master/SPIKE) - 一个模糊的开发框架，如sulley，sulley的前身.
- [PROTOS](https://www.ee.oulu.fi/roles/ouspg/Protos) - 协议实现的安全测试.
### Driver
- [Charm](https://github.com/trusslab/charm) - 一种便于动态分析移动系统设备驱动程序的系统解决方案.
## Platform
- [certfuzz](https://github.com/CERTCC/certfuzz) - 它包含CMU CERT基本模糊测试框架（BFF）和CERT故障观察引擎（FOE）的源代码.
- [Peach Fuzzer Platform](https://www.peach.tech/products/peach-fuzzer/) - 自动安全测试平台，通过查找硬件和软件系统中的漏洞来防止零日攻击.
- [Blackhat USA 2018 AFL workshop training materials](https://github.com/wrauner/afl-fuzzing-training) - 来自Samsung Research的@wrauner.

## Contribute

 欢迎捐款！  阅读 [contribution guidelines](https://github.com/cpuu/awesome-fuzzing/blob/master/contributing.md) 第一.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

在法律允许的范围内，cpuu已放弃所有版权和
相关或相邻的权利.
