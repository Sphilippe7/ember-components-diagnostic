# Ember Components Diagnostic

Record your responses inside the fenced code blocks below each question.

1.  Give an example of a visual hierarchy that could be modeled with components. Explain why each piece might be it's own component.

    ```md

    ```

1.  What is the command to generate a new component called '`my-map`'?

    ```sh
    ember generater component my-map
    ```

1.  What files are created and/or edited to produce a component, and what are their responsibilities?

    ```md
    a folder with the name of what you generated
    withing that folder is a component and a template file
    ```

1.  Suppose you have a component '`my-contact`', which is loaded from
    '`app/contacts/template.hbs`' when visiting the `/contacts` route. What is
    the syntax (code that is written) to render this component inside that template?

    ```html
    {{#each model as |contacts|}}
        {{contacts/my-contact my-contacts=my-contacts}}
    {{/each}}
    ```

1.  Each contact has multiple phone numbers. Suppose you also have '`my-phone`'
    nested under '`my-contact`'. What is the code you would write in
    '`app/components/my-contact/template.hbs`' to load the nested component and
    pass it data?

    ```html
    <!-- your response here -->
    ```
