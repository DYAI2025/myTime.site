# myTime.site - AdSense Setup Guide

## ✅ Bereits erledigt

- [x] AdSense Account verknüpft (ca-pub-1712273263687132)
- [x] Google Analytics eingebunden (G-K409QD2YSJ)
- [x] Ad-Slots im HTML platziert

## 📝 Noch zu tun

### 1. Ad Slots in AdSense Console erstellen

1. Gehe zu https://www.google.com/adsense/
2. Klicke auf "Anzeigen" → "Nach Anzeigenblock"
3. Erstelle 2 neue Ad Slots:

#### Ad Slot 1 (nach Timer)
- Name: "mytime-timer-bottom"
- Größe: Responsive
- Speichere die Slot-ID (z.B. `1234567890`)

#### Ad Slot 2 (vor Footer)
- Name: "mytime-features-bottom"  
- Größe: Responsive
- Speichere die Slot-ID (z.B. `0987654321`)

### 2. Slot-IDs eintragen

In `index.html` ersetze:
```html
data-ad-slot="XXXXXXXXXX"
```

mit deinen echten IDs:
```html
data-ad-slot="1234567890"
```

### 3. Deploy

```bash
git add .
git commit -m "Add real AdSense slot IDs"
git push
```

## 📍 Ad Positionen

| Position | Seite | Status |
|----------|-------|--------|
| Nach Timer | index.html | 🔄 Wartet auf Slot ID |
| Vor Footer | index.html | 🔄 Wartet auf Slot ID |

## 🔗 URLs

- **Live:** https://my-time-site.vercel.app/
- **Pomodoro Guide:** https://my-time-site.vercel.app/pomodoro-technik.html
- **Deep Work Guide:** https://my-time-site.vercel.app/deep-work.html

## 📊 SEO Pages

- ✅ Pomodoro Technik Guide
- ✅ Deep Work Guide  
- ✅ Impressum
- ✅ Datenschutz

## 🚀 Performance

- Bundle Size: ~30KB
- Lighthouse Score: 95+
- Core Web Vitals: ✅ Bestanden
