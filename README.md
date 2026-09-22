# RTM Icons Free - Icon Font Library

RTM Icons Free is a comprehensive, open-source icon font library designed for web developers and designers. This collection includes 1,025+ professionally crafted icons in two styles: **regular** and **thin**, providing flexibility and consistency for your projects.

## Features

- **1,025+ Icons**: Complete set of icons covering various categories
- **Two Styles**: Regular (555 icons) and Thin (470 icons)
- **Multiple Formats**: WOFF2, WOFF, TTF, SVG, and EOT formats for maximum browser compatibility
- **Lightweight**: Optimized font files with minimal file size
- **Easy Integration**: Simple CSS-based implementation
- **Interactive Gallery**: Built-in index.html with searchable icon preview and one-click class copying

## Icon Categories

The icon library includes icons for:
- UI/UX Elements (buttons, forms, toggles, switches)
- Navigation (arrows, chevrons, menus, sidebars)
- Media (images, videos, audio, camera)
- Business (finance, charts, graphs, analytics)
- E-commerce (shopping carts, products, pricing)
- Social Media (platforms and sharing icons)
- Utilities (settings, notifications, alerts, clocks)
- And many more categories...

## Getting Started

### Installation

1. Download or clone the RTM Icons Free repository to your project directory
2. Copy the `fonts/` and `css/` directories to your project

### Basic Usage

#### Step 1: Link the CSS file in your HTML

```html
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" href="path/to/css/rtmicons.css">
</head>
<body>
    <!-- Your content here -->
</body>
</html>
```

#### Step 2: Add icons using the class names

**Regular Style Icons:**
```html
<i class="rtmicon rtmicon-accordion"></i>
<i class="rtmicon rtmicon-add-circle"></i>
<i class="rtmicon rtmicon-arrow-right"></i>
```

**Thin Style Icons:**
```html
<i class="rtmicon-thin rtmicon-alarm-clock"></i>
<i class="rtmicon-thin rtmicon-user"></i>
<i class="rtmicon-thin rtmicon-settings"></i>
```

### Styling Icons

You can customize icon appearance using CSS:

```css
/* Change icon size */
i.rtmicon {
    font-size: 24px;
}

/* Change icon color */
i.rtmicon {
    color: #333333;
}

/* Add hover effects */
i.rtmicon:hover {
    color: #007bff;
    transition: color 0.3s ease;
}

/* Change icon weight (thin style) */
i.rtmicon-thin {
    font-size: 32px;
    color: #666666;
}
```

## Finding Icons

### Using the Interactive Gallery

Open `index.html` in your browser to access the interactive icon gallery which features:
- **Search functionality**: Filter icons by name in real-time
- **Tab navigation**: Switch between Regular, Thin, and All icons views
- **One-click copying**: Click any icon to copy its class name automatically
- **Visual feedback**: "Copied!" notification confirms successful copy
- **Icon statistics**: See total icon counts for each style

### Icon Naming Convention

Icons follow a consistent naming pattern:
```
rtmicon-{icon-name}
```

Examples:
- `rtmicon-accordion`
- `rtmicon-add-box`
- `rtmicon-arrow-down`
- `rtmicon-shopping-cart`

## Complete Icon List

