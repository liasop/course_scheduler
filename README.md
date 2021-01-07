# course_scheduler

This project is a database solution for a course scheduling task. Our implementation populates a database using a relational model implemented in SQLite that stores information on courses, professors, as well as key constraints, including non-overlapping courses and class time per week. Additionally, generate_prof_pairings and generate_sched have algorithms which generate schedules and a ranking system for optimal schedules.

Users, in our case department chairs, first upload their courses they plan to schedule as well as the professors teaching that semester. Examples of these excel sheets are CourseTemplate and ProfessorTemplate. Then, optimal schedules are shown given the constraints. Users can then download the schedule for their convenience. 
