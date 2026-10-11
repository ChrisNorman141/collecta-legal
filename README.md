# Collecta legal documents

Public legal documents for Collecta, operated by Norman Solutions.

Privacy contact: **chris.norman141@gmail.com**.

## Files

- `index.html`: standalone privacy policy page for GitHub Pages. It requires no build tools, JavaScript, or external assets.
- `privacy-policy.md`: editable Markdown copy of the policy. Keep it aligned with `index.html`.
- `.nojekyll`: tells GitHub Pages to serve the static files directly.

## Publish with GitHub Pages

1. Push these files to the root of the `main` branch of the public `ChrisNorman141/collecta-legal` repository.
2. In GitHub, open **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose **main** and **/ (root)**, then save.
5. Wait for the Pages deployment to finish and open the URL below. Verify that it loads without signing in.

Expected privacy policy URL:

https://chrisnorman141.github.io/collecta-legal/

The account-deletion instructions are at:

https://chrisnorman141.github.io/collecta-legal/#retention-and-deletion

These URLs become available only after the repository is pushed and Pages is enabled. Enter the completed privacy policy URL in Play Console and link to it inside Collecta. The deletion section can serve as an external deletion-request resource once its process and retention details are complete and supported operationally.

## Complete before Play Console submission

The policy is still a review draft. It preserves the outstanding questions rather than inventing commitments:

- Release the updated Collecta client with Profile > Delete account. The deployed backend passed a disposable-account/avatar smoke test. Retained community collections lose custom text, images, tags, and manual items, keeping imported provider-backed places.
- Confirm provider-held internal backup/service-log erasure periods and external exports. Application and database Auth audit logs have hourly cleanup after 30 days; expired visits have hourly cleanup after their 24-hour expiry.
- Establish handling of children's accounts, consent, public content, and location features; the owner currently sets no minimum age.
- Verify applicable international-transfer arrangements; the Supabase project is hosted in Ireland.
- Follow the mailbox procedure for email deletion requests and 12-month support-email retention; these are manual operator tasks.
- Review the Data safety declaration and background-location disclosure/consent against actual production behavior.

Confirmed by the owner: no minimum user age; account deletion within 28 days; public collections remain; no intended additional legal/security retention; Supabase project hosted in Ireland; operator based in England; no current advertising, analytics, crash-reporting, or payment integrations.

The owner agreed to support-email retention of 12 months after resolution, with unnecessary attachments removed sooner, and to disconnect retained public collections from deleted accounts and remove their personal information. Backend deletion and database cleanup are implemented and tested. Provider-held internal backup/service-log erasure periods and manual mailbox procedures still need verification. The 28-day live-data deletion commitment is separate from backup expiry.

Resolve the draft notice and all **To be confirmed before publication** sections in both policy copies before submission. Update the policy date when making substantive changes. Keep the hosted page accessible while the app is available.

## References

- [GitHub Pages setup](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
- [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311?hl=en)
- [Google Play account deletion requirements](https://support.google.com/googleplay/android-developer/answer/13327111?hl=en)
