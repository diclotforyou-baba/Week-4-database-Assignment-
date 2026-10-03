<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Week 5 Database Assignment</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f2f2f2;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 1100px;
            margin: auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
        }

        h1 {
            text-align: center;
            color: #222;
        }

        .description {
            text-align: center;
            color: #555;
            margin-bottom: 25px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        th {
            background: #222;
            color: white;
            padding: 15px;
            text-align: left;
        }

        td {
            padding: 15px;
            border: 1px solid #ddd;
            vertical-align: top;
        }

        tr:nth-child(even) {
            background: #f8f8f8;
        }

        .question {
            width: 45%;
        }

        pre {
            background: #1e1e1e;
            color: #fff;
            padding: 15px;
            border-radius: 6px;
            overflow-x: auto;
        }

        button {
            background: #007bff;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #0056b3;
        }

        footer {
            text-align: center;
            margin-top: 25px;
            color: #777;
        }

        @media (max-width: 700px) {
            table {
                font-size: 14px;
            }

            td, th {
                padding: 10px;
            }
        }
    </style>
</head>

<body>

<div class="container">

    <h1>Week 5 Database Assignment</h1>

    <p class="description">
        Database Systems – SQL Assignment
    </p>

    <table>

        <thead>
            <tr>
                <th>Question</th>
                <th>SQL Code</th>
            </tr>
        </thead>

        <tbody>

            <tr>
                <td class="question">
                    <strong>Question 1</strong>
                    <p>
                        Write an SQL query to drop an index
                        named <strong>IdxPhone</strong> from
                        <strong>customers</strong> table.
                    </p>
                </td>

                <td>
                    <pre><code id="code1">DROP INDEX IdxPhone ON customers;</code></pre>
                    <button onclick="copyCode('code1', this)">
                        Copy Code
                    </button>
                </td>
            </tr>

            <tr>
                <td class="question">
                    <strong>Question 2</strong>
                    <p>
                        Write an SQL query to create a user
                        named <strong>bob</strong> with the password
                        <strong>S$cu3r3!</strong>, restricted to
                        the localhost hostname.
                    </p>
                </td>

                <td>
                    <pre><code id="code2">CREATE USER 'bob'@'localhost'
IDENTIFIED BY 'S$cu3r3!';</code></pre>
                    <button onclick="copyCode('code2', this)">
                        Copy Code
                    </button>
                </td>
            </tr>

            <tr>
                <td class="question">
                    <strong>Question 3</strong>
                    <p>
                        Write an SQL query to grant the
                        <strong>INSERT</strong> privilege to
                        user <strong>bob</strong> on the
                        <strong>salesDB</strong> database.
                    </p>
                </td>

                <td>
                    <pre><code id="code3">GRANT INSERT ON salesDB.*
TO 'bob'@'localhost';</code></pre>
                    <button onclick="copyCode('code3', this)">
                        Copy Code
                    </button>
                </td>
            </tr>

            <tr>
                <td class="question">
                    <strong>Question 4</strong>
                    <p>
                        Write an SQL query to change the password
                        for user <strong>bob</strong> to
                        <strong>P$55!23</strong>.
                    </p>
                </td>

                <td>
                    <pre><code id="code4">ALTER USER 'bob'@'localhost'
IDENTIFIED BY 'P$55!23';</code></pre>
                    <button onclick="copyCode('code4', this)">
                        Copy Code
                    </button>
                </td>
            </tr>

        </tbody>

    </table>

    <footer>
        Week 5 Database Assignment
    </footer>

</div>

<script>
    function copyCode(id, button) {

        const code = document.getElementById(id).innerText;

        navigator.clipboard.writeText(code).then(function () {

            const oldText = button.innerText;

            button.innerText = "Copied!";

            setTimeout(function () {
                button.innerText = oldText;
            }, 1500);

        });
    }
</script>

</body>
</html>
