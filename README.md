
# YouTube Liked Videos PDF Generator

Generate a PDF report of your liked YouTube videos with this Python script. This project utilizes the YouTube Data API and ReportLab to create a PDF document that lists your liked videos with details such as title, description, channel, and clickable links.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)


## Installation

1. Clone this repository to your local machine using `git clone`.

2. Install the required Python libraries using pip:

   ```bash
   pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib reportlab
   ```
  - Set up your YouTube Data API credentials by following the steps in the Google API Python Client documentation.

  - Create a `client_secret.json` file with your API credentials.

## Usage

Run the script:
In order to run in non-Jupyter platform, convert file named 'python generate_pdf' to py extension and then:
``` bash
python generate_pdf.py
```
- This will fetch your liked videos from YouTube and generate a PDF report.

- The generated PDF will be saved as liked_videos_report.pdf in the same directory.

## Configuration
- You need to configure the client_secret.json file with your YouTube Data API credentials. Ensure that you have the necessary permissions to access your liked videos.

## Contributing
- Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.
