# berVaz
berVaz is a basic module I wrote that allows one to either simulate or run the Bernstein-Vazirani algorithm on a real IBMQ quantum device of choice in only one line of code. 

There are two main functions:

sim(n), which simulates the berVaz algorithm on your computer using the qasm_simulator

and

run(n,device='ibmq_16_mealborne'), which pretty much runs the experiment on any IBMQ device you want (with ibmq_16_mealborne being the default)


Note that for berVaz to work, you need to have qiskit set-up and using it on jupyter notebook (preferrably). The run() function will only work if you dealt with the token and stuff beforehand.


Good luck and feel free to contact me for any reason!
