# One Login's Limited Scope and Privacy-First Architecture

GOV.UK One Login operates as a **privacy-conscious authentication service** rather than a comprehensive data-sharing platform, implementing strict boundaries that limit cross-government data trading while prioritizing user control and data minimization principles.

## Identity Federation Uses Service-Specific Identifiers

**One Login does NOT create cross-government identifiers for data trading**. Instead, the system implements a sophisticated **pairwise subject identifier architecture** that generates unique identifiers for each user-service combination.

The technical architecture uses **sector identifiers** - URI-based configurations that control user identification across services. Government organizations have three options: completely separate user identifiers for each service, shared identifiers across specific related services, or hybrid models. This design prevents automatic cross-service user correlation unless explicitly configured through deliberate architectural decisions.

As the official documentation states: **"Where possible, we ask for and transmit a yes/no response to identity assurance questions, rather than requesting or sharing personal information."** This reflects a fundamental design principle prioritizing privacy over administrative convenience.

## Attribute Sharing Remains Strictly Limited

The scope of attributes One Login shares is **deliberately constrained to core biographical data** - primarily name, date of birth, current address, email, and phone number. The system explicitly avoids sharing comprehensive identity proofing evidence.

**Critical limitation**: Evidence document data from passports or driving licenses is "only shared in very limited cases to prevent identity fraud" - not as default functionality. The official policy emphasizes **"we share the minimum data (number of fields) that will uniquely distinguish that document from another. We do not share the entire document data."**

The system provides verification outcomes and confidence levels rather than underlying evidence. Future development plans focus on **"sharing only the confirmation of identity proved to the required level of confidence, without sharing personal information from identity documents."**

## Evidence Trading Between Services Is Highly Restricted

**One Login does NOT currently operate as an evidence trading platform** between government organizations. The current model follows strict data minimization principles, sharing verification outcomes rather than comprehensive identity proofing evidence.

Government services operate as "independent data controllers under Memorandums of Understanding," with each service managing its own data needs. While coordination exists with authoritative sources like HMRC, DVLA, and HM Passport Office for verification purposes, this represents controlled verification flows rather than broad evidence sharing.

The proposed **Digital Economy Act expansion** could enable broader data sharing capabilities in the future, but these would require legislative approval and would operate under strict governance frameworks with public transparency requirements.

## Government-Only Boundaries Are Strictly Enforced

One Login is **exclusively designed for government-to-citizen use cases** with no plans for third-party organization access. Multiple official sources confirm these boundaries, and the private sector identity industry has **explicitly urged the government not to make One Login available for commercial services**.

The UK maintains separate frameworks: One Login for government services and the **Digital Identity and Attributes Trust Framework (DIATF)** with 50+ certified private providers for commercial digital identity services. This separation prevents unfair competition between public and private sector identity services.

Future expansion plans focus on **local government integration** rather than private sector access, maintaining the principle that One Login remains "the preserve of the public sector."

## Authentication Over Authorization Defines Core Purpose

**One Login's primary function is authentication and identity verification**, not providing a data-sharing mechanism across government. The system implements standard OpenID Connect protocols focused on proving users are who they claim to be and enabling secure sign-in across government services.

The architecture prioritizes **digital identity reuse** - once a user's identity is verified, that verification can be reused across services without requiring re-verification. However, this reuse mechanism shares verification outcomes rather than comprehensive personal data or evidence files.

## Conclusion

One Login represents a **privacy-by-design approach** to government digital identity that deliberately constrains cross-government data sharing in favor of user privacy and organizational autonomy. Rather than creating a centralized data trading platform, it provides controlled authentication services with minimal data exchange, service-specific identifiers, and strict boundaries against commercial use.

This architecture reflects a balanced approach between government efficiency and citizen privacy protection, prioritizing authentication capabilities while maintaining strong data protection principles that prevent the system from becoming a comprehensive surveillance or data-sharing infrastructure.