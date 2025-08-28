# New Project

This is a project created from the local system.

Created by **Shivani**.
This branch contains a **button** implementation.

console.log("Welcome to Shivani's project!");

document.getElementById("contactForm").addEventListener("submit", function(e) {
  e.preventDefault();
  alert("Form submitted from MAIN branch!");
});

document.getElementById("magicBtn").addEventListener("click", function() {
  alert("Button clicked from FEATURE branch!");
});
