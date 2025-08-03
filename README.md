<!DOCTYPE html>
<html lang="en">
<body>
    <header>
        <h1>reu2025-cybersec-Roman</h1>
    </header>
    <section>
        <h2>Project Title</h2>
        <p>
            Trust-Aware Task Allocation Using Quantum Optimization Under Adversarial Attacks in Multi-Agent Robotic Systems
        </p>
    </section>
    <section>
        <h2>Student Name</h2>
        <ul>
            <li>Giselle Roman</li>
        </ul>
    </section>
    <section>
        <h2>Mentors</h2>
        <ul>
            <li>Dr. Yugyung Lee (University of Missouri–Kansas City)</li>
            <li>Dr. Dianxiang Xu (University of Missouri–Kansas City)</li>
            <li>Luke Miller (University of Missouri–Kansas City)</li>
            <li>Dr. Duy Ho (California State University, Fullerton)</li>
        </ul>
    </section>
    <section>
        <h2>Project Summary</h2>
        <p>
            This project investigates how adversarial attacks affect coordination and trust in multi-agent robotic systems 
            deployed in post-disaster hospital environments. We modeled attacks such as spoofing, misinformation, urgency decay, 
            bait tasks, and communication failures. To defend against these threats, we integrated trust modeling, curing 
            mechanisms, urgency-weighted recovery, and team-task synergy. 
        </p>
        <p>
            The task allocation problem was formulated as a Quadratic Unconstrained Binary Optimization (QUBO) model and solved 
            using the NEAL sampler. We compared performance against Greedy and MILP baselines on both synthetic hospital 
            simulations and MRTA-100 benchmark datasets. Results showed that QUBO, combined with trust-aware defenses, 
            preserved agent trust and coordination, while Greedy solvers collapsed under adversarial conditions.
        </p>
    </section>
    <section>
        <h2>Tools and Models</h2>
        <ul>
            <li><b>Python</b> (simulation and modeling)</li>
            <li><b>NetworkX</b>: Synthetic hospital graph construction</li>
            <li><b>NumPy / Pandas</b>: Trust matrices, cost functions, and analysis</li>
            <li><b>Matplotlib</b>: Visualizations (trust heatmaps, trust over time, outcome trends)</li>
            <li><b>D-Wave Ocean SDK (NEAL)</b>: QUBO solver using simulated annealing</li>
        </ul>
    </section>
    <section>
        <h2>Setup Instructions</h2>
        <p>To run the simulation:</p>
        <ul>
            <li>Install dependencies: 
                <code>pip install numpy pandas matplotlib networkx dimod neal</code>
            </li>
            <li>Run the simulation scripts in the <code>src/</code> folder.</li>
            <li>Simulation outputs (CSV metrics + plots) will appear in the <code>outputs/</code> folder.</li>
        </ul>
    </section>
    <section>
        <h2>Progress Summary</h2>
        <h3>Methods</h3>
        <ul>
            <li>Simulated post-disaster hospital environments with adversarial attacks (spoofing, comms loss, noise, bait tasks, precedence violations).</li>
            <li>Modeled dynamic trust degradation and recovery across 100+ simulation rounds.</li>
            <li>Formulated task allocation as QUBO, solved with NEAL simulated annealing.</li>
            <li>Compared QUBO against Greedy and MILP baselines on both synthetic and benchmark MRTA-100 environments.</li>
        </ul>
        <h3>Results</h3>
        <ul>
            <li>QUBO preserved trust and coordination under adversarial conditions.</li>
            <li>Greedy solvers collapsed when exposed to spoofing and urgency decay.</li>
            <li>Visualizations confirmed QUBO’s resilience: higher trust recovery, coordination success, and robustness across rounds.</li>
        </ul>
    </section>
</body>
</html>
