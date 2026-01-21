# Supermarket Specials Finder — Mobile App Concept

## App Concept Overview
A modern, clean mobile app that helps consumers find the best supermarket food specials for a product they enter or scan. Users type or scan a product (e.g., “Anchor butter 500g” or “chicken breast”) and instantly see which nearby supermarkets have the best current specials, sorted from cheapest to most expensive. The interface emphasizes trust, clarity, and speed so users can identify the best option in under 10 seconds.

**Core value proposition:** transparent, location-aware price comparison with clear promotions and price-per-unit insights, delivered in a calm, premium UI.

## Key User Flows
1. **Search & compare**
   - Open app → tap the single prominent search bar → type or scan product → autocomplete suggests products → results list sorted by cheapest price.

2. **Location-aware results**
   - On first use, user grants location → nearby stores prioritized → optional manual override (city, suburb, or postcode) for travelers or privacy-conscious users.

3. **Deal evaluation**
   - User taps a result card → detail view shows discount breakdown, multi-buy rules, promo expiry, and price-per-unit comparison for fair value.

4. **Save & alert**
   - User saves a product → chooses alert preferences → receives push alerts when item goes on special at nearby stores.

5. **List ↔ map comparison**
   - User toggles list and map view to compare deals by proximity or travel time.

## Core Screens & Layout Descriptions
### 1) Home / Search
- **Layout:** Single prominent search bar centered near top with optional barcode scan icon.
- **Elements:**
  - Autocomplete suggestions list with product thumbnails and category tags.
  - Recent searches and saved items below (lightweight, minimal).
- **Design:** Generous white space, soft shadows, and clear focus on the search bar.

### 2) Results List (Cheapest First)
- **Layout:** Stacked rounded cards with subtle elevation and price prominence.
- **Card content:**
  - Store logo + distance.
  - Product name, size, and price-per-unit.
  - Big bold price, with “On Special” and “Best Value” badges.
  - Promotion details (multi-buy, expiry date) shown clearly.
- **Interactions:**
  - Tap card for detail view.
  - Toggle list/map in top right.

### 3) Map View
- **Layout:** Map with store pins; bottom sheet with top 2–3 cheapest options.
- **Interactions:**
  - Tap a pin to highlight and bring its card to the top of the sheet.
  - Quick filter for “Open now” or “Within X km.”

### 4) Product Detail
- **Layout:** Focused card with price hierarchy and transparent promotion details.
- **Elements:**
  - Price breakdown: regular price → discounted price → savings.
  - Price-per-unit comparison chart (simple, horizontal bar).
  - Promotion expiry date and terms.
  - Save/alert toggle.

### 5) Saved Items & Alerts
- **Layout:** List of saved products with current best price and store.
- **Elements:**
  - Alert settings per item (price threshold, nearby stores).
  - Clear status when no specials are active.

## Visual Style & UI Direction
### Style Principles
- Clean, modern, minimal interface.
- Trust-focused with data transparency.
- No clutter or ad-heavy patterns.
- Soft elevation, rounded cards, restrained motion.

### Color Palette
- **Primary (Teal):** #1FB6A6 — actions, highlights.
- **Secondary (Deep Navy):** #1F2A37 — headings and structure.
- **Accent (Soft Amber):** #F59E0B — “On Special” badge, price emphasis.
- **Success/Savings:** #10B981 — savings indicators.

**Backgrounds**
- Primary: #F9FAFB
- Card: #FFFFFF
- Secondary surface: #F3F4F6

**Text**
- Primary: #111827
- Secondary: #4B5563
- Muted: #9CA3AF

**Dividers/Borders:** #E5E7EB

### Typography
- **Font:** Inter (Regular, Medium, SemiBold, Bold).
- **Prices:** Bold, large, dominant.
- **Headings:** SemiBold.
- **Body:** Regular with generous line spacing for readability.

### Dark Mode
- **Background:** #0F172A
- **Cards:** #1E293B
- **Primary text:** #F8FAFC
- **Secondary text:** #CBD5E1
- **Primary accent:** Teal with slightly reduced saturation.

## MVP Feature Prioritisation
### Must Have (MVP)
- Product search with autocomplete.
- Price comparison across multiple supermarket chains.
- Location-based store prioritization with manual override.
- Clear specials display (discounts, multi-buy, expiry dates).
- Price-per-unit comparison.

### Should Have
- Barcode scanning.
- Save favourite products.
- Alerts when items go on special.
- List and map view toggle.

### Nice to Have
- Stock availability indicators.
- Personalized deal recommendations.
- Basket price comparison across multiple items.
- In-app loyalty card integration.
