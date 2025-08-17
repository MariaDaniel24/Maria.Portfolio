// تحديد الوقت الحالي
const now = new Date();
const hour = now.getHours();

let greeting;

if (hour < 12) {
  greeting = "GOOD MORNING";
} else if (hour < 18) {
  greeting = "GOOD AFTERNOON";
} else {
  greeting = "GOOD EVENING";
}

// عرض الرسالة في عنصر معين
document.addEventListener("DOMContentLoaded", function () {
  const greetingElement = document.getElementById("greeting");
  if (greetingElement) {
    greetingElement.textContent = greeting;
  }
});