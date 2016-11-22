---
layout: col-lg-12
title: Scenario C
---

# Storage Coordination

DSOs are experiencing a growing number of challenges in the grid due to fluctuations in private consumption as well as variable power injections
from local intermittent Renewable Energy Sources (RES). In northern European grids such as in the Island of Fur (Denmark) consumption fluctuations
are likely to be related to large electric residential and commercial heating systems (heat pumps), industrial loads and peaks due to electric cooking. On the other hand, production fluctuations are mostly related to
sudden variations of injected power by installed PV and wind turbines.

While the current distribution grid configuration is sufficiently strong to bear the current status, growth in RES
penetration, electric mobility and heating (stimulated because of the de-carbonization policies), may create
problems in the longer term, thus resulting in significant needs for investments in strengthening the distribution
grid. Moreover, even in case grid reinforcements needs would not became a reality, lack of time correlation
between loads and generation patterns would anyways result in a reduced potential for self-consumption, and thus
on lower decarbonisation effects. Therefore, the problem will just be shifted from the need to improve the local
distribution grid to the need of investing more on interconnections at medium and high voltage level and on
deployment of more instantaneous, controllable plants.

Installation of storage system at different levels in the grid is considered by the local DSO as a potentially
interesting solution to help improving self-consumption, increase grid flexibility and deferring grid reinforcement
efforts. The Danish island of Fur (Figure 12) is small island in the municipality of Skive, which host a small
community of users which have been involved already in several Danish and EU R&D projects including the
GreenCom18 project, coordinated by partners ISMB and participated by partners FIT and EMIDT.

Because of the small scale and participative community, Fur is the ideal place for testing and experimenting with
prototypal systems and evaluate user acceptance of low-TRL technical solutions. Five households in the island,
which were already previously owning PV systems, have already been instrumented in 2015 by EMIDT with
Fronius Symo three-phases hybrid inverters and small-scale storage Li-Ion batteries (capacity: 4.5 kWh). While
these systems are monitored via the GreenCom cloud-based ICT infrastructure, they are self-controlled autonomous
systems, programmed to maximize self-consumption at individual level without considering external signals.
Given the good acceptance and effect on prosumers’ awareness and behaviour, this is widely considered a
promising case, but in order to secure future take-up of storage solutions, a number of gaps still need to be filled
mostly related to: enabling such systems to be controlled externally to achieve adaptation to current grid conditions;
achieving coordinated behaviour e.g. to exploit synergies arising between houses connected to the same radial
and/or with storage at substation level; enabling users to access and control their own storage data without relying
on external cloud services; devising evaluation techniques to properly evaluate and dimension storage investments
given specific user settings or load patterns.

In order to allow EU utilities such as EMIDT and their customers to pursue more informed investments in storage,
while increasing RES self-consumption and avoiding heavy investments in strengthening the gird, S4G will study
methodologies for planning, evaluating and controlling distributed storage installations at user premises and at
substation level in a coordinated fashion. Figure below depicts the reference architecture of the "Storage Coordination"
scenario and test site, covering a number of control and evaluation cases. The scenario involves the five residential

![Storage Coordination Scenario](../img/storage-coordination-scenario.png)

Fur houses already provided with storage. Such houses feature various sizes of PV installations (ranging from 5 to
12 kW sizes) and are all connected to the same distribution radial. Such houses will be provided with an USM,
integrated with the residential ESS and a dedicated local GUI. Similarly, a substation-level ESS will be deployed
on-site. Overall, all available control capabilities will be interconnected with the DSO SCADA system, thus
enabling cooperative behaviours in the storage systems.

These settings are quite representative of typical residential areas in the suburbs. For this reason this will represent
a sensible test site to evaluate a number of control and planning cases where storage is needed as a buffer for
fluctuations. S4G will provide DSOs with tools, control and planning methodologies to perform technical and
economic comparative evaluations.

Logically, the system will be evaluated by allowing informed strategic decisions among alternative investment
options such in the following:

