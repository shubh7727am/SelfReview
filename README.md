# SelfReview

Sure! Here’s a draft of your README file:

---

# **Project Documentation: AiCloset App**

## **1. Clean Code Principles**

## **Recognizing Bad Code**
- Issues identified: **opacity, rigidity, inseparability, and fragility** due to unclear naming, hardcoded values, and implicit dependencies.
- Refactoring steps:
  - Improved function names.
  - Removed hardcoded values.
  - Modularized dependencies.
  - Implemented effective logging.

## **Key Takeaways from Clean Code Videos**
- **Readability & Clarity**: Write expressive code that communicates intent without excessive comments.
- **Refactoring Techniques**:
  - "Extract Till You Drop"
  - **Feature Envy**
  - Modularization for focused functions.
- **Polymorphism & Encapsulation**: Adhere to OOP principles.
- **Commenting Best Practices**:
  - Avoid unnecessary comments.
  - Remove outdated comments.
  - Rely on self-explanatory code.
- **Code Formatting & File Management**: Keep files concise, structured, and maintainable.

## **Application of Learnings**
- Optimized code for readability, maintainability, and efficiency.

---

## **2. Tools, Best Practices & Professional Growth**

## **AI & Automation Tools**
- **Jammie**: Summarized video content for efficient learning.
- **Claude AI**: Assisted in code refactoring and analysis.
- **ChatGPT & Gemini**: Enhanced documentation and communication.

## **Project & Team Collaboration**
- **Jira & Slack**: Improved task tracking and teamwork.
- **Scalable Software Development**: Insights into long-term project structuring.

## **Git & Version Control Improvements**
- **Better Commit Habits**: Shifted to **frequent small commits**.
- **SourceTree**: Simplified Git workflow management.
- **Rebasing & Merging**: Enhanced integration and branch management.

## **Software Engineering Best Practices**
- **Spec Writing & Planning**:
  - Started planning before implementation.
  - Updated specifications as needed.
- **Dependency Evaluation**:
  - Compared dependencies for better decision-making.

## **Mentorship & Professional Growth**
- **Guidance from Prashant Sir**:
  - Balanced independence and collaboration.
  - Improved communication in standups and feedback loops.
  - Developed long-term career strategies.
  - Learned to navigate workplace dynamics and job transitions.
  - Understood the balance between skills, money, and happiness.

---

## **3. Software Development & Leadership Contributions**

## **Library Screen Implementation**
- **Item Addition**:
  - Added items linked to the **local database**.
- **Persistent Marking of Added Items**:
  - Green dot displays for added items.
- **Local Data Storage**:
  - Enabled fast access & offline support.
- **Search & Filtering**:
  - Integrated search bar and filtering by categories.

## **Closet Screen Development**
- Initiated development.
- Merged multiple repositories into a single app.

## **Team Collaboration & Leadership**
- **Hosted team meetings**.
- Provided resources & Udemy courses.
- Assisted teammates with Kotlin and other queries.
- **Created a scalable app architecture**.

## **Core Business Logic & Architecture**
- Developed base logic for API data fetching & dependency injection.
- Established Room database structure & DAO utilities.
- Discussed scalability challenges.

## **Problem-Solving & Security Insights**
- **Search Bar Implementation**:
  - Network-based Library Search.
  - Local MyCloset Search.
- **API Key Security**:
  - Explored encryption techniques.

## **Impact & Next Steps**
- Improved team collaboration & knowledge sharing.
- Built a scalable and structured project foundation.
- Solved key implementation challenges.
- Continue closet screen implementation and refine architecture.

---

## **4. Key Architectural Decisions & Insights**

## **API Authentication & Security**
- AiCloset API requires user authentication.

### **Theme Mode Considerations**
- Supporting themes early is a good practice.
- Initially implementing Light theme only.

## **Color Storage Best Practices**
- Storing colors in a centralized Kotlin file.

### **Database Schema Planning**
- Structured Room DB design focusing on products, closet items, and user preferences.

## **Local Image Storage Strategy**
- **Hybrid Approach**:
  - Store low-res copies & metadata in DB.
  - Store high-res images in file storage.

## **Image Storage Visibility**
- Images will be private and synced with the server.
- No retention post-app uninstallation.

## **Image Background Handling**
- Check if AiCloset API provides background-free images.
- Explore background removal techniques if not provided.

## **Next Steps**
- Design a scalable local database schema.
- Implement efficient image storage.
- Confirm API image format and plan background removal.

---

You can copy this content and save it as a README.md file in your project. Let me know if there's anything else you'd like to add or modify!
