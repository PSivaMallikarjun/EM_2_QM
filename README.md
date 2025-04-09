# **Engineering Mechanics to Quantum Solver**

## **Overview**
The **Engineering Mechanics to Quantum Solver** is an advanced computational tool that enables users to analyze engineering mechanics problems such as beam loads, trusses, and frames while also exploring quantum mechanics analogs. This interactive tool features **2D and 3D Free Body Diagrams (FBDs) and quantum simulations** for a selected problem type.

## **Features**
### **🔹 Engineering Mechanics Solver**
- Supports **beam load analysis, truss analysis, and frame structures**.
- Generates **2D and 3D Free Body Diagrams (FBDs)** for visualization.
- Computes **reaction forces and moments** using symbolic computation.

### **🔹 Quantum Mechanics Mapping**
- Converts classical mechanics problems into **quantum analogs**.
- Uses **Schrödinger’s equation** to model quantum effects.
- Computes the **wave function behavior** based on mechanical constraints.

### **🔹 Interactive UI with Gradio**
- **User-friendly** interface using **Gradio**.
- **Real-time visualization** of input problems.
- Supports **dynamic interaction** with engineering problem setups.

## **Installation**
To run the project locally, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/PSivaMallikarjun/EM_2_QM.git
   cd EM_2_QM
   ```

2. **Create a virtual environment (Optional but recommended)**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use: env\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   python main.py
   ```

5. **Access the Gradio Interface**
   - The application will launch in your web browser at `auto generated URL`

## **How to Use**
1. Select the **problem type** (e.g., beam load, truss analysis).
2. The system generates:
   - **Pre-text explanation** of the problem.
   - **2D Free Body Diagram (FBD)**.
   - **3D Free Body Diagram (FBD)**.
   - **Quantum Mechanics Equivalent using Schrödinger’s equation**.
3. View results and interpret the engineering and quantum behavior.

## **Technical Details**
### **🔹 Dependencies**
- `NumPy` - Numerical calculations
- `Matplotlib` - 2D/3D plotting
- `SymPy` - Symbolic mathematics for equation solving
- `Gradio` - Interactive UI

### **🔹 Core Functions**
#### `engineering_mechanics_solver(problem_type)`
- Generates **pre-text explanation, FBDs, and quantum equivalent simulation**.

#### `generate_2d_fbd(problem_type)`
- Uses **Matplotlib** to draw a **2D Free Body Diagram**.

#### `generate_3d_fbd(problem_type)`
- Uses **Matplotlib 3D plots** for **force and moment visualization**.

#### `quantum_simulation(problem_type)`
- Implements Schrödinger’s equation:
  
  ```math
  - \frac{\hbar^2}{2m} \frac{d^2 \psi}{dx^2} + V(x)\psi = E\psi
  ```

#### `launch_gradio()`
- **Starts the Gradio interface** for user interaction.

## **Future Enhancements**
- Add support for **more complex mechanics problems**.
- Integrate **machine learning models** for predictive analysis.
- Expand **quantum interpretations** for advanced mechanics cases.
- Develop **web-hosted and mobile-friendly** versions.

## **Contributors**
# Siva Mallikarjun Parvatham


---
🚀 **Start solving engineering and quantum mechanics problems today!**

![Screenshot 2025-04-09 080043](https://github.com/user-attachments/assets/67393d57-dcdd-4c6a-9b47-a22da8baea12)
![Screenshot 2025-04-09 214506](https://github.com/user-attachments/assets/441ab34b-e811-4bf8-b4aa-f574d96ea4c8)
![Screenshot 2025-04-09 080404](https://github.com/user-attachments/assets/da64c91c-8110-4c6f-9776-a6b5f970ae75)
![Screenshot 2025-04-09 080353](https://github.com/user-attachments/assets/b188da0a-271b-4047-a4ac-81cbb8dc9532)
![Screenshot 2025-04-09 080053](https://github.com/user-attachments/assets/8d91d4b6-2f4a-453d-8861-8367c50902f2)
![Screenshot 2025-04-09 214552](https://github.com/user-attachments/assets/67135a4f-00bc-4281-989e-c2cc3be739d3)
![Screenshot 2025-04-09 214536](https://github.com/user-attachments/assets/37bc3bc6-eede-4eae-b1a7-33b38994fb8e)
![Screenshot 2025-04-09 214515](https://github.com/user-attachments/assets/aa9a7462-a2e7-4485-b2b7-c0fa868f446b)
