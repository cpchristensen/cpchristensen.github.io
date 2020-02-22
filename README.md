## Carl Christensen's ePortfolio

### Professional Self Assessment
The Computer Science program here at SNHU has done a lot to help me develop and demonstrate my abilities as a software engineer. There are several auxillary skill sets that are very important when one is trying to enter the industry, such developing software with a security mindset, keeping client needs in mind during development, or working within a team in order to complete projects. I have taken several different courses that relate to these skills, and they have helped me to focus on certain types of development that I probably would not have without them.
One such example, working in a team environment, I experience while taking a course. The final project was to coordinate within a group to develop a calculator in the Java language. There were four of us in total and the experience pushed me to become comfortable with working on projects that are not just limited to myself. Another course I took focusing on Agile development methodologies helped me to reinforce not only the software development life cycle, but the concept of consistently having deliverables that can be shown to the client. This is an important skill to have in the workfoce. As for cybersecurity, not only have I taken classes specifically about secure coding, but also in most of my Computer Science courses security has been a priority in at least some capacity. The fact that it was so heavily enforce is very helpful because in this day and age writing secure and reliable code is more important than ever.

In addition to the Computer Science program as a whole, my ePortfolio for my Capstone has helped me to reinforce my skills within three major categories: Software   Design/Engineering, Data Structures and Algorithms, and Databases. I have taken a look at two projects that I completed during my Computer Science degree, and analyzed ways that I could enhance them in the aforementioned categories. These are three major areas which any programmer must be proficient in, and the courses I have taken with SNHU have given me a sizeable headstart towards becoming a good programmer. The two projects that I have revisted are a student grade viewer/editor for a teacher, and a RESTful API that performs standard CRUD operations on a Mongo database. I set about the task of finding specific ways to enhance these projects in the previously mentioned areas. Software Engineer/Data Structures and Algorithms were the primary focus for the grades program, while improving the usage of Databases was the focus for the REST api. I improved the grades program by implementing some better design choices relating to security and the way that the data is being packaged and stored. For the API, I went with the route of designing a front end for it, so that users could have a much easier time interacting with the database.

### Code Review
[Watch my code review here](https://media.githubusercontent.com/media/cpchristensen/cpchristensen.github.io/master/code-review.mp4)

### Enhancement 1: Software Design and Engineering
[Link to repository](https://github.com/cpchristensen/grade-viewer)

The artifact that I am enhancing in the software engineering and design category comes from a reverse engineering course I took serveral terms ago. The purpose of the assignment was to take a compiled executable, look at the corresponding assembly code, and then write the C code that it was compiled from. The program itself was a tool for professors to analyze and edit student’s grades. It had a simple credentials sysem fory verifying the professor trying to log in. This artifact is a good addition to my portfolio because it shows my proficiency with difficult skills and topics. I had to have a solid grasp of how programs operate “under the hood”, and this artifact does a good job at demonstrating that. The enhancements took this demonstration a step further by showing my ability to identify weaknesses in existing code and then develop solutions to addres the weaknesses. I used security practices for storing user credentials safely, and improved the design of the software by organizing adding the functionality of multiple different accounts, rather than just one.

Fortunately,  the enhancement development process has been smooth. I feel that the enhancements I have completed so far have met the objectives that I had wanted, specifically the objectives referring to using well-founded techniques and developing with a security mindset. The hashing strategy for storing user credentials and allowing support for multiple user passwords are both techniques that are common place in real-world scenarios. In addition to this, hashing passwords is a very common security feature of most log-in systems. Currently there are no updates on the expected outcome coverage plans.

The modification of this artifact has taught me a lot in the way of secure development. Before working on these enhancements, I had only a high-level view of how the password security process worked. However now that I have had the opporunity to implement the logic for myself, I feel like I have a mush more solid grasp of it. I would say the biggest challenge that I faced during the development of these enhacements would be the handling of strings in C. Strings are notoriously touchy in the C langauge, and all the file reading, password hashing, and string comparison left a lot of string work to be done. Fortunately though I was able to get through the development without too many scrapes and the code works just as I want it to.

### Enhancement 2: Algorithms and Data Structures
[Link to repository](https://github.com/cpchristensen/grade-viewer)

My artifact for the Data Structures and Algorithms enhancement is the same as the one I chose for the Software Engineering enhancement. It is the reverse-engineered grade changing program. I selected this artifact because I think it was a good showcase of the skills and knowledge I have when it comes to programming. There were many sub-problems that needed to be solved for these enhancements with further show my abilities, and so for these reasons I think this project is a good candidate for my portfolio.

The enhancements I have chose for this category were finding a good way to store the student and professor information, as well as determining the best algorithm for hashing the user’s passwords. As it was before, the data was being stored in a very unintuitive way, and there was no algorithm being used to hash the user’s credentials. My new system fixes both of thes problems. These enhancements first focus on making sure that the data is being stored efficiently: in this case that the student’s names and grads are being stored in an array of student structures, and professor data is being sotred in an array of professor structures.

These enhancements touched on three different course outcomes: problem solving using Algorithmic principles, using well founded techniques, and maintaining a security mindset during development. Algorthmic principles were an important aspect of these enhancements because I needed to understand why type of algoirtihm was best for the particular job of storing passwords. In this case, I chose SHA-1 which is a very common hashing algortihm used for security. This also feeds into the security mindset because when handling credential information such as passwords it is essential to always think about different possible security vulnerabilites. The data structures aspect of these enhancements demonstrates using well-founded techniques because I needed to modify the code to store the information in a much more intuitive way. The technique I chose of creating data types to store the information is very common and standard practice for many programs.

I learned the most from the algorithms portion of this enhancement, because I became more familiar with exactly how password security is handled. Understanding how a plaintext password is taken and then converted into ciphertext that is then stored/compared is a great skill to have for the future.

### Enhancement 3: Databases
[Link to repository](https://github.com/cpchristensen/crud-application)

This artifactwas originally a RESTful API that performed database queries based on predefined endpoints. The data that it operates with is stock data, but could work with other financial data. This artifact was created as a final project during my previous term for a Client/Server development course I took. My database enhancement for this artifact is to develop a web front-end for the API, so that users can have a more intuitive way of interfacing with the database, rather than having to create API calls in order to perform database operations.

I feel that this project is a strong component of my portfolio because it demostrates my ability to perform dataset operations with the popular database technology, MongoDB. In order to complete this artifact and its enhancement, I needed to be able to correctly identify how specific data in a dataset needed to be accessed and processed in order to be shown to a user, based on predefined logic. For the enhancement, I needed to focus on making the interface more approachable, so that the same functionality was present, just easier to access. I accomplished this through a Web GUI that supports the original 7 database operations from the REST API.

The course objectives that I met with this enhancement would be the “Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science” and the one covering the ability to use well founded techniques in order to find solutions to problems. This meets the first objective my attempting to build an interface that allows a diverse group of people (both technical and non-technical) to interact with a dataset for whatever business needs are necessary. The interface that I created allows these groups to work with data in a way that is more convenient than before. Web GUIs are a common and well-founded way of presenting information to a user, so this is how that objective is met. It may not specifically be “unique” however being able to create these inerfaces is a good skillset to have.
	
During the creations of this enhancement I learned a lot in regards to convenient ways of presenting information to a user. Especially in this use case, where that was a large volume of information that could potentially be queried against, I needed to make sure that the data could be easily viewed and understood by the user. This forced my to make considerations about how I wanted to present the information, as well as how the user to enter in their query parameters.


