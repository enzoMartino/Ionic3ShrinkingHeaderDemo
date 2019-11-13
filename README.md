# Ionic3ShrinkingHeaderDemo

# Shrinking Header
This component allows to shrink a portion of the ui proportionally the scroll of an ion-scroll component.

## Input Parameters
- scrollArea: **must** be the id assigned to the ion-scroll component
- headerHeight: is the original size of the portion of the ui which shrinks

## Usage Example

```html
<ion-header>
[...]

<shrinking-header  [scrollArea]="yourContent"
[startingHeaderHeight]="yourHeight">
***INSERT HERE THE CONTENT WHICH YOU WANT TO SHRINK***
</shrinking-header>

[...]
</ion-header>

<ion-content #yourContent>
***YOUR CONTENT***
</ion-content>
```

### Tips
- Bind a function to the touchend html event for angular's detect changes function for more fluidity.
