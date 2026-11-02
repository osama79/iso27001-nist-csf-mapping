# iso27001-nist-csf-mapping
Crosswalk of ISO/IEC 27001:2022 Annex A controls to NIST CSF 2.0 categories for audit prep.
# ISO 27001:2022 ↔ NIST CSF 2.0 Mapping

A working crosswalk between ISO/IEC 27001:2022 (Clauses 4-10 and selected
Annex A controls) and NIST Cybersecurity Framework 2.0 categories.
Built for audit preparation, gap assessments, and explaining one framework
in terms of the other.

> **Disclaimer:** This is an informative mapping based on my professional
> judgment. It is not an official ISO or NIST publication. ISO/IEC 27001
> is a copyrighted standard; control names are paraphrased and no standard
> text is reproduced. Mappings are many-to-many and should be validated
> for your own scope and context.

## How to use it
1. Find your control in the table below.
2. See which CSF 2.0 function and category it supports.
3. Use the **Evidence examples** column when preparing for audit.

## CSF 2.0 functions
Govern (GV) · Identify (ID) · Protect (PR) · Detect (DE) · Respond (RS) · Recover (RC)

## Mapping

### ISMS clauses
| ISO 27001 | Topic | CSF 2.0 category | Evidence examples |
|---|---|---|---|
| Cl. 4 | Context of the organization | GV.OC | Scope statement, interested-parties register |
| Cl. 5 | Leadership and policy | GV.PO, GV.RR | Signed policy, roles matrix |
| Cl. 6.1 | Risk assessment and treatment | GV.RM, ID.RA | Risk register, Statement of Applicability |
| Cl. 9 | Performance evaluation | GV.OV, ID.IM | Internal audit reports, management review minutes |
| Cl. 10 | Improvement | ID.IM | Corrective action log |

### Annex A: Organizational
| Control | Topic | CSF 2.0 category | Evidence examples |
|---|---|---|---|
| A.5.1 | Information security policies | GV.PO | Approved policy set, review log |
| A.5.2 | Security roles and responsibilities | GV.RR | RACI, job descriptions |
| A.5.9 | Asset inventory | ID.AM | CMDB export, asset register |
| A.5.12 | Information classification | ID.AM, PR.DS | Classification scheme, labeled samples |
| A.5.15-5.18 | Access control, identity, access rights | PR.AA | Access policy, joiner/mover/leaver records, access reviews |
| A.5.19-5.22 | Supplier security | GV.SC | Vendor risk assessments, contract clauses |
| A.5.24-5.26 | Incident planning, assessment, response | RS.MA, RS.MI, DE.AE | IR plan, incident tickets, tabletop results |
| A.5.27 | Learning from incidents | ID.IM | Post-incident reviews |
| A.5.29-5.30 | Continuity and ICT readiness | RC.RP, PR.IR | BCP/DR plans, DR test reports |
| A.5.31 | Legal and regulatory requirements | GV.OC | Compliance register |
| A.5.35-5.36 | Independent review, policy compliance | GV.OV, ID.IM | Audit schedule, review reports |

### Annex A: People
| Control | Topic | CSF 2.0 category | Evidence examples |
|---|---|---|---|
| A.6.3 | Awareness and training | PR.AT | Training records, phishing test results |

### Annex A: Physical
| Control | Topic | CSF 2.0 category | Evidence examples |
|---|---|---|---|
| A.7.1-7.2 | Perimeters and physical entry | PR.AA | Badge logs, visitor logs |
| A.7.4 | Physical security monitoring | DE.CM | CCTV retention records |

### Annex A: Technological
| Control | Topic | CSF 2.0 category | Evidence examples |
|---|---|---|---|
| A.8.2, A.8.5 | Privileged access, secure authentication | PR.AA | PAM reports, MFA enrollment |
| A.8.7 | Malware protection | PR.PS, DE.CM | EDR coverage report |
| A.8.8 | Vulnerability management | ID.RA, PR.PS | Scan reports, remediation SLAs |
| A.8.9 | Configuration management | PR.PS | Baselines, drift reports |
| A.8.13 | Backup | PR.DS, RC.RP | Backup job logs, restore tests |
| A.8.15-8.16 | Logging and monitoring | DE.CM, DE.AE | SIEM use cases, log retention config |
| A.8.20-8.22 | Network security and segregation | PR.IR | Network diagrams, firewall rule reviews |
| A.8.24 | Cryptography | PR.DS | Key management procedure |
| A.8.25-8.28 | Secure development | PR.PS | SDLC policy, code review records |
| A.8.32 | Change management | PR.PS | Change tickets, CAB minutes |

## Roadmap
- [ ] Add remaining Annex A controls
- [ ] Add a gap-assessment column (Implemented / Partial / Gap)
- [ ] Add a CSV version for import into GRC tools
- [ ] Add PCI DSS and UAE PDPL columns

## Author
Ali Khan: [LinkedIn](https://www.linkedin.com/in/alijobs/)
