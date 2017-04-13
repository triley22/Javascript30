Javascript 3/30 CSS Variables

What I learned:

CSS Variables are accessible via JavaScript on any DOM node using setProperty method.

function handleUpdate(e) {
  const suffix = this.dataset.sizing || '';
  document.documentElement.style.setProperty(`--${this.name}`, this.value + suffix);
}

Above we are listening to updates on input elements and reassigning CSS Variable on 
the document root with the same name as the input, and using the input's 
value as the CSS Variable's value.

NodeLists have limited functionality compared to Arrays.
NodeLists can be converted to Arrays.

Used dataset property of an element to access values of data attributes on it.