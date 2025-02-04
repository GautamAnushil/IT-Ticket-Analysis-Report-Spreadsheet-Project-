# IT Ticket Analysis (2016-2020)
### Enhancing IT Support Efficiency through Data-Driven Insights!
##### Spreadsheet Project - By Anushil K Gautam (25 Jan 2025)

- ## Dashboard:
  ![image](https://github.com/user-attachments/assets/d612ea46-9e34-4901-babe-614f85426ad7)




- ## Agenda:
  
  > Problem Statement
  > Data Description
  > Objective Key Metrics and Visualizations
  > Insights and Recommendations
  

- ## Problem Statement:
  The objective is to analyze the IT support ticket management system to understand the performance of IT agents, the efficiency of ticket resolution, and the satisfaction levels of employees. The analysis aims to identify high and low performers among IT agents, assess the overall effectiveness of the team, and pinpoint areas for improvement in the ticket resolution process. The ultimate goal is to make informed staffing decisions, including hiring, firing, and training, to enhance overall service quality and team performance.

- ## Goal:
  
  > Informed staffing decisions.
  > Improved training.
  > Software efficiency.
  

- ## Data Overview:
  - #### Total Ticket: 97498
  - <b>Ticket Sheet:</b> Contains information about IT support tickets. Tickets Sheet: Contains information about IT support tickets.
    - <b>ID:</b> Unique identifier for the ticket.
    - <b>Ticket Fecha:</b> Date of the ticket.
    - <b>Employee ID:</b> ID of the employee who raised the ticket.
    - <b>Agent ID:</b> ID of the agent assigned to the ticket.
    - <b>Request Category:</b> Category of the request (e.g., Login Access, System, Software).
    - <b>Issue Type:</b> Type of issue (e.g., IT Error, IT Request).
    - <b>Severity:</b> Severity of the issue.
    - <b>Priority:</b> Priority level of the issue.
    - <b>Resolution Time (Days):</b> Time taken to resolve the ticket.
    - <b>Satisfaction Rate:</b> Satisfaction rate provided by the employee (1-5 scale).
      
  - <b>IT Agents Sheet:</b> Contains information about IT agents.
    - <b>Agent ID:</b> Unique identifier for the agent.
    - <b>Full Name:</b> Full name of the agent.
    - <b>Email:</b> Email address of the agent.
    - <b>Year of Birth:</b> Year the agent was born.
    - <b>Month of Birth:</b> Month the agent was born.
    - <b>Day of Birth:</b> Day the agent was born.

- ## Conclusion on Key Metrics:
  - <b>Key Metrics:</b>
    - <b>Count:</b>
      - Total number of tickets handled by the agent.
      - Higher ticket counts could indicate high productivity. Consider whether the agent is meeting the workload expectation.
    - <b>Resolution Time:</b>
      - Average and median resolution times should ideally align with organizational benchmarks.
      - A high maximum resolution time could indicate inefficiency in handling certain cases.
    - <b>Satisfaction Rate:</b>
      - Customer satisfaction rate is a critical metric.
  - <b><mark>A satisfaction rate below a defined threshold (e.g., 3.5 out of 5) may be unacceptable.</mark></b>
  - <b>Decision Considerations:</b>
    - <b>Focus on Trends:</b>
      - If the agent's performance consistently skews towards the min or below average values for all metrics (e.g., low satisfaction, high resolution time), this may indicate a need for improvement or dismissal.
    - <b>Satisfaction as a Priority:</b>
      - Since customer satisfaction (median 4.2, min 3.0) is vital, consider firing the agent if their consistent satisfaction rate is closer to the minimum (3.0).
    - <b>Low Ticket Volume with Poor Metrics:</b>
      - If the agent has a low count of tickets and still shows poor resolution time or satisfaction rates, this might justify dismissal.
      - Compare with team averages to confirm underperformance.
    - **Balanced Approach:**
      - <mark>Provide training or coaching opportunities for agents who are borderline performers, especially if metrics like median resolution time (4.6) and average satisfaction rate (4.1) aren't far off from expectations.</mark>
 
 
- ## Recommendations:
  - To improve service efficiency, focus on optimizing resolution times for complex cases and scaling resources for System-related issues. 
  - Enhancing mid-level severity and priority ticket handling will improve response times. 
  - Tailoring support strategies for different age groups can further boost customer satisfaction. 
  - Additionally, planning for continued ticket volume growth will ensure sustained service excellence.
