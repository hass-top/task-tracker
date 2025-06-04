# task-tracker

it's a simple task tracker in the cli that work with json with CRUD to make my journy look fun 

# how it's work 
```php 
    echo "Usage:\n";
./task-cli add \"Description\"\n";
./task-cli update <id> \"New description\"\n";
./task-cli delete <id>\n";
./task-cli mark-in-progress <id>\n"
./task-cli mark-done <id>\n";
./task-cli list \n"; 
./task-cli list [status]\n";
```

# Make it Executable (Optional)

To run it like a native command (e.g., task-cli), do:
```
chmod +x task-cli
mv task-cli /usr/local/bin/task-cli
```
Now you can run it with:
```
./task-cli add "Buy groceries"
```

Add a Task
```
./task-cli add "My task description"
```
With optional parameters:
```
./task-cli add "Finish report" --priority=high --sort=2025-06-10
```
✏️ Update a Task
```
./task-cli update <id> "Updated description" --priority=low --sort=2025-06-20
```
❌ Delete a Task
```
./task-cli delete <id>
```
🔄 Mark Task as In Progress
```
./task-cli mark-in-progress <id>
```
✅ Mark Task as Done
```
./task-cli mark-done <id>
```
📋 List All Tasks
```
./task-cli list
```

🎯 List Tasks by Status
```
./task-cli list todo
./task-cli list in-progress
./task-cli list done
```
$ ./task-cli list
--------------------
ID: 1
Description: Buy groceries
Status: todo
Created At: 25-06-04 19:30:00
Updated At: 25-06-04 19:30:00
Priority: medium
Due: 2025-06-10
--------------------