### Regular Style (555 icons)
accordion, account-balance, add, add-box, add-business, add-card, add-circle, advanced-button, advanced-google-map, advanced-heading, advanced-hero-slider, advanced-sticky, advanced-tabs, advanced-toggle, alarm-clock, alert, analytics, anchor, android, animated-circle-button, animated-heading, apple, apps, archive-post, archive-product, arrow-down, arrow-down-left, arrow-down-right, arrow-down-to-line, arrow-left, arrow-long-down, arrow-long-left, arrow-long-right, arrow-long-up, arrow-right, arrow-up, arrow-up-left, arrow-up-right, artist, attach-money, audio-box, audio-file, author-box, auto-play, auto-renew, award, backpack, back-to-top-button, backup, badge-check, badge-dollar, badge-percent, ban, banner-ad, banner-discount, bar-chart, barcode, bar-progress, bars, bar-sort-left, bar-sort-right, battery, behance, blob-shape, block, blockquote, blog, blog-carousel, blog-post, bluetooth, bolt, book, bookmark, box, box-archive, box-check, box-circle-check, box-open, box-package, box-stacked, breadcumb, briefcase, browser, bug-report, business-hour, calculate, calendar, calendar-check, calendar-check-2, calendar-clock, calendar-days, calendar-minus, calendar-plus, calendar-star, calendar-xmark, call-to-action, call-to-action1, camera, campaign, camping, card-carousel, card-slider, caret-down, caret-down-2, caret-left, caret-left-2, caret-right, caret-right-2, caret-up, caret-up-2, celebration, charger, chart, chart-line-down, chart-line-up, chat-bubble, check, checkbox, check-box-outline-blank, chevron-down, chevron-left, chevron-right, chevrons-down, chevrons-left, chevrons-right, chevrons-up, chevron-up, circle-arrow-down, circle-arrow-down-2, circle-arrow-down-left, circle-arrow-down-left-2, circle-arrow-down-right, circle-arrow-down-right-2, circle-arrow-left, circle-arrow-left-2, circle-arrow-right, circle-arrow-right-2, circle-arrow-up, circle-arrow-up-2, circle-arrow-up-left, circle-arrow-up-left-2, circle-arrow-up-right, circle-arrow-up-right-2, circle-caret-down, circle-caret-down-2, circle-caret-left, circle-caret-left-2, circle-caret-right, circle-caret-right-2, circle-caret-up, circle-caret-up-2, circle-check, circle-chevron-down, circle-chevron-left, circle-chevron-right, circle-chevron-up, circle-down, circle-left, circle-minus, circle-plus, circle-right, circle-up, circle-user, circle-xmark, city, clapperboard-video, client-carousel, client-grid, client-list, clipboard, clipboard-check, clipboard-list, clipping-mask, clock, clock-desk, close, close-small, cloud-check, cloud-download, cloud-upload, code, code-2, coin, coin-dollar, coin-group, coins, color-picker, comment, comments, comments-question, content-slider, cookies, copyright, countdown, counter, counters, creative-button, credit-card-back, credit-card-front, currency-bitcoin, custom-cs, custom-cursor, custom-font, custom-js, date-form, delete, delete-forever, dentistry, desk, desktop, destruction, diamond, distance, diversity, done-all, done-outline, download, dribbble, dual-button, duplicator, earthquake, echo, elementor, email-form, envelope, envelope-check, envelope-circle-check, envelope-open, envelope-open-dollar, equalizer, error, error-404, event, event-2, event-list, expand-circle-down, facebook, favorite, fax, feather, featured-image, feedback, figma, file, file-arrow-down, file-arrow-up, file-audio, file-certificate, file-circle-check, file-circle-exclaimation, file-circle-minus, file-circle-plus, file-info, file-music, file-pdf, film-play, filterable-gallery, filter-list, finance-award, finance-shield, fingerprint, flag, flashlight, flashlight-on, flip-box, folder, folder-arrow-down, folder-arrow-up, folder-check, folder-file, folder-open, folder-open-2, folders, forest, form, forum, full-screen-slider, gear, gift, glass-cup, glass-effect, glasses, globe, globe-pointer, glowing-background-mouse-effect, graphic-bar, graphic-pie, graphic-spectrum-equalizer, grid-round, grid-rounds, group-add, handyman, header-footer, header-info, header-offcanvas, headset-mic, helicopter, help, horizontal-menu-copy, horizontal-progress-bar, hotspot, hourglass, hourglass-bottom, hourglass-top, house, icon-packs, id-card, image, image-accordion, image-box, image-comparison, image-gallery, image-hotspot, image-hover, image-info, image-list, image-marquee, image-masonry, images, image-showcase, image-slider, image-stack-info, instagram, instagram-feed, interactive-link, invoice, invoice-dollar, item-list, joystick, keep, keyboard, key-left, kite, lab-research, labs, laptop, leaderboard, leaf, lightblub, line-chart, link, linkedin, link-simple, list, live-tv, loader, lock, lock-2, login, logout, lottie-animation, male, medication, medium, megaphone, menu, menu-open, messanger, microphone, minus, mobile, mockup, mode-standby, money, money-bank-check, money-check, money-currency, money-rotation, money-target, more-horiz, more-vert, mouse, mouse-12, music-note, nav-menu, network-wifi, news-ticket, night-light-moon, note-hashtag, notes, notification, number, open-in-new, paper-form, paper-plane, pause, paypal, pen, pencil, pen-paintbrush, person-add, pets, phone, phone-classic, phone-volume-down, phone-volume-mute, phone-volume-up, pie-chart, pie-chart-2, pie-chart-analyst, pill, pin-map-location, pinterest, planet, play, play-arrow, play-circle, plus, podcast, popup-moda, portfolio-gallery, post-author, post-carousel, post-category-list, post-comment, post-content, post-excerpt, post-grid, post-info, post-list, post-navigation, post-title, presentation, price-list, price-table, pricing-compare, pricing-image-box, pricing-list, pricing-table, printer, process-step, product-carousel, product-grid, product-highlight, progress-bar, progress-step, protection, quote, radar, radial-progress-bar, radio, reddit, report, review-slider, rocket, romethemekit, rtm-form, sack-dollar, scale-balanced, scale-unbalanced, scale-unbalanced-flip, search, select, share, shield, shield-check, shield-minus, shield-plus, shield-xmark, shopping-cart, sidebar, single-post, single-product, site-logo, sliders, sliders-up, social-icons, social-share, social-share-2, spark, sparkles, speedometer, square-arrow-down, square-arrow-down-2, square-arrow-down-left, square-arrow-down-left-2, square-arrow-down-right, square-arrow-down-right-2, square-arrow-left, square-arrow-left-2, square-arrow-right, square-arrow-right-2, square-arrow-up, square-arrow-up-2, square-arrow-up-left, square-arrow-up-left-2, square-arrow-up-right, square-arrow-up-right-2, square-caret-down, square-caret-down-2, square-caret-left, square-caret-left-2, square-caret-right, square-caret-right-2, square-caret-up, square-caret-up-2, square-check, square-minus, square-plus, square-user, square-xmark, stacked-cards-scroll, stamp, star, store, submit-button, table-comparison, table-data, tablet, tag, taxes, team, team-carousel, team-content, telegram, telephone, testimonial, testimonial-carousel, text-area-form, text-form, text-marquee, textual-showcase, threads, tiktok, time, timeline, timer, toggle-off, toggle-on, tooltip, trash, trophy, tumblr, upload, user, users, veritcal-menu, video-box, video-button, video-camera, vimeo, volume-down, volume-mute, volume-up, wallet, wallet-money, watch, whatsapp, woo-product, wordpress, working-hours, wrapper-link, xmark, x-twitter, youtube

