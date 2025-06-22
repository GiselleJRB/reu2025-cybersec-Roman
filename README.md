<!DOCTYPE html>
<html lang="en">
<body>
    <header>
        <h1>reu2025-cybersec-Roman</h1>
    </header>
    <section>
        <h2>Project Title</h2>
        <p>
            Securing Dynamic Robotic Behavior in Unpredicted Environments: Enhancing Trust through Adaptive Learning and Cyber Defense
        </p>
    </section>
    <section>
        <h2>Student Name</h2>
        <ul>
            <li>Giselle Roman</li>
        </ul>
    </section>
    <section>
        <h2>Mentor Name</h2>
        <ul>
            <li>Dr. Yugyung Lee</li>
        </ul>
    </section>
    <section>
        <h2>Project Summary</h2>
        <p>
            As autonomous robots continue to operate in complex and unpredictable environments, their ability to adapt in real-time scenarios is important. By exploring learning-based methods like reinforcement and imitation learning, this project aims to optimize robotic behavior by developing both adaptive learning and highly secure cybersecurity.
        </p>
    </section>
    <section>
<section>
    <h2>Tools and Models</h2>
    <ul><li>Hugging Face Transformers (LLaVA): For explainability of robot decisions</li></ul>
    <ul><li>Adversarial Robustness Toolbox (ART): To simulate adversarial inputs and test defense methods</li></ul>
    <ul><li>Scikit-learn: For implementing and comparing machine learning-based detection methods</li></ul>
    <ul><li>Quantum Toolkit (Qiskit): Future integration for quantum-enhanced decision support</li></ul>
    <ul><li>Perspective API: trust-aware feedback</li></ul>
    <ul><li>OpenAI Gym / Gymnasium: RL-based simulation for adaptive robot control</li></ul>
    <ul><li>Stable-Baselines3 (PPO, CPO): Baseline reinforcement learning models</li></ul>
    <ul><li><b>DOcplex:</b> Used for formulating and exporting QUBO models in optimization tasks</li></ul>
    <ul><li><b>NetworkX:</b> Used to create and manipulate the synthetic knowledge graph</li></ul>
    <ul><li><b>Matplotlib:</b> For plotting success rates and learning trends from RL agents</li></ul>
</section>
    <section>
        <h2>Setup Intructions</h2>
        <p>For running the notebooks:</p>
        <ul><li>Install dependencies: pip install gymnasium stable-baselines3 matplotlib scikit-learn qiskit</li></ul>
        <ul><li>Open any notebook in the notebooks/ folder in Jupyter or Google Colab</li></ul>
        <ul><li>Outputs and screenshots will appear in the outputs/ folder after running</li></ul>
    </section>
    <section>
        <h2>Progress Summary</h2>
        <ul>
            <li>Generated a synthetic knowledge graph with agents, tasks, and anomalies. Focused on modeling task allocation relationships for use in quantum optimization.</li>
            <li>Practiced DP problems (LIS, 0/1 Knapsack, Edit Distance) and linked them to robot sensor log analysis, trust score trends, and task prioritization.</li>
            <li>Used Gymnasium's FrozenLake-v1 to train a Q-learning agent. Evaluated performance with Q-table and analyzed how the robot learns in uncertain environments.</li>
            <li>Extracted a subgraph (3 agents and 3 tasks) and built a QUBO task assignment problem using Qiskit Optimization.</li>
            <li>Continued literature review on graph anomaly detection (GAD) using GNNs and started reproducing one baseline.</li>
        </ul>
    </section>
</body>
</html>

