# Alt Text Button

Template for a button you can add to images on your website to visibly show/hide alt text.

## Demo

https://github.com/user-attachments/assets/670a5b19-0a72-4f80-96db-7870ec32a8c8

## How to Use

First, download the `alt-text-button.css` file and include it in your site HTML.

Then, use the following structure for your images:

```html
<figure>
    <picture>
        <img alt="A supermarket in Berlin with a sign that reads 'freshly made smiles'." loading="lazy" src="https://jamesg.blog/assets/smiles.avif">
    </picture>
    <details class="alt" aria-label="Show or hide the alt text for the image">
        <summary>ALT</summary>
        <p>A supermarket in Berlin with a sign that reads "freshly made smiles".</p>
    </details>
</figure>
```

## License

This project is licensed under an MIT-0 license.
