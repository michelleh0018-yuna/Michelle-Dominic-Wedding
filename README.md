<form name="rsvp" method="POST" data-netlify="true">
  <h2>RSVP 💌</h2>

  <input type="text" name="name" placeholder="Your Name" required />
  <input type="email" name="email" placeholder="Your Email" required />

  <select name="attendance">
    <option>Will you attend?</option>
    <option>Yes, I will be there 🎉</option>
    <option>No, I can’t make it 😢</option>
  </select>

  <button type="submit">Send RSVP</button>
</form>

<h2>Our Memories 📸</h2>

<div class="gallery">
  <img src="photo1.jpg" />
  <img src="photo2.jpg" />
  <img src="photo3.jpg" />
</div>

<h2>Countdown to Our Wedding ⏳</h2>
<p id="countdown"></p>

<script>
const weddingDate = new Date("2026-12-01").getTime();

setInterval(function () {
  const now = new Date().getTime();
  const distance = weddingDate - now;

  const days = Math.floor(distance / (1000 * 60 * 60 * 24));

  document.getElementById("countdown").innerHTML =
    days + " days to go 💍";
}, 1000);
</script>

body {
  font-family: Arial;
  text-align: center;
  background: #fffaf5;
  color: #333;
}

h2 {
  color: #d48b8b;
}

button {
  background: #d48b8b;
  color: white;
  padding: 10px 20px;
  border: none;
  cursor: pointer;
  border-radius: 8px;
}

.gallery img {
  width: 200px;
  margin: 10px;
  border-radius: 10px;
}
