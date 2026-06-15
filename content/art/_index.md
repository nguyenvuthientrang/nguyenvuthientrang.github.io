---
title: "Art"
---

<p style="text-align: center;">A few drawings of mine.</p>

<div class="art-gallery">
  <a href="/images/art/drawing-1.jpeg"><img src="/images/art/drawing-1.jpeg" alt="Drawing 1" loading="lazy"></a>
  <a href="/images/art/drawing-3.jpeg"><img src="/images/art/drawing-3.jpeg" alt="Drawing 2" loading="lazy"></a>
  <a href="/images/art/drawing-4.jpeg"><img src="/images/art/drawing-4.jpeg" alt="Drawing 3" loading="lazy"></a>
  <a href="/images/art/drawing-2.jpeg"><img src="/images/art/drawing-2.jpeg" alt="Drawing 4" loading="lazy"></a>
</div>

<style>
.art-gallery {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 1rem;
  margin-top: 1.5rem;
}
.art-gallery img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 6px;
  display: block;
}
@media (max-width: 600px) {
  .art-gallery { grid-template-columns: 1fr; }
}
</style>