### Thin Style (470 icons)
activity-rooms, acupunture, advanced-toggle, aerobic, affordable-courses, agreement, alarm-clock, alert, ambulance, analyst, anniversaries, architect, architectural-design, aromatherapy, arrow-down, arrow-down-left, arrow-down-right, arrow-down-to-line, arrow-left, arrow-long-down, arrow-long-left, arrow-long-right, arrow-long-up, arrow-right, arrow-up, arrow-up-left, arrow-up-right, attend-event, automobile-accident, award, badge-check, badge-dollar, badge-percent, balance, balance-sheet, bank-building, banner-ad, banner-discount, bar-progress, bar-sort-left, bar-sort-right, bars, battery, bill, birthday-cake, blob-shape, block-security, blog, blog-carousel, blueprint, body-building, body-scrub, body-treatment, body-wellness, book, boost-creativity, box-package, branding-design, brickwall, bridge, briefcase, broker, browser, budget-planning, budgeting, buldozer, business-law, business-workshop, calendar, calendar-check, calendar-days, call-to-action, camera, cancer-care, card-carousel, cardio, cardiology, caret-down, caret-left, caret-right, caret-up, certificate, certified-doctor, certified-institute, certified-nurse, certified-trainer, champange, chart, chart-line-down, chart-line-up, check, chemistry, chevron-down, chevron-left, chevron-right, chevron-up, chevrons-down, chevrons-left, chevrons-right, chevrons-up, circle-arrow-down, circle-arrow-down-left, circle-arrow-down-right, circle-arrow-left, circle-arrow-right, circle-arrow-up, circle-arrow-up-left, circle-arrow-up-right, circle-caret-down, circle-caret-left, circle-caret-right, circle-caret-up, circle-check, circle-chevron-down, circle-chevron-left, circle-chevron-right, circle-chevron-up, circle-down, circle-left, circle-minus, circle-plus, circle-right, circle-up, circle-user, circle-xmark, city, clapperboard-video, client-happy, client-list, clock, clock-desk, cloud-check, cloud-download, cloud-security, cloud-upload, code, coin, coin-dollar, coin-group, coins, color-pallete, color-picker, comments, comments-question, compass, concept-design, concrete, construction, content-slider, content-strategy, cookies, copywriting, corporate-building, counters, courthouse, crane, creative-idea, credit-card, credit-card-back, credit-card-front, criminal-database, currency, data-loss-prevention, data-privacy, data-security, database-security, decor-art, dermatology, design-development, design-process, desk, diamond, diet-program, digital-marketing, disco-light, doctor, download, drawing-class, drug-offense, email-spam, emergency-care, engineering, envelope, envelope-open-dollar, event-list, event-venue, evidence, face-scrub, facial-treatment, factory-building, family-law, fax, feather, file, file-info, file-pdf, film-play, finance-award, finance-shield, fingerprint, fingerprint-scan, firewall, flag, flip-box, floral-bath, folder, folder-case, folder-file, folder-open, folders, fullday-sessions, gavel, gear, gear-house, geography, glasses, global-economy, globe, globe-pointer, gold-bars, goverment-building, graphic-bar, graphic-chart, graphic-pie, grid-round, grid-rounds, growth, guitar, gym-bag, gym-machine, handcuffs, happy-students, hard-hat, health-check, health-report, healthy-nutrition, heart-care, help, herb, home-renovation, horizontal-progress-bar, hospital-building, hot-stone-therapy, house, house-building, house-plan, id-card, image, image-accordion, image-gallery, image-hotspot, image-info, image-list, image-masonry, image-showcase, image-slider, images, immigration-issue, insurance, interior-design, internet-banking, invoice, invoice-dollar, involved, judge, kettlebell, key-left, key-right, knowledge-class, landscaping-design, laptop, law-book, lawyer, legal, letter-law, lightblub, link, link-simple, list, literature, loader, lock, locker, logo-branding, management, manicure, masquerade-event, massage-therapy, measurement, medical-checkup, megaphone, microphone, minus, mobile, mockup, money, money-bank-check, money-check, money-currency, money-management, money-rotation, money-target, moodboard, motion-graphic, natural-mask, network-security, networking, note-hashtag, notes, nurse, nutritionist, office-building, online-course, opening-ceremony-scissor, operation-theater, orthopedics, painting, paper-form, paper-plane, pedicure, pen, pen-paintbrush, pencil, pencil-case, personal-trainer, pharmacy, pharmacy-store, phone-classic, photography-camera, physiotherapy, pie-chart, pie-chart-analyst, pin-map-location, planet, play, play-areas, plumbing, plus, police-badge, presentation, pricing-table, private-event, pro-equipment, product-highlight, profit, progress-step, project-done, protection, qualifed-teachers, quote, radial-progress-bar, radiology, rate, relaxation, renovation, repair, report, residential-design, roadblock, rocket, romethemekit, roofing-service, sack-dollar, sauna-relax, saving, scaffolding, scale-balanced, scale-unbalanced, scale-unbalanced-flip, screw, search, security-camera, server-protection, shield, shield-block, shield-check, shield-minus, shield-plus, shield-xmark, shopping-cart, sidebar, skilled-teachers, sliders, sliders-up, smart-home, smart-lock, social-advertising, social-share, software, speaker, speaker-group, special-bath, specialist, speedometer, sponsor, square-arrow-down, square-arrow-down-left, square-arrow-down-right, square-arrow-left, square-arrow-right, square-arrow-up, square-arrow-up-left, square-arrow-up-right, square-caret-down, square-caret-left, square-caret-right, square-caret-up, square-check, square-minus, square-plus, square-user, square-xmark, stair, stamp, star, store, structural, supplement, support-protection, table-comparison, table-data, tablet, tag, target, tax-law, taxation, taxes, team, testimonial, testimonial-carousel, therapies, thermal-spa, threat-intelligence, ticket, timeline, timer, toggle-off, toggle-on, top-speaker, towels, trainers, training-center, trash, treatment, trophy, ui-ux-design, upload, urban-planning, user, users, vaccination, video-camera, video-marketing, videography-camera, virus-protection, volume-down, volume-mute, volume-up, wallet, wallet-dollar, wallet-money, watch, web-design, web-development, web-security, wedding-event, weight-loss, working-hours, xmark, yoga

