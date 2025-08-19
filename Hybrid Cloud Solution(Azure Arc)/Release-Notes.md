# Hybrid Cloud Solution(Azure Arc)

Welcome to the **Hybrid Cloud Solution(Azure Arc)** workshop release notes. In this page, we will document the changes made during the last testing cycle, including updates related to the infrastructure, content, screenshots, and other relevant changes for the lab.

## Overview

This Page contains detailed notes about the latest updates and modifications made after each testing cycle. It includes:

- Testing dates
- Descriptions of changes to lab infrastructure
- Updates to content or documentation
- Changes to screenshots and visuals used in the lab

`For any further details or inquiries, feel free to reach out to the CloudLabs support team. Email Support: cloudlabs-support@spektrasystems.com`

# Release Notes
<details>
  <summary>2025-08-12</summary>

### Release Date: In-Progress

</details>

<details>
  <summary>2025-06-17</summary>

### Release Date: 2025-06-17

- **Testing Date**: 2025-06-17

## Infrastructure Changes

NA

## Content Changes
  
Instructions were updated to be more precise and clear.

## Screenshot Updates

Screenshots were updated to enhance the overall user experience. 

## Validation

NA

## Testing Notes

- **Test Validation Summary**: Validated the lab guide steps.

---
</details>

<details>
  <summary>2025-08-19</summary>

### Release Date: 2025-08-19

- **Testing Date**: 2025-08-13

## Infrastructure Changes

NA

## Content Changes
  
- Lab guide instructions have been updated to reflect the latest steps and UI changes.

## Screenshot Updates

- Updated screenshots throughout the lab guide to match the new UI.
- Added additional screenshots where necessary for better lab guide enhancement.

## Validation

Updated the validation logic for Exercises 1 and 2, as it was previously pointing to the wrong resources.
  - Exercise 1 – Task 5: Corrected validation for the policy assignment to ensure accurate identification of compliant and non-compliant resources.
  - Exercise 2 – Task 2: Fixed validation for onboarding Azure Arc-enabled servers to Microsoft Sentinel.

## Testing Notes

- **Testing Date**: 2025-08-13

- **Tested Features**: validations, latest UI changes, functionality of the lab.

- **Issues Found**: 
  - New UI changes in Microsoft Sentinal and Microsoft Defender for Cloud.
  - validations for Exercise 1 and 2.
  - Data Controller Indirect mode, exercise 10 were unclear and namespace was not getting created.

- **Resolved Issues**: 
  - Addressed the new UI changes in Microsoft Defender for Cloud.
  - Corrected validation steps to ensure proper resource compliance checks.
  - Added a note to create a namespace in an arcdata pod if it is not created, to avoid failures in Data Controller Indirect mode Exercise 10.

---
</details>
