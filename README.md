# 🔐 OffSecDiary – Certificate & Badge Verification Portal

Welcome to the official **OffSecDiary Verification System**.  
This portal allows participants, recruiters, institutions, and auditors to instantly verify the authenticity of certificates and digital badges issued by **OffSecDiary**.

---

## 📌 **Verification Categories Available**

The following certificate & badge types can be verified through this portal:

### 🟥 **1. CTF – Offensive Security Challenge (29 Nov 2025)**
- CTF Participation Certificates  
- CTF Winner Certificates  
- Winner Digital Badges  

### 🟦 **2. Offensive Cyber Internship – November 2025**
- Internship Completion Certificates  
- Guest Speaker Certificates  
- Special Recognition Awards  

---

## 🚀 **How to Verify a Certificate**

1. Visit the verification portal:  
   👉 **https://offsecdiary.github.io/offsecdiary-certificates**

2. Select the appropriate category:
   - **CTF Participation**
   - **CTF Winners**
   - **CTF Winner Badges**
   - **Internship Certificate Verification**
   - **Guest Speaker Certificates**
   - **Special Recognition Awards**

3. Enter the **Certificate ID** printed on the top-left of the certificate.  
   Example IDs:
```

OFSD-CTF-25-4529
OSD-GSP-25-6941
OSD-REC-25-3189

```

4. The system will automatically:
- Validate the certificate  
- Display the certificate holder’s name  
- Show event details  
- Confirm issuance authority  
- Show authenticity status (VALID/INVALID)  

---

## 📁 **Repository Structure**

```

offsecdiary-certificates/
│
├── index.html
├── style.css / style.scss
├── logo.png
│
├── images/
│     └── badges/
│           ├── 1st.png
│           ├── 2nd.png
│           ├── 3rd.png
│           ├── design.png
│           ├── operations.png
│           ├── research.png
│           ├── sales.png
│           ├── shadow-corps.png
│           ├── software.png
│           ├── ui/ux.png
│           └── writing.png
├── data/
│   ├── cadets_badges.json
│   ├── ctf_participation.json
│   ├── ctf_winners.json
│   ├── ctf_winner_badges.json
│   ├── certification.json
│   ├── guest_speakers.json
│   ├── recognition_certificates.json
│   └── shadow_corps_badges.json
│
├── LICENSE
└── README.md
```

All JSON files follow a clean structured format:

```json
"OFSD-CTF-25-4529": {
  "name": "Full Name",
  "certificate_type": "CTF Participation Certificate",
  "event": "OFSD Offensive CTF Challenge",
  "event_date": "29 November 2025",
  "issued_by": "OffSecDiary",
  "status": "valid"
}
````

---

## 🛡️ **Digital Verification Policy**

* All certificates issued by **OffSecDiary** carry a unique Certificate ID.
* Each ID maps to a backend dataset stored securely within this repository.
* Any modification or tampering of original certificates **will fail validation**.
* Verified entries display **status: valid**.
* Unknown or edited IDs display **status: invalid**.

---

## 📞 **Support & Contact**

For verification issues or corporate validation requests:

**Email:** [offsecdiary@gmail.com](mailto:offsecdiary@gmail.com)
**Support Email:** [support@offsecdiary.com](mailto:support@offsecdiary.com)
**Instagram:** @offsecdiary
**LinkedIn:** OffSecDiary

---

## 🏴‍☠️ OffSecDiary – Innovating in Cybersecurity

Providing real-world offensive security training, CTFs, internships, and digital certifications for the next generation of ethical hackers.

