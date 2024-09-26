---
name: POS Integration EPIC
description: Master Issue for a POS Integration.
title: "[POS Integration]: "
labels: ["EPIC", "POS"]
projects: ["ReceiptHero/3"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: sales_person
    attributes:
      label: Sales Responsible
      placeholder: Kuitti Keijo
    validations:
      required: true
  - type: input
    id: partner_contact
    attributes:
      label: Partner Contact
      placeholder: partner.contact@domain.com
    validations:
      required: true
  - type: date
    id: tech_meeting_date
    attributes:
      label: Technical meeting held on
    validations:
      required: true
  - type: date
    id: credetials_provided_date
    attributes:
      label: Sandbox credentials provided on
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Short description, including any special characteristics when it comes to this integration project 
      placeholder: This integration is very special because...
    validations:
      required: true
---

### Description

Short description, including any special characteristics when it comes to this integration project.

- **Sales Responsible**: SALES_RESPONSIBLE
- **Partner Website**: PARTNER_WEBSITE
- **Technical Meeting Held**: 2024-00-00
- **Dev Credentials Provided**: 2024-00-00

### Test User Details

#### 1.
- **Email**: USER1_EMAIL
- **Receipts in DynamoDB**: [USER#USER1_ID](https://eu-central-1.console.aws.amazon.com/dynamodbv2/home?region=eu-central-1#item-explorer?index=GSI1&operation=QUERY&pk=USER%USER1_ID&sk=RECEIPT&skComparator=BEGINS_WITH&sorting=DESC&table=dev-Hero)
- **Hubspot Company**: [COMPANY1_NAME](https://app.hubspot.com/contacts/7265974/record/0-2/HS1_ID)

#### 2.
- **Email**: USER2_EMAIL
- **Receipts in DynamoDB**: [USER#USER2_ID](https://eu-central-1.console.aws.amazon.com/dynamodbv2/home?region=eu-central-1#item-explorer?index=GSI1&operation=QUERY&pk=USER%USER2_ID&sk=RECEIPT&skComparator=BEGINS_WITH&sorting=DESC&table=dev-Hero)
- **Hubspot Company**: [COMPANY2_NAME](https://app.hubspot.com/contacts/7265974/record/0-2/HS2_ID)

### Additional Information

