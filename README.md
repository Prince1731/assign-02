#  The Smoothie Machine

A fun, interactive **client-side web app** where users can customize and order their perfect smoothie.  
It features live pricing, a visual smoothie cup preview, and an order history list — all without a backend.

##  Project Structure
```
smoothie_machine/
├── index.html       # Main HTML layout
├── styles.css       # App styling (dark theme with accent colors)
├── js/
│   ├── smoothie.js  # Smoothie class, pricing data, ingredient colors
│   └── app.js       # Form handling, DOM rendering, cup visuals
└── README.md        # Project documentation
```

##  Features
- **Size selection** — Small, Medium, Large
- **Base selection** — Water, Milk, Almond Milk, Yogurt
- **Multiple ingredients** — Choose from fresh fruits and greens
- **Optional add-ons** — Protein powder, chia seeds, honey
- **Sweetness slider** — 0% to 100% sweetness
- **Special instructions** — For personalized requests
- **Live order summary** — Updates immediately after placing order
- **Bill breakdown** — Itemized costs, subtotal, and total
- **Cup visualizer** — Shows smoothie layers based on selected ingredients
- **Order history** — Keeps track of previous orders (session-based)

##  Technologies Used
- **HTML5** — Semantic form structure
- **CSS3** — Responsive layout, dark mode design, and custom styling
- **JavaScript (ES Modules)** — Interactive logic and rendering

##  How to Run Locally
1. **Download or clone** this repository:
   bash
   git clone https://github.com/your-username/smoothie_machine.git
   
2. Open `index.html` in your **browser** (no server required).

##  Deployment (GitHub Pages)
1. Push all files to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Source**, choose:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**.
5. Your app will be available at:

   https://<your-username>.github.io/smoothie_machine/
   


