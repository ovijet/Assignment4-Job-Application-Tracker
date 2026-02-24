## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?

Ans: getElementById : নির্দিষ্ট একটা id দিয়ে element ধরতে ব্যবহার হয়।
getElementsByClassName :নির্দিষ্ট class name দিয়ে একাধিক element ধরতে ব্যবহার হয়।
querySelector : CSS selector ব্যবহার করে প্রথম matching element ধরে।
querySelectorAll : CSS selector ব্যবহার করে সব matching element ধরে।

### 2. How do you create and insert a new element into the DOM?

Ans: createElement() দিয়ে element তৈরি করো

innerText বা innerHTML দিয়ে content দাও

appendChild() বা অন্য method দিয়ে DOM এ insert করো

### 3. What is Event Bubbling? And how does it work?

Ans: Event Bubbling হলো এমন একটি প্রক্রিয়া যেখানে কোনো element এ event ঘটলে (যেমন click), সেই event প্রথমে সেই element এ কাজ করে, তারপর ধাপে ধাপে তার parent → grandparent → document পর্যন্ত উপরের দিকে যেতে থাকে।

### 4. What is Event Delegation in JavaScript? Why is it useful?

Ans: Event Delegation হলো এমন একটি technique যেখানে আমরা প্রত্যেকটা child element এ আলাদা আলাদা event না দিয়ে, তাদের parent element এ একটাই event listener বসাই।

### 5. What is the difference between preventDefault() and stopPropagation() methods?

Ans: preventDefault():👉 কোনো element এর default browser behaviour বন্ধ করে।
stopPropagation():Event কে parent এ উঠতে (bubble হতে) বাধা দেয়।