* Option 1 – traditional grid strengthening (baseline for benchmark). Starting from the most traditional
strategies, in most cases DSOs will initially consider investments in reinforcement of the grid by deploying
larger transformer stations, more radials and thicker cables. This is considered the most conservative, well-
known way of ensuring grid stability and security. The cost of such solution may not be sustainable in several
cases, as the main labour costs (related to digging) significantly exceeds the cost of material itself. This solution
would not have major effects on self-consumptions.

* Option 2 –private households investing in residential storage. A first interesting case involving storage
should consider investments by private households in renewable energy sources (RES) enriched with storage.
These investments are interesting for the private households mainly due to the economic advantage and a
reasonable return of investment. In terms of grid stabilization, the effect of combined RES and storage is
expected to be significant and cost-effective for the DSO. With current technologies, however, the DSOs would
not have any form of control over the flexibility potentially offered by such systems. In situations where pricing
schemas are not designed keeping existence of storage in mind, the probability of systems discharging to the
neighboring systems which is charging is not negligible, and this would counteract grid stabilization efforts,
beyond being a pure waste of energy due to efficiency loss. In order to foster use of storage in such segment,
the S4G DSF should be devised to increase know-how of end-users about performance and control possibilities
for residential users interested in investing in energy storage, giving predictable and reliable figures about the
expected technical and economic performance.

* Option 3 – DSO investing in large storage systems at substation level. This option will consider a situation
where DSOs is interested in installing larger energy storages on radials to act as a collective buffer for
production and consumption in a specific neighbourhood. To achieve stabilization in the grid the main
challenges in this case will be: selection of the most suitable storage technologies; correct dimensioning; most
suitable positioning in the grid; selection of the most suitable control configuration; prediction of the expected
performance, lifetime and operational costs (OPEX) of the deployed solution. In order to foster use of storage in
this segment, the S4G DSF should be devised to increase know-how of professional users about performance
and control, giving predictable and reliable figures about the expected technical and economic performance. In
such case, also the potential for using such systems to provide ancillary services could be relevant.
* Option 4 – Deploying and enforcing distributed controllable storage at various levels. In most general
cases, residential and substation-level storage may be deployed jointly to achieve more flexibility. On the
business side, this case would be more complex, as incentives and pricing schemas should be carefully designed
to ensure relevance of investments for house owners and for other relevant organizations (e.g. aggregatos,
energy service companies, etc.) to make and eventual pay for the incentives. Most likely the incentive will be
emphasizing the house owner to install controllable production, storage or consumption equipment to ensure
stabilization within the grid. To achieve stabilization this way, a system aggregator would require access to
storages control capabilities. While growing in complexity, this case would open interesting perspectives for
aggregators ensuring stabilization in a radial by controlling individual storage systems as well as groups. This
will require a lot of controls, monitoring to ensure the energy flow are not travelling from one battery to another.
This option will be the most technically relevant for evaluation, as it will require the exploitation of the overall
control capabilities developed by S4G.

For completeness, S4G will also exercise the DSF in grid segments outside Fur e.g. to analyse the potential of
storage for upgrading or stabilizing the grid in a public setting such as a city centre or near larger renewable plants
like wind turbine parks or PV parks.

In order to cope with this challenging scenario, S4G will study methodologies for planning, evaluating in advance
and controlling storage installations communicating and cooperating with storage systems by means of open,
standardized interfaces. S4G will support the design and sizing of local storage system and their impact on the cost, manageability and environmental sustainability of the storage process, both from the private users and from the local DSO point of view. Such analysis will result in the definition and pre-design of control interfaces required to support optimal coordinated charging also taking into account user needs and grid signals from the AMI. This will allow deployed storage systems to implement an optimal control strategy for jointly controlling the charging
process and the storage, to benefit the end-user and minimize impact on the grid. In the commercial case, the S4G
DSF will help optimal sizing and design of large-scale storage to stabilize the grid and help the DSO. At this
purpose, the S4G DSF will provide key information about the costs and benefits of such installations, as well as
suggesting the best control strategy for such system once the storage enters the operational phase.

Overall, analysis, development and evaluation activities for this scenario will be deployed in the Fur test site and
led by partner EMIDT.
