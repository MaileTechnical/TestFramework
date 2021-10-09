# TestFramework
A subject-matter-independent framework for automatically running self-checking test sets against an application.
## License
This is Open Source Software (OSS) licensed under Apache 2.0 (http://www.apache.org/licenses/LICENSE-2.0). 

Documentation is licensed under Creative Commons (https://creativecommons.org/).
## Overview
Read the description of the TestSequencer component for an overview of the intent and how it works.
For an overview of the messaging protocol view the sequence diagrams in the Documentation package.
## Usage
This framework must be combined with a subject-matter-specific "testbench" which specifies sequences of stimuli followed by observations.
At execution time, the framework sequences the injection of stimuli and the following observations adjudicate application response.
An example of the use of such a testbench in conjunction with the framework can be found in this car park control [application](https://github.com/MaileTechnical/CarPark).
## Issues
Please open issues for defects and feature requests within the GitHub issues database for this repository.
## Contributions
To contribute enhancements or defect resolutions, please follow this simple process:
1. Open an issue.  Each issue should cover a single defect or enhancement.
2. On your personal fork of the repository, create a branch named <issueNumber>_<short description of defect or enhancement> and make the changes on this branch.
3. Test your changes on all configurations.
4. Issue a pull request for your branch.
