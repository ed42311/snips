# snips

####These are snippets for Sublime Text 3
They are ordered by category in this format:
	**snippetName** :tabtrigger:  - What the snippet does
		Code block

###React Snippets

1. **reactComponent** :comp: - creates a React Component ready to interact with a skeleton html page.

	It starts out looking like this:
		``` var App = React.createClass({
	    		render: function() {
	        		return (
	         			<div>
	              			<ul>
	                			<h1>  hello world </h1>
	              			</ul>
	          			</div>
	        		);
	    		}
			});

			React.render(<App/>, document.body);



2. **reactRenderGetElementById** :getelbyid: - formulates a render function that allows you to render a component to the page with an id.

		It starts out looking like this:
		``` React.render(<App/>, document.getElementById('someID'));


3. **buttonThatRendersBtn**

4. **htmlReact**

5. **reactLikeButton**

6. **getIntialState**

7. **handleClick**

###Database Snippets

1. **AxiosLibraryAPIcall** :axslibcall: - drops in a axios library API call.

		It starts out looking like this:
		```  fetchSomeData: function (req, res ) {

		    var = someURL
		    var = someAPIReq

		    axios.get(someURL + someAPIReq)
		     .then(function (response) {
		       res.json(response);
		       console.log(response;
		     })

		     .catch(function (response) {
		       console.log(response);
		     });
		   }
		}
	
2. **simpleRestfulApi**

###Html Snippets

1. **htmlHeadTagStyle**

2. **simpleFormHTML**

3. **simpleHtmlSetup**

###Javascript Snippets

1. CompleteSimpleHTTPServer

2. **JavascriptTable** :tbl: - Creates a table with a few rows and some columns
	It starts out looking like this:
		``` <table>
			  <tr>
			    <td></td>
			    <td></td> 
			    <td></td>
			  </tr>
			  <tr>
			    <td></td>
			    <td></td> 
			    <td></td>
			  </tr>
			</table>

			



###Miscellaenuos

1. **bootstrapPreloader**

