# Guide to Adding Images, Maps, and Diagrams to Your Volcano Book

## Setting Up Your Images Folder

### Recommended Structure

```
volcano/
├── README.md
├── chapters/
│   ├── 01-introduction.md
│   ├── 02a-volcano-terminology.md
│   └── ...
├── images/
│   ├── maps/
│   │   ├── ring-of-fire.jpg
│   │   ├── plate-boundaries.png
│   │   ├── subduction-zone-diagram.png
│   │   └── volcano-distribution-map.jpg
│   ├── diagrams/
│   │   ├── volcano-anatomy.png
│   │   ├── stratovolcano-cross-section.jpg
│   │   ├── shield-volcano-diagram.png
│   │   ├── eruption-types.png
│   │   └── vei-scale-visual.jpg
│   ├── volcanoes/
│   │   ├── mt-fuji.jpg
│   │   ├── kilauea-lava.jpg
│   │   ├── mount-st-helens-1980.jpg
│   │   ├── etna-erupting.jpg
│   │   └── nyiragongo-lava-lake.jpg
│   └── features/
│       ├── pyroclastic-flow.jpg
│       ├── aa-lava.jpg
│       ├── pahoehoe-lava.jpg
│       └── caldera-formation.png
└── IMAGES-GUIDE.md
```

---

## How to Embed Images in Markdown

### Basic Syntax

```markdown
![Alt text description](path/to/image.jpg)
```

### With Caption

```markdown
![Mount Fuji covered in snow](../images/volcanoes/mt-fuji.jpg)
*Figure 1.1: Mount Fuji's perfect symmetry reflected in Lake Kawaguchi*
```

### Controlling Size (HTML in Markdown)

```markdown
<img src="../images/volcanoes/etna-erupting.jpg" alt="Mount Etna erupting at night" width="600">
*Figure 5.2: Mount Etna's lava fountains illuminate the Sicilian night sky*
```

### Side-by-Side Images

```markdown
<div style="display: flex; gap: 10px;">
  <img src="../images/lava/aa-lava.jpg" alt="Aa lava" width="300">
  <img src="../images/lava/pahoehoe-lava.jpg" alt="Pahoehoe lava" width="300">
</div>
*Figure 2.5: Aa lava (left) vs. Pahoehoe lava (right)*
```

---

## Where to Find Images

### Free, Legal Sources for Volcano Images

#### 1. **USGS (United States Geological Survey)**
- **URL**: https://www.usgs.gov/media/images
- **License**: Public domain (US government work)
- **Best for**: US volcanoes, scientific diagrams, monitoring data
- **Examples**: Mount St. Helens, Kilauea, Yellowstone

#### 2. **NASA Earth Observatory**
- **URL**: https://earthobservatory.nasa.gov/
- **License**: Generally public domain (check each image)
- **Best for**: Satellite views, global volcanic events
- **Examples**: Eruption plumes from space, volcanic islands

#### 3. **Smithsonian Global Volcanism Program**
- **URL**: https://volcano.si.edu/
- **License**: Varies (many public domain or with permission)
- **Best for**: Specific volcano photos, eruption histories

#### 4. **Wikimedia Commons**
- **URL**: https://commons.wikimedia.org/
- **License**: Various Creative Commons licenses
- **Best for**: Wide variety of volcano photos worldwide
- **Search**: "volcano", "volcanic eruption", "lava flow"
- **IMPORTANT**: Check license for each image. Look for:
  - CC0 (public domain)
  - CC-BY (requires attribution)
  - CC-BY-SA (requires attribution and share-alike)

#### 5. **Unsplash**
- **URL**: https://unsplash.com/
- **License**: Free to use (Unsplash License)
- **Best for**: High-quality artistic volcano photos
- **Search**: "volcano", "lava", "volcanic landscape"

#### 6. **Pexels**
- **URL**: https://www.pexels.com/
- **License**: Free to use
- **Best for**: General volcano imagery

#### 7. **NOAA Photo Library**
- **URL**: https://www.photolib.noaa.gov/
- **License**: Public domain
- **Best for**: Ocean/marine volcanoes, atmospheric effects

---

## Creating Your Own Diagrams

### Tools for Making Diagrams

#### Free Options:

