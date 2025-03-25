# System Patterns: Entangled Packets

## Architecture
- **Static Site Generation**: Using Astro's static site generation for optimal performance
- **Content-driven Structure**: Organizing the system around content collections
- **Composable Components**: Building reusable, self-contained UI components
- **Responsive Layouts**: Implementing mobile-first design patterns
- **Asset Optimization**: Automating image and resource optimization

## Technical Decisions
- **Astro Framework**: Selected for its content-focused approach and performance
- **Tailwind CSS**: Chosen for efficient implementation of minimal design
- **Markdown Content**: Using Markdown files with frontmatter for content management
- **Component Islands**: Leveraging Astro's partial hydration for interactive elements
- **Static-first Approach**: Prioritizing static generation with minimal client-side JavaScript

## Design Patterns
- **Component-based Architecture**: Organizing UI into reusable components
- **Content Collections**: Grouping related content with consistent schemas
- **Utility-first CSS**: Using Tailwind's utility classes for styling
- **Progressive Enhancement**: Building core functionality that works without JavaScript
- **Responsive Breakpoints**: Implementing consistent responsive design patterns

## Component Relationships
- **Layout Components**: Base templates that define page structure
- **UI Components**: Reusable interface elements (buttons, cards, navigation)
- **Content Components**: Specialized components for rendering article content
- **Page Components**: Top-level components representing full pages
- **Data Flow**: Content flows from Markdown through collection APIs to page templates
