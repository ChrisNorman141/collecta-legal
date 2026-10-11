# Collecta Privacy Policy

Draft for review — confirm the retention details marked below before publication.

Last updated: 11 October 2026

Norman Solutions, based in England, United Kingdom, operates Collecta. This policy explains how we handle personal information when you use Collecta. Contact us at **chris.norman141@gmail.com** with privacy questions or requests.

## Information we handle

- **Account information:** your email address, account identifier, authentication information, and profile details such as username, display name, bio, and profile picture. Email/password authentication is handled by Supabase. If you choose Google sign-in, Google and Supabase handle authentication and provide the account information needed to sign you in, which may include your email, name, and profile picture.
- **Collection information:** collections and items you create, wishlists, collection progress, visit confirmations, achievements, visibility preferences, and location-monitoring settings. Places you add may include names, addresses, and coordinates.
- **Photos:** the profile picture you choose is uploaded to cloud storage. Collecta does not upload your entire photo library. Profile pictures are publicly accessible to anyone with their URL.
- **Location:** when you press the map location button and grant permission, Collecta accesses your device location to centre the map. If you enable location monitoring, Collecta also accesses precise location in the background, including when the Android app is closed or not in use, to detect visits to eligible collection locations.
- **Technical information:** network requests disclose your IP address and request information to the services receiving them. Authentication and hosting services may process operational and security logs. Authentication sessions are retained on your device so you can remain signed in.
- **Support correspondence:** information you send when contacting us, including your email address and the content of your request.

## How we use information

We use information to create and authenticate accounts, save and display collections and wishlists, record progress, manage profiles and privacy settings, display maps, detect eligible visits, provide collection suggestions based on accessible public progress, respond to requests, and protect and maintain the service.

The reviewed Collecta application has no advertising, payment, or third-party analytics/crash-reporting SDK integrations. Our Supabase backend also contains application diagnostic logs, which can include an account identifier, session identifier, platform, application version, event, error type, and timing information. We do not use device location for advertising.

## Background location and visit detection

Location monitoring is optional and disabled by default. Enable it under **Profile > Location monitoring** and grant the required location and notification permissions. On Android, a persistent notification appears while monitoring is active.

While enabled, Collecta attempts a location check approximately every five minutes. It sends your current latitude and longitude to our Supabase backend to compare your position with eligible places within about 30 metres. These device coordinates are processed for the comparison and are not saved in application database tables as a location history. Hosting infrastructure may process request information separately.

When a match occurs, we store your account identifier, the matched place identifier, and observation and expiry times. Repeated matches can create a pending visit confirmation. A visit is added to your progress only after you accept it. Matched places and times can reveal where you have been even though raw device coordinates are not saved.

Visit observations and confirmation records expire after 24 hours and are removed by an hourly cleanup job. Cleanup can be delayed if a scheduled run fails. Accepted progress remains separately as part of your account until it is removed or your account is deleted.

You can disable monitoring in Collecta, revoke location permission in Android settings, or sign out to stop monitoring. Map browsing remains available without location permission. Location-bearing development diagnostics are disabled in release builds.

## Who receives information

- **Supabase:** provides authentication, database hosting, and file storage and processes account information, application records, uploaded photos, and location-comparison requests on our behalf.
- **Google:** handles sign-in if you choose Google authentication. If you select **Get directions**, Collecta opens an external Google Maps app or website with the destination coordinates; that service handles the resulting interaction under its own privacy policy.
- **OpenStreetMap services:** map tiles are requested from OpenStreetMap and place-search text is sent to its Nominatim service. Requests disclose your IP address and the requested map area or search terms. A map area centred on your position may reveal your approximate location.
- **Image hosts:** viewing a collection or place image hosted externally sends a request to that host, including your IP address and the image requested.
- **Other users and public viewers:** public collections and their items are accessible to other users. New accounts have private progress and achievement settings. You can choose to make these public; existing accounts keep their saved visibility choices. Profile text is available only to you and administrators. New collections default to private, and you can explicitly make them public. Profile pictures are public even if your progress is private. Avoid including sensitive information in public content.

