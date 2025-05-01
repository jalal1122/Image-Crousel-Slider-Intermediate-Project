# 🎞️ Image Carousel Slider – Intermediate Project

This is an intermediate-level **responsive image carousel slider** built using the [**Swiper.js**](https://swiperjs.com/) library. The project features autoplay, pagination, navigation buttons, and responsiveness for all device sizes.

🔗 **Live Demo**: (https://mjimagecrousel.vercel.app/)
📂 **GitHub Repo**: [github.com/jalal1122/Image-Crousel-Slider-Intermediate-Project](https://github.com/jalal1122/Image-Crousel-Slider-Intermediate-Project)

---

## 🚀 Features

- ✅ **Responsive Design** — Adjusts slides per view based on screen width.
- 🔄 **Autoplay** — Slides transition every 2.5 seconds.
- 🔘 **Pagination** — Dynamic bullets for easy slide tracking.
- ⬅️➡️ **Navigation Buttons** — Manual slide control.
- 🎨 **Clean UI** — Modern design with custom CSS.

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Swiper.js via CDN

---

## 📁 Project Structure

```
Image-Crousel-Slider-Intermediate-Project/
│
├── images/         # Folder containing images for the slider
├── index.html      # Main HTML file
├── style.css       # CSS styling
├── script.js       # Swiper configuration
└── README.md       # Project documentation
```

---

## 📌 Usage Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/jalal1122/Image-Crousel-Slider-Intermediate-Project.git
   cd Image-Crousel-Slider-Intermediate-Project
   ```

2. Add your custom images to the `images/` folder.

3. Update the `<img>` tags in `index.html` to point to your new images.

4. Open `index.html` in your browser to view the project.

5. Modify `script.js` to tweak Swiper settings if needed.

---

## ⚙️ Swiper Configuration Summary

```js
autoplay: {
  delay: 2500,
  disableOnInteraction: false,
},
pagination: {
  el: ".swiper-pagination",
  dynamicBullets: true,
},
navigation: {
  nextEl: ".swiper-button-next",
  prevEl: ".swiper-button-prev",
},
breakpoints: {
  0: { slidesPerView: 1 },
  768: { slidesPerView: 2 },
  1024: { slidesPerView: 3 },
}
```

---

## 🙌 Acknowledgments

- [Swiper.js Documentation](https://swiperjs.com/)
- [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins)

---

## 🤝 Contribute

Found an issue? Have an idea?  
Feel free to fork the repo, submit pull requests, or open issues. Contributions are welcome!
