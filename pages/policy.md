---
title: DCOI Policy
permalink: /policy/
layout: page
sidenav: policy

---

{% if site.draft %}
<header class="draft-instructions">
  <p>
    This is a draft policy open for public feedback. You may provide feedback in three ways:
  </p>
  <p>
   1. Content suggestions and discussions are welcome via GitHub “issues.” Each issue is a conversation initiated by a member of the public. We encourage you to browse and <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/issues">join in on discussions</a> in existing issues, or start a new conversation by opening a <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/issues/new">new issue</a>.
  </p>
  <p>
    2. Direct changes and line edits to the content may be submitted through a <a href="https://help.github.com/articles/creating-a-pull-request">&quot;pull request&quot;</a> by clicking &quot;Edit this page&quot; on any site page in <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/tree/{{ site.github.default_branch }}/pages/">the repository.</a>. You do not need to install any software to suggest a change. You can use GitHub's in-browser editor to edit files and submit a pull request for your changes to be merged into the document. Directions on how to submit a pull request can be found <a href="https://help.github.com/articles/creating-a-pull-request">on GitHub</a>. Open pull requests for the proposed guidance can be found <a href="https://github.com/{{ site.github.organization }}/{{ site.github.repository }}/pulls">in the site repository on GitHub</a>
  </p>
  <p>
    3. Send your content suggestions or proposed revisions to the OMB Office of the Federal Chief Information Officer via email to <a href="mailto:{{site.mail}}">{{site.mail}}</a>. Please note that all comments received will be posted publicly.
  </p>
  <p>
    Comments must be received on or before December 26, 2018.
  </p>
</header>
{% endif %}

**DRAFT MEMORANDUM FOR HEADS OF EXECUTIVE DEPARTMENTS AND AGENCIES**

FROM: Suzette Kent

Federal Chief Information Officer

# SUBJECT: Update to Data Center Optimization Initiative (DCOI)

The Federal Information Technology Acquisition Reform Act (FITARA)
passed in 2014,[^1] and required the Federal Government to consolidate
and optimize agencies' data centers until October 1, 2018. The Office of
Management and Budget (OMB) responded by issuing M-16-19, Data Center
Optimization Initiative (DCOI),[^2] which set priorities for data center
closures and efficiency improvements through the end of Fiscal Year 2018.
The FITARA Enhancement Act of 2017[^3] extended the data center
requirements of FITARA until October 1, 2020. As a result, OMB is
updating and extending the Data Center Optimization Initiative for
another two years.

This Memorandum contains requirements for the consolidation and
optimization of Federal data centers in accordance with Federal
Information Technology Acquisition Reform Act (FITARA). It establishes
consolidation and optimization targets and metrics for Federal agencies,
as well as requirements for reporting on their progress.

## Background

The Federal Government has made great strides in consolidating and
optimizing Federal data centers since 2010, when the Office of
Management and Budget (OMB) launched the initial Federal Data Center
Consolidation Initiative (FDCCI).[^4] Since then, agencies have achieved
significant cost savings, have improved their understanding of energy
efficiency technologies, and have begun implementing the initiative with
cloud-based and hybrid environments.

After eight years of work in consolidating and closing Federal data
centers, OMB has seen diminishing returns from agencies resulting from
their closures. Much of the "low-hanging" fruit of easily consolidated
infrastructure has been picked, and to realize further efficiencies will
require continued investment to address the more complex areas where
savings is achievable. While optimization will be the new priority,
consolidation and closures should continue wherever applicable. OMB will
focus on targeted improvements in key areas where agencies can make
meaningful improvements and achieve further cost savings.

## Authority

The requirements in this memorandum apply to the 24 Federal agencies
covered by the Chief Financial Officers (CFO) Act of 1990,[^5] including
the Department of Defense.[^6] The head of each covered agency, assisted
by the Chief Information Officer (CIO) of the agency, is required to
submit to OMB annually 1) a comprehensive inventory of the data centers
owned, operated, or maintained by or on behalf of the agency, and 2) a
multi-year strategy to achieve the consolidation and optimization of
these data centers. Each agency, under the direction of their CIO, must
submit quarterly updates on their progress towards completion of
activities, consolidation & optimization metrics, and cost savings
realized through the implementation of their strategy.

