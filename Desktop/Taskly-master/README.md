# Taskly

During a productivity seminar i voluntarily attended at a previous company, I was introduced to an effective way of managing daily tasks based on urgency and importance. The concept really resonated with me as I often struggled to prioritize my workload. We all have tasks that are both important and urgent, as well as those that are important but not urgent, or vice versa. Categorizing tasks in this way made it much easier for me to figure out what to tackle first and what could be saved for later.

The idea of classifying tasks into four distinct categories struck me as an efficient approach:

- Urgent & Important  
- Urgent but Not Important  
- Not Urgent but Important  
- Not Urgent & Not Important  

I initially used Trello boards to manage my own tasks using this method. But over time, I realized that creating an application specifically for this could help others manage their time just as effectively. This led to the creation of Taskly—a simple task management app that allows users to categorize their tasks and prioritize them based on urgency and importance.

With Taskly, you can easily modify the code to suit your workflow needs. I aimed to keep it as straightforward as possible, using a clean code architecture to ensure flexibility and scalability.

Though there’s always room for improvement, Taskly is a solid first step, and I’m committed to updating it regularly to make it even better.

## Features

- All tasks where you can see all available tasks.
- Add new task or edit existing task.
- Filter task by task type which mentioned above.
- Swipe task to remove.



## Tools and Architecture

- [RiverPod](https://pub.dev/packages/riverpod) for the state management
- [sqflite](https://pub.dev/packages/sqflite) for Sqlite Database
- [uuid](https://pub.dev/packages/uuid) for generating unique task id
- [Scrollable positined list](https://pub.dev/packages/scrollable_positioned_list) 

For the architecture used clean code architecture approach to architect the structure.



