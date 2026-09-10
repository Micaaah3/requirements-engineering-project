# Week 1 - Initial Discovery
## 1. Facts
 It is for a college, staff, students and IT may use it.
 The current system for bookings is confusing and may lead to double bookings.
 It's hard to tell whether equipment is available or not.
 Equipment may not be returned when expected.
 Contact details about the equipment is vague/hard to find.
## 2. Assumptions
 There is no current inventory keeping
 There is no way for people to know whether what equipment is available or when it may be available.
 There is no list of equipment that can be rented out; I.e a list of all possible equipment that is owned by the college.
 The staff need an automated system to remind people to bring equipment back in once it's over due.
## 3. Unknowns
 How will the staff and students be able to use this? i.e App? Website? Something else?
 Is there any incentives to return equipment before or on the due date?
 Is there any way for the staff to remind people to return the equipment?
 Is there any need for any equipment maintanence?
## 4. Stakeholders
 Staff, i.e receptionists. Manually deal with bookings if in person
 Maintainence/IT, able to get equipment to repair/replace it
 Students,  easy viewing of booked equipment and accessible methods of booking
 Administration, the ability to put up/remove equipment.

 Maintenance may take it upon themselves to replace/repair goods then inform Administration
 Whereas Administration may want to inform Maintenance about the damaged equipment first.
## 5. Goals
 It should make accessing booking information easy for everyone; Booked equipment should be at a bottom of the list for example
 It should reduce the likely-hood of missing equipment; Reminders should be sent out, incentives to return it should be enforced.
 It should make adding more equipment easier for staff. Have an admin system for staff to add more equipment.
## 6. Scope 3-4 likely part of problem, 2-3 can not currently assume
### In scope
 Authentication, how or if the user should require authentication to rent equipment.
 Ensuring everything is easy to access within less than 3-4 clicks.
 How should reminders be sent out to people?
### Out scope
 What's the maximum duration equipment should be let for, if any?
 Are there any cases of multiple of the same piece of equipment? If so, should we merge them or leave them separate?
## 7. Candidate Requirements 4 functional 2 non functional
### Functional
The system should ensure a connection to the internet in order to book equipment
The system shall check if a piece of equipment is already booked before letting any new bookings through
The system shall allow authenticated staff to dynamically update equipment information/add new information/equipment
The system shall prevent any unauthenticated users from changing/booking equipment
### Non-functional
The system should ensure a fast load time.
The system should connect with any existing authentication method.
## 8. Requirement Surgery 
### R1: "The system should be easy to use."
This is generally vague, what may be easy to one may be hard for another. We can measure this by seeing how long it takes for a user
to find a specific thing.
Could be written like: "The system should have information clearly laid out, with everything being accessible within at least 3 clicks."
### R2: "The system should be secure"
Again vague, what defines secure? How far should security go? Should we have a thousand layers of security, and blow our entire budget on security research?
Should we have a backup of the data or would that add too much cost? Testing could be thorough by hiring an outside cybersecurity team, or we could do quick
testing by having users do activities they should not be able to do; accessing admin pages, overwriting bookings, deleting bookings, etc
Rewrite it as: "The system should ensure that users do not have access to activities they do not have permission for; I.e a student adding new equipment."
## 9. Reflection
