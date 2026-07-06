# GitHub Actions-la APK Build Panna (Easy Steps)

## Step 1: GitHub Account
- https://github.com ku pogi free account create pannunga (illana already irundha login pannunga)

## Step 2: New Repository Create Pannunga
1. Top-right "+" icon → "New repository"
2. Name: `SaravanaCaller`
3. **Public** or **Private** — Private select pannunga (safe)
4. "Create repository" click pannunga

## Step 3: Files Upload Pannunga
1. Andha puthu repo page-la **"uploading an existing file"** link click pannunga
2. Intha zip-a extract panni, **ULLA irukura ella files/folders-um** (SaravanaCaller folder itself alla, atula irukura ellam) drag & drop pannunga
   - `.github` folder
   - `app` folder
   - `build.gradle`
   - `settings.gradle`
   - `gradle.properties`
   - `README.md`
   - `gradle` folder
3. Bottom-la "Commit changes" click pannunga

## Step 4: Automatic Build Aagum!
1. Repo top menu-la **"Actions"** tab click pannunga
2. "Build APK" workflow automatic-a run aagi irukum (2-3 minutes edukkum)
3. Green tick ✅ vandhaprom, andha run-a click pannunga
4. Kீழ scroll pannina **"Artifacts"** section-la `SaravanaCaller-APK` irukum → download pannunga
5. Idhu `.zip` file, athuku ulla `app-debug.apk` irukum

## Step 5: Phone-la Install
1. `app-debug.apk` file-a phone-ku transfer pannunga (WhatsApp to yourself, Google Drive, USB)
2. Phone-la open pannina "Install unknown apps" allow pannunga
3. Install pannunga
4. App open panni permissions grant pannunga (previous instructions padi)

## Build Fail Aana?
- Actions tab-la red ❌ irundha, athu click panni error log paarunga
- Screenshot edhuthu anupunga, naan fix pannuren
