## Tailwind CSS Easings

Tailwind CSS plugin that extends `transitionTimingFunction` with custom Cubic Bézier functions.

```css
  .ease-in-quad: { transition-timing-function: cubic-bezier(0.550,  0.085, 0.680, 0.530) }
  .ease-in-cubic { transition-timing-function: cubic-bezier(0.550,  0.055, 0.675, 0.190) }
  .ease-in-quart: { transition-timing-function: cubic-bezier(0.895,  0.030, 0.685, 0.220) }
  .ease-in-quint: { transition-timing-function: cubic-bezier(0.755,  0.050, 0.855, 0.060) }
  .ease-in-sine: { transition-timing-function: cubic-bezier(0.470,  0.000, 0.745, 0.715) }
  .ease-in-expo: { transition-timing-function: cubic-bezier(0.950,  0.050, 0.795, 0.035) }
  .ease-in-circ: { transition-timing-function: cubic-bezier(0.600,  0.040, 0.980, 0.335) }
  .ease-in-back: { transition-timing-function: cubic-bezier(0.600, -0.280, 0.735, 0.045) }
  .ease-out-quad: { transition-timing-function: cubic-bezier(0.250,  0.460, 0.450, 0.940) }
  .ease-out-cubic: { transition-timing-function: cubic-bezier(0.215,  0.610, 0.355, 1.000) }
  .ease-out-quart: { transition-timing-function: cubic-bezier(0.165,  0.840, 0.440, 1.000) }
  .ease-out-quint: { transition-timing-function: cubic-bezier(0.230,  1.000, 0.320, 1.000) }
  .ease-out-sine: { transition-timing-function: cubic-bezier(0.390,  0.575, 0.565, 1.000) }
  .ease-out-expo: { transition-timing-function: cubic-bezier(0.190,  1.000, 0.220, 1.000) }
  .ease-out-circ: { transition-timing-function: cubic-bezier(0.075,  0.820, 0.165, 1.000) }
  .ease-out-back: { transition-timing-function: cubic-bezier(0.175,  0.885, 0.320, 1.275) }
  .ease-in-out-quad: { transition-timing-function: cubic-bezier(0.455,  0.030, 0.515, 0.955) }
  .ease-in-out-cubic: { transition-timing-function: cubic-bezier(0.645,  0.045, 0.355, 1.000) }
  .ease-in-out-quart: { transition-timing-function: cubic-bezier(0.770,  0.000, 0.175, 1.000) }
  .ease-in-out-quint: { transition-timing-function: cubic-bezier(0.860,  0.000, 0.070, 1.000) }
  .ease-in-out-sine: { transition-timing-function: cubic-bezier(0.445,  0.050, 0.550, 0.950) }
  .ease-in-out-expo: { transition-timing-function: cubic-bezier(1.000,  0.000, 0.000, 1.000) }
  .ease-in-out-circ: { transition-timing-function: cubic-bezier(0.785,  0.135, 0.150, 0.860) }
  .ease-in-out-back: { transition-timing-function: cubic-bezier(0.680, -0.550, 0.265, 1.550) }
```

### Installation and Setup

```
npm install @whiterussianstudio/tailwind-easing --save-dev
```

Add plugin to a `plugins` array in the configuration file:

```js
// tailwind.config.js
plugins: [
  require('@whiterussianstudio/tailwind-easing'),
  ...
]
```

If needed, utility variants can be generated with Tailiwind CSS `variants`:

```js
// tailwind.config.js
variants: {
  transitionTimingFunction: ['responsive', 'hover'],
  ...
}
```
