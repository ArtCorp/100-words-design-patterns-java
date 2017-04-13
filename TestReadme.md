[![Build Status](https://travis-ci.org/dstar55/100-words-design-patterns-java.svg?branch=master)](https://travis-ci.org/dstar55)
[![Coverage Status](https://coveralls.io/repos/github/dstar55/100-words-design-patterns-java/badge.svg?branch=master)](https://coveralls.io/github/dstar55/100-words-design-patterns-java?branch=master) 
[![License](http://img.shields.io/:license-mit-blue.svg)](http://gus.mit-license.org/)

# 100 words GoF Design Patterns in Java

## Introduction

Idea: describe GoF Design Patterns on a simple way. 
Each pattern will be described with following structure:
* Story(less than 100 words)
* Implementation in Java

### GoF Design Patterns

#### Creational Patterns
* [Singleton](#Singleton)
* [Prototype](#Prototype)
* [Builder](#Builder)
* [Factory Method](#FactoryMethod)
* [Abstract Factory](#AbstractFactory)

#### Structural Patterns
* [Adapter](#Adapter)
* [Bridge](#Bridge)
* [Composite](#Composite)
* [Decorator](#Decorator)
* [Facade](#Facade)
* [Flyweight](#Flyweight)
* [Proxy](#Proxy)

#### Behavioral Patterns
* [Chain Of Responsibility](#ChainOfResponsibility)
* [Command](#Command)
* [Interpreter](#Interpreter)
* [Iterator](#Iterator)
* [Mediator](#Mediator)
* [Memento](#Memento)
* [Observer](#Observer)
* [State](#State)
* [Strategy](#Strategy)
* [Template Method](#TemplateMethod)
* [Visitor](#Visitor)

##### <a id="Singleton"></a>Singleton
* Story

Singleton ensures that only one(single) object can be created from the class.

Men's 100 meters world record holder is a singleton.
There can be at most one active "Men's 100 meters world record holder" at any given time. 
Regardless of who that person is the title, "Men's 100 meters world record holder" is a global point of access that identifies the fastes person in the world.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/singleton.jpg "Usain Bolt, Men's 100 meters world record holder")  
###### <a href='https://www.flickr.com/photos/mdpettitt/7825842576/' target='_blank'>
Brick Lane Graffiti Usain Bolt</a>&quot;&nbsp;(<a rel='license' href='https://creativecommons.org/licenses/by/2.0/' target='_blank'>CC BY 2.0</a>)
&nbsp;by&nbsp;<a xmlns:cc='http://creativecommons.org/ns#' rel='cc:attributionURL' property='cc:attributionName' href='https://www.flickr.com/people/mdpettitt/' target='_blank'>
Martin Pettitt</a>

* Implementation


UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/singleton.png "UML Singleton")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to singleton folder:

```
$  cd /src/main/java/com/hundredwordsgof/singleton
```

##### <a id="Prototype"></a>Prototype
* Story

Clone itself.

Sheep Dolly is the first mammal to be cloned, so Dolly is a duplicate.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/prototype.jpg "Sheep Dolly")  
###### Geni, <a href="https://commons.wikimedia.org/wiki/File:Dolly_the_sheep_2016.JPG">Dolly the sheep 2016</a>, <a href="https://creativecommons.org/licenses/by-sa/4.0/legalcode">CC BY-SA 4.0</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/prototype.png "UML Prototype")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to prototype folder:

```
$  cd /src/main/java/com/hundredwordsgof/prototype
```

##### <a id="Builder"></a>Builder
* Story

Separates the construction of a complex object from its representation so that the same construction process can create different representations.

This pattern is used by PC shops to contruct PC's.
PC is combination of various parts like CPU, motherboard, memory, storage, power supply, video card, etc.
To build a PC same construction process is used even for each part we have different variation.
Whether a customer picks a classical hard disk or SSD for storage, the construction process is the same. 

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/builder.jpg "The Antec P180, a popular computer case, suitable for use as a silent PC")  
###### By DonES (Own work) [<a href="http://www.gnu.org/copyleft/fdl.html">GFDL</a> or <a href="http://creativecommons.org/licenses/by-sa/3.0/">CC-BY-SA-3.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3ASilent_PC-Antec_P180.JPG">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/builder.png "UML Prototype")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to builder folder:

```
$  cd /src/main/java/com/hundredwordsgof/builder
```


##### <a id="FactoryMethod"></a>Factory Method
* Story

Defines an interface for creating objects, but lets subclasses decides which class to instantiate.
Plasticine is used for children's play. Plasticine is injected into predefined molds. The class of end product(ball, toy, sculpture, cake) is determined by the mold.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/factorymethod.jpg "Cake molds, Han people, metal - Museum of Vietnamese History - Ho Chi Minh City")  
###### Cake molds, Han people, metal - Museum of Vietnamese History - Ho Chi Minh City, By Daderot (Own work) [<a href="http://creativecommons.org/publicdomain/zero/1.0/deed.en">CC0</a>], <a href="https://commons.wikimedia.org/wiki/File%3ACake_molds%2C_Han_people%2C_metal_-_Museum_of_Vietnamese_History_-_Ho_Chi_Minh_City_-_DSC05796.JPG">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/factorymethod.png "UML Factory Method")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to factorymethod folder:

```
$  cd /src/main/java/com/hundredwordsgof/factorymethod
```

##### <a id="AbstractFactory"></a>Abstract Factory
* Story

Provides an interface for creating families of related objects, without specifying concrete classes. 

This pattern is found in the cards stamping equipment used in the 
manufacture in order to produce playing cards. 
Cards stamping machine is an Abstract Factory which produces a cards. 
The same machine is used to stamp French, Italian or German cards. 

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/abstractfactory.jpg "Poker Cards Back")  
###### <a href='https://www.pexels.com/photo/cards-poker-cards-poker-back-21827/' target='_blank'>
Poker Cards Back</a>&nbsp;(<a rel='license' href='https://creativecommons.org/share-your-work/public-domain/cc0/' target='_blank'>CC 0</a>)




* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/abstractfactory.png "UML Abstract Factory")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to abstractfactory folder:

```
$  cd /src/main/java/com/hundredwordsgof/abstractfactory
```

##### <a id="Adapter"></a>Adapter
* Story

Allows that interface of an existing class to be used from another interface.

Adapters are often used in daily life, for example eletrical adapter is a device that 
converts attributes of one electrical device or system to those of an otherwise incompatible device or system. 
Some modify power or signal attributes, while others merely adapt the physical form of one electrical connector to another.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/adapter.jpg "Adapter")  
###### <a href="https://commons.wikimedia.org/wiki/User:Lionel_Allorge">Lionel Allorge</a>, <a href="https://commons.wikimedia.org/wiki/File:Adaptateur_de_prise_fran�aise_en_prise_suisse_2.jpg">Adaptateur de prise fran�aise en prise suisse 2</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/legalcode">CC BY-SA 3.0</a>

* Implementation

UML: 
Class Adapter

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/classadapter.png "UML Class Adapter")

Object Adapter: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/objectadapter.png "UML Object Adapter")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to adapter folder:

```
$  cd /src/main/java/com/hundredwordsgof/adapter
```

##### <a id="Bridge"></a>Bridge
* Story

Decouple an abstraction from its implementation so that the two can vary independently.

Steering wheel is an example of the Bridge.
The purpose of a steering wheel is to transmit  driver's input to the steered wheels in order to dynamically change direction of the vehicle.
There are different implementations of the steering wheels used in cars, buses, tracks, tractors and formulas.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/bridge.jpg "Bridge")  
###### By Liftarn (Own work) [Public domain], <a href="https://commons.wikimedia.org/wiki/File%3A1924Stanley740-interior.jpg">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/bridge.png "UML Bridge")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to bridge folder:

```
$  cd /src/main/java/com/hundredwordsgof/bridge
```

##### <a id="Composite"></a>Composite
* Story

Compose objects into tree structures to represent part-whole hierarchies. 
Group of objects is to be treated in the same way as a single instance of an object. 

Lego brick represents Composite pattern. 
A brick is a basic object, but on a same time brick is a container which can hold other bricks in order to construct complex objects.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/composite.jpg "Composite")  
###### By Priwo (photo taken by de:Benutzer:Priwo) [Public domain], <a href="https://commons.wikimedia.org/wiki/File%3ALEGO-01.jpg">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/composite.png "UML Composite")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to composite folder:

```
$  cd /src/main/java/com/hundredwordsgof/composite
```

##### <a id="Decorator"></a>Decorator
* Story

Attach additional responsibilities to an object dynamically. 

The spoilers that are added to a car are examples of the Decorator.
The spoilers do not change the car itself, but adds additional functionality which is to 'spoil' unfavorable air movement across a body of a vehicle in motion, usually described as turbulence or drag.  

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/decorator.jpg "Decorator")  
###### <a href="http://www.flickr.com/people/15779944@N00">steve lyon</a> from los angeles, ca, usa, <a href="https://commons.wikimedia.org/wiki/File:2013_Porsche_911_Carrera_S_(8233337583).jpg">2013 Porsche 911 Carrera S (8233337583)</a>, <a href="https://creativecommons.org/licenses/by-sa/2.0/legalcode">CC BY-SA 2.0</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/decorator.png "UML Decorator")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to decorator folder:

```
$  cd /src/main/java/com/hundredwordsgof/decorator
```

##### <a id="Facade"></a>Facade
* Story

Facade hides the complexity of the system and provides an interface to the client from where the client can access the system.

You want to organize a marriage reception with dinner for 100 people. 
So in order to organize such event, you need to find and decorate a hall where the event will happen, 
then you need to find a music, organize flowers, send invitations and so on and so on.

If this is to much for you than you can find event manager which will organize event for you. 

This is a typical example for Facade. 

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/facade.jpg "Wedding Event Management")  
###### By WeMaxx1248 (Own work) [<a href="http://creativecommons.org/licenses/by-sa/4.0">CC BY-SA 4.0</a>], <a href="https://commons.wikimedia.org/wiki/File%3AEvent_management_in_pune.jpg">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/facade.png "UML Facade")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to facade folder:

```
$  cd /src/main/java/com/hundredwordsgof/facade
```

##### <a id="Flyweight"></a>Flyweight
* Story

Remove duplicates.

Flyweight pattern is used to reduce memory by loading only the data necessary to perform action.
Database normalization is flyweight. Normalisation, is the process of organizing the columns (attributes) and tables (relations) of a relational database to minimize data redundancy.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/flyweight.jpg "Database Normalization")  
###### By 04hutts (Own work) [Public domain], <a href="https://commons.wikimedia.org/wiki/File%3ANormalFormDiagram.png">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/flyweight.png "UML Flyweight")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to flyweight folder:

```
$  cd /src/main/java/com/hundredwordsgof/flyweight
```

##### <a id="Proxy"></a>Proxy
* Story

Provide a surrogate or placeholder for another object to control access to it.

Envoy Extraordinary is a Proxy. 
He is an accredited messenger, agent, or representative who is sent by one government to represent it in dealing with another government.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/proxy.jpg "The Envoy Extraordinary")  
###### By John Watkins (Kenwoon Mengyee, Burmese ambassador, The Envoy Extraordinary and Minister Plenipotentiary) [Public domain or Public domain], <a href="https://commons.wikimedia.org/wiki/File%3AKinwun_Mingyi.jpg">via Wikimedia Commons</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/proxy.png "UML Proxy")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to proxy folder:

```
$  cd /src/main/java/com/hundredwordsgof/proxy
```

##### <a id="ChainOfResponsibility"></a>Chain Of Responsibility
* Story

The Chain of Responsibility allows an object to send a command without knowing which object will receive and handle it. 
The request is sent from one object to another making them parts of a chain and each object in this chain can handle the command, pass it on or do both. 

Service request to call center is example of the Chain of Responsibility. 
Request can be handled at front desk level, supervisor level or any higher level. 
Correct handler of request is only known during execution of the request when request is traversing at various levels. 



* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/chainofresponsibility.png "UML Chain Of Responsibility")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to chainofresponsability folder:

```
$  cd /src/main/java/com/hundredwordsgof/chainofresponsibility
```


##### <a id="Command"></a>Command
* Story

Issue requests to objects without knowing anything about the operation being requested or the receiver of the request.

When your car needs service you visit Car Service Center. On reception you explain a problem and you leave a car.
The person at reception encapsulates the problem in to order for Car Technician. The order is queued internaly.
Car Technician will receive a request and fix a problem.

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/command.png "UML Command")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to command folder:

```
$  cd /src/main/java/com/hundredwordsgof/command
```

##### <a id="Interpreter"></a>Interpreter
* Story

A person who translates orally from one language into another.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/interpreter.jpg "Polish Sign Language - letter C")  
######  Polish Sign Language - letter C, By Tomt87 (Own work) [CC BY-SA 4.0 (http://creativecommons.org/licenses/by-sa/4.0)], via Wikimedia Commons


* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/interpreter.png "UML Command")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to command folder:

```
$  cd /src/main/java/com/hundredwordsgof/interpreter
```

##### <a id="Iterator"></a>Iterator
* Story

Book is a set of written, printed sheets bound together into a volume.
You can browse through the book page by page, or quickly jump to interesting chapter.
Process of browsing is example of Iterator pattern.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/iterator.jpg "Iterate book page by page")  
###### Open Book by Dave Dugdale, on Flickr&quot;&nbsp;(<a rel='license' href='https://creativecommons.org/licenses/by-sa/2.0/' target='_blank'>CC BY-SA 2.0</a>)&nbsp;by&nbsp; <a xmlns:cc='http://creativecommons.org/ns#' rel='cc:attributionURL' property='cc:attributionName' href='https://www.flickr.com/people/davedugdale/' target='_blank'>Dave Dugdale</a>


* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/iterator.png "UML Iterator")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to iterator folder:

```
$  cd /src/main/java/com/hundredwordsgof/iterator
```

##### <a id="Mediator"></a>Mediator
* Story

Defines an object that controls how a set of objects interact.

Radio Taxi is an example of the Mediator pattern.
Taxi drivers communicate with the Mediator(Radio Taxi Call Center), rather than with each other. 

When customer needs a taxi, he calls Radio Taxi Call Center. 
All taxis have a GPS unit which tells where the taxi is present right now, also there is a central information system which tells which taxi is available to serve the customer. 
The call center will contact the available taxi nearest to customer�s location and send them to serve the customer.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/mediator.jpg "Call Center Taxis Libres")  
###### Call Center Taxis Libres,By Jquemba (Own work) [Public domain], via Wikimedia Commons 

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/mediator.png "UML Mediator")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to mediator folder:

```
$  cd /src/main/java/com/hundredwordsgof/mediator
```

##### <a id="Memento"></a>Memento
* Story

Helps to restore an object�s state to it previous state.

Transactions are operations on the database that occur in an atomic, consistent, durable, and isolated fashion. 
A transaction can contain multiple operations on the database; each operation can succeed or fail, however a transaction guarantees that if all operations succeed, 
the transaction would commit and would be final. 
And if any operation fails, then the transaction would fail and all operations would rollback and leave the database as if nothing has happened.

This mechanism of rolling back uses the memento design pattern. 

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/memento.jpg "States of transaction")  
###### States of transaction 

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/memento.png "UML Memento")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to memento folder:

```
$  cd /src/main/java/com/hundredwordsgof/memento
```

##### <a id="Observer"></a>Observer
* Story

Keep me updated.

Newslettter subscription demonstrate Observer pattern.
A newsletter is a regularly distributed publication that is generally about one main topic of interest to its subscribers. 
Subscribers can subscribe or unsubscribe to the newsletters.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/observer.jpg "Newsletter")  
###### <a href="https://commons.wikimedia.org/wiki/User:Stevie_Benton_(WMUK)">Stevie Benton</a>, <a href="https://commons.wikimedia.org/wiki/File:Newsletter-banner-v2.jpg">Newsletter-banner-v2</a>, <a href="https://creativecommons.org/licenses/by-sa/3.0/legalcode">CC BY-SA 3.0</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/observer.png "UML Observer")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to observer folder:

```
$  cd /src/main/java/com/hundredwordsgof/observer
```

##### <a id="State"></a>State
* Story

Behavior depends on its state.

Pregnancy is time of great physical and emotional change for women. 
Everything from the size of her belly to the speed at which her heart beats will change over the nine months leading up to childbirth. 
Partly the result of hormonal fluctuations and partly the physical strain of carrying extra body weight, pregnant women can expect to buy new bras, 
search for ways to alleviate swollen ankles, gasp for breath after climbing a few stairs, and marvel at how quickly their nails grow.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/state.jpg "Human Pregnancy")  
###### <a href="http://flickr.com/photos/19616008@N00">Petteri Sulonen from Helsinki, Finland</a>, <a href="https://commons.wikimedia.org/wiki/File:Pregnant_graffiti.jpg">Pregnant graffiti</a>, <a href="https://creativecommons.org/licenses/by/2.0/legalcode">CC BY 2.0</a>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/state.png "UML State")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to state folder:

```
$  cd /src/main/java/com/hundredwordsgof/state
```

##### <a id="Strategy"></a>Strategy
* Story

Select an algorithm at runtime.

Payment options in a Shopping Cart is an example of Strategy.
User can choose various payment options like Master Card, Amex or PayPal.
Any of these payment options will pay items in Shopping Cart, and they can be used interchangeably. 
The user must choose the Strategy based on his possibilities, preferences.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/strategy.jpg "Credit Card")  
###### <a href='https://www.flickr.com/photos/mecklenburg/5417026496/' target='_blank'>Credit Card</a>&quot;&nbsp;(<a rel='license' href='https://creativecommons.org/licenses/by/2.0/' target='_blank'>CC BY 2.0</a>)&nbsp;by&nbsp;<a xmlns:cc='http://creativecommons.org/ns#' rel='cc:attributionURL' property='cc:attributionName' href='https://www.flickr.com/people/mecklenburg/' target='_blank'>ThomasKohler</a></div>

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/strategy.png "UML Strategy")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to state folder:

