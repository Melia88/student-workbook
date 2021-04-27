# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
We can do one way binding using {{ }} and/or :attribute <div :class="container"></div> which means that the variable is just bound to the DOM. And 2 way data binding with v-model which allows us to get and minipulate data. This would be used on a form submission like
 <input v-model="linuxhintText" placeholder="Type something" />
<p>You are typing: {{ linuxhintText }}</p></td>

```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
Single Page Application
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
A Spa uses one homepage that has things injected into it so it loads faster and can use the a lot of the same collections which will just switch out the data in them.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is like the _draw in MVC and it updates the page with the info within the onMounted as soon as its loaded.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
Creates a two-way binding on a form input element. Data is synced on every input event by default.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
it attaches a listener to an element like at onClick is now an @click or an onSubmit is now an @submit
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key attribute is ued to pass something unique about each object you pass. Like an id is unique to each post and a name could be unique to a different object.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```

```