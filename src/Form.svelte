

<form>
    <div>
        <label for="sending_postalcode">Sending Postal Code</label>
        <input required type="postalcode" id="sending_postalcode"/>

        <label for="going_postalcode">Going Postal Code</label>
        <input requred type="postalcode" id="going_postalcode"/>
    </div>

    <h3>Size</h3>

    <div>
        <label for="Unit">Unit</label>
        <input type="radio" name="cm" value="cm">cm
        <input type="radio" name="inches" value="inches">in.<br>
    </div>

    <div>
        <label for="length">Length</label>
        <input required type="number" id="length">
    </div>

    <div>
        <label for="width">Width</label>
        <input required type="number" id="Width"/>
    </div>

    <div>
        <label for="height">height</label>
        <input required type="number" id="height"/>
    </div>

    <h3>Weight</h3>

    <div>
        <label for="Unit">Unit</label>
        <input type="radio" name="kg" value="kg">kg
        <input type="radio" name="lb" value="lb">lb.<br>
    </div>

    <div>
        <label for="weight">Weight</label>
        <input required type="number" id="weight">
    </div>

</form>