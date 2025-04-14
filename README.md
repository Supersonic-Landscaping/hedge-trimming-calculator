# 📄 Hedge Trimming Service Calculator – Supersonic Landscaping

This **Hedge Trimming Service Calculator** by [Supersonic Landscaping](https://www.supersoniclandscaping.com) is a lightweight, embeddable tool designed to help landscaping businesses provide their visitors with quick, accurate hedge trimming estimates.

It allows users to input the hedge’s **length**, **height**, and **width**. The calculator dynamically adjusts the estimated labor cost based on hedge size, height difficulty, and thickness, while factoring in equipment usage when needed.

Designed for **easy embedding** into any landscaping service page, it includes **SEO-friendly schema markup**, **subtle brand attribution**, and a **responsive, mobile-friendly design**.

---

# 🚀 Features

**Instant Estimates**  
Calculates an estimated hedge trimming cost based on the hedge’s dimensions.

**Height-Based Pricing**  
Applies different per-foot rates depending on hedge height, automatically adding an equipment surcharge for very tall hedges.

**Width Adjustment**  
Charges a small additional fee for hedges wider than 3 feet to account for extra labor and cutting volume.

**Custom Pricing**  
Accepts customizable settings like base fee and equipment surcharge using `data-` attributes.

**SEO Optimized**  
Includes structured data (schema.org/WebApplication) to help search engines better index and associate your brand.

**Plug-and-Play**  
Fully mobile-friendly, lightweight, and simple to drop into any service page without coding experience.

**Brand Attribution**  
Subtly credits "Tool by [Supersonic Landscaping](https://www.supersoniclandscaping.com)" to boost organic branding and backlinks.

---

# 🔧 How to Use

1. **Include the CSS and JavaScript files** on your page:

```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/Supersonic-Landscaping/hedge-trimming-calculator@v0.0.1/style.css">
<script src="https://cdn.jsdelivr.net/gh/Supersonic-Landscaping/hedge-trimming-calculator@v0.0.1/hedge-trimming.js" crossorigin="anonymous"></script>
```

2. **Add the Widget HTML** where you want the calculator to appear:

```html
<div class="supersonic-hedgetrimming-calculator" 
     data-title="Hedge Trimming Calculator" 
     data-base-fee="100" 
     data-equipment-surcharge="50">
</div>
```

### Customizable Attributes:
- **`data-title` (optional):** Set a custom title for the calculator.
- **`data-base-fee` (optional):** Set a minimum charge for the service (default is $100).
- **`data-equipment-surcharge` (optional):** Add an extra charge for very tall hedges requiring special equipment (default is $50).

3. **That's it!**  
The widget automatically initializes on page load — no manual setup required.

---

# 🌱 Important Notes

- **Disposal fees are not included** in the estimate. Clients should be advised that debris haul-away may incur additional charges.
- **Height-Based Pricing:**  
  - Up to 6 ft tall = standard rate.  
  - 6–10 ft tall = higher rate.  
  - Over 10 ft tall = higher rate + equipment surcharge applied.
- **Width Adjustment:**  
  For every extra foot above 3 ft in width, a 10% labor cost increase is applied.

---

# 🎯 Learn More

Looking for custom website tools or SEO-friendly landscaping calculators?  
Visit [Supersonic Landscaping](https://www.supersoniclandscaping.com) — specialists in web design and marketing for landscaping businesses across North America!
