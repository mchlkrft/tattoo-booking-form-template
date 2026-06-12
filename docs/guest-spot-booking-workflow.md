# Guest Spot Booking Workflow

Traveling tattoo artists deal with a workflow that does not fit normal scheduling tools. Each guest spot has its own city, dates, studio, and booking window. Requests come in months ahead, fall outside the trip dates, or stack up faster than a single trip can absorb. This guide covers a clean way to organize guest spot booking requests.

The default rule for guest spots: collect city and date context up front, so requests can be sorted and reviewed without untangling chat threads later.

## Why guest spots need their own workflow

- Requests come from multiple cities at once.
- Each trip has a fixed start and end date.
- The studio you guest at may not be your home studio.
- Demand for a city often outlasts the trip itself (waitlist, return trip).
- Travel logistics and tattoo logistics interact: how many sessions per day, how many days at the studio.

A general booking flow that ignores city and trip context will collect requests that cannot be reviewed cleanly.

## Suggested guest spot structure

Each guest spot should have the following organized data, even if you keep it in a notebook:

- City
- Dates (start and end)
- Studio name and address
- Booking window (when requests open and close)
- Open requests
- Approved bookings
- Waitlist count

## Example structure

### Berlin Guest Spot

- Dates: April 15 to April 22
- Studio: Studio Example, Berlin
- Booking window: Opens February 1, closes April 5
- Open requests: 14
- Approved bookings: 6
- Waitlist count: 8

### Amsterdam Guest Spot

- Dates: May 10 to May 14
- Studio: Studio Example, Amsterdam
- Booking window: Opens March 1, closes May 1
- Open requests: 9
- Approved bookings: 4
- Waitlist count: 3

### Barcelona Guest Spot

- Dates: June 20 to June 28
- Studio: Studio Example, Barcelona
- Booking window: Opens April 15, closes June 10
- Open requests: 22
- Approved bookings: 8
- Waitlist count: 12

## Guest spot request fields

Beyond a normal tattoo intake, a guest spot request needs:

- City (matching the trip you are running)
- Preferred date range within the trip window
- Flexibility on dates (firm date, or flexible across the trip)
- Travel context (only available certain days, etc.)
- Studio confirmation (some clients ask to know the studio first)

See [guest-spot-request-template.md](../templates/guest-spot-request-template.md) for a ready template.

## How to review guest spot requests

1. Filter by city.
2. Sort by date the request was submitted (oldest first), or by best fit (style, scope, pricing).
3. Approve the requests that fit the trip first.
4. Move strong requests that do not fit this trip onto the waitlist for the next visit.
5. Decline requests that do not fit the city or your style.

## When to close a city's booking window

Most guest spots have a clear cutoff:

- Two to four weeks before the trip starts is a common window.
- After the trip is fully booked.
- When you have enough waitlist depth for a follow-up trip.

Closing the window publicly helps you stop fielding new DM requests and concentrate on the trip.

## Checklist

- [ ] Each guest spot has its own city, dates, studio, and booking window written down
- [ ] Booking form captures city and preferred dates within the trip
- [ ] Requests are reviewed per city, not in one mixed inbox
- [ ] Waitlist demand is logged for future trips
- [ ] Booking window has a clear open and close date

## Related

- [Tattoo booking form fields](tattoo-booking-form-fields.md)
- [Guest spot request template](../templates/guest-spot-request-template.md)
- [Guest spot booking request example](../examples/guest-spot-booking-request-example.md)
- [Tattoo waitlist guide](tattoo-waitlist-guide.md)
