
# Partials
When using the default view engine (ejs), Sails supports the use of partials (i.e. “view partials”). Partials are basically just views that are designed to be used from within other views.

They are particularly useful for reusing the same markup between different views, layouts, and even other partials.

Example:
app.js
app.set(‘views’, path.join(__dirname, ‘views’)); app.set(‘view engine’, ‘ejs’);
error.ejs
<% include ./base/header %> <h1> Other mark up here </h1> <% include ./base/footer %>

# why we use it ??
partials it like reuse the same html across multiple views we use it to help us to make large website easyer
