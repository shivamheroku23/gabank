# भुगतान और निपटान प्रणाली (Payment & Settlement Systems) – ओवरव्यू (हिंदी)

यह फ़ाइल भारत की **भुगतान एवं निपटान (Payment & Settlement) प्रणालियों** का मूल static overview देती है –  
NEFT, RTGS, IMPS, चेक क्लियरिंग, PSS Act, RBI / NPCI की भूमिका आदि।

---

## 1. Payment System और Settlement System – मूल अवधारणा

- **Payment System:**  
  - ऐसा सिस्टम जिसके माध्यम से **धन एक इकाई से दूसरी इकाई को transfer** होता है (funds transfer)।  

- **Settlement System:**  
  - वह प्रक्रिया जिसमें transactions का **अंतिम निपटान (final debit/credit)** प्रतिभागी बैंकों के खातों में होता है।  

भारत में इन प्रणालियों के लिए मुख्य कानूनी ढांचा:

- **Payment and Settlement Systems Act, 2007 (PSS Act)**  
- **Regulator:** Reserve Bank of India (RBI)

---

## 2. PSS Act, 2007 – संक्षिप्त सार

PSS Act के तहत RBI की powers:

- Payment systems को **authorise, regulate, supervise** करना।  
- System providers (जैसे banks, card networks, NPCI आदि) को authorize और उनकी निगरानी (oversight)।  
- Systems के लिए standards, guidelines, directions जारी करना।

इस Act के बाद:

- NEFT, RTGS, card networks, clearing houses, wallets आदि को clear legal framework मिला।

---

## 3. प्रमुख Fund Transfer Systems – Overview

### 3.1 NEFT – National Electronic Funds Transfer

- **प्रकार:** Deferred Net Settlement आधारित retail funds transfer system  
- **उपयोग:** व्यक्तियों, firms और corporates के बीच account‑to‑account transfer।  
- **मुख्य बिंदु (Concept):**
  - NEFT‑enabled बैंक शाखा होना ज़रूरी।  
  - सामान्यत: small / medium value transfers के लिए लोकप्रिय।  
  - Settlement batches में होता है (RBI समय के अनुसार frequency तय करता है – हाल में multiple batches, लगभग near‑real‑time)।

### 3.2 RTGS – Real Time Gross Settlement

- **प्रकार:** Real‑time, gross settlement system  
- **उपयोग:** उच्च मूल्य (high value) और urgent funds transfer – banks, corporates, individuals।  
- **मुख्य विशेषताएँ:**
  - **Real‑time** – instruction प्राप्त होते ही process।  
  - **Gross settlement** – प्रत्येक transaction अलग‑अलग settle, netting नहीं।  
  - Minimum transaction राशि का threshold होता है (नवीनतम आंकड़ा exam वर्ष के अनुसार देखें)।

### 3.3 IMPS – Immediate Payment Service

- **Operator:** National Payments Corporation of India (NPCI)  
- **प्रकार:** 24×7 instant interbank electronic funds transfer  
- **उपयोग:**  
  - Mobile banking, internet banking, ATM, UPI front‑ends आदि से।  
- **मुख्य विशेषता:** **Immediate credit – real‑time 24×7**।

---

## 4. Cheque Clearing, ECS, NACH – संक्षिप्त परिचय

### 4.1 Cheque Clearing System

- Cheque – एक **paper‑based negotiable instrument** है।  
- पहले physical cheques clearing houses में exchange होते थे;  
  अब **CTS (Cheque Truncation System)** के माध्यम से cheque की image process होती है – तेज़, सुरक्षित।

### 4.2 ECS – Electronic Clearing Service

- bulk और repetitive payments/receipts (salary, pension, dividend, utility bills आदि) के लिए electronic clearing व्यवस्था।  
- अब बड़े पैमाने पर **NACH** द्वारा replace / complement की गई है।

### 4.3 NACH – National Automated Clearing House

- **Developed by:** NPCI  
- **उपयोग:** bulk transactions –  
  - subsidies, pensions, salaries, utility bills, insurance premia आदि।  
