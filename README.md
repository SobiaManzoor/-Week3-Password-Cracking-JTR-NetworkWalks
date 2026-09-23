# 🔐 PDF Password Cracking Lab

## 📌 Overview

This project is part of the **Networkwalks Cybersecurity Project** and focuses on understanding how password-protected PDF files can be analyzed in a controlled cybersecurity lab environment.

The lab demonstrates the process of extracting a PDF password hash and using password-cracking tools to recover the password and access the protected file.

> ⚠️ **Disclaimer:** This project was performed only in an authorized cybersecurity lab environment using the provided sample PDF files.

---

## 🎯 Objectives

The main objectives of this lab are:

* Understand how password-protected PDF files use hashes.
* Extract the hash value from a locked PDF.
* Understand the role of password-cracking tools.
* Use a controlled lab environment to recover the sample password.
* Verify the recovered password by opening the protected PDF.
* Capture screenshots as evidence of the completed lab.

---

## 🛠️ Tools & Technologies

* **Networkwalks Hash Calculator**
* **Networkwalks Password Cracker**
* **John the Ripper (JTR)**
* **Johnny GUI**
* **OnlineHashCrack**
* **Microsoft Edge / Google Chrome**
* **Notepad**
* **PDF File**

---

# 🔹 Part 1 — Online PDF Hash Extraction

## Step 1: Download the PDF

The provided locked PDF file was downloaded from the lab page.

**File:**
`My Locked PDF1.pdf`

📸 **Screenshot:**
<img width="960" height="540" alt="Screenshot 2026-09-23 205547" src="https://github.com/user-attachments/assets/359cc9a7-3cc9-43ab-b1cc-1d3fd3e2897a" />


---

## Step 2: Generate the PDF Hash

The locked PDF was uploaded to the Networkwalks Hash Calculator.

The tool generated a PDF hash beginning with:

```text
$pdf$
```

The complete generated hash was copied for the next stage.

📸 **Screenshot:**

<img width="960" height="540" alt="PDF hash added" src="https://github.com/user-attachments/assets/b16ed665-3450-49bf-b233-9b05fc3f2242" />
<img width="960" height="540" alt="Hash calculator" src="https://github.com/user-attachments/assets/07b9080f-ff75-4008-ae54-a858fda2e50d" />
<img width="960" height="540" alt="Adding file for hash code" src="https://github.com/user-attachments/assets/570f102f-0046-4334-8884-69bde9106605" />


---

## Step 3: Submit the Hash for Password Recovery

The generated hash was entered into the authorized Networkwalks Password Cracker.

The cracking process was started using the provided lab functionality.

📸 **Screenshot:**

<img width="960" height="540" alt="PDF hash" src="https://github.com/user-attachments/assets/acdc7ce1-7c3d-4a0f-9034-76f6c3b40dfe" />

---

# 🔹 Part 2 — John the Ripper & Johnny GUI

## Step 1: Install John the Ripper

**John the Ripper (JTR)** was used as the password-cracking tool for the practical lab.

The required JTR files were installed and configured before starting the attack.

---

## Step 2: Configure Johnny GUI

**Johnny** was used as the graphical interface for John the Ripper.

The `john.exe` executable was configured through Johnny's settings.

📸 **Screenshot:**
<img width="960" height="540" alt="Johny GUI" src="https://github.com/user-attachments/assets/293b6831-2423-4e5b-bcf0-05e4a72f3eb4" />
<img width="960" height="540" alt="Screenshot 2026-09-23 205831" src="https://github.com/user-attachments/assets/ab366b4c-de84-437f-a7a3-b947876bff15" />

---

## Step 3: Prepare the Hash File

The extracted PDF hash was saved in a text file:

```text
hash1.txt
```

The file was then prepared for use with Johnny.

📸 **Screenshot:**

<img width="960" height="540" alt="J and R" src="https://github.com/user-attachments/assets/d4cbbd3d-0e21-4ea9-ba60-2262254755ab" />


