# 🤝 Contributing to IntelXSS 

<div align="center">

![IntelXSS Logo](/assets/intelxss_logo.png)

**Share Your XSS Discoveries. Become a Recognized Contributor.**

[![Get Listed As Contributor](https://img.shields.io/badge/🌐_Visit_Website-intelxss.in_(Click_Here)-00d4aa?style=for-the-badge)](cryptonicarea.wuaze.com/intelxss)

</div>

---

## 🎯 **How to Add Your Payload**

### **Step 1: Fork the Repository**
Fork the IntelXSS repository on GitHub to your account: [Fork Repository](https://github.com/karndeepbaror/IntelXSS/fork)

### **Step 2: Add Your Payload**
Edit `data/payloads.yaml` and add your XSS payload using YAML format (no escaping needed!):

```yaml
- code: |
    <script>alert("Hello World")</script>
  description: "Description of what your payload does"
  category: "advanced"
  contributor: "Your Full Name"
  github_username: "your-github-username"
  country: "Your Country"
  tags: ["bypass", "script", "alert"]
  browsers: ["Chrome", "Firefox", "Safari", "Edge"]
  date_added: "01-01-2026"
```

### **📝 Format Notes:**
- **Date Format:** Use DD-MM-YYYY format (e.g., "01-01-2026")
- **Contributor:** Use your full name
- **GitHub Username:** Your GitHub username for profile linking
- **Tags & Browsers:** Use inline array format ["item1", "item2"]

### **Step 3: Test Your Payload**
Before submitting, ensure your payload:
- ✅ Works in specified browsers
- ✅ Is properly categorized
- ✅ Has clear description and context
- ✅ Follows ethical usage guidelines

### **Step 4: Submit Pull Request**
Create a pull request with your contribution. Include:
- ✅ Clear PR title
- ✅ Payload testing results
- ✅ Browser compatibility notes
- ✅ Proper contributor attribution


---

## 📋 **Available Categories**

Choose the most appropriate category for your payload:

- **basic** - Simple, fundamental XSS vectors
- **advanced** - Complex techniques requiring expertise
- **bypass** - Filter and encoding bypass methods
- **waf** - Web Application Firewall evasion
- **csp** - Content Security Policy bypasses
- **polyglot** - Multi-context universal payloads
- **mobile** - Mobile-specific attack vectors
- **dom** - DOM-based XSS techniques
- **event** - Event handler based attacks
- **browser** - Browser-specific quirks and features
- **framework** - Framework-specific vulnerabilities
- **context** - Context-specific injection methods
- **unicode** - Unicode and encoding attacks
- **blind** - Blind XSS techniques
- **social** - Social engineering combined XSS
- **api** - API-related XSS vectors
- **unique** - Rare or unique attack methods
- **non-english** - Non-English character attacks

---

## 🏆 **Contributor Recognition**

### **Automatic Benefits:**
- Recongnic for [Community Support](https://whatsapp.com/channel/0029Vb6plDSBKfi3qGz2fq0f)
- GitHub profile linked to your contributions
- Payload attribution with your name/handle
- Recognition in the security community

### **Recognition Levels:**
- **🌟 New Contributor** - First payload accepted
- **🔥 Active Contributor** - Multiple quality payloads
- **⚡ Expert Contributor** - Advanced techniques and help others

---

## ✅ **Quality Guidelines**

### **We Accept:**
- Original XSS payloads you've discovered or created
- Well-tested payloads that work in real scenarios
- Clear descriptions of how and why they work
- Proper categorization and metadata

### **We Don't Accept:**
- Untested or theoretical payloads
- Poorly documented submissions

---

<div align="center">

## 🚀 **Ready to Contribute?**

**Your expertise helps secure the web for everyone.**

[![Fork & Contribute](https://img.shields.io/badge/Fork_&_Contribute-Now-00d4aa?style=for-the-badge)](https://github.com/karndeepbaror/IntelXSS/fork)

</div>
