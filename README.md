# Rivoningo Air Conditioning website
Static, mobile-friendly website. No build step required.

## Deploy to Railway
1. Create a GitHub repository and upload `index.html` and `logo.jpg` at the repository root.
2. Create a Railway project/service from that repository.
3. Configure the service start command: `python3 -m http.server ${PORT:-8080} --bind 0.0.0.0` (requires Python available in the deployment image). A static hosting provider is often easier and cheaper for this site.
4. Add `rivoningoair.co.za` and `www.rivoningoair.co.za` in your hosting provider's custom-domain settings.
5. Apply the exact DNS values supplied by the host in Domains.co.za; do not guess A or CNAME targets.
6. Verify HTTPS and then submit the website to Google Search Console.
