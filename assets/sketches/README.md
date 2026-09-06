# Visualization Sketches

These low-fidelity sketches use real aggregate values where numeric examples appear. They define layout, visual encoding, and interaction intent rather than final styling.

## 1 Pitcher profile radar

![Pitcher profile radar](01-pitcher-profile-radar.png)

**Technique:** Radar chart. **Purpose:** Compares each pitcher's velocity, Whiff%, Chase%, Zone%, and arsenal diversity to establish the baseline profile used to interpret two-strike choices.

## 2 Pitch-load heatmap

![Pitch-load heatmap](02-pitch-load-heatmap.png)

**Technique:** Matrix heatmap. **Purpose:** Shows whether velocity, secondary-pitch usage, or Whiff% changes as a starter moves from pitches 1-25 to 76+ within a game.

## 3 Count-to-arsenal shift

![Count-to-arsenal shift](03-count-arsenal.png)

**Technique:** 100% stacked bar chart. **Purpose:** Reveals how pitch-family shares differ between early, two-strike, and full counts for the selected pitcher.

## 4 Strike-zone expansion

![Strike-zone expansion](04-strike-zone-shift.png)

**Technique:** Binned spatial strike-zone map. **Purpose:** Compares the share of pitches in Heart, Shadow, Chase, and Waste regions before and after reaching the project's two-strike states.

## 5 Movement and Whiff efficiency

![Movement and Whiff efficiency](05-movement-whiff.png)

**Technique:** Bubble scatter plot. **Purpose:** Connects horizontal and vertical movement to Whiff%, pitch volume, pitch type, and location while suppressing unreliable small samples.

## Overall dashboard wireframe

![Dashboard wireframe](06-dashboard-wireframe.png)

The dashboard links all views through pitcher, count-state, batter-side, and minimum-sample filters. Selecting a pitcher or pitch type updates the workload, arsenal, location, and outcome views together.
