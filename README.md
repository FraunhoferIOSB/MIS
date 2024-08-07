# Manufacturer Information Service (MIS)

The **M**anufacturer **I**nformation **S**ervice **(MIS)** is a modular digital service that provides key modules for the **Manufacturing as a Service (MaaS)** use case.

More information about the MaaS use case :blue_book: [here](https://eclipse-tractusx.github.io/docs-kits/kits/Manufacturing%20as%20a%20Service%20Kit/Adoption%20View%20MaaS%20KIT#usecase--domain-explanation)

| MIS is still under development. Contributions in form of requirements, issues and pull requests are highly welcome. |
|-----------------------------|

## MIS Overview

Classification of MIS in an exemplary MaaS ecosystem under consideration of relevant stakeholders.

<img width="617" alt="MIS_Overview" src="https://github.com/user-attachments/assets/9e5b5207-2e69-4e61-910e-a4000c44f3ee">

The following use cases can be performed with the MIS.

### Use Cases of MIS
1. **Manual onboarding**
- Onboarding of manufacturer information via factory connectors.
- AI-based onboarding of manufacturer information, based on machine specifications.
2. **Automatic onboarding / crawling**
- The manufacturers' production capabilities are automatically read out by querying the factory connectors.
3. **Requesting manufacturer information**
- Data consumer can use the MIS to query information such as production capabilities for a data provider.
4. **Search for potential suppliers/supply chains**
- Identification of potential suppliers/supply chains for a given production process.

### MIS Architecture

MIS architecture with the functional components.

<img width="459" alt="MIS_Architecture" src="https://github.com/user-attachments/assets/074dd088-9065-4e1c-a323-a1dbdc47e25c">

| Components    | Goals         | URL           |
| ------------- | ------------- | ------------- |
| **Supplier Knowledge Base (SKB)** | Knowledge base for manufacturer/supplier information including capabilities, properties, etc. | [MIS](https://github.com/FraunhoferIOSB/MIS)  |
| **Asset Management and Refinement Application (AMARA)**  | Automatically derives manufacturing capabilities from machine specifications with Large Language Models (LLM)  | tbd  |
| **Asset Management Service (AMS)**  | Interface to manage asset information like enterprise, factories, manufacturing capabilities, etc. within the knowledge base |[MIS-AMS](https://github.com/FraunhoferIOSB/MIS-AMS)  |
| **Search Engine (SE)**  | Provision of manufacturer information such as production capabilities for a given process description  | [MIS-SE](https://github.com/FraunhoferIOSB/MIS-SE)  |

