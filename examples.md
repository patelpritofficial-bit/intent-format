Example 1: Approving a Payment
INTENT
version: 0.1

who:
  name: Prit Patel
  role: Director

what:
  action: approve payment

scope:
  target: Vendor invoice INV-4587

limits:
  money: maximum ₹2,00,000
  time: before 31 March 2025
  quantity: one payment

approval:
  required: yes
  by: Finance Head

proof:
  store: invoice and approval record
  retain_for: 7 years

  Example 2: Booking a Flight Using AI
  INTENT
version: 0.1

who:
  name: Prit Patel
  role: Traveller

what:
  action: book flight ticket

scope:
  target: Mumbai to Dubai

limits:
  money: maximum ₹35,000
  time: travel date between 10 April and 12 April 2025
  quantity: one ticket

approval:
  required: no
  by: not applicable

proof:
  store: booking confirmation and payment receipt
  retain_for: 1 year

Example 3: Granting Temporary System Access
INTENT
version: 0.1

who:
  name: Operations Manager
  role: Plant Operations

what:
  action: grant system access

scope:
  target: Vendor ABC – Inventory Module

limits:
  money: not applicable
  time: access valid for 30 days
  quantity: read-only access

approval:
  required: yes
  by: IT Head

proof:
  store: access logs and approval record
  retain_for: 3 years

