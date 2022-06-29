# Room_Managment
This is a room slot booking django project that does the following;

Authenticate the user

Allow new users to sign up

Allow existing users to sign in

Users are of two types: Room Manager & Customer.

Room Manager defines the number of rooms available.

A Room Manager defines the time slots for which a room is available every day.

Time slots are constantly recurring.

A Customer can book a Room and a corresponding Time Slot, once booked, the Room cannot be booked by another Customer for that Time Slot.

Only an authenticated user can book or set rooms

A Customer can book a Room ‘x’ days in advance. Room Manager defines the number of days ‘x’.

Only Room Manager adds, deletes or changes his own number of Rooms and Time Slots.

A Customer can only view and delete only his own bookings

Room Manager can view a summary of all bookings, occupancies and occupant customer details.

The customer can see all of his own (past and future) bookings, occupancies and room manager.
