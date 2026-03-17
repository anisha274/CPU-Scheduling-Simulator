# CPU-Scheduling-Simulator
CPU Scheduling Simulator A simple and interactive tool to visualize and simulate various CPU scheduling algorithms such as FCFS, SJF, Round Robin, and Priority Scheduling. Helps students and developers understand how different scheduling techniques manage process execution in operating systems.

Here’s a clean, professional **README.md** you can directly copy-paste into your GitHub repo 👇

---

# 🚀 CPU Scheduling Simulator (Web-Based)

A fully interactive **CPU Scheduling Simulator** built using **HTML, CSS, and JavaScript**. This project allows users to visualize and compare different CPU scheduling algorithms with dynamic Gantt charts, performance metrics, and algorithm recommendations.

---

## 📌 Features

✅ Supports multiple CPU Scheduling Algorithms:

* FCFS (First Come First Serve)
* SJF (Shortest Job First)
* SRTF (Shortest Remaining Time First)
* Priority Scheduling (Preemptive & Non-Preemptive)
* Round Robin (with Time Quantum)

✅ Dynamic Process Input

* Add/remove processes easily
* Input Arrival Time, Burst Time, and Priority

✅ Interactive Gantt Chart

* Visual representation of execution timeline
* Handles **idle CPU time** properly

✅ Performance Metrics Calculation

* Waiting Time
* Turnaround Time
* Response Time
* CPU Utilization
* Throughput

✅ Algorithm Comparison

* Compare all algorithms at once
* Automatic **best algorithm recommendation** based on performance

✅ Data Visualization (Charts)

* Bar Chart → Turnaround & Waiting Time
* Doughnut Chart → CPU Utilization
* Line Chart → Throughput

---

## 🖥️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling
* **JavaScript (Vanilla JS)** – Logic & Simulation
* **Chart.js** – Data Visualization

---

## ⚙️ How It Works

1. Add processes with:

   * Arrival Time
   * Burst Time
   * Priority (if required)

2. Select a scheduling algorithm

3. Click **Simulate**

   * View Gantt Chart
   * See detailed metrics

4. Click **Compare Algorithms**

   * Analyze all algorithms
   * Get the best recommendation

---

## 📊 Metrics Explained

* **Turnaround Time** = Completion Time - Arrival Time
* **Waiting Time** = Turnaround Time - Burst Time
* **Response Time** = First Execution Time - Arrival Time
* **CPU Utilization** = (Busy Time / Total Time) × 100
* **Throughput** = Processes completed per unit time

---

## 🧠 Algorithm Logic Highlights

* **Preemptive algorithms (SRTF, PriorityP)** interrupt execution when a better process arrives
* **Round Robin** uses time quantum for fair scheduling
* **Idle time handling** ensures realistic simulation
* **Weighted scoring system** is used to recommend the best algorithm

---

## 📂 Project Structure

```
📁 CPU-Scheduler
 ┣ 📄 index.html
 ┣ 📄 style.css
 ┣ 📄 script.js
 ┗ 📄 README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/anisha274/CPU-Scheduling.git
```

2. Open the project folder

3. Run the project:

* Simply open `index.html` in your browser

---

## 📸 Output Preview

* Gantt Chart Visualization
* Process Metrics Table
* Algorithm Comparison Table
* Performance Charts

---

## 🎯 Use Cases

* Operating System course projects
* Learning CPU scheduling concepts
* Algorithm performance comparison
* Academic demonstrations

---

## 💡 Future Improvements

* Step-by-step animation of scheduling
* Export results (PDF/CSV)
* Dark mode UI
* Real-time simulation speed control

---

## 👩‍💻 Author

**Umme Mehajabin Anisha**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

<img width="1215" height="651" alt="Screenshot 2026-03-17 at 8 07 05 PM" src="https://github.com/user-attachments/assets/b8195d25-60e3-4b16-844e-9a91d89a04ff" />
<img width="1249" height="554" alt="Screenshot 2026-03-17 at 8 07 22 PM" src="https://github.com/user-attachments/assets/bf360488-605f-4377-bc0c-5a4049bfac76" />
<img width="1251" height="399" alt="Screenshot 2026-03-17 at 8 07 41 PM" src="https://github.com/user-attachments/assets/12f658d4-c226-4b4d-8fd8-aa7d6ca3ac24" />
<img width="1244" height="388" alt="Screenshot 2026-03-17 at 8 07 53 PM" src="https://github.com/user-attachments/assets/204d94d1-4304-4052-a74b-1ef08620a4e5" />
<img width="1248" height="659" alt="Screenshot 2026-03-17 at 8 08 05 PM" src="https://github.com/user-attachments/assets/9e0181fa-a174-46ee-8f8d-afacd6e13b43" />
<img width="1226" height="664" alt="Screenshot 2026-03-17 at 8 08 19 PM" src="https://github.com/user-attachments/assets/0aa143ca-39b2-48eb-abce-20ceded09dce" />


