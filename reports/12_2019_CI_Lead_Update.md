# gcrNet CI Lead Update - December 2019

Author: *Jeff Whitworth (gcrNet PI)*

Date: *December 6, 2019*

## Project Update

The project is in Phase 1: Design Vaidation. Phase 1 was scheduled to complete in September 2019 but is currently delayed an estimated 5 months due to multiple reasons including:

* Project start date - the actual project start date (July 1, 2019) was 2+ months earlier than the proposed start date. Logistical issues were encountered in starting the project at both institutions (researcher availability, GA hiring, contracts & grants)
* Network redesign - The NSF CC* PI meeting revealed multiple issues with the origional network and server specifications. This required further investigation of the network requirements and ultimately design changes to both the network and server infrastructure.
* GA hiring - Graduate assistants were not able to be hired until after the fall semester started.
* Personel Changes - Multiple personel changes have required reassignment of staff.
* Multi-institution collaboration - Determining and setting update collaboration tools and project management tools between multiple institutions was not accounted for in the proposed project.

It is highly likely that the gcrNet project will need to request a no-cost extension.

### Phase 1 Milestone Status

__Completed:__

* Develop gcrNet Governance
* Update Network Quotes
* Validate Network Architecture

__In Progress:__

* Update Server Quotes
* Create research network satisfaction survey 

__Not Started:__

* Document Sustainability Plan
* Develop draft procedure for connecting devices to the gcrNet
* Create "Policy for Systems Involving High Speed Data Transfers"

## Year 1 Budget

*Total Year 1 Directs Actual (Budget):* $  ($353,531)

Equipment (hardware, support, supplies): $118,268.88 ($228,022)

Travel: $1,312.35 ($3,000)

Subawards: $116,593

Salaries (Senior Personel + GA): $3,727.57 ($15,049)

### Subaward

*Total Year 1 Directs Actual (Budget):* ($108,669)

Equipment (hardware, support, supplies):  $100,987.26 ($90,659)

Travel: ($3,000)

Salaries (Senior Personel + GA): ($13,924)

## gcrNet Network Update

After the CC* PI meeting it was determined that the initial network hardware did not have adequete buffer sizes to cupport high-speed WAN transfers of large data sets. This determination was made in collaboration with the esNet and EPOC hardware engineers. The network design has been updated to reflect hardware that will meet the requirements and has been reviewed and endorsed by esNet and EPOC.

In addition to changing the switch hardware, he network design removed a distribution switch from UNCG. The gcrNet core servers will be connected directly to the router.

The network design has been validated and a final quote for hardware for both UNCG and NC A&T. Deveices are ready for purchase. The NC A&T budget allocation will need to be updated to reflect the increased cost.

There are currently no network devices installed.

## gcrNet Systems Update

It was determined that the proposed DTN and IDS server specifications did not meet requirements to process 10G network and support high-speed WAN data transfers. Traditional data center hardware does not meet these needs and alternatives are currently being explored. Spcifically, the processor and network interface cards are being examined to find a vendor that can provide the necessary hardware. This will most likely be Dell or SuperMicro.

There are currenrtly no servers installed.

## gcrNet Research Projects Update

Research projects are pending the gcrNet moving to production.

## Additional Notes

I believe one reason that this proposal was selected for funding is the collabrative nature of the proposal. The majority of Science DMZ implementations appear to by single institution and a multi-institutional implementation presents some unique challenges. These include logistical (collaboration tools, timing, procurement) and budgetary. Both institutions use different vendors for some infrastructure, and even when the same is used the supporting account teams may not match. This has made alignment difficult all the way out to the hardware providers. The CC* budget cap of $500,000 requires some creative engineering, and ultimately is not enough to complete the project without some sacrafices. Much of this has been accounted for on the senior personel salaries reduction.

While there are challenges, there have also been some areas that are much simpler because we are creating a dedicated network. We do not have to contend with enterprise traffic and build around existing infrastructure - this is a "greenfield" network. This allows for a rather simple design and removes some of the edge burdens (IDS, router) that typically are a challenge for a Science DMZ.
