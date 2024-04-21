
## Optimizing Schedule Creation Using Genetic Algorithms

**Project Overview**

This project implements a genetic algorithm (GA) to optimize scheduling problems, specifically targeting scenarios like Santa's Workshop Tour (adaptable to other domains). 
It provides a framework for evolving efficient tours (schedules) through an iterative process inspired by natural selection.

**Features**
* **Genetic Algorithm Implementation:** Leverages core GA principles like selection, crossover, mutation, and fitness evaluation to generate improved tours across generations.
* **Santa's Workshop Tour Optimization:** Tailored to solve the problem from the https://www.kaggle.com/competitions/santa-workshop-tour-2019 competition, where the goal is to efficiently schedule families visits to various workshop stations while considering preferences and minimizing travel time.
* **Problem-Specific Customization:** Adaptable to various scheduling problems by modifying:
    * **Task Representation:** How locations or activities are encoded (e.g., permutation encoding for visit order).
    * **Fitness Function:** The objective function that measures tour quality (e.g., minimizing total travel time, maximizing preference satisfaction).
    * **Constraints:** Rules governing the scheduling process (e.g., time windows for visits, family group sizes).



* **Genetic Algorithm Implementation:** Leverages core GA principles like selection, crossover, mutation, and fitness evaluation to generate improved schedules across generations.
* **Problem-Specific Customization:** Tailored to your specific scheduling requirements through configuration options, allowing you to define:
    * **Task Representation:** How tasks are encoded within the GA (e.g., permutation encoding for task ordering, priority-based encoding for relative importance).
    * **Fitness Function:** The objective function that measures the quality of a schedule (e.g., minimizing completion time, maximizing resource utilization, balancing workload).
    * **Constraints:** Rules or limitations governing the scheduling process (e.g., task dependencies, resource availability, time windows).

## **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/kezouke/S24_NIC_Optimizing_Schedule_Creation_Genetic_Algorithm.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

After you have installed the necessary dependencies, follow these steps to use the `.ipynb` file:

1. Open the `.ipynb` file using Jupyter Notebook or any compatible platform.
2. Follow the instructions and guidelines provided within the notebook to execute the desired functions or analyses.
3. Ensure you have the required datasets or inputs available in the appropriate directories or accessible locations as specified in the notebook.
4. Execute the code cells sequentially, paying attention to any prompts or input requirements.
5. Review the output, visualizations, or any generated files as indicated within the notebook.
6. Customize and modify the notebook as needed for your specific use case, adjusting parameters or code blocks as necessary.
7. Save your work and any modifications made to the notebook for future reference or sharing.

Feel free to reach out if you encounter any issues or have questions regarding the usage of the `.ipynb` file.

## **References:**

* Kaggle competition: [Link](https://www.kaggle.com/competitions/santa-workshop-tour-2019)
* Genetic algorithm: [Link](https://en.wikipedia.org/wiki/Genetic_algorithm)
## **Credit:**

* [Kezouke](github.com/kezouke)
* [Liaaana](github.com/liaaana)
* [Amine](github.com/Amine-Trabelsi)
