<script type="module">
  // Import the functions you need from the SDKs you need
  import { initializeApp } from "https://www.gstatic.com/firebasejs/12.19.0/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/12.19.0/firebase-analytics.js";
  // TODO: Add SDKs for Firebase products that you want to use
  // https://firebase.google.com/docs/web/setup#available-libraries

  // Your web app's Firebase configuration
  // For Firebase JS SDK v7.20.0 and later, measurementId is optional
  const firebaseConfig = {
    apiKey: "AIzaSyDxjigog6ctxY25UFGrH7M3pYx1IN2RWSw",
    authDomain: "kissan-bajar.firebaseapp.com",
    projectId: "kissan-bajar",
    storageBucket: "kissan-bajar.firebasestorage.app",
    messagingSenderId: "629043004551",
    appId: "1:629043004551:web:f484c026c838399cff6422",
    measurementId: "G-TE6ZLGS1KF"
  };

  // Initialize Firebase
  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
