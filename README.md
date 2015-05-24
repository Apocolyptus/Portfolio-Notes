# Portfolio-Notes

Research
This week I've been working quite hard on getting the understanding on the MVC and how to implement it into my work. I'll cover what I know about the MVC model and have created a demo version to share as an example. It covers a little UML too, as I've found that-whilst I hate UML-it does have a purpose.

MVC or Model-View-Controller is a design pattern. 

The Model represents data and the rules that govern access to and updates of this data. In enterprise software, a model often serves as a software approximation of a real-world process. 

The View renders the contents of a model. It specifies exactly how the model data should be presented. If the model data changes, the view must update its presentation as needed. This can be achieved by using a push model, in which the view registers itself with the model for change notifications, or a pull model, in which the view is responsible for calling the model when it needs to retrieve the most current data.

The controller translates the user's interactions with the view into actions that the model will perform. In a stand-alone GUI client, user interactions could be button clicks or menu selections, whereas in an enterprise web application, they appear as GET and POST HTTP requests. Depending on the context, a controller may also select a new view -- for example, a web page of results -- to present back to the user.

Refer to image MVC_model.jpg.


Development
I've created the MVC model and created the example shown. This isn't my first rodeo, so to say.

Questions/Comments
Does it look like the graphic image emailed? I tried to see if it would match and work.
Also. I have portfolio one and two and whatever else, but they are on the computer. I don't know why I didn't think to put them on GIT... just not thinking I suppose.
