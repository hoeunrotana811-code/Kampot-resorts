# Kampot Resorts Website - រចនាសម្ព័ន្ធឯកសារ

## រចនាសម្ព័ន្ធទាំងស្រុង (File Structure)

```
kampot-resorts/
│
├── index.html              # ឯកសារ HTML មេ (Main HTML file)
├── style.css               # ឯកសារ CSS មេ (Main CSS with imports)
│
├── css/                    # ថត CSS components
│   ├── fonts.css           # ផ្នែក Font loading
│   ├── reset.css           # ផ្នែក Global reset & base styles
│   ├── header.css          # ផ្នែក Header & Navigation
│   ├── hero.css            # ផ្នែក Hero section
│   ├── search.css          # ផ្នែក Search box
│   ├── resorts.css         # ផ្នែក Resort cards
│   ├── deals.css           # ផ្នែក Deals section
│   ├── contact.css         # ផ្នែក Contact section
│   ├── footer.css          # ផ្នែក Footer
│   └── responsive.css      # ផ្នែក Responsive design
│
└── fonts/                  # ថត Fonts (if needed)
    ├── Flura-Regular.woff2
    └── Flura-Regular.woff
```

## ពិពណ៌នាឯកសារនីមួយៗ (File Descriptions)

### 1. **index.html** - ឯកសារ HTML មេ
- មានរចនាសម្ព័ន្ធទាំងអស់របស់គេហទំព័រ
- បែងចែកជា 7 ផ្នែកធំៗ

### 2. **style.css** - ឯកសារ CSS មេ
- ប្រើ `@import` ដើម្បីទាញយក CSS components ទាំងអស់
- ងាយស្រួលក្នុងការគ្រប់គ្រង

### 3. **css/fonts.css** - ផ្នែក Font
- ផ្ទុក custom fonts (Flura)

### 4. **css/reset.css** - ផ្នែក Reset
- Global reset styles
- Base styles សម្រាប់ body, container
- Section spacing

### 5. **css/header.css** - ផ្នែក Header
- Navigation bar
- Logo
- Menu links

### 6. **css/hero.css** - ផ្នែក Hero
- Hero section មានរូបភាពផ្ទៃខាងក្រោយ
- Title និង subtitle

### 7. **css/search.css** - ផ្នែក Search
- Search box styling
- Input fields
- Search button

### 8. **css/resorts.css** - ផ្នែក Resorts
- Resort cards layout
- Images, info, features
- Pricing និង ratings

### 9. **css/deals.css** - ផ្នែក Deals
- Special deals cards
- Discount badges

### 10. **css/contact.css** - ផ្នែក Contact
- Contact form
- Input fields
- Contact information

### 11. **css/footer.css** - ផ្នែក Footer
- Footer styling

### 12. **css/responsive.css** - ផ្នែក Responsive
- Mobile responsive styles
- Media queries



## របៀបប្រើប្រាស់ (How to Use)

1. ទាញយកឯកសារទាំងអស់
2. រក្សារចនាសម្ព័ន្ធថតដូចខាងលើ
3. បើក `index.html` ក្នុង browser
4. ប្រសិនចង់កែ styling មួយផ្នែក ចូលទៅកែក្នុង CSS file ដែលត្រូវការ

## ចំណាំសំខាន់ (Important Notes)

- ឯកសារ `style.css` មេប្រើ `@import` ដើម្បីទាញយក CSS ផ្សេងៗ
- រចនាសម្ព័ន្ធថត `css/` ត្រូវតែស្ថិតក្នុងថតដូចគ្នាជាមួយ `style.css`
- ប្រសិនមាន custom fonts ត្រូវដាក់ក្នុងថត `fonts/`
