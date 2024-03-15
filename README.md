# Testing the app


1. Download a copy or clone the repo
2. Run `npm install`
3. Run `ionic build`
4. Run `npx cap sync`
5. Open the project in either Android with `npx cap open Android` or iOS with `npx cap open ios`
6. Put your phone in the setting you wish to test location services in (ie, normal, airplane with bluetooth & wifi off, airplane with bluetooth off & wifi on, etc...)
7. Deploy the app to your device

The location will be displayed on the home page and look something like:
Current Location: { latitude: number; longitude: number; accuracy: number; altitudeAccuracy: number | null; altitude: number | null; speed: number | null; heading: number | null; }

If there is an error fetching the location, it will just display "Current Location: "

The coordinates will also be logged to the console