OMB is required to establish the deadlines, requirements, metrics for
agencies' reports, and must review the reports and progress of agencies
towards consolidation and optimization.

## Policy

This memorandum establishes a new Data Center Optimization Initiative
(DCOI), which replaces the previous DCOI created in M-16-19 for all
purposes.

Effective immediately, OMB rescinds M-16-19.

## Development Freeze for New and Current Data Centers

Agencies may not budget any funds or resources toward initiating a new
data center or significantly expanding an existing data center without
approval from OMB. To request such approval, agencies must submit a
written justification that includes an analysis of alternatives,
including opportunities for cloud services, shared services, and third
party co-location. This justification must include an explanation of the
net reduction in the agency's data center inventory that will be
facilitated by the new or expanded data center (such as through
consolidation of multiple existing data centers into a single new data
center).

This development freeze shall not apply to critical agency facilities as
described under the "Key Mission Facilities for Data Management" section
below. Agencies are strongly encouraged to have a detailed discussion
with OMB in advance of any planned expansions or new construction of
data center facilities.

## Consolidation and Closure of Existing Data Centers

As previously required by the FDCCI, agencies shall continue to
principally reduce application, system, and database inventories to
essential enterprise levels by increasing the use of virtualization to
enable pooling of storage, network and computer resources, and dynamic
allocation on-demand. Agencies shall evaluate options for the
consolidation and closure of existing data centers where practical, in
alignment with the **Cloud Smart**[^7] strategy. The Cloud Smart
strategy emphasizes the use of risk-based decision-making and service
delivery as key considerations in evaluating cloud technologies.

Potential options for migration include:

-   Transitioning to provisioned services, including cloud technologies,
    to the furthest extent practical;

-   Migrating to inter-agency shared services, intra-agency shared
    services, or collocated data centers; and

-   Migrating to more optimized data centers within the agency's data
    center inventory.

### Cloud and Data Center Optimization Initiative Program Management Office

OMB still considers shared services and shared knowledge to be
cornerstones of data center consolidation. As such, the General Services
Administration (GSA) Office of Government-wide Policy (OGP) shall
continue to maintain the Cloud and Data Center Optimization Initiative
Program Management Office (CDCOI PMO). OMB will no longer require GSA to
establish and maintain a data center shared services marketplace. In
this role, OGP will serve as a trusted agent, information broker, and
subject matter expert to assist data center providers and consumers of
data center services by providing guidance on technology advancements,
innovation, cybersecurity, acquisition, and best practices.

OMB tasks the CDCOI PMO, in consultation with the Office of Shared
Services and Performance Improvement (OSSPI) and the Technology
Transformation Service (TTS), with the following actions:

-   Coordinating with OMB to develop resources and guidance on data
    center and cloud implementation and optimization;

-   Coordinating with other key GSA components to create and maintain an
    inventory of acquisition tools, contract language, and products
    specific to the technology and services surrounding data center
    optimization, including procurement vehicles for the acquisition of
    automated infrastructure management and monitoring tools;

-   Developing, implementing, and maintaining financial and service
    models pertaining to cloud and data center procurement with
    customer/partner agencies and shared service providers; and

-   Providing a forum for participating and interested agencies to
    discuss cloud and data center implementation and optimization.


## Cloud Investment

Cloud environments are scalable and allow agencies to provision resources as required, on-demand.13 Consistent with the Cloud First policy, agencies shall use cloud infrastructure where possible when planning new mission or support applications or consolidating existing applications. Agencies should take into consideration cost, security requirements, and application needs when evaluating cloud environments. As required by FITARA, agencies utilizing cloud services shall do so in a manner that is consistent with requirements of the Federal Risk and Authorization Management Program (FedRAMP) and National Institute of Standards and Technology (NIST) guidance.

## Optimization of Data Centers

Over the past two years, the Office of Management and Budget has
received extensive feedback from agencies as they implemented the Data
Center Optimization Initiative, identifying areas where agencies were
able to achieve the greatest improvements and savings, as well as those
that did not yield a positive return on investment. In alignment with
the Administration's directive of shifting from low-value to high-value
work, and removing unnecessarily burdensome reporting,[^8] OMB revises
the classification of data centers and the optimization metrics as
follows.

