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
