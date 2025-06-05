# 📝 Browser Extension Audit Report

## 📌 Task Reference
**Internship Task 7: Identify and Remove Suspicious Browser Extensions**

---

## 🛡️ Example Extension Analyzed (Installed for Demonstration)

### 🔹 Extension Name: Sider – Chat with all AI models  
**Version:** 5.10.1  
**Size:** 20.04 MB  
**Source:** Chrome Web Store  

### 🎯 Purpose
This extension was **intentionally installed** to demonstrate how to identify and analyze potentially risky browser extensions for this internship task.

---
### 🔍 Observations
- Asks for **access to read and change all website data**
- Has permission to **read browsing history**
- High privilege for an assistant tool
- Not critical to browser functionality

---
### ⚠️ Risk Level: High  
**Reason:** Could collect sensitive user data across all sites.

### ✅ Action Taken
- Removed from Chrome after review

---

## ✅ Safe Extensions (No Risk Found)

| Extension Name | Reason for Keeping       | Risk Level |
|----------------|--------------------------|------------|
| None           | No other extensions were installed | Safe       |

---

## 📚 Summary of Review Process
1. Accessed `chrome://extensions`
2. For each extension:
   - Checked name and source
   - Reviewed permissions via "Details"
   - Cross-checked for known threats or unusual behavior
3. Installed the "Sider" extension as a case study
4. Removed it after analysis
5. Restarted browser for effect

---

## 🧠 Learning Outcome
- Understood how extensions can track and manipulate user data
- Practiced safe browser configuration
- Learned how to identify red flags in extension permissions
- Gained hands-on experience by simulating a real browser threat scenario

---



