# # Midterm Submission - INFR 3110

## Part 1: Scene Setup Choices
- **What:** Built a simple level layout based on Bubble Bobble using basic shapes.
- **How:** Used cubes for the ground and platforms, a cylinder for the player, spheres for bubbles, and capsules for enemies.
- **Why:** This keeps the project simple and quick to build during a short timed exam.

## Part 2: Object-Oriented Programming (OOP)
- **What:** Used three main rules of OOP: Inheritance, Encapsulation, and Polymorphism.
- **How:** Created a base class (`BaseGameEntity`) that code scripts inherit from. Protected the speed variable inside the class. Changed how bubbles and enemies start using overrides.
- **Why:** This makes the code organized, neat, and very easy to add new features to later.

## Part 3: Singleton Pattern
- **What:** Used a Singleton for the `GameScoreManager`.
- **How:** Used an instance check in `Awake()`. It deletes any extra copies and keeps the score alive between scenes.
- **Why:** The score must be handled by only one script so points do not get lost or mixed up.

## Part 4: Factory Pattern
- **What:** Used a Factory script to spawn game objects.
- **How:** The `EntityFactory` checks an enum type (Bubble or Enemy) and clones the right prefab.
- **Why:** This keeps creation code in one single spot. The player script does not need to know how to set up or build a bubble.

 
