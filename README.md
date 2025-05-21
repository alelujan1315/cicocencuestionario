<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Autoevaluación de Grado de Riesgo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #f3f9f8;
        }
        h1 {
            text-align: center;
            color: #219598;
            font-family: "Times New Roman", serif;
            font-size: 2em;
            margin-bottom: 5px;
        }
        h2 {
            text-align: center;
            color: #219598;
            font-family: Arial, sans-serif;
            font-size: 1.2em;
            margin-bottom: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ccc;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: #219598;
            color: white;
        }
        td {
            background-color: #ffffff;
        }
        .submit-btn {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #219598;
            color: white;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }
        .submit-btn:hover {
            background-color: #197a73;
        }
        .result {
            text-align: center;
            font-size: 18px;
            color: #219598;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>CICOCEN CONSULTORES</h1>
    <h2>Autoevaluación de grado de riesgo</h2>
    <form id="riskForm">
        <table>
            <thead>
                <tr>
                    <th>Pregunta</th>
                    <th>A</th>
                    <th>B</th>
                    <th>C</th>
                    <th>No Aplica</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>¿Cuál es la altura máxima de la edificación?</td>
                    <td><input type="radio" name="q1" value="A"> Menos de 25 m2</td>
                    <td><input type="radio" name="q1" value="B"> </td>
                    <td><input type="radio" name="q1" value="C"> Más de 25 m2</td>
                    <td><input type="radio" name="q1" value="NA"></td>
                </tr>
                <tr>
                    <td>¿Cuál es la superficie total del establecimiento?</td>
                    <td><input type="radio" name="q2" value="A"> Hasta 299 m2</td>
                    <td><input type="radio" name="q2" value="B"> De 300 a 2,999 m2</td>
                    <td><input type="radio" name="q2" value="C"> 3,000 m2 o más</td>
                    <td><input type="radio" name="q2" value="NA"> </td>
                </tr>
                <tr>
                    <td>¿Cuál es la capacidad de carga eléctrica máxima del establecimiento?</td>
                    <td><input type="radio" name="q3" value="A"> 100 volts</td>
                    <td><input type="radio" name="q3" value="B"> 220 volts</td>
                    <td><input type="radio" name="q3" value="C"> Subestación o transformador</td>
                    <td><input type="radio" name="q3" value="NA"></td>
                </tr>
                <tr>
                    <td>¿Almacena o maneja materiales explosivos?</td>
                    <td><input type="radio" name="q4" value="A"> No</td>
                    <td></td>
                    <td><input type="radio" name="q4" value="C"> Sí</td>
                    <td><input type="radio" name="q4" value="NA"> </td>
                </tr>
                <tr>
                    <td>¿Almacena o maneja líquidos inflamables?</td>
                    <td><input type="radio" name="q5" value="A"> Hasta 249 L</td>
                    <td><input type="radio" name="q5" value="B"> De 250 a 999 L</td>
                    <td><input type="radio" name="q5" value="C"> 1,000 L o más (gasolinera)</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
                </tr>
                 <tr>
                    <td>¿Almacena o maneja químicas, corrosivas, irritantes o tóxicas?</td>
                    <td><input type="radio" name="q5" value="A"> Hasta 49 Kg</td>
                    <td><input type="radio" name="q5" value="B"> De 50 a 99 kg</td>
                    <td><input type="radio" name="q5" value="C"> 100 kg o más</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr>
                <tr>
                    <td>¿Almacena o maneja material sólido de alta combustión (papel, cartón, madera, plástico)?</td>
                    <td><input type="radio" name="q3" value="A"> Hasta 999 kg</td>
                    <td><input type="radio" name="q3" value="B"> De 1,000 a 4,999 kg</td>
                    <td><input type="radio" name="q3" value="C"> 5,000 kg</td>
                    <td><input type="radio" name="q3" value="NA"></td>
                </tr>
                <tr>
                    <td>Instalación de aprovechamiento de gas:</td>
                    <td><input type="radio" name="q5" value="A"> Doméstico</td>
                    <td><input type="radio" name="q5" value="B"> Natural o Comercial</td>
                    <td><input type="radio" name="q5" value="C"> Uso Industrial</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr> 
                <tr>
                    <td>Número total de personas que ocupan el local (incluyendo clientela y trabajadores):</td>
                    <td><input type="radio" name="q5" value="A"> Hasta 14 personas</td>
                    <td><input type="radio" name="q5" value="B"> de 15 a 249 personas</td>
                    <td><input type="radio" name="q5" value="C"> 250 personas o más</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr> 
                <tr>
                    <td>¿Tiene venta de bebidas alcohólicas?</td>
                    <td><input type="radio" name="q5" value="A"> No</td>
                    <td><input type="radio" name="q5" value="B"> Sí, en envase cerrado o aforo de 84 personas</td>
                    <td><input type="radio" name="q5" value="C"> Sí, en envase abierto o aforo de 85 personas o más</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr> 
                <tr>
                    <td>¿El establecimiento es una estancia infantil, guardería o centro educativo??</td>
                    <td><input type="radio" name="q5" value="A"> No</td>
                    <td><input type="radio" name="q5" value="B"> Ludoteca</td>
                    <td><input type="radio" name="q5" value="C"> Sí</td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr>
                <tr>
                    <td>¿El desarrollo de sus actividades requiere el uso de equipo de Protección Personal (E.P.P.)?</td>
                    <td><input type="radio" name="q5" value="A"> No</td>
                    <td><input type="radio" name="q5" value="B"> Sí</td>
                    <td><input type="radio" name="q5" value="C"> </td>
                    <td><input type="radio" name="q5" value="NA"> </td>
               </tr>            
            </tbody>
        </table>
        <button type="button" class="submit-btn" onclick="calculateRisk()">Calcular Grado de Riesgo</button>
    </form>
    <p class="result" id="result"></p>
    <script>
        function calculateRisk() {
            const form = document.getElementById('riskForm');
            const formData = new FormData(form);
            let aCount = 0, bCount = 0, cCount = 0;

            for (let value of formData.values()) {
                if (value === 'A') aCount++;
                if (value === 'B') bCount++;
                if (value === 'C') cCount++;
            }

            let result = '';
            if (cCount > 0) {
                result = "ALTO";
            } else if (bCount > 0) {
                result = "MEDIANO";
            } else {
                result = "BAJO";
            }

            document.getElementById('result').textContent = `Grado de Riesgo: ${result}`;
        }
    </script>
</body>
</html>
