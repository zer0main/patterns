# patterns
Patterns of programming and design

## Design

### Model-view-controller (MVC)
#### Concept

It is used for implementing user interfaces. The main idea
is to divide program into three interconnected components.

#### Components

 - Model
 - View
 - Controller

#### Interactions

Controller manipulates the model so it changes and view
receives model's updates. Then view shows it for user.
User sees updates and uses the program; user's actions
encourage controller to manipulate the model again.

#### Examples

My first project where I used MVC: [bin_game_mvc][bin_game]
Project with modified MVC: [battleship][battleship]

#### Useful links

[MVC implementation for JavaScript (habrahabr)][habr_post]

### Unit testing

[bin_game]: https://github.com/zer0main/bin_game_mvc
[battleship]: https://github.com/zer0main/battleship
[habr_post]: http://habrahabr.ru/post/119369/
