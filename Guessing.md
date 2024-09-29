```mermaid
flowchart TD
A[[Start]] --> B[[Number = 4]]
B --> C[["Guess the number"]]
C --> D[[**guess** = input]]
D --> E[[Guess == number?]]
E ---> |True| F[["Correct"]]
E ---> |False| G[["incorrect"]]
F --> H[[End]]
G --> H
