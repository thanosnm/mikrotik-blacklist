<!-- keywords: mikrotik, blacklist, routeros, address-list, firewall, threat feeds, spamhaus, abuse.ch, ip blocklist, python mikrotik script -->

# 🇬🇷 Ελληνικές και Διεθνείς Λίστες Αποκλεισμού για MikroTik και Pi-hole
## 🇬🇧 Greek and International Blocklists for MikroTik and Pi-hole

🇬🇷 Αυτό το αποθετήριο περιέχει επιμελημένες λίστες από domain names και διευθύνσεις IP που απαγορεύονται βάσει της ελληνικής νομοθεσίας.  
Το περιεχόμενο είναι κατάλληλο για χρήση σε συστήματα φιλτραρίσματος περιεχομένου όπως MikroTik RouterOS και Pi-hole.

🇬🇧 This repository includes curated lists of domain names and IP addresses that are restricted under Greek law.  
The content is suitable for use with content filtering systems such as MikroTik RouterOS and Pi-hole.

---

## 📁 Περιεχόμενα / Contents

### 📄 eeep.txt  
  🇬🇷 Περιλαμβάνει domains που σχετίζονται με στοιχήματα και καζίνο – Ε.Ε.Ε.Π.  
  🇬🇧 Contains gambling-related domains – from Hellenic Gaming Commission (HGC / Ε.Ε.Ε.Π.)  
  ✅ Format: `0.0.0.0 casino-example.com`   

### 🧱 gr_bl.rsc  
  🇬🇷 Ελληνικές IP που παραβιάζουν πνευματικά δικαιώματα – έτοιμες για MikroTik  
  🇬🇧 Greek copyright-infringing IPs – MikroTik-ready  
  ✅ Format: `/ip firewall address-list add list=GR_BL address=1.2.3.4`   

### 🛡️ bds_atif.rsc 
  🇬🇷 Κακόβουλες IP από Binary Defense Systems (ATIF)  – έτοιμες για MikroTik  
  🇬🇧 Malicious IPs from Binary Defense Systems – ATIF – MikroTik-ready  

### 🚨 et_block.rsc   
  🇬🇷 Emerging Threats IPs – scanners, botnets, malware  – έτοιμες για MikroTik  
  🇬🇧 Threat IPs from Emerging Threats project – MikroTik-ready   

### 📛 spamhaus.rsc   
  🇬🇷 Spamhaus IP blacklist – έτοιμες για MikroTik  
  🇬🇧 Spamhaus IP blacklist – MikroTik-ready  

### 🧿 trackers-with-ip.txt   
  🇬🇷 Περιλαμβάνει hostnames από torrent trackers, μετατρεπόμενα σε μορφή 0.0.0.0 για φιλτράρισμα μέσω DNS. Κατάλληλο για χρήση σε MikroTik DNS static entries και Pi-hole adlists.   
  🇬🇧 Contains hostnames from torrent trackers, formatted as 0.0.0.0 for DNS-based filtering. Suitable for MikroTik DNS static lists and Pi-hole adlists.   
  ✅ Format: 0.0.0.0 tracker.example.com

### 🌐 websites-with-ip.txt   
  🇬🇷 Περιέχει hostnames από torrent ιστοσελίδες (indexers, proxy sites κ.λπ.), σε μορφή 0.0.0.0 για μπλοκάρισμα μέσω DNS. Ιδανικό για MikroTik και Pi-hole.   
  🇬🇧 Contains hostnames from torrent websites (indexers, proxy sites, etc.), formatted as 0.0.0.0 for DNS blocking.Great for MikroTik and Pi-hole setups.   
  ✅ Format: 0.0.0.0 torrent-site.example.com

### 🛑 blocklist_de.rsc  
  🇬🇷 Κακόβουλες IP που έχουν καταγραφεί να επιτίθενται σε SSH, SMTP, FTP, web services κ.ά., σύμφωνα με τα δεδομένα του blocklist.de.  
  🇬🇧 Malicious IPs recorded attacking SSH, SMTP, FTP, web services, etc., based on reports from blocklist.de.  
  ✅ Format: /ip firewall address-list add list=BLOCKLIST_DE address=1.2.3.4  

---

## ⚠️ Νομική Σημείωση / Legal Disclaimer

🇬🇷 Το περιεχόμενο παρέχεται για εκπαιδευτικούς και νομικά επιτρεπτούς σκοπούς.  
Η ευθύνη για τη χρήση και συμμόρφωση με τη νομοθεσία φέρει αποκλειστικά ο χρήστης.

🇬🇧 This content is provided for educational and legally permitted use only.  
The end user is solely responsible for lawful and compliant implementation.

---

## 📬 Συνεισφορά / Contribute

🇬🇷 Έχεις πρόταση, domain ή IP για προσθήκη/αφαίρεση; Κάνε ένα pull request ή άνοιξε issue.  
🇬🇧 Have a suggestion, domain, or IP to add/remove? Feel free to open an issue or submit a pull request.

---

## ☕ Στήριξέ με / Support My Work

🇬🇷 Είμαι δικτυάς και εκπαιδευτής με εμπειρία σε MikroTik, Ubiquiti και TP-Link. Αν βρήκες χρήσιμη τη δουλειά μου, μπορείς να με στηρίξεις με έναν καφέ!  
🇬🇧 I’m a network engineer & trainer focused on MikroTik, Ubiquiti and TP-Link networks. If you find my work useful, feel free to support me!

[![Buy Me A Coffee](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=☕&slug=pournarasaa&button_colour=FFDD00&font_colour=000000&font_family=Arial&outline_colour=000000&coffee_colour=ffffff)](https://buymeacoffee.com/pournarasaa)
