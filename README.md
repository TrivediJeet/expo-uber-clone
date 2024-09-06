<div align="center">
  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="reactnative" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgresql" />
    <img src="https://img.shields.io/badge/-Expo-black?style=for-the-badge&logoColor=white&logo=expo&color=000020" alt="expo" />
    <img src="https://img.shields.io/badge/-Stripe-black?style=for-the-badge&logoColor=white&logo=stripe&color=008CDD" alt="stripe" />
  </div>

</div>

## <a name="table">Table of Contents</a>

1. [Introduction](#introduction)
2. [Tech Stack](#tech-stack)
3. [Features](#features)
4. [Quick Start](#quick-start)
6. [Links](#links)
7. [Assets](#assets)

## <a name="introduction">Introduction</a>

Built with React Native, Google Maps for rendering maps with directions, stripe for
handling payments, serverless Postgres for managing databases, and styled with TailwindCSS.

## <a name="tech-stack">Tech Stack</a>

- React Native
- Expo
- Stripe
- PostgreSQL
- Google Maps
- zustand
- Clerk
- Tailwind CSS

## <a name="features">Features</a>

- **Onboarding Flow**: Seamless user registration and setup process.

- **Email Password Authentication with Verification**: Secure login with email verification.

- **oAuth Using Google**: Easy login using Google credentials.

- **Authorization**: Secure access control for different user roles.

- **Home Screen with Live Location & Google Map**: Real-time location tracking with markers on a map.

- **Recent Rides**: View a list of recent rides at a glance.

- **Google Places Autocomplete**: Search any place on Earth with autocomplete suggestions.

- **Find Rides**: Search for rides by entering 'From' and 'To' locations.

- **Select Rides from Map**: Choose available cars near your location from the map.

- **Confirm Ride with Detailed Information**: View complete ride details, including time and fare price.

- **Pay for Ride Using Stripe**: Make payments using multiple methods like cards and others.

- **Create Rides After Successful Payment**: Book a ride after confirming payment.

- **Profile**: Manage account details in the profile screen.

- **History**: Review all rides booked so far.

- **Responsive on Android and iOS**: Optimized for both Android and iOS devices.

and many more, including code architecture and reusability

## <a name="quick-start">Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/TrivediJeet/expo-uber-clone.git
cd expo-uber-clone
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

EXPO_PUBLIC_SERVER_URL=https://expo-uber-clone.dev/

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

Download the [Expo Go](https://expo.dev/go) app and Scan the QR code on your respective device to view the project.


## <a name="links">Links</a>

- <a href="https://www.nativewind.dev/quick-starts/expo" target="_blank">Expo NativeWind Setup</a>
- <a href="https://www.nativewind.dev/v4/getting-started/typescript" target="_blank">TypeScript Support for
  NativeWind</a>
- <a href="https://docs.expo.dev/guides/using-eslint/" target="_blank">Eslint and Prettier Setup</a>
- <a href="https://neon.tech/" target="_blank">Serverless NeonDB</a>
- <a href="https://go.clerk.com/DtiSBEI" target="_blank">Clerk Auth</a>
- <a href="https://clerk.com/docs/quickstarts/expo" target="_blank">Clerk Expo Quickstart</a>
- <a href="https://clerk.com/docs/custom-flows/oauth-connections" target="_blank">Clerk Expo OAuth</a>
- <a href="https://www.geoapify.com/" target="_blank">Geoapify Map</a>
- <a href="https://docs.stripe.com/payments/accept-a-payment?platform=react-native&ui=payment-sheet" target="_blank">
  Stripe React Native SDK</a>
- <a href="https://docs.stripe.com/payments/accept-a-payment-deferred" target="_blank">Stripe</a>

## <a name="assets">Assets</a>

Assets used in the project can be
found [here](https://drive.google.com/file/d/1ekttG-aCyy4g0SKqLSrEn_uHf2MJMRJ4/view?usp=sharing)
