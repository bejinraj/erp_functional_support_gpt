# ERP Process Guide - Order-to-Cash (O2C) Module

Standard Operating Procedure (SOP) | ERP Systems | SAP SD / Finance

## Overview of Order-to-Cash

Order-to-Cash (O2C) covers the complete business cycle from receiving a customer order to collecting payment and closing the customer account transaction.

Process Flow: Customer Inquiry / Quotation → Sales Order Creation → Order Validation → Order Confirmation → Delivery Processing → Goods Issue → Billing and Invoicing → Payment Receipt → Customer Account Reconciliation.

## Process 1: Creating a Customer Quotation

Role: Sales Executive / Sales Operations Executive

Purpose: To provide the customer with product or service details, pricing, quantities, and delivery terms before an order is confirmed.

Steps:

1. Navigate to Sales and Distribution → Sales → Quotation → Create.
2. Enter the customer number or sold-to party details.
3. Enter the material or service, requested quantity, and validity period.
4. Verify the applicable pricing, discounts, and taxes.
5. Enter the requested delivery date and shipping terms, where applicable.
6. Review payment terms and other commercial conditions.
7. Check the quotation for accuracy and completeness.
8. Save the quotation and note the quotation number.
9. Send the quotation to the customer for review and acceptance.

Expected Result: The customer quotation is created and shared with the customer.

## Process 2: Creating a Sales Order

Role: Order Management Executive / Sales Operations Executive

Purpose: To record the customer's confirmed order in the ERP system and initiate order fulfillment.

Steps:

1. Navigate to Sales and Distribution → Sales → Sales Order → Create.
2. Enter the sales order type, such as a standard order.
3. Enter the sold-to party and ship-to party details.
4. Enter the customer's purchase order number and purchase order date, where applicable.
5. Enter the material or service code, order quantity, and requested delivery date.
6. Reference the approved customer quotation, if applicable.
7. Verify the customer pricing, discounts, currency, and payment terms.
8. Confirm the sales organization, distribution channel, and division.
9. Review the Bill-To and Ship-To details.
10. Check the order for missing information, blocks, and system warnings.
11. Save the sales order and record the sales order number.

Expected Result: The customer sales order is created and recorded in the ERP system.

## Process 3: Validating Sales Order Details

Role: Order Management Executive / Sales Order Validation Executive

Purpose: To ensure that the sales order contains accurate customer, material, pricing, agreement, and billing information before further processing.

Steps:

1. Open the sales order using the order number.
2. Verify the sold-to, ship-to, bill-to, and payer details.
3. Validate the customer's purchase order number and supporting documents.
4. Check the material description, quantity, unit of measure, and requested delivery date.
5. Verify customer-specific pricing and applicable discounts.
6. Validate contract, agreement, or licensing details where required.
7. Check payment terms, currency, tax details, and billing requirements.
8. Confirm that mandatory documents and approvals are available.
9. Identify and correct missing or inaccurate information.
10. Save the corrected order and document any outstanding issues.

Expected Result: The sales order is validated and ready for the next processing stage, subject to required approvals and system checks.

## Process 4: Checking Customer Credit and Order Blocks

Role: Credit Control Executive / Order Management Executive

Purpose: To identify credit restrictions and other system blocks that may prevent order processing or delivery.

Steps:

1. Open the sales order and review its overall processing status.
2. Check whether the order has a credit block or payment-related restriction.
3. Review customer credit status and outstanding receivables, where authorized.
4. Check for delivery blocks, billing blocks, or incomplete master data.
5. Identify the reason for each block using ERP status messages or reports.
6. Contact the credit control, finance, or master data team as appropriate.
7. Obtain the necessary approval or correction to resolve the block.
8. Remove or release the block only when authorized.
9. Recheck the sales order status to confirm that processing can continue.

Expected Result: The order is cleared for further processing or remains documented with the reason for the outstanding restriction.

## Process 5: Checking Product Availability

Role: Order Management Executive / Inventory Planning Team

Purpose: To verify whether the ordered quantity can be supplied within the customer's requested delivery timeline.

Steps:

