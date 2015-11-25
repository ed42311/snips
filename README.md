# snips

####These are snippets for Sublime Text 3
They are ordered by category in this format:
	**snippetName** :tabtrigger:  - What the snippet does
		Code block

###React Snippets

1. **reactComponent** :compReact: - creates a React Component ready to interact with a skeleton html page.

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



2. **reactRenderGetElementById** :reactRenderID: - formulates a render function that allows you to render a component to the page with an id.

		It starts out looking like this:
		``` React.render(<App/>, document.getElementById('someID'));

	


		
###Miscellaenuos

1.

