
## Validate form 

- A library to use as a form validate
- Convenient in validating form fields by adding rules attribute as shown below


```bash
<div class="form-group">
    <label for="email" class="form-label">Email</label>
    <input id="email" rules="required|email" name="email" type="text" placeholder="VD: email@domain.com"
    class="form-control" />
    <span class="form-message"></span>
</div>
```

You can add rules in the input tag

```bash
rules="required|email"
```

