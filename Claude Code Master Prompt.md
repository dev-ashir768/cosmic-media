Act as an expert Senior Frontend Developer and UI/UX Engineer specialized in luxury, avant-garde, and high-fashion editorial web designs.

Your objective is to generate a complete, production-ready, fully responsive, and highly animated Single-Page Landing Page for a premium creative digital marketing and branding agency named "Cosmic Media".

The core visual DNA of this website must match the exact colors, mood, and aesthetic of the reference image "image\_36d489.jpg", while integrating the clean, bold branding elements of the logo "logo.png".

### **🎨 Design & Aesthetic DNA (Sourced from image\_36d489.jpg & logo.png):**

* **Color Palette (Strict Celestial Luxury):**  
  * **Primary Background:** Deep cosmic obsidian/plum/dark amethyst (\#120917 to \#180e1f) giving a rich, celestial night-sky depth.  
  * **Secondary Background:** Velvet dark space/abyss (\#0a040e).  
  * **Primary Brand Accent (The Glow):** Rich, luxurious celestial gold/champagne (\#dfba6b or \#d4af37) used for highlights, borders, buttons, and active interactive states.  
  * **Glow Effects:** Subtle, diffused radial gradients representing soft cosmic nebulas and purple/gold ambient back-glows.  
  * **Typography Text Color:** Elegant warm cream/ivory (\#faf6ee) for primary content, and soft lavender-gray (\#9a8ea2) for readable body text.  
* **Typography Suite:**  
  * **Headers/Brand Fonts:** Combination of 'Lemon Milk' (modern, geometric bold) and an elegant luxury editorial serif resembling 'Cormorant Garamond' or 'Cinzel' (imported via Google Fonts).  
  * **Body Text:** Sleek minimalist sans-serif (e.g., 'Inter' or 'Helvetica Neue').  
* **Visual Motifs:**  
  * Arch-shaped frames, rounded portal windows, thin gold celestial constellation mapping lines, and glowing moon phases.  
  * The logo "logo.png" must be featured seamlessly in the sticky header as a high-contrast white/gold-hover element and integrated as a watermark background in strategic sections.

### **💎 Key Features & Motion Architecture (GSAP & jQuery):**

1. **Celestial Magnetic Custom Cursor:** Hide the default cursor. Implement a glowing Gold Dot (\#dfba6b) surrounded by a thin lavender-gold rotating ring using jQuery to track coordinates and GSAP for fluid, lag-free motion. The cursor must expand, reveal a cosmic lens flare, or invert when hovering over major focal elements/links.  
2. **Top-Tier X-Axis Shutter Hover Animation:** For key portfolio cards and capability sliders, design a "camera shutter" style transition. On hover, the element must split or slide open wide along the X-axis (left and right panels moving apart) using GSAP custom easing, revealing vibrant, deep cosmic media previews or service metrics nested underneath.  
3. **Oversized Elastic Split-Text Entrance (Hero Section):** On page load, the main headline must split by character/word and reveal with a dynamic, fluid, elastic spring curve, transitioning from subtle blur to sharp gold brilliance.  
4. **Horizontal Viewport Scroll (Capabilities Section):** Use GSAP ScrollTrigger to pin the viewport at the "Capabilities" section. As the user scrolls vertically, the track must smoothly slide horizontally (left-to-right) revealing arched, constellation-styled capability panels.  
5. **Interactive Celestial Campaign Calculator:** A beautifully styled widget featuring gold-bordered cards (border-\[\#dfba6b\]/30) and a glowing gold range slider. Users can slide their AED marketing budget and watch cosmic indicators (Reach, Deliverables, Impressions) count up dynamically on the fly with custom numeric animations.

### **📐 Section-by-Section Structure:**

#### **1\. Hero Section (The Celestial Stage)**

* Features a large watermark silhouette of the logo "logo.png" in the background with a parallax depth effect.  
* An absolute masterclass headline: "WE LAUNCH BRANDS INTO THE DIGITAL COSMOS." (rendered in Lemon Milk and editorial luxury serif).  
* Floating subtle constellation lines in the background that shift with the user's mouse position (interactive parallax).  
* A primary CTA button styled as a solid gold block that expands to reveal a cosmic gradient on hover.

#### **2\. Cosmic Impact Ticker (Social Proof)**

* A thin, elegant gold-bordered horizontal ticker infinitely scrolling key milestones: \[50M+ Views Delivered\] ✦ \[3.5x Average ROAS\] ✦ \[15+ Elite UAE Brands\] styled with moon phase icons separating the metrics.

#### **3\. Capabilities & Case Studies (Horizontal Track)**

* Pinned scroll section featuring three arched "Portal" cards (matching the arches in image\_36d489.jpg):  
  * **Portal 1 (Paid Acquisition):** Detailed with star-mapping visuals.  
  * **Portal 2 (Social Media Engine):** Focused on short-form Gen-Z dynamic content creation.  
  * **Portal 3 (Aesthetics & Branding):** Representing pure visual design identity.  
* Each card utilizes the custom X-axis Shutter reveal on mouse hover.

#### **4\. The Campaign Estimator (Interactive Calculator)**

* Resembles a high-end astrological dashboard but engineered for marketing metrics.  
* Sleek gold range sliders and customized inputs mapping budgets from 2,000 to 50,000+ AED.  
* Real-time calculations displaying projected results with smooth step animations.

#### **5\. High-Converting Oracle Form (Lead Gen) & Footer**

* A clean, celestial questionnaire-style layout asking questions like "What cosmic milestone are you chasing?"  
* Dynamic inputs with an elegant glowing gold highlight effect on focus.  
* Footer featuring a minimalist version of the logo "logo.png", contact information, and coordinates of the UAE agency headquarters.

### **💻 Code**