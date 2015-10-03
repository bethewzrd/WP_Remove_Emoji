<?php
 /*
 Plugin Name: WP Remove Emoji
 Description: Removes emoji code from the head in a split second.
 Version: 1.0
 Author: WZRD
 License: GPL2
 */
defined( 'ABSPATH' ) or die( 'No script kiddies please!' );
	remove_action( 'wp_head', 'print_emoji_detection_script', 7 );
	remove_action( 'admin_print_scripts', 'print_emoji_detection_script' );
	remove_action( 'wp_print_styles', 'print_emoji_styles' );
	remove_action( 'admin_print_styles', 'print_emoji_styles' );	
	remove_filter( 'the_content_feed', 'wp_staticize_emoji' );
	remove_filter( 'comment_text_rss', 'wp_staticize_emoji' );	
	remove_filter( 'wp_mail', 'wp_staticize_emoji_for_email' );
?>
