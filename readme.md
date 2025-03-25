Overview
This Ansible playbook is designed to gather and report installed packages on target hosts. It creates a structured CSV output for easy analysis and includes features for organizing reports by date.

Key Features
Package Facts Gathering: Uses package_facts to collect information about installed packages.

CSV Reporting: Generates CSV files containing package details (hostname, package name, version, architecture, release).

Date-Based Organization: Creates a directory structure with subdirectories named by the current date (yyyy.mm.dd) to store reports.

Combined Reporting: Offers an option to combine all host reports into a single CSV file for easier analysis.

Security: Supports the use of Ansible Vault for securing sensitive data like passwords.

Usage
Run the Playbook: Execute ansible-playbook playbook.yml to generate reports.

Vault Integration: Use --ask-vault-pass to run the playbook with encrypted variables.

Benefits
Simplifies package management and auditing.

Provides structured data for analysis.

This playbook is designed to be flexible and scalable, making it suitable for environments requiring regular package audits.
