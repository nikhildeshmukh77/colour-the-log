# ConsoleLogColorizer

ConsoleLogColorizer is a lightweight Node.js package designed to enhance developer productivity by providing easy-to-use functions for logging messages to the browser console in eye-catching colors. With ConsoleLogColorizer, you can quickly identify and differentiate important log messages, errors, warnings, and more, improving the debugging and troubleshooting process.

## Features

- **Simple Integration:** Easily integrate ConsoleLogColorizer into your TypeScript projects with minimal configuration.
- **Colorful Logging:** Enhance the readability of your console logs by logging messages in red, blue, or highlighted yellow colors.
- **Customizable:** Customize the color and style of log messages to suit your preferences and improve visual distinction.
- **Developer Friendly:** Designed with developers in mind, ConsoleLogColorizer offers intuitive and straightforward functions for logging messages to the browser console.
- **TypeScript Support:** Built using TypeScript for enhanced type safety and developer experience.

## Usage

```typescript
import { Log } from 'colour-the-log';

// Log messages in red color
Log.danger('This is an important error message');

// Log messages in highlighted yellow color
Log.info('This is an informative message');

// Log messages in blue color
log.success('This is a success message');
