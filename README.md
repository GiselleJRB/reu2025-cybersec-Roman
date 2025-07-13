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
            As autonomous robots continue to operate in complex and unpredictable environments, their ability to adapt in real-time scenarios is important. This project aims to optimize robotic coordination by developing adaptive learning methods and robust cybersecurity measures. By modeling adversarial attacks and defense countermeasures, the work focuses on maintaining trust-aware, reliable task allocation even under cyber-physical threats.
        </p>
    </section>
    <section>
        <h2>Tools and Models</h2>
        <ul>
            <li>Hugging Face Transformers (LLaVA): For explainability of robot decisions</li>
            <li>Adversarial Robustness Toolbox (ART): To simulate adversarial inputs and test defense methods</li>
            <li>Scikit-learn: For implementing and comparing machine learning-based detection methods</li>
            <li>Quantum Toolkit (Qiskit): Future integration for quantum-enhanced decision support</li>
            <li>Perspective API: Trust-aware feedback</li>
            <li>OpenAI Gym / Gymnasium: RL-based simulation for adaptive robot control</li>
            <li>Stable-Baselines3 (PPO, CPO): Baseline reinforcement learning models</li>
            <li><b>DOcplex:</b> Used for formulating and exporting QUBO models in optimization tasks</li>
            <li><b>NetworkX:</b> Used to create and manipulate the synthetic knowledge graph</li>
            <li><b>Matplotlib:</b> For plotting success rates and learning trends from RL agents</li>
        </ul>
    </section>
    <section>
        <h2>Setup Instructions</h2>
        <p>For running the notebooks:</p>
        <ul>
            <li>Install dependencies: <code>pip install gymnasium stable-baselines3 matplotlib scikit-learn qiskit</code></li>
            <li>Open any notebook in the <code>notebooks/</code> folder in Jupyter or Google Colab</li>
            <li>Outputs and screenshots will appear in the <code>outputs/</code> folder after running</li>
        </ul>
    </section>
    <section>
        <h2>Progress Summary</h2>
        <h3>Prior Weeks</h3>
        <ul>
            <li>Generated a synthetic knowledge graph with agents, tasks, and anomalies. Focused on modeling task allocation relationships for use in quantum optimization.</li>
            <li>Practiced DP problems (LIS, 0/1 Knapsack, Edit Distance) and linked them to robot sensor log analysis, trust score trends, and task prioritization.</li>
            <li>Used Gymnasium's FrozenLake-v1 to train a Q-learning agent. Evaluated performance with Q-table and analyzed how the robot learns in uncertain environments.</li>
            <li>Extracted a subgraph (3 agents and 3 tasks) and built a QUBO task assignment problem using Qiskit Optimization.</li>
            <li>Continued literature review on graph anomaly detection (GAD) using GNNs and started reproducing one baseline.</li>
        </ul>
        <h3>Week 7</h3>
        <ul>
            <li>Simulated adversarial attacks that degrade trust matrices, modeling GPS spoofing and communication interference in post-disaster environments.</li>
            <li>Implemented defense countermeasures that partially restore trust based on agent success and failure feedback.</li>
            <li>Formulated task assignment as a Quadratic Unconstrained Binary Optimization (QUBO) problem with trust-based reward terms and hard assignment constraints.</li>
            <li>Used NEAL simulated annealing sampler to optimize task assignments under degraded trust conditions.</li>
            <li>Generated visualizations including trust heatmaps (baseline, attack, defense), QUBO assignment overlays, average fleet trust over time, trust distributions, and mission outcome trends.</li>
            <li>Evaluated system resilience by analyzing trust score dynamics, success and failure counts, and compromised agent trends across 1000 simulation rounds.</li>
        </ul>
    </section>
</body>
</html>


