# Data Visualization Projects: Visualize Data with a Treemap Diagram for freecodecamp.org

### Build a Treemap Diagram with D3


#### Objective

Build a CodePen.io app that is functionally similar to this: https://codepen.io/freeCodeCamp/full/KaNGNR.

#### Fulfill the below user stories and get all of the tests to pass. Give it your own personal style. You can use HTML, JavaScript, CSS, and the D3 svg-based visualization library. The tests require axes to be generated using the D3 axis property, which automatically generates ticks along the axis. These ticks are required for passing the D3 tests because their positions are used to determine alignment of graphed elements. Required (non-virtual) DOM elements are queried on the moment of each test. If you use a frontend framework (like Vue for example), the test results may be inaccurate for dynamic content. We hope to accommodate them eventually, but these frameworks are not currently supported for D3 projects.

1. User Story: My tree map should have a title with a corresponding id="title".
2. User Story: My tree map should have a description with a corresponding id="description".
3. User Story: My tree map should have rect elements with a corresponding class="tile" that represent the data.
4. User Story: There should be at least 2 different fill colors used for the tiles.
5. User Story: Each tile should have the properties data-name, data-category, and data-value containing their corresponding name, category, and value.
6. User Story: The area of each tile should correspond to the data-value amount: tiles with a larger data-value should have a bigger area.
7. User Story: My tree map should have a legend with corresponding id="legend".
8. User Story: My legend should have rect elements with a corresponding class="legend-item".
9. User Story: The rect elements in the legend should use at least 2 different fill colors.
10. User Story: I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. User Story: My tooltip should have a data-value property that corresponds to the data-value of the active area.

#### For this project you can use any of the following datasets:

* Kickstarter Pledges: https://cdn.rawgit.com/freeCodeCamp/testable-projects-fcc/a80ce8f9/src/data/tree_map/kickstarter-funding-data.json
* Movie Sales: https://cdn.rawgit.com/freeCodeCamp/testable-projects-fcc/a80ce8f9/src/data/tree_map/movie-data.json
* Video Game Sales: https://cdn.rawgit.com/freeCodeCamp/testable-projects-fcc/a80ce8f9/src/data/tree_map/video-game-sales-data.json
