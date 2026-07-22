accessibility. You can choose to enable a more compact line height from the view settings menu.
‎service-worker.js‎
Lines changed: 13 additions & 0 deletions
Original file line number
Diff line number
Diff line change
@@ -0,0 +1,13 @@
const CACHE_NAME = "my-wallet-pro-v1";
self.addEventListener("install", (event) => {
self.skipWaiting();
});
self.addEventListener("activate", (event) => {
event.waitUntil(clients.claim());
});
self.addEventListener("fetch", (event) => {
event.respondWith(fetch(event.request));
});
