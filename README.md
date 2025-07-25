# Track-Minor Overlap & ULC Checker

I am working on a tool/website that will be used by the advisors in the Computer Science department at the University of Maryland.
The main function of the tool is to detect overlapping courses between a student's major and minor.

## Features

### Track Support
- **General Track**: Standard CS track with area-based electives
- **Cybersecurity Track**: Security-focused curriculum
- **Machine Learning Track**: AI/ML specialized courses
- **Data Science Track**: Data analysis and statistics focus
- **Quantum Information Track**: Comprehensive quantum computing curriculum

### Quantum Information Track (NEW!)
The Quantum Information track has been fully implemented with detailed requirements:

#### 🎯 Upper Level Concentration (ULC)
- 12 credits at 300-400 level outside CMSC
- 1.7 GPA minimum requirement
- Must be chosen in consultation with CMSC advisor
- No cross-listed CMSC courses allowed

#### 📚 Lower Level Requirements
1. **Math Foundation**: MATH 140, MATH 141 (required)
2. **CS Core**: CMSC 131/133, 132, 216, 250, 330, 351 (6 courses)
3. **Statistics**: One 400-level STAT course with MATH 141+ prerequisite
4. **Math Choice**: One from MATH 240, 341, or 461

#### 🔬 Required Courses
- CMSC 457 (Quantum Computation) - also counts as Area 4
- PHYS 467 (Quantum Information)

#### 🌟 Quantum Information Areas
5 courses from at least 3 different areas (max 3 per area):
- **Area 1 - Systems**: CMSC 411, 412, 414, 416, 417
- **Area 2 - Information Processing**: CMSC 420, 421, 422, 423, 424, 426, 427, 470, 471, 472
- **Area 3 - Software Engineering**: CMSC 430, 433, 434, 435, 436, 471
- **Area 4 - Theory**: CMSC 451, 452, 454, 456, 457, 474, MATH 456
- **Area 5 - Numerical Analysis**: CMSC/AMSC 460, 466

#### 📖 QI Electives
3 credits from CMSC 300/400 level courses (excluding CMSC 330, 351)

## Minor Support
- Math Minor
- Robotics Minor
- Statistics Minor
- Quantum Science & Engineering (QSE) Minor
- Computational Finance Minor
- Business Analytics Minor

## Overlap Detection
- Identifies courses that count for both track and minor requirements
- Color-coded results:
  - 🟢 Green: Allowed overlaps (optimal)
  - 🟡 Yellow: Single overlaps (acceptable)
  - 🔴 Red: Not allowed (exceeds limits or minor-minor overlaps)

## ULC Validation
- Automatically filters out restricted ULC courses
- Provides warnings for courses that don't count toward ULC requirements
- Tracks total valid ULC credits

## Usage
1. Select your track from the dropdown
2. Check the minors you're pursuing
3. Click "Check Overlap and ULC Validation"
4. Review the color-coded results and recommendations

## Files
- `index.html` - Main application interface
- `Quantum Track.html` - Detailed Quantum Information track requirements
- `General Track.html` - General track course definitions
- `Cybersecurity Track.html` - Cybersecurity track specifics
- `ML Track.html` - Machine Learning track courses
- `Data Science Track.html` - Data Science track requirements
- `test_quantum.html` - Test file for Quantum track validation
