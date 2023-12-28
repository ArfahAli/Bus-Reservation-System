Bus Reservation System - README
Introduction
This Bus Reservation System is developed in C language. It's designed to manage bus ticket bookings, providing various functionalities like seat reservation, bus rental, passenger management, and feedback collection.

Features
Passenger Management: Handling passenger details, ticket booking, and editing passenger data.
Bus Management: Managing bus details including bus information, seat availability, and rental options.
Login System: Secure access to the system.
Search and Sorting: Features to search passengers by name or seat number and sort by name or age.
Feedback System: Collecting feedback from passengers.
Timetable and Pricing: Displaying bus timetables and ticket prices.
Structure
The system uses several structures:

Tickets: For passenger details.
bus: For bus information.
login: For login credentials.
feedback: For storing passenger feedback.
Functions
display_in_detail: Show passenger details.
searchbyname: Find passenger by name.
searchbyseat: Find passenger by seat number.
sortbyname: Sort passengers by name.
sortbyage: Sort passengers by age.
booking: Handle ticket booking.
view_bus_list: Show list of buses.
login_sys: Handle system login.
cancel_seat: Cancel a seat reservation.
edit_data: Edit passenger data.
display: Display passenger information in a list.
timetable: Show bus timetables.
Rent_whole_Bus: Rent an entire bus.
feedback_from_pass: Collect feedback.
rent_per_seat: Display rent per seat for buses.
Usage
Login: Use predefined credentials (username=user, password=code) to log in.
Main Menu: Navigate through various options like viewing passenger details, booking tickets, renting buses, etc.
Data Management: Use the respective functions to add, edit, or view data.
Installation
Clone the repository.
Ensure you have a C compiler installed.
Compile the program using your C compiler.
Run the executable to start the application.
License
This project is open-sourced under the MIT License.

