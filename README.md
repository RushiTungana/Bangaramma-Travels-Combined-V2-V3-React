# Bangaramma Travels — Combined Version 2 + Version 3

Premium React website for Bangaramma Travels, with a procedural animated 3D sedan scene, destination signboard, direct call/WhatsApp booking and responsive layout.

## Important: You do NOT need Node.js on your computer to deploy this
You can upload this project directly to GitHub and let Vercel install dependencies and build it in the cloud.

## GitHub upload
1. Create a new GitHub repository, e.g. `bangaramma-travels`.
2. Upload the complete contents of this folder (not the ZIP itself).
3. Keep `package.json`, `index.html`, `vite.config.js`, `vercel.json`, and `src/` at the repository root.

## Vercel deployment
1. In Vercel choose **Add New → Project** and import your GitHub repository.
2. Framework preset: **Vite** (or let Vercel detect it).
3. Build command: `npm run build`.
4. Output directory: `dist`.
5. Install command: `npm install` (default).
6. Click Deploy. Vercel runs the install/build on its servers. No local Node/npm installation is needed.

## Features
- No father portrait included.
- Procedural 3D animated sedan scene made with React Three Fiber and Three.js.
- Animated roadside destination signboard in the 3D scene.
- Swift Dzire illustrative image gallery from front/rear/side angles.
- Destination cards for Pathapatnam, Paralakhemundi, Srikakulam and Visakhapatnam.
- Regional OpenStreetMap view spanning Andhra Pradesh, Odisha and Telangana.
- Direct tap-to-call and WhatsApp buttons throughout, including mobile sticky dock.
- Trip enquiry form sends details to Ramu's WhatsApp; no email required.
- Four sample review-card designs clearly labelled as sample previews.
- Customer review submission form opens WhatsApp so Ramu can review feedback before publishing.
- Mobile responsive layout and motion effects.

## Before publishing
- Dzire gallery images are illustrative external images, not verified photographs of the actual vehicle. Replace them with the owner's actual car photos if desired.
- The four review cards are sample placeholder content, not genuine verified customer reviews. Replace with real customer-submitted reviews or remove them before advertising them as real.
- Destination photos are representative scenic images and may not be exact photographs of the named towns. Replace with licensed, location-verified images if exact local imagery is required.
- The map is an indicative regional map, not an exact office or pickup address.
- Confirm vehicle availability, AC/Non-AC options, prices and extra-car arrangements directly with Ramu.
- External images, Google Fonts and OpenStreetMap tiles need an internet connection.

## Destination image references
- Pathapatnam town aerial photo: OneIndia, `https://imagesvs.oneindia.com/webp/te/img/2019/04/pathapatnam-1-1554283618.jpg`
- Brundavan Palace, Paralakhemundi: Odisha Dairy, `https://odishadairy.wordpress.com/wp-content/uploads/2015/08/gajapati-b-n-palace-paralakhemundi11.jpg`
- Srikakulam coastal scenery: Holiday Landmark, `https://www.holidaylandmark.com/blog/wp-content/uploads/2023/03/Top-Tourist-Places-to-Visit-in-Srikakulam-4.jpg`
- Visakhapatnam Beach Road aerial: Wikimedia Commons, `https://upload.wikimedia.org/wikipedia/commons/f/fe/Vizagcity.jpg`
Check source terms/permissions before commercial use; remote image hosts may change URLs.
