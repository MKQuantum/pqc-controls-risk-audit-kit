# PQC Risk and Controls Matrix

_Control Description: not yet populated._

<table>
<thead>
<tr>
<th align="center">Risk Category</th>
<th align="center">Risk Name</th>
<th align="center">Risk Description</th>
<th align="center">Control Description</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="5" align="center" valign="middle"><b>Strategy and Governance</b></td>
<td valign="top">Lack of a Quantum Readiness Strategy</td>
<td valign="top">Without a defined strategy and roadmap for the threat from cryptographically relevant quantum computers (CRQCs), migration to PQC becomes reactive and uncoordinated. It is likely to cost more than a planned multi-year transition and can leave long-lived sensitive data and critical services exposed. (GSMA §1.1; Deloitte GV.RM-03)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Strategy not Aligned to Mission and Risk Appetite</td>
<td valign="top">PQC effort that isn’t tied to the organisation’s mission, critical services and risk appetite can concentrate investment on low-impact systems while the assets the business depends on most remain vulnerable. (Deloitte GV.OC-01, GV.RM-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Policies not Updated for Quantum Risk</td>
<td valign="top">Security, procurement and development policies that ignore PQC and crypto-agility, or aren’t revised as standards emerge, allow new quantum-vulnerable systems to keep entering the estate. (Deloitte GV.PO-01, GV.PO-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">No Executive Ownership or Board Visibility</td>
<td valign="top">Where quantum risk has no named executive owner and little board awareness, accountability is unclear and competing initiatives emerge. Decisions on funding, priorities and risk acceptance stall or are taken without the right authority. (GSMA §1.1; Deloitte GV.RR-01, GV.RM-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Fragmented Cryptographic Governance</td>
<td valign="top">Without a central, cross-functional body such as a Cryptography Centre of Excellence, responsibility for cryptographic policy, key and certificate management and migration is spread across teams. The result is inconsistent standards and duplicated or missed work. (GSMA §3.1; Deloitte GV.RM-05)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="5" align="center" valign="middle"><b>People and Knowledge Management</b></td>
<td valign="top">Insufficient quantum and cryptography skills.</td>
<td valign="top">A shortage of people who can interpret quantum threat guidance, assess cryptographic exposure and integrate PQC into systems, protocols and products delays assessment and migration. It also creates dependence on a few individuals or external parties. (GSMA §1.1, §5.2.3.1)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Low Awareness and Misjudged Scope of the Threat.</td>
<td valign="top">Architects, developers, procurement staff and business owners who don’t understand the quantum risk keep buying and building technology that relies on vulnerable cryptography. Misunderstanding which cryptography is affected also distorts investment. Public-key schemes such as RSA and elliptic-curve are fundamentally exposed, while symmetric cryptography and hash functions are affected far less. (Deloitte PR.AT, GV.RM-04; GSMA §5.2.3.2)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Outdated Threat and Timeline Assumptions.<br>(Scale AI approach)</td>
<td valign="top">If estimates of when a CRQC and capable threat actors will exist, and of the state of PQC standards, aren’t refreshed, priorities and migration timelines rest on stale assumptions. (GSMA §3.2, §4.1.1; Deloitte ID.RA-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Cryptography-related Roles Insufficiently Protected.<br>(Scale AI approach)</td>
<td valign="top">Staff and contractors who know the organisation’s cryptographic estate and its weaknesses may not be vetted or classified as sensitive, which raises insider and social-engineering exposure. (Deloitte GV.RR-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Lessons and Decisions not Captured.</td>
<td valign="top">If results from discovery, pilots, testing and risk decisions aren’t documented and fed back into the programme, improvements are missed and knowledge is lost when people move on. (Deloitte ID.IM, GV.OV)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="3" align="center" valign="middle"><b>Third-party and Supplier Management</b></td>
<td valign="top">Unknown Supplier Quantum Readiness.</td>
<td valign="top">Suppliers such as software, cloud, hardware, device and managed-service providers may have no PQC roadmap, or may embed CRQC-vulnerable cryptography in their products (e.g. HSMs, PKI, firmware). If they can’t migrate, the organisation depends on a fix it doesn’t control. (GSMA §5.2.3.4; Deloitte GV.SC-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">No Visibility of Third-party Cryptography.</td>
<td valign="top">Without cryptographic bills of materials (CBOMs), supplier attestations and a clear shared-responsibility model, the organisation can’t build a complete inventory across SaaS, cloud and outsourced services. (Deloitte GV.SC-02, GV.SC-05, Appendix A; GSMA §5.4)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Contracts silent on quantum risk</td>
<td valign="top">Agreements that don’t require readiness plans, timely reporting of cryptographic compromise or obligations that survive termination leave the organisation holding exposure and liability it cannot recover. (Deloitte GV.SC-05, GV.SC-06, GV.SC-10)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="4" align="center" valign="middle"><b>Risk management and compliance</b></td>
<td valign="top">Quantum risk not integrated into enterprise risk management</td>
<td valign="top">Treated as a technical issue outside enterprise risk management (ERM) and risk registers, quantum risk isn’t consistently prioritised, tracked or reported to leadership. (GSMA §1.1; Deloitte GV.RM-03)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Flawed prioritisation methodology</td>
<td valign="top">Methods that ignore data shelf life, system criticality, migration lead time and the business impact of a compromise can misrank assets. For example, a critical service whose data has little long-term sensitivity may be rated low risk because the threat seems distant, even though forged authentication or loss of availability would be severe. (GSMA §3.4, §4.1.2; Deloitte GV.RM-06)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Regulatory, contractual and sector-specific non-compliance</td>
<td valign="top">Obligations on quantum-safe security are emerging unevenly across jurisdictions and sectors. Existing data protection, cybersecurity, resilience and contractual duties already apply to the data at stake. Failing to track them risks fines, loss of customer trust and a weaker position after any breach. (GSMA §3.4; Deloitte GV.OC-03)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Residual risk not identified or monitored</td>
<td valign="top">After mitigation through acceptance, reduction or transfer, remaining risk is left unassessed and unmonitored, so the organisation overestimates how well it is protected. (GSMA §3.6)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="4" align="center" valign="middle"><b>Cryptographic and data asset governance</b></td>
<td valign="top">Incomplete cryptographic inventory</td>
<td valign="top">Without an accurate inventory of where cryptography is used (algorithms, protocols, keys, certificates, embedded and third-party), the organisation can’t scope, prioritise or plan migration, and may miss vulnerable assets entirely. (GSMA §3.3.2; Deloitte ID.AM-01, ID.AM-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Data longevity not assessed, leaving data exposed to “store now, decrypt later”</td>
<td valign="top">If the organisation doesn’t know how long each dataset must stay confidential, it can’t identify data captured today that a CRQC could decrypt later. That is a present risk for health records, insurance and financial contracts, intellectual property and personal data, and it also leaves no basis for deciding what to protect first. Data already harvested can’t be re-protected. (GSMA §3.2.1, §3.3.1, §5.5; Deloitte ID.AM-07)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Inventory becomes outdated</td>
<td valign="top">Manual, point-in-time inventories drift as systems change, so decisions rest on a stale picture. Continuous discovery and CBOMs are needed to keep it current. (GSMA §3.2.4; Deloitte ID.AM-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Data assumed destroyed remains at risk</td>
<td valign="top">Data “erased” by destroying keys protected with quantum-vulnerable cryptography may still be recoverable if encrypted copies were retained or harvested. (Deloitte PR.DS)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="4" align="center" valign="middle"><b>Enterprise architecture and cryptographic agility</b></td>
<td valign="top">Lack of cryptographic agility</td>
<td valign="top">Cryptography that is hard-coded or embedded, and can’t be replaced quickly and cheaply, turns every future algorithm or protocol change into a major, disruptive migration. (GSMA §2.2; Deloitte PR.PS-06)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Accumulated cryptographic debt in legacy assets</td>
<td valign="top">Legacy platforms, firmware and hardware (e.g. embedded, medical or industrial equipment, long-lived core systems) with rigid or absent cryptographic protection can cost more to keep running than to modernise. Where PQC isn’t technically feasible, full replacement may be the only option. (Deloitte GV.OC-04, GV.RR-03, PR.PS-03)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Protection applied at too few layers</td>
<td valign="top">Relying only on quantum-resistant network protection (e.g. a PQC-enabled VPN) leaves data, database and application layers exposed, with no defence in depth. (Deloitte PR.DS, PR.IR)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Poorly governed hybrid and fallback modes</td>
<td valign="top">Hybrid key exchange and fallback to classical cryptography support continuity and compatibility. Left unmanaged, they can leave assets exposed or allow downgrades, and may be unsuitable for assets needing high confidentiality or integrity. (GSMA §3.5, Annex B; Deloitte ID.RA-06)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="6" align="center" valign="middle"><b>Migration programme and solution delivery</b></td>
<td valign="top">Underestimated migration lead time</td>
<td valign="top">Migration across a complex estate can take many years (GSMA cites industry experience of 5–20 years, depending on size and complexity), plus long design, test and acceptance cycles for products and services. If lead time is underestimated, assets can become vulnerable before they are protected. (GSMA §3.2.2, §4.1, §4.2.3)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Inadequate funding and resourcing</td>
<td valign="top">If migration costs, including replacing assets that cannot support PQC, aren’t built into multi-year budgets, the programme stalls midway or defaults to a costlier reactive response. (Deloitte GV.RR-03, GV.OC-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Uncoordinated delivery and no progress measurement</td>
<td valign="top">Isolated pilots that aren’t aligned to initiatives such as Zero Trust or cloud migration, and the absence of maturity measures, leave management unable to track progress or evidence readiness to boards and regulators. (Deloitte GV.RM-07, GV.OV, CSF Tiers)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Immature or flawed PQC implementation</td>
<td valign="top">PQC standards and protocol integrations are still maturing, so adopting too early or without a selection policy can lock in choices that later need rework. New code, messages and processing can also introduce implementation flaws and side-channel weaknesses, potentially raising exposure to classical attacks while lowering quantum exposure. (GSMA Annex B; Deloitte GV.RM-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Insufficient interoperability and performance testing</td>
<td valign="top">Untested PQC changes can break connections with partners, suppliers and legacy systems or degrade performance, especially without representative test environments or independent validation. (GSMA §4.2.3, §5.2.3.3; Deloitte GV.SC-02, PR.IR)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Business disruption from cryptographic migration</td>
<td valign="top">Changing cryptography can break dependent business processes, data flows and third-party connections (e.g. payments, claims processing, patient or customer services), causing outages or failed transactions if not planned with business owners. (Deloitte GV.OC-04, GV.RM-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="4" align="center" valign="middle"><b>Key management, PKI and identity</b></td>
<td valign="top">Compromise of trust infrastructure (PKI, certificates and key exchange)</td>
<td valign="top">Once a CRQC exists, attackers could break or forge certificates, signatures and key exchanges (PKI, TLS, VPN/IPsec). That would let them impersonate users, devices and services, intercept traffic or forge signed software and firmware updates. Compromise of central identity or management infrastructure could give control of many systems at once. (GSMA §3.2.2, §4.2.3, §5.2.3.2; Deloitte ID.RA-09)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Quantum-vulnerable authenticators and credentials</td>
<td valign="top">Credentials and authentication mechanisms for users, services and hardware that rely on vulnerable cryptography could be spoofed, giving unauthorised access to systems and data. (GSMA §5.2.3.2; Deloitte PR.AA)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Weak key and certificate lifecycle management</td>
<td valign="top">Manual or fragmented handling of keys, certificates and pre-shared keys, including secure out-of-band distribution, increases errors, expiry outages and key compromise as cryptographic complexity grows. (GSMA Annex B; Deloitte PR.PS-01)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Key custody in hardware that can’t be upgraded</td>
<td valign="top">HSMs, key management systems and other hardware that stores or protects keys may rely on quantum-vulnerable algorithms or be unable to support PQC. The organisation’s most sensitive keys then have no practical upgrade path, and replacement can be slow and costly. (GSMA §3.2.4; Deloitte ID.AM-01, GV.SC-04, PR.PS-03)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="5" align="center" valign="middle"><b>Security monitoring and incident response</b></td>
<td valign="top">Limited indicators of quantum-enabled compromise</td>
<td valign="top">Compromise by a CRQC may leave few detectable indicators, so exposure can go unnoticed without quantum-specific threat intelligence and active monitoring of cryptographic posture. (Deloitte ID.RA-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">No continuous cryptographic monitoring</td>
<td valign="top">Monitoring that doesn’t span all layers and third-party systems lets deprecated algorithms, unauthorised cryptography and unlogged changes to cryptographic assets go unseen. (Deloitte DE.CM, PR.PS-04, PR.PS-05)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Hybrid attack chains assessed in isolation</td>
<td valign="top">A quantum-enabled exploit combined with classical weaknesses (e.g. a forged software signature leading an administrator to install malware) may be missed if each risk is assessed separately. (GSMA §3.2.3)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Incident response not prepared for cryptographic compromise</td>
<td valign="top">Incident response plans, playbooks and exercises that don’t cover CRQC-based compromise or failed migrations, or that leave out suppliers running cryptographic services, make the organisation slow to detect, escalate and contain a cryptographic incident. (Deloitte GV.SC-07, GV.SC-08)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">No plan for exposure of harvested data</td>
<td valign="top">If sensitive data has already been harvested, the absence of a response and recovery strategy for its eventual exposure leaves the organisation unprepared for legal, regulatory, customer and reputational consequences. (GSMA §5.5, §3.4)</td>
<td valign="top"></td>
</tr>
<tr>
<td rowspan="4" align="center" valign="middle"><b>IT operations, change and resilience</b></td>
<td valign="top">Cryptographic impact missing from change control</td>
<td valign="top">New systems, upgrades and procurements approved without considering their cryptography add vulnerable algorithms and deepen cryptographic debt. (Deloitte ID.RA-07, GV.PO-02)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Regression to vulnerable cryptography</td>
<td valign="top">Patches, configuration changes or fallback behaviour can quietly revert migrated assets to quantum-vulnerable algorithms, undoing earlier progress. (Deloitte ID.RA-06, ID.RA-07)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Performance and capacity degradation</td>
<td valign="top">PQC changes message sizes, message sequences and processing load. On constrained devices (e.g. IoT, smart cards, medical or industrial equipment) and high-volume systems (e.g. payment, trading, messaging or network infrastructure), this can degrade latency, capacity or availability. (GSMA Annex B; Deloitte PR.IR, GV.RM-04)</td>
<td valign="top"></td>
</tr>
<tr>
<td valign="top">Continuity and recovery plans exclude cryptographic failure</td>
<td valign="top">Business continuity and disaster recovery plans that don’t consider a CRQC-driven loss of availability or integrity, or a failed cryptographic migration, can prolong outages of critical services. Suppliers responsible for cryptographic services may also be missing from recovery arrangements. (Deloitte GV.SC-09, ID.RA-04, ID.RA-06; GSMA §4.2.3)</td>
<td valign="top"></td>
</tr>
</tbody>
</table>

## Source key

Bracketed references at the end of each risk description point to the source material:

- **GSMA** – [Guidelines for Quantum Risk Management for Telco, v1.0](https://www.gsma.com/get-involved/working-groups/wp-content/uploads/2023/09/Guidelines-for-Quantum-Risk-Management-for-Telco-v1.0.pdf). Section numbers (for example §3.2.1) refer to this document.
- **Deloitte** – [Cryptographic Resilience Community Profile](https://www.deloitte.com/content/dam/assets-shared/docs/services/consulting/2026/deloitte-cryptographic-resilience-community.pdf). Identifiers such as GV.RM-03 are NIST CSF 2.0 subcategories.
