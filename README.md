# CMPG 323 Overview - 39127257
 
# CMPG 323 Overview - <add your student number>

Welcome to the repository for CMPG 323 Overview. This repository is organized to manage multiple projects and their associated documentation.

## Projects and Repositories

Each project in this course will have its own dedicated repository on GitHub. Below is the list of projects and their corresponding repositories:

1. **Project 1**
   - Repository: [Link to Project 1 Repository]([link_to_project_1_repo](https://github.com/PhemeloPearl/CMPG-323-Overview-39127257-)
   - 
2. **Project 2**
   - Repository: [Link to Project 2 Repository](link_to_project_2_repo)

3. **Project 3**
   - Repository: [Link to Project 3 Repository](link_to_project_3_repo)

4. **Project 4**
   - Repository: [Link to Project 4 Repository](link_to_project_4_repo)

5. **Project 5**
   - Repository: [Link to Project 5 Repository](link_to_project_5_repo)

## Documentation

For detailed documentation of each project, please refer to the respective project repositories.

- Documentation: [Link to Overall Documentation](link_to_overall_documentation)

## Branching Strategy

Branching strategy is crucial for enabling developers to collaborate effectively on projects, track changes efficiently, and manage multiple versions of the codebase. There are various Git branching strategies available, each with its own set of pros and cons. Among these, I have chosen to use the GitFlow branching strategy. This strategy aims to enhance productivity by ensuring proper coordination among developers and supporting parallel development, allowing multiple features and bug fixes to be worked on simultaneously. It also helps organize releases in a planned and structured manner, providing a systematic approach to version control. The GitFlow strategy includes several key branches, with the **Master** branch containing the production-ready code and the **Develop** branch serving as the integration point for features and fixes before they are ready for production. This approach not only streamlines the development process but also maps a clear path from making changes in the software to deploying those changes in a production environment. Overall, GitFlow facilitates a well-defined workflow that supports efficient and organized software development.

## .gitignore File

The `.gitignore` file is used in Git to specify which files and directories Git should ignore, preventing them from being tracked in the repository. It helps keep the repository clean by excluding temporary and system files, such as `.DS_Store` on macOS or `Thumbs.db` on Windows. It also ignores editor and IDE-specific files like `*.swp` from Vim and `*.sublime-workspace` from Sublime Text. Build artifacts, such as compiled code and build directories, are often ignored to avoid cluttering the repository. Logs and database files, including `*.log` and `*.sqlite`, are also typically excluded. Dependency and environment files, such as `node_modules/` for Node.js and `venv/` for Python, are ignored to prevent unnecessary files from being tracked. Configuration files and environment variables, which may contain sensitive information, should be excluded for security reasons. Pre-made `.gitignore` templates for various languages and tools can be used as a starting point. Customizing the `.gitignore` file to fit the specific needs of your project ensures that only relevant files are tracked. Properly managing the `.gitignore` file helps maintain a clean and efficient repository.

## Storage of Credentials and sensitive information

Storing credentials and sensitive information in a secure and responsible manner is crucial to protect your data and prevent unauthorized access.

Storage credentials and sensitive protection of information that will be implemented:

Avoiding Hardcoding Credentials

The Use Environment Variables

Configuration Of Files

Version-Controlled Template

Most credentials will be stored using the Git Credential Manager (GCM) is another way to store your credentials securely and connect to GitHub over HTTPS.
