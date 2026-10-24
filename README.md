# Buy / Sell — MySQL exercise

Small PHP/MySQL exercise for displaying product data.

## Files and setup

connect.php queries the products table through mysqli; index.html links to it. Use a PHP server with mysqli and a local MySQL database containing the expected products schema. This repository does not contain the schema migration.

Open connect.php through the PHP server. Opening index.html as a static file or publishing it on GitHub Pages does not execute its embedded PHP. The example is not a complete store: no checkout, authorization or order workflow is implemented.

## Maintenance

Preserve the existing source and sample assets when making changes. Do not commit credentials, personal data or generated build output. This review documents the checked-in project; it does not certify production readiness or a successful build on every platform.
