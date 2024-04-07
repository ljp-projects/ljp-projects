window.addEventListener('fetch', event => {
 const url = new URL(event.request.url);
 const hostname = url.hostname;

 if (hostname.match(/googleads\.g\.doubleclick\.net/)) {
    event.respondWith(new Response('', { status: 204 })); // Block the request
 }
});
