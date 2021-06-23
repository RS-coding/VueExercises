# Vue Exercises

## Vue Exercises that I have been doing in my jorney.

Beginner Friendly  
Some are simple logic exercises others are mini-projects.
[Demo](https://rs-coding.github.io/VueExercises/)

Let's Go!

#### Note:

#### whoever wants to practice and contribute with new solutions:

- go to the **dev** branch and fork that branch by clicking on **fork** button
- copy the **url** of the document
- at your terminal write **git clone <url>** to download and work locally
- do the exercises in your code editor
- save the files exactly has they are with the same titles as mine using the commands **git add .** and **git commit -m "text"**
- after saving to your local repository do a **git push origin dev** to your github repository(forked file based on mine)
- go to my original project and make a **"pull request"**
- don't forget to write the necessary comments about what you did differently from what I did and what you think would be better.

---

### 01 - Exercise

#### **Task:**

- In an html file add the script source of Vue.js inside <script src=""> tag
- Inside Body tag you will create your first app by adding a div with id called app
- Inside the div tag create a paragraph that will be interpolated by Vue.js
- Create your first Vue new instance inside the <script> tags before </body>.
- Inside the new Vue Instance ,has you may know, you have to add the el and data properties.
- Inside data, create a property called title with the value ' Using Vue JS'
- now you have to interpolate by adding that title inside the paragraph <p>

#### _Subjects Tips:_

_Add script src vue [link](https://vuejs.org/v2/guide/index.html#Getting-Started)_, _Declare and rending [link](https://vuejs.org/v2/guide/index.html#Declarative-Rendering)_,

**Resolution:** [Code](https://github.com/RS-coding/VueExercises/blob/main/solutions_exercises/01exercise.html)

---

### 02 - Exercise

#### **Task:**

- Doing the same thing as exercise number 1
- add a method changeMessage() in vue instance , get the title propriety and change to 'Vue.JS is really cool'
- interpolate by using the name of the method in the paragraph

#### _Subjects Tips:_

_Data and Methods [link](https://vuejs.org/v2/guide/instance.html#Data-and-Methods)_

**Resolution:** [Code](https://github.com/RS-coding/VueExercises/blob/main/solutions_exercises/02exercise.html)

---

### 03 - Exercise

#### **Task:**

- create a link tag '<a>' inside the the div '#app' with text 'click here to learn more about v-bind attribute'
- in the vue instace create a property called link with the value 'https://vuejs.org/v2/guide/syntax.html#Attributes'
- bind that value inside the link tag '<a>' using the attribute v-bind

#### _Subjects Tips:_

_v-bind Attribute [link](https://vuejs.org/v2/guide/syntax.html#Attributes)_

**Resolution:** [Code](https://github.com/RS-coding/VueExercises/blob/main/solutions_exercises/03exercise.html)

---

### 04 - Exercise

#### **Task:**

- Create a div #app with two paragraphs
- in the Vue instance create a property called title with the vale "Using Vue' and create a method called greeting() that take that property and change to "Welcome".
  -In first paragraph interpolate the title and in the second paragraph interpolate the methid greeting() using double moustache syntax (double curly braces)
- you may notice that when there is a changing in some value at vue instance, it is automaticaly updated so both paragraphs have the same result.
- Add in the first paragraph a directive that allows to show the previous value of title property before it was changed by the metthod grreting(). can you remember which is ?

#### _Subjects Tips:_

_Directives [link](https://vuejs.org/v2/guide/syntax.html#Directives)_

**Resolution:** [Code](https://github.com/RS-coding/VueExercises/blob/main/solutions_exercises/04exercise.html)

---

### 05 - Exercise

#### **Task:**

- Create a div #app with 1 paragraph
- add in that paragraph a directive that prints pure HTML .For example a tag <a href="https://vuejs.org/">Vue Documentation</a> that is the value of a proprety in Vue instance.
- You may notice the result by inspect the elements and see that was added a tag a inside the paragraph

#### _Subjects Tips:_

_Directives [link](https://vuejs.org/v2/guide/syntax.html#Directives)_

**Resolution:** [Code](https://github.com/RS-coding/VueExercises/blob/main/solutions_exercises/04exercise.html)
