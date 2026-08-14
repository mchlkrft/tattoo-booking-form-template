# Tattoo Deposit Status Tracker Template

Intended reader: tattoo artists tracking deposits after a tattoo request has been reviewed and approved.

This template keeps the payment state connected to the right client, project, and held date. It does not replace a deposit policy or explain how to take deposits online. It gives you one record for what was requested, when it was due, whether receipt was verified, and what happened next.

Use it in a spreadsheet, table, notebook, or booking system. Keep the status words consistent so "the client says they paid" never gets mistaken for "the payment arrived."

## Deposit status definitions

| Status | Meaning | What changes it |
|---|---|---|
| Ready to request | The project is approved, but payment instructions have not been sent | Deposit request is sent |
| Requested | Amount, deadline, payment method, and policy were sent | Client reports payment, payment arrives, or deadline passes |
| Pending verification | The client says they paid, but receipt has not been confirmed in the payment record | Payment is verified or the issue is resolved |
| Received | The correct payment was verified and matched to the booking | Refund, credit, or later policy outcome |
| Expired | The deadline passed without verified payment and the hold was released | A new approval and hold, if offered |
| Refunded | Money was returned under the applicable policy or requirement | Final state, with the amount and date recorded |
| Credited | All or part of the deposit was moved to another agreed booking or date | Credit is used, changed, or refunded |

Do not use "paid" as a catch-all. A clear state is more useful when a client pays late, uses the wrong reference, sends the wrong amount, or needs a refund or credit later.

## Compact tracker

Copy this table and add one row per approved booking.

```text
| Booking ID | Client | Appointment | Amount | Requested | Due | Status | Verified | Reference | Outcome note |
|---|---|---|---:|---|---|---|---|---|---|
| ___ | ___ | ___ | ___ | ___ | ___ | ___ | ___ | ___ | ___ |
```

Use the booking ID or another stable project reference. Do not rely on an Instagram handle as the only way to connect money to a booking.

## Detailed deposit record

Use this version when you need more context than one table row can carry.

```text
Booking ID: ___
Client: ___
Project: ___
Appointment date and time: ___
Studio or city: ___

Deposit amount and currency: ___
What the deposit reserves: ___
Payment method: ___
Payment reference requested from client: ___
Policy version or link: ___

Requested at: ___
Payment deadline: ___
Client reported payment at: ___
Verified received at: ___
Verified amount and currency: ___
Payment record reference: ___

Current status: Ready to request / Requested / Pending verification / Received / Expired / Refunded / Credited
Hold released at, if applicable: ___
Refund or credit amount: ___
Refund or credit date: ___
Outcome note: ___
```

Keep access limited to people who need the record. Follow the retention, receipt, tax, and privacy requirements that apply to your setup and location.

## Update the record at each handoff

### After project approval

Create the record before sending payment instructions. Add the booking, client, amount, currency, policy link, held date, and deadline. Set the status to `Ready to request`.

### After sending the deposit request

Record the time it was sent and set the status to `Requested`. The client message itself belongs in the [tattoo booking reply templates](../docs/tattoo-booking-reply-templates.md), not in this tracker.

### When the client says they paid

Set `Pending verification` if the payment is not yet visible in the account or record you trust. A message or screenshot can help you search, but it does not confirm receipt by itself.

Check:

- Amount and currency
- Client name or payment reference
- Booking or project reference
- Payment state in the actual payment account
- Whether the payment arrived before the deadline

Do not accuse the client of sending a false screenshot when a transfer is simply delayed or unmatched. Record what you can verify and ask for the missing reference calmly.

### After receipt is verified

Record the verified time, amount, currency, and payment reference. Set the status to `Received`, then send the appointment confirmation from the authoritative [booking reply templates](../docs/tattoo-booking-reply-templates.md).

### When the deadline passes

Check the payment record once more. If nothing has arrived, set the status to `Expired`, record when the hold was released, and use the [expired deposit hold reply](../docs/tattoo-booking-reply-templates.md#release-an-expired-deposit-hold).

If a late payment arrives after the date was released, do not silently attach it to another appointment. Keep it unmatched while you contact the client, check current availability, and apply the agreed policy and any requirements that apply.

### After a refund or credit

Record the amount, currency, date, reason, and new status. If only part of the payment moved, record both the amount moved and the remaining balance so the next person does not have to reconstruct it.

## Illustrative tracker example

The entries below are fictional and only demonstrate how the states differ.

| Booking ID | Client | Appointment | Amount | Requested | Due | Status | Verified | Reference | Outcome note |
|---|---|---|---:|---|---|---|---|---|---|
| EX-101 | Client A | September 12 | EUR 80 | August 14 | August 16 | Received | August 15 | PAY-101 | Appointment confirmation sent |
| EX-102 | Client B | September 13 | EUR 80 | August 14 | August 16 | Expired | Not received | None | Hold released August 17 |
| EX-103 | Client C | September 20 | EUR 120 | August 14 | August 16 | Credited | August 15 | PAY-103 | Moved to the agreed October date |

The tracker shows the outcome without pretending the three clients followed the same path.

## Tracker checklist

- [ ] Every deposit is connected to a stable booking or project ID
- [ ] Amount and currency are recorded together
- [ ] Request time and deadline are specific
- [ ] The agreed policy version or link is attached
- [ ] Client-reported payment and verified receipt are different states
- [ ] Payment is matched by amount, currency, client, and reference
- [ ] Expired holds record when the date was released
- [ ] Late or unmatched payments stay unresolved until reviewed
- [ ] Refunds and credits record amount, date, reason, and remaining balance
- [ ] Client messages come from the one authoritative reply pack

If you want the deposit status attached to the booking instead of maintaining a separate tracker, [Inklee](https://inklee.app/tattoo-deposit-tool) keeps the request and deposit state connected.

## Related

- [Tattoo deposit policy template](../docs/tattoo-deposit-policy-template.md)
- [Tattoo booking reply templates](../docs/tattoo-booking-reply-templates.md)
- [Tattoo booking request review checklist](../docs/tattoo-booking-request-review-checklist.md)
- [Tattoo pricing and quote requests](../docs/tattoo-pricing-and-quotes-guide.md)
- [Tattoo cancellations, reschedules, and no-shows](../docs/tattoo-cancellations-reschedules-and-no-shows.md)
- [Pre-appointment client message template](pre-appointment-client-message-template.md)
