# 🖥️ 102.4-Use-Debian-Package-Management

## 🖧  Introduction
I explored core package management tools in Debian 🐧. These tools are essential for Linux administrators and are heavily tested in the LPIC-1 exam. I focused on both manual .deb installs and working with APT repositories. 💻

I’ve included some helpful links to guide you through the lab and for studying afterward:

[102.4 Use Debian Package Management Exam Objective](https://www.lpi.org/our-certifications/exam-101-102-objectives/#102.4_Use_Debian_package_management)

[LPIC 102.4 NOTES]()

[LPIC 102.4 LAB](https://1drv.ms/w/c/354f1c8d534fbced/ES8_Htw7HXdPi0U3FYU3MH4BMxOQVcrmNRTtZKnv3fRWHg?e=KfthDA)

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

![H69F6zk](https://github.com/user-attachments/assets/031d63f5-ee8a-49d7-83b5-e6a456e0dedd)

🔹 Upgrading installed packages using APT

![mw59xUx](https://github.com/user-attachments/assets/f0d4f176-b83c-4e09-91f5-c288dbb87c7a)

🔹 Removing a package without config files

![SMtXUuS](https://github.com/user-attachments/assets/7a815aad-fc82-4cc9-bfcd-e6c08b5109e5)

🔹 Purging a package (remove including config files)

![DJJ9RjB](https://github.com/user-attachments/assets/0b1078fc-b047-4436-a0f3-21ae49e265db)

### 2️⃣📡 Find Packages Containing Specific Files or Libraries

🔹 Checking which installed package owns a file

![3mCX24d](https://github.com/user-attachments/assets/f5462cdd-501f-4d93-b54c-6c82be81b001)

🔹 Installing and updating apt-file for repo-wide searches

![xvfiHh1](https://github.com/user-attachments/assets/837f8ba1-d6c0-43db-9431-27afd226b43c)

🔹 Searching for the package that provides a specific file

![IfgLQsn](https://github.com/user-attachments/assets/0ee400c0-9b16-45ae-b1cb-1fdbf5af9127)

### 3️⃣ Obtain Package🗂️ Info: Version, Content, Dependencies, and Status

🔹 Listing all installed packages

![csk2QlO](https://github.com/user-attachments/assets/2dce98b5-1d01-410b-a2bd-9b2d1f327695)

🔹 Showing full package information

🔹 Checking the installation status of a package

![JIKcQNB](https://github.com/user-attachments/assets/9861b0bf-6913-4eda-b72d-37cce4758cf9)

### 4️⃣ Awareness of APT 🌐

🔹 Updating package lists from /etc/apt/sources.list

![pG9XKOb](https://github.com/user-attachments/assets/132a6e8d-e051-4910-a7a6-864b249c7a31)

🔹 Installing packages from remote repositories

![fyXBDn9](https://github.com/user-attachments/assets/54ad2f65-fb69-48cf-aaeb-20c30042856b)

🔹 Searching for packages by keyword

🔹 Viewing or editing the APT sources list

![drhDXxo](https://github.com/user-attachments/assets/0ba42f1b-8192-46af-a1e0-e805d23e8dcb)

## 📚 What I Learned
This lab gave me practical experience in using Debian’s package tools to install, remove, troubleshoot, and inspect packages. I now feel confident using dpkg, apt-get, and apt-cache, and I understand how Debian manages both local and remote packages. 🧠📦
