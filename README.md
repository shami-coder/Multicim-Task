# Multicim-Task
📌 Author
Muhammad Ehtisham Sarwar

🔌 De Morgan’s Law Circuits (Multisim)
📘 Overview

This project demonstrates the practical implementation of De Morgan’s Law using digital logic circuits designed in NI Multisim. Two equivalent circuits were created to verify the laws by showing that different logic gate configurations can produce the same output.

🧠 De Morgan’s Laws

De Morgan’s Theorems are fundamental rules in Boolean algebra:

First Law:
(A⋅B)
′
=A
′
+B
′
Second Law:
(A+B)
′
=A
′
⋅B
′

These laws show how AND and OR gates can be interchanged using NOT (inversion).

⚙️ Project Description
🔹 Circuit 1: (A · B)' = A' + B'
Implemented using:
AND gate followed by a NOT gate
Equivalent circuit using two NOT gates and one OR gate
Purpose: To verify that both configurations give identical outputs
🔹 Circuit 2: (A + B)' = A' · B'
Implemented using:
OR gate followed by a NOT gate
Equivalent circuit using two NOT gates and one AND gate
Purpose: To confirm equivalence of both expressions
🛠️ Tools Used
NI Multisim
Basic digital logic components:
AND, OR, NOT gates
Input switches
Output indicators (LEDs or probes)
🧪 Results
Both pairs of circuits produced identical truth tables.
This confirms the correctness of De Morgan’s Laws in digital circuit design.
📂 Files Included
Multisim circuit files (.ms14 or similar)
Screenshots of circuits (optional)
Truth tables (if added)
🚀 How to Use
Open the circuit files in NI Multisim.
Run the simulation.
Toggle input switches (A and B).
Observe and compare outputs for both circuit implementations.
🎯 Conclusion

This project successfully demonstrates that De Morgan’s Laws hold true in practical circuit design, and that logic expressions can be simplified or transformed without changing their functionality
