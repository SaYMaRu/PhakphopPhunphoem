
# Revision Log

## Project: Dog Adoption System

### Revision Summary

| **Section**                  | **Change Description**                                                                                                                                      |
|------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Functional Requirements**  | Expanded to include 10 new requirements, such as support for dog image uploads, delivery logistics, and criminal record verification.                         |
| **Non-Functional Requirements** | Added disaster recovery plans, enhanced scalability, automatic backups, device compatibility, and compliance with WCAG AA accessibility standards.                |
| **Identifying Actors**       | Added details for new actors, specifically `Crime Suppression`, and updated responsibilities for `General User`, `Sponsor`, and `Organization Staff`.         |
| **Use Case Narratives**      | Added three new narratives: "Register an Account," "Login into an Account," and "Search for the Dog." Revised exceptions and conditions for existing cases.   |
| **Diagrams**                 | Modified Data Flow Diagrams (Level 0 and 1) and Functional Decomposition Diagram with updated links and visual enhancements.                                  |

### Detailed Changes

#### Functional Requirements
- New features added, including:
  - Uploading high-resolution images of dogs for display.
  - Recording detailed health and medical history for dogs.
  - Logging criminal records and blacklist checks for adopters.
  - Enhanced delivery tracking system for adopted dogs.
  - Sponsor visibility features, like displaying sponsor logos on the website.
- Expanded requirements for administrative reporting and enhanced user data encryption.

#### Non-Functional Requirements
- **New Additions**:
  - Disaster recovery plan to ensure rapid recovery in case of critical incidents.
  - Scalability to support growth in user traffic and transaction volumes.
  - Device compatibility to allow usage on desktops, tablets, and smartphones.
  - Automatic daily backups and data restoration within 5 minutes.
  - Adherence to accessibility standards (WCAG AA) and support for visually impaired users.
  - Enhanced security measures, such as two-factor authentication and encryption of sensitive user data.
  - Implementation of stringent authentication standards and data access restrictions.
  - Compliance with relevant regulations, including GDPR and Thailand’s PDPA.
  - Performance optimization to handle up to 1,000 transactions per day.
  - A user-friendly interface supporting all age groups and physical abilities.

#### Identifying Actors
- Added `Crime Suppression` as a new actor for background checks.
- Updated roles and permissions for:
  - `General User`: Refined responsibilities for dog searches and profile management.
  - `Sponsor`: Defined new benefits, such as public visibility for financial contributors.
  - `Organization Staff`: Enhanced permissions for adopter selection and data management.

#### Use Case Narratives
- Added new use cases:
  - **Register an Account**: Step-by-step process for new user registration, including exceptions.
  - **Login into an Account**: Detailed login flow with validation checks.
  - **Search for the Dog**: Comprehensive flow for searching and filtering dogs by criteria.
- Enhanced existing use cases with improved exception handling and post-conditions.

#### Diagrams
- Revised and updated diagrams to include:
  - Functional Decomposition Diagram.
  - Data Flow Diagram (Levels 0 and 1).
- New links provided for modified diagram boards.
