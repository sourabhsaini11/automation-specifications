# ONDC:TRV13 2.0.1 — Overview

## Summary

ONDC:TRV13 enables hotel bookings to flow through the ONDC network, connecting consumers directly to hotel properties. Hotels list their rooms, rates, and availability; travelers search, book, and manage reservations using ONDC-enabled applications, creating a standardized marketplace for accommodation transactions.

## Sector & Purpose

**Sector:** Hospitality and accommodation services.

**Problem Solved:** Hotels traditionally sell inventory through fragmented channels—direct websites, call centers, and third-party OTAs—each requiring separate integrations and commissions. ONDC:TRV13 standardizes hotel bookings on a single, open network. This allows hotels of any size to list inventory once and reach consumers across all ONDC-enabled buyer applications, while travelers access hotel options through a common set of discovery and booking flows.

## Real-World Actors

- **Consumers:** Travelers seeking accommodation who use ONDC-enabled mobile apps or websites to search, compare, and book hotels.
- **Hotels:** Accommodation providers (from boutique properties to chains) that list rooms, manage availability, set rates, and process bookings through ONDC-enabled backend services.

## Use Cases

- **Standard Hotel Booking:** Consumer searches for hotels by location and dates, views options with amenities and rates, selects a room, and completes a booking.
- **Real-Time Inventory Management:** Hotels push room availability updates using TTL-based catalog refresh, ensuring search results reflect current stock.
- **Buyer-Initiated Cancellation:** A consumer cancels their reservation and receives a refund according to the hotel's cancellation policy.
- **Merchant-Initiated Cancellation:** A hotel cancels a booking (e.g., due to overbooking or property closure) and notifies the consumer.
- **Booking Updates:** A consumer modifies their reservation (room type, check-in date, guest count) without canceling and rebooking.
- **Large Inventory Display:** Hotels with many properties or room types use pagination to serve search results efficiently.
- **Location-Based Search:** Consumers search hotels using GPS coordinates or city codes for precise geographic filtering.

## Key Concepts

- **Hotel Booking:** The transaction of reserving one or more rooms at a hotel for specified check-in and check-out dates.
- **Hotel Amenities:** Features and facilities offered by a property (e.g., WiFi, pool, parking, gym) that influence booking decisions.
- **Inventory & Availability:** Real-time room counts and rates that hotels update continuously to reflect occupancy and pricing.
- **Cancellation Policies:** Terms under which bookings can be canceled, including refund eligibility and deadlines.
- **Booking Updates:** Changes to confirmed reservations (dates, rooms, guests) made after the initial transaction.

## Example Scenario

A consumer traveling to a new city opens an ONDC-enabled travel app and searches for hotels near their destination using a map or city name. The app returns a list of available properties with room types, nightly rates, and key amenities. The consumer selects a 3-star hotel with good reviews, books a deluxe room for three nights, and receives a confirmation with payment details and cancellation terms. Two days later, the consumer's plans change; they log in and extend their stay by one night, and the hotel confirms the update. On the morning of checkout, the consumer cancels the last night under the hotel's flexible cancellation policy and receives a partial refund. Throughout this journey, the hotel managed its inventory on the ONDC platform, and the consumer used only their preferred ONDC-enabled app—no separate website visits or phone calls required.
