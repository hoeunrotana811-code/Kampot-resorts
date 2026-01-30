#  Icon Reference Guide - Kampot Resorts

## ការប្រើប្រាស់ Font Awesome Icons

គេហទំព័រនេះប្រើ **Font Awesome 6.5.1** សម្រាប់ icons ទាំងអស់។

---

##  Icons បច្ចុប្បន្នកំពុងប្រើ (Current Icons)

### 1. Header & Navigation
```html
<!-- Logo Icon -->
<i class="fas fa-umbrella-beach"></i>
```
- **Class**: `fas fa-umbrella-beach`
- **ប្រើនៅ**: Logo section
- **ពណ៌**: ស (white)

---

### 2. Resort Locations
```html
<!-- Location Pin Icon -->
<i class="fas fa-map-marker-alt"></i>
```
- **Class**: `fas fa-map-marker-alt`
- **ប្រើនៅ**: Resort location display
- **ពណ៌**: #667eea (primary color)

---

### 3. Rating Stars
```html
<!-- Star Icon -->
<i class="fas fa-star"></i>
```
- **Class**: `fas fa-star`
- **ប្រើនៅ**: Resort rating display
- **ពណ៌**: #ffd700 (gold)

---

### 4. Contact Icons

#### Email
```html
<i class="fas fa-envelope"></i>
```
- **Class**: `fas fa-envelope`
- **ប្រើនៅ**: Contact email section

#### Phone
```html
<i class="fas fa-phone"></i>
```
- **Class**: `fas fa-phone`
- **ប្រើនៅ**: Contact phone section

#### Location
```html
<i class="fas fa-map-marker-alt"></i>
```
- **Class**: `fas fa-map-marker-alt`
- **ប្រើនៅ**: Contact address section

---

##  Font Awesome Icons ផ្សេងទៀតដែលអាចប្រើបាន

### Resort & Hotel Icons
```html
<i class="fas fa-hotel"></i>              <!-- Hotel -->
<i class="fas fa-bed"></i>                <!-- Bed -->
<i class="fas fa-concierge-bell"></i>     <!-- Service Bell -->
<i class="fas fa-key"></i>                <!-- Room Key -->
<i class="fas fa-door-open"></i>          <!-- Door -->
```

### Amenities Icons
```html
<i class="fas fa-swimming-pool"></i>      <!-- Pool -->
<i class="fas fa-wifi"></i>               <!-- WiFi -->
<i class="fas fa-utensils"></i>           <!-- Restaurant -->
<i class="fas fa-spa"></i>                <!-- Spa -->
<i class="fas fa-dumbbell"></i>           <!-- Gym -->
<i class="fas fa-parking"></i>            <!-- Parking -->
<i class="fas fa-coffee"></i>             <!-- Coffee -->
<i class="fas fa-cocktail"></i>           <!-- Bar -->
<i class="fas fa-tv"></i>                 <!-- TV -->
<i class="fas fa-wind"></i>               <!-- Air Conditioning -->
```

### Location & Travel Icons
```html
<i class="fas fa-map-marked-alt"></i>     <!-- Map -->
<i class="fas fa-route"></i>              <!-- Route -->
<i class="fas fa-plane"></i>              <!-- Airport -->
<i class="fas fa-taxi"></i>               <!-- Taxi -->
<i class="fas fa-car"></i>                <!-- Car -->
<i class="fas fa-bicycle"></i>            <!-- Bike -->
```

### Beach & Nature Icons
```html
<i class="fas fa-umbrella-beach"></i>     <!-- Beach -->
<i class="fas fa-water"></i>              <!-- Water -->
<i class="fas fa-mountain"></i>           <!-- Mountain -->
<i class="fas fa-tree"></i>               <!-- Tree -->
<i class="fas fa-sun"></i>                <!-- Sun -->
<i class="fas fa-cloud-sun"></i>          <!-- Partly Cloudy -->
```

