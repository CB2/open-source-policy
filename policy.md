# 18F: An Open Source Team

**Note:** This is currently a **draft**, **pre-decisional** document. It is **not finalized** for 18F.

[18F](https://18f.gsa.gov), a digital services delivery team within the [General Services Administration](http://gsa.gov), develops in-house digital solutions to help agencies meet the needs of the citizens and businesses it serves. This requires flexibility in how we code, with a focus on lowering costs for the American people, while improving their interactions with the U.S. Government.

The default position of 18F when developing new projects is to:

1. Use Free and Open Source Software (FOSS), which is software that does not charge users a purchase or licensing fee for modifying or redistributing the source code, in our projects and contribute back to the open source community.
2. Create an environment where any project can be developed in the open.
3. Publish all source code created or modified by 18F and its contractors publicly.

## Benefits

Using FOSS allows for product customization, advances interoperability between tools, and improves the overall quality of the final product. Other benefits include:

1. **Flexible usage.** The benefits of using FOSS compel 18F to meet citizen and business needs by modifying existing or creating new FOSS. FOSS is particularly suitable for rapid prototyping and experimentation. The testing process generates minimal costs, and the process encourages the identification and elimination of defects not recognized by the original development team.

1. **Community involvement.** Publicly available source code enables continuous and broad peer review. Whether simply publishing the completed code or opening the development process, the practice of expanding the review and testing process to a wider audience&mdash;beyond the development team&mdash;ensures increased software reliability and security. Developing in the open also allows for other opinions to help adjust the direction of a product to maximize its usefulness to the community it serves.

1. **Cost-savings.**  The ability to modify FOSS enables 18F to respond rapidly to changing missions and markets. Support and maintenance of open source code&mdash;as opposed to more burdensome usages of proprietary software&mdash;provides a real cost advantage where multiple copies of software are required, or when the user base grows. The total cost of ownership is shared with a community, rather than solely 18F.

1. **Reusability.** The code we create belongs to the American people as a part of the public domain. The code we work on was paid for by the American people, but the end-product is not the only way they should be able to interact with their government. By coding in FOSS, we help populate a larger commons that cities, states, businesses, and citizens can participate in. This creates real economic value by lowering the burden of replicating similar work or by allowing the private sector to build off of and create new businesses around code developed at 18F.

## Maximizing Community Involvement and Reuse

Active involvement from the open source community is integral to the success of open source code. 18F will be an active contributor to FOSS projects that it or its clients utilize, whether they are maintained or operated by 18F. Code written entirely by 18F staff, and by contractors who are developing software on behalf of 18F, are within the public domain. Because of this, 18F encourages contributions to its open source projects, whether it be code, commentary, bug reports, feature requests, or overall strategic direction.

Because all of 18F’s work is intended to be released for public use, forks or clones of our code repositories are free to be re-distributed. This means code created by 18F can be integrated into work that is under a more restrictive license, even those that are not considered open source licenses.

This changes when our code repositories include code that was not created by 18F and carries an open license. Code previously released under an open source license and then modified by 18F or its contractors is considered a ["joint work"] [4] and must be released under the terms of the original open source license.

  [4]: http://www.copyright.gov/title17/92chap1.html#101 "Joint Work"

The public can use our code as the basis of wholly proprietary and commercial systems. 18F would appreciate that users of our code disclose its lineage, but 18F maintains no legal right to require disclosure. Notifications that our work is used in a new system are always greatly appreciated.

## Open Source Licenses

As previously mentioned, most work generated at 18F falls within the U.S. public domain.

For our international colleagues, 18F also permanently waives all copyright and related rights worldwide to code created by 18F or its contractors.

Our [default LICENSE file](LICENSE.md) for projects acknowledges that our work is in the US public domain, and uses [CC0](https://creativecommons.org/publicdomain/zero/1.0/) to waive copyright internationally.

Our [default CONTRIBUTING file](CONTRIBUTING.md) informs contributors that their contributions will be licensed under the same terms.

However, certain projects will require the usage of licensed open source software not created by 18F. Some open source licenses make source code available under different terms and conditions. These terms and conditions specify how the code may be used, modified, or shared. When users modify 18F code, they should review and understand the terms of the open source license in question.

Each project may need to modify or extend the above LICENSE and CONTRIBUTING files as needed for its own circumstances.

## Distribution of Code

There is a misconception that FOSS that is distributed to the public should not be integrated or modified for use in sensitive systems. On the contrary, FOSS is often preferred for use in sensitive systems, due in part to its increased auditability. In other words, security in FOSS must be designed never to rely on obscurity in how the code works.

In addition, many open source licenses permit the user to modify OSS for internal use without obligating them to distribute source code to the public. However, if the user chooses to distribute the modified OSS outside the user's organization, then it is subject to whatever license it carries.

## Legal and Policy

Agencies have been encouraged to acquire the best information technology service to meet their needs. The Office of Management and Budget (OMB) has released memoranda indicating that policies surrounding procurement of new information technology are ["intentionally technology and vendor neutral,"][5] and has [stated][6] that open source software can and should be considered when procuring new services. In nearly every case, FOSS meets the definition of ["commercial computer software"][7] and agencies are [required][6] to include open source software in their market research.

  [5]: http://www.whitehouse.gov/omb/memoranda_fy04_m04-16 "OMB M-04-16"
  [6]: http://www.whitehouse.gov/sites/default/files/omb/assets/egov_docs/memotociostechnologyneutrality.pdf "OMB Memo on Tech Neutrality"
  [7]: http://www.gpo.gov/fdsys/pkg/CFR-2011-title48-vol1/pdf/CFR-2011-title48-vol1-sec27-405-3.pdf "Commercial computer software"

Numerous agencies&mdash;most prominently the [Department of Defense (DoD)](http://en.wikipedia.org/wiki/Use_of_Free_and_Open_Source_Software_(FOSS)_in_the_U.S._Department_of_Defense)&mdash;regularly use FOSS to meet their own needs and have updated their internal policies to take part in the communities built around FOSS.

## Exceptions

The only conditions where code shall not be released or developed in the open are:

* The U.S. Government does not have the rights to reproduce and release the item.

* The public release of the item is restricted by other law or regulation, such as the Export Administration Regulations or the International Traffic in Arms Regulation.

These decisions will be made as needed by the 18F DevOps team, which will lead an interdisciplinary team to review the conditions under which code will not be made available publicly. Any further exemptions will be rare, documented publicly, and the result of compelling interest. 

If an existing solution cannot be found in the open source community, 18F may consider other options, including creating an open source solution itself. Ultimately, the software that best meets the needs and mission of 18F should be used.

## Thanks

18F would like to thank the Consumer Financial Protection Bureau, Department of Defense, and Office of Management and Budget for their work in blazing the path for the use of FOSS in the Federal Government.

## Future Changes

This policy is a living document. 18F expects to make changes to this policy in the future, and we welcome [issues](https://github.com/18f/open-source-policy/issues) and pull requests. To contact us privately, email <a href="mailto:18F@gsa.gov">18F@gsa.gov</a>.