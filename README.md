Download Link: https://assignmentchef.com/product/solved-softcomputing-assignment-3-universe-and-fuzzy-set-classes-and-display-their-member-functions
<br>
Define Universe and Fuzzy Set Classes and Display their Member Functions

<ul>

 <li>Analyze the data and functions of the fuzzy sets defined on a continuous universe. Exercise objectoriented techniques to develop related C# classes for implementing the fuzzy sets. For example, you will have a Universe class to let user define the value ranges and resolution for displaying the member functions of fuzzy sets. Remember that in an MS Chart an embedded ChartArea is to host a number of series. Therefore, a Universe class should possess a ChartArea to host the fuzzy sets.</li>

 <li>On the other hand, a generic Fuzzy set class can be defined to accommodate particular fuzzy sets, which will be derived from the generic one. Note that a fuzzy set object should have a reference to an existing universe object, on which the set is defined. In real applications, several fuzzy set objects might share the same universe object. Therefore, an existing object of Universe class is required to create an object of FuzzySet and that will be imposed on constructors of the FuzzySet class. In addition, since a curve is associated with a fuzzy set to represent its member function, a FuzzySet class should possess a Series object and update data points by itself, if visual display is required.</li>

 <li>Exercise C# O-O design techniques by applying <em>virtual</em>–<em>override</em> methods and <em>Properties</em> to the family of FuzzySets. Following the instructions given in the lab time. Get familiar with the <em>property</em> structure of C# and the fact that all C# classes are internally inherited from <em>object</em></li>

 <li>Create a WinForm to host UI controls that allow user to define a universe and create objects of different fuzzy sets on it. Graphical UIs are therefore designed to display member functions of the fuzzy set objects. Note that these member functions are parameterized and you should provide UIs to let user interactively change their values. Property definitions for these parameters and uses of PropertyGrid controls can simplify the task. Default constructors associated with automatic titling and random parameter value initializing should be implemented to facilitate fast fuzzy set modeling.</li>

 <li>In general, more than one universe should be created to define various fuzzy sets in order to create a fuzzy inference system. Therefore, graphical UIs should be used to keep tracking of the created objects. TreeView control consisting of hierarchical structures is suitable for our fuzzy set modeling.</li>

 <li>Check your textbook and the lecture note for the function definitions of other types of fuzzy sets. For example: S, Z, , stepUp, stepDown fuzzy sets, etc. Note that several different definitions can be found in the text part and exercise part of the textbook.</li>

 <li>Prepare a folder named as &lt;your ID&gt;&lt;your name&gt;Ass03 to put your source code in it. Compress it as an RAR file and submit to course web site (COOL).</li>

</ul>


