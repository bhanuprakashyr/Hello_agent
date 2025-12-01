# Difference Between ML Model and Agent

## **Machine Learning Model**
A Machine Learning (ML) model is a statistical function trained to learn patterns from data and produce predictions.

### **Core Activities**
**Train the model**
- Use historical data to learn patterns and relationships

**Execute the model (Inference)**
- Use the trained model to make predictions on unseen data

**Tune the model**
- Adjust hyperparameters
- Add, drop, or transform features
- Add more or better-quality training data
- Try alternative algorithms
- Improve evaluation metrics based on validation feedback

### **Nature of an ML Model**
- Single-step mapping: **Input → Output**
- Does not decide what action to take next
- No autonomy or goal-based decision-making


---

## **What is an Agent?**
An **Agent** is a system that **perceives**, **reasons**, and **takes actions** autonomously to achieve a goal. It may use ML models as tools, but it is not limited to prediction.

### **Key Capabilities**
- Understands the goal or task
- Decides what action to take next
- Can call external tools, APIs, or services
- Can use and update memory or state
- Can plan and execute multiple steps

### **Agent Flow**
```text
Input → Reason / Plan → Choose Action → Execute → Evaluate → Continue or Return Result
