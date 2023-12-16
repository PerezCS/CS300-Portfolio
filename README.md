# CS300-Portfolio
**What was the problem you were solving in the projects for this course?**

These projects involved planning and developing a console program to load, manage, and display college course data, including their names, numbers, and prerequisites. The first challenge was to load and handle data that varied in size and complexity like courses with varying numbers of prerequisites. The second challenge was to weigh the strengths of each data structure before deciding on one that was most efficient and beneficial for this program. 

---

**How did you approach the problem? Consider why data structures are important to understand.**

Approaching the problem of data structure implementation involved carefully analyzing the nature of the data and the program's needs. Factors like data size, lookups, and sorting led me to decide on BSTs. Using the right data structure is important in order to create responsive programs that perform efficiently. It also can affect maintainability and future scalability.

---

**How did you overcome any roadblocks you encountered while going through the activities or project?**

One challenge was adapting logic for the different data structures. For example, sorting courses in a vector was straightforward, but for a hashmap, it required extracting and sorting keys separately. I addressed these challenges by modifying functions like SortCourseNumbersAlphanumerically to work with different structures, ensuring each function interacted correctly with the data structure. 

---

**How has your work on this project expanded your approach to designing software and developing programs?**

This project expanded my understanding of how data structures fundamentally shape software. For instance, the decision to use a hashmap or a vector directly influenced the design of functions like LoadCoursesFromFile and PrintCourseList, impacting overall program efficiency and scalability. It made me more aware of how software design involves not just fulfilling requirements, but also selecting the right tools and methods to do so.

---

**How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?**

The project helped me in writing maintainable, readable, and adaptable code by keeping the program modular. For instance, separating the logic for data loading, parsing, and user interaction into their own functions improved readability and adaptability. A benefit of this was that adjustments made for each data structure could be implemented easier without having to rewrite code from the ground-up for each data structure.
