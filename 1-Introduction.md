# Introduction

The advent of the internet and mobile broadband has connected billions of people globally, providing access to knowledge, free communications, and a wide range of lower-cost, more convenient services. This connectivity has also enabled more people to access the financial ecosystem. Yet, despite this progress, access to financial services is still limited for those who need it most. 

The mission of Libra is to change this state of affairs \[1\]. In this paper, we present Move, a new programming language for implementing custom transaction logic and smart contracts in the Libra protocol \[2\]. To introduce Move, we: 

1. Describe the challenges of representing digital assets on a blockchain \(Section 2\). 
2. Explain how our design for Move addresses these challenges \(Section 3\). 
3. Give an example-oriented overview of Move’s key features and programming model \(Section 4\). 
4. Dig into the technical details of the language and virtual machine design \(Section 5, Section 6, and Appendix A\). 
5. Conclude by summarizing the progress we have made on Move, describing our plans for language evolution, and outlining our roadmap for supporting third-party Move code on the Libra Blockchain \(Section 7\). 

**Audience**. This paper is intended for two different audiences: 

• Programming language researchers who may not be familiar with blockchain systems. We encourage this audience to read the paper from cover-to-cover, but we warn that we may sometimes refer to blockchain concepts without providing enough context for an unfamiliar reader. Reading \[2\] before diving into this paper will help, but it is not necessary. 

• Blockchain developers who may not be familiar with programming languages research but are interested in learning about the Move language. We encourage this audience to begin with Section 3. We caution that Section 5, Section 6, and Appendix A contain some programming language terminology and formalization that may be unfamiliar.

