#-------------------------------------------------------------------
# Custom variables

MD=$(wildcard *.md)

HTML=$(MD:.md=.html)

#-------------------------------------------------------------------

# emails : Create the format that the emails will be sent
emails : $(HTML)

$(HTML) : $(MD)
	@pandoc $< -o $@
