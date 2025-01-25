# Vartalaap 🚀

Vartalaap is a video conferencing platform built with a modern tech stack including Next.js, TypeScript, TailwindCSS, Clerk for authentication, GetStream.io for real-time video magic, and shadcn/ui for components 🪄

## Live Demo 🎉

Try it out live: [Vartalaap]([https://Vartalaap.vercel.app/](https://vartalaap-ochre.vercel.app/))

## Key Features ✨

- 🔐 **Authentication**: Secure login with Clerk, including social sign-ons and traditional methods.
- 🎥 **New Meeting**: Easily start a new meeting, configuring camera and microphone settings before joining.
- 🎛️ **Meeting Controls**: Full control over meeting aspects, including recording, emoji reactions, screen sharing, sound adjustments, grid layout, participant list view, and individual participant management.
- 🚪 **Exit Meeting**: Leave a meeting or end it for all participants.
- 📅 **Schedule Future Meetings**: Schedule meetings in advance and access them on the 'Upcoming Meetings' page.
- 📜 **Past Meetings List**: View details and metadata of previous meetings.
- 📼 **View Recorded Meetings**: Access recordings of past meetings.
- 🔗 **Personal Room**: Instant meetings with a unique link, shareable with others.
- 🌐 **Join Meetings via Link**: Join meetings created by others using a shared link.
- 📱 **Responsive Design**: Optimized for all devices, ensuring a seamless experience across different screen sizes and resolutions.

## Technologies Used 🛠️

- **Next.js**: Framework for server-rendered React applications.
- **TypeScript**: Static typing for JavaScript.
- **TailwindCSS**: Utility-first CSS framework.
- **Clerk**: Secure and scalable user authentication API.
- **GetStream.io**: Real-time video infrastructure.
- **shadcn/ui**: Beautifully designed and customizable components.

## Installation 🛠️

To set up Vartalaap locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yashxcode/astro-meet.git
   cd astro-meet
   ```

2. **Install the dependencies:**

   ```bash
   npm install
   ```

3. **Set up environment variables:**

   Create a new file named `.env` in the root of your project and add the following content:

   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
   CLERK_SECRET_KEY=

   NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
   NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

   NEXT_PUBLIC_STREAM_API_KEY=
   STREAM_SECRET_KEY=
   ```

   Replace the placeholder values with your actual Clerk and GetStream.io credentials.

4. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

---

Vartalaap is designed to provide a robust and user-friendly video conferencing experience.
For any issues, feel free to open an issue on this repository.
