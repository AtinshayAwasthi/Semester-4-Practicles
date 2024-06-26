# Practicles Of 4th Semester

This repository consists all the practical files along with a description for each practical.

## Git-And-GitHub

### Content

[Install Git and create a repository](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Git-And-GitHub%20Practical/Experiment%201.1.pdf)

Installing Git prompts you to select a text editor. If you don’t have one, we strongly advise you to install it before installing Git. Our roundup of the best text editors for coding may help you decide.

[Creating branches with GitHub](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Git-And-GitHub%20Practical/Experiment%201.2.pdf)

Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. Use a branch to isolate development work without affecting other branches in the repository. Each repository has one default branch and can have multiple other branches. You can merge a branch into another branch using a pull request.

[Create and explore Pull request](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Git-And-GitHub%20Practical/Experiment%201.3.pdf)

Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary. Pull Requests are commonly used by teams and organizations collaborating using the Shared Repository Model, where everyone shares a single repository, and topic branches are used to develop features and isolate changes. Many open source projects on GitHub use pull requests to manage changes from contributors as they are useful in providing a way to notify project maintainers about changes one has made and in initiating code review and general discussion about a set of changes before being merged into the main branch.

[Editing a file and committing changes on GitHub](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Git-And-GitHub%20Practical/Experiment%202.1.pdf)

Git commits are snapshots of a project's files at specific moments, each identified by a unique SHA-1 hash. They include metadata like author details, timestamps, and commit messages. Commits form a directed acyclic graph, with branches pointing to specific commits. Clear commit messages are crucial for documenting changes, and commits should represent atomic changes for clarity and ease of management. Git offers tools for manipulating commit history, but caution is necessary to maintain a coherent project history, especially in collaborative settings.

## Design Analysis And Algorithm

### Content

[Binary Search](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/DesignAnalysisAlgorithm%20Practicals/Experiment-1/Experiment-1.txt)

Binary search is an efficient algorithm used to find a target value within a sorted array or list. It works by repeatedly dividing the search interval in half, eliminating half of the remaining elements each time based on whether the target value is greater or lesser than the middle element. This process continues until the target value is found or the search interval is empty. Binary search has a time complexity of O(log n), where n is the number of elements in the array. This logarithmic time complexity makes it significantly faster than linear search algorithms, especially for large datasets, as it quickly narrows down the search space with each iteration. However, it requires that the array be sorted beforehand, which can add time complexity of O(n log n) if sorting is necessary, though this sorting can often be done separately from the binary search itself.

[Quick Sort](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/DesignAnalysisAlgorithm%20Practicals/Experiment-2/Experiment-2.txt)

Quick sort is a sorting algorithm that follows the divide and conquer strategy. It selects a pivot element, partitions the array into two sub-arrays around the pivot (one with elements less than the pivot and the other with elements greater), and recursively sorts the sub-arrays. It has an average time complexity of O(n log n), making it efficient for large datasets. However, its worst-case time complexity is O(n^2) if poorly chosen pivots, such as the first or last element, consistently lead to unbalanced partitions.

[Strassen Matrix](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/DesignAnalysisAlgorithm%20Practicals/Experiment-3/Experiment-3.txt)

Strassen's algorithm is a method for multiplying matrices that reduces the number of arithmetic operations needed compared to the standard matrix multiplication algorithm. It accomplishes this by recursively breaking down the matrices into smaller submatrices and using clever combinations of additions and subtractions to compute the result. Strassen's algorithm has a time complexity of approximately O(n^2.81), which is an improvement over the standard O(n^3) complexity for large matrices. However, it has higher constant factors and overhead due to its recursive nature, so it may not always outperform the standard algorithm for smaller matrix sizes.

[Kruskal’s Algorithm](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/DesignAnalysisAlgorithm%20Practicals/Experiment-4/Experiment-4.txt)

Kruskal's algorithm is a greedy algorithm used to find the minimum spanning tree (MST) of a connected, undirected graph. It works by sorting the edges of the graph by their weights and then adding them to the MST one by one in increasing order of weight while ensuring that no cycles are formed. This is achieved by maintaining disjoint sets of vertices and including an edge in the MST only if it connects two disjoint sets. Kruskal's algorithm has a time complexity of O(E log E), where E is the number of edges in the graph, primarily due to the sorting step.

[Job Sequencing](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/DesignAnalysisAlgorithm%20Practicals/Experiment-5/Experiment-5.txt)

Job sequencing is a problem in combinatorial optimization where a set of jobs with associated deadlines and profits are to be scheduled for execution on a single machine to maximize the total profit earned. The objective is to select a subset of jobs that can be completed within their deadlines while maximizing the total profit. This problem is typically solved using greedy algorithms such as the earliest deadline first (EDF) or highest profit first (HPF), with time complexity depending on the chosen approach.

## Agile Practices

### Content

[Agile Development](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Agile-Practices%20Practicals/agile%201.pdf)

Agile Development is an iterative and incremental approach to software development. It prioritizes collaboration, flexibility, and customer feedback. Common practices include Scrum, Kanban, and continuous delivery.

[JUnit Testing](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Agile-Practices%20Practicals/agile2.pdf)

JUnit is a widely-used testing framework for Java that supports unit testing. It provides annotations for identifying test methods and assertions to validate expected outcomes. Automated testing is crucial for maintaining code quality and catching regressions.

[Testing Using Selenium](https://github.com/AtinshayAwasthi/Semester-4-Practicles/blob/main/Agile-Practices%20Practicals/agile3.pdf)

Selenium is a popular tool for automating web browser interactions, commonly used for web application testing. It enables the simulation of user actions and the verification of expected behaviors.

[Extreme Programming Scenario]()

Extreme Programming (XP) is a software development methodology emphasizing rapid delivery, flexibility, and customer satisfaction. In an Xtreme Programming scenario, developers work closely with customers, employing practices like pair programming, continuous integration, and frequent releases to ensure high-quality software.
