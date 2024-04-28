# Animations

Due to the development state of the stylesheet, only few animations are available.

# Text Animation

Text animations apart from the text effects mentioned in the [previous](text_effects.md) page are mentioned below.

## Typewriter effect

Want to give your text an amazing typing effect? Just add the following line of code.

```html
<typebox>

       <type>Typing Effect</type>

<typebox>
```

The tag `<type></type>` must be used inside the tag `<typebox></typebox>`

Due to the limitations of this code which is pure css you have to change the following as well.

```css
type{

    width: 13ch;
}
```

Include the code above in another css file assigned below the SJML css file.

> [!IMPORTANT]
> Make sure to change the `width` to the number of characters in your text INCLUDING white spaces.


## Smooth Typing Effect

Same as the typewriter effect but instead of the typing effects this gives the text smooth appearing effect.

```html
<typebox>

       <typesmooth>Smooth Typing</typesmooth>

<typebox>
```

The tag `<typesmooth></typesmooth>` must be used inside the tag `<typebox></typebox>`

Due to the limitations of this code which is pure css you have to change the following as well.

```css
typesmooth{

    width: 13ch;
}
```

Include the code above in another css file assigned below the SJML css file.

> [!IMPORTANT]
> Make sure to change the `width` to the number of characters in your text INCLUDING white spaces.


# Background animations

More to come! 

## Animated Gradient

Use the following code to give your webpage an amazing animated background gradient

### Preview
![Gradient Animation Preview](gr.png)
