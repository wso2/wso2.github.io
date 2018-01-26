# Upgrading from the Previous Release

> Use this template to create an upgrade guide for each release. Change the placeholders in the text below.

The followings steps describe how to upgrade from `<Previous product version>` to `<Current product version>`. To upgrade from a version older than `<Previous product version>`, start from the documentation that was released immediately after your current release and upgrade incrementally.

If you want to move your current product configurations to a different environment (e.g., from Test to Production) within the same product version, see the `<link to migration instructions in the product's documentation>`. 

## Preparing to upgrade

> - Provide any recommendations before you begin (e.g., what third-party software is recommended to be upgraded along with this, recommended time of migration such as low-traffic periods in the system, etc.)
> - Describe limitations and incompatibilities, if any.
> - Describe how to back up the databases.
> - Describe the expected system downtime.

## Upgrading the database/registry

> Give step-by-step instructions on what databases to change and what changes to do in each database.

## Upgrading the configurations

> Describe the config files and applications that can simply be moved from the older version to the new version without being changed. Include the following:
> - How to move the applications, tenants, workflows, user stores etc. (You can have separate subsections for each type. These subsections
> may vary depending on the product.)
> - How to move the configuration files. (Can the users simply override the existing files, or do we have to warn them of any configurations
> that might be overridden if they copy/paste?)

## Testing the upgrade

> Mention what tests the user should run to make sure that the upgrade has not caused any issues in the system.
