# Basic Joins

### 1. Unique ID for Each User
   - **Question:** Write a solution to show the unique ID of each user. If a user does not have a unique ID, show null. Return the result table in any order.
   - **Solution:**
  
<img width="461" alt="1" src="https://github.com/user-attachments/assets/e945be7a-b632-4618-a297-17f7a197a4d9">

   - **Explanation:** This query ensures that each user is displayed with their unique ID, substituting null where no unique ID exists.

### 2. Product Details from Sales
   - **Question:** Write a solution to report the product_name, year, and price for each sale_id in the Sales table. Return the resulting table in any order.
   - **Solution:**
  
<img width="465" alt="2" src="https://github.com/user-attachments/assets/a368b051-6fcd-49b8-a0e0-a814b59a1ceb">

   - **Explanation:** This query retrieves product details including name, year, and price, for each sale, providing a comprehensive view of the sales data.

### 3. Users Without Transactions
   - **Question:** Write a solution to find the IDs of the users who visited without making any transactions and the number of times they made these types of visits. Return the result table sorted in any order.
   - **Solution:**

<img width="470" alt="3" src="https://github.com/user-attachments/assets/2e1c45c5-d4e0-4f56-992c-06f0c4149d1c">

   - **Explanation:** This query identifies users who visited the site but did not make any transactions, along with the count of such visits.

### 4. Higher Temperature Dates
   - **Question:** Write a solution to find all dates' Id with higher temperatures compared to its previous dates (yesterday). Return the result table in any order.
   - **Solution:**

<img width="472" alt="4" src="https://github.com/user-attachments/assets/7b9bbc7f-21b0-45a9-9c3f-9fe567296d85">

   - **Explanation:** This query finds dates where the temperature was higher than the previous day, useful for analyzing temperature trends.

### 5. Average Process Time per Machine
   - **Question:** There is a factory website that has several machines each running the same number of processes. Write a solution to find the average time each machine takes to complete a process. The time to complete a process is the 'end' timestamp minus the 'start' timestamp. The average time is calculated by the total time to complete every process on the machine divided by the number of processes that were run. The resulting table should have the machine_id along with the average time as processing_time, which should be rounded to 3 decimal places. Return the result table in any order.
   - **Solution:**

<img width="591" alt="5" src="https://github.com/user-attachments/assets/ac394423-c69b-4fc7-a5e6-88f1ee8bcb00">

   - **Explanation:** This query calculates the average processing time for each machine, giving insights into machine efficiency.

### 6. Employees with Low Bonuses
   - **Question:** Write a solution to report the name and bonus amount of each employee with a bonus less than 1000. Return the result table in any order.
   - **Solution:**
  
<img width="477" alt="6" src="https://github.com/user-attachments/assets/09349ad4-1c53-407c-a8d1-b328f5311797">

   - **Explanation:** This query lists employees with bonuses below 1000, highlighting those with lower performance rewards.

### 7. Student Exam Attendance
   - **Question:** Write a solution to find the number of times each student attended each exam. Return the result table ordered by student_id and subject_name.
   - **Solution:**
  
<img width="653" alt="7" src="https://github.com/user-attachments/assets/681b34f6-a711-4380-a639-5cfc0e02949c">

   - **Explanation:** This query counts how often students attended exams, sorted by student ID and subject, useful for tracking attendance patterns.

### 8. Managers with Direct Reports
   - **Question:** Write a solution to find managers with at least five direct reports. Return the result table in any order.
   - **Solution:**
  
<img width="471" alt="8" src="https://github.com/user-attachments/assets/5fee65ae-509e-4c7f-ac05-7dd939487162">

   - **Explanation:** This query identifies managers who have at least five subordinates, helping to understand management structure.

### 9. User Confirmation Rate
   - **Question:** The confirmation rate of a user is the number of 'confirmed' messages divided by the total number of requested confirmation messages. The confirmation rate of a user that did not request any confirmation messages is 0. Round the confirmation rate to two decimal places. Write a solution to find the confirmation rate of each user. Return the result table in any order.
   - **Solution:**
  
<img width="473" alt="9" src="https://github.com/user-attachments/assets/c9efca0b-da48-4887-b838-e0536bc73d16">

   - **Explanation:** This query calculates the confirmation rate for each user, showing how effectively users confirm messages.

---

Feel free to explore these solutions and their explanations. Each solution is designed to address the specific problem efficiently and effectively. If you find these solutions helpful, please star this repository and follow my progress!
