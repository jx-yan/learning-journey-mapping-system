<h1 align="center">Learning Journey Mapping System</h1>

<p align="center">A personal learning journey tracker that could guide staff on the courses they could take either from the LMS or in physical classes to prepare them for the next position or in a different area within the organisation.</p>
 
## Getting Started
 
- Install [NodeJS](https://nodejs.org/en/) and [yarn](https://yarnpkg.com/) before installing project

1. Download and unzip project
2. Run the following command on CMD in project directory
```
yarn install
yarn start
yarn dev
```

## Functionalities
### Staff
- **View Jobs** - View all available jobs on LJPS
- **Set and View Learning Journeys** - Set and view learning journeys by setting jobs as learning goals
- **View Skills of Jobs and Courses** - View skills required in jobs and skills acquired in courses
- **Add/Remove Courses to Learning Journeys** - Add or Remove courses added to learning journeys
- **View eligible courses to add to learning journeys** - View courses that can be added to acquire skills required in learning journeys
- **Add/Remove Learning Journeys** - Add or Remove learning journeys

 
### Human Resources
- **View and Edit Jobs** - View and edit all jobs on LJPS
- **View and Edit Skills** - View and edit all skills on LJPS
- **Activate/Disable Jobs and Skills** - View all skills and jobs to activate or disable on LJPS
- **Add/Remove Skills from Jobs and Courses** - Add or Remove skills required in jobs and skills acquired in courses
- **Add/Remove Courses to Learning Journeys** - Add or Remove courses added to learning journeys
- **Filter Courses by Skills** - View and filter courses by skills

## Frontend Frameworks and Libraries
- [Nuxt 3](https://v3.nuxtjs.org/)
- [Tailwind CSS](https://tailwindcss.com/docs/configuration)
- [DaisyUI](https://daisyui.com/)

## Backend Frameworks and Libraries
- [Express](https://expressjs.com/)
- [NodeJS](https://nodejs.org/en/)
- [Planetscale](https://planetscale.com/)
- [Prisma](https://www.prisma.io/docs/)
- [Jest](https://jestjs.io/)

## Data Storage
- PlanetScale RDMS, A cloud-hosted mySQL compatible database

## CI pipeline 
- building, testing with unit test and code linting to check on every push to develop, master branch and pull request with Bitbucket Pipelines

## Endpoints
- CRUD for Courses, Journey, Jobs, Staff, Skills, Depts
