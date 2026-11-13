পরবর্তী ধাপের Firebase কোড

১) ফাইলগুলো HTTPS ওয়েব হোস্টিং-এ প্রকাশ করতে হবে; ফোনের File Manager থেকে index.html খুললে Phone OTP কাজ করবে না।
২) Firebase Authentication > Settings > Authorized domains-এ হোস্টিং ডোমেইন যোগ করো।
৩) ওয়েবসাইটে প্রথমে নিজের নম্বর দিয়ে OTP লগইন করো। স্ক্রিনে Firebase UID দেখাবে।
৪) সেই UID firebase.js-এর ADMIN_UID এবং firestore.rules-এর PASTE_ADMIN_UID_HERE—দুই জায়গায় বসাও।
৫) Firestore > Rules-এ firestore.rules-এর পুরো কোড বসিয়ে Publish করো।
৬) তারপর সাইট রিফ্রেশ করে Admin হিসেবে আবার লগইন করো।

Phone OTP-তে SMS quota/দেশভিত্তিক সীমা বা চার্জ হতে পারে। Console-এর quota ও pricing যাচাই করো।
এটি প্রাথমিক কোড; launch-এর আগে security testing দরকার। ছবি upload এখনো নেই।