### Classification of Physical Data Centers

Agencies have seen the greatest gains in cost savings and optimization
in their larger, dedicated data centers providing general compute
resources to the enterprise. However, the previous definition of a
"tiered" data center resulted in spaces reported as server closets
simply due lack of a backup generator or other hardware, even if they
acted as a data center in all other regards. The intent, instead, is to
treat these facilities as full-fledged data centers. Therefore, for the
purposes of this memo, agencies shall report purpose-built physically
separate and dedicated spaces as tiered data centers when they
appropriately meet key criteria. Agencies should focus their efforts on
"general compute" servers and systems -- those hosting business
applications that are largely hardware agnostic -- rather than special
purpose systems.

Agencies have seen little real savings from the consolidation of
non-tiered facilities, small server closets, telecom closets, individual
print and file servers, and single computers acting as servers.
Optimizing and consolidating these spaces not designed to be data
centers generally incurs large costs for agencies, with little or no
benefit from efficiencies gained. This also frequently introduces
additional hurdles in the form of increased latency and other
performance detriments that unfavorably affect agency mission delivery.
As a result, OMB will no longer require agencies to consolidate these
server closets, meet optimization targets, or include them in their
inventory submissions. Agencies should consolidate any business
applications hosted in non-tiered data centers and closets whenever
cost-effective, appropriate for agency mission, or to enhance system
security or privacy[^9].

Private sector-provided cloud services are not considered data centers
for the purposes of this memorandum, but agencies must continue to
report these in their quarterly inventory data submissions to OMB.

### Key Mission Facilities for Data Management

In the original M-16-19 memo, OMB created an exemption for some data
centers from closures:

> *"data centers that are physically inseparable from non-IT hardware
> (e.g. simulation and modeling devices, sensors, etc.) and that perform
> a specific, non-standard set of tasks (e.g. do not provide general
> purpose computing or storage services to Federal facilities)."*[^10]

As a matter of practice, agencies have many types of mission-critical or
non-severable systems and services that do not fit into this definition.
These include MRI machines, weather stations, air traffic control
systems, supervisory control and data acquisition (SCADA) systems, and
other uses where separation of data collection, storage, and processing
is technically possible but increases latency beyond a reasonable
amount. Agencies cannot consolidate many types of systems in remote
locations without detriment to the agency mission; these range from
embassy file servers in foreign countries to dam floodgate controls.
Furthermore, numerous Federal labs and research facilities have data
centers that cannot be consolidated and where further optimization (such
as lowering energy usage) would have an unacceptably negative impact on
performance; these include special-purpose processing nodes (SPPNs),
high-performance computing (HPC) nodes, and similar systems. Finally,
numerous data centers will continue to be required for legal or
logistical reasons.

As a result, for individual tiered data centers that fall within these
areas, agencies may request an exemption from closure targets as well as
optimization metrics, with justification. While these data centers may
be exempt from requirements, agencies should optimize them for energy
and operational efficiency where practical.

### Closures and Cost Savings

The amount of information gathered and processed by the Federal
Government continues to grow, especially with the rise of the "Internet
of Things," cheap mobile computing, and Smart Cities. This has resulted
in increasing agency compute needs to keep up with demand. Although
vendor-provided services such as cloud technologies are potential
solutions, they are not always more cost-effective alternatives to
agency-hosted services. As a result of work that has occurred over the
past years, there will be continuous improvements, but the Federal
Government should not expect to see continued dramatic savings or
large-scale closures from ongoing data center consolidation and
optimization efforts.

Agencies should consider opportunities for investments that may yield
long-term savings through energy efficiency. For instance, refreshing
inefficient hardware may lead to long-term savings, especially where
legacy systems past their end-of-life incur large costs for support.
Agencies should also consider EPEAT-registered servers when upgrading or
replacing hardware to maximize energy efficiency. The standard used by
EPEAT requires registered servers to be ENERGY STAR certified and
support ASHRAE's Class A2 or higher allowable environmental operating
range, and further incentivizes efficiency levels beyond ENERGY STAR for
power supplies and active/inactive power states. Agencies are also
encouraged to use performance contracting including Energy Savings
Performance Contracts[^11] and Utility Energy Service Contracts[^12] to
finance energy improvements.

