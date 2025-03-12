<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        /* Inline CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-image: url(https://assets.onecompiler.app/42zp5pya9/43bjn4kvr/1812589.jpg);
            color: white;
            text-align: center;
            padding: 1em;
        }
        nav {
            text-align: center;
            margin: 10px 0;
        }
        nav a {
            text-decoration: none;
            margin: 0 10px;
            color: #4CAF50;
        }
        nav a:hover {
            color: #007BFF;
        }
        main {
            padding: 20px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        a {
            text-decoration: none;
            color: #007BFF;
            margin: 0 10px;
        }
        a:hover {
            color: #4CAF50;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <a href="http://www.linkedin.com/in/shashank-p-6966b0315">About Me</a>
        <a href="#section1">Educational Qualification</a>
        <a href="#section2">Section 2</a>
        <a href="#section3">Section 3</a>
    </nav>
    <main>
        <h2 id="about">About Me</h2>
        <p>Hello! I'm Shashank P, passionate about the technology field.</p> 
        <details>
            <summary>
                <h2 id="section1">Educational Qualification</h2>
            </summary>
            <p>
                <ul>
                    <li>
                        <h5>Bachelor of Engineering in Computer Science and Engineering (2025 - Present)</h5>
                        Currently pursuing my 1st semester at East West Institute of Technology through CET quota.<br>
                        Gaining foundational knowledge in computer science principles and practical applications.
                    </li>
                </ul>
                <br>
                <ul>
                    <li>
                        <h5>Pre-University Course (PUC) - Science Stream (2022 - 2024)</h5>
                        Secured distinction in the Karnataka Pre-University Examination.<br>
                        Specialized in subjects like Physics, Chemistry, Mathematics.
                    </li>
                </ul>
                <br>
                <ul>
                    <li>
                        <h5>Secondary Education (2012 - 2022)</h5>
                        Achieved distinction in the Karnataka Secondary Education Examination (10th Standard).
                    </li>
                </ul>
                <ul>
                    <li>
                        <h5>Skills and Certifications</h5>
                        Proficient in Python, HTML, and Web Development.<br>
                        Successfully completed relevant courses and hands-on projects in web technologies.
                    </li>
                </ul>
            </p>
        </details>
        <details>
            <summary>
                <h2 id="section2">Python Basic PDF</h2>
            </summary>
            <p>
                <a href="https://docs.google.com/document/d/1eTNzsIDHbGF_3FBRk7L6-RM3HeFyWyeL3Rbp8IcaJzM/edit?usp=drivesdk" target="_blank" download>Click here to download the PDF</a><br>
                <iframe src="https://docs.google.com/document/d/1eTNzsIDHbGF_3FBRk7L6-RM3HeFyWyeL3Rbp8IcaJzM/edit?usp=drivesdk" width="400px" height="600px">
                    Your browser does not support iframes. Please
                    <a href="https://docs.google.com/document/d/1eTNzsIDHbGF_3FBRk7L6-RM3HeFyWyeL3Rbp8IcaJzM/edit?usp=drivesdk">download the PDF here</a>
                </iframe>
            </p>
        </details>
        <details>
            <summary>
                <h2 id="section3">Python Simple Project</h2>
            </summary>
            <p>
                <a href="https://docs.google.com/document/d/1KTYYMn3Lgany40ugcwd_jSzFmMoxCvTeXFx10FdCxW0/edit?usp=drivesdk" target="_blank" download>Click here to download the PDF</a><br>
                <iframe src="https://docs.google.com/document/d/1KTYYMn3Lgany40ugcwd_jSzFmMoxCvTeXFx10FdCxW0/edit?usp=drivesdk" width="400px" height="600px">
                    Your browser does not support iframes. Please
                    <a href="https://docs.google.com/document/d/1KTYYMn3Lgany40ugcwd_jSzFmMoxCvTeXFx10FdCxW0/edit?usp=drivesdk">download the PDF here</a>
                </iframe>
            </p>
        </details>
        <br>
        <p>Explore my profiles below:</p>
        <div>
            <a href="https://www.linkedin.com/in/shashank-p-6966b0315?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAFAD1tIBWeJ5El079otY4ykuY0YsitNCQ3c&lipi=urn%3Ali%3Apage%3Ad_flagship3_search_srp_all%3BypVV2GC8T7Sg2nboNafnLQ%3D%3D" target="_blank" onclick="return showAlert();">LinkedIn</a> |
            <a href="https://www.instagram.com/imaginative_imprint" target="_blank" onclick="return showAlert1();">Instagram</a> |
            <a href="https://github.com/imaginativeimprint" target="_blank" onclick="return showAlert2();">GitHub</a>
        </div>
    </main>
    <footer>
        <p>&copy; 2025 My Website. All rights reserved.</p>
    </footer>
    <script>
        function showAlert() {
            alert("Opening LinkedIn Profile");
            return true; // Allow navigation to proceed
        }

        function showAlert1() {
            alert("Opening Instagram Profile");
            return true; // Allow navigation to proceed
        }

        function showAlert2() {
            alert("Opening GitHub Profile");
            return true; // Allow navigation to proceed
        }
    </script>
</body>
</html>
