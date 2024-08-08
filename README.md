# ansible-deprecations
Custom Lint rules for Ansible deprecations

Write up of lint rules can be found here
https://averytechguy.wordpress.com/2024/07/18/ansible-lint-for-deprecated-items/

Seeing every major release of Ansible gives us a list of functionality deprecated, I wanted to have a way to scan my existing playbooks to check for any code I would need to change before upgrading. Ansible lint allowed me to create custom rules for each of the deprecations.