The Office of Management and Budget will continue to work with agencies
to set agency-specific goals for data center closures and cost savings
that are appropriate to the mission and budget of each agency. OMB will
update these targets from those set for M-16-19 to match agencies'
current status and progress.

### Automated Infrastructure Management

Agencies should continue to replace manual collections and reporting of
systems, software, and hardware inventory housed within data centers
with automated monitoring, inventory, and management tools (e.g., Data
Center Infrastructure Management (DCIM)). Agencies will need to update
these tools to match the performance metrics defined in this memorandum.

Any data center initiation, significant expansion, or migration project
that received Development, Modernization, and Enhancement (DM&E) funds
in fiscal year 2017 or later must implement automated monitoring and
management tools. Agencies are strongly encouraged to implement
automated monitoring and management tools throughout their data centers.

To the extent permissible under the Federal Acquisition Regulation
(FAR), agencies must include automated infrastructure management
requirements for all new data center service contracts or procurement
vehicles. Further, any new data center contractor procurement vehicle
must require the contractor to report to the contracting agency whether
the contracted facility utilizes automated infrastructure management,
except where such data is already reported directly to OMB or GSA
through participation in a multi-agency service program.

Agencies are encouraged to require the same for extension of existing
vehicles. GSA has identified acquisition vehicles for automated
monitoring and management tools to support agency needs. Agencies shall
not issue new solicitations for these requirements unless they have
developed a business case, approved by the agency's CIO and shared with
OMB, to establish that the separate procurement of these needs results
in better value, considering price and other appropriate factors.

## Performance Metrics

OMB calculated the performance metrics outlined in M-16-19 as averages
across an agency's entire inventory of applicable data centers. These
calculations resulted in a lack of clarity around specific successes and
failures across an agency's inventory, and a few low-performing data
centers would dramatically reduce the apparent efficiency of an entire
agency. This would result in data centers scheduled for closure -- which
would not be cost-effective for optimization -- negatively affecting the
overall average. Several of the metrics were nearly impossible for
agencies to meet, and the only success criteria was whether the average
did or did not meet the given target. As a result, these averages do not
yield transparency into how effectively or efficiently an agency is
running data centers, or whether the agency is improving over time.

Moving forward, to more accurately measure the performance of data
centers, OMB will avoid using averages for metrics whenever possible or
setting arbitrary goals, and will instead identify metrics where
agencies can demonstrate continuous improvement beyond the performance
period of this memorandum.

### Updated Metric: Virtualization

With the rapidly growing marketplace around virtualization and
containerization, this remains an important area for agencies to realize
savings and optimization. The ability to assign resources dynamically
based on need is key to delivering timely services, and is an important
concept in the **Cloud Smart** strategy. As such, OMB prioritizes the
increased virtualization of Federal systems as critical for IT
modernization efforts, to drive efficiency and application portability.
OMB expects all new agency applications to use virtualization whenever
possible and appropriate.

Due to the number of virtual client applications fluctuating based on
demand, calculating these as a ratio to physical hosts, as described in
M-16-19, is not ideal. The former policy also did not include mainframes
that can support virtualization, or include servers that host containers
through popular tools. Instead, OMB will require agencies to report the
number of servers and mainframes that are currently serving as hosts for
virtualized or containerized systems in their agency-managed data
centers.

Under this memorandum, agencies are required to report their cloud
investments as part of their data center inventories. Given that
transitioning applications to the cloud may reduce the count of virtual
hosts in their data centers, and given that cloud providers use
virtualized systems by definition, agencies *may* report systems under
their cloud investments towards this total count to more accurately
reflect the state of their virtualized portfolio.

### Updated Metric: Advanced Energy Metering