```
$  cd /src/main/java/com/hundredwordsgof/strategy
```

##### <a id="TemplateMethod"></a>TemplateMethod
* Story

Defines a skeleton of an algorithm in an operation.
Algorithm will have common and specialized part.

Daily routine is example of the Template method.
Every day workers get up(common part), go to work(specialized part), go home and go to sleep.
There are workers with different professions like enginners, teachers, etc.
During work engineer will fix machines while teacher will teach childern how to read and write.
At the end of the day worker go home, have a dinner and go to sleep.

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/templatemethod.png "UML Template")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to template folder:

```
$  cd /src/main/java/com/hundredwordsgof/templatemethod
```

##### <a id="Visitor"></a>Visitor
* Story

Allows for one or more operations to be applied to a set of objects at runtime, decoupling the operations from object structure.

Shopping in supermarket is example of the Visitor pattern. 
You pick a products and put them in shopping cart. When you get to the checkout, the cashier acts as a visitor, taking the 
disparate set of elements, some with prices and others that needs to be weighted, in order to provide you with total.

* Image

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/gh-pages-resources/visitor.jpg "Cashier in Supermarket")  
###### Cashier in Supermarket, CC0 Public Domain

* Implementation

UML: 

![alt text](https://github.com/dstar55/100-words-design-patterns-java/blob/master/src/main/resources/visitor.png "UML Visitor")

Source Code:

Clone repo:
```
$  git clone https://github.com/dstar55/100-words-design-patterns-java.git .
```

Move to visitor folder:

```
$  cd /src/main/java/com/hundredwordsgof/visitor
```