### Social & Contact Icons
```html
<i class="fab fa-facebook"></i>           <!-- Facebook -->
<i class="fab fa-instagram"></i>          <!-- Instagram -->
<i class="fab fa-twitter"></i>            <!-- Twitter -->
<i class="fab fa-whatsapp"></i>           <!-- WhatsApp -->
<i class="fab fa-telegram"></i>           <!-- Telegram -->
<i class="fas fa-share-alt"></i>          <!-- Share -->
```

### Action Icons
```html
<i class="fas fa-search"></i>             <!-- Search -->
<i class="fas fa-calendar-alt"></i>       <!-- Calendar -->
<i class="fas fa-user"></i>               <!-- User -->
<i class="fas fa-users"></i>              <!-- Group -->
<i class="fas fa-heart"></i>              <!-- Favorite -->
<i class="fas fa-bookmark"></i>           <!-- Bookmark -->
<i class="fas fa-shopping-cart"></i>      <!-- Cart -->
<i class="fas fa-credit-card"></i>        <!-- Payment -->
```

### UI Icons
```html
<i class="fas fa-check"></i>              <!-- Check -->
<i class="fas fa-times"></i>              <!-- Close -->
<i class="fas fa-chevron-right"></i>      <!-- Arrow Right -->
<i class="fas fa-chevron-left"></i>       <!-- Arrow Left -->
<i class="fas fa-chevron-down"></i>       <!-- Arrow Down -->
<i class="fas fa-chevron-up"></i>         <!-- Arrow Up -->
<i class="fas fa-bars"></i>               <!-- Menu -->
<i class="fas fa-ellipsis-v"></i>         <!-- More Options -->
```

---

## របៀបប្រើប្រាស់ (How to Use)

### Basic Usage
```html
<i class="fas fa-icon-name"></i>
```

### With Text
```html
<p>
    <i class="fas fa-map-marker-alt"></i>
    Kampot, Cambodia
</p>
```

### With Custom Styling
```html
<i class="fas fa-star" style="color: gold; font-size: 1.5rem;"></i>
```

### Multiple Icons
```html
<div>
    <i class="fas fa-wifi"></i>
    <i class="fas fa-parking"></i>
    <i class="fas fa-swimming-pool"></i>
</div>
```

---

## CSS Styling

### Icon Colors
```css
.icon-primary { color: #667eea; }
.icon-success { color: #28a745; }
.icon-danger { color: #dc3545; }
.icon-warning { color: #ffc107; }
.icon-gold { color: #ffd700; }
```

### Icon Sizes
```css
.icon-sm { font-size: 0.875rem; }
.icon-md { font-size: 1.25rem; }
.icon-lg { font-size: 1.75rem; }
.icon-xl { font-size: 2.5rem; }
```

### Icon Spacing
```css
.icon-mr-1 { margin-right: 0.25rem; }
.icon-mr-2 { margin-right: 0.5rem; }
.icon-ml-1 { margin-left: 0.25rem; }
.icon-ml-2 { margin-left: 0.5rem; }
```

---

## 🔗 Resources

- **Font Awesome Website**: https://fontawesome.com/
- **Icon Search**: https://fontawesome.com/icons
- **Documentation**: https://fontawesome.com/docs

---

##  ចំណាំសំខាន់ (Important Notes)

1. **CDN Link**: Icons load from Cloudflare CDN (ល្បឿនលឿន)
2. **Icon Classes**: 
   - `fas` = Font Awesome Solid
   - `far` = Font Awesome Regular  
   - `fab` = Font Awesome Brands
3. **Performance**: Font Awesome file size ~75KB (acceptable)
4. **Browser Support**: Works on all modern browsers

---

##  ការបន្ថែម Icon ថ្មី (Adding New Icons)

1. ស្វែងរក icon នៅ: https://fontawesome.com/icons
2. Copy class name (ឧ: `fas fa-swimming-pool`)
3. បន្ថែមក្នុង HTML: `<i class="fas fa-swimming-pool"></i>`
4. Add custom styling in CSS if needed

**ឧទាហរណ៍**:
```html
<!-- Before -->
<span class="feature-tag">Pool</span>

<!-- After -->
<span class="feature-tag">
    <i class="fas fa-swimming-pool"></i>
    Pool
</span>

