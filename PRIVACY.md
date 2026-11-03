# Discs privacy information

Discs is a macOS app for managing a personal music collection. Your library, listening history, profile and settings are stored locally on your Mac. Discs does not require an account, and the app does not include an advertising or analytics SDK.

## Information stored on your Mac

Your library may contain album and artist information, artwork, lyrics, notes, prices, collection locations and listening dates. Your profile may contain a name and photo. Locations describe where you keep your collection; they are not GPS locations.

These data remain on your Mac unless you export them or use a backup, synchronization or storage service that copies them. The security of those copies depends on your Mac and the services you choose.

## Online features

Discs connects to external services when you use online search. The relevant service receives the information needed to answer the request, as well as network information such as your IP address:

- **MusicBrainz:** artist names, release names or barcodes used in music searches.
- **Cover Art Archive and its hosting services:** release identifiers used to retrieve artwork.
- **Apple iTunes Search and artwork hosting:** artwork search terms and your selected store country.
- **LRCLIB:** track and artist names used to search for lyrics. A lyrics result may also trigger an artwork search.

These services have their own privacy practices. See [MetaBrainz privacy](https://metabrainz.org/privacy), [Internet Archive terms and policies](https://archive.org/about/terms), [Apple privacy](https://www.apple.com/legal/privacy/) and [LRCLIB](https://lrclib.net/) for more information.

Discs also checks its configured Sparkle update feed on GitHub. GitHub and the update download hosts receive the network information needed for those requests, including your IP address. See the [GitHub privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## Backups and images

Library backups use the `.discsbackup` extension and contain JSON data. They can include your profile, images, listening history, notes and collection details. **Discs does not encrypt these backups:** anyone with access to a backup can read its contents. Save backups to a trusted location and use an encrypted storage solution if you need additional protection. CSV and PDF files exported by earlier versions can also contain collection information.

When a backup is imported, images are validated and re-encoded to remove original metadata and reduce their dimensions. Damaged or oversized images are skipped and Discs reports how many were omitted. Very large backups can require substantial memory during import.

## Your controls

You decide when to import or export a backup and whether to use online search. You can control notification permission in macOS Settings. Clearing the collection in Discs removes albums, artists, listening sessions and tags from the library; it does not remove the profile, exported files or copies held by backup services. Review and remove any exported or externally stored copies separately when needed.

## Contact

For questions about Discs and privacy, open an issue in [Discs Releases on GitHub](https://github.com/emilianooowo/Discs-Releases/issues). Issues are public and may require a GitHub account. **Do not include private information, backup files, personal photos or other sensitive content in an issue.**

This information applies to Discs 3.9.
