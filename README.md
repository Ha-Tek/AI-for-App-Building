# 🤖 AI for App Building

Build three practical AI-powered applications using **Google AI Studio**:

* 🧠 **Tie-Breaker App** — Make difficult decisions by comparing options and analyzing pros and cons.
* 🎨 **Brand Builder App** — Prototype marketing and branding assets with AI.
* 📊 **Interactive Dashboard** — Explore, understand, and make informed decisions using your data.

🔗 **Google AI Studio:** https://aistudio.google.com/

> **Hands-on Project:** Developed as part of a Coursera course focused on AI-powered application development and **vibe coding**.


Teaches how to use **natural language prompts to build functional applications** that solve specific business problems—without needing to write all the code manually.

---

# 1. 🧠 Build with AI: Tie-Breaker App

The **Tie-Breaker** app helps users make difficult decisions by using AI to analyze different options through:

* Pros and Cons
* Comparison Tables
* SWOT Analysis

## 🛠️ Lab Tasks

### Step 1: Define Your App

1. Open **Google AI Studio**.
2. Navigate to **Build AI apps**.
3. In the prompt box, describe the application you want to create.

Use the following prompt:

> **I want an app called The Tiebreaker that helps me make decisions. I want to provide a decision that I need to make, and I'd love AI's help in showing me different pros and cons. This can be through a pros and cons list, a comparison table, or even a SWOT analysis.**

4. Click **Build**.

---

### Step 2: Test Your Application

Once the app interface appears, test it with a real-world decision.

1. Locate the input field, such as:
   `What decision do you need to make?`

2. Enter the following decision:

> **Should I offer my software for free with paid features, or charge a flat $20/month premium plan?**

3. Select an analysis type, such as **Pros and Cons List**.
4. Click **Get Analysis**.
5. Review the AI-generated results.

---

### Step 3: Troubleshoot and Auto-Fix Errors

If the application breaks or stops working, **don't start over**. Troubleshooting is part of the development process.

When an error occurs:

1. Review the error message.
2. Look for the **Auto-fix** button in the prompt box on the left.
3. Click **Auto-fix**.

The AI model will analyze the error, determine a potential solution, and modify the application code to fix the problem.

---

### Step 4: Verify the Fix

After **Auto-fix** completes, test the application again to make sure everything works correctly.

Enter a new decision:

> **What should I eat tonight: Sushi or Chinese food?**

Then:

1. Select **Comparison Table**.
2. Click **Get Analysis**.
3. Verify that the results are displayed correctly in the new format.

---

## 🎯 Project Outcome

By completing this lab, you will have built and tested an AI-powered **decision-making application** using natural language prompts and Google AI Studio.

This project demonstrates how **AI-assisted development and vibe coding** can be used to quickly prototype functional applications for real-world business problems.

---

## 🔧 Tools & Technologies

* **Google AI Studio**
* **Generative AI**
* **Prompt Engineering**
* **Vibe Coding**
* **AI-Assisted Application Development**

## 📚 Course

This project was completed as a **hands-on project as part of a Coursera course**.

# 2. Build with AI: Brand builder app to visualize any product

It teaches how to vibe code using natural language to create a functional app to solve a specific business problem.

Lab tasks:


Step 1: Define your app prototype 

Once in AI Studio, make sure you are signed in with your Google account. Next, navigate to “Build AI apps”. In the prompt box on the Build page, describe the Brand builder app:

**I want an app called the Brand builder app that lets me describe a product and imagine it across a bunch of different mediums, this could include a billboard, a newspaper, and a social post. Maintain product consistency between each shot. I do not want to see people in any of the images. You must use the Nano-Banana model for these images.
**

When you are ready, click the “Build” button.



Step 2: Run an initial product test 


Once the app interface loads, type the product you want to visualize into the product description field: 

**Augmented Reality AI glasses
**

Then, click the “Generate” button.

If the generation fails or an error message appears, follow the troubleshooting technique in the next step. 

