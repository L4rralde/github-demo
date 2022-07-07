# github-demo
A simple demo repository to show the basic Git Workflow


notes: 
	How to enable and use access token: 
			https://www.youtube.com/watch?v=kHkQnuYzwoo
	Highlights: 
		- Generate token with repo permissions from User>settings>developer settings
		- Use token as password when requested. 
		- use the following command to cache user and password and avoid being requested again and again:
			git config --global credential.helper cache
		- Use the following to clear above (needed when updating token):
			git config --global --unset credential.helper
			
