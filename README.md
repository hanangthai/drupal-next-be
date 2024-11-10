# About Us Page Cloning

This project aims to clone the page at [https://it-consultis.com/about-us/](https://it-consultis.com/about-us/) using Drupal and Next.js.

## Technologies Used

- **Drupal**: For content management and API delivery. https://github.com/hanangthai/drupal-next-demo
- **Next.js**: For frontend rendering and interaction. https://github.com/hanangthai/drupal-next-fe

---

## Project Requirements

### 1. Drupal Setup

- **JSON:API**: Install and enable the `jsonapi` module in Drupal to provide access to the content without authentication. Since this is a test project and involves only public API access, no additional authentication is required.

- **Section Ordering**:
  - We need to set up a way to arrange sections in Drupal so that they are displayed in the correct order on the Next.js application.
  - => To achieve this, we're using the **Basic Page** content type to create the "About Us" page. In this content type, an additional field `field_sections` has been added. This field allows the addition and reordering of paragraph sections, enabling a flexible structure that can be displayed accurately in the Next.js app.

## Installation

### 1. Backend (Drupal)

- Clone this repository https://github.com/hanangthai/drupal-next-demo
- Install the site using the downloaded database and files: https://drive.google.com/drive/folders/1Kj3dRsTGHNFK_HMXLMyA00KKexcWAsxc?usp=sharing
- Replace files downloaded from the above link to `web/sites/default/files`
- Copy settings.local.php to `web/sites/default`
