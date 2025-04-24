# 📱 Android App Publishing Guide (Google Play Console)

## 1. ✅ Create App

### From Dashboard:
#### ➤ Set Up Your App
1. **Set Privacy Policy**
2. **App Access**
   - Specify if login credentials are required  
3. **Ads**
   - Indicate if your app contains ads  
4. **Content Rating**
   - Complete the questionnaire to avoid age restriction or removal  
5. **Target Audience**
   - Define your app’s intended age group  
6. **News App**
   - Indicate if the app distributes news content  
7. **Data Safety**
   - Declare data collection, sharing, encryption practices  
8. **Government Apps**
   - Specify if your app is affiliated with government entities  
9. **Financial Features**
   - Declare UPI, banking, wallet or other finance-related functions  
10. **Health**
    - Declare health-related data usage if applicable  
11. **App Category & Contact Details**
    - Select primary category (e.g., Education, Tools)  
    - Add contact email, phone, and website  
12. **Setup Store Listing**
    - Add the following:

---

### 🛍 Store Listing Details

- **App Name** (Max 50 characters)
- **Short Description** (Max 80 characters)
- **Full Description** (Max 4000 characters)
- **App Icon**: 512x512 PNG (no alpha)
- **Feature Graphic**: 1024x500 JPG/PNG
- **Phone Screenshots**:
  - Min: 2 | Max: 8  
  - Aspect ratio: 16:9 or 9:16  
  - Resolution: 320px to 3840px  
- **Tablet Screenshots** (if tablet support is enabled)
- **Optional: Promo Video**
  - YouTube link showcasing app usage

---

## 2. 🌐 Localization (Optional but Recommended)
- Add translations for app title, description, and screenshots if targeting multiple regions/languages

---

## 3. 🔐 App Access Credentials (if required)
- Go to `App Content > App Access`
- Provide login credentials (test account) for reviewers

---

## 4. ⚙️ Technical Configuration & Release Creation

1. **Choose Release Track**  
   - Go to `Release > Production` or `Testing` (Internal/Closed/Open)  
   - Click **Create New Release**

2. **Upload App Bundle**  
   - Upload `.aab` (Android App Bundle) file

3. **Set Version Information**  
   - Provide **Version Code** and **Version Name**

4. **App Signing**  
   - Enable **App Signing by Google Play** (required if not already set up)

5. **Target API Level**  
   - Must target the latest Android API level as required by Google

6. **Add Release Notes**  
   - Write short notes for what's new in the release

7. **Save and Review**  
   - Validate the release setup before submission

---

## 5. 🧪 Testing & QA

- Use **Internal Testing** to distribute builds to your team  
- Enable **Pre-launch Reports** for automated device testing  
- Monitor crashes, ANRs, and performance in Play Console  

---

## 6. 🚀 Submit for Review

- Go to: `Release > Overview`  
- Click **Send for Review**

> ⚠️ **Note**: If **Managed Publishing** is turned **OFF**, your app will be **automatically published** once approved.

---

## 📝 Post-Publishing

- Monitor reviews, ratings, and crash reports  
- Prepare for follow-up updates and improvements  
- Respond to user reviews (recommended for good PR)

---
