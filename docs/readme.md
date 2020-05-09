# SASS Kickstart Documentation

## Typography
``` html
<h1>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</h1>
```

## Notification 
Use this for showing message for ```.success```, ```.warning```, ```.error``` will work with ```.message``` class
### Basic
``` html
<div class="message error">
    <p>Vestibulum ante ipsum primis in <strong>faucibus orci luctus et ultrices posuere cubilia Curae;
        </strong>In eleifend, eros in molestie condimentum</p>
    </div>

<div class="message success">
    <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; In
        eleifend, eros in molestie condimentum</p>
</div>

<div class="message warning">
    <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; In
        eleifend, eros in molestie condimentum</p>
</div>

<div class="message">
    <p>Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; In
        eleifend, eros in molestie condimentum</p>
</div>
```

### Advance with title
Even you can add sensible title for message by adding ```strong``` tag inside the ```.message``` div
``` html
<div class="message error">
    <strong>Oops!! Something went wrong</strong>
    <p>Vestibulum ante ipsum primis in <strong>faucibus orci luctus et ultrices posuere cubilia Curae;
        </strong>In eleifend, eros in molestie condimentum</p>
</div>
```

## Form Elements
### Buttons
``` html
<button class="button">Button</button>
<button class="button" disabled>Button disabled</button>
<button class="button large">Button large</button>
<button class="button small">Button small</button>
```

### Buttons (primary)
``` html
<button class="button primary">Button primary</button>
```

### Buttons (secondary)
``` html
<button class="button secondary">Button secondary</button>
```

### Buttons fluid (full-width)
``` html
<button class="button fluid">Button fluid</button>
```

### Input
``` html
<input type="text" class="input type-text" placeholder="this is text">
<br>
<input type="number" class="input type-number" placeholder="this is number">
<br>

<input type="text" class="input type-number" placeholder="this is number type text"><br>
<input type="email" class="input type-email" placeholder="this is email"><br>
```

### input fluid
use fluid class for full width ```.fluid``` on any element of form
``` html
<input type="text" class="input type-text fluid" placeholder="this is text">
```

### Checkbox
``` html
<div class="control-groups">
    <label class="control control--checkbox">First checkbox
        <input type="checkbox" checked="checked" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--checkbox">Second checkbox
        <input type="checkbox" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--checkbox">Disabled
        <input type="checkbox" disabled="disabled" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--checkbox">Disabled & checked
        <input type="checkbox" disabled="disabled" checked="checked" />
        <div class="control__indicator"></div>
    </label>
</div>
```

### Radio
``` html
<div class="control-groups">
    <h4>Radio buttons</h4>
    <label class="control control--radio">First radio
        <input type="radio" name="radio" checked="checked" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--radio">Second radio
        <input type="radio" name="radio" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--radio">Disabled
        <input type="radio" name="radio2" disabled="disabled" />
        <div class="control__indicator"></div>
    </label>
    <label class="control control--radio">Disabled & checked
        <input type="radio" name="radio2" disabled="disabled" checked="checked" />
        <div class="control__indicator"></div>
    </label>
</div>
```

### Select
``` html
<div class="control-groups">
    <h4>Select boxes</h4>
    <div class="select">
        <select>
            <option>First select</option>
            <option>Option</option>
            <option>Option</option>
        </select>
        <div class="select__arrow"></div>
    </div>
    <div class="select">
        <select>
            <option>Second select</option>
            <option>Option</option>
            <option>Option</option>
        </select>
        <div class="select__arrow"></div>
    </div>
    <div class="select">
        <select disabled="disabled">
            <option>Disabled</option>
            <option>Option</option>
            <option>Option</option>
        </select>
        <div class="select__arrow"></div>
    </div>
</div>
```


