=== Anywhere List Shortcode ===
Tags: post list
Requires at least: 3.9.1
Tested up to: 3.9.1
License: GPLv2 or later
License: URI: http://www.gnu.org/license/gpl-2.0html

You can simply put a "[list]" short code, to list the title of the latest article (link with) and the front page of your blog, sidebar, footer. Set category and custom post type, taxonomy also other it is also possible.

=== Description  ===

WordPress post retrieve and list.
Purpose to be output by the number specified latest posts mainly is suitable.

Parameters(Main parameters, refer to the get_posts of Codex.)
- post_type: WordPress post type. Default is post.
- cat_name: Category slug.
- num: Number: The number of posts you want to output.
- class: Unorderd list's class name. maybe easy controllable :)
- orderby: Post's order.
- order: Ascending Descending.
- length: If you want to adjust the length of post title
- end_of_title: Specify a string to be appended to the end of the article. This must be required for 'length'.
- taxonomy: If you want to output by specifying a custom taxonomy.
- term: Required for 'taxonomy'.

Example
[list] most simple.
[list post_type=post cat_name=news num=5 class=newslist] at visual editor
<?php echo do_shortcode( '[list]' ); ?>

Other
It can be also be used in widget :)
