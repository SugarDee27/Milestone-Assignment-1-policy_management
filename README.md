# Policy Management System – Milestone Assignment 1  

## 📌 Project Description  
This project is a **Policy Management System** for an insurance company. It manages **policyholders, products, and payments**. The system allows policy managers to:  
- Register, suspend, and reactivate policyholders.  
- Create, update, and suspend policy products.  
- Process payments, send reminders, and apply penalties.  
- View details of policyholders and their associated products/payments.  

The implementation uses **Object-Oriented Programming (OOP)** concepts in Python, with three core classes:  
- `Policyholder`  
- `Product`  
- `Payment`  

---

## 📂 Project Structure  

```
policy_management/
│
├── main.py             # Main script to demonstrate functionality
├── policyholder.py     # Policyholder class
├── product.py          # Product class
├── payment.py          # Payment class
└── README.md           # Project instructions and details
```

---

## ⚙️ How to Run  

### 1. Clone or Download Project  
If using GitHub:  
```bash
git clone <your_repo_link>
cd policy_management
```  
Or download as a `.zip`, extract, and open the folder.  

### 2. Run the Program  
Make sure Python is installed (version 3.8+ recommended).  
In the terminal or command prompt:  
```bash
python main.py
```

---

## ✅ Demonstration  

When you run `main.py`, the following actions are demonstrated:  
1. Two policyholders (Disere Leghemo and Richard Obioha) are registered.  
2. Two products (Life Insurance, Car Insurance) are assigned.  
3. Payments are processed (with reminders and penalties for late payment).  
4. Policyholder details (with products and payments) are displayed.  

**Sample Output:**  

```
Policyholder Disere Leghemo registered successfully.
Policyholder Richard Obioha registered successfully.
Product Life Insurance assigned to Disere Leghemo.
Product Car Insurance assigned to Bob Richard Obioha.
Payment of $500 processed for Disere Leghemo.
Reminder: Richard Obioha, your payment of $300 is pending.
Penalty of $50 applied. New amount due: $350.
Payment of $350 processed for Richard Obioha.

--- Policyholder Details ---
ID: 1
Name: Disere Leghemo
Status: Active
Products:
   - Life Insurance ($500, Active)
Payments:
   - Amount: $500, Status: Paid
----------------------------

--- Policyholder Details ---
ID: 2
Name: Richard Obioha
Status: Active
Products:
   - Car Insurance ($300, Active)
Payments:
   - Amount: $350, Status: Paid
----------------------------
```

---

## 📝 Notes
- This project was developed as part of **Milestone Assignment 1** (Modules 1–3).  
- It demonstrates OOP best practices and clean separation of concerns across multiple files.  
