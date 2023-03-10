<h1>Quantum-Mess</h1>
<p>This repository is a collection of circuits which I have built from what I have understood by reading different materials available online and from books. I have followed Qiskit's Free Online Textbook and a few books: Qiskit Pocket Guide and Quantum Computing for Computer Scientists (by Noson Yanofsky). Feel free to open issues and discuss about better ways to implement what I have implemented.</p>
<h3><b><u>Contents:</u></b></h3>
<ul>
<li>Base Gates
<ul>
<li>and</li>
<li>not</li>
<li>or</li>
<li>xor</li>
</ul>
</li>
<li>Full Adder</li>
<li>Half Adder</li>
<li>Swap</li>
</ul>

<h3><u>Base Gates :</u></h3>
<br>
<p>This folder is a collection of the basic gates used in classical computers, the only difference being that they can be used on an ideal Quantum Computer. These gates have been made using matrices and no special pre-existing quantum gates are used for their formation.</p>
<ul>
<li><code>and</code><p>This gate does the normal and operation. It is same as the Toffoli Gate used in Quantum Computation.</p></li>
<li><code>not</code><p>This gate does the normal not operation. It is same as the X Gate used in Quantum Computation.</p></li>
<li><code>or</code><p>This gate does the normal or operation. The gate that is created here as a control bit as well. When the control bit is in |0> state, the output of the or gate is normal. However, when the control bit is in |1> state, the output is the inverse of the output which would be when the control bit is in state |0>.</p></li>
<li><code>xor</code><p>This gate does the normal xor operation. It is same as the CX Gate used in Quantum Computation.</p></li>
</ul>

<h3><u>Full Adder :</u></h3>
<p>This folder has the code for creating a Full Adder using Quantum Gates and using the 'or' gate created in the 'Base Gates' folder. This circuit has three inputs: input1, input2 and carry. It has two outputs, the LSB and the MSB. The folder contains both the Python code and the corresponding circuit's image and the histogram plot.</p>

<h3><u>Half Adder :</u></h3>
<p>This folder has the code for creating a Half Adder using Quantum Gates. This circuit has two inputs and gives two outputs, one is the LSB and the other is the MSB. This folder contains both the Python code and the corresponding circuit's image and the histogram plot.</p>

<h3><u>Swap :</u></h3>
<p>This folder has the code for creating a swap operation on the two input qubits. Theb solution is using a matrix which was created keeping mapping in mind. The folder also contains the image of the circuit and the histogram plot of the circuit.</p>
