# Neulight
A lightweight neumorphic CSS framework

## 1. Basic Setup

Neulight CSS is designed to be easy to integrate into your project. After including the CSS file, you're ready to use the framework. The dark mode feature is particularly useful for creating a visually appealing night-time experience or for users who prefer darker interfaces.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Neulight CSS Project</title>
    <link rel="stylesheet" href="path/to/neulight.css">
</head>
<body>
    <!-- For light mode -->
    <div class="neulight-container">
        <h1 class="neulight-text-2xl">Welcome to My Neulight CSS Project</h1>
        <!-- More content here -->
    </div>

    <!-- For dark mode -->
    <div class="neulight-dark">
        <div class="neulight-container">
            <h1 class="neulight-text-2xl">Welcome to Dark Mode</h1>
            <!-- More content here -->
        </div>
    </div>
</body>
</html>
```

## 2. Typography

Neulight CSS provides a comprehensive set of typography classes to control font size and weight. This allows for consistent and responsive text styling across your project.

```html
<h1 class="neulight-text-5xl neulight-font-bold">Main Heading</h1>
<h2 class="neulight-text-4xl neulight-font-medium">Subheading</h2>
<p class="neulight-text-base">
    This is a paragraph with <span class="neulight-font-bold">bold text</span> and 
    <span class="neulight-font-light">light text</span>.
</p>
<small class="neulight-text-xs">Small print</small>
```

## 3. Containers

The `neulight-container` class creates a responsive container that adjusts its max-width at different breakpoints. This ensures your content looks good on various screen sizes.

```html
<div class="neulight-container">
    <div class="neulight-neumorphic neulight-p-4">
        <h2 class="neulight-text-2xl">Responsive Container</h2>
        <p>This content will adjust its width based on the screen size.</p>
    </div>
</div>
```

## 4. Neumorphic Styles

Neumorphism is the core design principle of Neulight CSS. It creates a soft, extruded look using subtle shadows.

```html
<div class="neulight-flex neulight-justify-between">
    <div class="neulight-neumorphic neulight-p-4 neulight-m-2">
        <h3>Raised Element</h3>
        <p>This element appears to be raised from the surface.</p>
    </div>
    <div class="neulight-neumorphic-inset neulight-p-4 neulight-m-2">
        <h3>Inset Element</h3>
        <p>This element appears to be pressed into the surface.</p>
    </div>
</div>
```

## 5. Buttons

Neulight CSS offers a variety of button styles. The neumorphic effect is particularly noticeable on interactive elements like buttons.

```html
<div class="neulight-flex neulight-flex-wrap neulight-justify-between">
    <button class="neulight-btn neulight-m-2">Default</button>
    <button class="neulight-btn neulight-btn-primary neulight-m-2">Primary</button>
    <button class="neulight-btn neulight-btn-secondary neulight-m-2">Secondary</button>
    <button class="neulight-btn neulight-btn-success neulight-m-2">Success</button>
    <button class="neulight-btn neulight-btn-danger neulight-m-2">Danger</button>
</div>
```

## 6. Form Elements

Form elements in Neulight CSS are styled to match the neumorphic design, providing a cohesive look to your forms.

```html
<form class="neulight-neumorphic neulight-p-4">
    <div class="neulight-mb-3">
        <label for="name" class="neulight-block neulight-mb-2">Name:</label>
        <input type="text" id="name" class="neulight-input" placeholder="John Doe">
    </div>
    <div class="neulight-mb-3">
        <label for="message" class="neulight-block neulight-mb-2">Message:</label>
        <textarea id="message" class="neulight-textarea" placeholder="Your message here"></textarea>
    </div>
    <div class="neulight-mb-3">
        <label for="country" class="neulight-block neulight-mb-2">Country:</label>
        <select id="country" class="neulight-select">
            <option>Select a country</option>
            <option>USA</option>
            <option>Canada</option>
            <option>UK</option>
        </select>
    </div>
    <div class="neulight-mb-3">
        <label class="neulight-radio">
            I agree to the terms
            <input type="radio" name="terms">
            <span class="neulight-radio-checkmark"></span>
        </label>
    </div>
    <button type="submit" class="neulight-btn neulight-btn-primary">Submit</button>
</form>
```

## 7. Cards

Cards are versatile components for displaying content. In Neulight CSS, they feature the signature neumorphic style.

```html
<div class="neulight-grid neulight-grid-cols-3 neulight-gap-4">
    <div class="neulight-card">
        <h3 class="neulight-text-xl neulight-mb-2">Card 1</h3>
        <p>This is the content for card 1.</p>
    </div>
    <div class="neulight-card">
        <h3 class="neulight-text-xl neulight-mb-2">Card 2</h3>
        <p>This is the content for card 2.</p>
    </div>
    <div class="neulight-card">
        <h3 class="neulight-text-xl neulight-mb-2">Card 3</h3>
        <p>This is the content for card 3.</p>
    </div>
</div>
```

## 8. Toggle Switch

The neumorphic toggle switch provides an attractive alternative to standard checkboxes.

```html
<div class="neulight-flex neulight-items-center">
    <label class="neulight-switch neulight-mr-3">
        <input type="checkbox">
        <span class="neulight-slider"></span>
    </label>
    <span>Toggle Feature</span>
</div>
```

## 9. Layout Utilities

Neulight CSS provides both flexbox and grid utilities for creating responsive layouts.

```html
<!-- Flexbox example -->
<div class="neulight-flex neulight-flex-wrap neulight-items-center neulight-justify-between neulight-p-4 neulight-neumorphic">
    <div class="neulight-neumorphic-inset neulight-p-2 neulight-m-2">Flex Item 1</div>
    <div class="neulight-neumorphic-inset neulight-p-2 neulight-m-2">Flex Item 2</div>
    <div class="neulight-neumorphic-inset neulight-p-2 neulight-m-2">Flex Item 3</div>
</div>

<!-- Grid example -->
<div class="neulight-grid neulight-grid-cols-4 neulight-gap-4 neulight-p-4 neulight-neumorphic">
    <div class="neulight-neumorphic-inset neulight-p-2">Grid Item 1</div>
    <div class="neulight-neumorphic-inset neulight-p-2">Grid Item 2</div>
    <div class="neulight-neumorphic-inset neulight-p-2">Grid Item 3</div>
    <div class="neulight-neumorphic-inset neulight-p-2">Grid Item 4</div>
</div>
```

## 10. Spacing Utilities

Neulight CSS includes utilities for adding margin and padding, allowing for fine-tuned spacing in your layouts.

```html
<div class="neulight-neumorphic neulight-p-4">
    <div class="neulight-neumorphic-inset neulight-p-2 neulight-m-3">
        This element has padding of 0.5rem and margin of 1rem.
    </div>
    <div class="neulight-neumorphic-inset neulight-p-4 neulight-mt-5">
        This element has padding of 1.5rem and a top margin of 3rem.
    </div>
</div>
```

## 11. Responsive Utilities

These utilities allow you to show or hide elements based on screen size, enabling the creation of responsive designs.

```html
<div class="neulight-neumorphic neulight-p-4">
    <p class="neulight-hidden neulight-sm:block">This text is hidden by default but visible on small screens and up.</p>
    <p class="neulight-block neulight-md:hidden">This text is visible by default but hidden on medium screens and up.</p>
    <p class="neulight-hidden neulight-lg:block">This text only appears on large screens and up.</p>
</div>
```

By combining these elements and utilities, you can create complex, responsive layouts with a consistent neumorphic style. Remember to consider accessibility when using these styles, especially ensuring sufficient color contrast and clear visual indicators for interactive elements.

