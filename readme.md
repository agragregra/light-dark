# light-dark
support for light/dark mode (html/css/js)

### css mode classes (root):
```
.light
.dark
```

### theme switcher:
```
<span data-mode="light">Light</span>
<span data-mode="dark">Dark</span>
<span data-mode="auto">Auto</span>
```

### switcher active item:
```
[data-mode].active {}
```

### theme toggler:
```
<div class="toggler"><button></button></div>
```

### toggler active item:
```
(recommended):
.light .toggler {}
.dark .toggler {}

(option):
.toggler.toggler-light {}
.toggler.toggler-dark {}
```
