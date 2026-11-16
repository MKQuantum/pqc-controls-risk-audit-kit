# PQC Risk and Controls Matrix

_Control Description: populated from Risk Mapping.docx._

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
<td align="center" rowspan="5" valign="middle"><b>Strategy and Governance</b></td>
<td valign="top">Lack of a Quantum Readiness Strategy</td>
<td valign="top">Without a defined strategy and roadmap for the threat from cryptographically relevant quantum computers (CRQCs), migration to PQC becomes reactive and uncoordinated. It is likely to cost more than a planned multi-year transition and can leave long-lived sensitive data and critical services exposed. (GSMA §1.1; Deloitte GV.RM-03)</td>
<td valign="top">Establish and maintain an enterprise-wide Quantum Readiness Strategy and multi-year PQC migration roadmap. The strategy should define scope, objectives, milestones, dependencies, funding requirements, accountable owners and target completion dates. It should include cryptographic discovery, risk assessment, prioritised remediation, crypto-agility and ongoing monitoring, with periodic reviews to reflect changes in quantum capabilities, standards and organisational technology.</td>
</tr>
<tr>
<td valign="top">Strategy not Aligned to Mission and Risk Appetite</td>
<td valign="top">PQC effort that isn’t tied to the organisation’s mission, critical services and risk appetite can concentrate investment on low-impact systems while the assets the business depends on most remain vulnerable. (Deloitte GV.OC-01, GV.RM-02)</td>
<td valign="top">Define quantum risk management objectives in alignment with organisational mission, business priorities, critical services and established risk appetite. Use business impact, data sensitivity, confidentiality requirements, system criticality and operational dependencies to guide investment and migration priorities. Document risk tolerance and establish escalation and approval thresholds for exceptions and residual risks.</td>
</tr>
<tr>
<td valign="top">Policies not Updated for Quantum Risk</td>
<td valign="top">Security, procurement and development policies that ignore PQC and crypto-agility, or aren’t revised as standards emerge, allow new quantum-vulnerable systems to keep entering the estate. (Deloitte GV.PO-01, GV.PO-02)</td>
<td valign="top">Review and update information security, cryptographic, enterprise architecture, software development, procurement and technology lifecycle policies to explicitly address quantum risk. Define approved cryptographic algorithms, PQC adoption requirements, crypto-agility standards, algorithm deprecation criteria and security review requirements. Establish a formal policy review cycle to incorporate evolving standards and regulatory guidance.</td>
</tr>
<tr>
<td valign="top">No Executive Ownership or Board Visibility</td>
<td valign="top">Where quantum risk has no named executive owner and little board awareness, accountability is unclear and competing initiatives emerge. Decisions on funding, priorities and risk acceptance stall or are taken without the right authority. (GSMA §1.1; Deloitte GV.RR-01, GV.RM-04)</td>
<td valign="top">Assign a designated executive accountable for quantum readiness and establish clear roles and responsibilities across technology, cybersecurity, enterprise risk, procurement and business functions. Provide regular reporting to executive leadership and the board on quantum risk exposure, migration progress, programme funding, significant dependencies, exceptions and residual risk.</td>
</tr>
<tr>
<td valign="top">Fragmented Cryptographic Governance</td>
<td valign="top">Without a central, cross-functional body such as a Cryptography Centre of Excellence, responsibility for cryptographic policy, key and certificate management and migration is spread across teams. The result is inconsistent standards and duplicated or missed work. (GSMA §3.1; Deloitte GV.RM-05)</td>
<td valign="top">Establish a Cryptography Centre of Excellence (CCoE), or equivalent cross-functional governance structure, to coordinate cryptographic risk management and PQC migration. Define central ownership for cryptographic standards, architecture, inventory, key and certificate management, supplier requirements and migration oversight. Establish consistent processes, reporting, technical guidance and decision-making authority across the organisation.</td>
</tr>
<tr>
<td align="center" rowspan="5" valign="middle"><b>People and Knowledge Management</b></td>
<td valign="top">Insufficient quantum and cryptography skills.</td>
<td valign="top">A shortage of people who can interpret quantum threat guidance, assess cryptographic exposure and integrate PQC into systems, protocols and products delays assessment and migration. It also creates dependence on a few individuals or external parties. (GSMA §1.1, §5.2.3.1)</td>
<td valign="top">Establish a quantum readiness training and capability development programme for security architects, cryptographers, developers, infrastructure teams, risk professionals and procurement personnel. Define required competencies, provide role-specific training and practical exercises, and maintain access to specialist expertise. Periodically assess skills gaps and address them through recruitment, professional development, industry collaboration or specialist third-party support.</td>
</tr>
<tr>
<td valign="top">Low Awareness and Misjudged Scope of the Threat.</td>
<td valign="top">Architects, developers, procurement staff and business owners who don’t understand the quantum risk keep buying and building technology that relies on vulnerable cryptography. Misunderstanding which cryptography is affected also distorts investment. Public-key schemes such as RSA and elliptic-curve are fundamentally exposed, while symmetric cryptography and hash functions are affected far less. (Deloitte PR.AT, GV.RM-04; GSMA §5.2.3.2)</td>
<td valign="top">Implement an organisation-wide quantum risk awareness programme explaining the capabilities and limitations of quantum computing, the implications for current cryptography and the distinction between vulnerable public-key algorithms and the comparatively less affected symmetric cryptography and hash functions. Incorporate quantum risk into security awareness, architecture reviews, software development training and procurement processes.</td>
</tr>
<tr>
<td valign="top">Outdated Threat and Timeline Assumptions.<br/>(Scale AI approach)</td>
<td valign="top">If estimates of when a CRQC and capable threat actors will exist, and of the state of PQC standards, aren’t refreshed, priorities and migration timelines rest on stale assumptions. (GSMA §3.2, §4.1.1; Deloitte ID.RA-02)</td>
<td valign="top">Establish a process for continuously monitoring developments in quantum computing, cryptanalysis, PQC standards, threat intelligence and regulatory guidance. Assign responsibility for evaluating new information and periodically reassessing assumptions about CRQC timelines, adversary capabilities, harvest-now-decrypt-later threats and algorithm security. Update the quantum risk assessment, migration priorities and roadmap when material developments occur.</td>
</tr>
<tr>
<td valign="top">Cryptography-related Roles Insufficiently Protected.<br/>(Scale AI approach)</td>
<td valign="top">Staff and contractors who know the organisation’s cryptographic estate and its weaknesses may not be vetted or classified as sensitive, which raises insider and social-engineering exposure. (Deloitte GV.RR-04)</td>
<td valign="top">Identify personnel and contractors with privileged access to cryptographic infrastructure, keys, certificates, cryptographic inventories and sensitive vulnerability information. Apply appropriate personnel screening, role-based access controls, least-privilege principles, segregation of duties, privileged activity monitoring and periodic access reviews. Include cryptography-related responsibilities in personnel security and contractor offboarding procedures.</td>
</tr>
<tr>
<td valign="top">Lessons and Decisions not Captured.</td>
<td valign="top">If results from discovery, pilots, testing and risk decisions aren’t documented and fed back into the programme, improvements are missed and knowledge is lost when people move on. (Deloitte ID.IM, GV.OV)</td>
<td valign="top">Establish a central repository for quantum risk assessments, cryptographic discovery results, architecture decisions, migration plans, pilot outcomes, testing evidence, exceptions and risk acceptance decisions. Define documentation ownership, version control and review requirements. Conduct post-implementation reviews and incorporate lessons learned into programme standards, policies, training and future migration activities.</td>
</tr>
<tr>
<td align="center" rowspan="3" valign="middle"><b>Third-party and Supplier Management</b></td>
<td valign="top">Unknown Supplier Quantum Readiness.</td>
<td valign="top">Suppliers such as software, cloud, hardware, device and managed-service providers may have no PQC roadmap, or may embed CRQC-vulnerable cryptography in their products (e.g. HSMs, PKI, firmware). If they can’t migrate, the organisation depends on a fix it doesn’t control. (GSMA §5.2.3.4; Deloitte GV.SC-04)</td>
<td valign="top">Establish a supplier quantum readiness assessment process covering technology, software, hardware, cloud, telecommunications, managed services and cryptographic service providers. Require suppliers to disclose their PQC readiness, cryptographic dependencies, migration roadmaps, product lifecycle commitments and support for crypto-agility. Incorporate quantum readiness into supplier onboarding, periodic assessments, risk classification and ongoing performance reviews.</td>
</tr>
<tr>
<td valign="top">No Visibility of Third-party Cryptography.</td>
<td valign="top">Without cryptographic bills of materials (CBOMs), supplier attestations and a clear shared-responsibility model, the organisation can’t build a complete inventory across SaaS, cloud and outsourced services. (Deloitte GV.SC-02, GV.SC-05, Appendix A; GSMA §5.4)</td>
<td valign="top">Require suppliers and service providers to provide Cryptographic Bills of Materials (CBOMs), cryptographic inventories or equivalent evidence identifying algorithms, protocols, libraries, key management dependencies and relevant cryptographic components. Maintain visibility of cryptography used in outsourced services, SaaS, cloud platforms and embedded products. Define shared-responsibility arrangements and integrate supplier information into the organisation's central cryptographic inventory.</td>
</tr>
<tr>
<td valign="top">Contracts silent on quantum risk</td>
<td valign="top">Agreements that don’t require readiness plans, timely reporting of cryptographic compromise or obligations that survive termination leave the organisation holding exposure and liability it cannot recover. (Deloitte GV.SC-05, GV.SC-06, GV.SC-10)</td>
<td valign="top">Incorporate quantum readiness and cryptographic resilience requirements into supplier contracts, procurement agreements and service-level agreements. Include obligations for cryptographic inventory disclosure, PQC migration planning, support for approved standards, vulnerability notification, security incident reporting, interoperability testing and ongoing maintenance. Define accountability, remediation timelines, audit rights, business continuity obligations and appropriate data protection and transition requirements upon contract termination.</td>
</tr>
<tr>
<td align="center" rowspan="4" valign="middle"><b>Risk management and compliance</b></td>
<td valign="top">Quantum risk not integrated into enterprise risk management</td>
<td valign="top">Treated as a technical issue outside enterprise risk management (ERM) and risk registers, quantum risk isn’t consistently prioritised, tracked or reported to leadership. (GSMA §1.1; Deloitte GV.RM-03)</td>
<td valign="top">Incorporate quantum-related cryptographic risks into the enterprise risk management framework, cybersecurity risk register and established risk assessment processes. Define consistent risk identification, assessment, scoring, treatment, escalation and reporting procedures. Assign accountable risk owners and ensure quantum risk exposure is periodically reviewed alongside other strategic, operational, technology and cybersecurity risks.</td>
</tr>
<tr>
<td valign="top">Flawed prioritisation methodology</td>
<td valign="top">Methods that ignore data shelf life, system criticality, migration lead time and the business impact of a compromise can misrank assets. For example, a critical service whose data has little long-term sensitivity may be rated low risk because the threat seems distant, even though forged authentication or loss of availability would be severe. (GSMA §3.4, §4.1.2; Deloitte GV.RM-06)</td>
<td valign="top">Implement a documented, risk-based prioritisation methodology that considers data sensitivity, confidentiality shelf life, system criticality, cryptographic vulnerability, exposure, migration complexity, implementation lead time and business impact. Assess both store-now-decrypt-later threats and future quantum-enabled attacks against confidentiality, integrity, authenticity and availability. Use the results to rank assets, determine treatment urgency and allocate migration resources proportionately.</td>
</tr>
<tr>
<td valign="top">Regulatory, contractual and sector-specific non-compliance</td>
<td valign="top">Obligations on quantum-safe security are emerging unevenly across jurisdictions and sectors. Existing data protection, cybersecurity, resilience and contractual duties already apply to the data at stake. Failing to track them risks fines, loss of customer trust and a weaker position after any breach. (GSMA §3.4; Deloitte GV.OC-03)</td>
<td valign="top">Establish a process to identify, monitor and assess applicable legal, regulatory, industry, privacy, cybersecurity and contractual obligations relevant to cryptographic resilience and PQC migration. Map applicable requirements to internal policies, technical standards and control objectives. Periodically review compliance, retain supporting evidence and update requirements as relevant standards, regulatory expectations and contractual obligations evolve.</td>
</tr>
<tr>
<td valign="top">Residual risk not identified or monitored</td>
<td valign="top">After mitigation through acceptance, reduction or transfer, remaining risk is left unassessed and unmonitored, so the organisation overestimates how well it is protected. (GSMA §3.6)</td>
<td valign="top">Require formal reassessment and documentation of residual quantum risk following each mitigation, acceptance, transfer or avoidance decision. Assign an accountable risk owner, document the rationale and approval authority, and define monitoring requirements, review dates, risk thresholds and escalation triggers. Reassess accepted residual risks when threat intelligence, technology, standards or business circumstances materially change.</td>
</tr>
<tr>
<td align="center" rowspan="4" valign="middle"><b>Cryptographic and data asset governance</b></td>
<td valign="top">Incomplete cryptographic inventory</td>
<td valign="top">Without an accurate inventory of where cryptography is used (algorithms, protocols, keys, certificates, embedded and third-party), the organisation can’t scope, prioritise or plan migration, and may miss vulnerable assets entirely. (GSMA §3.3.2; Deloitte ID.AM-01, ID.AM-02)</td>
<td valign="top">Establish and maintain a central cryptographic inventory covering enterprise applications, infrastructure, networks, databases, endpoints, cloud services, embedded systems and third-party products. Record cryptographic algorithms, protocols, libraries, keys, certificates, cryptographic dependencies, asset owners, locations, business criticality and lifecycle information. Use automated discovery tools where feasible and supplement them with manual assessments, supplier CBOMs and architecture reviews.</td>
</tr>
<tr>
<td valign="top">Data longevity not assessed, leaving data exposed to “store now, decrypt later”</td>
<td valign="top">If the organisation doesn’t know how long each dataset must stay confidential, it can’t identify data captured today that a CRQC could decrypt later. That is a present risk for health records, insurance and financial contracts, intellectual property and personal data, and it also leaves no basis for deciding what to protect first. Data already harvested can’t be re-protected. (GSMA §3.2.1, §3.3.1, §5.5; Deloitte ID.AM-07)</td>
<td valign="top">Establish a data classification and retention assessment process that identifies sensitive information requiring confidentiality beyond the anticipated availability of a CRQC. Record data sensitivity, confidentiality shelf life, retention periods, storage locations, encryption mechanisms and associated cryptographic dependencies. Prioritise long-lived sensitive information for migration to quantum-resistant protection, considering both current interception risks and future decryption capabilities.</td>
</tr>
<tr>
<td valign="top">Inventory becomes outdated</td>
<td valign="top">Manual, point-in-time inventories drift as systems change, so decisions rest on a stale picture. Continuous discovery and CBOMs are needed to keep it current. (GSMA §3.2.4; Deloitte ID.AM-02)</td>
<td valign="top">Implement continuous or periodically scheduled cryptographic discovery and inventory reconciliation. Integrate discovery with configuration management, asset management, software composition analysis, change management and procurement processes. Establish automated detection of new, modified, deprecated or unauthorised cryptographic implementations and require asset owners to validate inventory accuracy at defined intervals.</td>
</tr>
<tr>
<td valign="top">Data assumed destroyed remains at risk</td>
<td valign="top">Data “erased” by destroying keys protected with quantum-vulnerable cryptography may still be recoverable if encrypted copies were retained or harvested. (Deloitte PR.DS)</td>
<td valign="top">Establish secure data sanitisation and cryptographic erasure procedures that verify the destruction of all relevant encryption keys, key backups, replicas and recovery copies. Assess whether encrypted data copies may have been retained, replicated or previously exfiltrated and whether the underlying encryption is quantum-vulnerable. Do not treat key destruction alone as sufficient evidence of irreversible data destruction where historical encrypted copies may remain accessible.</td>
</tr>
<tr>
<td align="center" rowspan="4" valign="middle"><b>Enterprise architecture and cryptographic agility</b></td>
<td valign="top">Lack of cryptographic agility</td>
<td valign="top">Cryptography that is hard-coded or embedded, and can’t be replaced quickly and cheaply, turns every future algorithm or protocol change into a major, disruptive migration. (GSMA §2.2; Deloitte PR.PS-06)</td>
<td valign="top">Establish enterprise cryptographic architecture standards that enable cryptographic algorithms, protocols, libraries and key management mechanisms to be replaced or upgraded without extensive application or infrastructure redesign. Use modular cryptographic components, abstraction layers, configurable algorithm selection and centralised cryptographic services where appropriate. Incorporate crypto-agility requirements into architecture reviews, software development standards, procurement and technology lifecycle management.</td>
</tr>
<tr>
<td valign="top">Accumulated cryptographic debt in legacy assets</td>
<td valign="top">Legacy platforms, firmware and hardware (e.g. embedded, medical or industrial equipment, long-lived core systems) with rigid or absent cryptographic protection can cost more to keep running than to modernise. Where PQC isn’t technically feasible, full replacement may be the only option. (Deloitte GV.OC-04, GV.RR-03, PR.PS-03)</td>
<td valign="top">Establish a cryptographic debt assessment and remediation programme to identify legacy systems, hardware, firmware, applications and embedded devices that cannot readily support PQC. Evaluate upgrade feasibility, vendor support, operational dependencies, business criticality and replacement costs. Define remediation plans that include upgrades, compensating controls, isolation, replacement or retirement, with documented exceptions and risk acceptance for assets that cannot immediately migrate.</td>
</tr>
<tr>
<td valign="top">Protection applied at too few layers</td>
<td valign="top">Relying only on quantum-resistant network protection (e.g. a PQC-enabled VPN) leaves data, database and application layers exposed, with no defence in depth. (Deloitte PR.DS, PR.IR)</td>
<td valign="top">Implement a defence-in-depth strategy that applies quantum-resistant cryptographic protection across relevant network, transport, application, database, storage, endpoint and data protection layers. Assess cryptographic exposure across the complete data lifecycle, including data in transit, at rest and in use where applicable. Validate that protection at one layer does not create an assumption that other cryptographic dependencies are adequately secured.</td>
</tr>
<tr>
<td valign="top">Poorly governed hybrid and fallback modes</td>
<td valign="top">Hybrid key exchange and fallback to classical cryptography support continuity and compatibility. Left unmanaged, they can leave assets exposed or allow downgrades, and may be unsuitable for assets needing high confidentiality or integrity. (GSMA §3.5, Annex B; Deloitte ID.RA-06)</td>
<td valign="top">Establish technical standards and governance requirements for hybrid classical/PQC cryptographic implementations and fallback mechanisms. Specify approved algorithms, protocol configurations, downgrade protections, negotiation requirements, key handling and deprecation criteria. Test hybrid configurations for interoperability and security, monitor fallback activity and require formal approval, documented justification and time-bound remediation for any continued reliance on quantum-vulnerable algorithms.</td>
</tr>
<tr>
<td align="center" rowspan="6" valign="middle"><b>Migration programme and solution delivery</b></td>
<td valign="top">Underestimated migration lead time</td>
<td valign="top">Migration across a complex estate can take many years (GSMA cites industry experience of 5–20 years, depending on size and complexity), plus long design, test and acceptance cycles for products and services. If lead time is underestimated, assets can become vulnerable before they are protected. (GSMA §3.2.2, §4.1, §4.2.3)</td>
<td valign="top">Develop a phased, risk-based PQC migration roadmap informed by the cryptographic inventory, business dependencies, system criticality, supplier readiness and technical complexity. Include discovery, architecture, procurement, development, testing, deployment and decommissioning activities, with realistic lead times, dependencies and milestones. Review migration assumptions periodically and accelerate remediation for assets with high confidentiality shelf life or critical operational dependencies.</td>
</tr>
<tr>
<td valign="top">Inadequate funding and resourcing</td>
<td valign="top">If migration costs, including replacing assets that cannot support PQC, aren’t built into multi-year budgets, the programme stalls midway or defaults to a costlier reactive response. (Deloitte GV.RR-03, GV.OC-04)</td>
<td valign="top">Establish a multi-year financial and resource plan for quantum readiness and PQC migration. Include funding for cryptographic discovery, specialist personnel, technology upgrades, vendor engagement, testing, hardware replacement, software remediation, operational support and legacy system retirement. Align programme funding to assessed risk and migration priorities and periodically review expenditure, resource capacity and forecast costs against the approved roadmap.</td>
</tr>
<tr>
<td valign="top">Uncoordinated delivery and no progress measurement</td>
<td valign="top">Isolated pilots that aren’t aligned to initiatives such as Zero Trust or cloud migration, and the absence of maturity measures, leave management unable to track progress or evidence readiness to boards and regulators. (Deloitte GV.RM-07, GV.OV, CSF Tiers)</td>
<td valign="top">Establish a centrally coordinated PQC migration programme with defined workstreams, accountable owners, milestones, dependencies and governance oversight. Integrate migration activities with relevant enterprise initiatives, including Zero Trust, cloud transformation, infrastructure modernisation and technology refresh programmes. Define measurable key performance indicators and maturity assessments covering inventory completeness, risk remediation, migration progress, supplier readiness, crypto-agility and outstanding residual exposure.</td>
</tr>
<tr>
<td valign="top">Immature or flawed PQC implementation</td>
<td valign="top">PQC standards and protocol integrations are still maturing, so adopting too early or without a selection policy can lock in choices that later need rework. New code, messages and processing can also introduce implementation flaws and side-channel weaknesses, potentially raising exposure to classical attacks while lowering quantum exposure. (GSMA Annex B; Deloitte GV.RM-04)</td>
<td valign="top">Establish a cryptographic technology selection and approval process based on recognised standards, approved algorithms, security guidance and relevant implementation maturity. Require security architecture reviews, secure development practices, code review, cryptographic implementation validation and independent security testing. Monitor changes to PQC standards and known vulnerabilities, and maintain processes to update or replace implementations when weaknesses or superseding standards emerge.</td>
</tr>
<tr>
<td valign="top">Insufficient interoperability and performance testing</td>
<td valign="top">Untested PQC changes can break connections with partners, suppliers and legacy systems or degrade performance, especially without representative test environments or independent validation. (GSMA §4.2.3, §5.2.3.3; Deloitte GV.SC-02, PR.IR)</td>
<td valign="top">Establish a formal PQC testing framework covering functional correctness, interoperability, protocol compatibility, security, performance, scalability and operational resilience. Test implementations against representative production environments, legacy platforms, network infrastructure, external partners and supplier systems. Evaluate increased key and signature sizes, message overhead, latency, throughput and resource consumption. Require documented test results and formal security and operational approval before production deployment.</td>
</tr>
<tr>
<td valign="top">Business disruption from cryptographic migration</td>
<td valign="top">Changing cryptography can break dependent business processes, data flows and third-party connections (e.g. payments, claims processing, patient or customer services), causing outages or failed transactions if not planned with business owners. (Deloitte GV.OC-04, GV.RM-04)</td>
<td valign="top">Implement controlled migration and deployment procedures that include business impact assessments, dependency mapping, stakeholder engagement, phased rollouts, pilot deployments, rollback arrangements and contingency plans. Coordinate changes with application owners, operations teams, suppliers and business stakeholders. Validate critical business processes and service availability before and after migration, and ensure that migration windows and recovery arrangements align with operational requirements.</td>
</tr>
<tr>
<td align="center" rowspan="4" valign="middle"><b>Key management, PKI and identity</b></td>
<td valign="top">Compromise of trust infrastructure (PKI, certificates and key exchange)</td>
<td valign="top">Once a CRQC exists, attackers could break or forge certificates, signatures and key exchanges (PKI, TLS, VPN/IPsec). That would let them impersonate users, devices and services, intercept traffic or forge signed software and firmware updates. Compromise of central identity or management infrastructure could give control of many systems at once. (GSMA §3.2.2, §4.2.3, §5.2.3.2; Deloitte ID.RA-09)</td>
<td valign="top">Establish a PQC migration and resilience programme for public key infrastructure, certificate authorities, digital signatures, key exchange protocols and associated trust services. Prioritise critical trust infrastructure, including root and intermediate certificate authorities, identity services, TLS, VPN/IPsec and software-signing infrastructure. Implement approved quantum-resistant algorithms and protocols as appropriate, strengthen key protection and certificate lifecycle controls, and validate trust-chain interoperability and recovery procedures.</td>
</tr>
<tr>
<td valign="top">Quantum-vulnerable authenticators and credentials</td>
<td valign="top">Credentials and authentication mechanisms for users, services and hardware that rely on vulnerable cryptography could be spoofed, giving unauthorised access to systems and data. (GSMA §5.2.3.2; Deloitte PR.AA)</td>
<td valign="top">Identify and assess authentication mechanisms, digital certificates, credentials and device identities that depend on quantum-vulnerable cryptography. Develop a migration plan for affected authentication and authorisation systems, incorporating approved PQC mechanisms and appropriate quantum-resistant credential protection. Validate user, service and device authentication, maintain secure credential issuance and revocation processes, and monitor for unauthorised access and authentication anomalies.</td>
</tr>
<tr>
<td valign="top">Weak key and certificate lifecycle management</td>
<td valign="top">Manual or fragmented handling of keys, certificates and pre-shared keys, including secure out-of-band distribution, increases errors, expiry outages and key compromise as cryptographic complexity grows. (GSMA Annex B; Deloitte PR.PS-01)</td>
<td valign="top">Establish standardised, centralised key and certificate lifecycle management processes covering generation, distribution, storage, rotation, renewal, revocation, archival and destruction. Apply cryptographic key protection, access restrictions, segregation of duties, secure backup and recovery, certificate expiry monitoring and auditable key handling procedures. Review lifecycle processes to accommodate PQC algorithm requirements, larger key and signature sizes and changes to cryptographic protocols.</td>
</tr>
<tr>
<td valign="top">Key custody in hardware that can’t be upgraded</td>
<td valign="top">HSMs, key management systems and other hardware that stores or protects keys may rely on quantum-vulnerable algorithms or be unable to support PQC. The organisation’s most sensitive keys then have no practical upgrade path, and replacement can be slow and costly. (GSMA §3.2.4; Deloitte ID.AM-01, GV.SC-04, PR.PS-03)</td>
<td valign="top">Maintain an inventory and capability assessment of hardware security modules (HSMs), key management systems, trusted platform modules and other hardware responsible for cryptographic key custody. Require suppliers to disclose PQC support, firmware upgrade capabilities, cryptographic algorithm roadmaps and product lifecycle commitments. Establish migration, upgrade or replacement plans for hardware that cannot support approved quantum-resistant algorithms, ensuring that secure key generation, storage, backup and recovery remain available throughout the transition.</td>
</tr>
<tr>
<td align="center" rowspan="5" valign="middle"><b>Security monitoring and incident response</b></td>
<td valign="top">Limited indicators of quantum-enabled compromise</td>
<td valign="top">Compromise by a CRQC may leave few detectable indicators, so exposure can go unnoticed without quantum-specific threat intelligence and active monitoring of cryptographic posture. (Deloitte ID.RA-02)</td>
<td valign="top">Establish threat intelligence and security monitoring processes that consider quantum-related cryptographic threats, including potential CRQC-enabled attacks, compromised public-key algorithms, forged signatures and harvested encrypted data. Monitor relevant threat intelligence, cryptographic vulnerability disclosures, standards updates and indicators of compromise affecting cryptographic infrastructure. Define procedures for escalating emerging quantum threats and reassessing exposed assets and associated risk.</td>
</tr>
<tr>
<td valign="top">No continuous cryptographic monitoring</td>
<td valign="top">Monitoring that doesn’t span all layers and third-party systems lets deprecated algorithms, unauthorised cryptography and unlogged changes to cryptographic assets go unseen. (Deloitte DE.CM, PR.PS-04, PR.PS-05)</td>
<td valign="top">Implement continuous or scheduled monitoring of cryptographic assets, configurations, algorithms, protocols, certificates and key management services across enterprise and third-party environments. Detect the use of deprecated or unauthorised algorithms, configuration drift, unauthorised cryptographic changes, certificate anomalies and deviations from approved cryptographic standards. Integrate monitoring with security operations, vulnerability management and configuration management processes.</td>
</tr>
<tr>
<td valign="top">Hybrid attack chains assessed in isolation</td>
<td valign="top">A quantum-enabled exploit combined with classical weaknesses (e.g. a forged software signature leading an administrator to install malware) may be missed if each risk is assessed separately. (GSMA §3.2.3)</td>
<td valign="top">Incorporate quantum-enabled attack scenarios into threat modelling, attack-path analysis and enterprise security assessments. Evaluate how quantum-enabled compromise of cryptographic controls could combine with conventional vulnerabilities, identity compromise, software supply chain attacks and privilege escalation. Assess the resulting impact across interconnected systems and business processes and implement layered preventive, detective and response controls to address complete attack scenarios.</td>
</tr>
<tr>
<td valign="top">Incident response not prepared for cryptographic compromise</td>
<td valign="top">Incident response plans, playbooks and exercises that don’t cover CRQC-based compromise or failed migrations, or that leave out suppliers running cryptographic services, make the organisation slow to detect, escalate and contain a cryptographic incident. (Deloitte GV.SC-07, GV.SC-08)</td>
<td valign="top">Update cybersecurity incident response plans and playbooks to include quantum-related cryptographic compromise, certificate and key compromise, compromised digital signatures, failed PQC migration and supplier-related cryptographic incidents. Define detection, triage, escalation, containment, revocation, key rotation, recovery and stakeholder notification procedures. Conduct tabletop exercises and technical simulations involving security operations, PKI teams, business owners and relevant third-party providers.</td>
</tr>
<tr>
<td valign="top">No plan for exposure of harvested data</td>
<td valign="top">If sensitive data has already been harvested, the absence of a response and recovery strategy for its eventual exposure leaves the organisation unprepared for legal, regulatory, customer and reputational consequences. (GSMA §5.5, §3.4)</td>
<td valign="top">Establish a response and recovery strategy for sensitive information that may have been intercepted, exfiltrated or retained in encrypted form by threat actors for future decryption. Identify affected datasets, assess confidentiality shelf life and potential future exposure, and define legal, regulatory, contractual and customer notification procedures. Maintain documented decision-making, communications, remediation and recovery arrangements, recognising that previously harvested data cannot be retrospectively protected through subsequent cryptographic migration.</td>
</tr>
<tr>
<td align="center" rowspan="4" valign="middle"><b>IT operations, change and resilience</b></td>
<td valign="top">Cryptographic impact missing from change control</td>
<td valign="top">New systems, upgrades and procurements approved without considering their cryptography add vulnerable algorithms and deepen cryptographic debt. (Deloitte ID.RA-07, GV.PO-02)</td>
<td valign="top">Incorporate mandatory cryptographic impact assessments into IT change management, solution architecture reviews, software development and technology procurement processes. Require changes to identify cryptographic algorithms, protocols, certificates, key management dependencies and PQC compatibility. Ensure that new systems and upgrades comply with approved cryptographic standards, crypto-agility requirements and the organisation's quantum readiness roadmap before approval and deployment.</td>
</tr>
<tr>
<td valign="top">Regression to vulnerable cryptography</td>
<td valign="top">Patches, configuration changes or fallback behaviour can quietly revert migrated assets to quantum-vulnerable algorithms, undoing earlier progress. (Deloitte ID.RA-06, ID.RA-07)</td>
<td valign="top">Establish cryptographic configuration management and continuous compliance controls to prevent systems from reverting to deprecated or quantum-vulnerable algorithms. Maintain approved cryptographic baselines, automated configuration validation, secure deployment pipelines and version-controlled cryptographic configurations. Monitor changes, patches and fallback behaviour for deviations and require investigation, remediation and formal exception approval where compliance cannot be maintained.</td>
</tr>
<tr>
<td valign="top">Performance and capacity degradation</td>
<td valign="top">PQC changes message sizes, message sequences and processing load. On constrained devices (e.g. IoT, smart cards, medical or industrial equipment) and high-volume systems (e.g. payment, trading, messaging or network infrastructure), this can degrade latency, capacity or availability. (GSMA Annex B; Deloitte PR.IR, GV.RM-04)</td>
<td valign="top">Conduct performance, capacity and resource assessments before deploying PQC algorithms and protocols into production environments. Evaluate computational overhead, memory consumption, bandwidth requirements, message sizes, latency, throughput and processing capacity across relevant devices, applications and network infrastructure. Establish performance acceptance criteria, conduct representative load and stress testing, and implement capacity upgrades or architectural adjustments where necessary.</td>
</tr>
<tr>
<td valign="top">Continuity and recovery plans exclude cryptographic failure</td>
<td valign="top">Business continuity and disaster recovery plans that don’t consider a CRQC-driven loss of availability or integrity, or a failed cryptographic migration, can prolong outages of critical services. Suppliers responsible for cryptographic services may also be missing from recovery arrangements. (Deloitte GV.SC-09, ID.RA-04, ID.RA-06; GSMA §4.2.3)</td>
<td valign="top">Incorporate cryptographic compromise, PQC migration failure, key management disruption, certificate infrastructure outages and loss of cryptographic service availability into business continuity and disaster recovery plans. Define recovery objectives, secure backup and restoration procedures, alternative trust and key management arrangements, rollback capabilities and supplier recovery responsibilities. Conduct periodic exercises to validate the ability to restore critical services while maintaining appropriate cryptographic security.</td>
</tr>
</tbody>
</table>

## Source key

Bracketed references at the end of each risk description point to the source material:

- **GSMA** – [Guidelines for Quantum Risk Management for Telco, v1.0](https://www.gsma.com/get-involved/working-groups/wp-content/uploads/2023/09/Guidelines-for-Quantum-Risk-Management-for-Telco-v1.0.pdf). Section numbers (for example §3.2.1) refer to this document.
- **Deloitte** – [Cryptographic Resilience Community Profile](https://www.deloitte.com/content/dam/assets-shared/docs/services/consulting/2026/deloitte-cryptographic-resilience-community.pdf). Identifiers such as GV.RM-03 are NIST CSF 2.0 subcategories.
