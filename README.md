# MEDICINE-CHECKER-SYSTEM
  "A Python-based Medicine Checker System that lets users search, add, update, remove, and list medicines using an interactive menu. It stores details like dosage, uses, precautions, side effects, and availability in a structured dictionary database."
# 💊 Medicine Checker System

## 🌟 Overview of the Project

The Medicine Checker System is a simple, command-line interface (CLI) application designed to manage a database of medicines. It allows users to quickly **search** for medicine details, **add** new entries, **update** existing information, **remove** entries, and **view** a list of all medicines. This system is ideal for a small pharmacy, clinic, or personal use to keep track of essential drug information like dosage, precautions, uses, side effects, and stock availability.

## ✨ Features

* **Search Medicine:** Quickly retrieve all details (Uses, Dosage, Side Effects, Precautions, Availability) for a specific medicine name.
* **Add New Medicine:** Input details to add a new medicine entry to the database.
* **Update Existing Medicine:** Modify any field (uses, dosage, side effects, precautions, availability) for an existing medicine. Users can skip fields they don't wish to change.
* **Remove Medicine:** Delete a medicine entry from the database.
* **Show All Medicines:** Display a list of all medicine names currently in the database.
* **Case-Insensitive Search:** Medicine names are stored and searched in lowercase for user convenience.

## 💻 Technologies/Tools Used

* **Language:** Python 3.x
* **Tools:** Standard Python IDLE or any compatible code editor/IDE (e.g., VS Code, PyCharm).
* **Database:** A simple Python **dictionary** (`medicines`) is used to store and manage all data in memory.

## ⚙️ Steps to Install & Run the Project

1.  **Prerequisite:** Ensure you have Python 3.x installed on your system.
2.  **Save the Code:** Copy the entire Python code provided above and save it into a file named, for example, `medicine_checker.py`.
3.  **Run the File:** Open your command line or terminal, navigate to the directory where you saved the file, and run the following command:
    ```bash
    python medicine_checker.py
    ```
4.  **Access:** The system's main menu will appear in the terminal, prompting you to enter a choice.

## 🧪 Instructions for Testing

After running the script, you can test the following functionalities using the initial sample data (`medomol`, `zyrtec`, `nurofen`):

1.  **Test Search:**
    * Choose option **1**.
    * Search for an existing medicine (e.g., `Medomol`). Verify the correct details are printed.
    * Search for a non-existent medicine (e.g., `Asprin`). Verify the "Medicine not found" message.
2.  **Test Add New Medicine:**
    * Choose option **2**.
    * Enter a unique medicine name and its required details.
    * Choose option **5** to verify the new medicine is listed.
3.  **Test Update Existing Medicine:**
    * Choose option **3**.
    * Enter an existing medicine name (e.g., `Nurofen`).
    * Enter new information for one or more fields (e.g., change 'New availability: In stock'). **Leave all other fields blank.**
    * Choose option **1** to search for the updated medicine and verify only the changed field was modified.
4.  **Test Remove Medicine:**
    * Choose option **4**.
    * Enter a medicine name (e.g., `Zyrtec`).
    * Choose option **5** to verify the medicine name is no longer listed.
5.  **Test Exit:**
    * Choose option **6** to confirm the application gracefully exits.