# Verification

Checked November 3, 2026.

- JavaScript syntax check passed with `node --check dist/script.js`.
- All internal anchor targets and local HTML asset references resolve.
- IDs are unique and Organization structured data parses as JSON.
- Desktop layout visually reviewed at the preview browser's 1363-pixel viewport.
- All four service panels reviewed. Arrow-key tab navigation changes the selected panel and keyboard focus.
- Privacy dialog opens and closes.
- Email and telephone links contain the supplied address and telephone number.
- Email-copy control shows its manual-copy fallback on the HTTP preview. Successful Clipboard API copying on HTTPS was not independently verified.
- Mobile layouts visually reviewed in 390-pixel and 320-pixel frames.
- The smallest layout was corrected and rechecked: HTML clientWidth and scrollWidth both measured 305 pixels in the 320-pixel frame with its scrollbar.
- Mobile navigation opens; selecting a section closes it and moves to the section.
- No launch date, pricing, client testimonials, or unsupported performance numbers were invented.
- Temporary mobile QA page removed before deployment.

Private publication succeeded. The root custom domain has been staged and is pending verification. Domain DNS has not been changed. See `../DOMAIN_SETUP.md` for the exact hosting-returned records and remaining launch steps.
