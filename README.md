# Media Scout

Media Scout is a local HTML-based application designed to make finding photos, GIFs, and videos easier through a simple, easy-to-navigate interface.

The application allows users to choose a media type and a supported website, then search that source for relevant content.

For example, selecting **Photos** and **Pixabay** will search Pixabay for photos related to the user's search query.

## Features

* Search for photos, GIFs, and videos
* Choose which supported website to search
* Select the type of media you are looking for
* Simple and easy-to-navigate interface
* Runs locally in your web browser
* No installation required

## API Keys Required

Media Scout uses APIs from supported third-party websites to retrieve search results.

**API keys are required for the application to function properly.**

To set up Media Scout:

1. Create an account with the API provider you want to use.
2. Create an API key through that provider.
3. Add your API key to the appropriate location in the Media Scout source code.
4. Save the changes.

The API keys used during development are **not included in this repository**.

**Do not upload your personal API keys to GitHub.**

## Running Media Scout

1. Download or clone the repository from GitHub.
2. Add the required API keys.
3. Open the `index.html` file in your web browser.
4. Start searching for media.

## How It Works

Media Scout uses the search options selected by the user to determine which source and media type should be searched.

For example:

**Photos + Pixabay + "cars"**

Media Scout will search the selected source for photos related to "cars."

## Disclaimer

Media Scout is a search and discovery tool and does not host or claim ownership of third-party content.

Content is retrieved from third-party websites and remains subject to their respective terms of service, licenses, and copyright policies.

Users are responsible for ensuring that any content they download or use is permitted under the applicable license or terms.

## Technologies

* HTML
* CSS
* JavaScript

## License

This project is licensed under the MIT License.
