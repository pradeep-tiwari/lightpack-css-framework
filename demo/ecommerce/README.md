# E-commerce Theme - TechStore

Professional, production-ready e-commerce pages built with **100% Lightpack CSS utilities** - no custom CSS classes needed!

## 📦 Pages Included

### 1. Landing Page (`index.html`)
Complete e-commerce homepage featuring:
- Top announcement bar
- Sticky navigation with cart
- Hero section with CTA
- Feature highlights (shipping, warranty, returns, payment)
- Category grid (4 columns responsive)
- Featured products grid (1→2→4 columns)
- Customer testimonials
- Newsletter subscription
- Multi-column footer

### 2. Product Detail Page (`product.html`)
Full-featured product page with:
- Product image gallery with thumbnails
- Product info (price, ratings, stock status)
- Color selection buttons
- Quantity selector
- Add to cart & buy now actions
- Feature badges (shipping, warranty, returns)
- Tabbed content (description, specs, reviews, shipping)
- Customer reviews with ratings breakdown
- Review cards with helpful votes
- Related products grid

### 3. Shopping Cart (`cart.html`)
Complete cart experience:
- Cart items with images & details
- Quantity controls per item
- Remove item buttons
- Order summary with calculations
- Promo code input
- Payment method badges
- Recommended products
- Trust badges section

## 🎯 100% Lightpack Utilities

### Zero Custom CSS
These pages use **ONLY** Lightpack's built-in classes:
- ✅ Layout: Grid, Flexbox, Container
- ✅ Spacing: Margin, Padding, Gap
- ✅ Typography: Font sizes, weights
- ✅ Colors: Backgrounds, text, borders
- ✅ Components: Cards, badges, buttons, alerts, forms
- ✅ Responsive: Breakpoint variants
- ✅ Positioning: Absolute, relative, sticky
- ✅ Effects: Shadows, borders

### Inline Styles Used (Minimal)
Only 2 cases where inline styles are necessary:
1. **Progress bar widths** - Dynamic data-driven values (e.g., `width: 75%`)
2. **Input group constraints** - Max-width on quantity selectors

These are acceptable as they represent dynamic/contextual values not covered by utility classes.

## 🚀 Lightpack Features Showcased

### Components Used
- ✅ **Cards** - Product cards, info cards
- ✅ **Badges** - Category, status, discount badges
- ✅ **Buttons** - Primary, outline, ghost variants
- ✅ **Alerts** - Success messages
- ✅ **Forms** - Inputs, input groups
- ✅ **Navbar** - Sticky navigation
- ✅ **Breadcrumbs** - Navigation trail
- ✅ **Tabs** - Product information tabs
- ✅ **Progress** - Rating breakdown bars
- ✅ **Avatar** - User initials, icons

### Layout Patterns
- ✅ **Grid System** - Responsive product grids
- ✅ **Flexbox** - Navigation, card layouts
- ✅ **Sticky Positioning** - Fixed navbar
- ✅ **Absolute Positioning** - Badge overlays
- ✅ **Responsive Columns** - Mobile-first design

### Utility Classes
- ✅ **Spacing Scale** - Consistent margins/padding (`p-4`, `mb-3`, `gap-5`)
- ✅ **Typography** - Font sizes (`fs-xl`, `fs-2xl`), weights (`fw-600`, `fw-700`)
- ✅ **Colors** - Semantic colors (`bg-primary`, `text-success`, `bg-surface`)
- ✅ **Display** - Show/hide (`d-none`, `d-block-md`)
- ✅ **Flexbox** - Alignment (`flex`, `items-center`, `justify-between`)
- ✅ **Grid** - Columns (`grid-cols-1`, `grid-cols-md-2`, `grid-cols-lg-4`)

## 📱 Responsive Design

All pages are fully responsive using Lightpack's breakpoint system:

**Mobile (< 640px)**
- Single column layouts
- Stacked navigation
- Full-width cards

**Tablet (640px - 1024px)**
- 2-column product grids
- Visible navigation links
- Optimized spacing

**Desktop (> 1024px)**
- 4-column product grids
- Full navigation
- Sidebar layouts

## 🎨 Design Highlights

