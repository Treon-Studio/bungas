# Bungas UI

Bungas is a thoughtfully crafted component library designed for modern React applications.
Built on the foundation of Radix UI Primitives, Tailwind CSS v4, Tailwind Variants, and TypeScript,
it offers a comprehensive suite of accessible, customizable, and type-safe components to
streamline your development process.

## Core Principles

* **Variants** - Leveraging the power of Tailwind Variants for advanced styling control
* **Accessibility First** - Every component adheres to WCAG guidelines and WAI-ARIA patterns
* **Developer Experience** - Intuitive APIs with comprehensive TypeScript definitions
* **Design Flexibility** - Easily adapt components to match your unique design system
* **Separation of Concerns** - CSS files are separated from component logic for improved maintainability and readability

## Why Bungas?

Bungas stands out from other component libraries like shadcn/ui by fully embracing
[**Tailwind Variants**](https://www.tailwind-variants.org/) - a powerful utility that
combines Tailwind's flexibility with a first-class variant API. This key difference provides:

* **Superior Variant Management** - Create complex component states with a clean, declarative API
* **Responsive Variants** - Easily define different styles across breakpoints
* **Slot-based Styling** - Apply styles to specific parts of components with precision
* **Conflict Resolution** - Automatic handling of conflicting Tailwind classes
* **Type Safety** - Full TypeScript integration for autocomplete and error prevention

## Design Philosophy

Bungas follows a component architecture that maximizes the benefits of Tailwind Variants while
separating styling from logic. This approach offers:

* **Improved Readability** - Cleaner component files with variant definitions clearly separated
* **Enhanced Maintainability** - Style variants can be modified without affecting component logic
* **Better Collaboration** - Designers can work on style variants while developers focus on functionality
* **Simplified Theming** - Create theme variants with minimal code duplication
* **Consistent API** - Uniform pattern for handling component variations across the library

This architecture creates a more sustainable and flexible codebase that scales with your project's complexity.

## FAQ

### Is Bungas open source?
Bungas is licensed under a dual license: [Apache License 2.0](https://www.tldrlegal.com/license/apache-license-2-0-apache-2-0)
and [MIT license](https://www.tldrlegal.com/license/mit-license). This means you
can choose either license based on your project's needs. The dual licensing
provides flexibility for both commercial and open-source projects. Copyrights
in the project are retained by their contributors.

### How does Bungas differ from shadcn/ui?
The key difference is our integration of Tailwind Variants. While `shadcn/ui`
uses [Class Variance Authority](https://cva.style/docs), Bungas leverages
Tailwind Variants to provide a more powerful, type-safe API for component styling.
This allows for more complex variant combinations, better handling of responsive
styles, and cleaner component code. Additionally, our separation of styling
from component logic creates a more maintainable architecture.

### What benefits does Tailwind Variants provide?
Tailwind Variants enhances the Tailwind experience by providing a first-class variant API.
This means you can define component variants (like size, color, state) in a structured
way with TypeScript support. It efficiently handles class merging, prevents style
conflicts, and enables slot-based styling for complex components. The result is
cleaner code, better developer experience, and more maintainable styling.

### Why does Bungas separate CSS from component files?
Separating CSS from component logic improves maintainability and readability of
the codebase. This approach makes it easier to update styles without touching
component logic, simplifies debugging of styling issues, and creates a cleaner
development experience. When combined with Tailwind Variants, this separation
becomes even more powerful, allowing for sophisticated styling patterns without
cluttering component files.

### Can I use Bungas with my existing Tailwind setup?
Yes! Bungas is designed to work seamlessly with existing Tailwind CSS projects.
Our components use Tailwind Variants which is compatible with standard Tailwind
configurations. You can gradually adopt Bungas components alongside your
existing UI elements and even leverage Tailwind Variants for your custom components.

### Can I use Bungas with Tailwind CSS v3?
Bungas is primarily designed and optimized for Tailwind CSS v4. While it can be used with
Tailwind CSS v3, some adjustments may be necessary, and you might encounter styling issues
due to breaking changes introduced in Tailwind CSS v4. For the best experience and to avoid
potential styling problems, we recommend using Bungas with Tailwind CSS v4. If you're using
Tailwind CSS v3, be prepared to make some adaptations to ensure proper component rendering.

### Is Bungas suitable for production applications?
Absolutely. Bungas is built with production use cases in mind. Our components
are thoroughly tested for accessibility, performance, and cross-browser compatibility.
Even better, Bungas components are designed to be highly customizable. The use of Tailwind Variants
also ensures consistent styling behavior across different environments and browsers.

## Acknowledgements

Bungas is a thoughtful blend of design philosophies from two exceptional UI libraries:

* **[Tremor](https://tremor.so/)**: Many of Bungas's foundational components draw heavy inspiration from Tremor's well-crafted designs. We've reimagined these components with our own architectural approach while respecting Tremor's excellent work.

* **[shadcn/ui](https://ui.shadcn.com/)**: Bungas incorporates design patterns and component structures from shadcn/ui, adapting them to fit seamlessly with the Bungas ecosystem.

Key differences that set Bungas apart include:

* Separation of style files for each component, improving organization and customization
* Use of [Lucide icons](https://lucide.dev/) instead of Remix Icons (used by Tremor)
* Integration of Tailwind Variants for enhanced styling capabilities
* A carefully curated blend of design elements from both inspirational libraries

We're grateful to these projects for their contributions to the React and Tailwind ecosystem, and for providing the foundation upon which Bungas builds its unique identity.

## Join the Community

Bungas is more than just a component library - it's a growing community of developers building better user interfaces with modern tools like Tailwind Variants. Connect with us:

* Star our [GitHub repository](https://github.com/riipandi/Bungas)
* Follow us for updates and announcements
* Share your projects built with Bungas

We're excited to see what you create!
