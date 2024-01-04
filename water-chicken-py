from bs4 import BeautifulSoup
import requests

def boil(url):
	req = requests.get(url)
	html = req.text
	soup = BeautifulSoup(html, 'html.parser')	
	return soup.prettify()

if __name__ == '__main__':
	frog = 'http://allaboutfrogs.org/funstuff/randomfrog.html'
	swikee = boil(frog)
	print(swikee)

