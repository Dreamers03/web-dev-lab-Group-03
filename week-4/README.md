LAB 4: Understanding Layout Control in CSS

A practical laboratory project focused on mastering core CSS layout techniques using the Box Model, Positioning, and Float/Clear concepts without relying on modern layout systems such as Flexbox or CSS Grid.

📌 Objective

The objective of this lab is to develop control over webpage layouts by manipulating:

Box Model (margin, padding, border)
Positioning (static, relative, absolute, fixed, sticky)
Float and Clear (float, clear)

The project intentionally demonstrates layout behavior and possible layout issues when CSS concepts are misapplied.

📂 Project Structure
LAB-4/
│
├── index.html
├── styles.css
└── README.md
🧠 Concepts Covered
Part 1 — Box Model (Control of Space)
Description

Every HTML element behaves like a rectangular box consisting of:

Content
Padding
Border
Margin
Implemented Tasks
Created three stacked boxes using <div>
Each box contains:
A heading
A paragraph
Applied:
padding
border
margin
Expected Observations
Padding increases internal spacing
Margin creates separation between boxes
Border surrounds content and padding
Part 2 — Positioning (Breaking Normal Flow)
Description

CSS positioning controls how elements are placed within the page layout.

Implemented Tasks
Created a bordered container
Added:
A paragraph
A label (NEW)
Applied:
position: relative to the container
position: absolute to the label
Positioned the label at the top-right corner
Additional Features
Fixed header using position: fixed
Sticky navigation bar using position: sticky
Expected Observations
Absolute elements position relative to the nearest positioned parent
Fixed elements remain visible during scrolling
Sticky elements switch behavior while scrolling
Part 3 — Float and Clear (Flow Manipulation)
Description

Float removes elements from the normal document flow and aligns them left or right.

Implemented Tasks
Created:
Main content section
Sidebar
Applied:
float: left
float: right
Added footer below both sections
Critical Requirement
Applied clear: both to the footer
Expected Observations
Floats disrupt normal stacking behavior
Footer overlaps if clear is not used
Layout instability appears when flow is unmanaged
Part 4 — Integrated Mini Layout
Description

Combined all learned concepts into a complete webpage layout.

Included Features
Fixed header
Sticky navigation bar
Two-column float layout
Styled content boxes using the box model
Absolutely positioned labels
Properly cleared footer
⚠️ Constraints

The following technologies were intentionally NOT USED:

❌ Flexbox
❌ CSS Grid

Only the following CSS concepts were allowed:

✅ Box Model
✅ Positioning
✅ Float and Clear
🚀 How to Run the Project
Download or clone the repository:
git clone <repository-url>
Open the project folder.
Launch index.html in any web browser.
📄 Deliverables
index.html
styles.css
👥 Group Members Participated
No.	Name	Registration Number
1	Jovin Jackson Peter	34559/T.2024
2	Deusdedit Allanus Muganyizi	34415/T.2024
3	Faraja Peter Kalikali	32741/T.2024
4	Douglas Munisi	34363/T.2024
5	Lilian Ado Moyo	32485/T.2024
6	Simwata Chrispin Mwansanga	34383/T.2024