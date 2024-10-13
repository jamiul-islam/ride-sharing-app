# Ride Sharing App

This project showcases a ride sharing app similar to Uber or Ryde

## Figma Design

[See design on Figma](https://www.figma.com/design/sYYXxLpiyU7CkvRljZzCRH/Ryde---Uber-Clone-App?node-id=0-1)

## Tech Stack

- React Native
- Expo
- Stripe
- PostgreSQL
- Google Maps
- zustand
- Clerk
- Tailwind CSS

## Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/jamiul-islam/ride-sharing-app.git
cd ride-sharing-app
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=

EXPO_PUBLIC_PLACES_API_KEY=
EXPO_PUBLIC_DIRECTIONS_API_KEY=

DATABASE_URL=

EXPO_PUBLIC_SERVER_URL=https://uber.dev/

EXPO_PUBLIC_GEOAPIFY_API_KEY=

EXPO_PUBLIC_STRIPE_PUBLISHABLE_KEY=
STRIPE_SECRET_KEY=
```

Replace the placeholder values with your actual Clerk, Stripe, NeonDB, Google Maps, andgeoapify credentials. You can
obtain these credentials by signing up on
the [Clerk](https://clerk.com/), [Stripe](https://stripe.com/in), [NeonDB](https://neon.tech/), [Google Maps](https://console.cloud.google.com/)
and [geoapify](https://www.geoapify.com/) websites respectively.

**Running the Project**

```bash
npx expo start
```

## App Screens

<div style="display: grid; grid-template-columns: repeat(4, 1fr);">
<img src="/app-snapshots/1.png" width=20%>
<img src="/app-snapshots/2.png" width=20%>
<img src="/app-snapshots/3.png" width=20%>
<img src="/app-snapshots/4.png" width=20%>
<img src="/app-snapshots/5.png" width=20%>
<img src="/app-snapshots/6.png" width=20%>
<img src="/app-snapshots/7.png" width=20%>
<img src="/app-snapshots/8.png" width=20%>
<img src="/app-snapshots/9.png" width=20%>
<img src="/app-snapshots/10.png" width=20%>
<img src="/app-snapshots/11.png" width=20%>
</div>
