```mermaid
flowchart TD
A[[Start]] --> B[[Number = 4]]
B --> C[["Guess the number"]]
C --> D[[**guess** = input]]
D --> E[[Guess == number?]]
E ---> |True| F[["Correct"]]
E ---> |False| G[["incorrect"]]
G --> H
F --> H[[End]]

For each step I just typed the whole flowchart and clicked commit, if there was a problem (which I did have a problem with line 6 the most) I would fix it until it worked, and reviewing different ways from the flowchart documentation.
