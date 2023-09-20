# Kotlin Fundamentals

> Inspired from Kotlin Education, for more information view [here](https://kotlinlang.org/education/)
>
> <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
---

## Syllabus  

### Prerequisites

- Intro to Java 
- Introduction to Programming 

### Duration

- 1 semester or 12 weeks 

### Preperations Recommendations 

- IntelliJ Idea Community 
- IntelliJ Student and Educator License can be applied to 

### Descriptions 

Join us on a journey through the powerful Kotlin programming language, utilized in diverse domains like web development, Android, and data science. Experience comprehensive modules and hands-on training to master core concepts such as data types, control flow, variables, object-oriented programming, and functions. You'll also delve into advanced topics, including exception handling, collections, generics, and cutting-edge Kotlin features like null safety, coroutines, and extension functions. Finally, get a deep dive into building systems with Gradle and explore the inner workings of the Kotlin K2 compiler. Let us take your programming skills to the next level together.

### Goals  

- **Mastery of Kotlin**: The primary goal is to enable students to become proficient in Kotlin, understanding its syntax, features, and best practices.

- **Practical Problem-Solving**: Equip students with the ability to apply Kotlin effectively to solve real-world software development challenges, preparing them for practical work in various domains.

- **Programming Fundamentals**: Build a strong foundation in programming fundamentals, including data types, variables, control flow, and functions, ensuring students are well-grounded in the basics.

- **Object-Oriented Proficiency**: Foster expertise in object-oriented programming principles and practices, enabling students to design and build software systems using Kotlin.

- **Exception Handling**: Teach students how to handle exceptions gracefully, enhancing the robustness and reliability of their software.

- **Collections and Generics**: Provide in-depth knowledge of working with collections and generics, allowing students to manipulate and manage data structures effectively.

- **Advanced Kotlin Features**: Introduce students to advanced Kotlin features such as null safety, extension functions, and coroutines, enhancing their ability to write efficient and safe code.

- **Build Systems**: Familiarize students with build systems, with a focus on Gradle, to help them manage complex projects efficiently.

- **Compilation Techniques**: Explore compilation techniques and the inner workings of the Kotlin K2 compiler, deepening students' understanding of how code is transformed into executable software.

- **Hands-On Experience**: Ensure that students gain practical, hands-on experience through coding assignments, projects, and exercises to reinforce their learning.

- **Versatility**: Empower students to use Kotlin in a versatile manner, whether for Android app development, web development, data science, or other application domains.

- **Critical Thinking**: Encourage critical thinking and problem-solving skills by presenting students with complex coding challenges and encouraging creative solutions.

- **Self-Reliance**: Foster self-reliance and the ability to explore and adapt to new tools and technologies as they continue their journey in software development.

- **Industry Readiness**: Prepare students to be industry-ready by exposing them to industry-standard practices and coding conventions.

- **Continuous Learning**: Instill a passion for continuous learning, as the field of software development is ever-evolving, and adaptability is key to success.

### Content 


| Week # | Assignment #  | Topic                               |
| :----: | :-----------: | :---------------------------------- |
|   1    |               | Introduction to Kotlin              |
|   2    |       1       | Object-Oriented Programming         |
|   3    |               | Generics                            |
|   4    |       2       | Collections                         |
|   5    |               | Functional Programming              |
|   6    | Midterm (1-5) | Build Systems                       |
|   7    |               | Parallel and Concurrent Programming |
|   8    |       3       | Asynchronous Programming            |
|   9    |               | JVM and K2 Compiler                 |
|   10   |       4       | Exceptions                          |
|   11   |               | Testing                             |
|   12   |  Final Exam   |

Material provided by Kotlin Education can be viewed in their [Google Drive](https://drive.google.com/drive/folders/1nN3LuyEfmBaSDZpnb4VA9kDuLakmVXH1) or seen in the `material/KotlinFundamentals` folder. 

### Grade Breakdown 
| Type                 | Weight |
| -------------------- | ------ |
| Assignments (x4)     | 20%    |
| Quizzes (each topic) | 10%    |
| Midterm              | 30%    |
| Final Exam           | 40 %   |


### Assesment Plan 

#### Quizzes 
- Multiple choice 

#### Assignments 

Assignment 1: Kotlin Essentials (topics 1 & 2)

Description:
In this assignment, you will explore the fundamental features of the Kotlin programming language. You will write simple Kotlin programs to demonstrate your understanding of basic concepts.

Tasks:

1. Write a Kotlin program that prints `"Hello, Kotlin!"` to the console.
2. Create a Kotlin function that calculates the area of a rectangle given its length and width. Test the function with different values.

3. Define a Kotlin class representing a 'Person' with properties for name, age, and email. Create an instance of the class and initialize its properties.

---

Assignment 2: Building a Task Manager (topics 3 & 4)

Description:
In this assignment, you will apply your knowledge of Kotlin collections to create a simple task manager. You will use collections like lists and maps to manage tasks and their properties.

Tasks:

1. Create a Kotlin data class called Task with properties for task ID (an integer) and task description (a string).
2. Implement a Kotlin program that manages a list of tasks using a MutableList. Include functions for adding, updating, and deleting tasks.
3. Extend your task manager to categorize tasks by priority using a map. Allow users to set and change task priorities (e.g., High, Medium, Low).
4. Write a function to display all tasks, sorted by priority.

---

Assignment 3: Parallel Data Processing with Kotlin Coroutines

Description:
In this assignment, you will explore the power of functional programming and parallelism in Kotlin using coroutines. You will work with a dataset and leverage Kotlin's functional programming features to process data concurrently, improving performance.

Tasks:

1. Download a sample dataset (e.g., a CSV file) containing a list of records (e.g., sales transactions, sensor readings, or any dataset of your choice).
2. Write a Kotlin program that reads and parses the dataset into a list of data objects.
3. Implement a functional transformation on the dataset, such as filtering, mapping, or aggregating the data using Kotlin's higher-order functions (e.g., map, filter, reduce).
4. Rewrite the transformation from task 3 using Kotlin coroutines to perform the operation concurrently on multiple records.
5. Measure and compare the execution time of the sequential and concurrent transformations for a significant dataset. Analyze and present the results.

--- 

Assignment 4: Asynchronous File Processing and Exception Handling

Description:
In this assignment, you will explore asynchronous programming in Kotlin, delve into the Java Virtual Machine (JVM) environment, and practice exception handling. You will create a program that reads and processes data from files asynchronously while handling exceptions gracefully.

Tasks:

1. Create a Kotlin program that reads data from multiple text files (at least three) asynchronously. Each file may contain lines of data.
2. Implement asynchronous processing to analyze and transform the data (e.g., counting words, extracting specific information, or any data processing task).
3. Handle exceptions that may occur during file reading, data processing, or asynchronous operations. Use Kotlin's exception handling mechanisms effectively.
4. Write the processed data to an output file.

Additional Tasks (Optional):  

5. Implement error logging to capture and log exceptions that occur during file processing.

6. Explore and discuss how the Kotlin code is compiled into Java bytecode and executed on the JVM.

---
### Learning outcomes 

- Use the unique features of Kotlin to write readable, optimal and robust code. 
- Use Kotlin to solve practical problems in software development 
- Be able to use and understand the JVM and K2 compilers

### Recommended Materials 
- Roman Elizarov, Svetlana Isakova, Sebastian Aigner, and Dmitry Jemerov: [Kotlin in Action](https://www.manning.com/books/kotlin-in-action-second-edition), Second Edition, Manning Publications, 2022.
- [Kotlin Documentation](https://kotlinlang.org/docs/home.html)
- [Kotlin Onboarding Introduction](https://plugins.jetbrains.com/plugin/21067-kotlin-onboarding-introduction)
- [Kotlin Onboarding Object Oriented Programming](https://plugins.jetbrains.com/plugin/21913-kotlin-onboarding-object-oriented-programming)