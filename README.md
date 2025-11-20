# Plushiez Shopify Theme

A custom Shopify theme designed specifically for Plushiez - your destination for cute plushies, anime characters, K-pop collectibles, and kawaii items.

## Features

- **Cute & Kawaii + Modern Minimalist Design**: Perfectly balanced aesthetic combining playful elements with clean, professional layouts
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Custom Color Palette**: Soft pastels (Blush Pink, Lavender, Mint) with modern neutrals
- **Beautiful Product Pages**: Image galleries, variant selection, and smooth animations
- **Featured Collections**: Showcase your best products with style
- **Hero Banner**: Eye-catching homepage section with customizable text and images
- **Custom Typography**: Clean, modern fonts with gradient text effects
- **Smooth Animations**: Subtle micro-interactions throughout
- **SEO Optimized**: Fast loading times and proper semantic HTML
- **Newsletter Integration**: Built-in newsletter signup form
- **Social Media Links**: Connect with customers on Instagram, TikTok, Twitter, and Pinterest

## Color Palette

- **Soft Blush** `#FFB6C8` - Primary color
- **Lavender Dream** `#C4B5FD` - Secondary color
- **Mint Fresh** `#A7F3D0` - Accent color
- **Peachy** `#FECACA` - Warm accent
- **Cloud** `#F9FAFB` - Light backgrounds
- **Silver** `#E5E7EB` - Borders
- **Charcoal** `#374151` - Body text
- **Noir** `#1F2937` - Headings

## Installation

### Prerequisites

- Shopify CLI installed (included in this setup)
- A Shopify store (you have: plushiez.shop)
- Git installed

### Deploy to Shopify

1. **Authenticate with Shopify**
   ```bash
   cd plushiez-theme
   shopify login --store=plushiez.shop
   ```

2. **Push the theme to your store**
   ```bash
   shopify theme push
   ```

   When prompted, choose whether to push to a new development theme or publish directly.

3. **Preview your theme**
   ```bash
   shopify theme dev
   ```
   This will open a preview URL where you can see your theme in action.

### Alternative: Upload via Shopify Admin

1. Zip the `plushiez-theme` folder
2. Go to your Shopify Admin > Online Store > Themes
3. Click "Upload theme" and select the zip file

## Customization

### Theme Settings

Access theme settings in Shopify Admin > Online Store > Themes > Customize

**Available Settings:**
- Colors: All brand colors can be adjusted
- Typography: Choose your preferred font
- Layout: Adjust page width and margins
- Border Radius: Control roundness of buttons and inputs

### Header Customization

- Upload your logo image (recommended: 200px wide)
- Configure navigation menu
- Enable/disable search icon

### Footer Customization

- Add your tagline
- Social media links (Instagram, Twitter, TikTok, Pinterest)
- Configure footer menus
- Enable/disable newsletter signup

### Homepage Setup

1. **Add Hero Banner**
   - Customize: Online Store > Themes > Customize
   - Add section: "Hero Banner"
   - Set title, subtitle, image, and button links

2. **Add Featured Collection**
   - Add section: "Featured Collection"
   - Select a collection to showcase
   - Choose number of products to display (4-12)

## File Structure

```
plushiez-theme/
├── assets/
│   └── critical.css          # Main stylesheet
├── config/
│   ├── settings_schema.json  # Theme settings
│   └── settings_data.json    # Default values
├── layout/
│   └── theme.liquid          # Main layout
├── sections/
│   ├── header.liquid         # Site header
│   ├── footer.liquid         # Site footer
│   ├── hero-banner.liquid    # Homepage hero
│   ├── featured-collection.liquid
│   ├── product.liquid        # Product page
│   └── collection.liquid     # Collection page
├── snippets/
│   └── css-variables.liquid  # CSS custom properties
└── templates/                # Page templates
```

## Development

### Local Development

```bash
shopify theme dev
```

This starts a local development server with hot reload.

### Making Changes

1. Edit files in your local theme directory
2. Changes will sync automatically when using `shopify theme dev`
3. For manual deployment:
   ```bash
   shopify theme push
   ```

## Product Setup Tips

1. **Product Images**: Use square images (1:1 ratio) for best results
2. **Collections**: Create collections for different categories:
   - Cute Animals
   - Anime Characters
   - K-pop Idols
   - Food Plushies
3. **Tags**: Use tags to categorize products (e.g., "kawaii", "plushie", "keychain")
4. **Descriptions**: Write engaging product descriptions

## Menu Setup

### Main Navigation

Create a menu in Shopify Admin > Navigation with links to:
- Home
- Shop / Collections
- About
- Contact

### Footer Menus

Create two menus:
1. **Quick Links**: Shop, About, Blog
2. **Customer Care**: Shipping, Returns, FAQ, Contact

## Social Media

Add your social media URLs in the Footer section settings:
- Instagram: Best for product photos
- TikTok: Great for plushie unboxing videos
- Twitter: Customer engagement
- Pinterest: Product inspiration boards

## Performance

This theme is optimized for speed:
- Lazy loading images
- Responsive images with srcset
- Critical CSS inlined
- Minimal JavaScript
- Font loading optimization

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Support

For theme support:
- Check Shopify's theme documentation
- Review this README
- Contact Plushiez support at your store email

## License

Custom theme for Plushiez © 2024

---

**Built with love for cute things** 🧸💕