## Font File Formats

RTM Icons includes multiple font formats for optimal browser compatibility:

- **WOFF2** (.woff2) - Modern format, smallest file size
- **WOFF** (.woff) - Wide browser support
- **TTF** (.ttf) - Desktop and legacy browser support
- **SVG** (.svg) - Older Safari versions
- **EOT** (.eot) - Internet Explorer support

## Browser Support

RTM Icons is compatible with all modern browsers:

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Project Structure

```
rtm-icons-free/
├── css/
│   ├── rtmicons.css              # Main CSS file (imports all styles)
│   ├── rtmicon-regular.css       # Regular style definitions
│   └── rtmicon-thin.css          # Thin style definitions
├── fonts/
│   └── rtmicons/
│       ├── rtmicon-regular.woff2
│       ├── rtmicon-regular.woff
│       ├── rtmicon-regular.ttf
│       ├── rtmicon-regular.svg
│       ├── rtmicon-regular.eot
│       ├── rtmicon-thin.woff2
│       ├── rtmicon-thin.woff
│       ├── rtmicon-thin.ttf
│       ├── rtmicon-thin.svg
│       └── rtmicon-thin.eot
├── index.html                    # Interactive icon gallery
└── README.md                      # This file
```

## Advanced Examples

### Using in React/Vue/Angular