### Color System
- **Primary** - Black/dark for main actions
- **Success** - Green for positive states
- **Danger** - Red for discounts/alerts
- **Warning** - Orange for urgency
- **Info** - Teal for information
- **Surface** - Light gray backgrounds

### Typography Scale
- **Headings** - `fs-5xl` (hero), `fs-3xl` (sections), `fs-2xl` (subsections)
- **Body** - `fs-base` (default), `fs-lg` (emphasis)
- **Small** - `fs-sm` (meta), `fs-xs` (labels)

### Spacing Consistency
- **Sections** - `py-8` (standard), `py-6` (compact)
- **Cards** - `p-4` (body), `p-5` (featured)
- **Grids** - `gap-4` (standard), `gap-5` (spacious)

## 💡 Key Patterns

### Product Card
```html
<article class="card">
    <img src="..." class="card-media">
    <div class="card-body">
        <span class="badge bg-primary text-white px-2 py-1 mb-2">Category</span>
        <h3 class="fw-600 mb-2">Product Name</h3>
        <div class="flex items-center gap-2 mb-3 fs-sm">
            <span class="text-warning">★★★★★</span>
            <span class="text-muted">4.8 (245)</span>
        </div>
        <div class="flex items-center justify-between">
            <span class="fs-xl fw-700 text-primary">$199</span>
            <button class="btn btn-primary btn-sm">Add</button>
        </div>
    </div>
</article>
```

### Feature Highlight
```html
<div class="flex items-center gap-3">
    <div class="avatar bg-primary text-white fw-700">🚚</div>
    <div>
        <div class="fw-600">Free Shipping</div>
        <div class="fs-sm text-muted">On orders over $50</div>
    </div>
</div>
```

### Badge Overlay
```html
<div class="relative">
    <img src="..." class="card-media">
    <span class="badge bg-danger text-white absolute top-3 right-3">-20%</span>
</div>
```

## 📊 Stats

- **Total Pages**: 3 (Landing, Product, Cart)
- **Total Lines**: ~1,200 lines (all pages)
- **Custom CSS**: 0 classes
- **Inline Styles**: 2 use cases (progress bars, input constraints)
- **Lightpack Utilities**: 100% of styling
- **Components Used**: 10+ (cards, badges, buttons, alerts, forms, etc.)
- **Responsive Breakpoints**: 4 (sm, md, lg, xl)

## 🔗 Navigation

- **Home** → `index.html`
- **Product** → `product.html`
- **Cart** → `cart.html`

## 🎓 Learning Points

### What This Demonstrates

1. **Utility-First Works** - Complex e-commerce UI without custom CSS
2. **Component Reusability** - Same card pattern used everywhere
3. **Responsive by Default** - Mobile-first approach with breakpoint variants
4. **Semantic HTML** - Proper use of article, nav, section elements
5. **Accessibility** - Proper button labels, alt text, semantic markup
6. **Consistency** - Design system enforced through utilities

### Best Practices Shown

- ✅ Consistent spacing using scale (`--g-1` to `--g-9`)
- ✅ Semantic color usage (success, danger, warning, info)
- ✅ Responsive grid patterns (1→2→4 columns)
- ✅ Flexbox for alignment and distribution
- ✅ Card component for content containers
- ✅ Badge component for labels and status
- ✅ Button variants for different actions
- ✅ Typography hierarchy with font scale

## 🚀 Quick Start

1. **View the demos**:
   ```bash
   open demo/ecommerce/index.html
   open demo/ecommerce/product.html
   open demo/ecommerce/cart.html
   ```

2. **Customize**:
   - Change colors: Modify badge classes (`bg-primary`, `bg-success`)
   - Adjust spacing: Change utility classes (`p-4` → `p-5`, `gap-4` → `gap-5`)
   - Modify layout: Change grid columns (`grid-cols-lg-4` → `grid-cols-lg-3`)

3. **Learn**:
   - Inspect HTML to see utility patterns
   - Notice zero custom CSS needed
   - Study responsive design approach

## 🎯 Production Ready

These pages are production-ready and include:
- ✅ Semantic HTML5
- ✅ Accessible markup
- ✅ SEO-friendly structure
- ✅ Mobile-responsive
- ✅ Fast loading (no custom CSS)
- ✅ Easy to maintain (utility classes)

---

**Built with ❤️ using 100% Lightpack CSS Framework**
