# Fastly_Cdn Release Notes

## 1.2.7

- Add a UI to add a custom error/maintenance page

## 1.2.6

- Add a check to make sure user has saved config before attempting upload

## 1.2.5

- Add Backend Settings configuration - allows reconfiguration of existing backends
- Minor bug fixes

## 1.2.4

- Add Force TLS button in advanced settings - it enables/disables it in the Fastly service

## 1.2.3

- Fix VCL if user has uploaded custom VCL and changed req.url

## 1.2.2

- Minor VCL optimizations

## 1.2.1

- Fix for VCL Snippet upload when no snippets exist

## 1.2.0

- Convert to using VCL snippets https://docs.fastly.com/guides/vcl-snippets/. This will provide for better maintainability since it breaks
down functionality into separate files instead of one large file. Also it avoids the need for having VCL upload functionality enabled
- Button to Test Credentials

## 1.0.9

- Updated etc/fastly.vcl to remove set-cookies on static content. Also to
cache static 404's for 5 minutes.

## 1.0.8

- Some styling changes to better match Magento's style

## 1.0.7

- bumped version.

## 1.0.6

- Corrected autoload typo.

## 1.0.5

- Corrected spelling mistake in README.
- Adjusted dependencies for 2.1 installation issue.

## 1.0.4

- Fixed compilation errors due to dependency declaration

## 1.0.3

- Fixed display of cache management.

## 1.0.2

- Added CLI command to generate VCL

## 1.0.1

- Updates to README.
- Adjustments from Marketplace review.
- Resolved Geo-IP ESI tag being added when Geo-IP function is disabled.
- Adjusted cache headers for caching of Geo-IP response

## 1.0.0

- Changed module name for marketplace review

## 0.9.0

Initial release for testing.
