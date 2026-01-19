# tbd-book-proj

Software with friends!

### Prerequisites

- Node.js (v20 or higher)

### Installation

1.  **Clone the repo**
    ```bash
    git clone https://github.com/haha-computer/tbd-book-proj.git
    cd tbd-book-proj
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Create .env file**
    ```bash
    cp .env.example .env
    ```

### Running Locally

To start the development server with hot-reloading:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment

Deployment is automated via **Fly.io**.

- **Automatic**: Pushing to the `main` branch triggers a GitHub Action to deploy the latest version.
- **Manual**: You can also deploy using the Fly CLI if needed: `fly deploy`.

## Project Structure

- `server.js`: Main Express application entry point.
- `public/`: Static files (if added).
- `.github/workflows`: CI/CD configuration.
