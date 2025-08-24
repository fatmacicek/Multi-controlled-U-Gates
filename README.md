**<ins> Summary </ins>**

This project is about implementations of a multi-controlled $U$ gate, denoted by $C^n U$, for a general unitary matrix $U$ in $U(2).$ 

I wrote a Qiskit code for implementing $C^n U$ for general $n$. This is done by a function named <em>multi_controlled</em> whose inputs are a positive integer $n$ together with a numpy array $U$ that is to satisfy the conditions of a unitary matrix. The output is a circuit which implements the gate $C^n U$. The discussion is based on Corollary 4.2 and Figure 4.10 of Nielsen and Chuang's book <em>Quantum Computation and Quantum Information</em>. I also added brief a survey of other implementations.  

This was a mini project that I completed during the Quantum Computing Bootcamp at [the Erdős Institute](https://www.erdosinstitute.org/) during summer 2025. The project was proposed by the course lead [Dr. Ákos Nagy](https://akosnagy.com/).
