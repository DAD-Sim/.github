## Hi there 👋

Welcome to the DADSim team. The DADSim is the abbreviation of **D**istributed **A**utonomous **D**riving **Sim**ulator, which is designed as a modular, distributed autonomous driving simulator with the following features:

- Modularity: DADSim is crafted as a set of packages running on ROS2, with each functionality provided by one or more nodes that can be tailored as needed.
- Distribution: Agents are positioned on an equal footing, distributed as ROS nodes.
- Clock Synchronization: A centralized time server is responsible for disseminating simulation time. The time promise/fulfillment mechanism ensures the synchronization of node clocks and patiently waits for slower nodes to complete computations when necessary.

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

## Feature Lists

- [x] Time server and promise/fulfillment mechanism.
- [x] Map server and API based on OpenDRIVE 1.4 (only road and junctions are supported yet).
- [x] Object manager for range looking up and collision detection.
- [x] Simple RViz visualization.
- [ ] (In the future) 3D rendering and sensor support.
