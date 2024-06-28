# Database Management system for Hospitals

## Description

Built a hospital management system with a MySQL-backend database and integrated it to a GUI using python for a user-friendly experience  
It has functionalities to add, update, delete data points(like doctors, staff, patients, equipment, etc.) along with an efficient search mechanism and display analytics of the data  
The design for the same was made using ER(Entity-Relationship) diagram converting it finally to 3NF form to ensure a good database design  


## Project Phases

The project was done in 4 phases  

### Phase 1: Requirements Analysis and Design
We defined the problem statement and database specifications, identified key entities such as Patients, Doctors, Treatments, and Equipment, established relationships between these entities, and outlined the system's functional requirements.

### Phase 2: ER Diagram
We created a comprehensive Entity-Relationship (ER) diagram to visualize relationships and cardinalities between entities, accurately representing the system's complexity.

### Phase 3: Relational Model and Normalization
We transformed the ER diagram into a relational model and applied normalization techniques (1NF, 2NF, 3NF) to optimize the database structure, ensuring data integrity and minimizing redundancy.

### Phase 4: Implementation and Query Development
We developed SQL code for database creation and management, involves operations like insertions, updates, deletions, and complex retrievals. Functionalities for data analysis and reporting were also done.


## How to run

1. Prerequisites - Python and MySQL

2. Set up the database:
```sh
     mysql -u your_username -p < dump.sql
```

3. Run the Python script:
```sh
     python3 pythonscript.py
```

4. Prompts will be dispayed on the screen, follow the same to access the database

## Contributors
- Abhinav Raundhal
- Gargie Tambe 
- Yash Shinde
- Chetan Mahipal
