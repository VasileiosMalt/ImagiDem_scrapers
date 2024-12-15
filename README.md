# 🖼️ ImagiDem Scrapers

A collection of web scraping tools developed for the ImagiDem Project (Images of Democracy), exploring visual representations of democracy and protest movements across European digital archives.

## 📚 Overview

These scrapers facilitate the systematic collection of historical images and metadata from various European digital archives, supporting research on collective memory and visual democracy.
Based on the code files provided, here is the complete list of scrapers:

## 🛠️ Available Scrapers
### 🇵🇹 Portuguese Archives
- **Digitarq Scraper**
  - Targets: Portuguese National Archives
  - Features: Keyword search, high-resolution image downloads, metadata extraction
  - Collections focus: Historical protests, political movements, democratic transitions

- **Centro de Documentação 25 de Abril**
  - Targets: April 25 Documentation Center
  - Features: Item page scraping, bulk image downloads, custom folder organization
  - Collections focus: Carnation Revolution, democratic transition period

 **Casa Comum**
- Features:
  - Search term customization
  - Document link extraction
  - Image URL collection
  - Organized folder structure for downloads

### 🇫🇷 French Archives
- **Musée de l'Histoire Vivante**
  - Features: Exhibition-based scraping, automated CSV generation
  - Collections focus: Labor movements, social protests, popular front

- **BnF Gallica Scraper**
- Targets: Bibliothèque nationale de France's digital library
- Features:
  - Search with specific terms
  - 50 images per page pagination
  - High-resolution image downloads
  - CSV generation with image URLs

### 🇫🇮 Finnish Archives
- **Museovirasto (Finnish Heritage Agency)**
  - Features: Date-range filtering, high-resolution downloads
  - Collections focus: Social movements, protests, civil society

- **Arjenhistoria**

- **HelsinkiKuvia (Helsinki City Museum)**
  - Features: Custom date ranges, metadata extraction
  - Collections focus: Urban social movements, local democracy
 
### GE German Archives
- **Boell Sammlungen Scraper**
- Targets: Heinrich Böll Foundation's digital collections
- Features:
  - Session ID authentication
  - Customizable page scraping
  - Image URL extraction
  - Systematic download organization

- **Bundesarchiv Scraper**
- Features:
  - Year-range search capability
  - Multiple page scraping
  - High-resolution image downloads
  - CSV generation with metadata

## 💻 Technical Requirements

- Python 3.x
- Key Dependencies:
  ```python
  requests
  beautifulsoup4
  pandas
  selenium
  ```

## 🔧 Usage Instructions

1. Install required dependencies:
```bash
pip install -r requirements.txt
```

2. Select appropriate scraper for target archive
3. Configure search parameters:
   - Keywords
   - Date ranges
   - Number of pages
4. Execute scraper:
```python
python scraper_name.py
```

## 📁 Output Structure

```
images_from_the_past/
├── PORTUGAL/
│   ├── search_term_1/
│   └── search_term_2/
├── GERMANY/
├── FRANCE/
│   └── exhibition_name/
└── FINLAND/
    ├── museovirasto/
    └── helsinkikuvia/
```

Here is a comprehensive table of all archives supported by the ImagiDem scrapers based on the code:

| Country | Archive | Content Focus |
|---------|---------|---------------|
| Portugal | Digitarq | National Archives & Historical Photos |
| Portugal | CD25A | Democratic Revolution & Protest Murals |
| Portugal | Casa Comum | Portuguese-speaking Historical Archives |
| France | Musée de l'Histoire Vivante | Social Movements & Popular Front |
| France | BnF Gallica | National Library Collections |
| Finland | Museovirasto | Cultural Heritage & Social Movements |
| Finland | HelsinkiKuvia | Urban History & Local Democracy |
| Finland | Arjenhistoria | Everyday Life & Labor History |
| Germany | Bundesarchiv | Federal Archives, Historical Photos |
| Germany | Boell Sammlungen | Heinrich Böll Foundation's Digital Collections |

## ⚠️ Important Note

These scrapers are developed strictly for academic research within the ImagiDem Project framework. Users must:
- Comply with each archive's terms of service
- Respect copyright and fair use policies
- Use collected data exclusively for research purposes
- Properly attribute sources in academic outputs

For more information about the ImagiDem Project and our research on visual democracy, visit the [ImagiDem Project](https://csd.fi/imagidem/) website.
