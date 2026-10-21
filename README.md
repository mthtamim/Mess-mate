<div align="center">

<img src="./messmate-logo.png" alt="MessMate Logo" width="180" />

# MessMate — Smart Mess Management

**🍛 Your Ultimate Mess Manager**
মেসের মিল, বাজার আর মাসের হিসাব — সব এক অ্যাপে।

![Version](https://img.shields.io/badge/Version-1.9.1-059669)
![Platform](https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)
![Firebase](https://img.shields.io/badge/Firebase-Auth%20%2B%20Firestore-FFCA28?logo=firebase&logoColor=black)
![License](https://img.shields.io/badge/License-Private-lightgrey)

</div>

---

## ✨ বৈশিষ্ট্য (Features)

- 🍽️ **মিল ও খরচের হিসাব** — Meal & expense accounting: অ্যাডমিন-নির্ধারিত ফিক্সড মিল রেট, গেস্ট মিল, জরিমানা আর জমা — সবার হিসাব এক জায়গায়, সবসময় আপ-টু-ডেট।
- 🏠 **ব্লক-ভিত্তিক খরচ ভাগ** — Block-wise splitting: পুরো মেসের খরচ সবার মধ্যে, ব্লকের খরচ শুধু ওই ব্লকের সদস্যদের মধ্যে ভাগ হয়।
- 🛒 **বাজার ডিউটি রোস্টার** — Duty roster: তারিখ ধরে বাজারের দায়িত্ব, আজ/আগামীকালের রিমাইন্ডার আর হোম-স্ক্রিন ব্যানার।
- 🔁 **মাল্টি-টার্গেট বাজার বদলি** — Swap your bazar duty with multiple members at once; প্রথমে যিনি accept করবেন, বদলি তাঁর সঙ্গেই।
- 📸 **রসিদের ছবি** — Receipt photos (Cloudinary): বাজার ও খরচের এন্ট্রিতে একাধিক রসিদের ছবি attach করা যায়।
- ☁️ **রিয়েল-টাইম ক্লাউড সিঙ্ক** — Firestore sync: সব সদস্যের ফোনে একই লাইভ ডেটা, কোনো এন্ট্রি দিলেই সবার কাছে পৌঁছে যায়।
- 🔔 **পুশ নোটিফিকেশন** — Push notifications: অ্যাডমিনের নোটিফিকেশন সেন্টার (সবাই / ব্লক / একজন, সাধারণ ও জরুরি), অটো-ইভেন্ট (নোটিশ, ডিউটি, মিল-অফ, সোয়াপ, জরিমানা), আর অ্যাডমিন-নিয়ন্ত্রিত সময়সূচি, দৈনিক ক্যাপ ও নীরব সময়।
- 📄 **মাস-শেষের স্টেটমেন্ট PDF** — Month-end statement: এক চাপে পুরো মাসের হিসাবের PDF শেয়ার।
- 🌐 **বাংলা / English** — দুই ভাষাতেই পুরো অ্যাপ।

## 📲 ইনস্টল (Install)

1. [Releases পেজ](https://github.com/mthtamim/Mess-mate/releases) থেকে সর্বশেষ APK ডাউনলোড করুন।
2. আগের সংস্করণ থাকলে সেটি আগে **আনইনস্টল** করুন, তারপর APK-টি ইনস্টল করুন (আনইনস্টল ছাড়া আপডেট বসবে না)। আনইনস্টল করলে লগআউট হয়ে যাবেন — আবার লগইন করলেই সব ডেটা ফিরে পাবেন, কারণ সব তথ্য ক্লাউডে থাকে।
3. ইমেইল বা Google দিয়ে লগইন করুন, আর নোটিফিকেশনের অনুমতি (Allow) দিয়ে দিন।

## 🛠️ প্রযুক্তি (Tech Stack)

| অংশ | প্রযুক্তি |
| --- | --- |
| Frontend | React 19 + TypeScript + Vite + Tailwind CSS 4 |
| Mobile | Capacitor 8 (Android) |
| Auth & Database | Firebase Authentication + Cloud Firestore (রিয়েল-টাইম সিঙ্ক) |
| Media | Cloudinary (রসিদের ছবি) |
| Push | FCM — service-account worker দিয়ে, Blaze ছাড়াই |
| CI/CD | GitHub Actions — প্রতিটি রিলিজে স্বয়ংক্রিয় APK বিল্ড |

## 🗂️ সংস্করণ ইতিহাস (Version History)

| সংস্করণ | যা এসেছে |
| --- | --- |
| 1.0 | প্রথম APK — লগইন ও মৌলিক মেস ব্যবস্থাপনা |
| 1.1 | স্থায়ীভাবে সদস্য মুছে ফেলা, ডিউটি উন্নয়ন |
| 1.2 | ক্লাউড সিঙ্ক (Firestore) — সব ফোনে একই লাইভ ডেটা |
| 1.3 | রসিদের ছবি (Cloudinary) |
| 1.4 | মিল-অফের সময় অ্যাডমিনের হাতে + একাধিক রসিদের ছবি |
| 1.5 | পুশ নোটিফিকেশন + নোটিফিকেশন সেন্টার |
| 1.6 | নোটিফিকেশন সময়সূচি + মাল্টি-টার্গেট বাজার বদলি + নতুন লোগো |
| 1.7 | হোম-স্ক্রিন widget (বাজার ডিউটি + আমার হিসাব) |
| 1.8 | ইনভাইটে ব্লক সিলেকশন + strict ব্লক-ভিত্তিক খরচের হিসাব |
| 1.9.1 | মিল-অফ অনুরোধ→ম্যানেজার অনুমোদন + মিল-কাউন্ট পুশ + ট্যাপ-কল + নোটিফিকেশন ক্র্যাশ হটফিক্স — বর্তমান সংস্করণ ✅ |

## 👤 তৈরি (Author)

**Tamim** ([@mthtamim](https://github.com/mthtamim)) — **থ্রি স্টার ছাত্রাবাস**-এর জন্য ভালোবাসা দিয়ে তৈরি। 💚
