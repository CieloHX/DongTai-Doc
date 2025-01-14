洞态专注于 DevSecOps，帮助企业发现并解决应用安全风险。洞态 IAST 是全球首家开源的 IAST，支持 SaaS 访问及本地部署，助力企业在上线前解决应用的安全风险。

### 什么是IAST

交互式应用程序安全测试（Interactive Application Security Testing）是2012年Gartner公司提出的一种新的应用程序安全测试方案，通过代理、VPN或者在服务端部署Agent程序，收集、监控Web应用程序运行时函数执行、数据传输，并与扫描器端进行实时交互，高效、准确的识别安全缺陷及漏洞，同时可准确确定漏洞所在的代码文件、行数、函数及参数。 IAST 会检测执行时的每一行代码，以及应用程序响应每个 HTTP(S) 请求时的堆栈跟踪、内存值和实际数据流。

IAST 相当于是 DAST 和 SAST 结合的一种互相关联运行时安全检测技术，它融合了 SAST 和 DAST 技术的优点，无需源码，支持对字节码的检测。IAST 的一个显著特性是，它是在软件生命周期 (SDLC) 中的 QA/Testing 阶段进行的。IAST 通过把安全测试从生产阶段分离，使得团队可以提前捕获动态漏洞，进而降低漏洞修复成本、消除延迟、降低应用程序被破坏的风险。

IAST 分为主动式 IAST 和被动式 IAST。主动式 IAST 通过在被测试应用程序中部署探针，然后使用外部扫描器触发流量由探针进行捕获、检测是否存在漏洞；被动式 IAST 通过在被测试应用程序中部署探针，然后获取程序执行的代码上下文信息及数据流向，根据数据流向及程序执行的代码上下文信息梳理污点链路，判断是否存在漏洞。

### 洞态IAST的优势

1. “洞态IAST”属于被动式IAST，具有近实时检测、高检出率、低误报率、低漏报率等优点；

2. “洞态IAST”不需要重放数据包，可覆盖加密、防重放、验证码等真实业务场景；

3. “洞态IAST”不产生脏数据，不对测试人员工作造成干扰

4. "洞态IAST"使用全新的技术架构，打破探针间的壁垒，解藕数据采集与漏洞检测两大逻辑，探针只负责运行时数据的采集，云端统一进行漏洞的检测，实现了探针间数据格式的统一。

5. "洞态IAST"提供强大的在线靶场，提供海量探针数据，基于数据分析快速提取漏洞规则，实时应用于洞态IAST，更快的检测新出现的漏洞。

6. "洞态IAST"提供便捷的流程接入，提供DevOps流程中的快速接入、提供开发阶段的IDE插件、支持主流风险管理平台的一键式对接；快速接入，降低使用成本。

7. "洞态IAST"提供基于使用场景的开源社区，提供不同行业、业务场景下，如何进行风险检测、如何快速落地并与内部流程/系统打通，用更高的效率和更低的成本解决应用安全问题与供应链安全问题。

### 常用链接

- [快速开始](doc/tutorial/quickstart)

- [检测能力](/doc/tutorial/detects)

- [架构设计](/doc/deploy/intro)

- [常见问题](/doc/qa)

- [技术支持](/doc/aboutus/support)
