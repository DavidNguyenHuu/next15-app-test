# Next.js Feature Test Application

This project is a basic Next.js application designed to test various rendering features, compare loading performance with and without Turbopack, and showcase the integration of shadcn UI components.

## Features

- Next.js 15.0.1 with React 19 RC
- Turbopack integration for faster development builds
- shadcn UI components for a modern, customizable interface
- Server-side rendering demonstration with a users list
- Basic routing and page structure

## Getting Started

1. Clone the repository
2. Install dependencies:

npm install
# or
yarn install
# or
pnpm install

3. Run the development server:

npm run dev
# or
yarn dev
# or
pnpm dev

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `app/`: Contains the main application pages and components
- `components/`: Reusable UI components, including shadcn components
- `lib/`: Utility functions and shared code
- `public/`: Static assets

## Key Files

- `app/page.tsx`: The main entry point of the application
- `app/users/page.tsx`: Demonstrates server-side rendering with a user list
- `app/components/ProductCard.tsx`: An example client-side component
- `tailwind.config.ts`: Tailwind CSS configuration, including shadcn theme settings

## Testing Turbopack

This project is configured to use Turbopack in development. To compare performance:

1. Run with Turbopack (default):

npm run dev

2. Run without Turbopack:
   Edit the `package.json` file and modify the `dev` script:

"dev": "next dev",

Then run:

npm run dev

Compare the startup and refresh times between the two configurations.

## Customization

The project uses shadcn UI components, which can be easily customized. Refer to the `tailwind.config.ts` file for theme settings and the `components/ui/` directory for individual component styles.

## Learn More

To learn more about the technologies used in this project, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://reactjs.org/docs/getting-started.html)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [shadcn UI](https://ui.shadcn.com/)

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your feedback and improvements are welcome!

## License

This project is open-source and available under the MIT License.