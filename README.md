# S&H restored homepage

This update restores the attached base page's animated partner ribbon, boxed text/image divisions (including alternating left/right layouts), rotating semi-circle partners and moving event gallery. It retains the recent hero design and Manrope typography.

## Use the files

Replace your current index with `index.html`. Keep `sh-hero.jpg` next to it. All other image src routes match the attached browser-saved HTML exactly, including the companion folder:

`S&H Consulting _ Turnkey Projects, VIP Car Hire & Logistics_files/`

The ZIP contains that folder populated with the site's existing images, so its paths work when the package is extracted. The hero is the only new image route. CSS, page JavaScript and two font weights are inside index.html. Font Awesome icons use the existing version's public CDN stylesheet; an internet connection is needed for those small icons. Existing partner logos and gallery pictures are local files.

If your current live site stores pictures directly in its root, move/copy them into the included companion folder or replace that folder prefix consistently in the HTML before uploading. The exact paths were retained because they were explicitly requested.

## Interaction and responsive refinements

- Seamless two-group animation loops (ribbon and gallery).
- A global pause/resume button; hover pauses individual strips and the orbit.
- Respect for reduced-motion device preferences.
- Keyboard-accessible image viewer, mobile menu state, larger touch targets and readable mobile text.
- Split division boxes retained on mobile, with overflow fixed and appropriate font sizes.
- The original form recipient and service routes are retained. Preview form submissions are blocked outside sh-consulting.co.za.
- Admin points to the existing admin URL without the base HTML's simulated authentication.
- The missing project subpage is routed to the enquiry section.

## SEO and content

The canonical, social metadata and Organization/WebSite/WebPage/Service structured data remain. Original favicon/logo paths are retained. Apply favicon links to subpages as needed. Google controls its final search display.

Original image mappings—including g20_setup.jpg and 09_icon_governance.png—are intentionally restored as requested. Confirm the corresponding source images, G20 experience and B-BBEE wording before publishing. Placeholder registration/ISO/100%-compliance claims are excluded.

Hero imagery is illustrative brand imagery. All existing project gallery images are retained. The missing contact-background companion file has been populated using an existing S&H event photograph while preserving its original route.

## Checks

Checked original image-path parity, file availability, JavaScript syntax, unique IDs, primary heading count and JSON-LD syntax. Browser/device visual testing was not available in this environment.
