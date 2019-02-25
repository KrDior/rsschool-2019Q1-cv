Saveli Savich
============

-------------------     ----------------------------
e-mail:                        <krdiorka@gmail.com>
mobile:                            +37529 765-09-50
-------------------     ----------------------------


Summary
--------

**Why I will be part of your team:**

Every day I wake up with thoughts that I **must something change** that I can do it. I suppose I’m technical guy and I like all around tech sphere. Like in RPG game I *like to improve my skills/ability*, in this way programming it’s amazing case for live gaming **where you could improving yourself** so much as you can.
Nowadays I’m a little less than 30 and I know *how need work*, what I want and I totally sure that without permanent *self-development* I can not be… 

Skills
------

*Programming languages:*
:   **first-lang:** Python beginning knowledge (online course in [Stepik.org](https://stepik.org/course/67));

:   **second-lang:** 
- javaScript beginning knowledge (reading [developer.mozilla](https://developer.mozilla.org/ru/), [javascript.ru](http://www.javascript.ru) and other online articles; online course in [Stepik.org](https://stepik.org); workout in [freeCodeCamp](https://www.freecodecamp.org/));
- HTML/CSS online course in [coursera.org](https://www.coursera.org/learn/html-css-javascript-for-web-developers?).


Implementation data structure  double linked list:
---------------------------------------------------
```
function Node(element) {
    this.element = element;
    this.next = null;
    this.prev = null;
};

function DoublyLinkedList() {
    this.head = null;
    this.tail = null;
    this.length = 0;
};

DoublyLinkedList.prototype.addToHead = function (element) {
    let node = new Node(element);
    if (this.head) {
        this.head.prev = node;
        node.next = this.head;
    } else {
        this.tail = node;
    }
    this.head = node;
    this.length++;
};

DoublyLinkedList.prototype.addToTail = function (element) {
    let node = new Node(element);
    if (this.tail) {
        this.tail.next = node;
        node.prev = this.tail;
    } else {
        this.head = node;
    }
    this.tail = node;
    this.length++;
};
```

Experience:
------------
*HTML coding example:* [link](http://mjane.surge.sh/)

Education:
----------

***BSUIR*** // all online courses look please paragraph №4.

### Plugins

Have experience with the following plugins. You can see list of them below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Fontello | [plugins/fontello-webpack-plugin/README.md][PlFW] |

Language skills:
-----------------

Between **B1** and **B2** level. I have *experience of studying in English*; can **read unadapted** literature.

> I will be studying!
> I will be work hard!
> I will be better!

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlFW]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/fontello/fontello/wiki/Help/README.md>