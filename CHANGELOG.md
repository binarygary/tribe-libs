# Changelog

All notable changes to this project will be documented in this file.

## 3.4.4 - 2021-07-14

- Add composer v2 support
- Fix cron queues from cleaning up before finishing

## 3.4.3 - 2021-07-14

- Fix router query vars

## v3.4.3 - 2021-07-14

- Fix query vars in routing package

## v3.4.2 - 2021-04-29

 - Adds docs for routing

## v3.4.1 - 2021-04-22

 - Adds update for routing

## v3.4.0 - 2020-11-23

- Added a CLI block generator

## v3.3.0 - 2020-11-04

- Reworks Block_Config to remove sections and add method if doing this in the plugin instead
- Adds Field_Section

## v3.2.1 - 2020-10-27

- Force Composer v1 instead of v2 to avoid failing installs and tests due to unsupported dependencies.
- Adds CLI helper method for freeing up memory during long running processes.

## v3.2.0 - 2020-10-23

- Added SVG support to the Media package. This replaces the Safe SVG plugin with a more
  robust implementation that efficiently handles sanitization, scaling, and metadata
  regeneration. This is backwards compatible, but to take advantage of SVG minification,
  the new `Media_Definer` should be registered with the DI container.

## v3.1.2 - 2020-09-24

- Added Field_Group class
- Improvements to Repeater and Block_Config

## v3.1.1 - 2020-09-15

- Added missing packages to the monorepo config

## v3.1.0 - 2020-09-03

- Update release script for monorepo-builder 8.0 compatibility
- Minimum PHP version bump to 7.2

## v3.0.0 - 2020-09-01

- Many updates to libs in support of the SquareOne framework Fidgety Feet epic.

## v2.1.2 - 2020-04-02

- Added post type registration for blog copier internal post type for compatibility with WP 5.1+

## v2.1.1 - 2020-02-22

- Ignored and removed OS/IDE files

## v2.1.0 - 2020-02-22

- Added support for ACF Gutenberg Blocks

## v2.0.0 - 2019-10-07

- Migrated repository to a monorepo structure
- Migrated queues package from Square One
