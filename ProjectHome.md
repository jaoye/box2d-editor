# Introduction #

**Physics Body Editor** (_previously known as box2d-editor_) lets you import your game images and easily define collision outlines for them. These outlines are automatically transformed into multiple convex polygons to fit physics engines requirements. Then, an in-game loader can be used to retrieve the collision data from the saved files and build your bodies in just with as few lines of code as possible.

The editor is engine-independent. Therefore, it may be compatible with any physics engine, like [Box2D](http://www.box2d.org/), [Chipmunk](http://code.google.com/p/chipmunk-physics/), [Farseer](http://farseerphysics.codeplex.com/), etc. All you have to do is to write a custom loader for your preferred engine implementation if there is none already provided.

**NOTE**: if you indeed write a custom loader, I would love you to share it with other people. Send it to me at aurelien.ribon [at](at.md) gmail.com and I'll include it directly in the distributed zip file, with credits given to you. Thanks in advance.

**Features**:
  * Automatically decomposes concave shapes into convex polygons,
  * Automatically traces your images if needed,
  * Supports multiple outlines for a single body,
  * Supports polygon and circle shapes,
  * Reference point location can be changed,
  * Visual configurable grid with snap-to-grid option,
  * Built-in collision tester! Throw balls at your body to test it,
  * Loader provided for [LibGDX](http://libgdx.badlogicgames.com/) game framework (written in Java),
  * Simple export format (JSON), to let you easily create your own loader for any framework in any language.

# Manual & Help #

**Reference manual:** http://www.aurelienribon.com/blog/projects/physics-body-editor/

**Help forum:** http://www.aurelienribon.com/forum/viewforum.php?f=6

<a href='http://www.youtube.com/watch?feature=player_embedded&v=KASY91EiTXQ' target='_blank'><img src='http://img.youtube.com/vi/KASY91EiTXQ/0.jpg' width='425' height=344 /></a>

# Screenshots #

![http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-01.jpg](http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-01.jpg)

![http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-04.jpg](http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-04.jpg)

![http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-02.jpg](http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-02.jpg)

![http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-03.jpg](http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-03.jpg)

![http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-05.jpg](http://www.aurelienribon.com/blog/wp-content/uploads/2012/04/pbe-05.jpg)