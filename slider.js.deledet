const slides = document.querySelectorAll(".slide");
let current = 0;

function showNextSlide() {
  slides[current].classList.remove("active");
  slides[current].classList.add("left");

  current = (current + 1) % slides.length;

  slides[current].classList.remove("left");
  slides[current].classList.add("active");
}

setInterval(showNextSlide, 3000);
