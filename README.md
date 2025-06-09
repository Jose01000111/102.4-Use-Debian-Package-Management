# 🖥️ 102.4-Use-Debian-Package-Management

## 🖧  Introduction
I explored core package management tools in Debian 🐧. These tools are essential for Linux administrators and are heavily tested in the LPIC-1 exam. I focused on both manual .deb installs and working with APT repositories. 💻

I’ve included some helpful links to guide you through the lab and for studying afterward:

[102.4 Use Debian Package Management Exam Objective](https://www.lpi.org/our-certifications/exam-101-102-objectives/#102.4_Use_Debian_package_management)

[LPIC 102.4 NOTES]()

[LPIC 102.4 LAB]()

---

### 0️⃣ Create Your Own .deb File from Scratch 🛠️

Creating your own Debian package is a fantastic hands-on intro to how packages are built and installed. Let’s make a simple .deb that installs a custom shell script.

📂 Step 0.1: Create a working directory

![qsUE86s](https://github.com/user-attachments/assets/c9106181-b7bf-46e9-90f9-0adf569c70f7)

🧾 Step 0.2: Create a script or dummy file

![LM5vKQk](https://github.com/user-attachments/assets/462f9893-a4a8-47d4-a88d-e46d1dacdf27)

📁 Step 0.3: Create the DEBIAN control file

![2iaqjUJ](https://github.com/user-attachments/assets/92a399eb-354c-4df7-81df-e924b2e864a5)

📦 Step 0.4: Build the .deb file

![oA7qo6A](https://github.com/user-attachments/assets/b50ae597-a226-4ec3-be37-336e0b952b3b)

🔍 Step 0.5: Test installing your package

![MfOEagv](https://github.com/user-attachments/assets/9c458432-16db-42ca-8fd0-48681a070798)

🧪 6. Test It

![QTSVFVE](https://github.com/user-attachments/assets/99f7d143-53a8-44c2-ab26-239829f466c2)

### 1️⃣ Upgrade and Uninstall Debian Binary Packages📟

🔹 Fixing broken dependencies after manual install

![oA7qo6A](https://github.com/user-attachments/assets/1f262baf-884b-4fd2-a0ba-ea0d16a77382)

🔹 Upgrading installed packages using APT



🔹 Removing a package without config files

🔹 Purging a package (remove including config files)

### 2️⃣📡 Find Packages Containing Specific Files or Libraries
🔹 Checking which installed package owns a file

🔹 Installing and updating apt-file for repo-wide searches

🔹 Searching for the package that provides a specific file

### 3️⃣ Obtain Package🗂️ Info: Version, Content, Dependencies, and Status
🔹 Listing all installed packages

🔹 Showing full package information

🔹 Checking the installation status of a package

### 4️⃣ Awareness of APT 🌐

🔹 Updating package lists from /etc/apt/sources.list

🔹 Installing packages from remote repositories

🔹 Searching for packages by keyword

🔹 Viewing or editing the APT sources list

## 📚 What I Learned
This lab gave me practical experience in using Debian’s package tools to install, remove, troubleshoot, and inspect packages. I now feel confident using dpkg, apt-get, and apt-cache, and I understand how Debian manages both local and remote packages. 🧠📦
