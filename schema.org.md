The Article and Blog schema descriptions are pretty vague right now and will probably change sometime in the future, but i believe the Blog schema to be a little more relevant for a, well, blog (it's even implied in the Article schema description page down below, under "More specific types").

So, you can start by defining your main blog page with the higher level schema:

<!DOCTYPE html itemscope itemtype="http://schema.org/Blog">
<meta itemprop="creator" content="Creator of the blog">
<meta itemprop="name" content="Title of your Blog">
<meta itemprop="description" content="Description of your blog">
<meta itemprop="image" content="http://www.yourblog.com/main/image/pic.gif">
And you can define your blog pages with the second level blog schema, BlogPosting, and define the appropriate item properties, like so:

<!DOCTYPE html itemscope itemtype="http://schema.org/BlogPosting">
<meta itemprop="author" content="Author of your blog">
<meta itemprop="name" content="Title of your content">
<meta itemprop="description" content="Description of your post">
<meta itemprop="image" content="http://www.yourblog.com/post/image/pic.gif">
Urghh, complicated :P, there are a million properties you can employ, but just focus on the most important ones.