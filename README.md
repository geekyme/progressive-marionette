Clone this project and open any one of the html files in your favorite browser. 

What I've done is to render some HTML and then allow Backbone Views to be attached to the rendered content. 

For item_view.html, we see that after allowing Backbone to run its code, we are able to click on the 'view' and see it alerting the model attribute. 

For collection_view.html, we are able to click each item on the list and see the model attribute updated and reflected in the view. 

For composite_view, clicking the list of items show the same effect as collection_view.html. However, clicking the 'Hello World' title changes the model attribute which results in a full render of the whole CompositeView. 

What's a good way to only re-render changed content?