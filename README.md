# Tab Category Slider with Active Tabs and Cards + Show More Button (Vue 3)

This Vue 3 component creates an interactive course catalog with category tabs and course cards. It features a responsive design and dynamic content loading.

## Features

- **Category Tabs**: Horizontal scrollable tabs for different course categories.
  - Responsive design with left/right navigation arrows.
  - Active tab highlighting.

- **Course Cards**: Display course information in a grid layout.
  - Shows course image, title, subtitle, pricing, and a "View Details" link.
  - Responsive grid adjusts based on screen size.

- **Dynamic Content Loading**: 
  - Initial load shows a limited number of cards.
  - "Show More" button to expand the view and display additional courses.
  - "Show Less" option to collapse back to the initial view.

- **Responsive Design**:
  - Adapts to various screen sizes from mobile to desktop.
  - Adjusts the number of visible cards based on screen width.

- **Smooth Animations**:
  - Transition effects when showing/hiding course cards.

- **Additional Navigation**:
  - "View All" button for accessing the complete course catalog.

## Sample Previews

### Active Tab Preview
![Active Tab Preview](https://github.com/AroshaRavishan/Common-card-with-active-tab-slider-cards-with-Show-more-Buttons-Vue3/blob/main/active%20tab%20preview.png)

### Show Less Preview
![Show Less Preview](https://github.com/AroshaRavishan/Common-card-with-active-tab-slider-cards-with-Show-more-Buttons-Vue3/blob/main/show%20less%20preview.png)

### Show More Preview
![Show More Preview](https://github.com/AroshaRavishan/Common-card-with-active-tab-slider-cards-with-Show-more-Buttons-Vue3/blob/main/show%20more%20preview.png)


## Component Structure

1. **Category Slider**: Uses Splide.js for smooth horizontal scrolling of category tabs.
2. **Course Cards**: Custom component to display individual course information.
3. **Show More/Less**: Toggle functionality to expand or collapse the course list.
4. **Responsive Behavior**: Utilizes Vue's reactive properties and computed values to adjust layout and content based on screen size.

## Styling

- Custom clip-path for a unique section shape.
- Tailwind CSS classes for responsive design and styling.
- Custom transitions for smooth card appearance/disappearance.

## Usage

This component is designed to be part of a larger Vue 3 application. It requires additional components like `PrimaryButton`, `SecondaryButton`, and `CourseCard`, which should be implemented separately.

To use this component, import it into your Vue 3 application and include any necessary props or data management as per your application's architecture.
