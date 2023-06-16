# Web Crawler

This Java program is a simple web crawler that uses the Jsoup library to crawl web pages and collect information about visited URLs. It allows you to specify the depth of crawling and retrieves and prints the URLs and titles of the visited pages.

## Usage

1. Set the starting URL:
    - Open the `Main` class.
    - Modify the `url` variable in the `main` method to set the starting URL for crawling. By default, it is set to "https://en.wikipedia.org/".

2. Set the crawling depth (optional):
    - Open the `crawl` method in the `Main` class.
    - Adjust the value in the `if (level <= 5)` condition to change the maximum depth of crawling. The current code limits the crawling to a depth of 5 levels.

3. Run the program.

4. Results:
    - The program will start crawling from the specified URL.
    - The URLs and titles of the visited pages will be printed on the console.
    - The visited URLs will be stored in an ArrayList.

## Prerequisites

- Java Development Kit (JDK) 8 or higher installed.
- Jsoup library added to the project.

Feel free to customize the code to perform additional actions with the visited URLs or extract more information from the web pages according to your specific needs.