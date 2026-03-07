# 🎮 Free Fire Tournament Management System (A-Z)

এটি একটি পূর্ণাঙ্গ **Free Fire Tournament** ম্যানেজমেন্ট সিস্টেম যা **Firebase** এবং **HTML/Tailwind CSS** ব্যবহার করে তৈরি করা হয়েছে। এই অ্যাপের মাধ্যমে প্লেয়াররা ম্যাচে জয়েন করতে পারবে এবং অ্যাডমিন পুরো সিস্টেম কন্ট্রোল করতে পারবে।

## ✨ প্রধান ফিচারসমূহ (Features)
- **Authentication:** ইমেইল এবং পাসওয়ার্ড দিয়ে লগইন ও রেজিস্ট্রেশন।
- **Tournament List:** হোম পেজে লাইভ এবং আপকামিং ম্যাচের তালিকা।
- **Wallet System:** বিকাশ/নগদ এর মাধ্যমে টাকা অ্যাড করার রিকোয়েস্ট এবং ব্যালেন্স চেক।
- **Match Joining:** ওয়ালেট ব্যালেন্স থেকে এন্ট্রি ফি কেটে টুর্নামেন্টে জয়েন করা।
- **Admin Panel:** ম্যাচ তৈরি করা এবং ইউজারদের পেমেন্ট রিকোয়েস্ট অ্যাপ্রুভ করা।
- **Profile:** গেম ইউআইডি (UID) আপডেট এবং লগআউট সুবিধা।
- **Match History:** জয়েন করা ম্যাচের রুম আইডি এবং পাসওয়ার্ড দেখার সুবিধা।

## 🛠 টেকনোলজি (Tech Stack)
- **Frontend:** HTML5, Tailwind CSS, FontAwesome Icons.
- **Backend:** Firebase Authentication, Firestore Database.

## 🚀 কিভাবে ব্যবহার করবেন (Setup Guide)
1. এই রিপোজিটরি ক্লোন করুন।
2. আপনার নিজস্ব `firebaseConfig` টি `auth.html`, `index.html`, `wallet.html`, `admin.html` এবং অন্যান্য ফাইলে আপডেট করুন।
3. Firebase Console থেকে **Authentication** এবং **Firestore Database** এনাবল (Enable) করুন।
4. `index.html` ফাইলটি ব্রাউজারে রান করুন।

## 📁 ফাইল স্ট্রাকচার (Folder Structure)
- `auth.html` - লগইন এবং রেজিস্ট্রেশন পেজ।
- `index.html` - হোম পেজ (ম্যাচ লিস্ট)।
- `match-details.html` - ম্যাচের নিয়ম ও জয়েনিং বাটন।
- `wallet.html` - টাকা অ্যাড ও ব্যালেন্স।
- `admin.html` - অ্যাডমিন ড্যাশবোর্ড।
- `profile.html` - ইউজার প্রোফাইল।
- `history.html` - ম্যাচ হিস্ট্রি ও রুম ডিটেইলস।
