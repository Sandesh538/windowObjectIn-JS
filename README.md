# Subobjects of the Window Object in JavaScript

<p align="center">
  <img src="/omshingare.jpg" alt="my image">
</p>

<div align="center">  
  <p>📘 Welcome to the documentation of various subobjects within the <code>window</code> object in JavaScript.</p>
  <p>🌐 The <code>window</code> object is a global entity representing the browser window or tab, offering a myriad of functionalities for web development.</p>
</div>

## Table of Contents

- 📖 [Introduction](#introduction)
- 📜 [List of Subobjects](#list-of-subobjects)
- 💡 [Usage](#usage)
- 🤝 [Contributing](#contributing)
- 📜 [License](#license)
- 📬 [Contact](#contact)

## Introduction

🌟 The `window` object is a cornerstone in web browsers, serving as a container for diverse subobjects, each tailored for specific roles. Gaining insights into these subobjects can significantly augment your prowess in crafting dynamic and interactive web applications.

## List of Subobjects

- [window (global object)](https://developer.mozilla.org/en-US/docs/Web/API/Window)
  - [document](https://developer.mozilla.org/en-US/docs/Web/API/Document): Represents the DOM of the current web page.
  - [console](https://developer.mozilla.org/en-US/docs/Web/API/Console): Provides methods for interacting with the browser console.
  - [localStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage): Allows data storage on the client side.
  - [sessionStorage](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage): Similar to `localStorage`, but data is session-specific.
  - [navigator](https://developer.mozilla.org/en-US/docs/Web/API/Navigator): Provides information about the user's browser and system.
  - [location](https://developer.mozilla.org/en-US/docs/Web/API/Location): Contains information about the current URL.
  - [history](https://developer.mozilla.org/en-US/docs/Web/API/History): Allows manipulation of the browser's history.
  - [screen](https://developer.mozilla.org/en-US/docs/Web/API/Screen): Provides information about the user's screen.
  - [frames](https://developer.mozilla.org/en-US/docs/Web/API/Window/frames): Refers to the frames within the current window.
  - [parent](https://developer.mozilla.org/en-US/docs/Web/API/Window/parent): Refers to the parent window or frame.
  - [top](https://developer.mozilla.org/en-US/docs/Web/API/Window/top): Refers to the top-level browsing context.
  - [self](https://developer.mozilla.org/en-US/docs/Web/API/Window/self): Refers to the current browsing context.
  - [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest): Used for making HTTP requests.
  - [AudioContext](https://developer.mozilla.org/en-US/docs/Web/API/AudioContext): Handles audio processing and synthesis.
  - [Video](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video): Represents a video element for playback.
  - [WebRTC](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API): Enables real-time communication via web browsers.
  - [WebSocket](https://developer.mozilla.org/en-US/docs/Web/API/WebSocket): Provides full-duplex communication channels over a single TCP connection.
  - [Math](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math): Provides mathematical functions and constants.
  - [Date](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date): Allows working with dates and times.
  - [Object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object): The base object for all JavaScript objects.
  - [Array](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array): Represents a collection of elements in a specific order.
  - [String](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String): Represents a sequence of characters.
  - [Number](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Number): Represents a numeric value.
  - [Boolean](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean): Represents a true or false value.
  - [Error](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Error): Represents an error object.
  - [Function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function): Represents a function in JavaScript.
  - [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise): Represents a value that might be available in the future.
  - [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON): Provides methods for working with JSON data.
  - [Map](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map): Represents a collection of key-value pairs.
  - [Set](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Set): Represents a collection of unique values.
  - [Symbol](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol): Represents a unique and immutable value.
  - [RegExp](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp): Represents a regular expression pattern.
  - [Image](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img): Represents an image element for display.
  - [Audio](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/audio): Represents an audio element for playback.
  - [Worker](https://developer.mozilla.org/en-US/docs/Web/API/Worker): Enables running JavaScript in a background thread.
  - [Intl](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Intl): Provides internationalization support for formatting and parsing.
  - [Blob](https://developer.mozilla.org/en-US/docs/Web/API/Blob): Represents binary data.
  - [DataView](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DataView): Represents a low-level view of binary data.
  - [Event](https://developer.mozilla.org/en-US/docs/Web/API/Event): Represents an event that occurs in the DOM.
  - [EventTarget](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget): Represents an object that can receive events.
  - [File](https://developer.mozilla.org/en-US/docs/Web/API/File): Represents a file selected by the user.
  - [URL](https://developer.mozilla.org/en-US/docs/Web/API/URL): Provides methods for working with URLs.
  - [URLSearchParams](https://developer.mozilla.org/en-US/docs/Web/API/URLSearchParams): Represents query parameters in a URL.
  - [Crypto](https://developer.mozilla.org/en-US/docs/Web/API/Crypto): Provides cryptographic functionality.
  - [GlobalEventHandlers](https://developer.mozilla.org/en-US/docs/Web/API/GlobalEventHandlers): Represents an object that can handle events globally.
  - [Selection](https://developer.mozilla.org/en-US/docs/Web/API/Selection): Represents the user's text selection in a document.
  - [KeyboardEvent](https://developer.mozilla.org/en-US/docs/Web/API/KeyboardEvent): Represents a keyboard event.
  - [MouseEvent](https://developer.mozilla.org/en-US/docs/We  - [RTCDataChannel](https://developer.mozilla.org/en-US/docs/Web/API/RTCDataChannel): Represents a channel for sending data over WebRTC.
  - [RTCPeerConnection](https://developer.mozilla.org/en-US/docs/Web/API/RTCPeerConnection): Represents a connection between two peers in WebRTC.
  - [Performance](https://developer.mozilla.org/en-US/docs/Web/API/Performance): Provides timing and performance-related information.
  - [IndexedDB](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API): Provides a local database for storing structured data.
  - [Intl.Collator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Collator): Provides string comparison with language-sensitive collation.
  - [Intl.DateTimeFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/DateTimeFormat): Provides localized date and time formatting.
  - [Intl.NumberFormat](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/NumberFormat): Provides localized number formatting.
  - [TextDecoder](https://developer.mozilla.org/en-US/docs/Web/API/TextDecoder): Decodes text from binary data using a specified encoding.
  - [TextEncoder](https://developer.mozilla.org/en-US/docs/Web/API/TextEncoder): Encodes text into binary data using a specified encoding.
  - [WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly): Represents WebAssembly modules and instances.
  - [ServiceWorker](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API): Enables the use of background scripts to handle network requests.
  - [SpeechRecognition](https://developer.mozilla.org/en-US/docs/Web/API/SpeechRecognition): Enables speech recognition capabilities.
  - [SpeechSynthesis](https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis): Enables speech synthesis capabilities.
  - [Clipboard](https://developer.mozilla.org/en-US/docs/Web/API/Clipboard): Provides access to the clipboard for copying and pasting.
  - [MediaStream](https://developer.mozilla.org/en-US/docs/Web/API/MediaStream): Represents a stream of media content.
  - [FileSystem](https://developer.mozilla.org/en-US/docs/WebAPI/FileSystem): Represents the file system for web applications.
  - [EventSource](https://developer.mozilla.org/en-US/docs/Web/API/EventSource): Represents a connection to a server-sent events stream.
  - [Camera](https://developer.mozilla.org/en-US/docs/WebAPI/Camera): Represents a camera for capturing video or images.
  - [AudioTrack](https://developer.mozilla.org/en-US/docs/WebAPI/AudioTrack): Represents an audio track in a media stream.
  - [VideoTrack](https://developer.mozilla.org/en-US/docs/WebAPI/VideoTrack): Represents a video track in a media stream.
  - [MediaRecorder](https://developer.mozilla.org/en-US/docs/WebAPI/MediaRecorder): Records media streams, such as audio and video.
  - [HTMLCanvasElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement): Represents a canvas element for 2D rendering.
  - [HTMLImageElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLImageElement): Represents an image element for display.
  - [HTMLAudioElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLAudioElement): Represents an audio element for playback.
  - [HTMLVideoElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLVideoElement): Represents a video element for playback.
  - [HTMLIFrameElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLIFrameElement): Represents an inline frame element for embedding other documents.
  - [HTMLFormElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement): Represents a form element for collecting user input.
  - [HTMLInputElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLInputElement): Represents an input element for user data entry.
  - [HTMLTextAreaElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLTextAreaElement): Represents a textarea element for multiline text input.
  - [HTMLSelectElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLSelectElement): Represents a select element for dropdown menus.
  - [HTMLOptionElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLOptionElement): Represents an option element within a select element.
  - [HTMLButtonElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLButtonElement): Represents a button element for user interaction.
  - [HTMLAnchorElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLAnchorElement): Represents an anchor element for hyperlinks.
  - [HTMLMediaElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMediaElement): Represents a base class for media-related elements (audio, video).
  - [HTMLScriptElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLScriptElement): Represents a script element for executing JavaScript code.
  - [HTMLStyleElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLStyleElement): Represents a style element for embedding CSS styles.
  - [HTMLLinkElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLLinkElement): Represents a link element for external resources (CSS, etc.).
  - [HTMLMetaElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLMetaElement): Represents a meta element for document metadata.
  - [HTMLTitleElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLTitleElement): Represents a title element for the document's title.
  - [HTMLHeadElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLHeadElement): Represents the head element containing metadata.
  - [HTMLDivElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLDivElement): Represents a division element for grouping content.
  - [HTMLSpanElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLSpanElement): Represents a span element for inline content styling.
  - [HTMLParagraphElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLParagraphElement): Represents a paragraph element for text grouping.
  - [HTMLHeadingElement](https://developer.mozilla.org/en-US/docs/Web/API/HTMLHeadingElement): Represents heading elements (h1 to h6) for headings.
  - [TouchEvent](https://developer.mozilla.org/en-US/docs/Web/API/TouchEvent): Represents a touch event on a touch-enabled device.
  - [WebGLRenderingContext](https://developer.mozilla.org/en-US/docs/Web/API/WebGLRenderingContext): Provides access to the WebGL graphics rendering context.
  - [WebGL2RenderingContext](https://developer.mozilla.org/en-US/docs/Web/API/WebGL2RenderingContext): Provides access to the WebGL 2 graphics rendering context.
  - [RTCDataChannel](https://developer.mozilla.org/en-US/docs/Web/API/RTCDataChannel): Represents a



## Usage

✨ Each subobject within the `window` object boasts a unique collection of properties and methods, empowering you to engage with distinct facets of web development. For further details, consult the corresponding subobject sections.

## Contributing

🤝 Your contributions are highly valued! If you identify any inaccuracies or desire to enrich information about a specific subobject, please consider submitting a pull request.

## License

📄 This repository is licensed under the [MIT License](LICENSE). You are free to utilize and distribute the content as you see fit.

## Contact

📧 Should you have any queries or suggestions, don't hesitate to get in touch:

- **Name:** Om Shingare
- **Email:** omshingare@duck.com
- **GitHub:** [@ShingareOm](https://github.com/ShingareOm)
