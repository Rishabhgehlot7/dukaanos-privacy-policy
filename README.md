# Privacy Policy for DukaanOS

**Effective Date:** October 11, 2026  
**Last Updated:** October 11, 2026  
**Application Version:** 1.0.0+1  

Welcome to **DukaanOS** ("we," "our," or "us"). DukaanOS is a smart retail operating and billing software application developed by BoostEngine / Rishabh Gehlot to help retail merchants, shopkeepers, and wholesalers efficiently manage their daily point-of-sale (POS) billing, digital ledger (Khata / Udhaar-Jama), and product inventory.

We are committed to respecting and protecting the privacy of our merchants and their customers. This Privacy Policy details our policies regarding the collection, use, protection, and disclosure of information when you use our mobile application and services.

---

## 1. Information We Collect

To provide our POS billing and ledger management services, DukaanOS collects the following categories of information:

### A. Merchant Business Profile Information
When you set up or use your store profile, we collect:
- **Shop / Business Name:** To identify your retail store.
- **Merchant Name:** The shop owner or primary manager.
- **Phone Number & Email Address:** Used for authentication, account recovery, and customer support.
- **Store Address & GSTIN (Optional):** Used exclusively for printing on sales tax invoices and receipts.

### B. Transactional & Store Operations Data
- **Inventory & Catalog:** Product names, selling prices, purchase prices, stock quantities, and barcode numbers.
- **Sales & Invoices:** Digital sales receipts, items purchased, totals, discount amounts, and payment modes (Cash, Online/UPI).
- **Digital Ledger (Khata / Customer Records):** Customer names, phone numbers, credit/debit balances (उधार / जमा), notes, and transaction timestamps.

### C. Authentication Information
- When you sign in using Google Sign-In or Firebase Authentication, we receive unique secure authentication credentials (UID, email). We do **not** collect or store your personal account passwords.

---

## 2. Device Permissions and Usage

DukaanOS requests specific Android device permissions strictly necessary for business utility:

* **Camera (`android.permission.CAMERA`):**  
  Used **strictly for scanning product barcodes and QR codes** to instantly add items to the billing cart or look up product details. DukaanOS does **not** capture photos of individuals, record video, or store any camera images.
* **Internet Access (`android.permission.INTERNET`, `ACCESS_NETWORK_STATE`):**  
  Required to securely synchronize your offline store entries with our cloud database (Firebase Firestore) so your business data is backed up safely in real time.
* **Bluetooth (`BLUETOOTH`, `BLUETOOTH_CONNECT` / `BLUETOOTH_SCAN`):**  
  Used optionally if you choose to connect a 58mm / 80mm wireless thermal ESC/POS receipt printer to print paper receipts.

---

## 3. How We Use Your Information

We use the collected information solely for:
- Operating and maintaining the DukaanOS billing engine and khata management.
- Enabling automatic real-time cloud backup to prevent data loss if your mobile device is damaged or lost.
- Generating sales analytics, daily revenue reports, and ledger summaries for the merchant.
- Facilitating customer receipt sharing via standard Android share sheets (e.g. WhatsApp).

---

## 4. Data Sharing & Third-Party Services

**We do NOT sell, rent, monetize, or trade your business data, sales numbers, or customer records to any third-party advertisers or data brokers.**

We rely on trusted enterprise infrastructure:
- **Google Firebase (Google Cloud Platform):** Authentication and secure cloud database (Firestore) hosting. All network communications are encrypted via TLS/HTTPS, and database storage is encrypted at rest using AES-256.
- **WhatsApp (Meta Platforms):** Used only as an intent trigger when you choose to share a bill or payment reminder with your customer. DukaanOS does not read or intercept your personal chats.

---

## 5. Data Retention and Account Deletion

You retain full ownership and control over all data recorded in DukaanOS:
- **In-App Editing & Deletion:** You can edit or delete individual transactions, invoices, customers, and inventory items directly within the app at any time.
- **Complete Account & Data Erasure:** If you wish to permanently delete your account and erase all associated business records from our cloud database, please contact our support team at **boostengine001@gmail.com** or **rishabh3x@gmail.com** with your registered mobile number/email. All associated cloud data will be permanently wiped within 30 days.

---

## 6. Children's Privacy

DukaanOS is a commercial point-of-sale tool intended strictly for business operators and adults aged 18 and older. We do not knowingly collect personal information from children under 13.

---

## 7. Changes to This Privacy Policy

We may update this Privacy Policy periodically. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Last Updated" date.

---

## 8. Contact Us & Grievance Redressal

If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us:

- **Entity / App:** DukaanOS (BoostEngine)
- **Developer:** Rishabh Gehlot
- **Email:** boostengine001@gmail.com / rishabh3x@gmail.com
- **Address:** Jodhpur, Rajasthan, India
