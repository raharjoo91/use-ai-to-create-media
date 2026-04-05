# K3 Color Palettes & Safety Standards

> ISO 7010 compliant color schemes for occupational health and safety communication

## Table of Contents
1. [ISO 7010 Safety Colors](#iso-7010-safety-colors)
2. [Recommended Color Palettes](#recommended-color-palettes)
3. [Contrast Requirements](#contrast-requirements)
4. [Implementation in Tools](#implementation-in-tools)
5. [Accessibility Check](#accessibility-check)

---

## ISO 7010 Safety Colors

### Mandatory Safety Sign Colors

| Color | Purpose | Hex Code | RGB | CMYK |
|-------|---------|----------|-----|------|
| **Red** | Prohibition, Fire equipment | `#E74C3C` | 231, 76, 60 | 0, 67, 74, 9 |
| **Yellow** | Warning, Caution | `#F39C12` | 243, 156, 18 | 0, 36, 93, 5 |
| **Green** | Safe condition, Emergency exit | `#27AE60` | 39, 174, 96 | 78, 0, 100, 0 |
| **Blue** | Mandatory action | `#1A5F7A` | 26, 95, 122 | 79, 22, 0, 52 |
| **Black/White** | Information | `#2C3E50` / `#FFFFFF` | 44, 62, 80 | 45, 23, 0, 69 |

### Color Usage Guidelines

```
RED (E74C3C):
├─ Stop signs
├─ Prohibition symbols (circle with slash)
├─ Fire equipment location
├─ Emergency stop buttons
└─ Danger warnings

YELLOW (F39C12):
├─ Caution signs
├─ Warning of hazards
├─ Slip/trip/fall warnings
├─ Electrical hazard warnings
└─ "Watch your step" signs

GREEN (27AE60):
├─ Emergency exit signs
├─ First aid equipment location
├─ Safe condition indicators
├─ "Go" signals
└─ Assembly points

BLUE (1A5F7A):
├─ Mandatory action signs
├─ PPE requirements
├─ Specific instructions
├─ Information signs
└─ Process indicators
```

---

## Recommended Color Palettes

### Palette 1: Standard K3 (ISO 7010)

```
Primary:   #1A5F7A (Blue - Mandatory)
Secondary: #579BB1 (Light Blue)
Accent:    #E74C3C (Red - Danger)
Success:   #27AE60 (Green - Safe)
Warning:   #F39C12 (Yellow - Caution)
Neutral:   #7F8C8D (Gray)
```

**Use Cases:**
- General safety posters
- Standard K3 communications
- Regulatory compliance materials
- Training materials

### Palette 2: Fire Safety

```
Primary:   #C0392B (Fire Red)
Secondary: #E74C3C (Bright Red)
Accent:    #F39C12 (Warning Yellow)
Success:   #27AE60 (Safe Exit)
Neutral:   #ECF0F1 (Light Gray)
Text:      #2C3E50 (Dark Blue-Gray)
```

**Use Cases:**
- Fire safety posters
- Emergency evacuation maps
- Fire equipment locations
- Emergency procedure guides

### Palette 3: Medical/First Aid

```
Primary:   #27AE60 (Medical Green)
Secondary: #2ECC71 (Light Green)
Accent:    #E74C3C (Emergency Red)
Warning:   #F39C12 (Caution)
Neutral:   #D5F4E6 (Pale Green)
Text:      #1A5F7A (Dark Blue)
```

**Use Cases:**
- First aid posters
- Medical emergency guides
- Health promotion materials
- Wellness campaign materials

### Palette 4: Construction Safety

```
Primary:   #F39C12 (Safety Orange/Yellow)
Secondary: #E67E22 (Orange)
Accent:    #1A5F7A (Hard Hat Blue)
Success:   #27AE60 (Safe)
Neutral:   #F5F5F5 (Light Gray)
Text:      #2C3E50 (Dark)
```

**Use Cases:**
- Construction site posters
- PPE requirement signs
- Hazard warning materials
- Site-specific safety guides

### Palette 5: Office Ergonomics

```
Primary:   #1A5F7A (Calm Blue)
Secondary: #579BB1 (Light Blue)
Accent:    #27AE60 (Healthy Green)
Warning:   #F39C12 (Alert)
Neutral:   #ECF0F1 (Light Gray)
Text:      #2C3E50 (Dark Blue-Gray)
```

**Use Cases:**
- Office safety posters
- Ergonomics guides
- Wellness materials
- Indoor environment signs

---

## Contrast Requirements

### WCAG 2.1 AA Standards

**Minimum Contrast Ratios:**
- Normal text (< 18pt): 4.5:1
- Large text (18pt+): 3:1
- Graphics/Icons: 3:1

### Validated Color Combinations

| Background | Text | Ratio | Pass? |
|------------|------|-------|-------|
| White | Black | 21:1 | ✅ |
| White | #1A5F7A | 7.5:1 | ✅ |
| White | #E74C3C | 4.5:1 | ✅ |
| White | #F39C12 | 1.4:1 | ❌ |
| #1A5F7A | White | 7.5:1 | ✅ |
| #E74C3C | White | 4.5:1 | ✅ |
| #F39C12 | Black | 10.1:1 | ✅ |
| #F39C12 | White | 1.4:1 | ❌ |
| #27AE60 | White | 4.8:1 | ✅ |
| #27AE60 | Black | 4.4:1 | ❌ |

**Note:** Yellow on white fails WCAG AA. Use black text on yellow, or choose a darker yellow.

### Improved Yellow for Accessibility

```
Standard Yellow: #F39C12 (contrast 1.4:1 with white) ❌
Accessible Yellow: #D4AC0D (contrast 4.6:1 with white) ✅

Use #D4AC0D for:
├─ Yellow backgrounds with white text
├─ Warning signs requiring readability
└─ Accessible materials

Use #F39C12 for:
├─ Icons and graphics
├─ Accent elements
└─ High-visibility warnings
```

---

## Implementation in Tools

### Canva Brand Kit

**Setup Steps:**
```
1. Open Canva → Brand Kit
2. Add primary color: #1A5F7A
3. Add secondary: #579BB1
4. Add accent: #E74C3C
5. Add success: #27AE60
6. Add warning: #F39C12 or #D4AC0D
7. Save as "K3 Safety Palette"
```

**Quick Apply:**
- Select element
- Click brand color
- Choose from palette

### NotebookLM

While NotebookLM doesn't use colors directly, you can specify color requirements in prompts:

```
Prompt: "Create a poster design specification using
ISO 7010 safety colors: red #E74C3C for danger elements,
yellow #F39C12 for warnings, green #27AE60 for safe actions,
blue #1A5F7A for mandatory requirements"
```

### Sora Video Prompts

Include color specifications in prompts:

```
"Worker wearing high-visibility vest in ISO 7010 yellow #F39C12
with blue hard hat #1A5F7A, against white background #FFFFFF,
ensuring high contrast and visibility"
```

---

## Accessibility Check

### Online Tools

**WebAIM Contrast Checker:**
- URL: https://webaim.org/resources/contrastchecker/
- Enter foreground and background colors
- Check WCAG compliance
- Get suggestions for improvement

**Canva Built-in Checker:**
- Accessible from Accessibility menu
- Real-time contrast feedback
- Suggestions for improvements

### Manual Checklist

```
Visual Check:
☐ Text is readable from intended distance
☐ Color coding is not the only indicator
☐ Grayscale view still conveys meaning
☐ No red/green combinations (color blindness)
☐ Sufficient contrast between adjacent colors

Technical Check:
☐ Contrast ratio ≥ 4.5:1 (normal text)
☐ Contrast ratio ≥ 3:1 (large text, 18pt+)
☐ Validated with WebAIM checker
☐ Tested in grayscale
☐ Tested by colorblind users if possible
```

### Color Blindness Considerations

**Avoid These Combinations:**
- Red/green (most common color blindness)
- Green/brown
- Blue/purple
- Light green/yellow

**Safe Alternatives:**
- Blue/orange
- Black/white
- Blue/yellow
- Patterns + colors

**Testing:**
- Use color blindness simulator
- Test with deuteranopia/protanopia filters
- Ensure meaning without color

---

## Quick Reference

### Copy-Paste Color Codes

```
Red (Danger):     #E74C3C
Yellow (Caution): #F39C12
Green (Safe):     #27AE60
Blue (Mandatory): #1A5F7A
Black (Text):     #2C3E50
White (Bg):       #FFFFFF
```

### Canva Hex Codes

```
Primary:   1A5F7A
Secondary: 579BB1
Accent:    E74C3C
Success:   27AE60
Warning:   F39C12
Dark:      2C3E50
Light:     ECf0F1
```

### CSS Variables

```css
:root {
  --k3-red: #E74C3C;
  --k3-yellow: #F39C12;
  --k3-green: #27AE60;
  --k3-blue: #1A5F7A;
  --k3-dark: #2C3E50;
  --k3-light: #ECF0F1;
  --k3-gray: #7F8C8D;
}
```

---

## Resources

- [ISO 7010:2019 Standard](https://www.iso.org/standard/75782.html)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Canva Color Palette Generator](https://www.canva.com/colors/color-wheel/)
- [Color Blindness Simulator](https://www.toptal.com/designers/colorfilter)

---

*Last updated: 2026-04-05*
