# GitHub Repo Card Generator

GitHub Repo Card Generator is a feature-rich application designed for effortlessly creating SVG cards that showcase GitHub repositories.

Repository cards can be generated using the user interface and entering the GitHub username and repository name.  
The card colors can be customized by clicking on the color pickers and selecting a color.

The generated SVG card will be displayed along with BBCode, HTML, and Markdown quick copy codes for embedding the card.

## Features

- Generates SVG cards for GitHub repositories with customizable colors and options
- Lightweight responsive UI with quick copy codes (BBCode, HTML, Markdown) for embedding the output SVG card
- Configurable cache supported by SQLite
- Optionally limits the number of requests per hour to the GitHub API

## Screenshots

![GitHub Repo Card Generator Interface](https://i.imgur.com/PikixRc.png)


## Setup

### Local Setup

1. Clone the repository

```bash
git clone https://github.com/yourusername/github-repo-card-generator.git
```

2. Install dependencies
```bash
npm install
```

3. Rename `.env.example` in the root directory to `.env` add your GitHub token and configuration:

```makefile
GITHUB_TOKEN=your_github_token
```

4. Start the server
```bash
npm start
```

The server will start running at `http://localhost:3000`.


## Usage
Navigate to `http://localhost:3000` in your web browser (or your public URL if configured).
Enter the GitHub username and repository name in the provided fields, customize the card colors if desired, and click "Generate" to generate an SVG card for the repository.

The generated SVG card will be displayed along with BBCode, HTML, and Markdown quick copy codes for embedding the card.

The repository must be public.