1. Open the sales order in the ERP system.
2. Review the material, quantity, plant, and requested delivery date.
3. Check the material availability or Available-to-Promise (ATP) result.
4. Review the confirmed quantity and confirmed delivery date.
5. Identify any stock shortages or delayed supply.
6. Coordinate with inventory planning or the warehouse team if availability is insufficient.
7. Update the order schedule or propose an alternative delivery date when authorized.
8. Communicate any delivery changes to the relevant team or customer.
9. Confirm that the order's delivery schedule is updated correctly.

Expected Result: Product availability and the expected delivery schedule are confirmed.

## Process 6: Creating an Outbound Delivery

Role: Warehouse Executive / Shipping Executive

Purpose: To create the delivery document that supports picking, packing, and shipment of the customer's order.

Steps:

1. Navigate to Logistics → Shipping → Outbound Delivery → Create.
2. Enter the relevant sales order number or select eligible orders due for delivery.
3. Verify the customer, ship-to address, shipping point, and delivery date.
4. Review the material, quantity, and confirmed schedule lines.
5. Check delivery eligibility and any outstanding delivery blocks.
6. Create the outbound delivery document.
7. Record the outbound delivery number.
8. Share the delivery details with the warehouse or shipping team for fulfillment.

Expected Result: The outbound delivery document is created and ready for warehouse processing.

## Process 7: Picking and Packing Goods

Role: Warehouse Executive / Shipping Team

Purpose: To prepare the ordered goods for shipment according to the sales order and delivery document.

Steps:

1. Open the outbound delivery document.
2. Review the material codes, delivery quantities, and warehouse location.
3. Pick the required goods from the designated storage bins or locations.
4. Verify the picked quantity against the delivery requirement.
5. Record batch numbers or serial numbers where applicable.
6. Pack the goods according to shipping and handling requirements.
7. Enter packaging or handling-unit details if required.
8. Confirm that all required items are picked and packed.
9. Update the delivery document with the completed picking and packing status.

Expected Result: The goods are picked, packed, and ready for shipment.

## Process 8: Posting Goods Issue (PGI)

Role: Warehouse Executive / Shipping Executive

Purpose: To confirm that the goods have been dispatched and record the corresponding inventory and accounting movements.

Steps:

1. Open the outbound delivery document.
2. Verify the delivery quantity, picked quantity, and shipping details.
3. Confirm that all mandatory picking and packing activities are completed.
4. Check that no unresolved delivery blocks remain.
5. Verify the actual shipment details and dispatch readiness.
6. Post the Goods Issue in the ERP system.
7. Record the material document or goods movement reference, where applicable.
8. Confirm that the delivery status is updated to Goods Issue Posted.
9. Verify the inventory and relevant accounting updates, as applicable.

Expected Result: Goods Issue is posted, and the inventory records are updated according to the configured process.

## Process 9: Creating Customer Billing Documents

Role: Billing Executive / Order Management Executive

Purpose: To generate a customer billing document based on the applicable sales order, delivery, or service transaction.

Steps:

1. Navigate to Sales and Distribution → Billing → Create Billing Document.
2. Select the relevant billing due list or enter the reference document number.
3. Verify the sales order or outbound delivery reference.
4. Confirm the sold-to party, bill-to party, payer, and billing address.
5. Validate the billing quantity against the applicable order or delivery quantity.
6. Check pricing conditions, discounts, freight, taxes, and currency.
7. Verify the billing date, payment terms, and customer-specific billing requirements.
8. Resolve any billing blocks or incomplete data.
9. Create and save the billing document.
10. Record the billing document number and verify the document status.

Expected Result: The customer billing document is generated and recorded in the ERP system.

## Process 10: Validating Customer Invoice Details

Role: Billing Executive / Order Management Executive

Purpose: To ensure that the customer invoice is accurate, complete, and consistent with the approved commercial terms.

Steps:

1. Open the billing document using its document number.
2. Verify the customer name, billing address, and invoice reference.
3. Check the billed material or service, quantity, and unit price.
4. Validate discounts, surcharges, freight, and applicable taxes.
5. Verify the customer's purchase order number and contract or agreement reference, where required.
6. Check the Bill-To, Ship-To, and payer details.
7. Confirm the invoice date, currency, and payment terms.
8. Review the invoice for duplicate references or incorrect billing data.
9. Correct discrepancies through the authorized process.
10. Confirm that the billing document is approved for output and accounting posting, as applicable.