To judge how efficiently a data center is using electricity, the use of
metering through Data Center Infrastructure Management (DCIM) tools can
help to determine where efficiencies may be found. Installing advanced
energy meters in data centers, as described in M-16-19, was required by
Executive Order 13693: Planning for Federal Sustainability in the Next
Decade, but that order has since been revoked by the Executive Order
13834: Efficient Federal Operations.[^13]

Although automated monitoring is advantageous for agencies to gain
better insight to energy usage and to drive optimization, it can also be
prohibitively expensive for agencies to purchase and install these
tools. Many facilities already have energy metering and other
measurement devices that are not specific to the data center area of the
facility, and an experienced facilities manager will be able to estimate
energy usage accurately. It is not useful for agencies to install these
tools in a facility they are planning on closing.

OMB will continue to track agencies' implementations of advanced energy
metering by measuring the number of facilities with a majority of the
space having this metering, rather than using a combined metric of
metering and gross floor area as required under M-16-19. Furthermore,
agencies will be able to request an exemption for individual facilities
where it is not cost effective to install this monitoring, or if they
are planning to close the facility.

### Removed Metric: Energy Efficiency

M-16-19 required agencies to report the energy efficiency of data
centers using Power Usage Effectiveness (PUE), the proportion of energy
used by IT equipment compared to the total energy used by the data
center. That memorandum set a target goal of PUE of 1.5 for existing
data centers, and 1.4 for new data centers, as defined in Executive
Order 13693 -- which, as mentioned previously, was revoked by Executive
Order 13834.

The PUE metric does not allow for easy comparison between multiple
facilities or agencies. Differences in factors such as geographic
location, weather, time of year, and building construction can have a
huge impact on the measured PUE of a facility. For instance, an
extremely efficient data center in a warmer part of the country can
easily register a higher PUE than an inefficient data center in a colder
climate, but agency mission may determine the location of that facility.

The intent of energy efficiency under DCOI is to drive savings through
lowered energy usage, but there is an upper bound on the savings gained
through this optimization. Although OMB will continue to collect PUE as
part of the inventory reporting for statistical purposes, it will no
longer set a target for PUE or use this metric to judge improvement over
time. Instead, agencies are encouraged, but not required, to report cost
savings and avoidance through efficient energy usage and improvements as
part of their data center strategic plans.

### Updated Metric: Server Utilization

FITARA establishes the requirement for OMB to track data center
"efficiencies, including, at a minimum, server efficiency."[^14] OMB
interprets this to mean that the Federal Government should be
identifying and reducing underutilized servers. The metric defined for
Server Utilization in M-16-19 set a baseline for utilization as a
calculated average, which did not aid in finding and removing
underutilized servers. Moreover, this was measured as a combined metric
with "automated monitoring," making the target more difficult for
agencies to achieve.

"Server efficiency" is a relative term, depending on the nature of the
hardware and applications running on the server (i.e. citizen-facing
systems that may only have high utilization during peak business hours).
Agency mission may also determine whether a server is running
efficiently or not --possessing many redundant systems may be
inefficient for one agency, but necessary for another to be able to
respond to critical emergencies and security incidents.

As a result, OMB will task agencies with identifying and reporting the
number of under-utilized production servers in each data center, with
the intent that agencies should reduce the number of these servers over
time. Since backups, standbys, development, and test servers are all
critical to a well-functioning enterprise information system, they will
not be included in this measurement -- but agencies will count and
identify these systems for transparency.

Due to mission-specific, device-specific, and application-specific
requirements influencing what can be considered efficient operation, OMB
will not set a specific methodology for determining server utilization
evaluation for each agency. OMB expects agencies to consider CPU usage
and storage space at a minimum. Agencies should use this process
regularly, to identify applications that require large amounts of
resources seasonally or infrequently which may be ideal candidates to
shut down or move to cloud technologies, in alignment with the **Cloud
Smart** strategy.

As agencies are performing this rationalization, automated monitoring is
strongly suggested to measure application usage to accurately determine
needs -- such as storage space, CPU, memory, and redundancy -- for
moving to cloud or otherwise. OMB will no longer include automated
monitoring as part of this metric, as it is largely duplicative of the
metering under the Automated Infrastructure Management requirement and
Advanced Energy Metering metric.

### Removed Metric: Facility Utilization

