
# Group 5 MIST 4610 Group Project 1
A brief description of what this project does and who it's for

## Team Name:
62755 Group 5

## Team Members:
1. Armaan Bhasin [@armaanbhasin](https://www.github.com/taralbpatel)
2. Colby Cannizzaro [@colbycannizzaro](https://github.com/colbycannizzaro/MIST4610GroupProject1)
3. Evan Liu [@evanliu](https://www.github.com/RileyDoggett)
4. Theresa Nguyen[@ripleykurtz](https://www.github.com/RipleyKurtz)
5. Allison Ramirez Diaz [@sequoyethsimpson](https://www.github.com/quoysimpson)

## Scenario Description:
The UGA Department of Recreational Sports in the Division of Student Affairs wants to create a database that keeps track of information about the various sports sessions offered, the staff that run the activities, and the clients that wish to participate in these activities. 





## Data Model:
They wish to track the staff that work at Recreational Sports. They would like to store information about a staff member such as their name, email address, and phone number. A staff member can be an instructor or a fitness monitor for multiple classes. 

Each staff member also has at least one certification. The Department would like to store information about the certification name and a description of the certification. They would also like to know what certifications each staff member has obtained, the date it was obtained, and the expiration date for that certification.

The Department of Recreational Sports has a variety of classes to offer to clients at UGA. They would like to keep track of the types of activities offered for a session and the type of activity it is. They would also like to keep information about the start and end times for each session, the day of the week that it occurs on, the semester it is offered, and the location of the session. A session can be either a group or small group–a small group session is offered quarterly. Each session also has an instructor responsible for a specific class and a fitness monitor that overlooks a class. They also need to track how many clients attend each session.

In addition to group sessions, Recreational Sports also offers personal training sessions. Each session is personalized, so they would like to track the session date, start time, and end time for each session. An instructor can teach many personal training sessions and a client can sign up for multiple sessions.

The Department of Recreational Sports has many different clients that sign up for the activities that they offer. They would like to store information about a client such as their name, email, and phone number. Recreational sports are offered to all types of clients such as students, faculty, and alumni/UGA affiliates. Based on the type of client they are, a client will pay a different amount according to the package type they choose to purchase. For group, small group, and personal training sessions; there is a fixed price for the 3 standard types of clients.

On certain occasions, there is a discount that is applicable to group session packages. The Department of Recreational Sports offers an early semester discount that takes 25% the original price for all types of group packages. Halfway through the semester, the department also offers a 50% discount on the original price for all types of group packages.

![App Screenshot](https://github.com/colbycannizzaro/MIST4610GroupProject1/blob/25ca4b8bba8a1a8e8b96cb06319b74019f6be103/unknown.png)
## Data Dictionary:
## Queries:
USE ns_F25MIST4610_62755_Group5;

### Simple
1. List the class types offered

Insert Screenshot Here

This query provides a summary of the different activity categories that are offered by the Department of Recreation Sports, making it quick for a manager to observe.

2. List all client information - Theresa

Insert Screenshot Here

This query provides the necessary information about the clients of Recreation Sports that a manager would need to store.

3. List classes on a Tuesday in the afternoon (12pm–7pm)

Insert Screenshot Here

From a managerial perspective, this query helps identify which classes are scheduled in the afternoon on Tuesdays. Managers can use this to balance instructor workloads, allocate resources and ensure classes are spread evenly throughout the day.

4. List average package prices of clients that attend more than five classes a week.-Evan

Insert Screenshot Here

This query provides important information about clients who attend a higher number of classes per week.

### Complex

5. List the contact information including name, number, and email of all staff that have the ACE certification - Allison

Insert Screenshot Here

This query lists information for any staff member that has an ACE certification, which will be useful from a managerial perspective to identify specific staff members needed for classes requiring the ACE certification. This query can also be edited to identify staff members with other certifications. 

6. List all clients who have come to more than 5 group fitness class 

Insert Screenshot Here

This query is helpful from a managerial perspective to identify repeat clients for group fitness classes.

7. List all students who have taken a morning yoga class and morning cycle class before 

Insert Screenshot Here

From a managerial perspective, UGA Fitness and Wellness likes to see which classes are popular among students to know if they are worth having. This query returns the number of students that attended cycling classes on Thursdays.  

8. List the client who attended both yoga sessions on September 20th, 2025. - Colby

Insert Screenshot Here

From a managerial perspective, this query helps us identify highly engaged clients who attend multiple sessions of the same activity in one day. We wanted to see if there were any clients committed enough to attend two sessions in one day.

9. List the most active client's based of attendance who have attended to more than 3 classes 

Insert Screenshot Here

From a managerial perspective, UGA Fitness and wellness can use this query to identify highly active clients, as frequent attendance predicts stronger retention. This helps managers target loyalty efforts and encourage continued engagement.

10. List the instructor's name, the number of sessions, the date the session starts and the client's names based on the class being in Studio A

Insert Screenshot Here

This query can be used to identify information on a specific class session as long as the studio is A. This can also be changed to identify information on other studios.
















## Database Information:
Data Base Information: Name of the database: ns_F25MIST4610_62755_Group5