Expected Result: The customer invoice is validated and ready for issuance and financial processing.

## Process 11: Posting Billing to Finance

Role: Billing Executive / Finance Executive

Purpose: To transfer the billing transaction to Financial Accounting and record the customer's receivable and applicable revenue and tax entries.

Steps:

1. Open the billing document in the ERP system.
2. Review the billing status and accounting transfer status.
3. Verify the customer account, revenue account determination, tax codes, and company code.
4. Confirm that the required accounting period is open.
5. Check for errors preventing transfer to Financial Accounting.
6. Resolve missing account determination or master data issues through the appropriate team.
7. Release or post the billing document to accounting, as applicable.
8. Record the accounting document number.
9. Confirm that the accounting status is updated successfully.
10. Verify that the customer receivable is reflected in the financial records.

Expected Result: The billing document is transferred to Financial Accounting, and the customer receivable is recorded.

## Process 12: Sending Customer Invoices

Role: Billing Executive / Accounts Receivable (AR) Executive

Purpose: To deliver the invoice to the customer through the approved communication channel.

Steps:

1. Identify the completed and approved billing document.
2. Verify the customer's invoice delivery preference and contact details.
3. Confirm that the invoice PDF or electronic billing output is generated correctly.
4. Check the invoice number, amount, tax details, and payment due date.
5. Send the invoice through the configured channel, such as email, EDI, or a customer portal.
6. Confirm the output status in the ERP system.
7. Monitor failed email delivery or rejected electronic invoices.
8. Correct output issues and resend the invoice when authorized.
9. Retain the invoice transmission reference for tracking.

Expected Result: The customer invoice is successfully issued through the required channel.

## Process 13: Recording Customer Payments

Role: Accounts Receivable (AR) Executive / Finance Executive

Purpose: To record payments received from customers and apply them to the correct outstanding invoices.

Steps:

1. Navigate to Finance → Accounts Receivable → Incoming Payments.
2. Identify the payment received through the bank statement, remittance advice, or approved payment channel.
3. Verify the customer account, payment amount, currency, and receipt date.
4. Identify the invoice or invoices against which the payment should be applied.
5. Match the payment reference with the outstanding customer items.
6. Apply the payment to the correct invoice or invoices.
7. Investigate short payments, overpayments, deductions, or unidentified receipts.
8. Post the incoming payment in the ERP system.
9. Record the payment document number.
10. Confirm that the invoice status and customer open-item balance are updated correctly.

Expected Result: The customer payment is recorded and applied to the appropriate receivable.

## Process 14: Managing Overdue Receivables and Payment Follow-Up

Role: Accounts Receivable Executive / Collections Executive

Purpose: To monitor overdue invoices, follow up with customers, and reduce outstanding receivables.

Steps:

1. Navigate to Accounts Receivable → Customer Open Items or Aging Reports.
2. Identify invoices that are approaching or have exceeded their payment due dates.
3. Review invoice amounts, payment terms, and outstanding balances.
4. Check for disputes, credit notes, unapplied payments, or billing errors.
5. Contact the customer or relevant internal team to clarify the outstanding amount.
6. Send payment reminders according to the company's collection policy.
7. Record customer responses, expected payment dates, and follow-up actions.
8. Escalate unresolved disputes or significant overdue balances as required.
9. Update the collection tracker or case management system.
10. Monitor the invoice until payment is received or the issue is resolved.

Expected Result: Overdue receivables are tracked, follow-ups are documented, and outstanding payment issues are addressed.

## Process 15: Creating Credit Notes and Debit Notes

Role: Billing Executive / Accounts Receivable Executive

Purpose: To adjust customer billing when an approved price correction, return, underbilling, or other commercial adjustment is required.

Steps:

1. Receive the request for a credit or debit adjustment.
2. Review the original invoice, sales order, delivery, and supporting documents.
3. Identify the reason for the adjustment, such as a pricing error, returned goods, or an approved commercial change.
4. Verify the adjustment amount, tax implications, and customer details.
5. Obtain the required business or finance approval.
6. Navigate to the relevant billing adjustment process.
7. Reference the original billing document where applicable.
8. Enter the approved adjustment details and reason code.
9. Create and validate the credit or debit note.
10. Post the document to accounting and issue it to the customer as required.

