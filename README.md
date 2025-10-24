## QLab
Ove laboratorijske vežbe predstavljaju uvod u osnovne koncepte i algoritme kvantnog računarstva kroz programske zadatke u Python-u koristeći Qiskit biblioteku. Kreirajte i simulirajte kvantna kola, vizualizujte rezultate i primenite principe kvantne mehanike za rešavanje različitih problema.

### Kubiti
[Lab 01](Lab%2001%20-%20Bloch%20Sphere.ipynb): Blohova sfera<br>
[Lab 02](Lab%2002%20-%20Born%20Rule.ipynb): Demonstrating the Born Rule<br>

### Kvantna kola
[Lab 03](Lab%2003%20-%20Quantum%20Circuits.ipynb): Building Simple Quantum Circuits<br>
[Lab 04](Lab%2004%20-%20QRNG.ipynb): Quantum Random Number Generation with Hadamard Gates<br>
[Lab 05](Lab%2005%20-%20Bell%20state.ipynb): Creating and Measuring a Bell State<br>
[Lab 06](Lab%2006%20-%20Conditional%20Bell%20State%20Encoding.ipynb): Conditional Bell State Encoding<br>
[Lab 07](Lab%2007%20-%20Ramsey%20phase%20estimation.ipynb): Single Qubit Ramsey-like Phase Estimation<br>
[Lab 08](Lab%2008%20-%20Quantum%20Fourier%20Transform.ipynb): Quantum Fourier Transform<br>
[Lab 09](Lab%2009%20-%20Kitaev%20Phase%20Estimation.ipynb): Kitaev Phase Estimation
### Kvantni algoritmi
[Lab 10](Lab%2010%20-%20Deutsch–Jozsa%20algorithm.ipynb): Deutsch–Jozsa Algorithm<br>
[Lab 11](Lab%2011%20-%20Bernstein–Vazirani%20algorithm.ipynb): Bernstein–Vazirani Algorithm<br>
[Lab 12](Lab%2012%20-%20Simons%20algorithm.ipynb): Simon's Algorithm<br>
[Lab 13](Lab%2013%20-%20Grover%20Search%20Algorithm.ipynb): Grover Search Algorithm<br>
[Lab 14](Lab%2014%20-%20Grover%20SAT%20Solver.ipynb): Grover SAT Solver<br>

### Kvantne komunikacije
[Lab 15](Lab%2015%20-%20Superdense%20coding.ipynb): Superdense Coding<br>
[Lab 16](Lab%2016%20-%20Quantum%20Teleportation.ipynb): Quantum Teleportation<br>

### Kvantna kriptografija
[Lab 17](Lab%2017%20-%20Quantum%20authentication%20protocol.ipynb): Quantum authentication protocol<br>
[Lab 18](Lab%2018%20-%20Quantum%20Money.ipynb): Quantum Money

### Kvantno mašinsko učenje
[Lab 19](Lab%2019%20-%20Grover%20Classifier.ipynb): Grover Classifier<br>
[Lab 20](Lab%2020%20-%20Minimal%202-qubit%20QBM.ipynb): Minimal 2-qubit Quantum Born Machine (QBM)<br>
[Lab 21](Lab%2021%20-%203-qubit%20QBM.ipynb): 3-Qubit QBM for Coffee Shop Simulation<br>
[Lab 22](Lab%2022%20-%204-qubit%202-layer%20QBM.ipynb): 4-qubit 2-layer QBM for Traffic Simulation<br>
[Lab 23](Lab%2023%20-%202-Qubit%20VQC%20Classifier.ipynb): 2-Qubit Variational Quantum Classifier

### Google Colab uputstvo

These examples are fully compatible with **Google Colab**. To open them:

1. Open **[Google Colab](https://colab.google.com/)** and log in with a Google account.
1. Go to **File > Open notebook**
2. Select the **GitHub** tab
3. Enter the repository URL:
   ```
   Quantum-Computing-Institute-Cape-Town/QC-Labs
   ```

Before running the examples, install Qiskit by executing the following commands in the first cell:

```bash
!pip install qiskit
!pip install qiskit-aer
!pip install qiskit[visualization]
!pip install qiskit_ibm_runtime
```
