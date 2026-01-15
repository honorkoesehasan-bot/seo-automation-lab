# 🔬 SEO Automation Lab

**Statisches SEO-Labor für E-Commerce Automation Testing mit n8n**

---

## 📌 Was ist das?

Ein minimalistisches, statisches Website-Projekt auf GitHub Pages/Netlify zum Testen von:
- ✅ **Keyword-Recherche & Intent-Analyse**
- ✅ **Content-Strukturen** (H1-H6, FAQ, interne Links)
- ✅ **Technical SEO** (robots.txt, sitemap.xml, Schema.org)
- ✅ **n8n-Workflows** (JSON/XML Daten für Automation)

---

## 🗂️ Projekt-Struktur

```
seo-automation-lab/
├── index.html              # Hauptseite
├── style.css               # Basis-Styling
├── robots.txt              # Crawler-Anweisungen
├── sitemap.xml             # XML-Sitemap für Suchmaschinen
├── pages/                  # Unterseiten
│   ├── keyword-lab.html    # Keyword-Recherche Basics
│   ├── content-lab.html    # Content-Struktur Beispiele
│   └── technical-lab.html  # Technical SEO Checkliste
└── data/                   # JSON-Daten für n8n
    ├── seed-keywords.json  # 20 Seed-Keywords mit Prioritäten
    └── pages.json          # Metadaten aller Seiten
```

---

## 🚀 Deployment

### Option 1: Netlify (Empfohlen)
1. Repo auf [Netlify](https://netlify.com) verbinden
2. Build Settings: **LEER lassen** (statische Seite)
3. Publish directory: `/` (Root)
4. Deploy → URL notieren

### Option 2: GitHub Pages
1. Settings → Pages → Source: **main branch**
2. Warten auf Deployment
3. URL: `https://<username>.github.io/seo-automation-lab/`

---

## 🔧 URLs anpassen

Nach dem Deployment:
1. In `index.html` alle `YOUR_GITHUB_PAGES_URL_HERE` ersetzen
2. In `sitemap.xml` URLs aktualisieren
3. Commit & Push

---

## 🤖 n8n-Integration

**Beispiel-Workflow:**
1. HTTP Request → `https://deine-url.netlify.app/data/pages.json`
2. JSON Parser → Neue Seiten erkennen
3. Notion/Airtable → Content-Ideen speichern
4. ChatGPT/Claude → Auto-Briefing generieren

**Verfügbare Endpunkte:**
- `/data/seed-keywords.json` - Keyword-Liste mit Prioritäten
- `/data/pages.json` - Alle Seiten-Metadaten
- `/sitemap.xml` - Standard XML-Sitemap

---

## 📚 Nächste Schritte

1. ✅ **Deployment abschließen** (Netlify/GitHub Pages)
2. ✅ **URLs in allen Dateien anpassen**
3. 🔍 **Google Search Console** - Property hinzufügen, Sitemap einreichen
4. 🤖 **n8n-Workflow bauen** - Daily Check auf neue Inhalte
5. 📊 **Erste Test-Inhalte** - Neue Seiten in `/pages/` hinzufügen

---

## 🎯 Lernziele

- **SEO-Basics verstehen** (Keywords, On-Page, Technical)
- **Strukturierte Daten** für Suchmaschinen aufbereiten
- **JSON/XML APIs** für Automation-Workflows nutzen
- **n8n-Workflows** mit echten Daten testen

---

**Built for Learning | Open Source | No Dependencies**
