[Home](index.md) | [Manual Assessment Memo](manual_assessment_memo.md) | [Chatbot](chatbot.md) | [Procedure Video](procedure_video.md) | [Manual](manual.md) | [Reflective Blogs](reflective_blogs.md) | [Statement of AI](AIstatement.md) 

# Manual 

## GitHub Pages: A Beginner-Friendly Guide for Students and Hobby Coders 
<img src="githubcat.jpg" alt="GitHub Cat" width="900">

### Table of Contents 

    1. Introduction to GitHub & GitHub Pages 

    2. Why Use GitHub Pages? 

    3. Getting Started with GitHub 

    4. Creating Your First Repository 

    5. Understanding Branches & Commits 

    6. Forking Repositories and Why It Matters 

    7. Introduction to GitHub Pages Hosting 

    8. Creating a GitHub Pages Site (Step-by-Step) 

    9. Using a Custom Domain with GitHub Pages 

    10. Using Jekyll for Blog-Style Sites 

    11. Theme Customization 

    12.  Markdown Basics for GitHub Pages 

    13. Using HTML, CSS, and JavaScript with GitHub Pages 

    14. Project Ideas to Host with GitHub Pages 

    15. Common Errors and How to Fix Them 

    16. GitHub Desktop: An Easier Way to Manage Repos 

    17. More GitHub Features to Explore 

    18. Useful Resources & Communities 

    19. Glossary 

    20. Final Tips & What’s Next 

### 1. Introduction to GitHub & GitHub Pages 

GitHub is a cloud-based platform where developers store code, collaborate on projects, and manage version control using Git. GitHub Pages is a free feature that allows you to publish static websites directly from your GitHub repository. 

### 2. Why Use GitHub Pages? 

    - Free Hosting: No cost for hosting simple HTML/CSS/JS websites 

    - Perfect for Portfolios: Show off projects, resumes, blogs 

    -  No Server Management: Everything is served as static content 

    - Version Control: Easily roll back to previous versions 
    
### 3. Getting Started with GitHub 

    1. Go to github.com 

    2. Create an account (free) 

    3. Set your username, email, and password 

    4. Verify your email and log in 

### 4. Creating Your First Repository 

    1. Click the + in the top-right and select New Repository 

    2. Name it (e.g., my-portfolio) 

    3. Add a description (optional) 

    4. Choose Public or Private 

    5. Check Initialize this repo with a README 

    6. Click Create Repository 

### 5. Understanding Branches & Commits 

    - Branch: A version of your project. The default is usually main. 

    - Commit: A snapshot of your code. Each time you make changes, write a message like "Added homepage layout" and commit them. 

    - Use Pull Requests to merge changes from one branch to another. 

### 6. Forking Repositories and Why It Matters 

    Forking is copying someone else's repository to your own account so you can experiment or improve it. 

    Why Fork?:

    - Try out code safely 

    - Make changes and suggest improvements with Pull Requests 

   -  Build on open-source projects 

    How to Fork: 

    - Visit any public repository 

    - Click Fork in the top right 

    - It creates a copy in your GitHub account 

    - Work on your fork without affecting the original repo 

 ### 7. Introduction to GitHub Pages Hosting 

    GitHub Pages lets you publish a website directly from your repository using the files in your main or gh-pages branch. 

    You can host: 

    -  Project Pages (in a specific repo) 

    - User Pages (from a repo named username.github.io) 

### 8. Creating a GitHub Pages Site (Step-by-Step) 

    1. Create or open your repo 

    2. Add your HTML/CSS/JS files 

    3. Go to Settings > Pages 

    4. Under "Source," select main branch (or docs/ folder) 

    5. Click Save 

    6. Your site is now live at https://yourusername.github.io/repo-name/ 
    
### 9. Using a Custom Domain with GitHub Pages 

Want to use your own domain? 

    1. Buy a domain name from a registrar (e.g., Namecheap) 

    2. In your repo, go to Settings > Pages and enter your domain 

    3. Update your DNS settings: 

        -  Add a CNAME record pointing to yourusername.github.io 

    5. Confirm in GitHub that your domain is connected 

### 10. Using Jekyll for Blog-Style Sites 

Jekyll is a static site generator built into GitHub Pages. It turns Markdown files into blog posts. 

    - Use a theme with _config.yml 

    - Create blog posts in _posts/ with the format YYYY-MM-DD-title.md 

    - Add front matter like: 

        --- 
        title: "My First Blog" 
        date: 2025-04-08 
        --- 

### 11. Theme Customization 

Choose a theme via Settings > Pages > Theme Chooser. 

Or manually set it in _config.yml: 

theme: minima 

Customize colors, fonts, and layouts with custom CSS and HTML overrides. 

### 12. Markdown Basics for GitHub Pages 

Markdown is a lightweight markup language that allows you to format text easily. It’s often used in GitHub repositories, README files, and wikis. Markdown files have a .md extension and are a great way to document your projects, write blog posts, or create structured content for GitHub Pages. 

Here are some rules of thumb: 
    - # Heading 1 

    - ## Heading 2 

    - **bold**, *italic*, `code` 

    - Lists: -, *, 1. 

    - Links: [text](url) 

    - Images: ![alt text](image.jpg) 
