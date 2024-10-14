# Exercise-3-Flow-sequence-or-Flow-chart-using-Repeat-While-and-Do-While-loops


## Aim:
To automate the process of filling out a web form using the Application/Browser activity in UiPath Studio.

## Equipment Required:
UiPath Studio installed on your computer.
Web Browser (e.g., Chrome, Edge, with UiPath extensions installed).
Computer with:
Minimum 4 GB RAM.
Minimum 2.0 GHz CPU.
Windows operating system.
A Web Form to be automated.

## Procedure:
Open UiPath Studio:
Start a new project in UiPath Studio by creating a Blank Process.
# Declare Variables:
Create an integer variable counter and initialize it with 0.

# Designing the Flow Sequence:
Step 1: Add a Flowchart to the workspace from the Activities panel.

Step 2: Drag and drop the following control activities into the flowchart.

Repeat Loop: Repeat Number of Times activity"
In the log message  give the message ad "System.DateTime.Now.Hour<12  and Log level as Trace
Inside the loop, use Assign activity to increment counter = counter + 1.
Add a Log Message to print the value of the counter after each iteration.
While Loop: Condition: counter < 10.
Inside the loop, use Assign activity to increment counter = counter + 1.
Add a Log Message to print the value of the counter.
Do-While Loop:Inside the loop, increment counter = counter + 1 and print the value using Log Message.
Condition: counter < 15.
End Process:
Once all loops complete, use a final Log Message indicating that the process is done.

## Flowchart Breakdown:
Start → Initialize counter = 0.
Repeat Loop: Repeat 5 times → Increment counter and log the value.
Log message for time will be executed as per the given "System.DateTime.Now.Hour<12"
While Loop: While counter < 10 → Increment counter and log the value.
Do-While Loop: Increment counter, then check if counter < 15. Continue as long as the condition is true.
End Process → Log final message and terminate.

## Output:
![image](https://github.com/user-attachments/assets/3b0f1d3e-3387-4acb-af40-4b970655db9a)
![image](https://github.com/user-attachments/assets/b4cfeb35-84ff-4922-979f-e4cdc196bc19)
![image](https://github.com/user-attachments/assets/b21596b2-fdeb-454a-bd7e-169a0e8ff574)
![image](https://github.com/user-attachments/assets/77c0509d-b7a4-4d64-adbc-7030b8c09f6e)
![image](https://github.com/user-attachments/assets/637c0b1c-c3c2-4e1e-a14b-393462c6840f)
![image](https://github.com/user-attachments/assets/84b2d736-e0d0-4abe-8cc4-1b900567064f)
![image](https://github.com/user-attachments/assets/1b0a5306-320a-4558-a5d4-f18949661ab6)
![image](https://github.com/user-attachments/assets/80265a16-638f-4936-9325-2315c1760f38)
![image](https://github.com/user-attachments/assets/dd24eb18-09f1-4547-8243-3d5d51e6cf67)


## Result:
Thus, to Create a Flow sequence or Flow chart using Repeat, While and Do-While loops is executed succesfully using uipath studio
