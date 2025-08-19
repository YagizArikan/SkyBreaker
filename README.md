## 🛠️ Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/YagizArikan/SkyBreaker.git
cd SkyBreaker
```

SkyBreaker 🚀

Minimalist, physics-driven “thrust & rotate” lander built in Unity. No fluff—tight controls, readable code, reusable components.

Controls: A = rotate left · D = rotate right · Space = thrust forward
Goal: thread the caverns, land on the pad, don’t smack the walls. ⚠️

Features

Rigidbody flight with stable FixedUpdate thrust/rotation

Reactive audio + particles for engine and side thrusters

Win/lose sequences with scene progression

Drop-in Oscillation for moving hazards

Compact, inspector-driven tuning 🛠️

Quick Setup

Just open Build1

Wire actions: thrust (Space), rotation (A/D).

Code Map

Movement.cs — thrust, rotation, audio/particles

Collision.cs (class named Collusion—consider renaming) — win/lose + scene flow

Oscillation.cs — PingPong mover

Quit.cs — optional exit action

<img width="1680" height="1050" alt="SkyBreaker" src="https://github.com/user-attachments/assets/dee6bb6c-d60a-4441-9b66-d01c5309a61d" />


<img width="1680" height="866" alt="SkyBreaker1" src="https://github.com/user-attachments/assets/3f9bbdef-786f-4eb9-8682-51522b320c4f" />



