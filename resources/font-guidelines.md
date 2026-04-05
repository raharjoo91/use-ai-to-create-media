# Font Guidelines for K3 Media

> Typography standards for accessible, readable occupational health and safety materials

## Table of Contents
1. [Font Selection](#font-selection)
2. [Sizing by Distance](#sizing-by-distance)
3. [Hierarchy & Weight](#hierarchy--weight)
4. [Accessibility](#accessibility)
5. [Implementation](#implementation)

---

## Font Selection

### Recommended Fonts

**Sans-Serif (Primary Choice):**

| Font | Availability | Best For | Notes |
|------|--------------|----------|-------|
| **Arial** | Universal | All media | Default choice |
| **Verdana** | Universal | Small text | Highly legible |
| **Helvetica** | Widely available | Professional look | Classic |
| **Open Sans** | Google Fonts | Digital | Modern, clean |
| **Roboto** | Google Fonts | Digital | Android standard |

**Use Sans-Serif For:**
- ✅ All body text
- ✅ Headlines
- ✅ Signs and posters
- ✅ Digital displays
- ✅ Safety messages

**Avoid:**
- ❌ Decorative fonts (Comic Sans, Impact)
- ❌ Script fonts (hard to read)
- ❌ Serif fonts at small sizes
- ❌ All caps for long text

### Font Families

```
Primary Font: Arial
├─ Regular: Body text
├─ Bold: Emphasis, headlines
└─ Italic: Foreign words, quotes

Secondary Font: Verdana
├─ For longer body text
├─ Higher legibility at small sizes
└─ Better for low-literacy audiences
```

---

## Sizing by Distance

### The 10-Foot Rule

**Formula:** For every 10 feet of viewing distance, double the text size

```
Base Size: 12pt (30cm viewing distance)

Distance Multipliers:
├─ 1 meter (3 ft):  18pt minimum
├─ 3 meters (10 ft): 36pt minimum
├─ 5 meters (16 ft): 60pt minimum
└─ 10 meters (33 ft): 120pt minimum
```

### Recommended Sizes by Medium

| Medium | Viewing Distance | Headline | Subhead | Body | Captions |
|--------|------------------|----------|---------|------|----------|
| **Leaflet** | 30-50 cm | 18-24 pt | 14-16 pt | 10-12 pt | 8-10 pt |
| **A4 Poster** | 1-2 m | 48-72 pt | 24-36 pt | 18-24 pt | 14-18 pt |
| **A2 Poster** | 3-5 m | 72-120 pt | 36-48 pt | 24-36 pt | 18-24 pt |
| **A1 Poster** | 5-10 m | 120-200 pt | 60-96 pt | 36-48 pt | 24-36 pt |
| **Banner** | 10+ m | 200+ pt | 120-150 pt | 60-72 pt | 36-48 pt |
| **Digital** | 5-15 m | 150-250 pt | 80-120 pt | 60-100 pt | 40-60 pt |

### Quick Reference Chart

```
┌────────────────────────────────────────────────────────┐
│  DISTANCE   │  HEADLINE  │  BODY TEXT  │  CAPTION    │
├────────────────────────────────────────────────────────┤
│  0.5 m      │  24 pt     │  12 pt      │  10 pt      │
│  1 m        │  36 pt     │  18 pt      │  14 pt      │
│  2 m        │  48 pt     │  24 pt      │  18 pt      │
│  3 m        │  72 pt     │  36 pt      │  24 pt      │
│  5 m        │  120 pt    │  48 pt      │  36 pt      │
│  10 m       │  200 pt    │  72 pt      │  48 pt      │
│  15 m       │  300 pt    │  100 pt     │  60 pt      │
└────────────────────────────────────────────────────────┘
```

**Golden Rule:** When in doubt, go BIGGER. Better too big than too small.

---

## Hierarchy & Weight

### Visual Hierarchy

```
Level 1: HEADLINE (Largest, Boldest)
├─ Purpose: Grab attention, state main message
├─ Weight: Bold or Extra Bold
├─ Size: 2-3x body text
└─ Color: Primary brand or safety color

Level 2: SUBHEAD (Medium-Large)
├─ Purpose: Section breaks, key points
├─ Weight: Bold
├─ Size: 1.5-2x body text
└─ Color: Secondary brand color

Level 3: BODY TEXT (Medium)
├─ Purpose: Main content, explanations
├─ Weight: Regular
├─ Size: Base size for distance
└─ Color: Dark on light background

Level 4: CAPTION (Small)
├─ Purpose: Supporting info, contact
├─ Weight: Regular or Light
├─ Size: 0.75-0.9x body text
└─ Color: Muted or gray
```

### Font Weights

```
Extra Bold (800+):  Use sparingly for emphasis
Bold (700):         Subheads, important points
Semi-Bold (600):   Emphasis within body
Regular (400):     Body text, standard reading
Light (300):       Large display text only
```

### Line Spacing

```
Body Text:     1.5x font size (minimum)
Headlines:     1.2x font size
Captions:      1.3x font size
Lists:         1.4x font size
```

**Example:**
- 12pt body text → 18pt line spacing (1.5x)
- 48pt headline → 58pt line spacing (1.2x)

---

## Accessibility

### Minimum Size Standards

**WCAG Guidelines:**
```
Small text:  < 18pt (or 14pt bold) → 4.5:1 contrast
Large text:  ≥ 18pt (or 14pt bold) → 3:1 contrast
```

**Our Recommendations:**
```
Absolute minimum: 12pt body text
Recommended:      16pt body text (digital)
Large print:      18pt body text (print)
Signage:          24pt body text (minimum)
```

### Legibility Factors

**Character Spacing (Kerning):**
```
Normal:      0 (default)
Loose:       +5% for headlines
Tight:       -5% avoid (reduces readability)
```

**Word Spacing:**
```
Normal:      Space bar width
Wide:        1.5x for emphasis
Narrow:      Avoid
```

**Paragraph Width:**
```
Optimal:     45-75 characters (8-15 words)
Maximum:     100 characters (absolute max)
Narrow:      < 30 characters (avoid)
```

### Reading Level

**Target Reading Grade: 6-8**

**Achieve by:**
- Simple vocabulary
- Short sentences (10-15 words)
- Active voice
- One idea per sentence
- Explain technical terms

**Testing:**
- Use Flesch Reading Ease test
- Target score: 60-70 (standard)
- Test with target audience

---

## Implementation

### Canva Text Settings

```
Headline Setup:
├─ Font: Arial Bold
├─ Size: 72pt (adjust for distance)
├─ Spacing: 1.2
├─ Color: #1A5F7A (primary)
└─ Alignment: Left or Center

Body Text Setup:
├─ Font: Arial Regular
├─ Size: 24pt (adjust for distance)
├─ Spacing: 1.5
├─ Color: #2C3E50 on white
└─ Alignment: Left

Caption Setup:
├─ Font: Arial Regular
├─ Size: 18pt (adjust for distance)
├─ Spacing: 1.3
├─ Color: #7F8C8D (gray)
└─ Alignment: Left
```

### NotebookLM Prompts

```
Prompt: "Generate text for K3 poster with:
- Headline: 5-7 words, Arial Bold, 72pt
- Subhead: 10-12 words, Arial Bold, 36pt
- Body: 3-5 bullet points, Arial Regular, 24pt
- Caption: Contact info, Arial Regular, 18pt

Keep language at grade 6-8 reading level.
Use active voice and simple vocabulary."
```

### Digital Signage

```
Minimum Font Sizes (per 1920x1080 display):
├─ Title: 80-120pt
├─ Headlines: 60-80pt
├─ Body: 40-60pt
└─ Captions: 30-40pt

Test at actual size before deployment!
```

---

## Quick Checklist

```
Font Selection:
☐ Sans-serif font (Arial, Verdana)
☐ Professional appearance
☐ Universal compatibility
☐ No decorative fonts

Sizing:
☐ Calculated for viewing distance
☐ Headline 2-3x body text
☐ Body text meets minimums
☐ Tested at actual viewing distance

Spacing:
☐ Line spacing 1.5x (body)
☐ Character spacing normal
☐ Paragraph width 45-75 chars
☐ Adequate white space

Accessibility:
☐ Contrast ratio ≥ 4.5:1
☐ Reading grade 6-8 level
☐ Tested with screen reader
☐ Available in large print

Consistency:
☐ Same font family throughout
☐ Consistent hierarchy
☐ Aligned with brand
☐ Documented in style guide
```

---

## Common Issues

### Issue: Text Too Small

**Symptoms:**
- Squinting at distance
- Complaints about readability
- Low engagement

**Solutions:**
1. Increase by 25-50%
2. Reduce content to fit
3. Break into multiple posters
4. Use QR codes for detail

### Issue: Poor Font Choice

**Symptoms:**
- Hard to distinguish letters
- Unprofessional appearance
- Accessibility complaints

**Solutions:**
1. Switch to Arial or Verdana
2. Avoid decorative fonts
3. Use bold sparingly
4. Test with users

### Issue: Inconsistent Hierarchy

**Symptoms:**
- Confusing layout
- Unclear what's important
- Scannability issues

**Solutions:**
1. Define clear levels
2. Size differences obvious
3. Use weight for emphasis
4. Color coding support

---

## Resources

- [WebAIM Font Accessibility](https://webaim.org/techniques/fonts/)
- [Canva Typography Guide](https://www.canva.com/learn/typography/)
- [Google Fonts](https://fonts.google.com/)
- [Flesch Reading Ease Test](https://readabilityformulas.com/flesch-reading-ease/)

---

*Last updated: 2026-04-05*
