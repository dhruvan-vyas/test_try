**dvs_printf v1.0 Release Note**

Initial Release of dvs_printf
We are thrilled to announce the initial release of dvs_printf, a dynamic Python module designed to enhance console output with engaging animation styles. This release includes a range of features and improvements to ensure a seamless user experience.

**Key Features**
1. printf Function:

    * Supports any data type, including custom objects.
    * Offers various animation styles such as typing, async, and headline animations to improve readability and user engagement.

2. init Method:

    * Provides dynamic initialization, ensuring consistent formatting and animation behavior across different parts of your application.

3. showLoding Function:

    * Implements a loading bar using threading, suitable for indicating progress during time-consuming tasks.

4. list_of_str Function:

    * Converts different data types into a list of strings, allowing for easy integration with animated print functions.

**New Features**
* Async Style:
    * Introduces a new animation style named "Async" that allows multiple lines to animate simultaneously, providing a more dynamic and visually appealing output.
    * Supports the syntax async <int>, enabling control and animation of specific sets of lines for greater flexibility and customization.

**Bug Fixes**
* Line Wrapping:
    * Fixed issues with lines exceeding terminal width. Lines larger than the terminal width are now split and moved to a new line for better handling and display.

**Improvements**
* Stability Enhancements:
    * Improved overall stability to prevent crashes and unexpected behavior during usage.
* Code Optimization:
    * Optimized the codebase for better performance and efficiency, reducing execution time and resource usage.

**Additional Features**
* Style Naming Error Detection:
    Added a feature to detect and alert users to naming errors in styles, improving the development experience.

* Handling Invalid Values:
    Implemented functionality to handle unexpected values and keywords, ensuring smooth operation with suitable default values.


**Use Cases**
* **User Interaction:** Enhance console applications with visually appealing output.
* **Progress Visualization:** Use loading bars and animations to indicate progress.
* **Highlighting Information:** Make important information stand out with animations.
* **Debugging and Monitoring:** Facilitate better understanding and monitoring of processes through animated outputs.

For detailed usage instructions and examples, please refer to the [README](https://github.com/dhruvan-vyas/dvs_printf?tab=readme-ov-file#dvs_printf) on the GitHub repository.

We hope you enjoy the new features and improvements in this release. Your feedback and contributions are highly appreciated to make dvs_printf even better.

