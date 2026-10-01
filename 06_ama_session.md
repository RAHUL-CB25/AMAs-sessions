## AMA – Questions & Answers

1. **What is the difference between SQLite and PostgreSQL?**  
   SQLite is a lightweight, file-based database, while PostgreSQL is a powerful client-server relational database designed for larger and more complex applications.

2. **What is the rsync command?**  
   rsync is used to efficiently copy and synchronize files or directories between locations, locally or over a network.

3. **How do you create a branch, switch to a branch, and merge a branch?**  
   Use `git branch branch_name` to create, `git switch branch_name` to switch, and `git merge branch_name` to merge a branch.

4. **How do you change the previous commit message?**  
   Use `git commit --amend -m "new message"` to change the message of the most recent commit.

5. **In Django, what does it mean that a QuerySet is lazy?**  
   A QuerySet does not execute the database query immediately; it executes only when its results are actually needed.

6. **What is the difference between a Python module and a Python class?**  
   A module is a Python file containing code such as functions, variables, and classes, while a class is a blueprint used to create objects.

7. **Explain MVT in Django.**  
   MVT stands for Model, View, and Template. Model handles data, View handles business logic, and Template handles the user interface.

8. **What are the field types in Django models?**  
   Django provides fields such as CharField, IntegerField, BooleanField, DateTimeField, EmailField, TextField, ForeignKey, and ManyToManyField.

9. **What is the purpose of request in a Django view?**  
   `request` contains information about the incoming HTTP request, such as method, data, headers, user, and session information.

10. **What is the purpose of the Meta class?**  
    The Meta class provides additional configuration for a Django model, such as ordering, table name, constraints, and verbose names.