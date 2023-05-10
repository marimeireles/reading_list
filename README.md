# Reading list

[reading_list.webm](https://user-images.githubusercontent.com/17600982/234714380-9842ca92-6fef-47bf-8510-b2dfc83e7f42.webm)

## 📚 Adding a Reading List Page to My Own Website

Here are the steps to make this work on your website:

1. 📋 Copy the files `books_js.js` and `books.html` to your website folder
2. 📝 Edit the file `your_csv_address.js` to contain your `.csv` file address
   (I recommend hosting it on Github, but feel free to use any other hosting service)
3. 🎉 Congrats! Your website should now have a cool new page with your own books! Just navigate to your-website.com/books.html.

If you run into any issues, don't hesitate to open an issue here! 😊

## 📖 How Should My CSV Look?

Check out the [test.csv](test.csv) file in this repository.
Every column should be separated by commas, like a default CSV. However! make sure to separate the type labels with `;` and not commas. Also make sure to trim any single comma from the title of books, or notes, or authors, if you leave commas behind it will break the parsing of the table and ugly things will happen.
Happy reading! 🤓
