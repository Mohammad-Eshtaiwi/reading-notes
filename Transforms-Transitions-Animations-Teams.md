# About Teams

To make the team more efficent better the teammates need to feel safe.So sometimes teammates need to explane themselfs with the others and that make them feel closer. Also it is important to make a clear goals to the team to make it work mor efficent.

# transform

```
transform: type(value)
```

## 2D Rotate

The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees.

```
transform: rotate(20deg);
```

##2D Scale

Using the scale value within the transform property allows you to change the appeared size of an element.

```
transform: scale(.75);
```

## 2D Translate

The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

```
.box-1 {
  transform: translateX(-10px);
}
.box-2 {
  transform: translateY(25%);
}
.box-3 {
  transform: translate(-10px, 25%);
}
```

## 2D Skew

The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both.

```
.box-1 {
  transform: skewX(5deg);
}
.box-2 {
  transform: skewY(-20deg);
}
.box-3 {
  transform: skew(5deg, -20deg);
}

```

for more info: [Transforms](https://learn.shayhowe.com/advanced-html-css/css-transforms)

# Transitions

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

# Animations

Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

for more info: [Transitions & Animations](https://learn.shayhowe.com/advanced-html-css/transitions-animations/)
