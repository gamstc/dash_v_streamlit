# Dash vs Streamlit

Some small app to compare Dash and Streamlit. Accompanying repository for this article: https://towardsdatascience.com/plotly-dash-vs-streamlit-which-is-the-best-library-for-building-data-dashboard-web-apps-97d7c98b938c

Most important take aways from the article: 

"... while Streamlit provides a very good looking styling out of the box, the superior flexibility of Dash and the ability to leverage existing Bootstrap themes gives it the nod."


"As you might have seen in my code above, Dash uses the concept of “callbacks” to add in interactivity. Functions need to be set up so that whenever a linked input changes, it triggers the function (like the update_fig() function above).

This might be more verbose, but then the Dash app only needs to re-run the function that has been called. On the other hand, Streamlit is configured so that any time an input is changed, all of the app is re-run."

