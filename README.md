# This is my blog

It is powered by [Jekyll](http://jekyllrb.com/) and gets automatically generated by [GithHub Pages](http://pages.github.com/) whenever I push to this repository.

However, to start a local Jekyll server, do:

	jekyll serve -w
    
## Style Sheets

I use [Stylus](http://learnboost.github.io/stylus/) and [Nib](http://visionmedia.github.io/nib/) to process my style sheets, like this:

	stylus css/styles.styl -w -c -u '/usr/local/share/npm/lib/node_modules/nib/'
	
Just make sure to update Nib route accordingly.