# Drupal 11 – University Staff Directory Prototype

A self-directed prototype built in **Drupal 11** (using **DDEV**, **Composer**, and **Drush**) to practice Drupal site-building workflows, custom content architecture, sub-theming, and configuration management aligned with university web standards.

## Key Features

* **Custom Content Type (`Staff Profile`):** Structured content model with custom fields (`field_job_title`, `field_department`, `field_email`, and `field_photo` with image accessibility alt-text).
* **Dynamic Directory View (`/ue_staff_directory`):** Responsive **Grid** view built using Drupal **Views** to query and display published staff profiles.
* **Custom Sub-Theme (`ue_staff`):** Built on top of the **Olivero** base theme (`web/themes/custom/ue_staff`) with custom CSS (`style.css`) for Flexbox card layout, brand accent borders, and circular avatar framing (`object-position: top center`).
* **Configuration Management:** Full site configuration exported to YAML (`.yml`) files via Drush (`drush config:export`) for Git-based version control.

## Tech Stack

* **CMS:** Drupal 11
* **Backend & CLI:** PHP 8.3, Composer, Drush
* **Development Environment:** DDEV (Docker containers: Nginx, MariaDB), GitHub Codespaces
* **Frontend & Templating:** HTML5, CSS3, Twig, Olivero Base Theme
* **Version Control:** Git & GitHub

## Visual Comparison (Before & After Custom CSS)

### 1. Default Drupal Views Output (Before Styling)

<img width="1164" height="754" alt="ue staff" src="https://github.com/user-attachments/assets/75e40942-3d74-408e-80ae-4d5e013d4f82" />

### 2. Custom Sub-Theme (`ue_staff`) with Custom CSS (After Styling)
<img width="990" height="436" alt="Screenshot 2026-11-17 160335" src="https://github.com/user-attachments/assets/d7407254-9be6-4242-abc5-617bebbfee19" />


<img width="990" height="436" alt="Screenshot 2026-11-17 160335" src="https://github.com/user-attachments/assets/cb037412-196f-4e5e-a64a-790bf69e4a12" />
# drupal-staff-directory
Creating a staff directory portal to practice Durpal skills  
