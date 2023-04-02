# Security Considerations in Design

Addressing security is important at every stage of product development, but it is especially critical to address security
at the beginning of a project through careful consideration and planning. Identifying and fixing security issues at the
end of a product development cycle or after a product release can be expensive, both in terms of the rework cost and
with regard to schedules, deliverables, revenue, and customer good will. Security risks not only come from determined
attackers, but also from innocent oversights in software administration.

When developers consider security in the functional design, they conduct three basic tasks:
- Evaluate for vulnerabilities
- Assess the possibility of a threat compromising a vulnerability
- Mitigate the vulnerability in design or recommend suitable secure deployment of functionality

Reviewing the vulnerabilities and threats that might arise in software, along with the associated mitigations relative to
the operation of the product, establishes a security posture, or baseline security state for the product. You can think of
this in the same way that a military organization evaluates, anticipates, and prepares to address security issues, thereby
establishing a posture relative to a specific threat or vulnerability. The security posture for a router deployed in a bank is
different from that of a switch installed in an office.

The types of attacks and threats associated with the software security posture depend on
the product and can include, but are not limited to, eavesdropping, replay, message insertion, message deletion,
modification of data, man-in-the-middle, and denial of service (DoS). Some products might also require a review of
cryptographic functions.


> Reviewing security relative to feature functionality is accomplished through a series of Secure Development Lifecycle
activities:

- Vulnerability assessments using industry standard information and publications such as RFCs
- Security posture evaluation in product software functional specifications
- Security feedback integrated into product planning and design
A solid understanding of a product’s security posture through review of the functionality design serves as input into other
Secure Development Lifecycle practices, including Threat Modeling.
