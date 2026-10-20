# Shi Hao Ng

I'm a second-year Computing student at Imperial College London. I train robots. I make robots see. I build robots.

[sienarindustries.com](https://sienarindustries.com) · [LinkedIn](https://www.linkedin.com/in/shi-hao-ng/) · [Hugging Face](https://huggingface.co/shng2025) · [Email](mailto:shi-hao.ng25@imperial.ac.uk)

## Now

- **Project Ladder** | [CodeBase](https://github.com/Ice-Citron/Project-Ladder.git)
    - Successor of Project Automaton: I will attempt to publish my first robotic research paper on cable-insertion.
    - On the side, I'm currently exploring coverage-driven, edge-case testing for robot deployment, which I believe will a big bottleneck in robot deployment.

## Flagship projects & experiences

- **Vikaso Robotics** | Robotics & Machine Learning Intern | [Website](https://sienarindustries.com/project/vikaso-internship)
    - Built Vikaso's first camera-intrinsic and robot extrinsic (TCP-to-robot-base) calibration pipeline for a UR5e.
    - Built Vikaso's first perception stack, integrated two segmentation and four 6D-pose-estimation open-source models behind one interface.
    - To check my integrations' correctness, I built an evaluation harness which benchmarks 6D localisation and 2D detection models on public datasets and compare their metrics with published results.
  
- **Project Automaton** | [CodeBase](https://github.com/Ice-Citron/Project-Automaton) | [More details in Website](https://sienarindustries.com/project/project-automaton) <br>
    - Rucha Agashe and I competed in the Intrinsic’s AI for Industry Challenge, placing 49th of 196.
    - We implemented a FSM-ACT policy which gets a Universal Robots UR5e to insert a fiber-optic cable into server racks, which scored 141 locally and 89 on hidden scenes.
    - This gap between local evals and held-out evals have inspired my work to further explore robotics in Project Ladder and GapHunter. 

- **GPT-2 Pre-Training: Layer Normalization Study** | [Research code](https://github.com/Ice-Citron/nanoGPT-Valkyrie) | [GPT-2 reproduction](https://github.com/Ice-Citron/GPT2-Reproduction) | [Paper](https://drive.google.com/file/d/1dlhTgv4-A2cCYSsL00An_XpfGpg1DyWy/view)  
    - Reproduced GPT-2 124M from scratch in PyTorch, pre-trained on FineWeb using DDP on 4x NVIDIA H100s; tuned GPU configurations, batch size, mixed precision, etc. achieving training throughput of 1.27M tokens/s
    - Implemented LayerNorm, RMSNorm & PowerNorm. RMSNorm achieved comparable loss at 6% higher throughput than LayerNorm; PowerNorm's gradients exploded. Ran normalization ablations and analyzed per-layer gradients
    - Fine-tuned base \& ablated models on BillSum and SQuAD. Evaluated text generation, summarization and QA. Awarded Grade A for this IB Computer Science Extended Essay

- **C++ OpenGL Game Engine** | [Sparky](https://github.com/Ice-Citron/Sparky) | [Hazel](https://github.com/Ice-Citron/CAS-Project--Hazel) | [Website](https://sienarindustries.com/project/game-engine)
    - Recreated game engine in C++/OpenGL following The Cherno's tutorials: batched sprite renderer with texture slots over shared buffers, GLSL shaders for texturing and lighting, and a hand-written matrix library with a transformation stack
    - Built an application framework using GLFW for windows \& input and C++ templates to dispatch events to handlers, with a layer stack that routes events to overlays first. Integrated ImGui docking and multi-viewport support into the render loop

## Built with my hands

- **Augmented electromagnetic railgun** | [Website](https://sienarindustries.com/project/railgun) | [Rail-launcher simulations](https://github.com/Ice-Citron/FEA-Physics_IA) | [Write-up](https://docs.google.com/document/d/1gprXPwxTy_E5e2jCCYmBK_HHdFBfU2vu7njF-C8hT4M/edit?usp=sharing)
    - Iterated through 3 physical railgun prototypes, modeling each in Fusion 360 before fabrication. Ran 70 LS-DYNA simulations across 10 voltage conditions and decided on augmented railgun design. Cut copper rails and assembled prototypes with laser-cut acrylic panels
    - For the power system, built a 450 V, 10,000 uF capacitor bank, charged via a ZVS driver, hand-wound ferrite-core transformer and bridge rectifier. Final railgun averaged 132 km/h across 10+ firing trials, estimated from high-speed footage

- **FPV racing drone** | [Website](https://sienarindustries.com/project/fpv-drone)  
    - Designed the frame in Blender and 3D-printed in PET-CF; hand-soldered electronics (Mamba F722, DJI O4 Pro, ELRS), tuned Betaflight PIDs. Replaced frame due to crash damage; flew the completed 610 g drone in Acro (240 km/h theoretical top speed)

- **F1 in Schools: Anduril Racing** | [Team site](https://andurilracing.com) | [Website](https://sienarindustries.com/project/f1-in-schools)
    - Team Lead & Technical Lead: secured $1.1k sponsorship; led Fusion 360 design, optimization with Ansys Fluent CFD, resin printing & CNC-machining (Mastercam); built a 20 m test track, saving the school ~$11k; won Innovation & Marketing awards

## Technical skills

- Languages: Python, C/C++, Kotlin, Java, Haskell, TypeScript/JavaScript, RISC-V assembly
- Machine learning: PyTorch, DDP, Hugging Face Transformers, LeRobot, YOLO, SAM, Weights & Biases, NumPy, vLLM, llama.cpp
- Robotics and simulation: ROS 2, MuJoCo C API, Gazebo, Isaac Sim, FoundationPose, OpenCV, Universal Robots UR5e
- Systems and graphics: Linux/CUDA toolchain, Git, Docker, GCP, AWS, OpenGL
- Web: React, Node.js, Firebase
- CAD and hardware: Fusion 360, Blender, Ansys Fluent, LS-DYNA, 3D printing, CNC, electronics, Betaflight

## Outside of work

I run 25–30 km a week, I work out once per 2 days.

I have a hard-line policy of not breaking small rules that I've set for myself. Because if I break a small rule, what's stopping me from coming up with more excuses to break even more rules.

Books and authors: Liu Cixin · Frank Herbert’s *Dune* · Haruki Murakami’s *What I Talk About When I Talk About Running*
