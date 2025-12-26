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