Expected Result: The approved billing adjustment is recorded and reflected in the customer account.

## Process 16: Handling Sales Order and Billing Errors

Role: Order Management Executive / Billing Executive

Purpose: To identify and resolve errors that prevent sales orders, deliveries, or billing documents from progressing.

Steps:

1. Identify the affected sales order, delivery, or billing document.
2. Review the ERP status, error messages, incompletion log, or workflow history.
3. Identify the issue, such as missing customer data, incorrect pricing, blocked order status, or incomplete delivery.
4. Verify the relevant customer master, material master, order data, and supporting documents.
5. Coordinate with the appropriate team, such as master data, pricing, credit control, warehouse, or finance.
6. Obtain any required approvals before making changes.
7. Correct the relevant data or resolve the blocking condition.
8. Reprocess the affected transaction through the approved workflow.
9. Verify that the document has moved to the expected status.
10. Document the resolution and escalate recurring issues when necessary.

Expected Result: The transaction error is resolved, and the order proceeds to the next applicable stage.

## Process 17: Monitoring Order-to-Cash Transactions and Reports

Role: O2C Process Executive / Order Management Analyst

Purpose: To monitor order processing, billing completion, payment status, and service-level compliance.

Steps:

1. Navigate to the relevant ERP sales, delivery, billing, and receivables reports.
2. Review newly created sales orders and orders awaiting validation.
3. Identify orders blocked due to missing information or approvals.
4. Monitor orders pending delivery, picking, or Goods Issue.
5. Review billing due lists and billing documents awaiting processing.
6. Identify billing documents with accounting transfer or output errors.
7. Review overdue invoices, unapplied customer payments, and open receivables.
8. Track cases and transactions against the applicable SLA or expected completion time.
9. Follow up with the responsible teams to resolve pending transactions.
10. Escalate critical issues, recurring errors, and SLA breaches.
11. Prepare periodic reports covering order status, billing, exceptions, and receivables.

Expected Result: O2C transactions are monitored, exceptions are addressed, and delays in order fulfillment, billing, and payment collection are reduced.

## Important ERP Terms

| Term             | Meaning                                        |
| ---------------- | ---------------------------------------------- |
| O2C              | Order-to-Cash                                  |
| SAP SD           | Sales and Distribution                         |
| Sold-to Party    | Customer placing the order                     |
| Ship-to Party    | Customer or location receiving the goods       |
| Bill-to Party    | Party receiving the invoice                    |
| Payer            | Party responsible for payment                  |
| ATP              | Available-to-Promise                           |
| PGI              | Post Goods Issue                               |
| AR               | Accounts Receivable                            |
| Billing Document | ERP record of a customer billing transaction   |
| Credit Note      | Document reducing a customer's billed amount   |
| Debit Note       | Document increasing a customer's billed amount |
| SLA              | Service Level Agreement                        |
| UAT              | User Acceptance Testing                        |

## Key O2C Performance Indicators (KPIs)

| KPI                          | What it measures                                                 |
| ---------------------------- | ---------------------------------------------------------------- |
| Order Processing Time        | Time taken to process a sales order                              |
| Order Accuracy Rate          | Percentage of orders processed without errors                    |
| On-Time Delivery Rate        | Percentage of deliveries completed on schedule                   |
| Billing Accuracy             | Percentage of invoices issued without corrections                |
| Billing Cycle Time           | Time from the relevant fulfillment milestone to invoice issuance |
| First-Pass Order Completion  | Orders completed without rework                                  |
| On-Time Payment Rate         | Percentage of customer payments received by the due date         |
| Days Sales Outstanding (DSO) | Average time taken to collect customer receivables               |
| SLA Compliance               | Percentage of transactions completed within defined timelines    |

Note: The menu paths and transaction codes depend on the ERP version and company configuration. In SAP GUI, common examples include VA01 for sales order creation, VA02 for changing a sales order, VA03 for displaying a sales order, VL01N for creating an outbound delivery, VL02N for changing a delivery, VF01 for creating a billing document, VF03 for displaying a billing document, and F-28 for posting incoming customer payments. Actual usage may vary in SAP S/4HANA and Fiori environments.
