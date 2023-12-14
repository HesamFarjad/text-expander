# text-expander
The provided code is a React component that creates a text expander, a UI element that allows users to show or hide a portion of text. 

Here's a step-by-step description of what the code is doing:
* 		Import Statements:
    * The code imports the useState hook from the React library to manage state in functional components.
    * It also imports styles from an external stylesheet ("./index.css"), which is assumed to contain styling for the components.
* 		App Component:
    * The App component is the main component that renders three instances of the TextExpander component with different configurations.
* 		TextExpander Component:
    * The TextExpander component is a reusable component that takes various props to customize its behavior and appearance.
        * Props include:
        * children: The text content that can be expanded or collapsed.
        * collapsedNumWords: The number of words to display when the text is collapsed.
        * expandButtonText: The text to display on the button when the text is collapsed.
        * collapseButtonText: The text to display on the button when the text is expanded.
        * buttonColor: The color of the button.
        * expanded: The initial state of the text (expanded or collapsed).
        * className: Additional styling class for the component.
* 		State Management:
    * The TextExpander component uses the useState hook to manage the state of whether the text is currently expanded or collapsed.
* 		Display Text:
    * The displayText variable is used to determine what text should be displayed based on whether the text is expanded or collapsed. If collapsed, it shows only a portion of the text with an ellipsis.
* 		Button Styling:
    * The buttonStyle object defines the styling for the button, including its appearance and color.
* 		Rendering:
    * The TextExpander component renders a div containing the display text and a button.
    * The button's text and appearance change dynamically based on the current state. It toggles between showing more or less text when clicked.
* 		Usage in App Component:
    * The App component renders three instances of the TextExpander component with different content and configurations to demonstrate its usage.
In summary, the code provides a flexible and reusable React component (TextExpander) that allows users to toggle between an expanded and collapsed view of text, with customizable button text and styling. The App component demonstrates the usage of this text expander with different pieces of text and configurations.



<img width="1440" alt="Screenshot 2023-12-14 at 18 52 57" src="https://github.com/HesamFarjad/text-expander/assets/81914229/8f5e1751-3392-4c3b-a21d-21bdf0745984">
<img width="1440" alt="Screenshot 2023-12-14 at 18 53 12" src="https://github.com/HesamFarjad/text-expander/assets/81914229/a11775ab-19a5-4d58-a43d-5adeec20fb8b">
