SHELF TRACKER - NEW APK REPOSITORY
The key and login domain are already filled in. Nothing to edit.
1. github.com > + > New repository > name: shelf-tracker-apk > Private > Create.
2. Add file > Upload files. Open the unzipped shelf-apk folder and drag in the ITEMS INSIDE it:
   www, docs, package.json, capacitor.config.json, schema.sql, .gitignore. Commit.
3. Add file > Create new file. Name: .github/workflows/build-apk.yml  (paste the text from build-apk.yml in this zip). Commit.
4. Actions > Build APK > Run workflow. Download the artifact shelf-tracker-apk, install app-debug.apk on the PDA.
5. PC page: Settings > Pages > Branch main > folder /docs > Save.
Staff log in with their Dock Manifest username and password.