In the process of consolidating data centers, OMB expects agencies to
find opportunities where they can move existing server inventory to
other facilities, resulting in greater density at the destination
facility. OMB has determined with input from agencies that in practice
Facility Utilization as a metric is in conflict with other, more
impactful priorities. For instance, increasing facility utilization can
negatively affect energy efficiency; meanwhile, improved virtualization
generally reduces facility utilization as agencies consolidate their
systems.

The method of calculating utilization outlined in M-16-19 uses an
idealized average for the floor space usage of server racks, without
taking into account elements such as mainframes, vertical designs not
requiring raised floors, or planning for future expansion. Since this
metric is largely redundant with accounting for progress towards the
overall consolidation effort, OMB will no longer track agencies
performance in this area.

### New Metric: Availability

For the commercial space, the most critical element for an
infrastructure provider is availability of the facility. Most service
level agreements contain discussion of the availability that the service
guarantees. The Federal Government should be prepared to deliver the
same level of service as that provided by private sector data centers
and cloud services.

OMB will require agencies to report the planned hours of availability
for each data center, as well as any unplanned outages for that data
center over the reporting period, also measured in hours. Unavailability
will include unplanned outages of a majority of the facility due to
disaster, systems failure, cybersecurity events, or other negative
events as well as any other hours that would otherwise be planned as
available hours.

This metric will track the data center's availability, not individual
server or application uptime or availability.

## Clarification on the Prioritization of Concerns

With numerous metrics and possible methods to optimize a data center,
agencies could select a variety of solutions and ways to invest in this
process. Not all of these methods will yield the same level of impact.

OMB prioritizes the effort to consolidate and optimize data centers in
the following hierarchy, to maximize the return on investment and based
on the level of impact for the effort. When considering the allocation
of limited resources or conflicting priorities, agencies should consider
their mission goals first, and this prioritization second.

1. Consolidation and Closure
2. {: .nested-list } Optimization
    1. Virtualization
    2. Availability
    2. Energy Metering
    4. Server Utilization

## Reporting

OMB will collect data on an agency-by-agency basis through the
Integrated Data Collection (IDC), as follows:

1.  Agencies must continue to maintain complete inventories of all data
    center facilities, closure/consolidation plans, and properties of
    each facility owned, operated, or maintained by or on behalf of the
    agency. Agencies must update these inventories at least annually,
    but agencies may optionally submit a quarterly update to improve the
    accuracy of the data.

2.  Agencies must annually evaluate the costs of operating and
    maintaining current facilities, and develop year-by-year targets for
    cost savings and cost avoidance due to consolidation and
    optimization through the sunset of this policy. Agencies shall
    report all realized cost savings and cost avoidance under the DCOI
    as part of their DCOI Strategic Plan (see below).

3.  Agencies must report quarterly progress toward meeting their
    closures & metric target values. Agencies may submit this
    information as a separate prose document.[^15]

### DCOI Strategic Plan

In accordance with FITARA,[^16] each agency head shall annually publish
a Strategic Plan to describe the agency's consolidation and optimization
strategy through the sunset of this policy. The DCOI Strategic Plan and
milestones described below replace existing FDCCI requirements for
consolidation plans.

Agencies' DCOI Strategic Plans must include, at a minimum, the
following:

1.  Planned and achieved performance levels for each optimization
    metric, by year;

2.  Planned and achieved closures, by year;

3.  An explanation for any optimization metrics and closures for which
    the agency did not meet the planned level in a previous Strategic
    Plan;

4.  Year-by-year calculations of target and actual agency-wide spending
    and cost savings on data centers through the sunset of this policy,
    including:

    a.  A description of any initial costs for data center consolidation
        and optimization; and

    b.  Life cycle cost savings and other improvements (including those
        beyond the sunset of this policy, if applicable).

5.  Historical costs, cost savings, and cost avoidances due to data
    center consolidation and optimization; and

6.  A statement from the agency CIO stating whether the agency has
    complied with all reporting requirements in this memorandum and the
    data center requirements of FITARA. If the agency has not complied
    with all reporting requirements, the agency must provide a statement
    describing the reasons for not complying.

