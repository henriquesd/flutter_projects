# gifs_searcher

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


---------------------------

# Using an external API

Get the API url on https://developers.giphy.com/

Inform the API key on the request variable, on home.page.dart file, changing "xxxxxxxx" for your API key on request const.

Example: response = await http.get("https://api.giphy.com/v1/gifs/search?api_key=xxxxxxxx&q=$_search&limit=$_offset&offset=75&rating=G&lang=en");




