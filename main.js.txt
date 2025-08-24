// Language toggle placeholder
function switchLanguage(lang) {
  alert("Language switched to: " + lang);
  // Future: Load translated content dynamically
}

// Form validation (optional enhancement)
document.addEventListener("DOMContentLoaded", () => {
  const form = document.querySelector("form");
  form.addEventListener("submit", (e) => {
    const name = form.name.value.trim();
    const email = form.email.value.trim();
    if (!name || !email) {
      alert("Please fill out all required fields.");
      e.preventDefault();
    }
  });
});