---

## Step 4: Load the Hash

The prepared hash file was loaded into Johnny using the password-file option.

📸 **Screenshot:**

<img width="960" height="540" alt="pswrd detected by Networkwalks tool" src="https://github.com/user-attachments/assets/96b1fd5b-845e-495a-ad77-5cfa48cf2ad8" />
<img width="960" height="540" alt="PDF hash" src="https://github.com/user-attachments/assets/16e27b85-789d-4c09-a7fa-d78383b67436" />

---

## Step 5: Start the Password Recovery Process

A new password-recovery attack was started from Johnny.

The tool processed the supplied PDF hash and attempted to recover the password in the controlled lab environment.

📸 **Screenshot:**



<img width="960" height="540" alt="Unlocked file" src="https://github.com/user-attachments/assets/8e7d4b9c-29a7-4973-8270-e5716a775629" />


---

# 🔹 Part 3 — Password Verification

After the password was recovered, it was used to open the provided locked PDF file.

The PDF was successfully unlocked using the recovered password.

📸 **Screenshot:**

<img width="960" height="540" alt="Unlocked file" src="https://github.com/user-attachments/assets/2e870239-32f2-4af0-9503-7cd436ee55ee" />


---

# 🚩 Lab Flag

After successfully completing the lab, the following confirmation was displayed:

> **"Congratulations! You have captured your 1st flag"**

📸 **Screenshot:**

<img width="960" height="540" alt="Unlocked file" src="https://github.com/user-attachments/assets/53a83ce9-51f5-4048-af68-14637fa170d0" />
<img width="960" height="540" alt="Unlocked file 1" src="https://github.com/user-attachments/assets/fb7b9290-cd0f-44d3-a766-e1d98c65f1a7" />

---

# 📊 Results

| Stage                       | Result      |
| --------------------------- | ----------- |
| Locked PDF downloaded       | ✅ Completed |
| PDF hash generated          | ✅ Completed |
| Hash copied                 | ✅ Completed |
| Password recovery performed | ✅ Completed |
| JTR/Johnny configured       | ✅ Completed |
| Hash file prepared          | ✅ Completed |
| Password recovered          | ✅ Completed |
| Protected PDF opened        | ✅ Completed |
| Lab flag captured           | ✅ Completed |

---

# 📚 Key Learning Outcomes

Through this lab, the following concepts were explored:

* PDF password protection
* Password hashes
* Hash extraction
* Password recovery in a controlled environment
* John the Ripper
* Johnny GUI
* Hash file preparation
* Cybersecurity lab procedures
* Evidence collection through screenshots

---

# 🔒 Ethical & Security Note

Password-cracking techniques should only be used on files, systems, and accounts for which you have explicit authorization.

This project was completed as part of an **authorized Networkwalks cybersecurity training lab** using the provided sample files.

---

# 📁 Project Structure

```text
PDF-Password-Cracking-Lab/
│
├── README.md
│
├── screenshots/
│   ├── hash-calculator.png
│   ├── password-cracker.png
│   ├── johnny-settings.png
│   ├── hash-file.png
│   ├── cracking-process.png
│   ├── unlocked-pdf.png
│   └── captured-flag.png
│
└── hash1.txt
```

> **Note:** Add your own screenshots to the `screenshots` folder and update the filenames if your screenshot names are different.

---

# 👩‍💻 Project Information

**Project:** Networkwalks Cybersecurity Lab
**Module:** Module 1
**Topic:** PDF Password Cracking
**Tools:** John the Ripper, Johnny GUI, Networkwalks Online Tools
**Environment:** Authorized Cybersecurity Training Lab

---

## ⭐ Conclusion

This lab provided practical exposure to password-protected PDF analysis, hash extraction, and password recovery techniques. It also demonstrated how tools such as **John the Ripper and Johnny GUI** can be used within an authorized cybersecurity testing environment.

The successful unlocking of the provided PDF and capture of the lab flag confirmed the completion of the practical task.
