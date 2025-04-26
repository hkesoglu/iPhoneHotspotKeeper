# iPhone Hotspot Keeper

https://hkesoglu.github.io/iPhoneHotspotKeeper/

On iPhone devices, when there is no active data usage over a hotspot connection for a period of time,
iOS may automatically disable the hotspot to save battery and improve security.
While this behavior is intentional, there are many cases (such as keeping background devices connected)
where a stable, continuous connection is necessary.

iPhone Hotspot Keeper provides a simple solution:
It creates a small, continuous data flow to keep the hotspot connection alive.
📢 How It Works

    When the page is opened, a small silent audio file (MP3) starts playing.

    iOS detects this as ongoing data activity.

    The data consumption is extremely low, and battery usage is minimal.

    As a result, the iPhone keeps the hotspot connection active, preventing it from automatically shutting down.

    No significant internet bandwidth is consumed.

🎯 Features

    Completely silent operation (no audible sound).

    Extremely low data and power usage.

    Works directly through a browser like Safari or Chrome — no app installation required.

    Easy hosting on platforms like Cloudflare Pages, GitHub Pages, or any static hosting service.

⚡ Use Cases

    Preventing the iPhone hotspot from disconnecting due to inactivity.

    Keeping IoT devices, laptops, or other connected devices online.

    Traveling or using personal hotspot for long periods without manual interaction.

    Note:
    This project is optimized to use minimal data, but it does create a very small, continuous data stream to maintain the hotspot connection.
