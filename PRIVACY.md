# Privacy Policy for YFull Finder (Ajwla)
**Last Updated:** January 18, 2026
This Privacy Policy describes how the **YFull Finder** browser extension ("we," "our," or "the extension") handles user data. Our primary goal is to provide a tool for genetic genealogy research while respecting your privacy.
## 1. Data We Collect
The extension is designed to be as "lean" as possible. We only collect data that is strictly necessary for the core functionality of the service:
*   **Authentication & Identity:** When you sign up or log in, we collect your **Email Address** and a **Username (Display Name)**. These are used to create your profile and attribute the DNA samples you contribute to the community database.
*   **Authentication Credentials:** We handle **Passwords** and **Session Tokens** through the secure Supabase Auth service.
*   **Website Content:** To provide its core function, the extension reads **Sample IDs** (e.g., YF12345) from the `yfull.com` domain. This data is used only to query our database for matching genealogical information to display to you.
## 2. Data Usage
Your data is used exclusively for the following purposes:
*   **Database Enrichment:** To display surnames, tribes, and ancestral regions next to samples on YFull.com.
*   **User Profiles:** To track your personal contribution statistics (how many samples you've added).
*   **Security:** To prevent spam and unauthorized access to our backend via authenticated sessions.
**We DO NOT:**
*   Sell your data to third parties.
*   Store your browsing history outside of the `yfull.com` domain.
*   Use your data for marketing or advertising purposes.
*   Collect financial, medical, or precise location information.
## 3. Data Storage & Security
*   **Local Storage:** We use `chrome.storage.local` to store your session token and UI preferences (theme, language). This data remains on your device.
*   **Cloud Storage:** Your profile data and contributed samples are stored in a secure **Supabase (PostgreSQL)** database.
*   **Encryption:** All communication between the extension and our backend is encrypted via HTTPS/TLS.
## 4. User Control & Privacy Choices
*   **Anonymous Contributions:** Users can choose the "Anonymous" (Shadow Profile) option when adding samples. This saves the genealogical data to the community database without public attribution to your account.
*   **Account Deletion:** You can request the removal of your account and associated data by contacting the project administrator through the Web Portal.
## 5. Third-Party Services
We use **Supabase** (as a backend provider) to handle authentication and database storage. Their privacy policy applies to the infrastructure level of data handling.
## 6. Contact Us
If you have questions about this Privacy Policy or how your data is handled, please contact us via the **Contact Admin** tab in the YFull Finder Web Portal.
