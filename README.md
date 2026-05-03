# 📚 BookLib

A comprehensive, full-stack library management application built with **Next.js**, **Tailwind CSS**, and **MongoDB**. This project provides a robust platform for browsing books, user authentication, and profile management with a sleek, modern UI.

## website Live Demo: [https://category-a8-mango.vercel.app/](https://category-a8-mango.vercel.app/)

## 🚀 Features

- **Modern & Responsive UI**: Built with Tailwind CSS v4 and DaisyUI, featuring a beautiful homepage with banners, featured books, and testimonials.
- **Authentication System**: Secure login and registration using [Better Auth](https://better-auth.com/), supporting both Email/Password and **Google OAuth**.
- **Database Integration**: Powered by MongoDB and Mongoose for reliable data storage.
- **Form Handling & Validation**: Uses React Hook Form and Zod for robust client-side validation.
- **Modular Components**: Clean architecture with reusable components for Hero, Marquee, Books, and more.
- **Real-time Notifications**: Integrated React Hot Toast for instant user feedback.

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) & [DaisyUI v5](https://daisyui.com/)
- **Authentication**: [Better Auth](https://better-auth.com/) (MongoDB Adapter)
- **Database**: [MongoDB](https://www.mongodb.com/) & [Mongoose](https://mongoosejs.com/)
- **Forms & Validation**: [React Hook Form](https://react-hook-form.com/) & [Zod](https://zod.dev/)
- **Icons**: [Lucide React](https://lucide.dev/) & [React Icons](https://react-icons.github.io/react-icons/)
- **Components**: [Swiper](https://swiperjs.com/) for interactive carousels

## 📦 Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js (v18.17 or higher)
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd book
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root of the project and add the following keys:

   ```env
   # Better Auth Configuration
   BETTER_AUTH_SECRET="your-secret-key"
   BETTER_AUTH_URL="http://localhost:3000"

   # MongoDB Connection
   MONGODB_URI="your-mongodb-connection-string"

   # Google OAuth (Optional)
   GOOGLE_CLIENT_ID="your-google-client-id"
   GOOGLE_CLIENT_SECRET="your-google-client-secret"
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 📁 Project Structure

- `/app`: Next.js App Router pages and API routes.
- `/components`: Reusable UI components (Hero, Marquee, Footer, etc.).
- `/lib`: Utility functions, database connections, and authentication configurations.
- `/public`: Static assets like images and fonts.

## 🚢 Deployment

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com/new). Check out the [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.

## 🤝 Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## 🙏 Acknowledgements

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [DaisyUI](https://daisyui.com/)
- [Better Auth](https://better-auth.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [React Hook Form](https://react-hook-form.com/)
- [Zod](https://zod.dev/)
- [Lucide React](https://lucide.dev/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Swiper](https://swiperjs.com/)
- [Vercel](https://vercel.com/)

 <br/>
Feel free to explore the codebase and contribute to making BookLib even better!
