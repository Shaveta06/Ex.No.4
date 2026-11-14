# EX.NO.4 – GENERATE THE PROMPT AND EVALUATE THE FOLLOWING PROMPT PATTERNS


**REGISTER NUMBER:** 212225050052

## AIM

To design and execute prompts using different prompt engineering patterns, compare their outputs using different AI tools, and evaluate their effectiveness using a suitable evaluation method such as a rubric.

The following prompt patterns are used:

1. Zero-shot Prompting
2. Few-shot Prompting
3. Chain of Thought Prompting
4. Persona Pattern
5. Reverse Prompting
6. Graph Prompting
7. Active Prompting

## EXPLANATION

Prompt Engineering is the process of designing effective instructions to guide AI models to generate accurate, relevant, and meaningful responses. Different prompt patterns help improve the quality, structure, and accuracy of AI-generated outputs.

## PROCEDURE

### 1. DEFINE THE SCENARIO AND USE CASE

**Scenario:**

The manufacturing industry aims to reduce manual monitoring and improve production efficiency through automation. The system uses IoT devices and embedded controllers to automate equipment, monitor performance, and enable predictive maintenance.

**Target Audience:**

Manufacturing companies, particularly in the automotive, electronics, and food processing industries.

**Main Objectives:**

1. Improve production efficiency by 30%.
2. Minimize machinery downtime through predictive maintenance.
3. Enable real-time monitoring and remote control of manufacturing systems.
4. Reduce energy consumption by optimizing industrial processes.

---

### 2. IDENTIFY PROMPT PATTERNS FOR EACH DESIGN ASPECT

### 1. ZERO-SHOT PROMPTING

**Definition:**

Zero-shot prompting is a technique in which an AI model is given an instruction without providing any examples. The model generates an answer based on its existing knowledge.

**Example Prompt:**

"Explain how IoT-based automation improves efficiency in manufacturing industries."

**Generated Output:**

IoT-based automation improves manufacturing efficiency by connecting machines, sensors, and controllers through the internet. It enables real-time monitoring, automatic control, predictive maintenance, and energy optimization.

**Evaluation:**

The AI generates a relevant response without requiring any prior examples or additional training information.

---

### 2. FEW-SHOT PROMPTING

**Definition:**

Few-shot prompting involves providing a few examples in the prompt so that the AI model can understand the expected format and generate similar outputs.

**Example Prompt:**

"Identify the industrial problem and suggest an automation solution using the following examples.

Example 1:
Problem: Excessive machine temperature.
Solution: Install temperature sensors for continuous monitoring.

Example 2:
Problem: High energy consumption.
Solution: Use smart energy meters to monitor and optimize electricity usage.

Now generate a solution for:

Problem: Unexpected machine failure."

**Generated Output:**

Problem: Unexpected machine failure.

Solution: Install vibration and temperature sensors to continuously monitor machine conditions. Use predictive maintenance algorithms to identify possible faults and alert operators before equipment failure occurs.

**Evaluation:**

The AI follows the given examples and generates a similar problem-solution format with relevant automation solutions.

---

### 3. CHAIN OF THOUGHT PROMPTING

**Definition:**

Chain of Thought prompting encourages an AI model to solve a problem through a structured sequence of steps before providing the final answer.

**Example Prompt:**

"Explain step by step how IoT-based predictive maintenance reduces machine downtime in a manufacturing industry. Provide the final result with a simple explanation."

**Generated Output:**

**Step 1: Data Collection**

Sensors collect machine data such as temperature, vibration, and pressure.

**Step 2: Data Transmission**

The collected data is transmitted to a monitoring system through IoT communication networks.

**Step 3: Data Analysis**

The system analyzes the collected data to identify unusual machine conditions.

**Step 4: Fault Prediction**

The system identifies possible failures and generates maintenance alerts.

**Step 5: Maintenance Action**

Technicians perform maintenance before the machine completely fails.

**Final Result:**

Predictive maintenance reduces unexpected breakdowns, minimizes downtime, and improves overall production efficiency.

**Evaluation:**

The AI presents the process in a logical sequence, making the explanation easier to understand.

---

### 4. PERSONA PATTERN

**Definition:**

Persona prompting assigns a specific role or identity to the AI model so that it generates responses from a particular professional perspective.

**Example Prompt:**

"Act as an industrial automation engineer. Suggest five ways to improve production efficiency in a manufacturing industry using IoT devices and embedded controllers."

**Generated Output:**

As an industrial automation engineer, I recommend the following solutions:

1. **Smart Sensors:** Install sensors to monitor temperature, pressure, and vibration.
2. **Automated Controllers:** Use embedded controllers to automate industrial equipment.
3. **Predictive Maintenance:** Monitor machine conditions to predict failures.
4. **Energy Monitoring:** Install smart energy meters to reduce unnecessary power consumption.
5. **Remote Monitoring:** Implement IoT dashboards to monitor industrial operations remotely.

**Evaluation:**

