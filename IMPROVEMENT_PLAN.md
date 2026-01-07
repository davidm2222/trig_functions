# Trig Function Visualizer - Improvement Plan

## Purpose
Teaching tool for a math-curious 12-year-old to understand trigonometric concepts visually, especially:
- What happens at edge cases (when side lengths go to 0)
- How the unit circle relates to right triangles
- How the ratios (sin/cos/tan) change as the angle changes

## Current Issues to Address
1. **Unit circle is bland** - lacks educational labeling to show what's happening
2. **Graph looks overwhelming** with all 3 functions at once - need better visual clarity
3. **Overall design is boring** - needs a more modern, slicker feel (functional, not fancy)
4. **Missing explicit ratio visualization** - need to show which sides form sine, cosine, etc.

## Planned Improvements

### 1. Enhanced Unit Circle Visualization
- **Highlight the sides that form each ratio**
  - Show which two sides are being compared for sine (vertical/radius)
  - Show which two sides are being compared for cosine (horizontal/radius)
  - Show which two sides are being compared for tangent (vertical/horizontal)
- **Add labels directly on the diagram**
  - Label sides: "opposite (sin)", "adjacent (cos)", "radius = 1"
  - Show the angle arc with degree marking
  - Add axis labels (0°, 90°, 180°, 270° around the circle)
- **Visual emphasis**
  - Use color coding to match graph colors (sin=red, cos=blue, tan=green)
  - Thicker lines or highlighting for active ratios

### 2. Explicit Ratio Calculations
Display the actual calculations below or near the unit circle:
- Example: `sin(45°) = opposite/radius = 0.71/1.00 = 0.71`
- Example: `cos(45°) = adjacent/radius = 0.71/1.00 = 0.71`
- Example: `tan(45°) = opposite/adjacent = 0.71/0.71 = 1.00`
- Show only for checked functions
- Update in real-time as angle changes

### 3. Animation Feature
- **Play/Pause button** to automatically sweep the angle from 0° to 360°
- Adjustable speed control (slow/medium/fast)
- Allows continuous observation of how ratios change
- Especially useful for seeing behavior at critical angles

### 4. Expanded Preset Angles
Add buttons for special angles where interesting things happen:
- **0°** - cos=1, sin=0, tan=0
- **30°** - special triangle values
- **45°** - sin=cos (current button)
- **60°** - special triangle values
- **90°** - sin=1, cos=0, tan=undefined (current button)
- **180°** - sin=0, cos=-1, tan=0 (current button)
- **270°** - sin=-1, cos=0, tan=undefined

### 5. Better Graph Visual Clarity
When multiple functions are displayed:
- Add a **legend** showing which color is which function
- Improve **line thickness** or add slight transparency
- Consider **grid lines** on the graph for easier reading
- Add **vertical dashed lines** at key angles (90°, 180°, 270°)

### 6. Enhanced Connection Between Circle and Graph
- **Highlight the current point** on each function curve that corresponds to the selected angle
- Draw a **dot or circle** on the wave at the current theta value
- Consider subtle **animation/pulse** effect to draw attention to the connection
- Match colors (sin point is red, cos point is blue, etc.)

### 7. Modern Design Updates
- **Improved color scheme** - more vibrant, cohesive palette
- **Better spacing and layout** - more breathing room between elements
- **Enhanced typography** - clearer labels and values
- **Rounded corners** on controls and buttons
- **Button hover effects** for better interactivity
- **Card-based layout** to separate different sections visually
- **Responsive sizing** - ensure everything scales well

## Implementation Priority
1. Unit circle enhancements (labels, ratio highlighting)
2. Ratio calculations display
3. Modern design/styling updates
4. Preset angle buttons
5. Graph visual improvements (legend, highlights)
6. Connection between circle and graph (point highlighting)
7. Animation/play button feature

## Success Criteria
- A 12-year-old can understand which sides create sine/cosine/tangent just by looking
- Edge cases (90°, 270°) are easy to explore and understand
- The connection between the unit circle and the wave functions is visually obvious
- The app looks modern and engaging without being distracting
- All features work smoothly together