Step 3: Work with AI to troubleshoot 

Sometimes the issue is that the app is trying to use multiple different models and confusing itself. In a situation like that: Click the error button on the bottom right of the window.

Select the errors, copy them, and paste them into the prompt box on the left. 

Then provide feedback to the model by typing a corrective prompt under the errors in the same prompt box:

**Please make sure you do not use any other image models. Use only Gemini 2.5 Flash or Nano-Banana for all steps.
**

Click the “Send prompt” button to have the model fix its code with your specific instructions.


Step 4: Visualize the campaign 

After the fix, re-enter your product idea and click the “Generate” button.

Review the gallery and verify that the product looks consistent across all images and that all original instructions were followed.


# 3. Build with AI: Interactive dashboard to uncover data insights

Lab tasks:

Step 1: Define your app prototype 

Once in AI Studio, make sure you are signed in with your Google account. Next, navigate to “Build AI apps”. In the prompt box on the Build page, describe the Interactive dashboard app: 

**I want to make an interactive dashboard that allows me to visualize data in many different ways. I am going to provide the data for you, so please set up the dashboard with it accurately.
**

Step 2: Explore and filter your data 

Once AI Studio generates the app, test its interactivity.

For example:

Observe how the model automatically created different chart types (e.g., pie charts, line graphs, and data tables).

Use the auto-generated filters to drill down into specific data points (e.g., filter by a specific product like "Premium Tailored Trousers").

Verify that the charts update in real-time as you change the filters.

Step 3: Iterate on the design and layout

If you want to change the design or layout, you can manually add your feedback onto the app. 

Click the “Annotate app” button in the prompt box.

Use the comment tool to highlight a specific area (e.g., draw a box around the KPI cards).

Type a design request, such as:

**Let's make these cards white
**

and click “Ok.” This will automatically add a screenshot with your feedback into the prompt box.

Click the “Send prompt” button and the model will read your visual feedback and update the app's code accordingly.

Once the model has updated the app. observe how it has changed the specific elements you pointed out (like the "KPI cards") and applies the visual changes without you needing to explain the technical details.


# 4. Build with AI: AHP calculator for incomplete pairwise comparison matrices
Prompt with Gemini in Google AI Studio as  follows:

Act as an expert in **AHP, numerical methods, and web application development**.

Using the **attached research paper as the authoritative source (https://www.sciencedirect.com/science/article/pii/S2214716023000076)**, build an interactive calculator for **completing incomplete pairwise comparison matrices (PCMs)** using the **11 methods described in the paper**.

### Requirements

1. Extract and correctly implement all 11 methods exactly as presented in the paper.
2. Allow users to:

   * Enter an incomplete pairwise comparison matrix.
   * Automatically enforce reciprocal values and diagonal = 1.
   * Select one method or run all 11 methods.
3. For each method, calculate:

   * Completed matrix
   * Estimated missing comparisons
   * Priority/weight vector
   * λmax
   * CI
   * CR
   * Consistency status
4. Build a **visual dashboard** comparing all 11 methods, including:

   * CR comparison
   * Priority-weight comparison
   * Estimated missing-value comparison
   * Final ranking comparison
5. Highlight methods that pass/fail the CR threshold (default **CR ≤ 0.10**).
6. Validate the implementation against the **numerical examples in the paper** and report any discrepancies.
7. Provide clear error handling, calculation details, and warnings for invalid or insufficient input.
8. Allow results to be exported to **Excel/CSV**.

### Technology

Prefer **Python + Streamlit + NumPy + Pandas + SciPy + Plotly**.

Organize the code into modular components for the 11 methods, matrix validation, consistency calculations, dashboard, and tests.

**Important:** Do not substitute generic matrix-completion techniques for the 11 methods in the paper. Preserve the paper's equations, assumptions, and calculation procedures.

- Result deployed, use Google Chrome: 
  https://aistudio.google.com/apps/01782b1b-d42d-494e-9e45-976704c57287?showAssistant=true&showPreview=true