- Government की अधिकांश DBT, subsidy payments NACH के माध्यम से।

---

## 5. भुगतान प्रणालियों में RBI और NPCI की भूमिका

### 5.1 RBI – Payment System Regulator

- PSS Act के तहत RBI को powers:
  - payment systems को authorise करना,  
  - नियम एवं दिशानिर्देश जारी करना,  
  - oversight और supervision।  

- RBI सीधे **RTGS और NEFT** systems operate करता है।  
- RBI का उद्देश्य – payment systems की **सुरक्षा, दक्षता और स्थिरता** को सुनिश्चित करना।

### 5.2 NPCI – National Payments Corporation of India

- NPCI – retail payments के लिए **umbrella organisation / system operator** (regulator नहीं)।  
- प्रमुख उत्पाद:
  - **IMPS** – Immediate Payment Service  
  - **UPI** – Unified Payments Interface  
  - **RuPay** – domestic card network  
  - **BHIM** app, **BBPS**, **AEPS**, **NACH** आदि

RBI regulation करता है; NPCI इन systems को operate करता है (regulatory framework के भीतर)।

---

## 6. Settlement Systems – RTGS एवं Clearing Houses

- **RTGS:**  
  - बड़े value transactions का real‑time settlement system।  
  - Banks के RTGS accounts RBI के पास होते हैं; interbank settlements वहीँ होते हैं।

- **Clearing Houses:**  
  - Cheques / retail payment instruments के net settlement clearing houses से होते हैं;  
  - अंतिम settlement RTGS / RBI accounts के माध्यम से।

> परीक्षा Angle: **“RTGS – real‑time, gross; NEFT – deferred, net; IMPS – 24×7 instant retail”**।

---

## 7. सुरक्षा, जोखिम और Oversight – High Level

- Payment systems में विभिन्न प्रकार के risk होते हैं:
  - Settlement risk,  
  - Operational risk,  
  - Fraud risk।  

- RBI एवं system operators:
  - multi‑layer security (encryption, authentication),  
  - मजबूत IT infrastructure,  
  - Business Continuity Plans (BCP),  
  - Monitoring & surveillance systems maintain करते हैं।

- ग्राहकों के लिए:
  - transaction limits,  
  - Two‑factor authentication (OTP / PIN),  
  - alerts (SMS / email),  
  - dispute resolution mechanism।

---

## 8. परीक्षा के लिए One‑Liners – Payment & Settlement

1. **PSS Act, 2007** – payment & settlement systems के regulation और oversight के लिए; regulator – **RBI**।  
2. **NEFT** – deferred net settlement आधारित retail funds transfer; NEFT‑enabled branches के बीच account‑to‑account transfer।  
3. **RTGS** – Real Time Gross Settlement – high value transactions; real‑time और gross basis पर settlement।  
4. **IMPS** – Immediate Payment Service – 24×7 instant interbank transfer; operator – **NPCI**।  
5. **NACH** – National Automated Clearing House – bulk और repetitive transactions (salary, subsidy, bills आदि) के लिए।  
6. **CTS** – Cheque Truncation System – cheque image आधारित clearing system।  
7. **NPCI** – UPI, IMPS, RuPay, NACH, AEPS, BBPS जैसे retail payment systems का system operator।

---

## 9. मेमोरी ट्रिक्स – Payment Systems

**Trick 1 – “R–N–I = RTGS–NEFT–IMPS”**

- **R – RTGS** = **Real‑time**, **Rich (high value)**  
- **N – NEFT** = **Net settlement**, normal retail  
- **I – IMPS** = **Instant**, 24×7 retail transfers  

**Trick 2 – “RBI Regulator, NPCI Operator”**

- RBI – कानून (PSS Act) बनाता, regulate करता, oversight करता।  
- NPCI – UPI, IMPS, RuPay, NACH, AEPS, BBPS इत्यादि **systems operate** करता है।

डिजिटल payments (UPI, BHIM, QR, BBPS आदि) का detail `Digital_Payments_and_UPI.md` फ़ाइल में है –  
दोनों को साथ‑साथ पढ़ने से पूरा picture clear हो जाएगा।