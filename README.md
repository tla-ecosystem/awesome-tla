# Awesome TLA [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Standards-based infrastructure for tracking learning activities, managing 
competencies, and maintaining learner records across defense, workforce 
development, and education systems.

The Total Learning Architecture (TLA) originated from the U.S. Department of Defense Advanced
Distributed Learning (ADL) Initiative and has transitioned to IEEE LTSC for formal standardization. TLA
encompasses multiple interconnected standards enabling organizations to build interoperable, adaptive
learning systems.

## Contents

- [Standards and Specifications](#standards--specifications)
- [Core Technologies](#core-technologies)
- [Reference Implementations](#reference-implementations)
- [Tools and Libraries](#tools--libraries)
- [Developer Resources](#developer-resources)
- [Community](#community)
- [Related Standards Bodies](#related-standards-bodies)

## Standards and Specifications

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
- [ISO/IEC DIS 9274-1-1 – Experience API (xAPI), joint IEEE/ISO work (in development)](https://www.iso.org/standard/91131.html) - Joint IEEE/ISO standardization of the Experience API for international adoption and harmonization.

### Working Group Standards (In Development)
- [P9274.2.1 - xAPI Profiles](https://sagroups.ieee.org/9274-2-1/) - JSON-LD specification for defining application profiles that extend xAPI for specific learning contexts.
- P9274.3.1 - Packaging, Launch, and Run-time of xAPI (cmi5) - Standard for launching xAPI content from learning management systems with session management.
- P9274.4.2 - Cybersecurity in xAPI Implementation - Security requirements and best practices for protecting learner data in xAPI systems.
- P2247.2 - Adaptive Instructional Systems Interoperability - Standards for adaptive learning systems that personalize instruction based on learner needs.
- P2247.4 - Ethically Aligned AI in Adaptive Instructional Systems - Ethical guidelines for AI-powered adaptive learning technologies.
- P2834 - Secure and Trusted Learning Systems - Security and privacy frameworks for learning technology infrastructure.
- P2997 - Enterprise Learner Record - Comprehensive learner record standard integrating learning, employment, and credential data.

## Core Technologies

### xAPI (Experience API)
- [xAPI Specification](https://github.com/adlnet/xAPI-Spec) - Official repository for the Experience API (xAPI) specification defining standard for tracking learning experiences.
- [xAPI Profiles](https://github.com/adlnet/xapi-profiles) - Specification and tools for creating application-specific extensions to xAPI for specialized learning contexts.

### Competency Frameworks
- [Competency and Skills System (CaSS)](https://github.com/cassproject) - Open-source platform for managing competency frameworks, assessments, and learning pathways aligned with IEEE 1484.20.3.
management

### Learning Record Stores (LRS)
- [SQL LRS](https://github.com/yetanalytics/lrsql) - Production-grade Learning Record Store with PostgreSQL backend, DoD Platform One certified.
- [Learning Locker](https://github.com/LearningLocker/learninglocker) - Open-source Learning Record Store with analytics dashboard and reporting features.
- [ADL LRS](https://github.com/adlnet/ADL_LRS) - Reference Learning Record Store implementation from the Advanced Distributed Learning Initiative.
- [ADL LRS Conformance test Suite](https://github.com/adlnet/lrs-conformance-test-suite) - A NodeJS project that tests the MUST requirements of the xAPI Spec and is based on the ADL testing requirements repository.
- [node.js LRS](https://github.com/webtech-uos/nodejs-lrs) - node.js implementation of a learning record store (LRS) as described in the XAPI specifications
- [Local LRS Server](https://github.com/gowithfloat/Float.TinCan.LocalLRSServer) - A local LRS server for xAPI client applications
- [LRS supporting the xAPI and Caliper](https://github.com/Transcordia/jupiter) - An open source Learning Record Store (LRS) supporting the xAPI and Caliper specifications

## Reference Implementations


### xAPI Tools

- [xAPI Wrapper](https://github.com/adlnet/xAPIWrapper) - JavaScript library simplifying xAPI statement creation and LRS communication for web applications.
- [cmi5 Advanced Testing Application and Player Underpinning Learning Technologies (CATAPULT)](https://github.com/adlnet/CATAPULT) - Conformance testing suite for cmi5 Assignable Units and Learning Record Stores.
- [xAPI cmi5 profile using JavaScript.](https://github.com/xapijs/cmi5) - Communicate over the xAPI cmi5 profile using JavaScript
- [cmi5.js Assignabel unit (AU) Runtime](https://github.com/RusticiSoftware/cmi5.js) - JavaScript implementation of cmi5 AU runtime
- [TinCanJS](https://github.com/RusticiSoftware/TinCanJS) - JavaScript library for creating and sending xAPI statements from web-based learning content.
- [cmi5 Assignable Unit (AU)/Learnign Record provider (LRP) Simulator](https://github.com/cawerkenthin/cmi5-AU-Simulator) - This application simulates the AU-side of the cmi5 specification. It is an exle of how to send cmi5 statements from an AU
- [xAPIadaper for Unity](https://github.com/e-ucm/xasu) - xAPI Analytics Submitter for Unity / A very simple xAPI tracker with cmi5 support
- [cmi5 Launch for Moodle](https://github.com/adlnet/Moodle-mod_cmi5launch) -  A Moodle plugin which allows teachers to upload cmi5 packaged lessons within a Moodle Course Activity and then assign the activity to students
- [RapidCMI5 Course Creation Tools](https://github.com/ByLightSDC/rapidcmi5) - RapidCMI5 is a CMI5 course creation toolset.
- [Learning Records Converter (Prometheus-X)](https://github.com/Prometheus-X-association/learning-records-converter) - Learning Records Converter is a tool enabling the interoperability of Learning Records in various formats (xAPI, SCORM, IMS Caliper, cmi5, proprietary).
- [xAPI Video Profile Reference Project](https://github.com/jhaag75/xapi-videojs) - Exle of xAPI Video Profile with the HTML5 / VideoJS Library
- [.NET library to speak to xAPI](https://github.com/Gimly/FluentxApi) - A fluent .Net Standard library to create xApi statements and communicate with a LRS
  
### Sharable Competency Definition (SCD)
- [TLA Toolbox](https://tlatoolbox.com) - Community platform for creating, managing, and sharing competency definitions and xAPI profiles.

## Tools and Libraries

### Development Tools
- [Rustici Engine](https://rusticisoftware.com/products/scorm-cloud/) - Commercial SCORM, xAPI, and cmi5 content hosting and testing platform with conformance validation.
platform
- [xAPI Lab](https://adlnet.gov/projects/experience-api/) - Visual tool for building, testing, and debugging xAPI statements with real-time LRS communication.

### Data Analysis
- [xAPI Dashboard](https://github.com/adlnet/xAPI-Dashboard) - Customizable dashboard for visualizing and analyzing learning activity data from xAPI Learning Record Stores.

## Developer Resources

### Documentation
- [ADL xAPI Documentation](https://adlnet.gov/projects/xapi/)  - Official documentation, specifications, and implementation guides for the Experience API.
- [IEEE LTSC Documentation](https://sagroups.ieee.org/ltsc/) - IEEE Learning Technology Standards Committee documentation for all TLA-related standards.
- [cmi5 Specification](https://github.com/AICC/CMI-5_Spec_Current) - Profile for using xAPI with traditional learning management system launch and tracking workflows.

### Other Standards of Interest
- [1EdTech Security Framework](https://www.imsglobal.org/spec/security/v1p0) - OAuth 2.0 security and authentication framework for learning technology applications and APIs.

### Tutorials and Guides
- [xAPI Tutorials](https://xapi.com/tutorials/) - Step-by-step tutorials and guides for implementing xAPI in learning applications and content.
  
## Community

### Discussion Forums
- [xAPI Community](https://groups.google.com/g/xapi-spec) - Google Group for discussing xAPI specification development and implementation questions.
- [TLA Community Forum](https://discuss.tlaworks.com) - Discussion forum for TLA practitioners, implementers, and standards contributors.

### Working Groups
- [IEEE LTSC Working Groups](https://sagroups.ieee.org/ltsc/workgroups/) - Active working groups developing and maintaining IEEE learning technology standards.
- [ADL Initiative](https://adlnet.gov/) - U.S. Department of Defense organization advancing distributed learning technology and standards.

### Events
- [IEEE LTSC Meetings](https://sagroups.ieee.org/ltsc/) - Regular meetings of IEEE LTSC for standards development and community coordination.
- [Learning Impact Conference Hosted by 1EdTech Consortium](https://www.learningimpact.com/) - Annual conference hosted by 1EdTech Consortium on learning technology innovation and interoperability.

## Related Standards Bodies

### International Organizations
- [IEEE Learning Technology Standards Committee (LTSC)](https://sagroups.ieee.org/ltsc/)
- [ISO/IEC JTC1 SC36](https://www.iso.org/committee/45392.html) - Information technology for learning, education and training
- [1EdTech Consortium](https://www.1edtech.org/) - Global learning technology consortium developing interoperability standards for education and workforce development.
- [W3C](https://www.w3.org/) - World Wide Web Consortium developing web standards including JSON-LD and RDF used in learning metadata.

### Industry and Education Organizations
- [Advanced Distributed Learning Initiative (ADL)](https://adlnet.gov/) - U.S. DoD organization that originated xAPI and continues advancing learning technology research.
- [i2DL](https://www.i2idl.org/) - Entity seeking coordinating learning technology standards conformance across sectors and regions.
- [HR Open Standards Consortium](https://www.hropenstandards.org/) - Standards organization developing HR and workforce data specifications complementary to learning records.
- [Credential Engine](https://credentialengine.org/) - Registry of credentials, competencies, and learning opportunities using linked open data standards.
- [PESC](https://www.pesc.org/) - Standards organization for education data exchange including learning and employment records.

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
