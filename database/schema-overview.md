# Database Overview

## Core Tables

### prisons
- id
- name
- country
- city
- rules
- allowed_items

### inmates
- id
- prison_id
- first_name
- last_name
- inmate_number

### products
- id
- name
- category
- prison_approved
- stock

### orders
- id
- user_id
- inmate_id
- status
- tracking_number

### users
- id
- full_name
- email
- role
