# CyberSecurity Educational Website

Կրթական վեբ կայք կիբերանվտանգության մասին՝ հայերեն։

## Տեխնոլոգիաներ

- HTML5
- CSS3
- JavaScript (Vanilla)
- SVG ներկառուցված լոգո
- Matrix անիմացիա canvas-ով

## Ֆայլերի կառուցվածքը

```
├── index.html       # Գլխավոր HTML ֆայլ (SVG լոգո ներսում)
├── vercel.json     # Vercel կոնֆիգուրացիա
└── README.md       # Այս ֆայլը
```

## Vercel-ում Deploy անելու քայլեր

### Տարբերակ 1: Vercel CLI-ով

1. Տեղադրեք Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Մուտք գործեք ձեր Vercel հաշիվ:
   ```bash
   vercel login
   ```

3. Deploy անեք պրոյեկտը:
   ```bash
   vercel
   ```

4. Production deploy-ի համար:
   ```bash
   vercel --prod
   ```

### Տարբերակ 2: Vercel Dashboard-ով

1. Գնացեք [vercel.com](https://vercel.com) և մուտք գործեք
2. Սեղմեք "Add New..." → "Project"
3. Import անեք ձեր GitHub/GitLab repository-ն
4. Vercel ինքնաշխատ կճանաչի static site-ը
5. Սեղմեք "Deploy"

### Տարբերակ 3: Git Integration-ով

1. Ստեղծեք Git repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. Push անեք GitHub-ին
3. Կապեք Vercel-ի հետ
4. Ավտոմատ deployment յուրաքանչյուր push-ի համար

## Տեղական զարգացում

Պրոյեկտը ունի պատրաստի workflow Replit-ում։ Եթե ցանկանում եք տեղական սերվերով աշխատել:

```bash
python -m http.server 5000
```

Այնուհետև բացեք browser-ում: `http://localhost:5000`

## Հատկություններ

✅ Matrix-ի նման անիմացիա  
✅ Responsive դիզայն  
✅ Collapsible բաժիններ  
✅ Smooth scrolling  
✅ "Վերև" կոճակ  
✅ Հայերեն բովանդակություն  
✅ SVG ներկառուցված լոգո (չի կախված արտաքին ֆայլերից)  
✅ Պաշտպանված right-click-ից և inspect-ից  
✅ **PWA աջակցություն բոլոր սարքերի համար:**
  - iPhone/iPad (Apple Touch Icons)
  - Android (Web App Manifest)
  - Windows (Microsoft Tiles)
  - Բոլոր բրաուզերներ (SVG Favicon)
  - "Add to Home Screen" հնարավորություն

## Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers

## License

Educational purposes only.

---

© CyberSecurity Educational Website
