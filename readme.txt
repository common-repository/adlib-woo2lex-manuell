=== Manueller Datenexport von WooCommerce nach Lexware ===
Contributors: Odido
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=owagner@ad-libitum.info&item_name=WooCommerce2Lexware&currency_code=EUR
Tags: export, order, woocommerce, lexware, opentrans
Requires at least: WooCommerce
Tested up to: 6.5
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Exports not yet exported orders from woocommerce to a xml-file for Lexware - format is openTRANS. On demand only completed orders are exported.

== Description ==

= Scan & Notify =
*WooCommerce to Lexware* exports orders from woocommerce. All exported orders are tagged in the database so they won't be exported again. The export file is a xml corresponding to the <a href="http://ad-libitum.info/plugins/adlib-bestellexport-manuell/Handbuch_Standardshopschnittstelle.pdf" target="_blank">specifications  described</a> by Lexware. The export files are named with this pattern: yyyymmdd-hhmmss.xml and are stored in the directory /export.

= Requirements =
* WooCommerce up to 8.9.2
* WordPress up to 6.5.4

= Donation =
* If you need an invoice including VAT contact owagner@ad-libitum.info mentioning the desired amount to donate and address and you will receive an invoice.
* [PayPal](https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=owagner@ad-libitum.info&item_name=WooCommerce2Lexware&currency_code=EUR)

= Documentation =
* [Bestellexport](https://www.ad-libitum.info/plugins/adlib-bestellexport-manuell "Bestellexport") (DE)

== Frequently Asked Questions ==

== Screenshots ==
1. The dialog of WooCommerce to Lexware

== Changelog ==

= 0.1 =
woo2lex is published

= 0.2 =
i18n added

= 0.9 =
i18n for german formal salutation - many thx to pawell87
new code to retrieve sku - many thx to freiheit 1903

= 0.9.1 =
new email for PayPal

= 0.9.3 =
buyers details are cleared before processing the next order - many thx to Niko

= 1.0.1 =
Additional address data (order AND billing) are added to the remark field
Prices are no longer rounded

= 1.0.2 =
Using product variations the sku of each individual product is returned - many thx to Christoph

= 1.0.3 =
Articles with price = 0 caused a NAN for tax - many thx to Christoph

= 1.0.4 =
Choose either to export all orders or only the ones that are completed - many thx to Kai