```html
<!-- React example -->
<i className="rtmicon rtmicon-star"></i>

<!-- Vue example -->
<i :class="['rtmicon', 'rtmicon-heart']"></i>

<!-- Angular example -->
<i [class.rtmicon]="true" [class]="'rtmicon-check'"></i>
```

### Combining Multiple Styles

```css
/* Custom size for thin icons */
.icon-small.rtmicon-thin {
    font-size: 16px;
}

/* Custom size for regular icons */
.icon-large.rtmicon {
    font-size: 48px;
}
```

### Animated Icons

```css
@keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
}

.rtmicon-spinner {
    animation: spin 2s linear infinite;
}
```

```html
<i class="rtmicon rtmicon-spinner"></i>
```

## License

RTM Icons Free is provided under a **Use-Only License** (Non-Commercial Use License).

### What You Can Do ✓
- Use the icon fonts in personal and commercial web projects
- Integrate icons into your websites and web applications
- Modify the CSS styling and appearance for your needs
- Use in unlimited projects

### What You Cannot Do ✗
- Redistribute the original font files or modified versions
- Resell or redistribute this library as a standalone product
- Claim ownership or copyright of the icons
- Use the fonts in closed-source downloadable applications

### Full License Terms

Permission is hereby granted, free of charge, to any person obtaining a copy of the RTM Icons Free font and associated documentation files (the "Font"), to use the Font without restriction in personal and commercial web projects, including the rights to:

1. Use the Font to create websites and web applications
2. Embed the Font in web pages using @font-face
3. Apply custom CSS styling to the Font
4. Use the icons in unlimited number of projects

However, the licensee is NOT permitted to:

1. Modify, reverse engineer, or create derivative works of the Font files themselves
2. Redistribute the Font files, whether modified or unmodified
3. Include the Font as a component in another downloadable product or service
4. Remove copyright notices from the Font

THE FONT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY.

For any licensing questions or to request special permissions, please contact the developers.

## Contributing

Found a bug or have a suggestion? Feel free to open an issue or contribute to improvements.

## Version History

- **v1.0** - Initial release with 1,025+ icons in Regular and Thin styles

## Support

For questions, issues, or feedback regarding RTM Icons Free:

1. Check the interactive gallery by opening `index.html`
2. Review this README for usage instructions
3. Inspect the CSS files in the `css/` directory for detailed class definitions

## Acknowledgments

RTM Icons Free is created and maintained for the web development community. Thank you for using our icon library!

---

**RTM Icons Free** - Professional Icon Font Library for Web Developers

Last Updated: 2026
