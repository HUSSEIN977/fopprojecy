

# 📝 Digital Diary (Maven JavaFX App)

Digital Diary is a JavaFX-based desktop application that allows users to securely write, manage, and export personal journal entries.
The app includes user authentication, mood tagging, motivational quotes, image attachments, and PDF export functionality.

##  Features

-  User Registration & Login (via username or email)
-  Create, Edit, and Delete Diary Entries
-  Mood Selection with Motivational Quotes
-  Attach Cover Images to Entries
-  Export Diary Entries to PDF
-  Search Entries by Title or Content

## Tech Stack

- **Java 21**
- **JavaFX 21**
- **Maven** for project management
- **Apache PDFBox** for PDF export
- **CSV File Storage** for user and diary data

## Project Structure

├── model/
│ ├── User.java
│ └── DiaryEntry.java
├── data/
│ ├── UserManager.java
│ ├── DiaryManager.java
│ └── FileUtilities.java
├── ui/
│ ├── LoginUI.java
│ ├── DigitalDiaryUI.java
│ ├── PdfExporter.java
│ └── MotivationalQuotes.java
├── Main/
│ └── Main.java
├── resources/
│ └── users.csv, diaries.csv (auto-generated)
├── pom.xml

##  Getting Started

### Prerequisites

- Java 21 or later
- Maven 3.8+
- JavaFX SDK 21

### Build & Run

Run the app using Maven:
mvn javafx:run



##The app starts with the login screen. You can register a new account if needed.



# Data Format
- users.csv
username,email,password
- diaries.csv
ownerUsername,title,content,mood,createdDate,imagePath



# Export Example (PDF)
Each exported diary PDF includes:

Title

Date

Mood

Content

# Note on Security
This demo app stores plaintext passwords. For real applications, use hashing (e.g., BCrypt).

# Contributors
-  HUSSIN MAHMOUD ABDELALL MAHMOUD (22120218)
-  REEM MOHAMED HASSAN DIYAB (23098850)
-  AMRO ALI ANSARI ALI SUROUR (23118003)
-  MAJD MAHER ABOKASH (23105660)