Agencies are required to publish their Strategic Plans at
\[agency\].gov/digitalstrategy under a section entitled, "Data Center
Optimization Initiative Strategic Plans." Agencies shall also make their
strategic plans available in a machine-readable format. OMB will provide
instructions to agencies, including a schema, 30 days of the issuance of
this memorandum.

Agencies shall update their agency digital milestones files, also posted
on their websites, to identify at a minimum five milestones per fiscal
year to be achieved through the DCOI. Agencies should update their DCOI
milestones quarterly as they progress. OMB will review these milestones
with the agencies in quarterly PortfolioStat[^17] sessions.

## Effective Date and Sunset

This memorandum is effective immediately, and will sunset on September
30, 2020.


## Footnotes

[^1]: Title VIII, Subtitle D of the National Defense Authorization Act
    (NDAA) for Fiscal Year 2015, Pub. L. No. 113-291, available at
    [https://www.congress.gov/113/plaws/publ291/PLAW-113publ291.pdf\#page=148](https://www.congress.gov/113/plaws/publ291/PLAW-113publ291.pdf%23page=148%20)
 

[^2]: <https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2016/m_16_19_1.pdf>

[^3]: FITARA Enhancement Act of 2017, Public Law No. 115-88:

    <https://www.congress.gov/115/plaws/publ88/PLAW-115publ88.pdf>

[^4]: FDCCI was established by OMB "Memo for CIOs: Federal Data Center
    Consolidation Initiative," issued on February 26, 2010, and modified
    by subsequent memoranda.
    <https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/assets/egov_docs/federal_data_center_consolidation_initiative_02-26-2010.pdf>

[^5]: See Chief Financial Officers Act of 1990, Pub. L. No. 101--576.

[^6]: Per Sec. 834(b)(1)(C) of the FY2015 NDAA, the Department of
    Defense may submit to OMB, in lieu of the Strategic Plan described
    in this memorandum, the defense-wide plan and cost savings report
    required under sections 2867(b)(2) and 2867(d), respectively, of the
    FY2012 NDAA. If submitting such plans and reports in lieu of the
    Strategic Plan, DOD shall ensure all information required by the
    Strategic Plan is included in the submitted plans and reports.

[^7]: Cloud Smart encourages agencies to consider vendor-based
    solutions, agency-hosted solutions, inter- and intra-agency shared
    services, multi-cloud, and hybrid solutions as appropriate for
    mission and security. <https://cloud.cio.gov>

[^8]: President's Management Agenda, "Shifting From Low-Value to
    High-Value Work":

    [[https://www.performance.gov/CAP/CAP\_goal\_6.html]](https://www.performance.gov/CAP/CAP_goal_6.html)

    Reducing Burden for Federal Agencies by Rescinding and Modifying OMB
    Memoranda:
    [[https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2017/M-17-26.pdf]](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2017/M-17-26.pdf)

[^9]: In accordance with OMB Circular A-130, [*Managing Information as a
    Strategic
    Resource*](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/circulars/A130/a130revised.pdf),
    CIOs should work with Senior Agency Officials for Privacy (SAOPs) to
    ensure compliance with applicable privacy requirements and to manage
    privacy risk when considering the consolidation of data centers that
    process personally identifiable information.

[^10]: M-16-19, page 9.

[^11]: See 42 USC 8287, et seq.

[^12]: See 42 USC 8256, 10 USC 2913, and 10 USC 2866

[^13]: [[https://www.whitehouse.gov/presidential-actions/executive-order-regarding-efficient-federal-operations/]](https://www.whitehouse.gov/presidential-actions/executive-order-regarding-efficient-federal-operations/)

[^14]: 44 USC 3601 note.b.2.G.ii.

[^15]: Agencies participating as a tenant in an inter-agency shared
    services provider data center are not required to report metric
    values to OMB. The provider will report this data to OMB.

[^16]: See FITARA Section 834(b)(1)(A)-(E).

[^17]: M-12-10. Implementing PortfolioStat.
    [[https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2012/m-12-10\_1.pdf]](https://www.whitehouse.gov/sites/whitehouse.gov/files/omb/memoranda/2012/m-12-10_1.pdf)
