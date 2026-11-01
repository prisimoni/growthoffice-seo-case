# Example: metadata verification workflow

This is illustrative documentation, not code from the production project.

1. Request a representative page with an HTTP client.
2. Inspect its response status and returned HTML.
3. Identify `<title>`, `meta[name="description"]`, canonical and Open Graph metadata.
4. Compare these values with the document after browser rendering.
5. Check agreement with the visible page topic and the canonical destination.
6. Record the URL, timestamp, observed values and any issues.

Do not configure different factual page content for crawlers and users. Any renderer or edge response should provide consistent primary information.
