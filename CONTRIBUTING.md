### 📚 Contributing Translations

Thank you for helping to translate the **ChessScanner App**! 🌍 Your contributions help make this app accessible to more people worldwide.

#### ⚠️ Contribution Agreement
By contributing, you agree that your translations can be used in the app without compensation.

#### 🛠 How to Contribute
1. **Fork the Repository**
    - Click the "Fork" button on GitHub to create a copy of the repository in your account.

2. **Locate the Localization Files**
    - Go to the `/locales/` folder.
    - Find the existing language files (e.g., `en.xml` for English).

3. **Add a New Language**
    - Copy the `en.xml` (or another reference file).
    - Rename it using the appropriate language code (e.g., `fr.xml` for French, `es.xml` for Spanish).
    - Translate the values while keeping the keys unchanged.

   **Example (`en.xml`):**
   ```xml
    <resources>
        <string name="welcome">Welcome to our app!</string>
        <string name="logout">Log out</string>
    </resources>
   ```  
   **Example (`fr.xml`):**  
   ```xml
   <resources>
        <string name="welcome">Bienvenue dans notre application!</string>
        <string name="logout">Se déconnecter</string>
   </resources>
   ```  

4. **Submit a Pull Request (PR)**
    - After translating, commit your changes and push them to your forked repository.
    - Open a **Pull Request** (PR) to the main repository.
    - In the PR description, mention the language added and any notes for reviewers.

#### ✅ Guidelines for Translations
- Keep translations **clear and natural**—avoid direct word-for-word translations.
- Use **formal/informal** tone depending on the language norms.
- **Do not modify keys** — only change the values.
- If a term is **hard to translate**, leave a comment or open an issue for discussion.

#### 🔍 Reviewing Translations
- If you are a native speaker, you can help **review translations** before they are merged!
- Leave comments on PRs if you notice any improvements needed.

#### 💡 Need Help?
If you have any questions or need clarification, feel free to open an **Issue** or join the discussion.

Thank you for your contribution! 🎉🚀  