The AI responds from the perspective of an industrial automation engineer and provides practical, domain-specific suggestions.

---

### 5. REVERSE PROMPTING

**Definition:**

Reverse prompting is a technique in which the AI model is asked to generate an effective prompt based on a given objective or desired output.

**Example Prompt:**

"I want to develop an IoT-based smart manufacturing system that monitors machine temperature, vibration, energy consumption, and equipment performance. Generate an effective and detailed AI prompt that can be used to obtain a complete system design."

**Generated Output:**

**Suggested Prompt:**

"Act as an industrial IoT system designer. Design a smart manufacturing automation system using IoT sensors and embedded controllers. Include sensor selection, hardware components, communication protocols, real-time monitoring, predictive maintenance, energy optimization, and system architecture. Present the solution in a structured format with suitable examples."

**Evaluation:**

The AI successfully converts the given objective into a detailed and structured prompt that can be reused for obtaining a complete system design.

---

### 6. GRAPH PROMPTING

**Definition:**

Graph prompting is a technique that instructs an AI model to represent information using nodes and connections to show relationships between different components of a system.

**Example Prompt:**

"Create a graph representing an IoT-based manufacturing automation system. Show the relationship between sensors, embedded controllers, cloud platforms, data analysis, and automated machines."

**Generated Output:**

**IoT-Based Manufacturing Automation Architecture:**

```text
        IoT Sensors
             |
             v
    Embedded Controllers
             |
             v
    Communication Network
             |
             v
       Cloud Platform
             |
             v
       Data Analysis
             |
       +-----+-----+
       |           |
       v           v
  Fault Alerts   Monitoring
       |           |
       v           v
 Maintenance   Automated
   Action       Control
       |           |
       +-----+-----+
             |
             v
    Improved Production
```

**Evaluation:**

The AI represents the manufacturing automation system using connected components, making the relationships and data flow easier to understand.

---

### 7. ACTIVE PROMPTING

**Definition:**

Active prompting is a technique in which the AI model identifies missing information or uncertainty and asks relevant questions to obtain additional details before generating a more accurate response.

**Example Prompt:**

"I want to develop an IoT-based manufacturing automation system. Before suggesting a solution, ask me five important questions about the machines, sensors, communication methods, maintenance requirements, and energy monitoring."

**Generated Output:**

The AI asks the following questions:

1. What type of machines are used in the manufacturing industry?
2. Which parameters need to be monitored, such as temperature, vibration, or pressure?
3. Which sensors and embedded controllers are available?
4. Which communication protocol is preferred, such as MQTT or Wi-Fi?
5. Is the system expected to support predictive maintenance and remote monitoring?

**Evaluation:**

The AI identifies missing requirements and asks relevant questions before suggesting an automation solution. This helps generate a more accurate and suitable system design.

---

## 3. EVALUATION USING RUBRIC METHOD

A rubric is a structured evaluation method used to assess the quality of AI-generated responses based on specific criteria.

**Evaluation Criteria:**

| S.No. | Criteria | Description | Marks |
|:---:|---|---|:---:|
| 1 | Relevance | Response matches the given prompt. | 5 |
| 2 | Accuracy | Information provided is technically correct. | 5 |
| 3 | Clarity | Response is simple and understandable. | 5 |
| 4 | Completeness | Response covers the required information. | 5 |
| | **Total** | | **20** |

**Sample Evaluation Table:**

| S.No. | Prompt Pattern | Sample Score (Out of 20) |
|:---:|---|:---:|
| 1 | Zero-shot Prompting | 17 |
| 2 | Few-shot Prompting | 18 |
| 3 | Chain of Thought Prompting | 19 |
| 4 | Persona Pattern | 18 |
| 5 | Reverse Prompting | 17 |
| 6 | Graph Prompting | 18 |
| 7 | Active Prompting | 19 |

*Note: These are illustrative scores for demonstrating the rubric. Actual scores should be assigned after testing the same prompts in the selected AI tools.*

### Comparison of AI Tools

The same prompts can be tested using different AI tools, such as:

| S.No. | AI Tool | Purpose |
|:---:|---|---|
| 1 | ChatGPT | Generates structured and detailed responses. |
| 2 | Google Gemini | Generates explanations and contextual responses. |
| 3 | Microsoft Copilot | Assists in generating technical information and structured outputs. |

The responses from these tools can be compared using relevance, accuracy, clarity, and completeness.

---

## CONCLUSION

The seven prompt engineering patterns were studied and executed successfully using the manufacturing industry automation scenario. Each pattern provides a different approach to generating AI responses. Zero-shot prompting provides direct answers, few-shot prompting uses examples, chain of thought prompting provides stepwise explanations, persona prompting generates role-based responses, reverse prompting creates effective prompts, graph prompting represents relationships visually, and active prompting collects additional information through questions.

## RESULT

Thus, the various prompt engineering patterns were successfully executed, and their generated outputs were evaluated using the rubric method.
