<div class="slider">
    <div class="slide">
        <h1>WELCOME TO ROBOTICS</h1>
        <p>Learn • Build • Innovate</p>
    </div>

    <div class="slide">
        <h1>EXPLORE ROBOTICS</h1>
        <p>Sensors • Motors • Arduino • AI</p>
    </div>

    <div class="slide">
        <h1>BUILD YOUR FUTURE</h1>
        <p>Turn your ideas into real robots.</p>
    </div>
</div>

<script>
let slideIndex = 0;
const slides = document.querySelectorAll(".slide");

function showSlide() {
    slides.forEach(slide => slide.style.display = "none");

    slideIndex++;

    if (slideIndex > slides.length) {
        slideIndex = 1;
    }

    slides[slideIndex - 1].style.display = "block";
}

showSlide();
setInterval(showSlide, 3000);
</script>
- [My Website](https://github.com/safwansunaina321-lang/my-website/tree/main)
