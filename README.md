<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>payment form</title>
</head>
<body>
   <form action="">
    <h1>payment Form</h1>
    <p>Required filled are folled by *</p>
    <h2>Contact informationp
        <p>Name:-* <input type="text" name="Name" required></p>
       <fieldset>
        <legend>Gender *</legend>
        <p>
            male <input type="radio" name="Gender" required id="male">
            female <input type="radio" name="Gender" required id="female">
        </h2>
           
        </p>
        <fieldset>
            <p>Address: <textarea name="Address" id="Address" cols="30" rows="7"></textarea></p>
            <p>Email:* <input type="email" name="Email" required id="">
    <p>Pincode: *<input type="number" name="Pincode" id="Pincode" required></p>
    <p>Mob:* <input type="number" name="Mob." id="Mob." required></p>
    <h2> Payment information * 
    <p>Card type:
        <select name="Card type" required id="Card type">
        <option value="">---select a card type---</option>
        <option value="visa">visa</option>
        <option value="master card">master card</option>
        <option value="rupay">rupay</option>
    </select>
    </p>
           
            <p>
                card number * <input type="number" name="card number" required id="card number">
            </p>
            <p>
                Expiration date: *<input type="date" name="exp_date" required id="exp_date">
            </p>
            <p>
                CVV: * <input type="password" name="CVV"required id="CVV">
            </p>
            <input type="submit" value="pay Now">
        </h2>
   </form> 
</body>
</html>
