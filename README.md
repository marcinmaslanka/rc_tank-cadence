# ⚙️ Using Verilog-A Models of an RC-Tank in Cadence Virtuoso

This guide explains how to integrate and simulate **Verilog-A modules** in **Cadence Virtuoso**, including compiling the model, instantiating it in schematics, and running simulations.

---

## 🛠️ 1. Create Verilog-A Model File

Save your Verilog-A code in a file with `.va` extension, for example:

```bash
rc_lowpass.va
```

## 🧱 2. Create a New Cellview for the Model

1. Open Virtuoso Library Manager.
2. Create a new library or choose an existing one.
3. Create a new cellview:
     - Navigate to: File → New → Cell View
     - Set:
         - View Name: veriloga
         - Tool: Verilog-A

4. Paste your Verilog-A code into the editor.
5. Press Check and Save.

## 🔌 3. Instantiate in Schematic

1. Open your testbench schematic.
2. Place your symbol in the design.
3. Wire it up like any other component.

## 🧪 4. Run Simulation in ADE

1. Select the simulation Type
2. Select your simulation type
3. Choose the outputs to plot
4. Press Run to start the simulation

---


Feel free to modify this repository for your own analog design projects. Contributions and improvements are welcome!

