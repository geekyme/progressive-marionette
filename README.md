Clone this project and open any one of the html files in your favorite browser. 

What I've done is to render some HTML and then allow Backbone Views to be attached to the rendered content. 

For item_view.html, we see that after allowing Backbone to run its code, we are able to click on the 'view' and see it alerting the model attribute. 

For collection_view.html, we are able to click each item on the list and see the model attribute updated and reflected in the view. 

For composite_view.html, we see the same effect as collection_view.html when we click items on the list. However, clicking the title 'Hello World' ends up re-rendering the entire composite view. That is not good for performance. 

For composite_view_binding.html, I build on the previous example by adding Backbone.ModelBinding. That will provide view-model binding and update only the title 'Hello World' on click. 