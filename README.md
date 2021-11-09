# Material UI Page/Component builder

https://user-images.githubusercontent.com/71606506/135815762-72ad07ce-3428-4e06-9681-20529cc31eb8.mp4

Current support over 50 components

All Components except (Typography) are created from json file

Component Props and Component Styles can be easy changed or upgraded

Example:

```
GridContainer: {
    component: "GridContainer",
    propTypes: {
      container: { propName: "container", type: "bool", default: true },
      item: { propName: "item", type: "bool", default: false },
      spacing: {
        propName: "spacing",
        type: "oneOfDD",
        values: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10],
        default: 0,
      },
      alignContent: {
        propName: "alignContent",
        type: "oneOfDD",
        values: [
          "stretch",
          "center",
          "flex-start",
          "flex-end",
          "space-between",
          "space-around",
        ],
        default: "stretch",
      },
      alignItems: {
        propName: "alignItems",
        type: "oneOfDD",
        values: ["flex-start", "center", "flex-end", "stretch", "baseline"],
        default: "stretch",
      },
      direction: {
        propName: "direction",
        type: "oneOfDD",
        values: ["row", "row-reverse", "column", "column-reverse"],
        default: "row",
      },
      justify: {
        propName: "justify",
        type: "oneOfDD",
        values: [
          "flex-start",
          "center",
          "flex-end",
          "space-between",
          "space-around",
          "space-evenly",
        ],
        default: "flex-start",
      },
    },
  },
```
