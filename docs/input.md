<h6 class="subtitle is-5 has-text-grey has-text-weight-semibold">Component</h6><h1 class="title is-1 has-text-weight-bold">Input</h1>
<p class="subtitle is-5"><span class="has-text-weight-semibold">Input fields</span> enable users to provide information.</p>

<hr class="is-visible is-large">

<form class="box is-relaxed has-background-light is-marginless" spellcheck="false">
    <input class="input is-small" type="tel" placeholder="Small input">
    <hr class="is-small">
    <input class="input" type="tel" placeholder="Normal input">
    <hr class="is-small">
    <input class="input is-medium" type="email" placeholder="Medium input">
</form>

    <input class="input is-medium" type="text" placeholder="..">


<hr class="is-visible is-large">

<h2 class="title is-4">Form fields</h2>

<form class="box has-background-light is-relaxed is-marginless" spellcheck="false">
    <div class="field">
        <label for="demofield" class="label">With a label</label>
        <input id="demofield" class="input" type="text" placeholder="Some input">
    </div>
    <div class="field">
        <label for="textfield" class="label">Textarea</label>
        <textarea id="textfield" class="textarea" placeholder="For looong text inputs.."></textarea>
    </div>
</form>

    <form>
        <div class="field">
            <label for="demofield" class="label">Label</label>
            <input id="demofield" class="input" type="text">
        </div>
        <div class="field">
            <label for="textfield" class="label">Textarea</label>
            <textarea id="textfield" class="textarea" placeholder="..."></textarea>
        </div>
    </form>

!> A field's Label should always have a `for="..."` attribute corresponding to the field ID it is refering to.

<hr class="is-large">

<div class="box is-bordered">
    More options on &nbsp;→&nbsp; <a href="https://bulma.io/documentation/form/input/" target="blank">Bulma / <strong>Input</strong></a>
</div>