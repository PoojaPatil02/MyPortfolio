https://www.figma.com/proto/QZPCc52b4Hn4JTYbd0WDwE/Untitled?node-id=379-1259&t=rMGrIiyg1ouEiUMy-1
https://www.figma.com/proto/QZPCc52b4Hn4JTYbd0WDwE/Untitled?node-id=374-422&t=rMGrIiyg1ouEiUMy-1

<!DOCTYPE html>
<html>

<head>
    <title>PDF in HTML</title>
</head>
<style>
    .pdf {
        width: 100%;
        aspect-ratio: 4 / 3;
    }

    .pdf,
    html,
    body {
        height: 100%;
        margin: 0;
        padding: 0;
    }
   h1,
    h3 {
        text-align: center;
    }

    h1 {
        color: green;
    }
</style>

<body>
        <h1>GeeksforGeeks</h1>
        <h3>Embedding the PDF file Using embed Tag</h3>
        <embed class="pdf" 
               src=
"https://media.geeksforgeeks.org/wp-content/cdn-uploads/20210101201653/PDF.pdf"
            width="800" height="500">
</body>

</html>
