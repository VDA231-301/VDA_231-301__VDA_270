![VDS 270](https://github.com/user-attachments/assets/3379067c-6783-4d68-8bc6-dcedcb572699)

# VDA 270 – Odour Test Results
## JSON Subschema according to VDA 231‑301
🔗 This subschema is part of the **VDA 231‑301 open JSON standard ecosystem**
➡ https://github.com/VDA231-301

## Purpose and Scope

This repository provides a **specific JSON subschema for the digital exchange of test results according to VDA 270**,  
*“Determination of the odour characteristics of trim materials in motor vehicles”*.
 - Recommendation source: https://webshop.vda.de/VDA/de/vda-270-052022
   
The subschema defines a **machine‑readable representation of odour test results** and supports the standardized, transparent, and interoperable exchange of laboratory data along the supply chain.

It is based on the **VDA 231‑301 recommendation** and represents a specialized extension of the generic VDA 231‑301 JSON schema.

---

## Position within VDA 231‑301

Within the VDA 231‑301 ecosystem:
- the **generic schema** defines the common structure for digital test reports,
- this **VDA 270 subschema** specifies the data elements required to represent odour test results generated according to the VDA 270 method.

The subschema ensures that odour test results from different laboratories can be exchanged and processed in a **consistent, system‑independent, and machine‑readable form**.

---

## Relation to the VDA 270 Test Method

VDA 270 defines a **laboratory test method** for the sensory evaluation of odour characteristics of materials, primarily used for interior components.

⚠️ **Important clarification:**
- This repository **does not describe the VDA 270 test procedure itself**.
- It does **not define panel evaluation rules, scoring systems, acceptance criteria, or limit values**.
- It provides a **technical data structure only** for representing the *results* of a VDA 270 odour test in digital form.

The authoritative description of the VDA 270 test method is published exclusively by the VDA and is available via the **VDA Webshop**.

---

## Documentation of Odour Test Results

The subschema specifies the **format in which odour test results shall be documented**.

This includes, for example:
- structured representation of **test conditions and specimen information**,
- documentation of **panel assessments and odour ratings**,
- clear association of results with test series, test dates, and laboratories.

By enabling a structured digital representation of odour test results, the subschema supports improved **traceability, comparability, and automated data processing** compared to document‑based reporting.

---

## Typical Use Cases

The VDA 270 subschema supports use cases such as:
- digital exchange of odour test results between laboratories, suppliers, and OEMs
- structured integration of odour assessment data into material databases
- traceable documentation of sensory evaluations for quality assurance
- automated processing of odour test data in IT systems

The subschema improves **data consistency, transparency, and reproducibility** across organizations and systems.

---

## Applicability Beyond the Automotive Industry

Although VDA 270 originates from the automotive interior context, **sensory odour evaluation of materials is relevant across many industries**, for example:
- consumer products
- furniture and interior materials
- construction products
- polymers, foams, adhesives, and textiles

The subschema is therefore **not limited to automotive applications**.  
It can be used wherever odour test results need to be:
- documented,
- exchanged between organizations,
- or integrated into digital quality and compliance workflows.

---

## Example Files

This repository contains example files illustrating the usage of the subschema:
- JSON examples representing VDA 270 test results
- the corresponding JSON Schema definition

These examples are provided for **illustration and implementation support only**.

---

## Important Note

> [!IMPORTANT]
> This subschema provides **structured odour test result data only**.  
> It does **not** perform odour evaluation, acceptance decisions,
> or pass/fail assessments.
> Such decisions remain the responsibility of the applicable standards,
> specifications, and quality processes.

---

## License 

The VDA 231‑301 JSON schemas, including this VDA 270 subschema, are released under the **MIT License**, allowing free use, modification, and distribution.


## Contributing & VDA Process

Contributions are welcome.  

Any changes intended to become part of the official VDA recommendation must follow the formal VDA committee and release process.
 
This repository hosts a subschema extending the generic VDA 231‑301 JSON schema.

GitHub is used as a platform for collaborative drafting, discussion, and technical refinement.  
Issues and Pull Requests are welcome.

⚠️ Please note:  
Only subschemas that have successfully passed the formal VDA committee and release process may become part of the official VDA 231‑301 recommendation.

Details on contribution rules, governance, and approval processes are described in the organization-wide Contributing Guidelines:  
https://github.com/VDA231-301/.github/blob/main/CONTRIBUTING.md



