## Scenario

_This scenario is based on a fictional company:_

"Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their
products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure
to support their online market worldwide.

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan.
She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also
interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the
IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. "

## Scope and goals of the audit.

### Scope

The scope of this audit is defined as the entire security program at Botium Toys.
This includes their assets like employee equipment and devices, their internal network,
and their systems. You will need to review the assets Botium Toys has and the controls
and compliance practices they have in place.

### Goals

Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices that need to be implemented
to improve Botium Toys’ security posture.

## Current assets

Assets managed by the IT Department include:

- On-premises equipment for in-office business needs.

- Employee equipment: end-user devices (desktops/laptops, smartphones),
  remote workstations, headsets, cables, keyboards, mice, docking stations,
  surveillance cameras, etc.

- Storefront products available for retail sale on site and online; stored in the
  company’s adjoining 

- Management of systems, software, and services: accounting,
  telecommunication, database, security, ecommerce, and inventory management.

- Internet access.

- Internal network.

- Data retention and storage.

- Legacy system maintenance: end-of-life systems that require human monitoring.M

## Risk assessment

### Description

Currently, there is inadequate management of assets. Additionally, Botium Toys does
not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.

### Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to
dedicate resources to identify assets so they can appropriately manage them.
Additionally, they will need to classify existing assets and determine the impact of the
loss of existing assets, including systems, on business continuity.

### Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.

### Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure.

## Controls Assessment Checklist

Does Botium Toys currenly have this control in place?

| Yes/No/? | Control Name                                                        | Explanations                                                                                                       |
| -------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| No       | Least Privilege                                                     | Everyone has access to the data internally stored, there can be a malicious breach if it's not taken care properly. |
|   No       | Disaster recovery plans                                             |                                                                                                                    |
|          | Password policies                                                   |                                                                                                                    |
|          | Separation of duties                                                |                                                                                                                    |
|          | Firewall                                                            |                                                                                                                    |
|          | Intrusion detection system (IDS)                                    |                                                                                                                    |
|          | Backups                                                             |                                                                                                                    |
|     Yes     | Antivirus software                                                  |       The antivirus software is active and regularly monitored by IT Team                                                                                                             |
|          | Manual monitoring, maintenance, and intervention for legacy systems |                                                                                                                    |
| No       | Encryption                                                          | Customer's credit card informations are not protected. The company should ensures that only authorized parties can access sensitive information, protecting it from hackers, eavesdroppers, and other malicious actors.                                                     |
|          | Password management system                                          |                                                                                                                    |
|          | Locks                                                               |                                                                                                                    |
| Yes      | Closed-circuit television (CCTV) surveillance                       | The company's store location is well equiped with up-to-date CCTV's and locks.                                             |
|     Yes     | Fire detection                                                      |        The company's warehouse and stores have functionning fire detection  and prevention systems. The team sould keep on maintaining them.                                                                                                        |

## Compliance Checklist

Does Botium Toys currenly adhrere to this compliance best practice?

- Payment Card Industry Data Security Standard (PCI DSS).

| Yes/No/? | Best Practice                                                                                       | Explanations |
| -------- | --------------------------------------------------------------------------------------------------- | ------------ |
|          | Only authorized users have access to customer's credit card information.                            |              |
|          | Credit card information is stored, accepted, processed, and transmitted, in a secure environment.   |              |
|          | Implement data encryption procedures to better secure credit card transaction touchpoints and data. |              |
|          | Adopt secure password management policies.                                                          |              |

-General Data Protection Regulation (GDPR)

| Yes/No/? | Best Practice                                                                                                     | Explanations |
| -------- | ----------------------------------------------------------------------------------------------------------------- | ------------ |
| testing  | E.U. customers’ data is kept private/secured.                                                                     | testing      |
|          | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |              |
|          | Ensure data is properly classified and inventoried.                                                               |              |
|          | Enforce privacy policies, procedures, and processes to properly document and maintain data.                       |              |

- System and Organizations Controls (SOC Type 1, SOC Type 2)

| Yes/No/? | Best Practice                                                                              | Explanations |
| -------- | ------------------------------------------------------------------------------------------ | ------------ |
| testing  | User access policies are established.                                                      | testing      |
|          | Sensitive data (PII/SPII) is confidential/private.                                         |              |
|          | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |              |
|          | Data is available to individuals authorized to access it.                                  |              |

## Recommendations

After researching Botium Toys's security posture, the analysts agreed that the security practice is far from the expectation. It lacks of protection of confidentialiy of sensitive information. The following are:

1. Least privilege
2. Disaster recovery plan
3. Password policies
4. Encryption
5. Password management system

To close compliance gaps, Botium must implement and establish policies that address the points mentioned above. Additionally, Botium should update its assets to ensure that any new controls are quickly identified, thereby enhancing their security practices.
