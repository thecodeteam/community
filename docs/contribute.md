# How to contribute to {code} and add your project

## What are we looking for in {code} projects?
------------------------------------------------
The {code} by Dell EMC(tm) team is looking for projects that maximize the presence in the open-source world while solving problems with Dell, EMC and non-EMC technology. Projects that include elements that can be contributed to relevant non-EMC open source technologies AND solve customer problems are a big plus, but individually both are important. Scripts that are small and concise that solve customer problems are also a big plus. **We are looking for innovative approaches to solving problems!**

{code} will be cautious of things that obscure value to the open-source community. These can include large scope endeavors that are poorly documented and contain redundant or rewrites of existing open-source code.

{code} believes in the mantra of **“CODE OPEN, DEPLOY EVERYWHERE”**. If it’s not on GitHub, it doesn’t exist. Certain minimalistic formatting is also required.

Before starting the process, it’s best to engage the {code} team about
the project, by sending an email to [emccode@dell.com](mailto:emccode@dell.com). This email should include the following information:
* Name and Contact Information
* Description and Overview of the Project
* Have you reviewed the [DevHigh5 checklist](devhigh5.md)?
* Links to existing repos or other documents
* Details on any EMC products that might be involved in the project

All contributors shall follow the Contributor Agreement guidelines [provided here](contributor-agreement.md).

Also see [Governance and Contributions](governance-and-contributions.md)

### Stage 1 – Open Development
We encourage open development and collaboration using GitHub.com and personal repositories. The use of GitHub repos helps emphasize good coding, establishing the baseline for how to maintain published code moving forward, and ensure the contents of a project are not sensitive ahead of time.

Prior to submitting a request to {code}, the project should be published to GitHub via a personal account/repo.

### Stage 2 – Documentation & licensing
It is important to ensure a repo has proper documentation to describe the work and make it as useful as possible. There is an expectation that the instructions to get the code up and running are simple, concise, and accurate. If relevant there should also be documentation that helps someone take advantage of the code outside of prescribed situations included as examples.

Is the documentation in Markdown format?  Is it organized in a meaningful way? Is there a problem statement, expectations of code usage, requirements, dependencies, install instructions, and examples in place? Is there recognition/first contributors, references to other code, licensing and support statements in place?

Please use our [sample README.md](sample-README.md) as a skeleton for your project.

All contributions should be licensed under the MIT license.  Lieu of the MIT license, you may use the BSD 2 or 3 clause license as [outlined here](license-information.md)

Projects linked to by {code} should license their project code under a license that is recognized by the Open Source Initiative as compliant with the Open Source definition.

### Step 3 – Open Testing
It will be important to ensure that the code has been tested against many situations and limitations are well known before it is published to {code}. Having the code successfully used already is a big plus in terms of ensuring this step is satisfied.  If code is continually being updated during a testing period, ensure branching is being used or the latest commit is the desired test candidate.

How many people have tested the code? Is it being used on a continuous basis? Have you received any feedback from the users? How long as the code been published? Does the code pose any risks to a customer?

### Step 4 – Verify {code} Requirements
Code that is hosted or linked to/from the {code} site may be viewed by some and materialize as supported in some ways. It is important that there is a support statement that speaks to a community driven process and lack of formal (Dell EMC) service level agreements (SLAs). Although there are no SLAs, the community does expect involvement from code authors so you must be willing to answer questions about your code.

### Step 5 – Publish to {code}
The last step is to get the code published to the {code} GitHub site. There are three options in this stage.

1. For projects that will be controlled by the {code} team, the existing repo should be cloned and re-initialized.
2. If the submitter will maintain the project, the {code} GitHub account will maintain a fork and update the fork upon request.
3. Otherwise, a simple link may be used to recognize other GitHub repos where the author maintains all aspects of the releases.
