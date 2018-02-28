Those principles are inspired of [Google’s Material Design](https://material.io/guidelines/material-design/elevation-shadows.html) rules concerning elements elevation. They’re used to create hierarchy between elements
and make them feel natural for users. In real life, all objects project a shadow. It has to be the same in an interface. Same elements with same elevation
and shadows belong to the same group.

## Layer and content properties


Any interface is composed by a set of **layers** arranged on top of each other. On these layers are placed **items** (like a pop-up, a navigation bar, a form...). Each item contains **a content** (paragraph, image, icon...). Each layer, item and content follow some rules helping to make the whole interface consistent. General rules are the following :

- all layers are the same thickness
- a layer has a thickness of 1px on the interface
- layers live on distincts  z-coordinate planes. Y-axis and blur of the box shadow are used to represent these planes
- items on the same layer cannot occupy the same space.
- items on different layers can be stacked on top of each other (overlay, for example)
- content appears on same plane as layer, they don’t have a proper elevation.


## Elevation scale

Elevation range is represented with a scale, from 0 to 24. 24 is the highest point of the interface. The higher the elevation of a layer is, the larger the shadow of this layer is. Unit of the elevation is equal to the pixel value of the blur applied to shadow.

```hint|neutral
- Base layer : no box-shadow
- Flat design : no box-shadow
- Raised : box-shadow (0 1px 2px opacity: 0.1)
- Overlay : box-shadow (0 4px 8px opacity: 0.1)
- Sticky nav : box-shadow (0 6px 12px opacity: 0.1)
- Other nav : box-shadow (0 8px 16px opacity: 0.1)
- Popup : box-shadow (0 12px 24px opacity: 0.1)
```

```image
plain: true
span: 3
src: "/assets/shadows/schema-shadowing.png"
```
