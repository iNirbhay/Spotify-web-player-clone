# Spotify Web Player Clone 

A clean, responsive frontend clone of the Spotify Web Player user interface, built using semantic HTML5 and custom CSS3 layouts. 

# The Core Challenge & My Journey
This project was initially started as part of a guided frontend development tutorial to practice basic document object structuring and layout positioning. However, several core components were left as independent challenges. 

I independently designed, calculated layout proportions, and developed the entire **sticky bottom music player component** entirely from scratch. This included:
*   **The Album Section:** Handling responsive truncating, layouts for song metadata, and icon positioning.
*   **The Playback & Range Controls:** Custom styling native HTML range sliders (`input[type="range"]`) with custom WebKit vendor prefixes to match the classic Spotify green accent theme.
*   **Flexbox Alignment:** Structuring three independent sub-flex containers (album, main controls, and utility options) to scale neatly across desktop interfaces.

# Tech Stack Used
*   **HTML5:** Structured using semantic elements for optimal accessibility and document outline hierarchy.
*   **CSS3:** Flexbox layout system, explicit positioning rules (`position: sticky`, `position: fixed`), custom pseudo-elements, components, hover transition states, and responsive media queries.
*   **FontAwesome:** Integrated via CDN for high-fidelity vector icons matching the original layout style.

# Key Takeaways
Building out the bottom player section on my own was an incredible learning experience. It pushed me past simply following along with code to active problem-solving—forcing me to figure out how properties interact in the wild, debug layout bugs, and master structural alignment rules in CSS.

## 🎯 What's Next?
*   Introduce JavaScript to make the playback tracking bar dynamic.
*   Add audio element functionality so users can play/pause actual short sample tracks.
*   Incorporate active state DOM manipulation when changing tracks or selecting items from the library sidebar.
