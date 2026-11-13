# ev ⚡ ChargeShare — Your Neighbourhood is Your Charging Network

A working prototype where EV owners find and book home chargers nearby, and homeowners earn money from their chargers. Includes Rescue mode: a host with a free charger goes live and low-battery drivers nearby can request an instant charge.

## Run it

Open `index.html` in any browser. No install, no build, no paid APIs.

## Demo logins (fictional, password Demo@123)

| Role | Email |
| :--- | :--- |
| EV owner | `owner1@demo.cs` (owner1–owner5) |
| Host | `host1@demo.cs` (host1–host5) |
| Admin | `admin@demo.cs` |

## Features

* **General:** Simple landing page, voice assistant (browser speech recognition; type if mic is blocked).
* **EV Owner:** Rescue (low battery), search and filters, map and list, cost calculator, booking, simulated payment, reviews, and vehicles.
* **Host:** Rescue mode (go live), charging points, accept/reject requests, earnings chart, and reviews.
* **Communication:** Chat between owners and hosts, and notifications.
* **Admin:** Statistics, suspend users, approve verification, reports, and platform fee.

## Publish on GitHub Pages

1. Create a new GitHub repository, e.g., `chargeshare`.
2. Upload `index.html` and `README.md` (**Add file** → **Upload files**).
3. Go to **Settings** → **Pages**.
4. Under **Source**, select **Deploy from a branch** → **main / root** → click **Save**.
5. Your site opens at `https://<your-username>.github.io/chargeshare/`.

## Notes and limits

* Data is stored in the browser (`localStorage`), not a shared server.
* The map is a schematic SVG with approximate host zones. To use real Leaflet + OpenStreetMap, add the Leaflet CSS/JS and tiles when you host it yourself.
* Payments are simulated. Verification badges on demo accounts are not real. Public stations, entertainment spots, amenities, and reply times are demo data.
* Hosts must use a dedicated EV charger installed by a qualified electrician.
