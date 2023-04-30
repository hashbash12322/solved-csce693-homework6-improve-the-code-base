Download Link: https://assignmentchef.com/product/solved-csce693-homework6-improve-the-code-base
<br>
<ol>

 <li> Improve the code base so that an explicit “void initialize()” method is defined in the game class, which calls initialize() in the entity manager class which calls initialize() in each entity being managed in its list – finally, each entity should call all of its components to initialize – the game object’s initialize method should be called in main() just after the game object is created. This turns the creation and initialization of entities (and its associated components) into a two-step process. This should also fix the Sprite component so that it does not search for a transform component which might not exist until later.  This means the template method to “add_component” should no longer be calling “initialize()”!</li>

 <li> Write sol-based lua code to read and parse the “config.lua” file to create the entities defined. In other words, update the Game load_level method so that it reads and processes the config.lua file.</li>

</ol>