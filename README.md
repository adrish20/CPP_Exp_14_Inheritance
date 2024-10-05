<h1>Aim</h1>
<p>To study and implement C++ inheritance</p>
<hr>
<h1>Software required</h1>
<p>Vscode</p>
<hr>
<h1>Theory</h1>
<p>Inheritance in C++ is a fundamental concept in object-oriented programming that allows a class (called a derived or child class) to inherit properties and behaviors (data members and member functions) from another class (called a base or parent class). This mechanism promotes code reusability and establishes a relationship between classes.Through inheritance, a derived class can override base class methods to provide specific functionality, enhancing polymorphism and allowing for dynamic method resolution at runtime.</p>
<hr>
<h1>Algorithms</h1>
<h2>Single inheritance</h2>
<ol>
        <li>Start.</li>
        <li>Define a class <strong>Uni</strong>.
            <ul>
                <li>Declare a public string variable <strong>uni</strong> initialized to <strong>"Symbiosis"</strong>.</li>
                <li>Define a public method <strong>discipline()</strong>:
                    <ul>
                        <li>Print <strong>"Engineering"</strong> to the console.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>Define a class <strong>Dep</strong> that inherits from <strong>Uni</strong>.
            <ul>
                <li>Declare a public string variable <strong>dept</strong> initialized to <strong>"Electronics & Communication"</strong>.</li>
            </ul>
        </li>
        <li>Create the <strong>main()</strong> function.</li>
        <li>Inside the <strong>main()</strong> function:
            <ul>
                <li>Create an object <strong>department</strong> of class <strong>Dep</strong>.</li>
                <li>Print the <strong>uni</strong> member of <strong>department</strong> to the console.</li>
                <li>Call the <strong>discipline()</strong> method on <strong>department</strong>.</li>
                <li>Print the <strong>dept</strong> member of <strong>department</strong> to the console.</li>
            </ul>
        </li>
        <li>End.</li>
    </ol>
<h2>Multiple inheritance</h2>
<ol>
        <li>Start.</li>
        <li>Define a class <strong>Vehicle</strong>.
            <ul>
                <li>Declare a public string variable <strong>company</strong> initialized to <strong>"Ford"</strong>.</li>
                <li>Define a public method <strong>type()</strong>:
                    <ul>
                        <li>Print <strong>"Fiesta"</strong> to the console.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>Define a class <strong>Specs</strong>.
            <ul>
                <li>Declare a public string variable <strong>mileage</strong> initialized to <strong>"12 kmph"</strong>.</li>
                <li>Define a public method <strong>colour()</strong>:
                    <ul>
                        <li>Print <strong>"Red"</strong> to the console.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>Define a class <strong>Car</strong> that inherits from both <strong>Vehicle</strong> and <strong>Specs</strong>.
            <ul>
                <li>Declare a public string variable <strong>seater</strong> initialized to <strong>"4 seater"</strong>.</li>
            </ul>
        </li>
        <li>Create the <strong>main()</strong> function.</li>
        <li>Inside the <strong>main()</strong> function:
            <ul>
                <li>Create an object <strong>f2</strong> of class <strong>Car</strong>.</li>
                <li>Call the <strong>colour()</strong> method on <strong>f2</strong>.</li>
                <li>Print the <strong>company</strong> member of <strong>f2</strong> to the console.</li>
                <li>Call the <strong>type()</strong> method on <strong>f2</strong>.</li>
                <li>Print the <strong>seater</strong> member of <strong>f2</strong> in parentheses.</li>
                <li>Print the <strong>mileage</strong> member of <strong>f2</strong> to the console.</li>
            </ul>
        </li>
        <li>End.</li>
    </ol>
<h2>Multilevel inheritance</h2>
<ol>
        <li>Start.</li>
        <li>Define a class <strong>Food</strong>.
            <ul>
                <li>Declare a public string variable <strong>cuisine</strong> initialized to <strong>"Indian"</strong>.</li>
                <li>Define a public method <strong>type()</strong>:
                    <ul>
                        <li>Print <strong>"Asian"</strong> to the console.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>Define a class <strong>Dish</strong> that inherits from <strong>Food</strong>.
            <ul>
                <li>Declare a public string variable <strong>dish</strong> initialized to <strong>"Biriyani"</strong>.</li>
            </ul>
        </li>
        <li>Define a class <strong>Restaurant</strong> that inherits from <strong>Dish</strong>.
            <ul>
                <li>Declare a public string variable <strong>name</strong> initialized to <strong>"Spice Kitchen"</strong>.</li>
            </ul>
        </li>
        <li>Create the <strong>main()</strong> function.</li>
        <li>Inside the <strong>main()</strong> function:
            <ul>
                <li>Create an object <strong>myRestaurant</strong> of class <strong>Restaurant</strong>.</li>
                <li>Print the <strong>name</strong> member of <strong>myRestaurant</strong> to the console.</li>
                <li>Print the <strong>cuisine</strong> member of <strong>myRestaurant</strong> to the console.</li>
                <li>Print the <strong>dish</strong> member of <strong>myRestaurant</strong> to the console.</li>
                <li>Call the <strong>type()</strong> method on <strong>myRestaurant</strong>.</li>
            </ul>
        </li>
        <li>End.</li>
    </ol>
<h2>Hierarchial inheritance</h2>
<ol>
        <li>Start.</li>
        <li>Define a class <strong>Jeans</strong>.
            <ul>
                <li>Declare a public string array <strong>type</strong> of size 3, initialized to <strong>{"Bootcut", "WideLeg", "Skinny"}</strong>.</li>
                <li>Define a public method <strong>brand()</strong>:
                    <ul>
                        <li>Print <strong>"Brand: H&M - &Denim"</strong> to the console.</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li>Define a class <strong>Bootcut</strong> that inherits from <strong>Jeans</strong>.
            <ul>
                <li>Declare a public string variable <strong>color</strong> initialized to <strong>"Dark Blue"</strong>.</li>
            </ul>
        </li>
        <li>Define a class <strong>WL</strong> that inherits from <strong>Jeans</strong>.
            <ul>
                <li>Declare a public string variable <strong>color</strong> initialized to <strong>"Light Blue"</strong>.</li>
            </ul>
        </li>
        <li>Define a class <strong>Skinny</strong> that inherits from <strong>Jeans</strong>.
            <ul>
                <li>Declare a public string variable <strong>color</strong> initialized to <strong>"Black"</strong>.</li>
            </ul>
        </li>
        <li>Create the <strong>main()</strong> function.</li>
        <li>Inside the <strong>main()</strong> function:
            <ul>
                <li>Create an object <strong>j1</strong> of class <strong>Bootcut</strong>.</li>
                <li>Create an object <strong>j2</strong> of class <strong>WL</strong>.</li>
                <li>Create an object <strong>j3</strong> of class <strong>Skinny</strong>.</li>
                <li>Print a newline character.</li>
                <li>Call the <strong>brand()</strong> method on <strong>j1</strong> and print <strong>j1.type[0]</strong> and <strong>j1.color</strong>.</li>
                <li>Call the <strong>brand()</strong> method on <strong>j2</strong> and print <strong>j2.type[1]</strong> and <strong>j2.color</strong>.</li>
                <li>Call the <strong>brand()</strong> method on <strong>j3</strong> and print <strong>j3.type[2]</strong> and <strong>j3.color</strong>.</li>
            </ul>
        </li>
        <li>End.</li>
    </ol>
<hr>
<h1>Conclusion</h1>
<p>In conclusion, through this experiment we have learnt about different types of inheritance and implemented them in C++ codes.</p>
