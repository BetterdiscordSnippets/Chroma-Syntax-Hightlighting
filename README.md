# Chroma Syntax Highlighting
Adds a chroma effect to code blocks that support syntax highlighting.
```css
@keyframes chroma {
    0% {color: red;}
    10% {color: orangered;}
    20% {color: orange;}
    30% {color: yellow;}
    40% {color: yellowgreen;}
    50% {color: turquoise;}
    75% {color: blue;}
    90% {color: rgb(147, 4, 248);}
    100% {color: rgb(255, 0, 55);}
}

.hljs-attr, .hljs-attribute, .hljs-class .hljs-title, .hljs-template-variable, .hljs-type, .hljs-variable {
    filter: brightness(1.5);
    animation: chroma 5s ease-in-out infinite;
}
.hljs-addition, .hljs-keyword, .hljs-selector-tag {
    filter: brightness(2);
    animation: chroma 5s ease-in-out infinite;
}
.hljs-name, .hljs-section, .hljs-selector-class, .hljs-selector-id, .hljs-title {
    filter: brightness(2);
    animation: chroma 5s ease-in-out infinite;
}
.hljs-doctag, .hljs-literal, .hljs-meta .hljs-meta-string, .hljs-number, .hljs-regexp, .hljs-string {
    filter: brightness(2);
    animation: chroma 5s ease-in-out infinite;
}
.hljs-built_in, .hljs-deletion {
    filter: brightness(2);
    animation: chroma 5s ease-in-out infinite;
}
```
