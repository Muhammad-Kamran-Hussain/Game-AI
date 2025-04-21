# 🛠️ Job Scheduler using Heap and Priority Queue

This is a simple Python project that demonstrates a **Job Scheduling System** using a **Min-Heap** and **Priority Queue**. Jobs are scheduled based on priority (lower number = higher priority) and simulated with duration timers.

---

## 📌 Features

- ✅ Add jobs with priority and duration
- ✅ Automatically schedules jobs based on priority
- ✅ Simulates job processing with `time.sleep`
- ✅ Clean and readable object-oriented code

---

## 🔍 How It Works

Jobs are pushed into a **Min-Heap** using Python’s built-in `heapq` module. The job with the **lowest priority value** is popped and executed first.

---

## 📂 Files

- `job_scheduler.py` – Main Python script

---

## 🚀 Getting Started

### ✅ Requirements

- Python 3.x

### ▶️ Run the Scheduler

```bash
python job_scheduler.py
