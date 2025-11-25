# 👥 Student Attendance & Behavior Tracker

A complete, browser-based attendance and behavior tracking system for teachers. No installation required, no server needed, completely free!

## ✨ Features

- **📊 Attendance Tracking** - Mark students as Present, Late, or Absent by period
- **⚠️ Behavior Recording** - Document student behaviors with notes
- **📅 Historical View** - Review past attendance records
- **🔍 Student Search** - View complete attendance and behavior history for any student
- **📥 Export Reports** - Generate Excel reports for attendance and behavior
- **💾 Backup & Restore** - Export/import your database
- **📧 Email Alerts** - Automatic alerts for students with 3+ lates
- **🕐 Live Clock** - Current date and time always visible
- **📱 Responsive Design** - Works on desktop, tablet, and mobile

## 🚀 Quick Start

### For Teachers:

1. **Open the App**: Visit [Your GitHub Pages URL]
2. **Create a Class**: Click "Add Class" and enter your class name
3. **Add Students**: Click "Manage Students" → Import CSV or add manually
4. **Take Attendance**: Click "Take Attendance" and mark students
5. **Save**: Click "Save Attendance" when done

That's it! Your data is automatically saved.

## ⚠️ IMPORTANT: Data Storage & Backup

### How Your Data is Stored

Your attendance data is stored **locally in your web browser** using localStorage and IndexedDB. This means:

✅ **Private** - Your data never leaves your computer  
✅ **Fast** - No internet required after initial load  
✅ **Free** - No accounts, no subscriptions  

### ⚠️ BUT - Data Can Be Lost!

Your data will be **PERMANENTLY LOST** if you:

- ❌ Clear your browser cache/cookies
- ❌ Use Private/Incognito browsing mode
- ❌ Switch to a different browser (Chrome → Firefox)
- ❌ Switch to a different device (laptop → phone)
- ❌ Reinstall your operating system
- ❌ Let your browser auto-clear data

### 🛡️ How to Protect Your Data

**BACKUP REGULARLY!**

1. Go to **Export** page
2. Click **"📥 Download Database (.sqlite)"**
3. Save the file to:
   - ☁️ Cloud storage (Google Drive, OneDrive, Dropbox)
   - 💾 External drive (USB stick, external hard drive)
   - 📧 Email it to yourself

**Recommended Backup Schedule:**
- 📅 Weekly during active semester
- 📅 After every major event (exams, parent-teacher conferences)
- 📅 Before school breaks

### 🔄 Restoring from Backup

1. Go to **Export** page
2. Click **"📤 Import Database"**
3. Select your `.sqlite` backup file
4. All your data will be restored

## 📝 How to Add Students

### Method 1: CSV Import (Bulk)

1. Create a CSV file with this format:
```csv
ID,Name
12345,John Smith
12346,Jane Doe
12347,Bob Johnson
```

2. Click **"Manage Students"** on your class
3. Click **"📁 Choose CSV File"**
4. Select your CSV file
5. Preview and click **"Import Students"**

### Method 2: Manual Entry (Individual)

1. Click **"Manage Students"** on your class
2. Enter Student ID
3. Enter Student Name
4. Click **"Add Student"**

## 📧 Email Alerts for Late Students

When a student reaches **3 or more late marks**, the system will:

1. Alert you with a prompt
2. Open a pre-formatted email to the counselor
3. Include:
   - Student name and ID
   - All dates they were late
   - Professional, courteous wording

**You can edit the email before sending!**

To configure:
1. Go to **Settings**
2. Enter counselor email address
3. Click **"👁️ Preview Email Format"** to see what it looks like

## 💻 System Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- ~5MB of free browser storage

## 🔒 Privacy & Security

- ✅ All data stays on your computer
- ✅ No data sent to any server
- ✅ No tracking or analytics
- ✅ No personal information collected
- ✅ Works offline after initial load

## 📱 Using on Multiple Devices

Since data is browser-specific, here's how to use across devices:

1. **Primary Device** (e.g., classroom computer):
   - Use normally
   - Backup regularly

2. **Secondary Device** (e.g., home laptop):
   - Export database from primary device
   - Import database on secondary device
   - Work on secondary device
   - Export when done
   - Import back to primary device

**Note:** There is no automatic sync. You must manually export/import.

## 🆘 Troubleshooting

### "Loading Database..." stuck

**Solution:** Refresh the page. If it persists, clear your browser cache and try again.

### Data disappeared

**Causes:**
- Cleared browser data
- Used incognito mode
- Different browser/device

**Solution:** Import your last backup file.

### Can't find backup file

**Prevention:** Always save backups to multiple locations!

### Attendance won't save

**Check:**
- Are you in "History Mode"? (Exit history mode)
- Did you click the "Save Attendance" button?
- Try refreshing and re-entering

### Students not showing up

**Check:**
- Are you in the correct class?
- Did you add students to this specific class?

## 📊 Best Practices

1. **Backup Weekly** - Set a recurring reminder
2. **Use Regular Browsing** - Never use incognito/private mode
3. **Stick to One Browser** - Pick Chrome or Firefox and always use that
4. **Export Before Updates** - Before major browser/OS updates
5. **Test Imports** - Periodically test restoring from backup
6. **Multiple Backups** - Keep backups in 2-3 different locations
7. **Document Your Process** - Know which browser and device you use

## 🎓 Support & Contributions

This is an open-source project. Feel free to:
- Report bugs via GitHub Issues
- Suggest features
- Submit pull requests
- Fork and customize for your needs

## 📄 License

MIT License - Free to use, modify, and distribute.

## ⚠️ Disclaimer

This software is provided "as is" without warranty. The developers are not responsible for data loss. **Users are responsible for backing up their own data.**

---

## 🔗 Links

- **Live Demo**: [Your GitHub Pages URL]
- **Source Code**: [Your GitHub Repository]
- **Issues/Support**: [GitHub Issues]

---

**Made with ❤️ for teachers who deserve better tools**
