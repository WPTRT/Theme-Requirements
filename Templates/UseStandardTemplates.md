If used in the theme, standard template files are required to be called by their respective function:

header.php (via get_header())

footer.php (via get_footer())

sidebar.php (via get_sidebar())

searchform.php (via get_search_form())



If you use the relevant templates, your theme should include:

wp_head() – (immediately before </head>)

body_class() – (inside <body> tag)
  
$content_width

post_class()

wp_link_pages()

the_comments_navigation(), the_comments_pagination()

the_posts_pagination(), the_posts_navigation()

wp_footer() – (immediately before </body>)
