#Syntax: Selector - Declarations 
					{ properti-value; property - value; property - value; }
-------------------------------------------------------------------
A <div> is one of the basic HTML elements. It is an empty container. In general, it is best to use other tags such as <h1> or <p> for content in your projects, but as we learn more about CSS you’ll find that there are many cases where the thing you need is just a container for other elements. 
-------------------------------------------------------------------
Selectors:



		**Universal selector **
					* {color: purple; }
					--------------------------------------
		**Type selector (vagy element selector)**
					<div>Hello, World!</div>
					div {color: white;}

										The div tag in HTML is a container that is used to group other HTML elements together and apply styles to them as a unit. It doesn't have any semantic meaning and is used purely for layout purposes. When you want to group a set of elements together, you can simply wrap them in a div tag.
					-------------------------------------
		**Class selector**
			<!-- index.html -->
					<div class="alert-text">Cunami arrives at 14:25 on the 9+ 3/4 Platform!
					
			/* styles.css */
					.alert-text {color: red; size=100; style:policeman-blue-and-red-blinking}
							syntax for class selectors: a period immediately followed by the case-sensitive value of the class attribute. Classes aren’t required to be specific to a particular element, so you can use the same class on as many elements as you want. 
							And you can use more than one class on any element, like:
					class="alert-text severe-alert"
							Since whitespace is used to separate class names like this, you should never use spaces for multi-worded names and should use a hyphen instead.
					---------------------------------------------
		**ID selector**
			<!-- index.html -->
					<div id="title">My Awesome 90's Page</div>
			/* styles.css */
					#title {  background-color: red;}
							The major difference between classes and IDs is that an element can only have one ID. It cannot be repeated on a single page and should not contain any whitespace
					------------------------------------------
		** Grouping selector**
							Ha két csoportban vannak ugyanolyan tulajdonságok, azokat összecsoportosíthatod, és a nem közös tulajdonságok maradhatnak külön sorban

					.read, .unread {  color: white;  background-color: black;}

					.read {	/* several unique declarations */}

					.unread {/* several unique declarations */}
					-----------------------------------------------
		



-----------------------------------------------------------------------------------------------
  

Properties

			color:
						p {
							/* hex example: */
							color: #1100ff;
							}

						p {
							/* rgb example: */
							color: rgb(100, 0, 127);
							}

						p {
							/* hsl example: */
							color: hsl(15, 82%, 56%);
							}

			background-color:
						#p1 {background-color:#ff0000;} red
						#p1a {background-color:#ff000080;} transparent red

			font-family: "Times New Roman", serif;

			font-size: 22px

			font-weight: 700

			text-align: center

			img { height: auto;	width: 500px;	}	













