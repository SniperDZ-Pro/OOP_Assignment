# OOP Lab 0: Introduction to Version Control

Welcome to the Object-Oriented Programming (OOP) course. This preliminary workshop is designed for 2nd-year Computer Engineering students. Mastering GitHub is a mandatory prerequisite for this course. You will use it continuously to download starter code, execute projects, submit assignments, and collaborate securely.

---

## Part 1: GitHub Account Creation
1. Visit [GitHub](https://github.com) and click **Sign up**.
2. Follow the prompts to create your account. Use a professional username (e.g., `firstname-lastname`).
3. Verify your email address.

## Part 2: Installing & Linking GitHub Desktop
1. Download **GitHub Desktop** from [desktop.github.com](https://desktop.github.com/download/).
2. Install and launch the application.
3. Click **Sign in to GitHub.com** and authorize the application in your browser.

## Part 3: Creating a Repository on GitHub
*A repository (repo) is the digital folder for your project, tracking all changes.*
1. Go to your GitHub dashboard and click the green **New** button.
2. **Repository name:** Enter a descriptive name (e.g., `OOP-Fundamentals`).
3. **Privacy:** Choose **Private** (to protect your assignments) or **Public**.
4. **Initialization:** Check **Add a README file** and select **Java** from the **Add .gitignore** dropdown.
5. Click **Create repository**.

## Part 4: From Local Folder to GitHub
*How to publish an existing local folder to GitHub.*
1. **Create Local Folder:** Create a new folder on your computer named `OOP_Assignment`.
2. **Add to Desktop:** Open GitHub Desktop. Go to `File > Add local repository`.
3. **Select Folder:** Click **Choose** and select your new folder.
4. **Initialize Git:** A warning will state this isn't a Git repo. Click the blue **create a repository** link.
5. **Configure:** Ensure **Git ignore** is set to **Java** (this prevents uploading unnecessary files later when we switch to our IDE). Click **Create repository**.
6. **Publish:** Click the blue **Publish repository** button. Choose your privacy setting and push!

---

## Individual Practical Tasks
To validate your understanding, complete the following tasks individually:

### Task 1: Environment Setup
Create a new folder on your computer (e.g., on your Desktop) named `OOP_Lab0_[YourLastName]`. Open GitHub Desktop, go to `File > Add local repository`, and select this new folder. Click the **create a repository** link, ensure you select **Java** for the `.gitignore` (to prepare for future IDE integration), and publish it as a **Private** repository.

### Task 2: First Object-Oriented Code & Commit
Open any text editor of your choice (e.g., Notepad++, VS Code, or standard Notepad). Create a new file, write a simple class containing three attributes (`name`, `id`, `major`) and an empty constructor, and save the file as `Student.java` inside your `OOP_Lab0_[YourLastName]` folder. Open GitHub Desktop, write a summary for your commit (e.g., "Add Student class structure"), and click **Commit to main**.

### Task 3: Push and Online Verification
Click **Push origin** in GitHub Desktop to upload your committed changes. Open your web browser, navigate to your GitHub repository, and verify that `Student.java` is visible and formatted correctly.

### Task 4: Collaboration (Assignment Submission)
In your GitHub repository settings on the web, navigate to **Settings > Collaborators**. Add your professor's GitHub username to grant them access to evaluate your code.
