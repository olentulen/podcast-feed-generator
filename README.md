## Podcast Feed Generator

This Node.js script is designed to streamline the process of generating RSS feeds for podcasts. It offers a flexible and easy-to-use solution for podcasters looking to host and distribute their content efficiently. The script scans a specified directory for audio files and dynamically creates an RSS feed that can be used with popular podcasting platforms and aggregators.

### Features

- **Customizable Feed Details**: Easily set podcast titles, descriptions, and other metadata to personalize your feed.
- **Wide Range of Audio Formats**: Supports various audio formats including MP3, MP4, M4A, and M4B, ensuring compatibility with diverse content.
- **Automatic File Detection**: Scans the specified directory and automatically includes all valid audio files in the RSS feed.
- **Simple Integration**: Designed to be integrated into existing podcast hosting setups, making it straightforward to adopt and use.

### Acknowledgements

This project was inspired by the PHP script for generating RSS feeds by @vsoch, available [here](https://gist.github.com/vsoch/4898025919365bf23b6f). After using their script and benefiting from its functionality, I was motivated to create a similar tool using JavaScript to provide a more accessible and adaptable solution for the podcasting community. I extend my heartfelt thanks to @vsoch for their original idea and work, which laid the foundation for this project.

### Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/olentulen/podcast-feed-generator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd podcast-feed-generator
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Run the script, specifying the path to your audio files:
    ```bash
    node src/generateFeeds.js /path/to/audio/files
    ```

For detailed usage and configuration options, please refer to the [documentation](https://github.com/olentulen/podcast-feed-generator/blob/main/README.md).

### Contribution

Contributions to the project are welcome! If you have suggestions for improvements or encounter any issues, please feel free to open an issue or submit a pull request.

### License

This project is licensed under the [MIT License](https://github.com/olentulen/podcast-feed-generator/blob/main/LICENSE) - see the LICENSE file for details.

