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

<iframe src="https://www.google.com/maps/embed?pb=..." width="600" height="450"></iframe>

<h2>Wedding Venue 📍</h2>

<iframe 
  src="PASTE_YOUR_GOOGLE_MAPS_EMBED_LINK_HERE"
  width="100%" 
  height="350" 
  style="border:0; border-radius: 12px;"
  allowfullscreen="" 
  loading="lazy">
</iframe>
