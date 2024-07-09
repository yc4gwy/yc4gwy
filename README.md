import webbrowser

def search(query):
    # Construct the search URL
    search_url = f"https://www.bing.com/search?q={query}"
    
    # Open the default web browser with the search results
    webbrowser.open(search_url)

# Example usage:
user_query = "best pizza places near me"
search(user_query)
