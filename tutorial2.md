# Plants & Pollinators

## @showdialog
Add Climate Action Land Extension from the Extension drawer. 
On the Extensions page search for Inksmith or Land
![Adding Land Extensions](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/add-extensions.gif)

## @showhint 
After adding the ``||Extension||`` create a variable. 
Go to ``||Variables||`` 
click on Make a Variable. 
Name the Variable ``||Variables:bugVisits||``
![Making a Variable](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Make%20a%20variable.gif)
Now under ``||Variables||``, ``||Variables:bugVisits||`` exists 
and three additional blocks are available.

## @showhint
Add ``||Variables:set bugVisits to 0||`` under ``||basic:on start||``
![Add Variable Block](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Variable%20Nest%20Under%20On%20Start.png)
## @showhint
Add ``||basic:showNumber||`` under ``||basic:on start||`` blocks.
![Add Show Number Block](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Variable%20%26%20Show%20Number%20Nest%20Under%20On%20Start.png)

## @showhint
Add ``||Variables:bugVisits||`` to ``||basic:showNumber||`` blocks
![Add Set bugVisits to 0](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Adding%20Variable.gif)
## @showhint
Add ``||logic.if true||`` conditional block under the ``||basic: forever||`` loop
![Add If/Else Block](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Forever%20If-Else.png)
## @showhint
Now add ``||Variables:change bugVisits by 1||`` everytime the conditional is true
![Add Change bugVisits by 1](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Forever%20If-Else%20Variable.png)
## @showhint
This step is to show the number on the micro:bit's LED display. 
Add ``||basic.showNumber||`` block and 
drag the ``||Variables:bugVisits||`` and 
place it in the oval space
![Add variable bugVisits to Show Number Block](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Forever%20If-Else%20Variable%20Show%20Number%20with%20Variable.png)

## @showhint
Now let's add the ``||Touch||`` sensor condition to the ``||logic:If true||`` statement.
Whenever the ``||Touch||`` sensor is activated the ``||Variables::bugVisits||`` will increment
![Adding Touch Sensor](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Adding%20touch%20sensor%20true%20condition.gif)
## @showhint
Here is the final code 
![Code](https://raw.githubusercontent.com/mbakhtar/plants-and-pollinators---tutorial-v001/master/Code%20Image%20Plants%20%26%20Pollinators.png)