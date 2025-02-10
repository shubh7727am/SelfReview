**Self-Review Document**

## **Deliverables and Impact**

### **Major Deliveries & Features Completed**
Over the past period, I have successfully delivered multiple features and enhancements. The most notable ones include:

- **Library Screen Implementation**: 
  - Designed and developed the library screen with a search bar and filter options at the top.
  - Fetched items dynamically from Rapid API.
  - Implemented functionality to add items to the local closet (e.g., all clothes).
  - Marked already added items with a green dot for persistent tracking.
  - Ensured local data storage to maintain a seamless user experience with offline support.

- **Closet Screen Preparation**:
  - Started working on the closet screen, integrating it efficiently into the app architecture.
  - Merging all created repositories into a single app effectively.

- **Scalability and Optimization**:
  - Created a **utils branch** apart from my library screen to include our current architecture implementation and dependencies.
  - Defined a basic **color palette and themes** for UI consistency.
  - Implemented the **base business logic** for functionality like:
    - Fetching data from API.
    - Dependency injection.
    - Base models (Product, Category, etc.).
    - Room database structure and DAO utilities.
    - Network monitor and common utilities.
  - Identified and solved issues related to **image caching and storage strategies**.

### **New Learnings & Their Application**
1. **Clean Code Principles**:
   - Watching **Clean Code videos** changed my approach to coding. Now, I constantly evaluate my code for:
     - **Opacity**: Ensuring method names are clear and self-explanatory.
     - **Rigidity**: Avoiding hardcoded values and making the code flexible.
     - **Inseparability**: Writing modular functions that can be reused efficiently.
     - **Fragility**: Adding proper error handling to improve robustness.
   - Applied these learnings by refactoring one of my old methods to **follow best practices**.

2. **AI Tools & Software Development Practices**:
   - Started utilizing AI tools like **Jammie (for video content summarization), Claude AI (for code refactoring), ChatGPT, and Gemini (for content generation).**
   - Gained proficiency in **project management tools like Jira and Slack**, which improved my collaboration and communication.
   - Developed better **Git practices**, such as committing smaller changes, utilizing SourceTree, and rebasing effectively.
   - Adopted a **scalable approach to software creation**, ensuring the project structure supports future growth.

3. **Structured Development Approach**:
   - Previously, I would dive into coding without planning. Now, I:
     - **Write specifications** before starting a project.
     - **Compare dependencies** to make informed decisions.
     - **Backtrace implementations** to evaluate better alternatives.

4. **Effective Communication & Mentorship**:
   - Under the mentorship of **Prashant Sir**, I learned:
     - **Balancing independence and collaboration.**
     - **Effective team communication.**
     - **Conducting daily stand-up meetings.**
     - **Providing and receiving constructive feedback.**
     - **Long-term career strategies and workplace dynamics.**

### **Challenges & Solutions**
1. **Handling API Keys Securely**:
   - Understood that API keys should not be stored in plaintext inside Android apps. Instead, encryption techniques can be used, but in our case, user authentication on our server makes additional encryption unnecessary.

2. **Local Image Storage Strategy**:
   - Decided on a **hybrid approach**:
     - Store image references (ID, name, paths, low-res copies) in the database.
     - Store high-resolution images in **file storage** for better performance.

3. **Search Implementation for Different Screens**:
   - **Library Search**: Implement network-based search to fetch top results dynamically.
   - **MyCloset Search**: Use local search as all items are already downloaded.

4. **Theme Management in Jetpack Compose**:
   - Decided to store colors in a **centralized Kotlin file** instead of XML for better manageability.

## **Contributions to Peers**

### **Supporting Fellow Engineers**
- **Team Knowledge Sharing**:
  - Shared insights from **Clean Code videos** to help others improve code quality.
  - Hosted discussions on **best practices for Git management**, including rebasing and branching strategies.
  - Conducted knowledge transfer sessions for Kotlin and dependency injection.
  
- **Team Meetings & Collaboration**:
  - Started hosting **regular team meetings** to resolve conflicts and align team members on project goals.
  - Provided Udemy courses and learning resources to **Shanmukha for Kotlin learning**.
  - Assisted **Jayant with debugging issues** and shared my reviews to derive optimal solutions.
  
- **Architectural Design & Standardization**:
  - Developed a **structured architecture** to help the team follow a common scalable structure.
  - Created a **utils branch** with:
    - **Networking setup**
    - **Color palette & theme management**
    - **Base models and business logic**
  - Engaged in discussions with **Ashwini Sir** to refine database structure and optimize implementation.

## **Areas for Improvement**

1. **Task Estimation & Time Management**:
   - Initially estimated completing the **library screen task in 3 days** but ended up taking **10-12 days** due to unexpected issues.
   - Plan to improve by:
     - **Breaking tasks into smaller, more realistic sub-tasks.**
     - **Allocating buffer time for unforeseen challenges.**
     - **Using AI tools to automate routine code tasks.**

2. **Technical Presentation Skills**:
   - While presenting my code to **Ashwini Sir**, I struggled to **clearly convey technical details**.
   - Plan to improve by:
     - **Practicing structured explanations before meetings.**
     - **Using diagrams to illustrate complex architectures.**
     - **Writing concise documentation alongside my code.**

3. **Task Definition & Scope Management**:
   - I tend to define **broad tasks**, leading to incomplete implementations.
   - Plan to:
     - **Define clear, achievable milestones.**
     - **Prioritize core functionality before adding refinements.**

4. **Handwritten Notes for Thought Structuring**:
   - Believe that writing down thoughts helps clarify ideas, but I lack the habit of maintaining structured notes.
   - Plan to start maintaining a **notebook or digital note-taking habit**.

5. **Immediate Issue Resolution**:
   - I often delay solving issues by thinking, "I'll ask someone later."
   - Plan to:
     - **Try resolving issues immediately.**
     - **Seek help proactively when blocked.**

## **Next Steps**

1. **Finalize Room Database Structure** after discussions with Ashwini Sir.
2. **Review codebase with Ashwini Sir** to refine implementation and align team members.
3. **Merge code into a single application** after aligning on architecture.
4. **Optimize workflow using AI tools** for repetitive coding tasks.
5. **Improve team coordination and knowledge sharing** through structured meetings and documentation.

---

This self-review has helped me reflect on my contributions, challenges, and growth areas. Moving forward, I aim to enhance my **time management, communication, and structured planning** to contribute more effectively to the team.