We may disclose information where legally required or necessary to protect users, investigate misuse, or defend legal rights. Our Supabase project is hosted in Ireland. Other service providers may process information outside the United Kingdom or Ireland. Contact us for information about applicable international-transfer arrangements.

## Security

Collecta uses HTTPS for configured cloud and map services, authentication, and database access controls intended to restrict access according to ownership and visibility settings. No transmission or storage system is completely secure. Public content can be copied by others, and changing visibility or deleting content cannot remove copies already made by third parties.

## Retention and deletion

Account information, profile content, collection records, preferences, and confirmed progress are kept to provide your account and its features. You can edit profile details, remove your profile picture, change progress and achievement visibility, and manage collections and wishlists through the app. Some removal operations may mark records as deleted rather than immediately erase them.

You can delete your account directly in Collecta under **Profile > Delete account**, after confirming the consequences. This stops location monitoring and attempts immediate deletion. If deletion fails, retry or contact us; some uploaded files may already have been removed.

To request deletion of your Collecta account and associated personal information outside the app, email **chris.norman141@gmail.com** with the subject **Collecta account deletion**, identifying the email address used for your account. We may ask you to verify account ownership. Do not send your password. Uninstalling the app or signing out does not delete your account.

We complete account-deletion requests within 28 days after verifying account ownership. Public collections remain available after account deletion.

When deleting your account, we disconnect retained public collections from your account and rename them Community collection. We remove custom titles, descriptions, cover images, tags, item media, and manually added items. Only places backed by our imported public-provider catalogue remain, with their name, address, and coordinates taken from that catalogue. Tag labels you created are replaced with generic labels. We delete your account, profile, uploaded profile picture, private collections, wishlists, observations, confirmations, progress, achievements, and preferences from the live service. We do not retain deleted account information for additional legal or security purposes.

Application diagnostic logs and database authentication audit logs are removed after 30 days by hourly cleanup jobs. Account deletion also removes account-linked application logs and matching database authentication audit records. Previously issued access tokens may remain valid until their expiry, but the account and its personal records are removed.

Our current Supabase plan is Free. Standard dashboard service-log history is available for one day; this is a dashboard access window, not a verified deadline for erasure of every provider-held copy. Supabase's paid-plan daily backup history is not included in the Free plan.

**To be confirmed before publication:** verify any exported backups, provider-held internal backups and service logs, and their applicable erasure periods. Deletion from the live database does not necessarily remove such copies immediately.

We retain support and privacy-request emails for 12 months after the request is resolved, then delete them. We remove unnecessary attachments sooner.

## Your choices and rights

You can control optional location and notification permissions through your device settings and use the profile controls described above. Depending on your jurisdiction, you may have rights to access, correct, delete, or obtain a copy of your personal information, restrict or object to processing, and withdraw consent for optional processing. Contact **chris.norman141@gmail.com** to make a request. You may also complain to your local data-protection authority.

## Children

Collecta currently sets no minimum user age. Parents or guardians can contact **chris.norman141@gmail.com** about a child's personal information or to request its deletion, subject to appropriate verification.

New collection/progress/achievement settings are private, map location is user-initiated, and background monitoring is disabled by default and requires an explicit disclosure and permission. Uploaded profile pictures and content you explicitly make public remain public.

**To be confirmed before publication:** the app does not verify age or parental approval. Establish lawful bases, parental consent where required, guardian-request verification, and suitable controls for children's public content and personalised suggestions before supporting children. The current privacy controls alone do not establish full children's privacy compliance.

## Changes and contact

We will update this policy when our practices change and revise the date above. Where required, we will notify you of material changes or request consent. Privacy enquiries and account-deletion requests should be sent to **Norman Solutions** at **chris.norman141@gmail.com**.
