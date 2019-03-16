# Security Audit Report

It's coming soon with the help of the community.

## 1. Disabled error logging when not used

In the wp-config.php file, make sure that it says:
`define('WP_DEBUG', false);`

## 2. Domain Name System Security Extensions (DNSSEC)

https://www.youtube.com/watch?v=MrtsKTC3KDM

## 3. Hypertext Transfer Protocol Secure (HTTPS)

### Overview

HTTPS encrypts the connection between a user and your website, securing any sensitive data that the user may have submitted on your site, such as personal details, password, and credit cards. It ensures that you really are talking to the server you think you're connected to and that no one can listen in on the conversation.