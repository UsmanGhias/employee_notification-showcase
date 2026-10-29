# Visa and Work Permit Expiry Reminders

![Odoo](https://img.shields.io/badge/Odoo-17.0-714B67) ![Editions](https://img.shields.io/badge/Editions-Community%2C_Enterprise-2563EB) ![License](https://img.shields.io/badge/License-OPL--1-0F766E)

In Saudi Arabia, the UAE and Qatar an expired visa or work permit means a fine for the employer. This app tracks both dates on the employee and warns the employee and their manager a week before expiry.

## What it does

- Visa Expiry Date and Work Permit Expiry Date on the employee form
- Daily scheduled action that finds expiries in the next 7 days
- To-do activity created on the employee record
- Reminder email to the employee with the manager in CC
- Expiration notice shown on the form

## How to use it

1. Fill in the two dates on each employee. The scheduled action does the rest.

## Technical notes

Technical name `employee_notification`, Odoo 17.0.

Extends `hr.employee` and adds an `ir.cron` job and a mail template. Depends on `hr` and `mail`.

## Get the module

This module is not on the Odoo App Store yet. Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=employee_notification) for a licence, the full source code and installation on your database.

Need it on another Odoo version, with changes for your workflow, or installed and tested on Odoo.sh? Email [iusmanghias@gmail.com](mailto:iusmanghias@gmail.com?subject=employee_notification%20customisation) or see [CODCrafters](https://codcrafters.org).

---

This repository is the product page. The module source is private and comes with the licence.

Built by [Usman Ghias](https://usmanghias.co.uk), [CODCrafters](https://codcrafters.org).
