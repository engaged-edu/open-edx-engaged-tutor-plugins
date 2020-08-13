# Changelog
All notable changes to this project will be documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.4.0] - 2020-08-12
### Removed
- Remove registration extra fields.

## [1.3.1] - 2020-08-07
### Fix
- Fix HTTP Error 403 CSRF verification

## [1.3.0] - 2020-07-03
### Added
- Enable ENABLE_DISCUSSION_EMAIL_DIGEST configuration.
### Removed
- Deprecated ENABLE_API_DOCS.
- Already enabled configurations for ENABLE_DISCUSSION_SERVICE, ENABLE_THIRD_PARTY_AUTH, and WIKI_ENABLED.

## [1.2.0] - 2020-06-12
### Changed
- Skip email validation after user registration.
- Disable account deletion.
- Enable milestones application.
- Send password reset failure email.

## [1.1.0] - 2020-06-08
### Changed
- Allow public account creation.
- Enable account deletion.
- Enable marketing site to redirect home page to sign in page when not authenticated.
- Set EngagED custom theme as default for both CMS and LMS.

## [1.0.0] - 2020-06-07
### Added
- Installation guide.
- Changelog documentation.
- Tutor plugin for environment configuration.