@ -1,51 +0,0 @@

# Bus Reservation System - README

## Introduction
This Bus Reservation System is developed in C language. It's designed to manage bus ticket bookings, providing various functionalities like seat reservation, bus rental, passenger management, and feedback collection.

## Features
- **Passenger Management**: Handling passenger details, ticket booking, and editing passenger data.
- **Bus Management**: Managing bus details including bus information, seat availability, and rental options.
- **Login System**: Secure access to the system.
- **Search and Sorting**: Features to search passengers by name or seat number and sort by name or age.
- **Feedback System**: Collecting feedback from passengers.
- **Timetable and Pricing**: Displaying bus timetables and ticket prices.

## Structure
The system uses several structures:
- `Tickets`: For passenger details.
- `bus`: For bus information.
- `login`: For login credentials.
- `feedback`: For storing passenger feedback.

## Functions
1. `display_in_detail`: Show passenger details.
2. `searchbyname`: Find passenger by name.
3. `searchbyseat`: Find passenger by seat number.
4. `sortbyname`: Sort passengers by name.
5. `sortbyage`: Sort passengers by age.
6. `booking`: Handle ticket booking.
7. `view_bus_list`: Show list of buses.
8. `login_sys`: Handle system login.
9. `cancel_seat`: Cancel a seat reservation.
10. `edit_data`: Edit passenger data.
11. `display`: Display passenger information in a list.
12. `timetable`: Show bus timetables.
13. `Rent_whole_Bus`: Rent an entire bus.
14. `feedback_from_pass`: Collect feedback.
15. `rent_per_seat`: Display rent per seat for buses.

## Usage
1. **Login**: Use predefined credentials (`username=user`, `password=code`) to log in.
2. **Main Menu**: Navigate through various options like viewing passenger details, booking tickets, renting buses, etc.
3. **Data Management**: Use the respective functions to add, edit, or view data.

## Installation
1. Clone the repository.
2. Ensure you have a C compiler installed.
3. Compile the program using your C compiler.
4. Run the executable to start the application.

## License
This project is open-sourced under the [MIT License](LICENSE.md).
