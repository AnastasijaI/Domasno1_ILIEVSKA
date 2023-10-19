<!DOCTYPE html>

<html>
  <head>
      <meta charset = "utf-8">
      <title>Domasno1</title>
  </head>
  <body>
     <form>
        <table border="2">
            <tr>
              <th colspan='2'>Pizza Shop 2.0</th>
            </tr>
            <tr>
              <td>Name</td>
                <td><input name="name" type="text" size="25" maxlength="30">
            </tr>
            <tr>
              <td>Pizza Toping</td>
                <td><input type="radio"> Supreme<br>
                  <input type="radio"> Vegetarian<br>
                    <input type="radio"> Hawaiian<br>
            </tr>
            <tr>
              <td>Pizza Sauce</td>
                <td><select name="sos">
                    <option>Tomato</option>
                    <option>Alfredo</option>
                    <option>Spicy</option>
                    <option>Barbecue</option>
                    <option>Dipping</option>
                    <option>Cucumber</option>
                  </select>
              </td>
            </tr>
            <tr>
              <td>Optional Extras</td>
                <td><input type="checkbox"> Extra Cheese
                  <input type="checkbox"> Gluten Free Base
            </tr>
            <tr>
              <td colspan='2'>Delivery Instruction:<br><textarea row="50" cols="50">
                  </textarea>
                </td>
                </tr>
            <tr>
                <td colspan='2'><input type="submit" value="Send my order">
                </td>
            </tr>

        </table>
      </form> 
  </body>
</html>
