🏥 Patient Allocation Calculator 

A **web-based workload distribution tool** for healthcare staff scheduling — built entirely with **pure HTML, CSS, and JavaScript** (no frameworks or backend required).

This calculator helps allocate patients to staff fairly and efficiently across multiple units (CCU, CD, CT, ICU) using a **CCU-first allocation logic**, allowing for **manual locking**, **live recalculation**, and a built-in **light/dark mode** switch.

Open here => https://tzx0203.github.io/CCA/

---

## ✨ Features

- 🧮 **Automatic Patient Distribution**  
  Distributes patient workload among available staff proportionally, with priority given to CCU → CD → CT → ICU.

- 🔒 **Lock/Unlock Columns**  
  Freeze specific staff assignments and recalculate others dynamically.

- 🔁 **Live Recalculation**  
  Update allocations instantly when changing patient numbers.

- 🎨 **Light / Dark Mode Toggle**  
  A built-in 🌙 / ☀️ switch for comfortable viewing — all handled locally with CSS variables.

- 📊 **Row and Column Totals**  
  Displays live totals per department and per staff, plus a grand total.

- 💻 **Fully Offline & Lightweight**  
  No dependencies, APIs, or database — runs directly in your browser.

---

## 🧰 How It Works

1. Enter:
   - Total number of staff  
   - Number of patients in **ICU**, **CT**, **CD**, and **CCU**

2. Click **Calculate**  
   → The system allocates patients per staff column using a *CCU-first* approach.

3. Optionally:
   - **Lock** specific staff columns to preserve their allocation.  
   - Adjust patient counts and press **Recalculate (Unlocked Only)** to redistribute remaining workload.

4. Use **Reset** to clear all inputs and start again.

---

## 🌗 Theme Toggle

- Click **🌙 Dark Mode** (top-right) to switch to dark mode.  
- Click again (**☀️ Light Mode**) to return.  
- Smooth transitions and color adjustments are automatic.

---

## 🏗️ Technologies Used

- **HTML5** — structure  
- **CSS3** — responsive design + color theming (CSS variables)  
- **JavaScript (ES6)** — core allocation logic and dynamic updates


---

## 👨‍⚕️ Author

Developed by **[Your Name or Team Name]**  
📧 *tanzx02@gmail.com*  
🌐 [GitHub Profile](https://github.com/tzx0203/)

---

> 💡 Tip: Works perfectly offline — no installation needed. Simply open the `.html` file anywhere, anytime.
