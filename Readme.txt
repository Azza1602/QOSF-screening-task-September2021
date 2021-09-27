-This notebook was originally created for the screening task of the Quantum Open Source Foundation (QOSF) Mentorship Program (Cohort four, September 2021). Actually, QOSF is a fantastic project aiming to support and help with the development of open-source codes for the quantum computing community. For more information, great learning resources, and a list of supported projects, visit https://qosf.org/


-Task 2 : Prepare 4 random 4-qubit quantum states of your choice. 
Create and train a variational circuit that transforms input states into predefined output states. 
Namely if random state 1 is provided, it returns state |0011> if random state 2 is provided, it returns state |0101> if random state 3 is provided, it returns state |1010> if random state 4 is provided, it returns state |1100> What would happen if you provided a different state?
Analyze and discuss the results.

-Libraries used : 
PennyLane, Numpy and torch.


-Brief summary : 
To answer the question, I started by implementing a multiclass classification algorithm on 4 random 4-qubits states and then evaluating the accuracy.
After that, I tried to change the data used, which has decreased the accuracy.
At the end, I maked some explanations and suggested futur works that may improve the ressults.


I hope that everything would be clear.
