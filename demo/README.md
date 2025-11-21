# Lightpack CSS Framework - Demo Themes

Professional, production-ready themes showcasing the power of Lightpack CSS Framework.

## 🎨 Available Themes

### 1. Blog Listing Page (`blog-listing.html`)
A modern blog homepage featuring:
- **Hero section** with gradient background
- **Featured post** with large card layout
- **Grid-based article listing** (responsive 1-2-3 columns)
- **Category badges** with semantic colors
- **Author avatars** and metadata
- **Newsletter subscription** section
- **Pagination** component
- **Sticky navigation** with theme toggle
- **Responsive footer** with multiple columns

**Lightpack Features Used:**
- Grid system (`grid`, `grid-cols-*`)
- Flexbox utilities (`flex`, `items-center`, `justify-between`)
- Spacing utilities (`p-*`, `m-*`, `gap-*`)
- Typography (`fs-*`, `fw-*`)
- Color utilities (`bg-*`, `text-*`)
- Responsive variants (`-sm`, `-md`, `-lg`, `-xl`)
- Card component
- Badge component
- Button variants
- Shadow utilities
- Border radius utilities

### 2. Blog Post Page (`blog-post.html`)
A beautiful article reading experience featuring:
- **Gradient header** with article metadata
- **Sticky sidebar** with table of contents
- **Prose styling** for long-form content
- **Code blocks** with syntax highlighting
- **Alert components** for callouts
- **Author bio** section
- **Related articles** grid
- **Comments section** with avatars
- **Share buttons**
- **Responsive layout** (sidebar hides on mobile)

**Lightpack Features Used:**
- Sidebar layout with sticky positioning
- Typography scale for content hierarchy
- Alert components (info, success)
- Card components
- Avatar component
- Form elements (textarea, input)
- Responsive grid
- Spacing scale for consistent rhythm
- CSS variables for theming

## 🚀 Key Highlights

### Minimal Custom CSS
Both themes use **less than 50 lines of custom CSS**, proving Lightpack's utility-first approach:
- Gradient backgrounds
- Hover transitions
- Prose styling
- Minor adjustments

### 100% Lightpack Utilities
- ✅ Layout: Grid & Flexbox
- ✅ Spacing: Margin, Padding, Gap
- ✅ Typography: Font sizes, weights, alignment
- ✅ Colors: Semantic colors, backgrounds, text
- ✅ Components: Cards, badges, buttons, alerts, forms
- ✅ Responsive: Mobile-first breakpoints
- ✅ Effects: Shadows, borders, radius

### Production-Ready
- Semantic HTML5
- Accessible markup
- SEO-friendly structure
- Mobile-responsive
- Dark mode support (toggle button)
- Fast loading (minimal CSS)

## 📱 Responsive Breakpoints

Both themes are fully responsive:
- **Mobile** (< 640px): Single column, stacked layout
- **Tablet** (640px - 1024px): 2-column grids
- **Desktop** (> 1024px): 3-4 column grids, sidebar visible

## 🎯 What These Demos Prove

1. **Rapid Development**: Complex layouts built with utility classes
2. **Consistency**: Design system enforced through variables
3. **Flexibility**: Easy customization via CSS variables
4. **Performance**: Minimal custom CSS needed
5. **Maintainability**: Utility classes are self-documenting
6. **Scalability**: Patterns easily replicable

## 🛠️ How to Use

1. **View the demos**:
   ```bash
   # Open in browser
   open demo/blog-listing.html
   open demo/blog-post.html
   ```

2. **Customize**:
   - Change colors via CSS variables
   - Adjust spacing with utility classes
   - Modify layouts with grid/flex utilities

3. **Learn from the code**:
   - Inspect the HTML to see utility class patterns
   - Notice minimal custom CSS
   - Study responsive design approach

## 💡 Learning Resources

Each demo showcases:
- **Grid System**: Responsive multi-column layouts
- **Flexbox**: Alignment and distribution
- **Typography**: Hierarchy and readability
- **Color System**: Semantic color usage
- **Components**: Cards, badges, buttons, alerts
- **Spacing**: Consistent rhythm
- **Responsive Design**: Mobile-first approach

## 🎨 Customization Examples

### Change Primary Color
```css
:root {
  --color-primary: var(--indigo);
}
```

### Adjust Spacing
```html
<!-- Change padding -->
<div class="p-4">  <!-- to -->  <div class="p-6">

<!-- Change gap -->
<div class="gap-4">  <!-- to -->  <div class="gap-6">
```

### Modify Typography
```html
<!-- Change font size -->
<h1 class="fs-4xl">  <!-- to -->  <h1 class="fs-5xl">

<!-- Change font weight -->
<p class="fw-400">  <!-- to -->  <p class="fw-500">
```

## 📊 Stats

- **Total Lines**: ~800 lines (both files)
- **Custom CSS**: < 50 lines per file
- **Lightpack Utilities**: 95%+ of styling
- **Components Used**: 10+ (cards, badges, buttons, alerts, forms, etc.)
- **Responsive Breakpoints**: 4 (sm, md, lg, xl)

## 🔗 Related Documentation

- [Utilities Guide](../docs/utilities.md)
- [Customization Guide](../docs/customization.md)
- [Components](../docs/)
- [Variables Reference](../docs/variables.md)

---

**Built with ❤️ using Lightpack CSS Framework**
