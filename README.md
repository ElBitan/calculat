<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width" />
  <title>calculatrice </title>
  <link rel="stylesheet" href="calculatrice.css" />
</head>
<body>
         <center>
      <h1 class="title">calculatrice de bête<h1>
      <table>
        <tr>
          <td colspan="4" align="right" id="case">
            <span id="calc-output"></span>
          </td>
        </tr>
     </table>
     <table>
       <tr>
         <td>
           <input class="number" type="button" value="1" id="button-1" onclick="btm(1)"/>
         </td>
         <td>
           <input class="number" type="button" value="2" id="button-2" onclick="btm(2)"/>
         </td>
         <td>
           <input class="number" type="button" value="3" id="button-3" onclick="btm(3)"/>
         </td>
         <td>
           <input class="operator" type="button" value="C" id="button-C" onclick="btmClean()"/>
         </td>
       </tr>

       <tr>
         <td>
           <input class="number" type="button" value="4" id="button-4" onclick="btm(4)"/>
         </td>
         <td>
           <input class="number" type="button" value="5" id="button-5" onclick="btm(5)"/>
         </td>
         <td>
           <input class="number" type="button" value="6" id="button-6" onclick="btm(6)"/>
         </td>
         <td>
           <input class="operator" type="button" value="+" id="button-+" onclick="btmPlus()"/>
         </td>
       </tr>

       <tr>
         <td>
           <input class="number" type="button" value="7" id="button-7" onclick="btm(7)"/>
         </td>
         <td>
           <input class="number" type="button" value="8" id="button-8" onclick="btm(8)"/>
         </td>
         <td>
           <input class="number" type="button" value="9" id="button-9" onclick="btm(9)"/>
         </td>
         <td>
           <input class="operator" type="button" value="-" id="button--" onclick="btmLess()"/>
         </td>
       </tr>
<tr>
         <td>
    <input class="operator" type="button" value="x" id="button-*" onclick="btmMultiply()"/>
         </td>
         <td>
           <input class="number"type="button" value="0" id="button-0" onclick="btm(0)"/>
         </td>
         <td>
   <input class="operator" type="button" value="÷" id="button-/" onclick="btmDivision()"/>
         </td>
         <td>
           <input class="operator" type="button" value="=" id="button-=" onclick="btmEgal()"/>
         </td>
       </tr>

     </table>
     </center>

  


  <script src="calculatrice.js"></script>
</body>
</html>
