# Submarine-Project-2023-Control-System
Design and implementation on Simulink environment of a controller to stabilize a submarine described by differential equations.


This project was created for the Control System exam given by Professor Adriano Fagiolini, Control System Teacher. We did the project with the group formed by: Giovanni Castelli, Raoul Renda, Gabriele Nicolò Costa, Spedito Antonio and Alessandro Macaluso. We all participated equally in the project.

The project consisted in designing a Controller that respects some specifications for a Submarine described by differential equations.

The project includes a first analytical part of resolution and description of the design and a numerical part to be carried out in the Simulink/MATLAB environment.

## Description
The stages were:

- Linearization of the provided model.

- Obtain the form of state.

- Obtain the eigenvalues described by the system with also the modes of the system.

- Deduce the transfer function and describe the poles and zeros of the transfer function.

- Design a controller that respects some project specifications.

- Model a controller on sisotool environment

- Implementation of the controller on a Simulink simulation of the system.


e repository we provide the matlab codes with comments in Italian and the document presented to the professor.


## Images
### Differential Equations
<p align="center">
<img width="800" alt="Senza titolo" src="https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/2c40bb7d-ff3b-44eb-a16a-3e6e8ebfc64e">
</p>
### Bode Diagrams

![bode_G(jw)](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/e9009029-dd8a-4cf0-9d0d-74612576c8ef)

![Bode_C(jw)G(jw)](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/50202dbd-814b-4e75-9d13-68bf02c5f00e)

![Bode_Gc(jw)](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/b1d179f8-bb08-4a48-8c45-e36623578a86)

### Simulink Projects

#### Linear Model

<p align="center">
<img width="1157" alt="Immagine 2023-05-15 234937" src="https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/aa18de01-1195-41e1-8187-2dbd8d86b12f">
</p>

![simulazione1](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/90d139d1-8180-4084-a7eb-0190476222a1)

#### Non Linear Model

![SimulinkNonLinear](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/b75bec65-ed73-448e-9292-9e95a1bb56ec)

![NonLinearSystem](https://github.com/AshenClock7613/Submarine-Project-2023-Control-System/assets/66488273/b2ae5d85-bb7a-4c89-8531-360c6dbc363e)


