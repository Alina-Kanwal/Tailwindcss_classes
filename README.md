# Tailwindcss_classes
🌟 TailwindCSS Cheat Sheet
🎨 Colors
bg-gray-100   → background light gray
bg-blue-500   → background blue
text-red-600  → red text
border-green-400 → green border

left right and top bottom gap
px-10 👉 left & right gap
py-4 👉 top & bottom gap
p-4 👉 all sides gap



👉 Pattern: bg-{color}-{shade}, text-{color}-{shade}, border-{color}-{shade}
Shades go from 50 (lightest) → 900 (darkest).

📏 Sizing
w-64     → width 16rem (256px)
h-32     → height 8rem (128px)
h-screen → height = full screen (100vh)
min-h-screen → minimum height = full screen
max-w-lg → max width large (about 32rem)

📐 Spacing (Margin + Padding)

👉 Pattern: m = margin, p = padding.
Add side letters: t (top), b (bottom), l (left), r (right), x (left+right), y (top+bottom).

m-4    → margin 1rem
mt-2   → margin-top 0.5rem
mb-8   → margin-bottom 2rem
px-6   → padding left & right 1.5rem
py-2   → padding top & bottom 0.5rem

✍️ Text
text-center   → align text center
text-left     → align left
text-right    → align right

text-sm       → small text
text-lg       → large text
text-2xl      → extra large text

font-light    → thin
font-semibold → semi-bold
font-bold     → bold

📦 Flexbox & Layout
flex              → enable flexbox
flex-col          → vertical layout (column)
flex-row          → horizontal layout (default)

items-center      → vertical center
items-start       → align top
items-end         → align bottom

justify-center    → horizontal center
justify-between   → space between
justify-around    → space around
justify-end       → align right

🖼 Borders & Radius
border            → add border
border-2          → border width 2px
border-gray-400   → gray border

rounded           → small rounded corners
rounded-lg        → medium round
rounded-full      → fully round (circle)

✨ Shadows
shadow-sm  → small shadow
shadow-md  → medium shadow
shadow-lg  → large shadow
shadow-xl  → extra large shadow

🔄 Positioning
absolute   → absolute positioning
relative   → relative positioning
fixed      → fixed to viewport
top-0      → stick to top
bottom-0   → stick to bottom
left-0     → stick to left
right-0    → stick to right

2. flex
➡️ Ye element ko Flexbox container bana deta hai.
Flexbox ek layout system hai jo easily content ko row/column me arrange aur center kar deta h

1. min-h-screen

➡️ Ye ensure karta hai ke <body> (ya jo bhi element hai) ki minimum height poori screen (100vh) ho.
Matlab agar content kam bhi ho, to bhi element poori screen ki height lega.
Isse fayda: center alignment properly kaam karti hai (warna chhoti height wale element ko center karna mushkil hota).

absolute ka kaam hota hai —
element ko normal layout se nikal kar screen (ya parent) ke andar exact position par rakhna.

🧠 Matlab:
tum absolute use karke top, right, bottom, left se uska exact jagah control karti ho.







