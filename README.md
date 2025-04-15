# 🧮 Fractional Knapsack Problem Visualizer

Welcome to the **Fractional Knapsack Visualizer** – a fun and interactive way to explore one of the classic problems in algorithms: how to get the *most value* from limited space using a greedy approach.

Explore the Fractional Knapsack algorithm like never before – with animations, interaction, and intuitive visualizations!  
🔗 **[Try it Live → fractional-knapsack-visualizer](https://fractional-knapsack-visualizer.vercel.app/)**

This project was developed as part of the **AOA IA2 Simulation Algorithms Project** by:

👨‍🎓 Siddhant Shukla – 16010123330  
👩‍🎓 Shravani Parte – 16010123319  
👨‍🎓 Shreejay Kurhade – 16010123320  
🧑‍🏫 Class: E

---

## 🔍 What This Tool Does

This visualizer helps you understand how the **Fractional Knapsack Algorithm** works. You can either enter item details manually or generate them at random. Then, watch the algorithm in action as it fills the knapsack to get the maximum value possible – one item (or part of it) at a time!

---

## 🧑‍💻 How to Use

### 1. Set Knapsack Details

- **Capacity:** How much weight your knapsack can carry (e.g., `50`)
- **Number of Items:** How many items you'd like to test with

> You’ll need to enter both values before moving on.

### 2. Add Items

You’ve got two choices here:

- **Generate Item Fields:** You fill in the value and weight for each item
- **Random Items:** The tool will auto-fill some values for you

### 3. Adjust Animation Speed

Pick your pace:

- 🐢 Very Slow
- 🐌 Slow
- ⏱️ Medium
- ⚡ Fast

### 4. Run the Algorithm

Click **Solve Knapsack** and see:

- Value-to-weight ratios 💰
- Which items are picked ✅
- Total value packed 🎯

---

## 🧠 How It Works

This tool uses a **Greedy Algorithm**:

1. It sorts all items based on their value/weight ratio
2. It picks the most valuable items per weight first
3. If the knapsack can’t fit the whole item, it just takes the portion that fits!

---

## 📈 Output Explained

- **Result:** Total value the knapsack ends up with
- **Ratio Table:** Breakdown of all items with their value, weight, and ratio
- **Visualization:** A visual of which items (and how much of them) were added

---

## 💡 Example Run

Say we set the capacity to `50`, and enter these items:

- Item 1: Value = 60, Weight = 10  
- Item 2: Value = 100, Weight = 20  
- Item 3: Value = 120, Weight = 30  

The visualizer will pick:

- ✅ All of Item 1
- ✅ All of Item 2
- 🧩 2/3 of Item 3  

**Total value:** Maxed out beautifully!

---

## 🛠️ Troubleshooting

- **Nothing happens when you hit Solve?**  
  Make sure all fields are filled in correctly with positive numbers.

- **Used a zero or negative value?**  
  That’s not allowed – all values and weights must be positive
