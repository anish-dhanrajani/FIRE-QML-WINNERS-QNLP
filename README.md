**<h1>Quantum Natural Language Processing (QNLP): Solving Complex Language Problems with Quantum Computing</h1>**
**<h2>Overview</h2>**
Welcome to our Quantum Natural Language Processing (QNLP) project. In this repository, we are tackling one of the cutting-edge frontiers in technology: leveraging quantum computing to solve natural language processing (NLP) problems. This README provides a detailed yet simplified explanation of the problem we're addressing, how we are approaching it, and why this is exciting for both the NLP and quantum computing communities.

**<h2>The Problem</h2>**
Natural language processing (NLP) is about teaching computers to understand and interpret human language. However, as language is extremely nuanced and complex, many NLP models require substantial computational resources to process text efficiently. Classical (non-quantum) computers are limited in how fast and effectively they can handle these operations.

This is where quantum computing comes in. Unlike classical computers, which process data in binary (1s and 0s), quantum computers use qubits, which allow for much more complex operations. The hope is that by using quantum computing, we can speed up tasks and even solve problems that are currently too difficult for classical computers. In our case, we are looking at how quantum computing can enhance NLP tasks like sentence classification and meaning extraction.

**<h2>Why Is This Important?</h2>**
The potential of quantum computing lies in its ability to handle tasks exponentially faster than classical computers. In fields like cryptography, chemistry, and now NLP, quantum computers could provide the computational power necessary to make huge leaps forward. In particular, understanding human language better and faster has implications for everything from AI assistants like Siri or Alexa, to medical research, legal automation, and much more.

However, quantum computing is still in its early stages. Current machines are limited (referred to as Noisy Intermediate-Scale Quantum or NISQ computers), meaning they are not yet fully capable of showing dramatic improvements over classical systems for most tasks. Yet, exploring how quantum computers handle language can help us pave the way for future breakthroughs when more advanced quantum machines become available.

**<h2>Our Approach</h2>**
Our project explores QNLP through sentence classification tasks. Specifically, we map sentences into quantum data structures that quantum computers can process more naturally. We use several models for comparison:

<li>Bag-of-words: Ignores sentence structure, treating words as an unordered collection.</li>
<li>Word-sequence model: Considers word order without deeper syntactic structure.</li>
<li>Syntax-sensitive model (DisCoCat): Incorporates grammatical structure, producing linguistically sound representations.</li>

<h3>Quantum Circuit Configuration</h3>

<ol>
  <li>Quantum Ansätze: Configured with one qubit per sentence and noun types, one IQP layer, and three parameters for single-qubit words.</li>
  <li>Optimization Parameters: Configured for one run with three optimization iterations.</li>
  <li>Backend Compatibility: Supports both IonQ and IBMQ backends for experimentation with various quantum hardware.</li>
</ol>

<h3>Data Handling</h3>
<ol>
  <li>Datasets</li>
    <li>A 130-sentence dataset categorizing sentences related to food or IT for binary classification.</li>
    <li>A 105-phrase dataset from linguistics, predicting subject- or object-based clauses.</li>
</ol>

Data is loaded from files (mc_train_data.txt, mc_dev_data.txt, and mc_test_data.txt) and parsed into vocabulary dictionaries and sentence-label mappings for training, development, and testing.
**<h2>Key Takeaways from Our Work (TBD)</h2>**
TBD
**<h2>Getting Started</h2>**
<h3>Prerequisites</h3>
Ensure you have the following packages installed:
<ol>
  <li>discopy==0.3.5</li>
  <li>qiskit==0.25.4</li>
  <li>pytket</li>
  <li>pytket-qiskit</li>
</ol>

**<h2>Running the Project</h2>**
<ol>
  <li>Data Preparation: Load datasets by placing them in the specified directory, as referenced in the code.</li>
  <li>Quantum Backend: Configure your preferred backend (e.g., IonQ or IBMQ) in the code by setting the appropriate provider and backend.</li>
  <li>Execution: Run the main script or notebook to perform sentence classification and evaluate the model’s performance.</li>
</ol>

**<h2>References</h2>**
<ol>
  <li>https://github.com/CQCL/qnlp_lorenz_etal_2021_resources/tree/main</li>
</ol>
