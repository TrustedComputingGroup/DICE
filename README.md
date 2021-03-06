# TCG DICE Root of Trust
## Introduction
Trusted computing relies on Roots of Trust to provide security critical capabilities.  Establishment of a cryptographic device identity is a fundamental capability.  A strong device identity is the foundation upon which more sophisticated scenarios can be built.  This is important since, for modern infrastructure, it's not enough to simply identify the devices on the network.  To protect sensitive data and other resources, we need to be able to reason about the security posture of a given device.  To achieve this requires not only identification of devices but the capability for the device to reliably attest to a variety of device characteristics.

Cryptographic device identity and attestation are quickly becoming baseline security functionality in datacenters and critical infrastructure.  This is a great start but we need to go further.  We also need to address concerns over supply chain security, i.e., how do we know the devices and platforms within our infrastructure contain exactly those components we expect them to contain, and nothing more?  How do we know those components are genuine and running trustworthy firmware?

To achieve this, the concepts of identity and attestation can also be applied at the component level to ensure that devices were not tampered with and contain genuine components.  Individual components are built with their own independent Hardware Root of Trust (HRoT) which uniquely identifies the component and attests component firmware.  Attestation evidence provided by a device or platform can include individual component identity and attestation information, thus providing assurance of component authenticity and trustworthiness as part of the platform attestation.  In this way, we get a more comprehensive view of platform security.  With an increasing reliance on disaggregated and complex supply chains, component level security is more important now than ever.

As connected devices increase in ubiquity so do the threats.  And as more critical infrastructure leverages increasingly decentralized supply chains, we need to minimize our exposure to risk.  Scenarios for eliminating or mitigating these risks are some of the use cases being addressed today with TCG DICE (Device Identifier Composition Engine) and associated architectural specifications.  

TCG technologies cover a range of hardware security solutions but the set of security capabilities of the hardware is just one piece of the puzzle.  Equally important are the solution architectures and protocols built on these hardware capabilities, as well as the interoperability of these solutions.  This is central to TCG’s mission to drive security standards that advance the state of Trusted Computing.

## Organization
This reposiroty contains resources for the TCG DICE Workgroup.  It is organized as follows:
- `doc` - Published workgroup documents and related references, specifications, etc.
- *Fill this in as content is added*
