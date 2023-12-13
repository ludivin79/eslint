const container = document.getElementById('container');
const registerBtn = document.getElementById('register'); // Correction: Suppression du tiret dans getElementById
const loginBtn = document.getElementById('login'); // Correction: Suppression du tiret dans getElementById

registerBtn.addEventListener('click', () => {
  container.classList.add("active");
});

loginBtn.addEventListener('click', () => {
  container.classList.remove("active");
});
