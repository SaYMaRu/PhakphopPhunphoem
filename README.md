# ITCS37_Introduction-to-Software-Engineering
# Revision Log

## Functional Requirements

### **New Additions:**
1. Recording the source of the dog, such as abandoned dogs or temporarily cared-for dogs.
2. Logging health checks and training status before the adoption process.
3. Uploading high-resolution images of dogs for display purposes.
4. Updating and editing dog information, such as recent health updates.
5. Connecting with external organizations to verify criminal records of adoption applicants.
6. Filtering applicants by cross-checking blacklists or related records.
7. Reviewing and selecting the most suitable adopter for a dog when multiple applications are received.
8. Scheduling and managing dog delivery logistics, including tracking status and time.
9. Allowing sponsors to register and fill out sponsorship details.
10. Reviewing and approving sponsor registrations, with sponsor logos displayed on the website.
11. Logging home visits and condition checks for dogs post-delivery, including monthly reports.
12. Generating reports on the number of dogs, adopters, and sponsors.
13. Encrypting sensitive user data and restricting access based on permissions.
14. Logging user access for tracking and auditing data usage.
15. Adding features to meet accessibility standards for visually impaired users.
16. Supporting processing of up to 1,000 transactions per day for scalability.

## Non-Functional Requirements

### **New Additions:**
1. Supporting at least 1,000 transactions per day while maintaining optimal performance.
2. Using a blue-and-white color scheme to align with organizational branding.
3. Recovering data within 5 minutes of disruption, supported by daily automatic backups.
4. Encrypting sensitive information, such as ID cards, and implementing two-factor authentication (2FA).
5. Restricting data access according to permissions, e.g., adoption records visible only to staff.
6. Logging access to critical information for tracking and auditing purposes.
7. Preventing duplicate data entry and validating submitted data for accuracy.
8. Meeting AA standards of the Web Content Accessibility Guidelines (WCAG).
9. Developing a Disaster Recovery Plan for timely resumption of operations.
10. Ensuring system code adheres to programming standards for easy future maintenance.
11. Supporting data retention for legally mandated periods and automatic deletion of expired data.
12. Expanding support for all device types (computers, tablets, and smartphones).

## Identifying Actors
### **New Additions:**
1. Crime Suppression:
- Responsibilities: This organization serves as a supporting entity for background checks on adopters, providing essential information for assessing eligibility, including:
  - Conducting criminal record checks and reporting results to the adoption system.
  - Providing information on individuals listed on blacklists, allowing shelter staff to verify if adopters have unfavorable histories.
  - Access Rights: They do not have direct access to the system but send information to the system for verification and review.


## Use Case Diagrams
## Actors
### Additions in Modified Diagram:
- **Criminal History Checker**: Added to handle criminal background checks.
- **Income Verifier**: Added for income verification during the adoption process.
- **Sponsor Approver**: Added to manage sponsorship approvals.
- **Adoption Approver**: Added to review and approve adoption requests.

## Use Cases
### New Use Cases in Modified Diagram:
1. **Approve the Adoption**:
   - Details the specific process for adoption approval.
2. **Approve the Sponsor**:
   - Outlines the review process for sponsors.
3. **Coach the Dog**:
   - Introduces a training aspect for dogs.
4. **Dog Health Checking**:
   - Adds a health verification step for the dogs.
5. **Submit Sponsorship & Logo**:
   - Includes submission of sponsorship details.
6. **Check Adopter Status**:
   - Enables monitoring the status of an adopter.
7. **Upload Photo**:
   - Adds a feature for uploading dog or adopter photos.
8. **Make Report**:
   - Documents report creation related to the adoption process.

## Relationships
### Modifications in Modified Diagram:
1. **Include Links**:
   - Added more "include" relationships for:
     - **Approve the Sponsor** in **Submit Sponsorship & Logo**.
     - **Approve the Adoption** in the adoption process.
   - Adds dependency details for steps like **Date** and **Location** in delivery appointments.
   
2. **Extend Relationships**:
   - **Update Dog Information** extends **Record the Dog**.
   - **Receive Impact Updates** extends **Track Contributions**.

## Data Flow Diagram Level 0

