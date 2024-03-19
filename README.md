# MSC_hackathon
Task Assignment and Management System for Teams
Develop a system that efficiently manages task assignments among multiple teams with varying numbers of members. The system should automate task allocation, handle planned and unplanned leaves of team members, and provide a user-friendly interface for different types of users.

Key Features:
1. Task Allocation Algorithm: Implement a round-robin task assignment algorithm where each team member receives an equal share of tasks to be completed daily. Tasks should be distributed evenly among team members.
2. Leave Management: The system should handle both planned and unplanned leaves of team members. If a team member is on planned leave, tasks should be redistributed among the remaining team members. In the case of unplanned leave, tasks should be assigned to all team members.
3. Escalation Mechanism: If a task remains incomplete for two consecutive days, an automated email and call should be triggered to the responsible team member. If the issue persists, an alert should be sent to all team members for resolution.
4. User Interface: 
- Super-Admin: Capable of adding, modifying, and deleting tasks. Can assign tasks to team members.
- Team Lead: Can rearrange tasks among team members. Has access to view task statuses and team member assignments.
- Member: Can view assigned tasks and mark them as completed.
5. Security: Implement a secure user-based login system to ensure that only authorized users can access the system and perform relevant actions based on their roles.

