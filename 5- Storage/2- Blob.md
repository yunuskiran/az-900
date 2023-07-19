### Blob

Binary Large Object

## Schenarios
    - Images
    - All Types
    - Streaming
    - Log Files
    - Data Store

## Blob Types
    - Block: Store text and binary data up to 4.7 TB. Made up of individually managed block of data.
    - Appended: Block blobs that are optimized for append operations. Works well for logging where data is constantly appended.
    - Page: Store file up to 8 TB. Any part of the file could be accessed at any time, for example virtual hard drive.

## Pricing Tiers
    - Hot: Frequently accessed files. Lower access time and higher access cost.
    - Cool: Lower storage cost and higher access times. Data remains here for at least 30 days.
    - Archive: Lowest cost and highest access times.