1. **Excalidraw** (https://excalidraw.com/)
   - Hand-drawn style diagrams
   - Perfect for volcano cross-sections, plate tectonics

2. **Draw.io / diagrams.net** (https://app.diagrams.net/)
   - Professional diagrams
   - Good for flowcharts, labeled diagrams

3. **Canva** (Free tier) (https://www.canva.com/)
   - Templates and graphics
   - Good for infographics, labeled maps

4. **GIMP** (Free Photoshop alternative)
   - Image editing
   - Add labels to photos

5. **Inkscape** (Free vector graphics)
   - Professional diagrams
   - Export as PNG or SVG

---

## Examples of Images to Include

### For Chapter 2A (Terminology)

```markdown
# Volcano Anatomy

![Diagram of volcano anatomy](../images/diagrams/volcano-anatomy.png)
*Figure 2.1: The anatomy of a stratovolcano showing magma chamber, conduit, vent, crater, and flank vents*

## Types of Volcanoes

### Shield Volcano

<img src="../images/diagrams/shield-volcano.png" alt="Shield volcano cross-section" width="500">
*Figure 2.2: Shield volcano cross-section showing broad, gentle slopes built from fluid lava flows*

**Real example**:
![Mauna Loa from aerial view](../images/volcanoes/mauna-loa-aerial.jpg)
*Figure 2.3: Mauna Loa, Hawaii—the world's largest shield volcano*

### Stratovolcano

<img src="../images/diagrams/stratovolcano.png" alt="Stratovolcano cross-section" width="500">
*Figure 2.4: Stratovolcano showing alternating layers of lava and ash*

**Real example**:
![Mount Fuji](../images/volcanoes/mt-fuji.jpg)
*Figure 2.5: Mount Fuji—a classic stratovolcano*
```

### For Chapter 4 (Global Overview)

```markdown
## The Ring of Fire

![Map of the Pacific Ring of Fire](../images/maps/ring-of-fire-map.jpg)
*Figure 4.1: The Pacific Ring of Fire accounts for 75% of the world's active volcanoes*

## VEI Scale Visual

![VEI Scale diagram](../images/diagrams/vei-scale.png)
*Figure 4.2: The Volcanic Explosivity Index (VEI) from 0 to 8*

## Plate Boundaries

![Tectonic plate boundaries map](../images/maps/plate-boundaries.jpg)
*Figure 4.3: Major tectonic plates and volcanic zones*
```

### For Regional Chapters

```markdown
# Chapter 5: Asia-Pacific

![Map of Asia-Pacific volcanoes](../images/maps/asia-pacific-volcanoes.jpg)
*Map 5.1: Active volcanoes of the Asia-Pacific region*

## Mount Fuji

![Mount Fuji with cherry blossoms](../images/volcanoes/fuji-cherry-blossoms.jpg)
*Photo 5.1: Mount Fuji framed by cherry blossoms*

![Mount Fuji from space](../images/volcanoes/fuji-satellite.jpg)
*Photo 5.2: Satellite view showing Fuji's perfect symmetry*
```

---

## Attribution Examples

### For Creative Commons Images

```markdown
![Krakatoa erupting](../images/volcanoes/krakatoa-anak.jpg)
*Anak Krakatau erupting, 2018. Photo by [Photographer Name](link) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)*
```

### For Public Domain

```markdown
![Mount St. Helens eruption](../images/volcanoes/st-helens-1980.jpg)
*Mount St. Helens eruption, May 18, 1980. USGS photo (public domain)*
```

---

## Essential Images for Your Book

### Priority Maps to Include:

1. **Ring of Fire Map** - Shows global distribution of volcanoes
2. **Tectonic Plates Map** - Shows plate boundaries
3. **Subduction Zone Diagram** - Cross-section showing how subduction creates volcanoes
4. **Divergent Boundary Diagram** - Shows rifting and volcanism
5. **Hot Spot Diagram** - Shows mantle plume and volcanic chain formation
6. **World Volcano Distribution** - Dots on map showing all active volcanoes

### Priority Diagrams:

1. **Volcano Types Comparison** - Shield, stratovolcano, cinder cone side-by-side
2. **Volcano Anatomy** - Labeled cross-section
3. **Eruption Types** - Hawaiian, Strombolian, Vulcanian, Plinian
4. **VEI Scale Visual** - Size comparison
5. **Lava Types** - Basalt vs. andesite vs. rhyolite
6. **Pyroclastic Flow Diagram** - How they form and move
7. **Lahar Formation** - How mudflows develop
8. **Caldera Formation Sequence** - Step-by-step collapse

### Priority Photos:

1. **Mount Fuji** - Perfect stratovolcano example
2. **Kilauea lava flow** - Active lava example
3. **Stromboli erupting** - Strombolian eruption
4. **Nyiragongo lava lake** - Largest lava lake
5. **Mount St. Helens before/after** - Lateral blast example
6. **Crater Lake** - Caldera example
7. **Pahoehoe and Aa lava** - Both lava types
8. **Pompeii casts** - Historical impact
9. **Mount Etna at night** - Lava fountains
10. **Erta Ale lava lake** - Persistent lava lake

---

## Quick Start: Adding Your First Images

### Step 1: Create Images Folder

```bash
cd /Users/tomrooney/src/volcano
mkdir -p images/maps images/diagrams images/volcanoes images/features
```

### Step 2: Download a Free Image

Go to Unsplash or Wikimedia Commons and download a volcano image.

### Step 3: Add to Your Book

In your markdown file:

```markdown
![Mount Fuji](../images/volcanoes/mt-fuji.jpg)
*Mount Fuji, Japan's most iconic volcano*
```

### Step 4: Preview

Open your markdown file in a markdown previewer or push to GitHub to see the rendered image.

---

## Tips for Great Image Integration

1. **Always include alt text** - Describes the image for accessibility
2. **Add captions** - Explain what the reader is looking at
3. **Number figures** - "Figure 2.1", "Map 5.3" for easy reference
4. **Place images near relevant text** - Don't make readers hunt for the image
5. **Use consistent sizing** - Keeps your book looking professional
6. **Optimize image size** - Use JPG for photos (smaller file size), PNG for diagrams
7. **Keep images under 1-2 MB each** - Faster loading

---

## Creating Maps with Free Tools

### Option 1: Google My Maps
1. Go to https://www.google.com/maps/d/
2. Create custom map
3. Add markers for volcanoes
4. Take screenshot
5. Add to your book

### Option 2: QGIS (Free GIS Software)
1. Download from https://qgis.org/
2. Add base map
3. Add volcano data points
4. Export as image

### Option 3: Manually Annotate
1. Find public domain world map
2. Open in GIMP or similar
3. Add dots/labels for volcanoes
4. Export as JPG/PNG

---

## Legal and Ethical Considerations

1. **Always check the license** before using an image
2. **Provide attribution** when required
3. **Don't use copyrighted images** without permission
4. **Public domain is safest** (USGS, NASA, old photos)
5. **Creative Commons** requires following license terms
6. **When in doubt**, create your own diagram or use text descriptions

---

**Ready to make your book visual!** Start with a few key diagrams (volcano anatomy, Ring of Fire map) and build from there.
