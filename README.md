# traceit v0.1

Very, very quick command line script for [Jon Matthews](https://github.com/joncarlmatthews)

Takes a url as an argument, runs curl command and extracts http response codes and locations. Outputs list of redirects.

Written by: [Kieran Masterton](https://github.com/kieranmasterton)

Date: 18.12.13

## Installation

1. Download
2. cd into traceit directory
3. chmod +x traceit
4. Add traceit to your $PATH if you wish
5. Done!

## Running a trace

	./traceit <url>	

For example

	./traceit http://google.com

Output should look like:

	301 Moved Permanently: http://google.com
	302 Found: http://www.google.com/
	200 OK: http://www.google.co.uk/?gws_rd=cr&ei=m9yxUuDwA6WyywPbpoGoCg
	Trace complete!