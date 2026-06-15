# Privacy Policy – FormaG

**Last updated:** June 15, 2026

This Privacy Policy explains how FormaG (“Application”) handles user information. We take your privacy seriously and are transparent about the data processing required for the functionality and improvement of the Application.

---

## 1. Data Collection and Purpose

To enable advanced analysis and continuous improvement of the tool, FormaG collects specific technical data from the tests performed.

### 1.1 Technical Data and Images
The data collected by the Application consists **strictly and exactly of the same information generated in the report that is saved locally on the user's device**, alongside the **exact timestamp (date and time)** indicating when the report was created. 

We do **not** collect any personal, sensitive, or identifiable information about the users (such as your name, email address, phone number, device accounts, or precise GPS location).

### 1.2 Purpose of Collection
This data is processed and used **strictly for scientific research, statistical studies, and technical improvements** of the FormaG tool by the developers. The data is stored securely and is **not** commercialized, leased, or used for user profiling or advertising.

---

## 2. Permissions Used

The application requests only the permissions strictly necessary for its technical execution:

### 2.1 Camera
* Used to allow the user to capture images of the samples directly within the app.
* These images are integrated into the PDF report and sent to the cloud storage for research purposes as described in Section 1.

### 2.2 Storage / Media Access
* Used to save the generated PDF reports into the device's public "Documents" directory, allowing the user to access, view, and share their history freely.

---

## 3. Data Synchronization and Offline Support

FormaG includes built-in offline synchronization features:
* If a network connection is unavailable when a report is completed, the technical data and images are temporarily stored in a private, encrypted local directory on the device.
* An automated background worker (**Android WorkManager**) schedules the transmission of this file. As soon as a stable internet connection is detected, the file is securely uploaded and immediately deleted from the private local cache, avoiding unnecessary storage consumption on the user's device.
* The copy stored in the user's public "Documents" folder is **never** deleted by the application.

---

## 4. Third-Party Services and Infrastructure

FormaG utilizes secure cloud infrastructure to handle data transmission and storage:

* **Firebase Storage (Google LLC):** Used as our cloud repository to store the uploaded test reports and images. Data is protected by strict backend security rules that prevent unauthorized public reading, writing, or tampering.
* **Google Play Services:** Used to support core Android background dependencies.

No other external analytic trackers, ad networks (such as AdMob), or marketing third-party services are integrated into this application.

---

## 5. User Consent and Access Restrictions

The collection and processing of test data are fundamental to the operation and purpose of FormaG. 
* Upon the first launch of the Application, the user will be presented with a mandatory Terms of Use and Privacy Policy acceptance screen.
* Agreement to these terms is a **strict requirement** to access and use the Application's features. If you do not agree to these terms, you must not use the Application.

---

## 6. Personal Accounts and Identity

FormaG **does not** require user registration, login creation, or account linking. We do not collect your name, email address, phone number, or precise GPS location. The uploaded technical reports are identified by dynamic, non-personally identifiable timestamps.

---

## 7. Security

We implement rigorous technical and administrative security measures within Firebase to protect the transmitted data against unauthorized access, loss, or alteration. However, because the files are also stored locally in the user's public directory, we highly recommend keeping your device updated and secure.

---

## 8. Changes to This Policy

We may update our Privacy Policy from time to time. Any changes will be reflected by the "Last updated" date at the top of this page. The latest version will always be accessible via the link provided in the Google Play Store listing and within the application interface.

---

## 9. Contact

If you have any questions or suggestions regarding this Privacy Policy, please contact the developer:

* **Email:** otavio04g.dev@gmail.com
