<script setup lang="ts">

</script>

<template>
    <h1>This is a demo page</h1>
    <hr />
    <h2>Text demo</h2>

    <h1>This is Heading 1</h1>
    <h2>This is Heading 2</h2>
    <h3>This is Heading 3</h3>
    <h4>This is Heading 4</h4>
    <h5>This is Heading 5</h5>
    <h6>This is Heading 6</h6>

    <p><strong>This is a bolded text. </strong>This text is back to normal, <i>but this is an italics. </i><a
            href='#'>There can be a link as well!</a></p>
    <blockquote>This is a quote.</blockquote>
    <hr />

    <h2>List demo</h2>
    <ol>
        <li>This is an element of an ordered list.</li>
        <li><strong>You can put anything inside.</strong></li>
        <li>Even other lists
            <ul style="list-style-type:square;">
                <li>And then nest them to your liking</li>
                <li>But in my opinion
                    <ul style="list-style-type:circle;">
                        <li>This might be an overkill</li>
                        <li><br>
                            <ul style="list-style-type:circle;">
                                <li>And isn't really used that much (no shit, I can see why ;-;)</li>
                            </ul>
                        </li>
                    </ul>
                </li>
            </ul>
        </li>
    </ol>
    <hr />

    <h2>Table demo</h2>
    <table>
        <tr>
            <th>Column 1</th>
            <th>Column 2</th>
        </tr>
        <tr>
            <td>Row 1, Column 1</td>
            <td>Row 1, Column 2</td>
        </tr>
        <tr>
            <td>Row 2, Column 1</td>
            <td>Row 2, Column 2</td>
        </tr>
    </table>
    <hr />

    <h2>Media demo</h2>
    <img src="https://i.pinimg.com/550x/45/ec/05/45ec05f86698752abd5d22214e601f3d.jpg"><br>
    <iframe width="420" height="315" src="https://www.youtube.com/watch?v=4UuxIrxEYSY">
    </iframe>

    <h2>Interactive form demo</h2>
    <form>
        <label for="name">Name</label>
        <input type="text" id="name" name="name"><br>

        <label for="surname">Surname</label>
        <input type="text" id="surname" name="surname"><br>

        <label for="country">Choose a Country</label>
        <select name="country">
            <option value="">Country</option>
            <option value="lmanberg">L'Manberg</option>
        </select><br>

        <label for="message">Send a Message</label>
        <textarea name="message">Provide a message</textarea><br>

        <input type="submit" value="Submit form">
    </form>
</template>

<style scoped>
</style>
