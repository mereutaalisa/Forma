<!DOCTYPE html>
<html>
    <head>
        <title>Inregistrare</title>
    </head>
    <body>
        <h2>Inregistrare</h2>
        <form>
            <label for="nume">Numele </label>
            <input type="text" id="nume" name="nume"><br></br>
            
            <label for="prenume">Prenumele</label>
            <input type="text" id="prenume" name="prenume"><br></br>
           
            <label for="data">Data</label>
            <input type="date" id="data" name="data"><br></br>
            
            <label for="alege">Alege din  lista</label>
            <select id="alegere" name="alege">
                    <option value="zi">Zi</option>
                    <option value="luna">Luna</option>
                    <option value="anul">Anul</option>
            </select><br></br>

             <input type="submit" value="Salveaza">
             <input type="button" value="Sterge">
         </form>
    </body>
</html>
