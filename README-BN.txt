# My Taka PWA

এটি My Taka-এর installable/offline PWA প্যাকেজ।

## ইনস্টল করার জন্য গুরুত্বপূর্ণ
PWA সরাসরি `file://` থেকে ইনস্টল হয় না। HTTPS-এ হোস্ট করতে হবে (যেমন GitHub Pages)।
এই প্যাকেজের সব ফাইল একই ফোল্ডারে রেখে GitHub repository-র root-এ আপলোড করুন।
তারপর Settings → Pages → Deploy from a branch → `main` → `/ (root)` চালু করুন।
HTTPS লিংক Chrome-এ খুলে ⋮ → Install app / Add to Home screen চাপুন।

## প্রাইভেসি
লেনদেনের ডেটা এই ডিভাইসের browser localStorage-এ থাকে। কোনো backend/API বা account নেই।
Browser data clear বা app uninstall করলে ডেটা হারাতে পারে। Backup থেকে JSON export করুন।
