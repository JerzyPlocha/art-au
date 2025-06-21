#### Functional Requirements

1. **User Registration & Roles**

   * Register as Artisan, Customer, or Trainee.
   * Manage artisan profiles and trainee identities.

2. **Artisan Dashboard**

   * View lists of crafted items and training courses.
   * Mint new NFTs for items and issue training certificates.

3. **NFT Minting & Issuance**

   * Form to input item/course details.
   * Configure monetization: royalties (%), fractional ownership (shares), token-gated content, bundles.
   * Generate mock Token/Certificate IDs and QR codes.

4. **Verification Flow**

   * Input or scan UniqueIdentifier/QR.
   * Display authenticity status, item/course details, artisan info, mint date.

5. **Global Monetization Settings**

   * Default toggles and inputs for royalties, fractional ownership, gating, bundles.

6. **Prototype Characteristics**

   * Mobile-first responsive UI.
   * Clickable navigation; in-memory state; mock data only.
   * Shareable via public URL (e.g., Expo Snack or no-code share link).

#### Non-Functional Requirements

* **Usability & Accessibility**

  * Large touch targets (≥44×44px).
  * High-contrast text, screen-reader friendly labels.

* **Performance**

  * Snappy transitions; minimal load times.

* **Security & Privacy**

  * No real personal data; all mock/demo.
  * No backend integration (read-only blockchain link).

* **Maintainability**

  * Modular code/components if React Native used.
  * Clear naming conventions aligned with domain terms.
