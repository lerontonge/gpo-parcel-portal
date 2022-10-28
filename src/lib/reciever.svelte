<form id="reciepient" action="#" method="">
    <div class="">
      <div class="">
        <div class="">
          <h2>Reciever Info</h2>

          <div class="">
            <label for="receptacle-id" class="">Receptacle ID</label>
            <input
              type="text"
              placeholder="Scan Item"
              name="receptacle-id"
              id="receptacle-id"
              autocomplete="email"
              class=""
            />
          </div>

          <div class="">
            <label for="postal-code" class="">Tracking Number</label>
            <input
              type="text"
              placeholder="Scan Item"
              name="postal-code"
              id="postal-code"
              autocomplete="postal-code"
              class=""
            />
          </div>
          <div class="">
            <label for="first-name" class="">Package Condition</label>
            <input
              type="text"
              name="first-name"
              id="first-name"
              autocomplete="given-name"
              class=""
            />
          </div>

          <div class="">
            <label for="first-name" class="">First Name</label>
            <input
              type="text"
              name="first-name"
              id="first-name"
              autocomplete="given-name"
              class=""
            />
          </div>

          <div class="">
            <label for="last-name" class="">Last Name</label>
            <input
              type="text"
              name="last-name"
              id="last-name"
              autocomplete="family-name"
              class=""
            />
          </div>

          <div class="">
            <label for="street-address" class="">Street Address</label>
            <input
              type="text"
              name="street-address"
              id="street-address"
              autocomplete="street-address"
              class=""
            />
          </div>
          <div class="">
            <label for="po-box" class="">P.O. Box</label>
            <input
              type="text"
              name="po-box"
              id="po-box"
              autocomplete="street-address"
              class=""
            />
          </div>

          <div class="">
            <label for="city" class="">City/Village</label>
            <input
              type="text"
              name="city"
              id="city"
              autocomplete="address-level2"
              class=""
            />
          </div>

          <div class="">
            <label for="region" class="">Parish</label>

            <select name="cars" id="region">
              <option value="select-parish">Select Parish</option>
              <option value="st-george">Saint George</option>
              <option value="st-john">Saint John</option>
              <option value="st-mary">Saint Mary</option>
              <option value="st-paul">Saint Paul</option>
              <option value="st-peter">Saint Peter</option>
              <option value="st-philip">Saint Philip</option>
              <option value="barbuda">Barbuda</option>
            </select>
          </div>

          <div class="package-condition-container">
            <h3>Package Condition</h3>
            <label for="good" class="">Good</label>
            <input
              type="radio"
              name="condition"
              id="good"
              class=""
              value="good"
            />
            <label for="damaged" class="">Damaged</label>
            <input
              type="radio"
              name="condition"
              id="damaged"
              class=""
              value="damaged"
            />
            <label for="violated" class="">Violated</label>
            <input type="radio" name="condition" id="violated" class=""
            value="violated">
          </div>

          <!-- #TODO #FUTURE #FEATURE 
           <div class="col-span-6 sm:col-span-3 lg:col-span-2">
              <label for="postal-code" class="">ZIP / Postal code</label>
              <input type="text" name="postal-code" id="postal-code" autocomplete="postal-code" class="">
            </div> -->
        </div>
      </div>
      <div class="">
        <button type="submit" class="">Save</button>
      </div>
    </div>
</form>