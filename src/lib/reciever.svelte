<div class="form-container">
  <form id="reciepient" action="#" method="">
    <div class="bg-neutral w-screen h-screen">
      <div class="mx-auto pt-20 sm:px-6">
        <div
          class="card card-normal prose card-body bg-primary shadow-2xl mx-auto"
        >
          <h2 class="mx-auto">Reciever Info</h2>

          <div class="form-control">
            <label for="receptacle-id" class="label-text">Receptacle ID</label>
            <label class="input-group">
              <span>Scan Item</span>
              <input
                type="text"
                name="receptacle-id"
                id="receptacle-id"
                autocomplete="email"
                class="input shadow-md hover:shadow-lg"
              />
            </label>
          </div>

          <div class="form-control">
            <label for="postal-code" class="label-text">Tracking Number</label>
            <label class="input-group">
              <span>Scan Item</span>
              <input
                type="text"
                name="postal-code"
                id="postal-code"
                autocomplete="postal-code"
                class="input shadow-md hover:shadow-lg"
              />
            </label>
          </div>
          <div class="grid gap-4 grid-cols-2">
            <div class="form-control f-name">
              <label for="first-name" class="label-text">First Name</label>
              <input
                type="text"
                name="first-name"
                id="first-name"
                autocomplete="given-name"
                class="input shadow-md hover:shadow-lg"
              />
            </div>

            <div class="form-control l-name">
              <label for="last-name" class="label-text">Last Name</label>
              <input
                type="text"
                name="last-name"
                id="last-name"
                autocomplete="family-name"
                class="input shadow-md hover:shadow-lg"
              />
            </div>
          </div>
          <div class="form-control">
            <label for="street-address" class="label-text">Street Address</label
            >
            <input
              type="text"
              name="street-address"
              id="street-address"
              autocomplete="street-address"
              class="input shadow-md hover:shadow-lg"
            />
          </div>
          <div class="form-control">
            <label for="po-box" class="label-text">P.O. Box</label>
            <input
              type="text"
              name="po-box"
              id="po-box"
              autocomplete="street-address"
              class="input shadow-md hover:shadow-lg"
            />
          </div>

          <div class="form-control">
            <label for="city" class="label-text">City/Village</label>
            <input
              type="text"
              name="city"
              id="city"
              autocomplete="address-level2"
              class="input shadow-md hover:shadow-lg"
            />
          </div>

          <div class="form-control">
            <label for="parish" class="label-text">Parish</label>

            <select
              name="parish"
              id="parish"
              class="select select-bordered shadow-md hover:shadow-lg"
              required
            >
              <option
                disabled
                selected
                value="select-parish border-accent shadow-md"
                >Select Parish</option
              >
              <option value="st-george">Saint George</option>
              <option value="st-john">Saint John</option>
              <option value="st-mary">Saint Mary</option>
              <option value="st-paul">Saint Paul</option>
              <option value="st-peter">Saint Peter</option>
              <option value="st-philip">Saint Philip</option>
              <option value="barbuda">Barbuda</option>
            </select>
          </div>

          <label for="options" class="label-text">Package Condition</label>
          <div class="btn-group">
            <input
              type="radio"
              name="options"
              value="Good"
              data-title="GOOD"
              class="btn btn-success w-24 

            shadow-md hover:scale-105
            "
              required
            />
            <input
              type="radio"
              name="options"
              value="Damaged"
              data-title="DAMAGED"
              class="btn btn-warning w-24 

              shadow-md hover:scale-105
              "
            />
            <input
              type="radio"
              name="options"
              value="Violated"
              data-title="VIOLATED"
              class="btn btn-error w-24 

              shadow-md hover:scale-105
              "
            />
          </div>
          <div class="card-actions justify-end">
            <button
              type="submit"
              class="btn btn-secondary shadow-lg hover:shadow-xl hover:scale-110"
              >Save</button
            >
          </div>
          <!-- #TODO #FUTURE #FEATURE 
           <div class="col-span-6 sm:col-span-3 lg:col-span-2">
              <label for="postal-code" class="">ZIP / Postal code</label>
              <input type="text" name="postal-code" id="postal-code" autocomplete="postal-code" class="">
            </div> -->
        </div>
      </div>
    </div>
  </form>
</div>
