# Awesome TLA [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Total Learning Architecture (TLA) resources, implementations, tools, standards, and
community projects

The Total Learning Architecture (TLA) originated from the U.S. Department of Defense Advanced
Distributed Learning (ADL) Initiative and has transitioned to IEEE LTSC for formal standardization. TLA
encompasses multiple interconnected standards enabling organizations to build interoperable, adaptive
learning systems.

## Contents

- [Standards &amp; Specifications](#standards--specifications)
- [Core Technologies](#core-technologies)
- [Reference Implementations](#reference-implementations)
- [Tools &amp; Libraries](#tools--libraries)
- [Developer Resources](#developer-resources)
- [Community](#community)
- [Related Standards Bodies](#related-standards-bodies)

## Standards &amp; Specifications

### IEEE LTSC Standards
- [IEEE 9274.1.1-2023](https://standards.ieee.org/ieee/9274.1.1/10437/) - xAPI (Experience API) using
JSON and RESTful data transport
- [IEEE 1484.20.3-2022](https://standards.ieee.org/ieee/1484.20.3/10355/) - Data Model for Shareable
Competency Definitions
- [IEEE 1484.2.1 (PESC LER alignment)](https://standards.ieee.org/ieee/1484.2/11142/) - Learning and Employment
Record (LER) Ecosystems
- [IEEE 2881-2025](https://standards.ieee.org/ieee/2881/11719/) - Learning Metadata Terms
- [IEEE 1484.12.1-2020](https://standards.ieee.org/ieee/1484.12.1/10324/) - Learning Object Metadata
- [IEEE 1484.11.1-2022](https://standards.ieee.org/ieee/1484.11.1/10350/) - Data Model for Content
Object Communication
- [IEEE 1484.11.2-2020](https://standards.ieee.org/ieee/1484.11.2/7698/) - ECMAScript API for Content
to Runtime Services Communication

### ISO/IEC Standards
- [ISO/IEC DIS 9274-1-1 – Experience API (xAPI), joint IEEE/ISO work (in development)](https://www.iso.org/standard/91131.html) - xAPI (joint IEEE/ISO standard, in
development)

### Working Group Standards (In Development)
- P9274.2.1 - [xAPI Profiles Working Group](https://sagroups.ieee.org/9274-2-1/) JSON-LD for Application Profiles of Learner Experience Data

- P9274.3.1 - Packaging, Launch, and Run-time of xAPI (cmi5)
- P9274.4.2 - Cybersecurity in xAPI Implementation
- P2247.2 - Adaptive Instructional Systems Interoperability
- P2247.4 - Ethically Aligned AI in Adaptive Instructional Systems
- P2834 - Secure and Trusted Learning Systems
- P2997 - Enterprise Learner Record

## Core Technologies

### xAPI (Experience API)
- [xAPI Specification](https://github.com/adlnet/xAPI-Spec) - Official specification repository
- [xAPI Profiles](https://github.com/adlnet/xapi-profiles) - Application profiles for xAPI

### Competency Frameworks
- [Competency and Skills System (CaSS)](https://github.com/cassproject) - Open-source competency
management

### Learning Record Stores (LRS)
- [Yet Analytics SQL-based Learning Record Store](https://github.com/yetanalytics/lrsql) - Open-source LRS
- [Learning Locker](https://github.com/LearningLocker/learninglocker) - Open-source LRS
- [ADL LRS](https://github.com/adlnet/ADL_LRS) - Reference LRS implementation
- [ADL LRS Conformance test Suite](https://github.com/adlnet/lrs-conformance-test-suite) - A NodeJS project that tests the MUST requirements of the xAPI Spec and is based on the ADL testing requirements repository.
- [node.js LRS](https://github.com/webtech-uos/nodejs-lrs) - node.js implementation of a learning record store (LRS) as described in the XAPI specifications
- [Local LRS Server](https://github.com/gowithfloat/Float.TinCan.LocalLRSServer) - A local LRS server for xAPI client applications
- [LRS supporting the xAPI and Caliper](https://github.com/Transcordia/jupiter) - An open source Learning Record Store (LRS) supporting the xAPI and Caliper specifications

## Reference Implementations


### xAPI Tools

- [xAPI Wrapper](https://github.com/adlnet/xAPIWrapper) - JavaScript library for xAPI communication
- [cmi5 Advanced Testing Application and Player Underpinning Learning Technologies (CATAPULT)](https://github.com/adlnet/CATAPULT)
- [xAPI cmi5 profile using JavaScript.](https://github.com/xapijs/cmi5) - Communicate over the xAPI cmi5 profile using JavaScript
- [cmi5.js Assignabel unit (AU) Runtime](https://github.com/RusticiSoftware/cmi5.js) - JavaScript implementation of cmi5 AU runtime
- [TinCanJS](https://github.com/RusticiSoftware/TinCanJS) - JavaScript library for the Experience API
- [cmi5 Assignable Unit (AU)/Learnign Record provider (LRP) Simulator](https://github.com/cawerkenthin/cmi5-AU-Simulator) - This application simulates the AU-side of the cmi5 specification. It is an example of how to send cmi5 statements from an AU
- [xAPIadaper for Unity](https://github.com/e-ucm/xasu) - xAPI Analytics Submitter for Unity / A very simple xAPI tracker with cmi5 support
- [cmi5 Launch for Moodle](https://github.com/adlnet/Moodle-mod_cmi5launch) -  A Moodle plugin which allows teachers to upload cmi5 packaged lessons within a Moodle Course Activity and then assign the activity to students
- [RapidCMI5 Course Creation Tools](https://github.com/ByLightSDC/rapidcmi5) - RapidCMI5 is a CMI5 course creation toolset.
- [Learning Records Converter (Prometheus-X)](https://github.com/Prometheus-X-association/learning-records-converter) - Learning Records Converter is a tool enabling the interoperability of Learning Records in various formats (xAPI, SCORM, IMS Caliper, cmi5, proprietary).
- [xAPI Video Profile Reference Project](https://github.com/jhaag75/xapi-videojs) - Example of xAPI Video Profile with the HTML5 / VideoJS Library
- [.NET library to speak to xAPI](https://github.com/Gimly/FluentxApi) - A fluent .Net Standard library to create xApi statements and communicate with a LRS
  
### Sharable Competency Definition (SCD)
- [TLA Toolbox](https://tlatoolbox.com) - Community hosted reference environment workspace for Sharable Competency Definitions and Assertions

## Tools &amp; Libraries

### Development Tools
- [Rustici Engine](https://rusticisoftware.com/products/scorm-cloud/) - Commercial content engine and xAPI/cmi5 testing platform
platform
- [xAPI Lab](https://adlnet.gov/projects/experience-api/) - Visual statement builder and testing tool

### Data Analysis
- [xAPI Dashboard](https://github.com/adlnet/xAPI-Dashboard) - Visualization tools for xAPI data

## Developer Resources

### Documentation
- [ADL xAPI Documentation](https://adlnet.gov/projects/xapi/)
- [IEEE LTSC Documentation](https://sagroups.ieee.org/ltsc/)
- [cmi5 Specification](https://github.com/AICC/CMI-5_Spec_Current)

### Other Standards of Interest
- [1EdTech Security Framework](https://www.imsglobal.org/spec/security/v1p0) - xAPI leaves security/Oauth details to "implementation"

### Tutorials &amp; Guides
- [xAPI Tutorials](https://xapi.com/tutorials/) - Getting started with xAPI

## Community

### Discussion Forums
- [xAPI Community](https://groups.google.com/g/xapi-spec)
- [TLA Community Forum](https://discuss.tlaworks.com)

### Working Groups
- [IEEE LTSC Working Groups](https://sagroups.ieee.org/ltsc/workgroups/)
- [ADL Initiative](https://adlnet.gov/)

### Events
- [IEEE LTSC Meetings](https://sagroups.ieee.org/ltsc/)
- [Learning Impact Conference Hosted by 1EdTech Consortium](https://www.learningimpact.com/)

## Related Standards Bodies

### International Organizations
- [IEEE Learning Technology Standards Committee (LTSC)](https://sagroups.ieee.org/ltsc/)
- [ISO/IEC JTC1 SC36](https://www.iso.org/committee/45392.html) - Information technology for
learning, education and training
- [1EdTech Consortium](https://www.1edtech.org/) - Learning technology interoperability standards
- [W3C](https://www.w3.org/) - Web standards (JSON-LD, RDF)

### Industry &amp; Education Organizations
- [Advanced Distributed Learning Initiative (ADL)](https://adlnet.gov/)
- [i2DL (Interoperability in Digital Learning)](https://www.i2idl.org/)
- [HR Open Standards Consortium](https://www.hropenstandards.org/)
- [Credential Engine](https://credentialengine.org/)
- [Postsecondary Electronic Standards Council (PESC)](https://www.pesc.org/)

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

To add a resource:
1. Fork this repository

2. Add your resource to the appropriate section
3. Ensure it follows the [Awesome List
guidelines](https://github.com/sindresorhus/awesome/blob/main/contributing.md)
4. Submit a pull request

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/
zero/1.0/)

To the extent possible under law, the TLA Ecosystem community has waived all copyright and related or
neighboring rights to this work.

---

**Maintained by the TLA Ecosystem community**
'Awesome' concept proposed by Gregory Kulp | Initial curation by Henry Ryng
