## **1. Introduction to Tailwind CSS**

- What is Tailwind CSS?
- Why Tailwind over traditional CSS?
- Comparison: Tailwind vs Bootstrap vs Custom CSS
- How Tailwind works (Utility-First, Atomic CSS)
- CDN vs NPM installation

🔸 **Example:** Build a simple responsive heading using CDN

---

## **2. Setting up Tailwind CSS**

- Using CDN (Quick Prototyping)
- Installing via NPM
- Using with:

  - **Vite**
  - **React**
  - **Next.js**
  - **Vue**
  - **Laravel**

- Creating a custom config file (`tailwind.config.js`)
- Purging unused styles

🔸 **Project Idea:** Set up Tailwind in a Vite + React or Next.js project

---

## **3. Tailwind CSS File Structure & Workflow**

- Directory structure
- Adding Tailwind to CSS (`@tailwind base`, `@tailwind components`, `@tailwind utilities`)
- How Tailwind compiles
- Using `npx tailwindcss build`

---

## **4. Core Concepts**

### a. Utility-First Classes

- Writing classes in HTML instead of CSS

### b. Mobile-First Breakpoints

- Responsive design in Tailwind (`sm:`, `md:`, `lg:`, etc.)

### c. Composability

- Composing multiple utilities into component classes

---

## **5. Styling Text & Typography**

- `text-base`, `text-xl`, `text-sm`, etc.
- `font-bold`, `font-light`, `font-medium`, `font-serif`, `font-sans`
- `leading-loose`, `tracking-tight`
- `text-center`, `text-left`, `text-right`
- `uppercase`, `capitalize`, `truncate`, `line-clamp`

🔸 **Example:** Build a blog post layout with heading, subheading, and body

---

## **6. Colors and Backgrounds**

- `bg-red-500`, `text-gray-700`, `border-blue-200`, etc.
- Hover, focus, and active states
- Opacity control: `bg-opacity-50`, `text-opacity-70`
- Gradients: `bg-gradient-to-r`, `from-indigo-500`, `to-pink-500`

🔸 **Mini Project:** Gradient login page with hover effects

---

## **7. Spacing (Padding and Margin)**

- `p-4`, `px-2`, `py-1`, `m-0`, `mt-2`, `ml-auto`, etc.
- Negative margins: `-mt-2`
- Space between elements: `space-x-4`, `space-y-2`

🔸 **Example:** Card layout with proper spacing

---

## **8. Sizing (Width, Height, Max, Min)**

- Widths: `w-1/2`, `w-full`, `w-screen`, `max-w-sm`
- Heights: `h-32`, `h-screen`, `min-h-full`
- Aspect ratio plugin: `aspect-w-16`, `aspect-h-9`

🔸 **Example:** Responsive image gallery using aspect ratio

---

## **9. Layout and Flexbox**

- `flex`, `inline-flex`
- `flex-row`, `flex-col`, `flex-wrap`
- `items-center`, `justify-between`, `gap-4`
- `grow`, `shrink`, `basis-1/3`

🔸 **Mini Project:** Navbar and pricing cards using flexbox

---

## **10. Grid System**

- `grid`, `grid-cols-2`, `grid-cols-12`
- `gap-4`, `col-span-6`, `row-span-2`
- Auto placement and template rows/cols

🔸 **Example:** Portfolio layout using grid

---

## **11. Positioning and Z-Index**

- `relative`, `absolute`, `fixed`, `sticky`
- `top-0`, `bottom-4`, `left-2`, `right-0`
- `z-0`, `z-10`, `z-50`

🔸 **Example:** Sticky header with z-index and shadow

---

## **12. Borders and Dividers**

- `border`, `border-2`, `border-dashed`
- `rounded`, `rounded-lg`, `rounded-full`
- `divide-x`, `divide-y`, `divide-gray-300`

🔸 **Example:** Dashboard cards with divider and rounded corners

---

## **13. Shadows and Effects**

- Box shadows: `shadow`, `shadow-md`, `shadow-xl`
- Ring effects: `ring`, `ring-offset-2`, `ring-blue-500`
- Mix-blend modes: `mix-blend-multiply`
- Backdrop filters (plugin): `backdrop-blur`, `backdrop-brightness`

---

## **14. Transitions and Animations**

- `transition`, `transition-colors`, `duration-300`, `ease-in-out`
- Animate plugin: `animate-bounce`, `animate-spin`, `animate-pulse`
- Custom keyframes in Tailwind config

🔸 **Mini Project:** Hover animation card

---

## **15. Pseudo-Class Variants**

- `hover:`, `focus:`, `active:`, `disabled:`, `group-hover:`
- `first:`, `last:`, `odd:`, `even:`
- `peer` and `peer-checked` use case

🔸 **Example:** Grouped hover effect on image and caption

---

## **16. Responsive Design**

- Breakpoints: `sm`, `md`, `lg`, `xl`, `2xl`
- Responsive visibility: `hidden`, `block`, `sm:block`
- Responsive utility stacking

🔸 **Project Idea:** Fully responsive landing page

---

## **17. Customization and Configuration**

- `tailwind.config.js` customization:

  - Extending colors
  - Adding custom fonts
  - Custom breakpoints
  - Extending variants and plugins

🔸 **Example:** Add custom color palette and font-family

---

## **18. Forms and Input Styling**

- `form-input`, `form-checkbox`, `form-select`
- Styling focus states
- `peer` based validation styling

🔸 **Example:** Contact form with error states

---

## **19. Reusable Components**

- Creating custom button, card, modal components
- Using `@apply` in your CSS
- Avoiding repetition with components

🔸 **Example:** Button component with hover, active, and disabled states

---

## **20. Theming and Dark Mode**

- `dark:` variant
- Toggle using class strategy or media strategy
  🔸 **Project Idea:** Dark mode portfolio toggle

---
