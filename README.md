# nodoss-security-pro
An ultra-lightweight, zero-allocation security and gateway defense engine for WordPress.
=== NoDoss ===
Plugin URI: https://wordpress.org/plugins/nodoss
Donate link: https://paypal.me/EBekedam
Contributors: frontiers
Author URI: https://github.com/frontiers-wp/nodoss
Tags: security, performance, brute force,
Description: Lightweight Security plugin againts attacks, incl mordern securty headers.
Requires at least: 5.9
Tested up to: 7.1
Requires PHP: 8.2
Stable tag: 1.1.6
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl-3.0.html

An ultra-lightweight, zero-allocation security and gateway defense engine for WordPress. 

== Description ==

An ultra-lightweight, zero-allocation security and gateway defense engine for WordPress. 
Engineered for absolute runtime optimization and bulletproof perimeter protection against automated botnets, brute-force exploits, script injection vectors, and Cross-Site Request Forgery (CSRF).

#### Core Threat Mitigation Matrix:
* Automated Exploit Scanner Disruption & User Enumeration Hardening.
* Bruteforce Attack Interception & Malicious Auth-Loop Defenses.
* Advanced Multi-Layered Script Jacking & DOM-based XSS Mitigation.
* Strict Runtime Reflection & Dangerous RPC Method Purging.
* Iframe & Secure Outbound Navigation (target="_blank") Isolation Matrix.

#### Enterprise Security Policy Headers Deployed:
* Cross-Origin Opener/Embedder/Resource Policies (COOP, COEP, CORP)
* Advanced Cross-Origin Resource Sharing (CORS) Access Constraints
* Deterministic Referrer-Policy & X-Content-Type-Options Enforcement
* Anti-Clickjacking X-Frame-Options & Cross-Domain Isolation Controls
* HSTS (Strict-Transport-Security) & Automated HTTPS Insecure Upgrades
* Isolated Engine Verification via Origin-Agent-Cluster Signaling

== Installation ==

1. Upload 'nodoss.zip' to the '/wp-content/plugins/' directory
2. Extract the Plugin to a `nodoss` Folder
3. Activate the plugin through the 'Plugins' menu in WordPress
5. General Settings – Heartbeat <15> <360> Interval seconds
6. Debugging Override: To temporarily halt the structural HTTPS routing engine during localized staging tasks, add "define('NODOSS_ENABLE_HTTPS_CHECK', false); " 
 directly to your wp-config.
7. Bypass Lockout wp-login: define('NODOSS_BYPASS_LOGIN_LOCKOUT', true);
8. White list your admin IP : define('NODOSS_IP_WHITELIST', '86.01.168.00' );  // example "withlist your IP"

1. Go to `Plugins` in the Admin menu
2. Click on the button `Add new`
3. Search for nodoss` and click 'Install Now' or click on the `upload` link to upload `nodoss.zip`
4. Click on `Activate plugin`
5. General Settings – Heartbeat <15> <360> Interval seconds
6. Debugging Override: To temporarily halt the structural HTTPS routing engine during localized staging tasks, add "define('NODOSS_ENABLE_HTTPS_CHECK', false); " 
 directly to your wp-config.
8. Bypass Lockout wp-login: define('NODOSS_BYPASS_LOGIN_LOCKOUT', true);
9. White list your admin IP : define('NODOSS_IP_WHITELIST', '86.01.168.00' );  / example 


== Frequently Asked Questions ==

= Why use NoDoss as a security plugin? =
Because it developed over a longer period of time, with fully hosted sites as well, there are performance and security layers that complement without breaking any of the basic functions of WordPress.

= Will the NoDoss plugin slow down my site? = 
It's developed to be lightweight because it covers all with very low impact on performance. 

= Will the plugin protect against XXS attacks? = 
Yes, XSS protection is part of this plugin.

== Screenshots ==
1. heartbeat-interval.png
2. safe-results.png
3. nodoss-banner-772-250.png
4. nodoss-ico.png
5. nodoss-icon.svg

== Changelog ==

= 1.0.1 =
* Refactored runtime inputs with strict cryptographic unslashing routines.

= 1.0.2 =
* Deployed optimized HTTP defense response headers.
* Improved PHP memory allocation matrices across core classes.

= 1.0.3 =
* Neutralized core fingerprinting vectors by purging the global WordPress generator identity layout.

= 1.0.4 =
* Implemented systemic debug tracing infrastructure.
* Deployed targeted anti-scraping and right-click execution lockouts.

= 1.0.5 =
* Standardized script pipeline bindings via formal wp_enqueue protocols.
* Enforced systemic context escaping, variable sanitization, and capability-based authentication gates.

= 1.0.6: December 01, 2025 =
* Initial stable production branch release.

= 1.0.7 =
* Visual branding and administrative asset integration updates.

= 1.1.3: August 23, 2026 =
* Verified complete runtime structural stability under WordPress 7.1 and PHP 8.5 runtimes.

= 1.1.5: September 19, 2026 =
* Deployed sub-systemic Brute-Force Rate Limiting and specialized login form botnet interceptors.
* Hardened Cross-Site Scripting (XSS) and Clickjacking prevention layers for modern PHP compilation runtimes.


= 1.1.6: September 28, 2026 = 
* API Gateway Hardening: 
Complete transition from legacy PHP superglobals to internal WordPress environmental abstractions, eliminating execution vectors for request-tampering scanner tools.
* Zero-Allocation JIT Optimization: 
Refactored runtime loops to utilize static matrices and type-safe closures,driving peak throughput performance under native PHP 8.5+ JIT compilation layouts.
* Gutenberg Sandbox Security Alignment: 
Enhanced the REST authentication filter pipeline to natively isolate public asset exposure while ensuring absolute session consistency for the block editor.
* Strict Codebase Compliance Overhaul: 
Successfully aligned core logic loops with advanced WordPress Coding Standards (WPCS) via precise internal sanitization mechanisms.

== Upgrade Notice ==
This crucial architectural update hardens the underlying REST API firewall, removes raw superglobal dependencies to prevent edge bypass vectors, and optimizes memory allocation for modern high-traffic PHP servers. Immediate upgrade is highly recommended to ensure system integrity.

