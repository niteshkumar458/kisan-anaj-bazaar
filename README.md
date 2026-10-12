KISAN ANAJ BAZAAR — अपलोड निर्देश

1) GitHub repo niteshkumar458/kisan-anaj-bazaar खोलें।
2) पुराने index.html को बदलकर इस पैकेज वाला index.html अपलोड करें और Commit changes करें।
3) Firebase Console > Authentication > Sign-in method में Email/Password चालू करें।
4) Firebase Console > Firestore Database बनाएं। Rules टैब में firestore.rules का पूरा टेक्स्ट पेस्ट करके Publish करें।
5) वेबसाइट पर नया अकाउंट बनाएं। Firebase Console > Firestore Database > users में उस UID वाले document को खोलें और admin को true तथा approved को true करें। यह काम सिर्फ अपने भरोसेमंद admin अकाउंट के लिए करें।
6) लॉगआउट करके दोबारा लॉगिन करें। Admin Panel में यूज़र approve करें।

जरूरी: Firebase config इस HTML में पहले से भरा है। यह शुरुआती MVP है। वेबसाइट पर UPI ID niteshai64910@nyes है। यह खुद से भुगतान verify नहीं करती; admin बैंक/UPI ऐप में पुष्टि करके payment status Paid करे। UPI PIN वेबसाइट में कभी न डालें।

सुरक्षा/सीमा: Firestore Rules सामान्य access रोकती हैं, लेकिन order total/stock की पूरी server-side validation के लिए Firebase Cloud Functions और payment gateway की जरूरत है। इसे बड़े/वास्तविक लेन-देन से पहले सुरक्षा समीक्षा के बिना production-grade न मानें।