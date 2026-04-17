# Short Response — LG 7.0: Responsive Units

Answer each question in 2–3 sentences. 

---

## Question 1 — Describe

What is the difference between a static unit like `px` and a responsive unit like `%` or `vh`? 

Describe what makes a unit responsive and why that matters when building a website.


Static units like px always stay the same size while on the other hand, responsive units like % or vh changed based off the container size. A unit is responsive when it scales depending on the size of the screen or container.





---

## Question 2 — Explain

Look at these two CSS rules:

```css
.image {
  width: 400px;
}

.image {
  width: 50%;
}
```

Explain what happens to the image on a small screen with each rule. Why does one behave better than the other?


With 400px, the image will stay as 400 pixels even on small screens which will cause it to be too big. Instead we should use 50% width because it allows the image scale to take up %50 of the screen no matter the size.



