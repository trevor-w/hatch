## Step 1: Pull the following repo under the same directory
`https://github.com/trevor-w/hatch`
`https://github.com/trevor-w/hatch-frontend`
`https://github.com/trevor-w/hatch-backend`

## Step 2: Run docker compose
`docker compose up --build`

** This command may take some time

The docker compose file contain 4 images
- Frontend React app of the assessment
- Backend NodeJS app of the assessment
- Mongodb image from the official docker site
- Redoc image to host the openapi document

## Step 3: Visit localhost:8080 to see the result
`localhost:8080`
