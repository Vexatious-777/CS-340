# CS-340


I write programs that are maintainable, readable, and adaptable by whenever possible taking an object-oriented approach and leaving relevant dev comments, whenever the function is not self-explanatory (get/set). This ensures that if one of the "pieces" needs to be changed or adapted it should typically be obvious as to where the change needs to be made. This is shown here in my CRUD Module for this project. I was having issues with my first implementation of my Read function and later had to revisit it during this project's evolution. The solution involved adding a projection parameter and ensuring that even if it is not in use it is present, otherwise, the query to MongoDB exhibited strange behavior.

I approach a problem as a computer scientist by first looking at the specifications or requirements for a project and then building towards satisfying those needs. Within the context of this project, I began by receiving instructions to import a CSV file into a database and from there began building towards creating a web application that enables the end-user to query and filter all of the results that are held within the database. This involved a step-by-step approach that enabled an incremental build that tested each piece compartmentally until the final product was reached.

Computer scientists work to provide end-users with strong computer-based tools to assist with their daily needs, whether that be for business or pleasure or somewhere in between. We enable someone to work alongside computers without needing technical knowledge that is not needed for their day-to-day responsibilities and enable man and machine to work together in a more harmonious nature if I can wax poetic for a moment. For example, this project was meant to assist a fictional company called Grazioso Salvare, whose primary goal is to train rescue dogs. This project did so by enabling them to quickly filter through the Austin Animal Center for potential recruits from their stable of shelter animals.
