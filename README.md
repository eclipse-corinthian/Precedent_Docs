<!--
SPDX-FileCopyrightText: 2024 Orcro Limited <team@orcro.co.uk>
SPDX-License-Identifier: 0BSD
-->

# Eclipse Corinthian

## Welcome to the Eclipse Corinthian Project

**THE MATERIALS IN THIS REPOSITORY DO NOT CONSTITUTE LEGAL ADVICE. THEY ARE PROVIDED FREE OF CHARGE AS A RESOURCE WHICH WE HOPE YOU WILL FIND USEFUL, BUT BEFORE DEPLOYING THEM, YOU SHOULD TAKE APPROPRIATELY QUALIFIED LEGAL ADVICE IN THE COUNTRY OR JURISDICTION APPLICABLE TO YOUR TRANSACTION OR ACTIVITIES. THE LAWYERS INVOLVED IN DRAFTING THESE DOCUMENTS ARE NOT YOUR LAWYERS, AND TO THE MAXIMUM EXTENT PERMITTED BY LAW THEY, AND ALL OTHER CONTRIBUTORS, EXCLUDE ALL LIABILITY RELATED TO THE USE OR MISUSE OF THE DOCUMENTS OR OTHER MATERIALS CONTAINED IN OR OBTAINED FROM THIS REPOSITORY.**

The Eclipse Corinthian Project has identified areas where template and process documents would add value to legal processes involved in technology, specifically in the areas of procurement and M&A activities involving open source software.

Contributors can raise issues with the documents, fork the documents (for example to create jurisdiction-specific versions of them), and issue pull/merge requests.

The documents will be edited in markdown, with release versions made available in markdown, docx and plain text formats.

We intend to develop a simple and clear web frontend, meaning that users who don’t wish to engage with the development process can easily access them directly. The licensing model will allow unrestricted use, modification and re-distribution.

## Overview

The initial set of documents was developed by Moorcrofts LLP in association with Orcro Limited, both based in the UK. Orcro is an OpenChain partner organisation (openchainproject.org) and has been working to develop the following sets of documents:

1. A due diligence questionnaire and set of warranties for acquiring software from a developer using open source software; and

2. A due diligence questionnaire and set of warranties for use in M&A transactions involving a target which develops software using open source.

We also have a suite of documents drafted to facilitate the supply of services over the internet using microtransaction architectures, which have also been developed by specialist law firms in a number of jurisdictions worldwide. The roadmap includes the development of software intended to facilitate the drafting, assembly, storage and analysis of legal documents. For example, since drafting contracts shares many characteristics with writing software, we propose developing a module for the Eclipse IDE which facilitates this.

## Due diligence and warranties for open source development: procurement and M&A

The open source procurement and M&A process has historically focussed on specific releases of supplied software (for example, by analysing the composition of that specific software release, and reviewing the licences for each component within the release). This is becoming less and less effective as a means of analysing and determining compliance risk as software development moves to a CI/CD model (continuous integration/continuous deployment/development).

A much more effective approach is to focus the warranties on the development process itself, and the processes, policies and procedures which the developing organisation uses to manage that development process. An ISO standard, ISO5230:2020 (OpenChain) defines the characteristics that a development program must have in order to manage open source compliance risk effectively, and the standard lends itself to a framework both for due diligence, and for warranties, both in procurement and M&A. The beauty of this approach is that it does not require that the target is compliant with, or even aware of, ISO5230:2020 (but it does mean that applying the process to a compliant organisation is that much more straightforward).

The initial set of due diligence questions for procurement has been developed using the ISO5230 framework, with the input from many active members of the OpenChain project, and the procurement terms have themselves been adapted to form the M&A due diligence and warranty suite.

## Contributing

We welcome contributions from any interested people. Contributions will only be accepted where the contributor has signed the [Eclipse Contributor Agreement](https://www.eclipse.org/legal/eca/). To sign that, a prospective contributor will need to create an Eclipse account using the same email address that the GitHub contribution will be made with. The steps are straightforward and more information can be found in [eclipse-collections/CONTRIBUTING.md](https://github.com/eclipse/eclipse-collections/blob/master/CONTRIBUTING.md).

The relevant licences for the Corinthian project are:

- For the template documents: [Creative Commons Zero v1.0 Universal]() (SPDX: CC0-1.0);

- For documentation: [BSD Zero Clause License](https://spdx.org/licenses/0BSD.html) (SPDX: 0BSD);

- For code, one of the following (depending on the stated out-licence of the sub-project): BSD Zero Clause License, [Apache License 2.0](https://spdx.org/licenses/Apache-2.0.html) (SPDX: Apache-2.0) or [Eclipse Public License 2.0](https://spdx.org/licenses/EPL-2.0.html) (SPDX: EPL-2.0).

Licence texts can be found under [LICENSES/](LICENSES/) or via the hyperlinks above.

For more specific information see the relevant project files themselves.

